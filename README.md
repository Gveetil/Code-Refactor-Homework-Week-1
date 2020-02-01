# Code Refactoring for Horiseon

## Context
This Project was created as part of the Coding Bootcamp course conducted by Monash University. "https://bootcamps.monash.edu/"

##  Description
Horiseon is a marketing agency who want their code base refactored to follow accessibility standards. They also want to optimize their website for search engines. This project is about refactoring their code base to meet these requirements.

Refactoring code can be quite tricky since you don't want to change functionality or design, but you do learn so much about how to code, and more importantly, how *not* to code, in the process. This is what makes this project both exciting and challenging at the same time. 

## Solution
Below is a list of changes made to Horiseon's code base and the problems they aim to solve:

### Apply Accessibility Standards
* Added accessible alt attributes for all image elements. This also enables the image to show up in image search as well.

### Search Engine Optimizations
* Updated the title of the web page to be concise and descriptive - this makes it easier for search engines to find the page.
* Updated headers to fall in sequential order - search engines use headers to index and structure web content. 
* Added Meta tags - keywords and description to increase page visibility in search engines.

### Bug Fixes
* The "Search Engine Optimization" link was not working. This has now been fixed.

### Code refactoring
* Restructured the source code to use semantic HTML elements like Header, Section, Article, Nav and Footer
* 

### CSS Optimizations
* The css classes "search-engine-optimization", "online-reputation-management" and "social-media-marketing" all have the exact same style definition. I've merged them into the parent class to reduce redundancy and thus optimize usage of the style.

* The css classes "benefit-lead", "benefit-brand" and "benefit-cost" again have the exact same style definition. So these have also been merged into one optimized class.

