---
title: "Engineering Oversee Responsibilties"
category: "R&R"
date: "2020-04-12"
tags: ['engineering', 'oversee', 'code-review']
description: Oversee checklist
---

## Project requirements

- [ ] Aware about the project objective
The end result of the project should be known at the start of the project

- [ ] Identify all the smaller products expected in the project and how they will be used
Identify smaller sub sections which can be created and reused in the project whether its some HTML elements like carousel, dropdown or a code snippet which can reused

- [ ] Designs clarity
Have clarity about the designs to be made as well as if zeplin needed is present or not

- [ ] Credentials (GTM / Sendgrid etc.) dependent on client
If supposedly we are planning to use client's creds for any such tools, then availability for the same.

- [ ] Environment support
Clarity on desktop configs / mobile / ipad / browser support. Atleast for new projects. For older ones may be getting an idea in advance will help

- [ ] Document some 'might' occur risks
The risks which the oversee foresees can be documented and shared with the PM as well as us(AB / SM / PP) for visibility.

- [ ] GTM / GA clarity
Clarity if GTM is needed on the project. If yes then is there any existing way to implement the same. Reference document for Economist project.

- [ ] Document assumptions if any
If team is going ahead with development,based on some assumptions,it needs to be documented so we all are on same page as in what is the thought process and also what is pending to clarity from client. Make sure to share the document with PM and project group id

- [ ] Document project requirement
Documentation is for reference which will help us to guage what exactly oversee understood in terms of project requirements

## Technical reference document

- [ ] Project architecture added
Documenting the project architecture to make sure it serves as a reference for future requests

- [ ] Analytics details to be added
If any changes done to analytics approach, other than the standard defined. Needs to be documented.

- [ ] Plugin details
Any third party plugins / libraries / services as well used needs to be documented with their version in it.

- [ ] Technical tweaks if any
If some tweaks has been done to meet technical requirements then it has to be documented.

- [ ] Document page speed records for production
Page speed records has to be maintained with screenshots for reference. This has to be on production environment

## Project timeline clarity

- [ ] Project phases timeline and estimate
Oversee should have clarity on what estimate is being provided and what is the timeline of the project. What has to be delivered on what date etc.

- [ ] Staging date for every phase
Should have clarity on staging release as well

- [ ] Client review date for every phase
The client review date for every phase should be known

- [ ] Go-live date for every phase
As the text suggest, go-live date for every phase should be known

## Define project architecture

- [ ] Identify distinct modules to be created
Identify sub modules which can be created and planned to go forward. Basically bifurcating the task

- [ ] Identify reusable modules
Reusable smaller modules need to be identified and created

- [ ] Define how the data will flow within different modules
We need plan what data is needed by every module and how are we planning to store that data and communicate between different modules

- [ ] Add .env file for sensitive details
As the text suggests, sensitive information should never be openly available and be part of .env

- [ ] DB architechture to be defined
Plan and define DB architecture first before going to actual implementation

## Development approach

- [ ] Decide the flow, the sequence of modules to be developed
Thought different modules have been defined, depending on the release oversee need to plan which module should be developed first or may b order of developing modules

- [ ] Share 'Code Review Document' link with team members and explain the same
A document is in progress which needs to be referred while wirting code as well as reviewing the PR

- [ ] Share 'Google Analytics' document with team for reference and explain the same
Please refer the document for more details on how GTM has to be implemented and share same with the team to make sure implementation is as per the standards

## Defining and Setup Git architechture
Refer 'Git Branching' document for further reference and explain the same

## Creating/Assigning sub-tasks 

- [ ] Create any sub task within specific modules
Within modules that have been created some more sub tasks can be defined depending on project requirements

- [ ] Assign task to different team members
Assigning those sub tasks within the team

## Define PR Guidelines
- [ ] PR Frequency Definition
Depending on team's performance / previous experience PR frequency should be defined. Eg once / twice a day.

- [ ] Merge code by oversee only
The code merge will be done only by oversee and no other team member

- [ ] All PR and the comments are tracked on Github
It is always good to have communication with your team but by ensuring that all the PR comments are tracked on Github would mean nothing gets missed.

## Define update frequency
 - [ ] Decide time for developer to provide update on slack
Decide at the start of the project, regarding how and when and at what time you need update of slack

 - [ ] Everyday time slots for meet
 Since oversee is also a developer on some other project. Define time in the day for meet, eg. evening 5pm everyday. This does not apply at time of release / urgent request.

## Inform delay at the right time
- [ ] Identify any slippages
Keep an eye to identify slippages if any

- [ ] Highlight to PM
If slippages / delays are identified please highlight it to PM

- [ ] Highlight to Poonam for technical concerns / team concerns
If team is stuck for a long time or facing a technical concerns, please don't be stuck on the issue for a logn time and highlight to your seniors and leads.

- [ ] Escalate to management if a milestone delivery is not happening because of internal factors
Escalate at the right time to management to highlight if a crucial milestone delivery is missed.

- [ ] Page Speed
Refer to [Performance](/checklist/performance) checklist.

- [ ] Analytics
Refer to [Analytics](/checklist/analytics) checklist.

- [ ] Security
Refer to [Security](/checklist/security) checklist.

- [ ] Peer feedback and coaching
Provide developer feedback about their performance, what they are doing well at (positive reaffirmation goes a long way) as well as giving them coaching/guidance on aspects that they need to work on. Always best to have this submitted in the feedback form to ensure it is not lost.