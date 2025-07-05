---
title: "DotSight"
author: "Aditya Venugopal"
description: "A single pixel camera"
created_at: "2024-07-04"
---

# July 4th: Made the projector thing work in Blender!

This project is to make a camera with just a single photodetector. (Inspired by: https://www.youtube.com/watch?v=dMH6VUs5u8k). Before designing and building the actual thing, I want to figure out how the code actually works. So I have decided to implement it using Blender and Python. First thing to do: Make a projector like thiing in blender. Got the thing to work. Got it to display pictures and videos. Can project images stuff onto objects now. Next would be to make a light sensor thing in blender using Python.

<img width="1671" alt="Screenshot 2025-07-04 at 11 02 20 PM" src="https://github.com/user-attachments/assets/5f4f7d59-891a-465e-a884-b22d60220d08" />
<img width="821" alt="Screenshot 2025-07-04 at 11 03 30 PM" src="https://github.com/user-attachments/assets/f0223f81-6cd5-42e1-b9a6-7d3d2b429c6e" />
<img width="767" alt="Screenshot 2025-07-04 at 11 03 45 PM" src="https://github.com/user-attachments/assets/ee06a6a0-e946-4730-a291-ff007bb421c6" />

**Total time spent: 1h**

# July 5th: Got a low-res version to work!
Started with implementing python scripts in Blender. Got a python script to generate a 4096 point scanning patterns, converted them to 30fps video, got the projector I made yesterday to project this video onto a 3d model of Doraemon to be scanned. Then a camera rendered each frame and the python script to calculate the sum of al pixel brightness in a given frame individually and reconstruct a image based on that data. Made it work with 64x64 low-res images. Will have to make higher res stuff tomorrow, along with prolly exploring Hadamard patterns.

![try6](https://github.com/user-attachments/assets/fff870d9-3946-4ffe-b4ce-232cc33b20ff)
![1try](https://github.com/user-attachments/assets/2822e4bf-3d7a-4086-aca2-2d219b2a42de)
![try4](https://github.com/user-attachments/assets/5db69613-703f-43a6-9bf0-3404b3ad63d6)
![reconstructed_image_from_frames](https://github.com/user-attachments/assets/698dde8d-a7e7-4d14-9ec2-258c3efa8226)
<img width="939" alt="Screenshot 2025-07-05 at 10 50 01 PM" src="https://github.com/user-attachments/assets/af74e302-bb7a-4eb4-854d-943528d2ceaa" />


**Total time spent: 3h**
