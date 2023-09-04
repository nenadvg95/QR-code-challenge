# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Acknowledgments](#acknowledgments)

## Overview
This is a Qr code component challenge that i built as a first project from Frontend mentor. It is a QR component card that should be responsive on smaller screen sizes.
### Screenshot
./Screenshot 2023-09-03 182848.png

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: http://127.0.0.1:3006/qr-code-component-main/index.html

## My process
I first used included README file with resources like colors, fonts, and other information that i could find to initiate them as variables in my css file. 
That i wrote my content html and tried to figure out how to structure it so i get the card like the goal provided image and so i can most easily style it. After that i tried to observe and decide on wether to use flexbod or grid, opted for the first mentioned and than used styling to try and achieve according to my observation the closest looking solution to the challenge.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Big screen-first workflow

### What I learned

I learned how effective can structuring variables before beggining of project be and how makes styling more easier by reusing them.
I learned as well that adding min-width of the container in media-query can affect all other components inside container and thus make it easier to 
nake it responsive.

'''
:root{
    --white:hsl(0, 0%, 100%);
    --Light-gray: hsl(212, 45%, 89%);
    --Grayish-blue: hsl(220, 15%, 55%);
    --Dark-blue: hsl(218, 44%, 22%);
    --ff-primary: "Outfit",sans-serif;
    --spacer:1.125rem;
}
'''
### Useful resources
 Modern CSS reset : https://gist.github.com/Asjas/4b0736108d56197fce0ec9068145b421
 Useful variable video :  https://www.youtube.com/watch?v=PHO6TBq_auI&list=PL4-IK0AVhVjOT2KBB5TSbD77OmfHvtqUi

## Acknowledgments

I would like to reference here Kevin Powells YouTube channel and web-page . Great guy and great expalining and examples of all different aspects of web development.

