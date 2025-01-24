---
author: Zhicong Lu
comments: true
date: 2014-06-15 11:34:28+00:00
layout: post
slug: portfolio-others
title: 'Programmable Camera'
img: /assets/img/camera2.jpg
importance: 1
related_publications: false
category: work
---

<h3><b>CONCEPT</b></h3>
<p>The Aesthetics Oriented Programmable Camera is a media for photography, that intends to break the current photography art form and extend the artist-audience and artist-artist relation.The AOP Camera is a media that artists can create their own cameras. They embed their ‘style’ in the camera, and make the stylized photograph with it. Audiences can appreciate the artist’s work by making their own photographs with the same camera. The camera itself is also an intelligent system with computer vision and feedback capability that sense and interact with the physical world. So with the style firstly defined by an artist, plus the audience’s own thoughts and composition of the subject, and finally added by the instantaneous processing of the camera, AOP Camera introduces a series of creativity that brings photography to a new level.</p>
<h3><b>Flash Module Design</b></h3>
<p>The first modual to build the platform is a camera with a ‘programmable flash’. We use a high lumen projector and a automated shutter to simulate the flash. Since it is actually a projector, it can project any content at the artist’s will. As stated before, the camera need to sense the scene every time it takes a picture. By using a method called structured light modelling in computer vision, the camera acquires the 3D information of the scene. In portrait photography application, we add a face model(STASM) to the camera, so that it can do face feature detection.</p>
![Camera Image 1]({{ site.baseurl }}/assets/img/camera1.jpg)
<h3><b>APPLICATION</b></h3>
<p>Together with artists, we created three different styles, namely the Virtue Lighting, Digital Makeup, and Lighting Collage.</p>
<p><b>Virtue Lighting:</b></p>
<p>This style is made for portrait photography. The artist set up the light environment in a virtual space, and render the lighting effect on human face. Afterwards, the projector ‘flash’ the effect onto the subject, so that the final photograph looks as if there is a real light.</p>
![Camera Image 2]({{ site.baseurl }}/assets/img/camera2.jpg)
<p class="p1"><span class="s1"><b>Digital Makeup:</b></span></p>
<p class="p1"><span class="s1">This style is made for portrait photography too. Artist will often need to do makeups on models, this style simulate the makeup effect and flash it onto the model.</span></p>
<h3><b>IDF 2013 SAN FRANCISCO</b></h3>
<p>The Aesthetics Oriented Programmable Camera was honored to exhibit in IDF(Intel Developer Forum) 2013 in San Francisco. During the forum, it was very popular and highly spoken of by Intel and the media.</p>
<h3></h3>
<h3><b>RESEARCH PAPER</b></h3>
<p>A research paper (in Chinese) is written on this project, and was published on Issue 10, Journal of Decoration, 2014:</p>
<b>Smart Flash: No Longer Just a Plain Flash, A Prototype of an Active Style Camera</b><br />
<p>Abstract: <em>Traditionally, cameras just record a scene from the perspective of the photographer, with only minor modifications of lighting performed by the flash. We propose an Active Style Camera, which actively augments the scene, adding a new dimension to the photography experience. The prototype, Smart Flash, implements this concept. Using a projector with an auto-controlled shutter, Smart Flash actively evaluates the scene and augments it by “flashing” a projection of photographer-defined simulated effects onto the real world. The simulated effect settings can be stored as a “style” that can be shared digitally with other photographers. Other users can download any of the “styles” to their own Active Style Camera and apply them to different scenes. In our experiment, we tested virtual lighting and digital makeup effects for portrait photography. Feedback from professional photographers, average users, and portrait subjects is discussed in the user study.</em></p>
<h3></h3>
<h3><b>IMPLEMENTATION</b></h3>
<ul>
<li>structured light 3D modelling (C++,openCV)</li>
<li>face model (STASM)</li>
<li>pro-cam system (C++,openCV)</li>
<li>shutter controlled by Arduino</li>
<li>graphic interface (Qt+OpenGL)</li>
</ul>
