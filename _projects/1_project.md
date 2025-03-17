---
layout: page
title: LabEmbryoCam
description: with background image
img: assets/img/LEC-RENDER.png
importance: 1
category: work
related_publications: true
---

The brief: repeated observations of embryos distributed across a multiwell plate - simple!

The LabEmbryoCam - at its core, addresses this via economical optics, motion systems, and compute platform - in a small, modular footprint.

The LabEmbryoCam project has origins > 15 years ago when Oli was assembling off the shelf high-end components in new ways, controlled via MicroManager - an ImageJ plugin, to achieve this goal.

Fast forward to 2025 and we are manufacturing the LabEmbryoCam - in house, aided by 3D printing. 

The LabEmbryoCam includes a custom user interface, and strikes a great balance between quality of video, and size constraints.

Gone are the days of needing to reduce the size of an experiment to fit the size of your available harddrives.

For more details, checkout the 2024 paper in our published work, or our Github repository.

If you are interested in the LabEmbryoCam for your own research, it is an opensource technology. However, if you would rather have us build one for you - we also have you covered. Checkout www.phenomyx.co.uk - our Community Interest Company established to maximise the impact of technologies just like the LabEmbryoCam.

<div class="row">
     {% include figure.liquid loading="eager" path="assets/img/3D-printing-timelapse.gif" title="example image" class="img-fluid rounded z-depth-1" %}
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
