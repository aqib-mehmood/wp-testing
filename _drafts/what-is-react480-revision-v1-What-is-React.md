---
id: 483
title: What is React?
date: 2020-08-21T10:10:55+00:00
author: aqib
excerpt: 'React is a UI library created by Facebook. It helps you create interactive web applications made up of components. '
layout: revision
guid: http://localhost/mysite2/2020/08/21/480-revision-v1/
permalink: /2020/08/21/480-revision-v1/
---
React is a UI library created by Facebook. It helps you create interactive web applications made up of&nbsp;**components**. If you’re familiar with HTML, you can think of components as fancy custom tags. That’s pretty much what they are: reusable bits of content and behavior that can be put on a web page.

A&nbsp;**component**&nbsp;is written as a plain JavaScript function. And this is real JavaScript here, not a template language. React supports a special syntax called JSX, which looks a lot like HTML, but it is turned into real JavaScript code by a compiler.

A web page is made up of components laid out in a nested “tree” structure. Just like HTML elements can contain other elements, React components can contain other components (and native elements like&nbsp;`div`s and&nbsp;`button`s). But these components are functions, remember, and they can be passed data to display.

One of the defining features of React is the idea of&nbsp;**one-way data flow**, and this was a big part of what set React apart when it first came out in 2013. These days, lots of other libraries (like Vue, Svelte, and Angular) have adopted the one-way data flow pattern too.