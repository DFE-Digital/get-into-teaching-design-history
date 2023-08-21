---
title: Update homepage modules
description: Various padding and spacing issues were pushing content further down the page.
date: 2023-08-21
---

## What we did

Previously, the homepage modules featured excess margin, padding and spacing which was making them larger than they needed to be and also pushing content further down the page, particularly on mobile. Furthermore, the horizontal 'salary' banner was missing a title tag, which causes accessibility issues, particularly with respect to screen readers.

To remedy the above problems, we firstly removed any excess padding, margin and spacing between components. An example of this can be seen in the screenshots below. Where there was previously a thin grey band of colour above the yellow icons and imagery, this has been deleted, thus reducing the height of those particular modules.

Our next step was to add a h3 tag to the horizontal 'salary' banner, therefore improving the accessibility and readability of this module.

## What we'll do next

We will be revisiting the design of these modules in the future.

<br>

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Previous modules",
      img: { src: "01-old-module-design.png" }
    }, {
      text: "Updated modules",
      img: { src: "02-new-module-design.png" }
    }]
}) }}
