---
layout: layouts/projects.njk
tags: project
title: Animal Image Filters
date: 2021-06-24T21:34:56.869Z
thumbnail: /images/uploads/animalfilter.jpg
---
The challenge this time was to build an image filter program. We had to collect 16 images from pexels.com. The images are of 4 different animals so each animal has 4 photos each. We had to create a search bar and have 5 buttons. The buttons are named after the animals plus a “show all” button. When a button is clicked the photos are filtered to only show the animal for the button selected. We then had to add functionality to the search bar so that when a ‘keyup’ event is triggered the images are filtered based on the search input matching against the images alt text. Additionally I added a ‘search’ event to call the same handler as this will trigger when the user presses enter in the search text field and when the user presses the ‘x’ in the search to empty the search text field. See my finished version <a href='https://codepen.io/ThomasAlexMann/pen/QWpedYy'>here</a>