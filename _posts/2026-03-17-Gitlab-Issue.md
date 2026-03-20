---
title: "GitLab Issue"
excerpt_separator: "<!--more-->"
date: 2026-03-17
categories:
  - Sprint 13
tags:
  - email
  - issue
show_date: true
---

When developing we encountered an error on GitLab stating that we've reached the space limit for the repository. 

When investigating we found out it was because we had by accident commited the node modules file early on in devlopment - because we arent able to push changes even if y=those changes are to remove files we contacted DCU Digital Technology Solutions

They replied that the cause of the issue was indeed the node modules and directed us to follow steps to delete the commited node modules - however this approach did not work and administation was not able to allocate us additional space.

The solution was to create another GitLab repositiory with a similar name, ensure the gitignore file contains the node modules and continue the rest of the projects development in the new repositiory.

Our new rerpositiory is "Mimir Smart Mirror 2" this is the link (https://gitlab.computing.dcu.ie/willid26/2026-csc1097-lagurac2-willid26-2)

<!--more-->

**Attendees:** Diana Williams Oshun, Christian Michael Lagura Yacapin