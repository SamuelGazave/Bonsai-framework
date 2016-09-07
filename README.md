# Bonzail-framework
A framework for e-mail design based on the fluid-hybrid method by Nicole Merlin

http://webdesign.tutsplus.com/tutorials/creating-a-future-proof-responsive-email-without-media-queries--cms-23919

I created a grid to help graphic designers adapt their work to the needs of reponsive e-mail creation and made the all thing work as a framework.

Coders can also use it to create various layouts in a small amount of time with the use of the grid and pre-built elements.

## How it works

HTML and CSS comes into separates files so HTML is lighter when you are creating the e-mail. The CSS contains all the class you need from the grid to the style element. This allows you to change the width of a column or the style of a button simply by changing the class applied to the HTML element.

For example, i have made diffrent class in my CSS to style my typographic elements that are .h1 .h2 .h3 .h4 etc...

if i want to change my heading from .h4 to .h1, i just have to change the class into the <td> like this :

`
<table>
  <tr>
    <td class="h4">
      Hello
    </td>
  </tr>
</table>
`
  
becomes
  
`
<table>
  <tr>
    <td class="h1">
      Hello
    </td>
  </tr>
</table>
`
  
this is the same method for every element in the framework from the columns to the styles
  
once all the css is set, use an inliner like https://inliner.cm/ to set the css inside the html and the mail is good to go.
  
## ATTENTION
  
a few things have to be known to have a good e-mail :
  
when changing a column, set the wright width into the outlooks conditionnal comments and into the image inside it (if you put one into it) taking account of the padding you set in the td containing the image (in a 300px width column with a .inner10 class applied to the td inside it, the image inside the td would be 280px wide)

there is more information in the commentaries inside the HTML and the CSS files on how to use the grid and how to use the inliner to get the e-mail done
