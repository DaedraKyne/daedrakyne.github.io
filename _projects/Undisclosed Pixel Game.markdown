---
layout: project
title: GPU Pixel Simulations
project-type: 4th-Year Thesis Project
categories: C# GLSL(Shader-Programming) Unity
year: 2023
links: []
# {name: Final report, href: "https://drive.google.com/file/d/1FEpNo7-92uGZv6gBoDTsEIz4tg0XtvTf/view?usp=drive_link"}
# Warning: MAKE SURELINKS DOES NOT HAVEAN EXTRA COMMA!!!! Sebastien

importance: 5

image:
  type: video
  path: "/images/water_islands_3d.mp4"
  thumbnail: "/images/water_islands_3d.mp4"
  autoplay: true

slideshow:
  [
    {
      image:
        {
          type: video,
          path: /images/raytrace_demo.mp4,
          autoplay: true,
          caption: "Custom voxel path-tracer incorporating reflection, refraction, and volumetric depth.\n\n The cube shown is a collection of refractive dark-grey blocks, coloured light blocks, green mirrors and purple glass.",
        },
    },
    {
      image:
        {
          type: video,
          path: /images/pixel-game.mp4,
          autoplay: true,
          caption: "A 2D water simulation - the water attempts to spread itself equally after losing its momentum.\n\n The terrain is uneven, being lower in height at the center.",
        },
    },
    {
      image:
        {
          type: video,
          path: /images/flowing_water_2d.mp4,
          autoplay: true,
          caption: "An early attempt at 2d water simulation. The attempts to become ubiquitous after losing its momentum.",
        },
    },
    {
      image:
        {
          type: video,
          path: /images/water_islands_3d.mp4,
          autoplay: true,
          caption: "The current state of the water simulation branch.\n\n A full 3D upgrade to the depth-affected 2d simulation. \n\n Runs at 200fps on 150k cells.",
        },
    },
    {
      image:
        {
          type: video,
          path: /images/pixel-game-fire.mp4,
          autoplay: true,
          caption: "A 2D first simulation - the first simulation I made.\n\n Simple logic that spreads fire forwards and fades.",
        },
    },
  ]
---

Solo-made Pixel-Simulated Game running on the GPU, inspired by Noita and Minecraft. (top-down)<br>
Main tech used is compute shaders, to ensure high efficiency with large maps.
