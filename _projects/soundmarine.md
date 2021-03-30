---
permalink: /soundmarine/
title: "Soundmarine"
header:
  image: /assets/images/soundmarine-1.png
  teaser: assets/images/soundmarine-1.png
---

Soundmarine came out as the short (actually, very short) music-driven game-experience. We decided to try to make a game in a distinct visual style reminiscent of the works of Jean Giraud aka Moebius.  

<iframe width="560" height="315" src="https://www.youtube.com/embed/GdnfOiPtmDg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  

**The idea on paper.** The player starts steering the submarine on a barely filled screen (the objects are in outlines only), in complete silence and collects sound-emitting objects resulting in a semi-random musical piece. The sounds are fading and you have to keep picking them to stay afloat. The world around gradually becomes more dense. Then there is a board with all the sounds in the end menu that you can switch on/off.

![](https://staging.dustyroom.com/assets/images/soundmarine-1-29570.png)  

**The process.** The biggest chunk of process was the work on shaders, particularly outlines. Also the controls and camera movement took a lot of time too. Models had to be created with this shading in mind as lots of outlines depended on vertex colors and normals of the meshes. The sound layers and sfx were done in the last day in under three hours.  

![](https://staging.dustyroom.com/assets/images/soundmarine-2-29575.png)  

**The results.** _The visual look_ came out mostly nice. The outlines were unfinished, however. We wanted to make them a bit more ‘chewed’, as in art of Moebius. The rendering of outlines was not equal on different platforms. In fact, we tested the game on Windows only two days later, just to discover that there is no lines at all! We managed to fix that now.  

![](https://staging.dustyroom.com/assets/images/soundmarine-3-2957a.png)  

_The performance_ was lagging a bit. It was due to literally millions of vertices on the scene. Luckily there are such things as dynamic occlusion and LOD (Level of Details) in Unity, which saved us a few FPS.  

_The music layers_ are ~40 sec long stems synced at the start. Each buoy unmutes a new layer. There are 15 of them, created to sound OK together and in isolation. Looking back, stacking some of the random layers came out too subtle.  

![](https://staging.dustyroom.com/assets/images/soundmarine-4-2957b.gif)  

_The gameplay_ in a jam version is a bit bare. There were bugs when the submarine floats away from the view. The pick-up buoys were manually distributed in a random fashion in the last hours of the jam. We are working on a post-compo version (WebGL version too) with more obstacles, which should liven up the game a bit.  

Check out the game or watch a video (which is basically a whole gameplay in less than 3 min).  

By the way, if you like the music from the game, you can find the album version of it in album [Colorspacious](http://dustyroom.com/colorspacious-album/) by Polygrim (one of us who does audio), the track in this record is called ‘Oceanic’.  

[Game Entry on LD Jam 45 page](http://ldjam.com/events/ludum-dare/45/soundmarine)  
[Soundmarine on itch.io](http://dustyroom.itch.io/soundmarine)  