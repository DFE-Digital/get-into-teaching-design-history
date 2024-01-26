---
title: Update promo blocks
description: The footer featured duplicated links from the primary navigation and was failing various accessibility checks.
date: 2024-01-26
---

## What we did

As a result of the brand colours update we recently applied to the website, various promo banners were negatively impacted from a colour contrast point of view. For example, with the darkening of the green on primary CTAs, any such buttons that were placed on a purple background would fail accessibility tests.

To fix this issue, we decided to subtly redesign the banners, incorporation the new brand colours in a manner that would return the colour contrast back to acceptable levels. This fix was applied to three banners in total, and called for changes to be made to the accompanying graphics, too.

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Previous promo banner on homepage",
      img: { src: "01-update-promo-blocks.png" }
    }, {
      text: "New promo banner on homepage",
      img: { src: "02-update-promo-blocks.png" }
    }, {
      text: "Previous promo banner on 'How to become a teacher' page",
      img: { src: "03-update-promo-blocks.png" }
    }, {
      text: "New promo banner on 'How to become a teacher' page",
      img: { src: "04-update-promo-blocks.png" }
    }, {
      text: "Previous promo banner on 'How to become a teacher' landing page",
      img: { src: "05-update-promo-blocks.png" }
    }, {
      text: "New promo banner on 'How to become a teacher' landing page",
      img: { src: "06-update-promo-blocks.png" }
    }]

}) }}
