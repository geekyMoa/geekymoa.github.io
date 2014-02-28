---
layout: post
title: How to Succeed in Open Source (or Things I Learned from Writing My First Rules Condition)
excerpt: My colleague Mattias keeps giving me one piece of great advice that I just keep forgetting. When you want to accomplish something, look at a piece of code that already does sort of what you want to do, copy and paste it, and modify it to work like you want it to.
---


My colleague Mattias keeps giving me one piece of great advice that I just keep forgetting.

When you want to accomplish something, look at a piece of code that already does sort of what you want to do, copy and paste it, and modify it to work like you want it to.

Today I wrote my first [Rules](https://drupal.org/project/rules) condition and I struggled for a *quite some time* with accessing the parameter I wanted from my condition function. I wanted a node object, and despite digging through the documentation I couldn't seem to get it right. (Or, as it turned out, I actually got it right but must've mistyped something, but that's beside the point.) Giving up, I turned to Mattias and as soon as he'd understood my plight he told me to look at an exisiting condition that did just that - accessed a node object.

For example, the very standard "Content is of type" condition.

Problem solved in less than two minutes. I am writing it down in the hopes of actually remembering this all by myself next time.