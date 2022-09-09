---
layout: essay
type: essay
title: "No Such Thing as a Dumb Question"
# All dates must be YYYY-MM-DD format!
date: 2022-09-08
published: true
labels:
  - Questions
  - StackOverflow
---

## No Such Thing as a Dumb Question

I can’t say that I can end the very polarizing debate over whether there is or is not such a thing as a dumb question. On one side it’s counterintuitive to stifle someone’s pursuit of knowledge simply because they are uninformed, however it is equally as unproductive to ask open ended questions that could easily be answered through a little self driven research. What I can say for sure is that there is such a thing as a “smart” question. 

## What is a smart question? 

A smart question is one that doesn’t already have an easily locatable answer. If your question has already been addressed on the forum you are planning to ask, there’s no good reason why to create a new thread and waste other people’s time. If the question you have is similar to an existing question, with a few key differences, it is important to note these differences and inform those you are planning to ask for help so they can understand the problem you are having. A smart question is also specific, asking an open ended question like “how do I make this function work?” is generally pointless in an environment such as stack overflow. Many kind individuals may come to your aid and produce their own solution to your janky code however they have no contextual knowledge of what exactly your function is interacting with. Adding specificity to your question also helps you to understand the issue further, it shows that you spend a considerable amount of time trying to solve your problem and that reaching out to others is the last thing you can do to move forward. Finally don’t expect someone to magically come to your rescue, when you seek assistance sometimes the most people can do is help you with one facet of your problem, be grateful that they took the time to help in the first place. It is very rude and unbecoming of an academic environment to take your help for granted. Sometimes people may not hold this same air of politeness and answer your well formatted question appropriately but just brush it off and move forward, arguing with others is not going to fix your problem. 

## Here’s an [example](https://stackoverflow.com/questions/1335851/what-does-use-strict-do-in-javascript-and-what-is-the-reasoning-behind-it) of a well formatted, smart question.

```
Recently, I ran some of my JavaScript code through Crockford's JSLint, and it gave the following error:
Problem at line 1 character 1: Missing "use strict" statement.
Doing some searching, I realized that some people add "use strict"; into their JavaScript code. Once I added the statement, the error stopped appearing. Unfortunately, Google did not reveal much of the history behind this string statement. Certainly it must have something to do with how the JavaScript is interpreted by the browser, but I have no idea what the effect would be.
So what is "use strict"; all about, what does it imply, and is it still relevant?
Do any of the current browsers respond to the "use strict"; string or is it for future use?
```
While not the most technically advanced question, this is a great example of the way to ask for help on a professional forum. The user describes his process briefly, informing us of the context of his issue, he gets an error from his compiler asking for a statement he doesn’t know about called “strict”. Then he provides an exact copy of the error he is seeing and discusses what he did to try to answer his question, talking about his findings on google and why he still needs clarification. Finally he ends the post with two concise, answerable questions. What is the purpose of the function and why is it important? This led to a very detailed and thorough explanation from multiple different users, they were able to completely understand where he was coming from and could cite some sources that may clear up the confusion caused from the original poster’s dead end google search. 

Here’s an [example](https://stackoverflow.com/questions/73659822/how-to-replace-all-space-dots-and-some-special-chars-like) of a “bad” question

```How to replace all space , dots and some special chars like _, `, ~, @, =, !, &, # from JavaScript string with regex. Basically I need to change uploaded file name where no space no dot and no special char allowed.```

In this post the user wants to replace special characters in a Javascript string with regex. This is the extent of information we are given. The user didn’t post a single piece of their own code nor did they walk us through their thought process. This issue is relatively easy to resolve through one’s own research, even I was able to find a relevant answer on an existing stackoverflow thread in one google query. This vague question with no context is a downvote dogpile waiting to happen, as of the time of writing this essay the post has gotten a handful of views and a few downvotes with no answer as expected. 

## In Conclusion
Even though this is potentially a case for the existence of “dumb questions.” it is more important to take away the process of how to properly reach out for help. When you decide that your only option is to reach out to strangers for help, take a step into their shoes and do a little extra work on your end to help them, help you, effectively. Sometimes this doesn’t always work but when it does, don’t forget to pay it forward and try your best to help someone else, at least someone who’s asking a “smart” question. 
