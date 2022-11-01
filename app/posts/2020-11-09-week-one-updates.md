---
title: Week one updates
description:
date: 2020-11-09
---

Following the analysis of the first week of in Beta, we made the following Changes:

## Feedback banner Position
To increase visibility of the feedback banner we changed this into a fixed position element that sits at the bottom of the viewport. 

## Homepage Feature Box ordering
Switched the order of boxes on the homepage to test if position has an effect on engagement of each item. 

## Pull in future events if there are none in current month
When a user landed on the events page toward the end of the month no events are showing, leading us to believe this is the cause of low conversion. It has been changed so that if there are no events in the current month then ones from future months.

## Add search box to events sub pages
To help user find events we brought in the search box from the events landing page to event type sub pages. 

## Add pagination to events
Events sub pages returned all upcoming events on one page, leading to huge page scrolls, we added pagination to break up results and reduce page length.

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Feedback banner",
      img: { src: "01-feedback-banner.jpg" }
    }, {
      text: "Homepage box ordering",
      img: { src: "02-homepage-box-ordering.jpg" }
    }, {
      text: "Pull in event if none in month",
      img: { src: "03-pull-in-event-if-none-in-month.jpg" }
    }, {
      text: "Events sub page search box",
      img: { src: "04-events-sub-page-search-box.jpg" }
    }, {
      text: "Events pagination",
      img: { src: "05-events-pagination.jpg" }
    }]
}) }}
