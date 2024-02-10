---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# Education

<p style="align:left">
    <b>University of Southern California</b>
    <span style="float:right">01/2022 -- 12/2023</span>
</p>
<p style="align:left">
    <i>Master of Science in Computer Science</i>
    <span style="float:right">Los Angeles, California</span>
</p>

<p style="align:left">
    <b>Peking University</b>
    <span style="float:right">09/2017 -- 07/2021</span>
</p>
<p style="align:left">
    <i>Bachelor of Science in Computer Science</i>
    <span style="float:right">Beijing, China</span>
</p>

# Experience

## Graphics Programmer Intern At The-Forge

<html lang="en" class="no-js">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">

	<link href='http://fonts.googleapis.com/css?family=Open+Sans:400,300,700' rel='stylesheet' type='text/css'>
	
	<link rel="stylesheet" href="assets/css/style.css"> <!-- Resource style -->
	<script src="assets/js/modernizr.js"></script> <!-- Modernizr -->
	
	<title>Image Comparison Slider | CodyHouse</title>
</head>
<body>
	<figure class="cd-image-container">
		<img src="images/before.jpg" alt="Original Image">
		<span class="cd-image-label" data-type="original">Original</span>

		<div class="cd-resize-img"> <!-- the resizable image on top -->
			<img src="images/after.jpg" alt="Modified Image">
			<span class="cd-image-label" data-type="modified">Modified</span>
		</div>
	
		<span class="cd-handle"></span>
	</figure> <!-- cd-image-container -->
  <script src="assets/js/jquery-2.1.1.js"></script>
  <script src="assets/js/jquery.mobile.custom.min.js"></script> <!-- Resource jQuery -->
  <script src="assets/js/main.js"></script> <!-- Resource jQuery -->
</body>
</html>


## Gameplay Engineer Intern At Tencent

<iframe width="560" height="315" src="https://www.youtube.com/embed/75RZiVnQTMs?si=quVvE3g910lAlMNv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

- Developed two mini games named [*Destroy Blocks*](https://drive.google.com/file/d/1p-Irq4oTw_zVFyyB4XbyJB7pNv7R-LcW/view?usp=sharing) and [*Jelly Warrior*](https://youtu.be/75RZiVnQTMs?si=43WYhWSJryIFql4n) with Unreal Engine

- Simulated elastic objects using three methods: mass-spring system, position-based dynamics and finite element method

# Project


## Game Engine Development

- Reduced draw calls by culling invisible game objects whose bounding boxes are outside view frustum
- Added physics components by simulating collisions with intersection tests based on game object bounding volumes
- Implemented a particle system that supports sequence frame animation to simulate flame effects ([demo](https://drive.google.com/file/d/1wKoV40oviNj0bW6BNq1i-rOeytk9_q_I/view?usp=sharing))
- Performed euler angles and quaternion Bezier spline interpolation on motion-captured keyframes ([demo](https://drive.google.com/file/d/1_ymHlso5JFII_XviUKM6LPGwG7EUYZHJ/view?usp=sharing))

## GzRenderer

- Programmed a soft renderer, including vertex transformation, rasterization, Phong shading and anti-aliasing
- Implemented a [metal shader](https://drive.google.com/file/d/1SFvnUmWjcF4UZqRzPTeaLTfTPFFlSwBe/view?usp=sharing) by combining physically-based BRDF models with image-based environment lighting

## A Roller Coaster Simulation

- Generated tracks procedurally from given points, and performed Phong shading to make track realistic
- Derived real-time position and direction of roller coaster and adjusted camera accordingly ([demo](https://drive.google.com/file/d/1tqbrImyZLrQsJpeCHQ9YSH3eqp98QVeE/view?usp=sharing))

## Geometry Aware Progressive Photon Mapping

- Wrote CUDA kernel to reduce radius based on chi-square test of photon distribution in progressive photon mapping
- Performed kernel estimation based on Voronoi diagram and accelerated using CUDA-written jump flooding algorithm
- Improved progressive photon mapping scheme to eliminate boundary bias and topology bias existed in standard scheme

<center><img src="images/box.png" width="800"></center>

<center><img src="images/boxDetail.png" width="800"></center>

## Real-time Realistic Rendering System for VR helmets

- Implemented photon mapping with OptiX engine and CUDA to generate realistic images for VR devices
- Originally proposed photon collection method based on shared memory of GPU, accelerating rendering by about 10%
- Exploited correlation between eyes to optimize calculation and reduced rendering time by around 15%

## Gesture Recognition with Deep Learning

- Built a residual network with over 150 layers using Python's Keras library to recognize static gestures
- Improved accuracy from 95% to 99.17% through setting a learning rate scheduler and performing data augmentation

## VR Game Design with Unity

- Designed an FPS game with Unity and wrote scripts in C# for game objects such as weapons and enemies
- Utilized SteamVR plugin to allow players to interact with game objects via HTC Vive VR devices
