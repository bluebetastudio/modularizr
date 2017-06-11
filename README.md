# modularizr
CSS and JS as you go.

# Motivation
When a developer is building a site, dozens of frameworks including fonts, CSS, Javascript etc. Most of those libraries includes dozens of useful resources, like Bootstrap, Foundation, jQuery etc, but most of them features lots of code that no one would use. In example, when you load a CSS library with +20KB filesize, but the only resources you use could be resizes to 3KB. Grid system, image galleries, carousels, form layouts, simple Javascript code, easy templates etc.
Other goals include:
- Mobile Web App Frameworks: One of the ideas to WAFs is to allow offline resources. When you can't load content from a CDN, you need to implement local files, and a < 20KB folder with all needed CSS and JS allows the site to load faster.
- Less classessome frameworks needs to include two or more classes insive lots of DIVs. You should be able to include only one class to implement all the changes. Less HTML code, faster loading site.
- Forceful HTML5 acceptance: All HTML5 sites should be created using HTML5 tags, as NAV, HEADER, ARTICLE etc. I follow a simple rule: we are in 2017, if Google site doesn't accept IE9- browser, why should we?

# Goal
The goal of Modularizr is to include commonly-used developer resources in modules. If you just need a simple way to create a 12-grid system, just include that module. If you want beautiful form buttons, include that too. In the end, you should be able to get max. two files (one CSS and one JS) to be implemented into your site. All Javascript will be compatible to <a href="http://zeptojs.com/">Zepto.js</a> because its gzipped files is <10KB and it does works in modules, too. 
The idea is still in development, but soon everyone will be able to include their own codes to be avaliable. Example: if someone made a Carousel structure which CSS and JS combined filesizes are <10KB, they can upload it.
