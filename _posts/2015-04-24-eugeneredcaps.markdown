---
title:  "Eugene Red Caps"
subtitle: "Reporting mobile application and API"
image: "img/redCaps.jpg"
date:   2015-04-24 12:12:12
---

### The Problem:
The downtown security team known as the Red Caps were in need of a better why of tracking the incidents they help resolve. So Downtown Eugene Inc entered this Challenge in the Eugene event Hack for a Cause.

### The Solution:
The Downtown Eugene website was already in some use for them. This site was a WordPress site and it was determined there was no need to force a new technology, a custom plugin for WordPress was developed. This plugin used the existing WP database to store incidents and created a custom WP API endpoint. Along with this API an app was developed to allow the downtown security to capture the Lat and Long and time of an incident every time. Further preset options make for a quick and consistent reporting experience.

### The technologies
A plugin with a WordPress API custom endpoint along with settings pages to edit data was developed. This was in PHP and used Googles charts and maps JavaScript libraries for charts and maps.

The mobile application was created with facebooks JavaScript React Native framework.
