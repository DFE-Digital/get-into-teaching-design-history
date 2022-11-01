---
title: Call to actions and highlight page
description:
date: 2020-12-08
---

## Calls to action

We added a flexible call to action component that can have various states:

- **Generic** - Has title, snippet and link
- **icon** - As generic, but can select from list of icons, including arrow, person and calendar
- **image** - As generic but has an image. 

## Highlight current page

Added indicator on what the current page is in top nav.

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Highlight current page in nav screenshot",
      img: { src: "01-highlight-current-page-in-nav-screenshot.jpg" }
    }, {
      text: "Call to action generic screenshot",
      img: { src: "02-call-to-action-generic-screenshot.jpg" }
    }, {
      text: "Call to action with icon screenshot",
      img: { src: "03-call-to-action-with-icon-screenshot.jpg" }
    }, {
      text: "Call to action with image screenshot",
      img: { src: "04-call-to-action-with-image-screenshot.jpg" }
    }]
}) }}
