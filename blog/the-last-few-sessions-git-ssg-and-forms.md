---
layout: layouts/blog.njk
tags: blog
title: Git, SSG and Forms
date: 2021-05-27T18:35:00.949Z
thumbnail: /images/uploads/pexels-luis-gomes-546819-1-.jpg
rating: 3
---
In the last few sessions at the Coders Guild we have covered a lot of great topics that all link together really well. We started learning the version control system git, we covered command line git, github desktop, forking, branching, collaborating and pull requests. We also touched on good workflow practices such as having different branches for testing, development and production. One key point I learnt and am putting into practice is to make commits regularly and write clear commit messages, this allows me and others to understand clearly what I have done throughout the development of a project. I now know the basics of git and finally understand what all the hype is about. I’m a git now (Is that what fans of git are called?)

Then we learned about static site generators. We used a static site generator called eleventy to create a basic blog. Eleventy is used with node.js as it is built with Javascript. My understanding of static site generators at this point is that they help you build a site quickly and efficiently from a collection of different content and layout files. This helps you keep your project DRY and organised. Eleventy utilises markdown files which are clearer and easier to read than HTML.

Then on github we created a repo to store our eleventy blog. We then connected this repo to netlify to host the site from the github repo. Now when I make changes to my local eleventy repo and push them to the remote repo. The live netlify site gets updated. This has opened my eyes to a really efficient way of creating and updating a website.

Lastly we added a netlify form to our eleventy blog site, learned about input types and html validation attributes. I added some required and maxlength attributes to ensure the form has all it fields filled out and that the input is a reasonable length. One point that was highlighted is that you always need server side validation as well as client side validation. The HTML validation I added to the form increases usability not security. You can see this form In the “about me” page on this site.