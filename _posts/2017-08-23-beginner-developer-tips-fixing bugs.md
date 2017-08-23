---
layout: post
title: Beginner Developer Tips&#58;<br> Finding Bugs in your &lt;code&gt; Part 1
---

One of the worst feelings I have felt during my development journey so far is what you feel when you check your site after working on a new feature, for hours, only to find out <em>'Doh! My site is broken!'</em>

![Frustrating Bug Gif](https://media.giphy.com/media/hw0ffPj1PSlBm/giphy.gif){: .center-image }

Learning a new language and using it in a project can sometimes be very frustrating, especially when you are following instruction line by line and somehow still miss something. Here's some tips I've found useful:

<ol>
  <h2><li> Commit early, and commit often!</li></h2>

  If you are old enough to remember the "save early, save often" mantra of early computer science, this is a similar idea. Committing frequently not only ensures you save work and reduce the risk of losing hours upon hours of work, it also makes it so that you have less lines of code to look through if something breaks. Even if you do not check your work after every commit (which you absolutely should when you are learning) you can revert back to previous commits and narrow down the bit of code that has broken your project.

  <h2><li> Use the comment shortcut to narrow down your code</li></h2>

  In a previous post I wrote about one of my favorite shortcuts, Comment/Uncomment. Once you've figured out the feature that broke your project, because you made frequent commits, you can comment out different sections of the newly written code and find what restores functionality after being removed. Work backwards from what you added in commenting out short snippets to narrow down to a few lines and then refactor or rewrite that part.

  <h2><li> Take a break, and come back to it</li></h2>

  Sometimes the bug doesn't completely break your project, but instead your intended functionality is just not there. Looking through code that is supposed to work, but doesn't, can be one of the most frustrating tasks, especially when you are on a deadline. It may sound counter-intuitive but take a break. Go grab a bite to eat or take a 5 minute walk. Something that simple can have a wonderful regenerating effect that can give the boost needed to find what you are looking for.
</ol>

![Losing hours of work](https://media.giphy.com/media/MpXXZBsIhu3II/giphy.gif){: .center-image } <center>*How I feel after finally fixing a bug.*</center> 

There are a lot of techniques to help when debugging and in part 2 I will go into Google developer tools among other things.

Are there other techniques or a story of debugging you want to share? Leave a note in the comments below!
