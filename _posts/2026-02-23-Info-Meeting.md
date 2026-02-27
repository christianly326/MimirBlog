---
title: "Info Meeting"
excerpt_separator: "<!--more-->"
date: 2026-02-23
categories:
  - Sprint 11
tags:
  - meeting
  - info
show_date: true
---
Meeting was initiated after the backend got deployed on Amazon Lighsail to made sure all project partners were up to speed.

- Decided to go with the Amazon Lightsail server as it best fits our project however for the clothing generation this would need to be setup on a replicate api for the catvton model so that we can only pay for the gpu that we use
- Currently we are on the 12$/month payment plan but we have the first 90 days for free
- To run backend on server terminal 1
  - Make sure that on the lightsail console that the instance is running
  - ssh -i .\LightsailDefaultKey-eu-west-1.pem ubuntu@63.33.185.81 
  - cd ~/2026-csc1097-lagurac2-willid26/src/mimir
  - source venv/bin/activate
  - gunicorn mimir.wsgi:application --bind 127.0.0.1:8000 --daemon
- went through all opperations to made sure that Chriastian could access and use the Lightsail server


<!--more-->

**Attendees:** Diana Williams Oshun, Christian Michael Lagura Yacapin