---
title: "Initial Mockup of the PPME Demo Website"
date: 2022-03-12
# post image
image: "images/mockup.jpg"
# post type (regular/featured)
type: "featured"
# meta description
description: "Intial set of the Demo"
# post draft
draft: false
---


This document explains the initial mock-up pages of PPME Website, from techical setup, code and hosting.

### Technical Setup
This demo page has been created with the help of:
* [Hugo](https://gohugo.io/) - ***The world’s fastest framework for building websites***
* [bigspring-light](https://github.com/themefisher/bigspring-light) Hugo template
* Original content from PPME Google Drive and PPME WordPress site


All the site demo code are stored in GitHub repository [ppme-demo-001](https://github.com/rostiarso/ppme-demo-001), and ***freely*** hosted in [Google Firebase](https://firebase.google.com/).

With this setup, the developers can checkout the code and build the website locally on their Windows/Mac/Linux machines.
We can collaborate and continue to build the website with ensurance of full backup and versioning provided by GitHub.

#### Implemented Features

* Responsive, pages should be accessible from mobile phone, tablets or desktop.
* Secured with TLS certificate
* Content Delivery Network (CDN) by default, ensuring reliable performance from global users
* Main page with simple interface, half the content still in mock-up stage.
* Navigation menu available 
* Multilingual. [EN](/) and [NL](/nl/) selectable from navigation menu and can be extended to ID. Example is the marriage page in [English](https://ppme-demo-001.web.app/ibadah/marriage/) and [Nederland](https://ppme-demo-001.web.app/nl/ibadah/marriage/) version

#### Todo Features

* Completing existing material migration from WP to Hugo
* Add events and special celebration information 
* Integrate Contact form with [Formspree](https://formspree.io/plans) but will cost
* Much-much later, - check possibility of allowing online donation(?) and integration with payment gateway
