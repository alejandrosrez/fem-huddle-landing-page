# Frontend Mentor - Huddle landing page with alternating feature blocks solution

This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


### What I learned

I was able to apply some feedback from my last challenge. For example, [Raymart Pamplona](https://www.frontendmentor.io/profile/pikapikamart) suggested me to apply some base styling to make it easier to work with sizes on my projects: 
```css
html {
    box-sizing: border-box;
    font-size: 100%;
  }
  
  body {
   margin: 0;
  }
  
  *,
  *::before,
  *::after {
    box-sizing: inherit
  }
```
By applying the box-sizing property (and a "border-box" value), now the size of a box takes into account the border of it. For example, if I want a box to be a 100px wide and it has a 5px border, by using this property the box would be 90px (5px border on each side) as the sizes that I set would include the borders. 

In addition, needed to apply some layers on top of buttons and use oppacity to show them only on hover. It is something that I first practiced on a previous challenge.

On top of that, I focused on structuring my code in a way that makes it easier for others to understand (and for my future self).

### Continued development

For future projects I would like to continue improving my skills on: 
- Working with images and vectors in CSS, making them responsive and resizing them. 
- CSS Grid

### Useful resources

- [CSS Box Shadow](https://www.w3schools.com/css/css3_shadows_box.asp) - This W3Schools guide helped me to review CSS box shadows. 
- [Z-index](https://developer.mozilla.org/es/docs/Web/CSS/z-index) - This MDN resources helped me to build my overlay layer for buttons.


