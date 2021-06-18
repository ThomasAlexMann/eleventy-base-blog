---
layout: layouts/blog.njk
tags: blog
title: " Loops, Arrays and Objects"
date: 2021-06-18T18:55:01.843Z
thumbnail: /images/uploads/pexels-negative-space-169573.jpg
rating: 5
---
 

In the last two coders guild sessions we covered JavaScript loops, arrays and objects. 

 A loop runs a piece of code a number of times based on a condition. We covered <code>while</code> loops, <code>for</code> loops and <code>for..of</code> loops. <code>for...of</code> loops are preferable over standard <code>for</code> loops as they avoid “off by one” errors. An “off by one” error typically happens when a loop that is iterating over an array iterates more times than there are elements in the array, the code in the loop will be trying to access an element in the array that does not exist. The standard for loop however is needed if you want a loop counter as <code>for...of</code> does not have this as a feature. 

Arrays are essentially lists of items. The items in an array can be of any data type (such as strings, numbers, arrays and objects), the items in an array are accessed by numerical index and square brackets such as myArray[3], this would access the fourth item in the array. 

Objects on the other hand have named properties and can be accessed with dot syntax such as user.age. This would access the value of the age property on the user object. You can also access object properties using square brackets such as user[‘age’] but it is often only used when necessary.   

In the first session we printed some times tables using nested <code>for</code> loops. We then went on to store some cooking recipes as objects using arrays to store the ingredients and directions for each recipe. View my code from the session <a href="https://codepen.io/ThomasAlexMann/pen/oNZQRPv?editors=0111" target="_blank">here</a>. 

In the second session we wrote some functions that accept a shopping cart array argument. We wrote a function to calculate the total of the shopping cart with a discount applied to certain types of product. We then built a filter function that takes a shopping cart array as an argument and returns a shopping cart array containing products within a certain price range. See my code <a href="https://codepen.io/ThomasAlexMann/pen/xxqMryb?editors=0111" target="_blank">here</a>. 

One last point I learned was that it is good practice to declare arrays and objects with the <code>const</code> keyword. Doing this doesn't mean that the arrays and objects can't have elements/properties created and changed, it just means that the array or object can't be overwritten. See example <a href="https://codepen.io/ThomasAlexMann/pen/oNZVQPN?editors=1111" target="_blank">here</a>.