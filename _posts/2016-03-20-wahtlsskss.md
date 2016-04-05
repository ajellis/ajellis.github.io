---
layout: post
title:  "The Pragmatic Programmer: Chapter 2, Part 1- The Evils of Duplication"
date:   2016-04-01 19:00:00 -0400
tags: [books, pragmatic_programmer]
permalink: blog/2016/4-01/evils-of-duplication
comments: True
---

### DRY- Don't Repeat Yourself

Those three words essentially sum up this section of the book. This is something that I know is extremely important, but I often find myself not paying enough attention to for various reasons. Repeating yourself can cause many problems in programming. Although I am not much of a Star Trek fan myself, I can appreciate the Captain Kirk analogy he used to describe how duplication can lead to conflicting information. The book describes four types of duplication: Imposed, Inadvertent, Impatient, and Interdeveloper.

Imposed duplication is usually the biggest reason. I often feel as though I don't have much of a choice. I need to get similar data, but use it in a different way. In Ruby, there is a simple fix for this, but I often just don't use it. Methods. This is what methods are for. This is true for most object-oriented languages. It's amazing how basic concepts that you learn in one language can be applied to so many different languages. Thinking like a programmer and building the correct habits and practices is indeed much more important than the language you use.

Inadvertent Duplication is also very common. I just don't realize that I am essentially doing the same thing as I did before. This one is a bit harder to avoid, because it is <i>inadvertent</i>. One trick that I have found that helps me avoid Inadvertent duplication is to always try to make a method for any work I need done, then to call that method whenever I need it.

It is so easy to copy and paste code when I need new code that is similar to my old code. But it can cause so many problems. If I ever need to edit that code, I now have to edit it in both places. "It's not a matter of if you will remember to change it everywhere, it's a matter of when you will forget."

Interdeveloper duplication was a problem that became very apparent for me while working on group projects at The Iron Yard. It is an understandable thing when you are just really getting into pair programming or being a part of a team. It's important not to just let these things sit, however. I have to be proactive in working to remove interdeveloper duplication from projects that I am working on. It will lead to much less conflict, and will create smoother code in the long term.
