---
title: 'Code Review Process'
category: 'Code Reviews'
date: '2020-04-12'
tags: ['html', 'daily', 'code-review']
description: When reviewing a project code written by your team member and a peer review is expected, do these checks, get the fixes done and only then promote or accept the code. This checklist is useful for the 'first pass' after a 'code drop'.
---

Inspired by [Mozilla's Code Review Process](https://wiki.mozilla.org/Webdev:Flux:Code_Review_Process)

- [ ] README.md exists and has everything you need to get the app up and running

- [ ] The project starts in development mode

- [ ] Spend a few minutes using the app

- [ ] Can you understand the purpose of the application?

- [ ] Page Speed Scores
      Check on [PageSpeed Insights](https://pagespeed.web.dev/)

- [ ] w3C Validator and/or any other Linter (SonarLint, ESLint, etc)
      Check on [The W3C Markup Validation Service](https://validator.w3.org/)

- [ ] Console - any 404 or 500 errors?

- [ ] Review package.json - anything stand out?

- [ ] Security - any obvious issues?

- [ ] JavaScript - does the code passes all the linting checks?

- [ ] CSS - good style?
