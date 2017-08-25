---
weight: 2
title: "Recruitement: Technical Testing"
date: 2017-08-25T14:22:45+10:00
---

## Context

Engineering candidates are required to pass a technical test. The goal of this test is to verify their ability to work with:

-   Ruby on Rails projects for the back-end
-   AngularJS technology for the front-end
-   APIs
-   User Interfaces oriented projects

## Expected Architecture

The final project is supposed to display widgets containing maps showing data retrieved from the Impac! API.

The AngularJS front-end is supposed not to query directly the Impac! API, but rather a Rails application which should take care of the API calls. This Rails app is supposed to be very simple (no database needed) as it is just a wrapper that queries the Impac! endpoints and structures the data in a format adapted to the maps that are going to be rendered in the widgets.

As per the basic rules of developing in AngularJS, directives and services are expected in the front-end.

## References

The test full brief can be found there: <https://gist.github.com/cesar-tonnoir/f30b30916b8c507f0c6a>

The test review sheet template there: <https://drive.google.com/open?id=1b0Duj9ReRdvd4sKOISum3ecV52nGvBoixm-VBo4Vswc>
