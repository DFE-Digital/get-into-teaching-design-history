---
title: Navigation
description: 
date: 2021-07-09
---

Design tidy up, removing bold from the nav. Adding top grey extra navigation bar to relieve lack of space for all the links. <br><br>The new grey bar will be closely monitored to asses usage and interactions over time, also with a view to remove more links from the nav where possible.

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Navigation screenshot",
      img: { src: "01-navigation-desktop-screenshot.png" }
    }, {
      text: "Mobile screenshot (closed menu)",
      img: { src: "02-navigation-mobile-screenshot.png" }
    }, {
      text: "Mobile screenshot (open menu)",
      img: { src: "02-navigation-mobileOPEN-screenshot.png" }
    }]
}) }}
