---
layout: page
title: "Demo"
meta_title: "Demo test page"
subheadline: "Wufoo-powered contact forms"
teaser: "Get in touch with me? Use the contact form."
permalink: "/demo/"
image_sliders:
  - slider1
  - slider2
  - slider3
---
demo test

[View the Markdown source for this page](https://raw.githubusercontent.com/jekylltools/jekyll-ideal-image-slider-include/gh-pages/examples.md)

[View the slider settings in `_data/sliders.yml`](https://github.com/jekylltools/jekyll-ideal-image-slider-include/blob/gh-pages/_data/sliders.yml)

## slider 1

settings for this slider taken from [Ideal-Image-Slider-JS#getting-started](https://github.com/Codeinwp/Ideal-Image-Slider-JS#getting-started)

{% include slider.html selector="slider1" %}

## slider 2

same images, different settings.

{% include slider.html selector="slider2" %}

## slider 3

same images, minimal settings, no bullets, no captions, no navigation

{% include slider.html selector="slider3" %}