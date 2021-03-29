---
permalink: /lowpoly-substances/
title: "Lowpoly Substances"
header:
  image: /assets/images/statickit-tapemachine-header-1.jpeg
  teaser: assets/images/statickit-tapemachine-header-1.jpeg
---

Lowpoly Substances is a set of shaders, materials and models that make stylized animations of fire and water (more substances to come). With Lowpoly Substances you can add stylish animated elements to your game without sacrificing performance.

Features include:
  * Performance: vertex shaders are very fast, this way of animation is much faster than particles
  * Cross-platform: the effects work on all platforms, including mobile and WebGL
  * Easy integration: drop one of the included prefabs and you’re done
  * Customizable: animation shaders expose many parameters if you would like to change the animation
  * Complete: the package includes different models of low-poly substances (and all additional models in demos)
  * Flexible: the shaders and materials can be used on your own objects too
  * Free updates

Watch the video of the demo scenes and noodling with the shaders included in the asset pack…  

[![YouTube — Lowpoly Substances Demo]()](https://youtu.be/hUS8_1_FMpk)


We included many general as well as more specific fire and water models in the asset (camp fire, candle fire etc). Also lots of useful presets of the materials (with the shaders on them) are ready to be dropped onto the models.

![](https://staging.dustyroom.com/assets/images/lowpoly-substances-web-post2.png)  
![](https://staging.dustyroom.com/assets/images/lowpoly-substances-web-post.png)  

The materials are highly adjustable. You can make two completely different fires using two (or more) copies of one fire prefab with two materials on each of them.  

![](https://staging.dustyroom.com/assets/images/lowpoly-substances-web-post3.png)

**Here is how to apply the shaders to any object:**

1. Add a model of fire or water to the scene (or any object for that matter)
2. Create a new material or duplicate one in the Materials folder of the asset
3. In the shader property of the material select either LowpolySubstances\Fire or LowpolySubstances\Water
4. Expand the shader properties at the bottom of inspector and tune the parameters to your taste. This step is shown [here](https://youtu.be/hUS8_1_FMpk?t=47s)

We didn’t describe all the parameters with text, because it’s tricky to do that for some of them. We think would be quicker for users to turn each parameter on/of and see what it does than read lengthy text. If you need the explanations however, we can make them.

One thing worth explaining about the fire shader is the particles (small sparks that regularly fly out and go up). If you want to have them on your own model, you need to make sure the following requirements are met:
1. Add small separated pieces of mesh to your model, those pieces will be animated as particles of fire. Usually you don’t want many particles in this case.
2. All the particles have to be above the main fire piece of mesh.
3. All those particles have to be in separate quadrants of the XZ plane. It means they shouldn’t be crossed by any axes (see picture below).
Sounds tricky, but it’s the easiest way to make such particles work in vertex shader. You can of course just use our models that are all set up, or turn off particles for your models by unchecking “Enable particles” in the Fire shader parameters.

![](https://staging.dustyroom.com/assets/images/lowpoly-fire-instructions.png)

[Campfire Demo (WebGL)](http://dustyroom.com/lowpoly-substances/demo1/)  
[Customization Demo (WebGL)](http://dustyroom.com/lowpoly-substances/demo2/)  
[Get Lowpoly Substances at Unity Asset Store](https://assetstore.unity.com/packages/slug/57242?aid=1101lHzQ)  
