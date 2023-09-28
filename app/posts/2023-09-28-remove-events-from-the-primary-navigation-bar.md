---
title: Remove 'Events' from the primary navigation bar
description: As part of the larger task of restructuring the website, it was decided that 'Events' should be removed from the primary navigation.
date: 2023-09-28
---

## What we did

User research and data analysis had suggested that we would need to restructure the primary navigation to align better with the customer journey map. As part of this restructure, it was decided that we'd be removing 'Events' from the primary navigation bar. The reasons for this were:

- Events are already heavily exposed via promo and homepage modules across the site
- User research suggested 'Events' was not getting as many clicks as other top-level links, therefore taking up valuable real estate

Whilst the task might have sounded straightforward, we were also required to appease the Events team who were concerned that removing 'Events' from the primary navigation would reduce traffic to their pages.

Following several iterations, it was decided that the best place for the 'Events' link was the slim grey bar that runs across the top of the website - now affectionately referred to as the 'Bonus Bar'. Moving the link in question here would not only free up space in the primary navigation, but also improve visibility on mobile, as it would no longer be hidden within the drop-down menu.

## What we'll do next

We will be monitoring the impact of this change and making further improvements if required. Early analysis suggests that this alteration has resulted in an dramatic increase in click-throughs to the Events page.

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Old 'Events' link location on desktop",
      img: { src: "01-old-events-link.png" }
    }, {
      text: "New 'Events' link location on desktop",
      img: { src: "02-new-events-link.png" }
    }, {
      text: "Old 'Events' link location on mobile",
      img: { src: "03-old-events-link-mobile.png" }
    }, {
      text: "New 'Events' link location on mobile",
      img: { src: "04-new-events-link-mobile.png" }
    }]
}) }}
