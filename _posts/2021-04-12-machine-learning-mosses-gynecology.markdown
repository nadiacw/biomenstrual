---
layout: post
title:  "Machine learning, mosses, and gynecology"
date:   2021-04-12 12:00:00 +0200
categories: reflections
excerpt_separator: <!--more-->
author: by Marie Louise Juul Søndergaard
---

![](/menstrual-care-blog/assets/images/GyneGEN_gallery.jpeg)
<span class="caption">GyneGAN</span>

This blog entry is documenting early design explorations of how machine learning could be used to attend to more-than-human and multispecies menstrual care. ML and AI are not innocent technologies. Rather, as revealed by e.g. Kate Crawford and Joy Buolamwini, the material infrastructure of ML/AI are damaging the environment, and the embedded bias and logics are perpetuating social inequality through sexist and racist recommender and face recognition systems. By using ML in design explorations with menstrual care, I seek to both disentangle and grasp these politics and — if still possible — imagine feminist and more-than-human utopian uses and applications of ML for purposes that nurture both society and planet.

<!--more-->

In a three-day ML/AI workshop ([https://github.com/auduno/aho-ml-workshop-v21](https://github.com/auduno/aho-ml-workshop-v21)), facilitated by Audun Mathias Øygard @auduno, I explored how machine learning could support the curiosities and entanglements that we are interesting in thickening in the multispecies menstrual care project.

The machine learning tools include: [ml5.js](https://ml5js.org/), [teachable machine](https://teachablemachine.withgoogle.com/), [RunwayML](https://runwayml.com/), and [Artbreeder](https://www.artbreeder.com/browse). 

## Moss classifier

I’m building a moss classifier! A tool that can help you recognise and name specific moss species local to Stockholm. Looking through the camera, and with the support of a machine learning model, the moss classifier assists you to find that one specific moss — for instance sphagnum moss — which is great for menstrual products, or it accompanies you in discovering the multitude of mosses that make up the carpet of the forest, a revitalising activity of pure enjoyment.

Building the moss classifier entails several steps:
1. Gathering mosses in forests around Stockholm
2. Training a machine learning model, through the teachable machine tool, to recognise and classify gathered mosses, through an image archive of mosses
3. Designing the moss classifier interface and tool in ml5.js

<div style="padding:97.83% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/535826376" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


## GyneGAN
I trained a StyleGaN2 machine learning model on 914 images of gynecology tools from Norwegian museum archives ([digitaltmuseum.no](http://digitaltmuseum.no)) for 1999 steps in one hour with Runway ML. After that, I generated a latent walk video of the training model, which resulted in some creepy steel tools morphing into a car. The mesmerising slow aesthetics of these mundane yet anxiety-inducing tools perhaps tells us something about the violent and oppressive histories of gynaecology care as it has been performed on women, yet leaves it open how we could design care objects differently.

<div style="padding:100% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/534910928" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Blood moss
I used Artbreeder to morph images of moss and blood into new constellations. This creative tool allows you to gain more control of the generated images by tuning different parametres in the StyleGEN2 model.

![](/menstrual-care-blog/assets/images/bloodmoss_1.png)
![](/menstrual-care-blog/assets/images/bloodmoss_2.png)


These early examples seek to open new pathways for thinking-with machine learning systems in the context of multispecies menstrual care. It’s an exploration of using more-than-human imagination to ideate and visualise how menstrual care could be practiced in ways that nurture more-than the human body, for instance through the practice of gathering sphagnum moss for menstrual products.


A remaining point for continuous reflection and critique is that ML models generate future images/decisions/predictions built on the past and that its planetary costs are high in terms of energy use and material resources. Could we, then, use ML to both tell the story of oppressive pasts as well as imagine more socially just futures? And could we both use AL systems of which planetary costs are high, to build and regenerate environmentally flourishing practices, rituals, tools or objects?
