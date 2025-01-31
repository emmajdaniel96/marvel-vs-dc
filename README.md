# Marvel Quiz Game 

## Table Of Contents:
* [Introduction](#Introduction)
    - [Requirements](#Requirements)
* [UX](#UX)
    - [Target User Demographic](#Target-User-Demographic)
* [Development Plan](#Development-Plan)
    - [Strategy](#Strategy)
* [Design](#Design)
    - [Structure](#Structure)
    - [Template](#Template)
    - [Colour Palette](#Colour-Palette)
* [Features](#Features)
    - [Future Features](#future-features)
* [Issues & Bugs](#issues-and-bugs)
    - [Unsolved Issues/Bugs](#unsolved-issues-bugs)
    - [Device Testing](#device-testing)
* [Deployment](#deployment)
* [Technologies Used](#technologies-used)
* [Credits & Acknowledgements](#credits-and-acknowledgements)

## Introduction:
This quiz has been designed and created to challenge the knowledge of Marvel fans, when it comes to both the MCU (Marvel Cinematic Universe) and comic books, whether they are a hardcore fan or even if they are just casual fans that want to test how muhc they really now.

The inspiration behind the quiz created, is from my love of Marvel; both the MCU and the comic books.

This document will include the development and testing processes taken in order to design and build this quiz along side the whole planning processes that have been taken.

This quiz is my second milestone project that is required for the completion of the full stack development course.

### Requirements:

For this project, the aim is to utilies the fundamentals of JavaScript along with elements of HTML and CSS in order to create an interactive quiz/ game that involves a selection of questions about both the MCU and Marvel comic book trivia to test how well the user/ player know this topic.


## UX:

## Target User Demographic:
The target demographic for this quiz are as follows:

![Marvel Logo](assets/images/marvel-logo.jpg)

* Marvel Comic Fans
* Comic Book Fans 
* Marvel Cinematic Universe Fans



### Goals for above target user demographic:
- To challenge their knowledge of quiz topic 
- To have fun/ be entertained
- Possibly learn new facts about quiz topic
- Navigate quiz with ease
- Simple but efective layout 


## Development Plan:

### Strategy:
Aim is to build a quiz using HTML, CSS, and JavaScript that is simple, fun and interactive. Incorporating all, if not, most of the target user demographic goals that are stated above will be part of what the developer needs to take into account whilst creating and designing the qiuz. Whilst forming the strategy, the identity of the quiz should resemble and take inspiration from the quiz topic.

The quiz needs to provide the following:
- Light-hearted fun
- Entertainment
- Simple navigation


## Design:

### Structure:
The format/ structure to the quiz should follow the simple sturcture of a multiple choice quiz. The user/ player will answer a question that is shown by choosing from a selction of answers, one of which will be the correct answer. For every correct answer, a score out of 10 will be shown, therefore showing the user their progress through the quiz.

### Template:
For the template, Wireframes have been created to map out how the quiz/ game should look overall in its basic form. In order to keep the user engaged the overall look and interactivity of the quiz is kept in mind through the design process.

![Quiz Template](assets/images/quiz-template.jpg)
![Multiple Choice Template](assets/images/multiple-choice-template.jpg)

### Colour Palette:
For the colour palette, the inspiraion has mainly been taken from the Marvel logo itself with the bright solid red mainly along with the white that is also in the main logo. For the answer boxes, the decision made to use a lighter red was due to wanting the answers written to be clear for the user to read and les distracting to the eye.

![Colour Palette](assets/images/collage.jpg)

### Typography:
The main font used throughout the quiz is Saira (Extra/ Semi Condensed), but also there is the back up of Sans-Serif, just in case any issues occcured with the primary font uploading. The font chosen was 


## Features:

* Header - Quiz title that appears at the top of the page throughout the quiz (From start page, through the quiz, and at the end of the quiz)

* Hero Image - main feature of the start page, used as a background through the quiz, main featuure on score page

* Quiz Area - the focal point of the page and the most interactive part of the quiz 

### Future Features:

- Score tracker
- Progress bar/ symbol

## Issues and Bugs:

(Minimal errors occured with html and css files)

### Start Page:

- index.html file - link to JavaScript file was incorrectly placed, was out of body element. 
- issue with link to font awesome in the head element of html file
    - [Font Awesome Link Error](assets/testing/start-page-error.jpg)
    - [JavaScript Link Error](assets/testing/js-link-error.jpg)

### Quiz Page:

- stray div tag from not correctly removing full div tag from the file


### End of Quiz Page:

- stray anchor tag 
    - [Stray Anchor Error](assets/testing/stray-anchor.jpg)

### CSS Styling Sheet:

- property used with an invalid value caused error through checks, once removed, no errors were identified
    - [CSS Error Free](assets/testing/css-styling-sheet.jpg)

### JavaScript File:

- missed several semi colons throughout the file 
- square bracket notation, a suggestion for dot notation was given instead.

After validating all file pages, no syntax errors have occured during final testing stage.

 - [Semi Colon Errors](assets/testing/semi-colon-errors1.jpg)
 - [More Semi Colon Errors](assets/testing/semi-colon-errors2.jpg)
 - [Dot Notation Susgestion](assets/testing/dot-notation.jpg)

## Unsolved Issues/ Bugs

### Quiz Page:
- problems getting the score tracker to update along with the questions answered (Removed from final product, further testing on this code will continue to make this a future feature)

- colours reacting to correct answers (eg. correct answer turning green once clicked)

A lot of the errors and lack of complex JavaScript code in general is definitely due to the lack of knowledge I have within this field. As I continue to learn and practice the lanuage of JavaScript, I hope this can only make me more confident to push the code further than it has currently been showcased.


## Device Testing:
- In order to make this quiz responsive, google chrome developer tools has been used to test the responsiveness on different devices. These are the following devices that have been tested:

- iPad Air
- iPad Mini
- Nest Hub
- iPhone XR
- iPhone 12 Pro
- Pixel 5
- Samsung Galaxy S20 Ultra

## Deployment

### Deployment to GitHub Pages:
- In GitGub repository, navigate to 'Settings' on the top horizontal bar
- From the 'Settings' page, find the 'GitHub Pages' section
- Locate 'Source', then select None tab and change it to Master then click 'Save'.
- When the page has loaded, scroll down to 'GitHub Pages' section again, and a maessage about site publication should come up. (This can take time to initially load.).

### Forking GitHub Repository:
There is also the possibility of forking the repository. This is where you are able to make a copy of the repository and make changes to it without effecting the original repository. This can be done in a few simple steps.
- Find the repository you wish to use
- Underneath the account icon on the top-right hand of the screen, the button labelled 'fork' can be found.
- Click on this in order to make a copy of the repository

### Make Local Clone:
- In the GitHub Repository, next to the Gitpod button, click on code.
- Copy the code that is displayed
- In Github, change the location to where you would like the directory to be located to.
- Type 'git clone' and pasted the link that was previously copied
- Once you press enter, a local clone has now been created 


## Technologies Used:

### Languages Used
- HTML
- CSS
- JavaScript

### Programs Used:
- [GitPod](https://www.gitpod.io/) - used to write the code, commit and then push to GitHub
- [GitHub](https://github.com/) - used to store the code/ project after being pushed from GitPod
- [Balsamiq](https://balsamiq.com/wireframes/) - used to create Wireframes throughout the design process 
- [Google Fonts](https://fonts.google.com/) - used throughout the site for the font which has been imported into the style.css file
- [Extends Class](https://extendsclass.com/javascript-fiddle.html) - used to identify errors in JavaScript code
- [JavaScript Beautifier](https://beautifier.io/) - to clean up aesthetic of JavaScript code
- [Coolors](https://coolors.co/) - used to build the colour palette used from hero image
- [RapidTables](https://www.rapidtables.com/web/color/RGB_Color.html) - used to generate rgb colour codes

## Credits & Acknowledgements:

- [W3Schools](https://www.w3schools.com/js/default.asp)
- [Brian Design](https://www.youtube.com/watch?v=f4fB9Xg2JEY)
- [James Q Quick](https://www.youtube.com/watch?v=zZdQGs62cR8&list=PLDlWc9AfQBfZIkdVaOQXi1tizJeNJipEx&index=6)

I would like to thank my mentor throughout this project as well as through the course this far. With this being my second project, I have recognised that I have hit a lot more hurdles this time in comparison to the last project. In all honesty, I have struggled with this module a lot but will continue to practice in order to better myself. I'd like to think my friends and family for their amazing support and giudance. Very eager to build on this further and make a much better product.



