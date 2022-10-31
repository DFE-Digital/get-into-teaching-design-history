---
title: Category pages
description:
date: 2022-04-20
---

Introducing 2nd level pages know as 'Category pages'<br>
Allowing for further navigation other than the top nav these pages are to be used to help direct users to more content where previously there would have been too much content on a single page.
<br>
This replaced/encompassed the "Ways to train" page


{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Category desktop screenshot",
      img: { src: "01-category-desktop-screenshot.png" }
    }, {
      text: "Category mobile screenshot",
      img: { src: "01-category-mobile-screenshot.png" }
    }]
}) }}
