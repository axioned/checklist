---
title: Pre Go-Live Checklist
category: Project Execution
date: "2020-03-10"
tags: ['meta', 'open-graph', 'twitter', 'handoff', 'seo']
description: The meta tags need to be defined on all projects.
---

## Engineering

- [ ] If the project is already live and new changes have to be migrated. Always make sure to take a backup / restore points of the live site ready before moving ahead with anything.

- [ ] Check if DNS poinitng is done.

- [ ] Check the server maximum upload and import value. This will help in planning for migration

- [ ] Make sure server grants the necessary file permission to upload/create new folder and files.

- [ ] Make sure Google Analytics is added proeprly with proper UA code (or implemented through Google Tag Manager)

- [ ] Make sure marketing scripts are added with proper id/code.

- [ ] Uncheck the Discourage site indexing checkbox

- [ ] If on Wordpress (or similar CMS), verify the site URL and Home URL

- [ ] Check if there are any static link being added. Make sure there are not absolute URL's

- [ ] Check if correct permalinks are set

- [ ] Make sure there are no errors in console.

- [ ] Make sure site is on Secure version i.e https://

- [ ] Check if there are 404 errors on the site

- [ ] Make sure all media types upload is allowed via dashboard.

- [ ] Check if there are limit set for maximum file upload size. Ideally it should not be more than 2-5MB.

## Quality Assurance

- [ ] Make sure all high priority functionalities are working as expected.
- [ ] Make sure you have performed regression on whole staging site.
- [ ] Ensure all actual content is already uploaded on stage environment. if not, we have all communication re: why we are not uploading missing some content/assests.
- [ ] Check whether you have performed Site Health Check on stage. (Performance, SEO, Best Practice, Accessibility)
- [ ] Make sure all the test data/ test users has been removed (from front-end and back-end)for time bound projects
- [ ] Make sure all the dummy images has been replaced with actual images
- [ ] Make sure, Test cases are updated with latest requirements (depends on projects)
- [ ] Issue log sheet, Zoho or any other issue tracking system used for the project updated
Make sure all issues which have been resolved/verified are closed and appropriate proper comments are added for 'Not an issue'.
- [ ] Make sure to check social share functionality. Use [Social Share Preview](https://socialsharepreview.com/) or similar services.
- [ ] Make sure to check 404 has been built.
- [ ] Make sure that GA/GTM (and other analytics code) are mapped to their respective site.
- [ ] All events are being tracked/working as expected