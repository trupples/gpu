# OpenGL ES 2.0 capable graphics card project

## Why?

Since I was a kid, I've been passionate about digital logic design, having been introduced to minecraft redstone computers around when I was 13, and then sucked into the wormhole of DIY computers in the likes of Ben Eater's, James Sharman's, and many others'. This year, I took part in the Digilent Digital Design Club at my University, which got me a long overdue introduction to VHDL. One of the main projects of the club was a one triangle rasterizer, which rebirthed a project idea I had a while ago to build a distributed graphics processor (its initial intent was to be used as an emulation challenge for XMAS CTF). My initial idea was to have a system with many small cores able to execute some compiled form of fragment shaders (see the kind of demos found on shadertoy), but I later decided to implement a more versatile API, and finally chose OpenGL ES 2.0 because I think it strikes an industry-proven balance between ease of implementation and ease of use. Here we go!

## Outlook

This endavour will be split into three parts:
- An OpenGL ES 2.0 library / driver - converts C calls to graphics commands
- A software implementation of the backend
- A VHDL implementation of the backend

I will initially develop the first two components concurrently, with the aim of correctly rendering OpenGL ES 2.0 demos such as: https://www.youtube.com/watch?v=qZg3kbj6ZaY





