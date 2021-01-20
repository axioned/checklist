---
title: "HTML Code Review Checklist"
category: "Code Reviews"
date: "2020-04-12"
tags: ['html', 'meta', 'code-review']
description: HTML checklist based on https://frontendchecklist.io/
---

## Head

- [ ] Doctype   
The Doctype is HTML5 and is at the top of all your HTML pages.

- [ ] Charset   
The charset declared (UTF-8) is declared correctly.

- [ ] Viewport  
The viewport is declared correctly.

- [ ] Title   
A title is used on all pages

- [ ] Description   
A meta description is provided, it is unique and doesn't possess more than 150 characters.

- [ ] Favicons    
Each favicon has been created and displays correctly.

- [ ] Apple Web App Meta    
Apple meta-tags are present.

- [ ] Windows Tiles   
Windows tiles are present and linked.

- [ ] Canonical   
Use rel="canonical" to avoid duplicate content.

- [ ] Language attribute    
The < code>lang</ code > attribute of your website is specified and related to the language of the current page.

- [ ] Direction attribute   
The direction of lecture is specified on the html tag (It can be used on another HTML tag).

- [ ] Alternate language    
The language tag of your website is specified and related to the language of the current page.

- [ ] Conditional comments    
Conditional comments are present for IE if needed.

- [ ] RSS feed    
If your project is a blog or has articles, an RSS link was provided.

- [ ] Inline critical CSS   
The inline critical CSS is correctly injected in the HEAD.

- [ ] CSS order   
All CSS files are loaded before any JavaScript files in the HEAD

- [ ] Facebook Open Graph  
You can look at [this](/setting-up-meta-tags) checklist for further information

- [ ] Twitter Card  
You can look at [this](/checklist/setting-up-meta-tags) checklist for further information

## HTML

- [ ] HTML5 Semantic Elements   
HTML5 Semantic Elements are used appropriately (header, section, footer, main...).

- [ ] Error pages   
Error 404 page and 5xx exist

- [ ] Noopener   
In case you are using external links with target="_blank", your link should have a rel="noopener" attribute to prevent tab nabbing. If you need to support older versions of Firefox, use rel="noopener noreferrer"

- [ ] Clean up comments   
Unnecessary code needs to be removed before sending the page to production.

- [ ] W3C compliant   
All pages need to be tested with the W3C validator to identify possible issues in the HTML code.

- [ ] HTML Lint   
I use tools to help me analyze any issues I could have on my HTML code.

- [ ] Link checker   
There are no broken links in my page, verify that you don't have any 404 error.

- [ ] Adblockers test   
Your website shows your content correctly with adblockers enabled

## Images

- [ ] Optimization   
All images are optimized to be rendered in the browser. WebP format could be used for critical pages (like Homepage)

- [ ] Picture/Srcset   
You use picture/srcset to provide the most appropriate image for the current viewport of the user.

- [ ] Retina   
You provide layout images 2x or 3x, support retina display.

- [ ] Sprite   
Small images are in a sprite file (in the case of icons, they can be in an SVG sprite image).

- [ ] Width and Height   
Set width and height attributes on <img> if the final rendered image size is known (can be omitted for CSS sizing).

- [ ] Alternative text   
All <img> have an alternative text which describe the image visually.

- [ ] Lazy loading   
Images are lazyloaded (A noscript fallback is always provided).