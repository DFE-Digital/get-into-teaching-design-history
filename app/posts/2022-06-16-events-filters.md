---
title: Events filters
description: Events redesigned to put users in control showing all events up front
date: 2022-06-16
---

This was an AB test now gone live. Results from AB test were fairly similar but the new design puts the user in control of searching for events using a more accessible and open filtering option.<br>
Ultimately, this resulted in reducing a lot of tech debt for the developers from the original page.

## Landing:

- Change of approach. Rather than splitting events by type allow users to search all events and filter out based on preference.
- 2 column layout
- Event types descriptions added into a 'details' component.
- Try to push events as high up page as possible.
- New card layout for events

## Individual event

- Used 'subject specific' layout to try and inspire a bit more (this layout is in its infancy)
- Build didn't quite match the design so will revisit further down the line


## Get Into Teaching events

- Renamed "Train to Teach events" to "Get Into Teaching events" 
- New card layouts used
- Used 'subject specific' layout to try and inspire a bit more (this layout is in its infancy)


{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Events landing desktop screenshot",
      img: { src: "01-eventslanding-desktop-screenshot.png" }
    }, {
      text: "Events landing mobile screenshot",
      img: { src: "01-eventslanding-mobile-screenshot.png" }
    }, {
      text: "Event desktop screenshot",
      img: { src: "02-event-desktop-screenshot.png" }
    }, {
      text: "Event mobile screenshot",
      img: { src: "02-event-mobile-screenshot.png" }
    }, {
      text: "Get Into Teaching events desktop screenshot",
      img: { src: "03-events-gitevents-screenshot.png" }
    }, {
      text: "Get Into Teaching events mobile screenshot",
      img: { src: "03-events-gitevents-mobile-screenshot.png" }
    }]
}) }}
