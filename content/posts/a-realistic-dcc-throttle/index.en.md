---
title: 'A Realistic DCC Throttle Inspired by Epoch IV - Driving the RENFE 269 at Home.'
date: 2025-03-02T07:35:00.000+02:00
draft: true
url: /2025/03/a-realistic-dcc-throttle.html
tags: 
- DCC
- throttle
---

I've always loved the look and feel of the RENFE 269. There's something deeply satisfying about the way those old electric locomotives from Epoch IV responded to the engineer's hands — the weight of the controls, the rhythm of braking and traction, the dance between tighten brake and release brake. After watching a cab ride video of a 269 in action, I found myself wondering — how could I bring that feeling home?

That question stuck with me until I discovered the ProtoThrottle — a brilliant piece of gear that recreates the feel of a real diesel cab throttle. It's a product made with love and intent, not just buttons and knobs. That was the spark I needed.

But I wanted to take a different path: to create something truly accessible. A DCC throttle for model railroading that captures the behavior and control rhythm of a classic Spanish electric locomotive, but that anyone with a 3D printer and a soldering iron could build themselves.

## So the goals for this project were clear:

### 1. Industrial Design That’s Practical and Printable  
The design needed to feel like a real control desk — not just another box with knobs. I sketched out a layout inspired by the 269's cab, but constrained myself to forms that could be printed on a common FDM printer. That meant smart angles, snap-fits, and using standard components for handles and levers.

### 2. Electronics With Common Components  
I wanted the electronics to be something you could assemble easy in the future. No proprietary boards, rare ICs or expensive rotary swithches that will be impossible to buy in two years. Just a jelly-bean micro and a screen — all easy to source, cheap, and hobbyist-friendly. 

### 3. Realistic Operation, Not Just Controls  
Software is where the soul lives. I didn’t want just a throttle and a brake lever. I wanted behavior. Things like:

- An idle state with real inertia, where nothing moves until the operator makes it move.
- I want the experience of building up pressure in the brake cylinders and releasing the brake slowly, letting the train roll.
- A traction motor controller with delay, notch simulation, and power surging under load.

By layering in these behaviors, it stops being just a control panel — and becomes a part of the simulation.

—

I’m still deep in development, but the foundation is laid. Once it’s ready, I’ll be publishing everything: 3D files, schematics, firmware, and build instructions. If you love Epoch IV electrics — stay tuned.

This isn’t just a throttle. It’s a homage.