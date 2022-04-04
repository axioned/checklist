---
title: Styling and CSS Code Review Checklist
category: Code Reviews
date: '2020-03-21'
tags: ['webfonts', 'css', 'styling']
description: Styling and CSS checklist based on https://frontendchecklist.io/
---

## Webfonts

- [ ] Webfont format  
      WOFF, WOFF2 and TTF are supported by all modern browsers.

- [ ] Webfont size  
      Webfont sizes don't exceed 100 KB (all variants included).

- [ ] Webfont loader  
      Control loading behavior with a webfont loader.

## CSS

- [ ] Responsive Web Design  
      The website is using responsive web design.

- [ ] CSS Print  
      A print stylesheet is provided and is correct on each page.

- [ ] Unique ID  
      If IDs are used, they are unique to a page.

- [ ] Reset CSS  
      A CSS reset (reset, normalize or reboot) is used and up to date.

- [ ] JS prefix  
      All classes (or id- used in JavaScript files) begin with js- and are not styled into the CSS files.

- [ ] Embedded or inline CSS  
      Avoid at all cost embeding CSS in <style> tags or using inline CSS

- [ ] Vendor prefixes  
      CSS vendor prefixes are used and are generated accordingly with your browser support compatibility.

- [ ] Concatenation  
      CSS files are concatenated in a single file (Not for HTTP/2).

- [ ] Minification  
      All CSS files are minified.

- [ ] Non-blocking  
      CSS files need to be non-blocking to prevent the DOM from taking time to load. See more [here](https://gist.github.com/thedaviddias/c24763b82b9991e53928e66a0bafc9bf?ref=frontendchecklist).

- [ ] Stylelint  
      All CSS or SCSS files are without any errors.

- [ ] Responsive web design  
      All pages were tested with the correct breakpoints.

- [ ] CSS Validator  
      The CSS was tested and pertinent errors were corrected.

- [ ] Desktop Browsers  
      All pages were tested on all current desktop browsers (Safari, Firefox, Chrome, Internet Explorer, EDGE...)

- [ ] Mobile Browsers  
      All pages were tested on all current mobile browsers (Native browser, Chrome, Safari...)

- [ ] OS  
      All pages were tested on all current OS (Windows, Android, iOS, Mac...)

- [ ] Reading direction  
      All pages need to be tested for LTR and RTL languages if they need to be supported.
