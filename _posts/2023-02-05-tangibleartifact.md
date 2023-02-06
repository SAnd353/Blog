---
title: "Tangible Artifact Blog"
description: "Blogging about my tangible artifact for 2/6"
layout: post
---

# My tangible artifact is a live-generated calendar (for the current month) with clickable days.
- this is largely done with Javascript.
- It makes use of Javascript's built in Date() object functionality
- The JS creates "daySquare" elements based upon the current month and current day of the week
- In the function that creates "daySquare" elements, the number of days in the first week of the month being generated that belong to the previous month is accounted for
    - This is so that the function can create an appropriate number of "padding days"

- Furthermore, whenever a daySquare is created, addeventlistener is used to make them clickable buttons

# Things to work on and improve
- Instead of making the days, when clicked, immediately ask for a new workout, make them open the currently saved workouts to the side and have buttons for adding, removing, and changing workouts there (Making things more intelligent)
- Saving and retrieving data to the backend (POST and GET requests with fetch())