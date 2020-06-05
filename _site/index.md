---
title: Jamstack trial
date: Created
tags:
    - home
    - welcome
    - info

---

# {{ title }}

**date:** {{page.date.toUTCString()}}

**by:** {{ pkg.author }}

<ul>
	{% for item in tags %}
<li> {{ item }} </li>
	{% endfor %}
</ul>

What is going wrong?

boom

The **JAMStack** is part of a family of techniques for creating sites called `serverless`, but those techniques can be a bit confusing.

In this course I'm going to show you how to create serverless sites using a static site generator called **Eleventy** and help you demystify the JAMStack.

We'll talk about what serverless is and why it can be faster and more secure than working with regular websites. We'll explore a **node.js** based platform called Eleventy that gives you a fantastic engine for creating JAMStack sites and apps.