---
title: Full Bloom
layout: base.njk
tags:
  - gallery
  - image
  - flowers
img:
  src: /images/jennifer-marquez-WW-TIGWKCyc-unsplash.jpg
  alt: person with dried flowers in front of face
  title: Full Bloom
  location: unknown
  date: April 10, 2021
  credit: 'Photo by <a href="https://unsplash.com/@jamscreativephotography?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jennifer Marquez</a> on <a href="https://unsplash.com/@jamscreativephotography?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>'
  description: Portrait of a person with decorative eye makeup behind branches with yellow blossoms.
---
<h1 class="pageTitle">{{title}}</h1>

<div class="image">
 <img src="{{img.src}}" alt="{{img.alt}}">
</div>
<div class="image-info">
    <p class="location">Location: {{img.location}}</p>
    <p class="date">Date: {{img.date}}</p>
    <p class="credit">{{img.credit | safe}}</p>
    <p class="description">{{img.description}}</p>
</div>

