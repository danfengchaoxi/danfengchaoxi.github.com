---
layout: page
title: 4、come to our carousel
tagline: a little java a few patterns
---

{% include JB/setup %}

## Advice

**The Fourth Bit of Advice**

When writing several functions for the same self-referential datatype, use visitor protocols so that all methods for a function can be found in a single class.

## Thinking

**visitor class.**

- 要解决的问题：
上一篇‘what's new?’中，想要对父类操作时，要在每一个类中定义一个方法。It becomes more and more difficult to understand the rationale for each of the methods in a variant and what the relationship is between methods of the same name in the different variants.

- 特点：
Those methods in the one class.

- 准备：
-- that refer to the class that contains the actions.
-- How the separation of data and action works.
-- Separate the action from the datatype.

## Question

- P60, 17-22 不清楚怎么翻译，尤其是'consume'。
