# Portfolio-HW2
Creating a Professional Portfolio

## The Task

Build a portfolio page, which can be added to as the course progresses. 

A portfolio of work can showcase your skills and talents to employers looking to fill a part-time or full-time position. An effective portfolio highlights your strongest work as well as the thought processes behind it. Students who have portfolios with deployed web applications (meaning they are live on the web) are typically very successful in their career search after the boot camp. This last point can’t be stressed enough: having several deployed projects is a minimum requirement to receive an initial interview at many companies. 

With these points in mind, in this homework you’ll set yourself up for future success by applying the core skills you've recently learned: flexbox, media queries, and CSS variables. You'll get to practice your new skills while creating something that you will use during your job search. It’s a win-win that you'll likely be grateful for in the future!

## Acceptance Criteria

Here are the critical requirements necessary to develop a portfolio that satisfies a typical hiring manager’s needs:

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

The following animation shows the web application's appearance and functionality:

![portfolio demo](./Assets/02-advanced-css-homework-demo.gif)

## HTML Structuring

When creating the HTML structure for my portfolio, I broke it down into indivdual & separate parts. The header contains my name, and then the navigation links that take the user to the respective sections on the page. The fourth link is an external link that when clicked, pulls up a PDF file of my resume. 

After the header, is a simple div element to simply insert a header image below the header, with a subtitle that says "Welcome to my Portfolio" overlayed on top of the background image. A div was used here because this portion has no real meaning or significance, rather it is there to make the page look a little nicer.

We then move into the "main" section of the page indicated by the main element. This is the parent element that contains the two main sections on the portfolio: the About Me section and the Work section. The About Me section is signified by the element of "article" since this section of the "main" contains paragraph style information about me. The div element is used to allow the children of this div element to be grouped under one class of "article-container" (which will be explained in more detail in the CSS Structuring section in this README). Within the div is the image of me, and the p element containing the actual information about me. 

After the article element, the section element is used to contain the work portion of the page. Here, within the section parent element, we have the header for the section ("Work") and then div's for each of the three projects. Each project div contains the reference source, which then contains the title for the project in the h element, the subtitle for the project in the p element, and the image to be used for the display of each project. 

After this section, the main portion of the page is ended and we move into the footer which contains the "Contact Me" information. The footer parent element simply contains the h element, and then the unordered list containing each of the different ways to contact/connect with me. 

## CSS Structuring



## Credits



## Links
