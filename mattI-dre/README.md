![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 04: HTML Templating w/HandlebarsJS
===

## Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[Handlebars Docs](http://handlebarsjs.com/)

[Arrow Functions MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

## Configuration
_Your repository must include:_

```
04-templating
├── .eslintrc.json
├── .gitignore
├── LICENSE
├── README.md
├── index.html
├── scripts
│   ├── article.js
│   ├── articleView.js
│   └── blogArticles.js
├── styles
│   ├── base.css
│   ├── fonts
│   │   ├── icomoon.eot
│   │   ├── icomoon.svg
│   │   ├── icomoon.ttf
│   │   └── icomoon.woff
│   ├── icons.css
│   ├── layout.css
│   └── modules.css
└── vendor
    └── styles
        └── normalize.css
```

## User Stories and Feature Tasks

- Continue styling the app using SMACSS practices. Take a few minutes for code review of your partner's CSS and decide how to incorporate it into your paired lab. You can choose one partner's CSS structure, or you can combine them as you see fit. Seek to optimize and organize your CSS as much as possible!

*As a user, I want my app to render articles with consistent formatting so that I can visit the site often and have the same experience each time.*

- Include the Handlebars.js CDN in your project to replace the `$.clone()` template.

*As a developer, I want to utilize the Handlebars library to dynamically render the articles using a template so that I can easily edit the way articles are rendered.*

- Convert your existing HTML template into a Handlebars template.
- Update the `Article.prototype.toHtml()` method to utilize the Handlebars template.

*As a developer, I want to utilize modern JavaScript features so that my code is up to date with industry standards.*

- Refactor the functions and methods in articleView.js to use ES6 arrow functions.

### Stretch Goal
*As a developer, I want to use Handlebars to build my filters so that my code is more DRY.*

- Look at all that duplicated markup inside your `#filter` list items! Looks like a good opportunity to use a template. Make a small template for each filter, and re-render the list once you have data to populate it.

## Documentation
_Your README.md must include:_

```md
# 04-Templating

**Author**: Matt Iwicki and Dre Ibarra
**Version**: 1.0.3

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 301 class. (i.e. What's your problem domain?) -->
Overall, we want to build a blog website that filters entries based on user preference as well as allows for new entries from the users themselves.  Today, we reformatted the code to maintain its sorting functionality while including arrow functions and mustache methods.  

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
To build this app up to this point, one must include a set of raw data, build a constructor function for the raw data with each article as an instance of that constructor, append those instances to the page, sort the instances by author name and category based on user input of click events within a drop-down menu selector, have a shift tab functionality that hides and shows appropriate tabs of the page based on click events, and have the page be responsive to the user's interface.  

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->
Using HTML for templates, CSS for styling, jQuery and handlebars for additional functionality, and JavaScript for overall functionality in response to user input.  

## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples:

10-27-2017 10:18am - Initialized the app with style sheets and starter code, added mustache functionality
10-27-2017 11:18am - Fixed read on functionality with handlebars
10-27-2017 12:00am - Refactoring functions to arrow format
## Credits and Collaborations
Jeff K, Seth, Rob, and Frank all helped when we were stuck, plus JB was always looking over to make sure we were going smoothly.  
-->
```
