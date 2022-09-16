---
layout: project
type: project
image: img/websquare.png
title: "Webcrawler"
date: 2021
published: true
labels:
  - Java
  - Trees
  - HTML
summary: "A webcrawler application developed for ICS 211."
---

This program is a simple web crawler that takes a webpage URL and an interger for the depth of the search to be performed and applies two different tree traversal methods to access more webpages through the hyperlinks found on the original page. The program constructs a graph with the read hyperlinks as nodes and traverses it using a breadth first search and a depth first search. 

A screenshot of the code running 
<img class="img-fluid" src="../img/crawlrun.png">

Here's the starting page. One of the first links scanned in the search is the privacy policy
<img class="img-fluid" src="../img/startsc.png">

Here's what it looks like when you visit the url scanned by the Webcrawler, it is a real link to a real page 
<img class="img-fluid" src="../img/privacysc.png">
