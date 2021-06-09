---
layout: layouts/blog.njk
tags: blog
title: Netlify CMS
date: 2021-06-01T21:14:19.214Z
thumbnail: /images/uploads/pexels-luis-gomes-546819-1-.jpg
rating: 5
---
This session we added a content management system from Netlify to our Eleventy blogs. The setup of this required quite a few steps. Some of the steps were creating files within the Eleventy project and some were altering settings within my Netlify account. After setting up and using the CMS I now understand much clearer the benefits of static site generators as I will now explain. When I visit the admin page on my live Eleventy blog it has a user inteface to create new blog posts. When I publish the new blog post the submission is sent to Netlify who has access to the git repo where the Eleventy blog files are stored. Netlify pushes a commit to the repo creating a new markdown file with blog specific front matter and the blog content. As a change has been made to the repo Netlify then runs the Eleventy build command to obtain an up to date set of static html files. This means the new blog post is now just a static html page. This contrasts to the dynamic method of pulling the blog post content out of a database and building a HTML page every single time someone views a blog page. Now the poor old database can have a well earned rest. 