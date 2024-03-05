---
title: Subject page template
description: Developing a template for subject pages, so they all have a consistent look and feel.
date: 2024-03-04
---
## What we did
We developed the scope of subject pages available on the website. There was already a subject page for maths, physics and engineers for physics but these were not hosted on the navigation. 

So we created a new template for the subject pages, based on previous user research, so that we can expand the amount of subjects hosted on the website. We did this to make sure they all had a consistent look and feel. And improve their navigation by adding them into the 'is teaching right for me?' category page, so users could access this content easily.

## Why did we do this work? 

We know from previous user research that perspective teacher trainees want to know more about the subject. They want to know:
- what the teaching environment is like, ie. classroom behaviour and lesson plans
- the qualifications and funding for the subject
- why they should choose this subject

## First section 



'Become a [subject name] teacher'

You'll use the first section to say briefly what this subject is and sell the subject/ why users should teach it.
You'll also include a line about the bursaries and scholarships available. 

'Tax-free bursaries x or scholarships of x are available for eligible trainee [subject] teachers.'

## Second section

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Pink text box for more information",
      img: { src: "subject-page-2nd-section.png" }
    }, 
    ]
}) }}

This section can be used for a quote or more information to introduce what teaching this subject includes.
This section can be used for a quote or more information to introduce what teaching this subject includes.

