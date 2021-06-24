---
layout: layouts/projects.njk
tags: project
title: Todo List
date: 2021-06-24T21:29:35.959Z
thumbnail: /images/uploads/todo.jpg
---
The challenge was to create a todo list program using JavaScript. We learned how to create elements and text nodes in JavaScript and append them to each other and elements in the DOM using <code>parent.appendChild(child)</code>. I also learned about HTML collections which are a built in feature you can use to quickly get JavaScript representations of HTML elements on the page. I used the forms collection to neatly get hold of some form elements. 

One interesting point that was highlighted is that the event handler for the form submission uses a ‘submit’ event as its trigger. This is better than having a ‘click’ event handler on a submit button as forms can be submitted in different ways such as by pressing Enter when a form text field is in focus. Using the ‘submit’ event means that however the form is submitted the event handler will be called. See my finished version <a href='https://codepen.io/ThomasAlexMann/pen/XWMwNaK' target="_blank">here</a>.  