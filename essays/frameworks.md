---
layout: essay
type: essay
title: "First Impressions of Bootstrap"
# All dates must be YYYY-MM-DD format!
date: 2023-10-04
published: true
labels:
  - Bootstrap
  - HTML
  - CSS
---

<img width="200px" class="rounded float-start pe-4" src="../img/bootstrap.jpg">

These past couple of weeks included my first ever experiences with HTML and CSS. To be completely honest, I did not think it would be as hard as it is. Learning them is pretty straightforward but the difficult part is learning and getting used to all the tools you have available for you. From these experiences, I've learned that creating webpages is especially difficult due to how tedious the process is. However, frameworks cut down the tedious-ness by providing classes that could potentially replace a large percentage of CSS code you would've written without it. As good as that may sound, there is also a learning curve for frameworks such as Bootstrap, which is something I've struggled with these past few days. 

## Hands on Experience

One of the more notable experiences of my Bootstrap journey so far is the WOD assignment where we had to choose a website and recreate it to the best of our ability using Bootstrap. For this assignment, I chose to recreate [https://ch.tetr.io/](https://ch.tetr.io), which seemed pretty difficult to implement. Unfortunately, that came true and I spent a good chunk of the day trying to figure out how to make something similar to the original. The biggest issues I had while doing the assignment was with alignments, margins, and paddings. Namely, at one point there was a huge whitespace between the footer and the body due to huge margins and paddings coming from elements that were relatively far away from the whitespace itself. One of the solutions I had in mind was to adjust those values manually using CSS, but to my surprise, it did not work. After a while of trying different things, I eventually opted to start over. That's when I realized how useful the 'container', 'row', and 'col' classes from Bootstrap are. While 'row' and 'col' allows you to align things side by side, and from my understanding, 'container' ensures that all the elements inside of it are all within the defined space without leaking out. The use of 'container' resolved the issue I had since it prevented the margins of an element from leaking past the space I defined them in, which essentially prevented whitespace between elements on the page. Overall, I'd like to believe that the use of these Bootstrap tools kept me from writing even more CSS than I already did.

## What Have I Learned?

Overall, Bootstrap 5 is pretty useful since it provides you with tools that save you from implementing simple, yet tedious formatting options for your webpage. I can confirm that they were not lying when they say it has a high learning curve considering the immense amount of different classes the library offers. It can be a bit annoying at times when things aren't being formatted the way you want it to, but based on my experience and what I've been hearing from others, that's probably just the usual when using HTML and CSS. On a side note, it would be a good idea to read the documentation and understand how the classes really work with a few Google searches. A lot of what I used were copied from the Bootstrap website and I just trusted that they'd work the way I assumed it did. Take this line of HTML using Bootstrap for example:

```<nav class="navbar navbar-expand-lg navbar-light bg-light">```

Clearly, it creates a navbar that you can use to store different elements in. However, I think it would be useful to know what each class does to format the navbar. For example, it would be useful to know that 'bg-light' makes the color of the navbar a light gray if you wanted to style it to be some other color. 
