---
title: "Project Blog"
description: "Blogging about my project"
layout: post
---

Our finished project utilizes a dynamically genearted calendar and weather API. The user can schedule events in the calendar by clicking on the day they want, typing in what they want to save, and hitting "save". The events are saved to a dictionary where each key is named after a day in the current month and each value is a list. Events are saved into their corresponding lists. The non-empty lists are displayed next to the calendar, with better formatting, of course. On the far right, the user can input a city and display weather information for the city, namely weather state, high temperature, low temperature, and current temperature. This data is acquired via API.