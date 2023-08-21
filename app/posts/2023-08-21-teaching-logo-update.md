---
title: Update 'Teaching' logo background colour
description: Improving website usability, especially on mobile, where the green menu CTA could clash with the green logo.
date: 2023-08-21
---

## What we did

We are planning to update the design and layout of the header component. Initial investigations concluded that the current 'Teaching' logo, with its green background, clashed with the green menu CTA, hence causing usability issues and decreasing the visibility of this component.

Following various design iterations, we decided that a blue background would work best across all screen sizes. The logo background colour has therefore been changed from green (#159964) to  blue (#2881be).

## What we'll do next

We will be updating the design and layout of the header component. This can now feature a green CTA that will not clash with the logo.

<br>

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Old logo colour",
      img: { src: "01-old-logo-colour.png" }
    }, {
      text: "New logo colour",
      img: { src: "02-new-logo-colour.png" }
    }]
}) }}
