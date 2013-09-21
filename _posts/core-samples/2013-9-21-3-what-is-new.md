---
layout: page
title: 3 what's new ?
tagline: a little java a few patterns
---

{% include JB/setup %}

## Advice

**The Third Bit of Advice**

When writing a function that returns values of a datatype, use **new** to create these values.

## Thinking

This is similar to the **interpreter** and **composite** patterns.

**Advantage**
- When we add variants to the datatypes we have defined, we don't need to change what we have.
- This is a really flexible way of defining classes and methods.

**Disadvantage**
- The more things we want to do with 'a class', the more methods we must add. That means cluttered classes.
