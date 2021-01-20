---
title: Web Accessibility
category: Front-End
date: "2020-03-20"
tags: ['accessibility', 'html']
description: The checklist for front-end developers to make sure their website is accessible for everyone!
---

- [ ] Make sure you use rem or em units whenever it is possible

- [ ] Make sure you	use helpful and clear page titles

- [ ] Make sure your html has lang attribute assigned

- [ ] Progressive enhancement   
Major functionality like main navigation and search should work without JavaScript enabled.

- [ ] Color contrast   
Color contrast should at least pass WCAG AA (AAA for mobile).

- [ ] H1   
All pages have an H1 which is not the title of the website.

- [ ] Headings   
Headings should be used properly and in the right order (H1 to H6).

- [ ] Specific HTML5 input types are used   
This is especially important for mobile devices that show customized keypads and widgets for different types.

- [ ] Make sure all images have appropriate alt tags   

- [ ] Label   
A label is associated with each input form element. In case a label can't be displayed, use aria-label instead.

- [ ] Keyboard navigation   
Test your website using only your keyboard in a previsible (logical) order. All interactive elements are reachable and usable.

- [ ] Focus style   
If the focus is disabled, it is replaced by visible state in CSS.


### Additional items to potentially consider depending on the project requirements

- [ ] Accessibility standards testing   
Use the WAVE tool to test if your page respects the accessibility standards.

- [ ] Screen reader   
All pages were tested in two or more screen readers (such as JAWS, VoiceOver, and NVDA).