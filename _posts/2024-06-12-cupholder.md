---
layout: post
title: car cupholder extension
date: 2024-06-12 12:00:00
description: for fitting large water bottles in small spaces
categories: 3Dprinting
thumbnail: assets/img/cup3used.jpg
images:
  compare: true
  slider: true
---

My water bottle is ever so slightly too big to fit in my car's cupholder, as seen below. I love my water bottle (even if it may be a little large) and needed to adapt this so that I could bring it everywhere securely.

<div class="row">
    <div class="col-sm">
        {% include figure.liquid loading="eager" path="assets/img/cupbottle.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The circle peg does not actually fit in the circle hole.
</div>

My first solution was to try and perfectly map the unusual shape right above the cupholder. Then I could create a cupholder on top of this plane and place my bottle there!

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/cuptopview.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/cup1alone.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/cup1used.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>
<div class="caption">
    The first cupholder solution I made.
</div>

This worked as far as I could tell! Until I actually drove with it and my water bottle tipped over on the first turn I took. This design sucked because there was nothing to counteract the bottle's inertia on turns and keep it in place. It also could only be used on one side unless mirrored and reprinted. That's why I redesigned it with a slightly different approach.

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/cup2alone.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/cup2used.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/cup2usedbottle.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/cup2useddrink.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>
<div class="caption">
    The second iteration of my cupholder solution.
</div>

This design proved to not only be much better, but was also much easier to design. Mapping out the cupholders unusual shape was difficult, but making cylinders is simple. As seen in the pictures above, smaller drinks still fit in the cupholder as well! This was much, much better but there was still one change I wanted to implement.

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/cup3iso.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/cup3side.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/cup3used.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/cup3usedbottle.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>
<div class="caption">
    The final iteration of my cupholder.
</div>

In this iteration, I implented slots so that the cupholder's original tabs would still work on smaller drinks and additionally keep the cupholder extension from coming out. I increased the thickness of the upper section's walls to add stiffness, as the previous version's walls were a tiny bit flimsy. Overall, I'm pretty happy with how this cupholder turned out and plan to keep it in my car for a long time.