# Code Refactoring for Horiseon

 [![Image of Horiseon Logo](assets/images/ReadMe_Logo.png "Open Horiseon's deployed website")](https://gveetil.github.io/Code-Refactor-Homework-Week-1)

## Context
This Project was created as part of the [Coding Bootcamp](https://bootcamps.monash.edu/ "Open Coding Bootcamp website") course conducted by Monash University. 

##  Description
Horiseon is a marketing agency who want their code base refactored to follow accessibility standards. They also want to optimize their website for search engines. This project is about refactoring their code base to meet these requirements.

Refactoring code can be quite tricky since you don't want to change functionality or design, but you do learn so much about how to code, and more importantly, how *not* to code, in the process. This is what makes this project both exciting and challenging at the same time. 

## Solution
![Image of Horiseon Main Page](assets/images/ReadMe_HoriseonWebsite.jpg "Horiseon Main Page")

The list of changes made to Horiseon's code base and the problems they aim to solve are as detailed below:

### Accessibility Standards and Search Engine Optimizations

#### * Added alt attributes for all image elements. 
Alt text improves accessibility for screen readers and users with slow connections. It also enables the image to show up in image searches.

#### * Restructured the source code to use semantic HTML elements like Header, Section, Article, Nav and Footer. 
Semantic HTML gives context to page elements thus making them more accessible to screen readers. It also helps search engines to better understand and index page content.

#### * Updated headers to be sequential by removing incorrect header usage. 
Headers are important as users rely on them to skim through page content, and search engines use headers to index and structure web content. 

#### * Updated the title of the web page to be concise and descriptive.
A better title makes it easier for search engines to find the page.

#### * Added Meta tags - keywords and description.
The keywords and description help increase the visibility of the page in search engines.

#### * Updated the source code to use logical HTML elements like strong
Logical tags like strong are recognised by aural browsers, text-only browsers, Braille displays etc. and so it makes the page more accessible. 

### Bug Fixes
* The "Search Engine Optimization" link was not working. This has now been fixed.

### CSS Optimizations
* The css classes "search-engine-optimization", "online-reputation-management" and "social-media-marketing" all have the exact same style definition. I've merged them into the parent class to reduce redundancy and thus optimize usage of the style.

* The css classes "benefit-lead", "benefit-brand" and "benefit-cost" again have the exact same style definition. So these have also been merged into one optimized class.
