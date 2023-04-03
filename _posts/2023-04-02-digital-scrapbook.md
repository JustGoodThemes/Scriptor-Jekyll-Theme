---
layout: post
title: "Digital Scrapbooking With A Joystick and an Arduino ESP-32"
description: "Upload your vacation photos and try out this digital scrapbooking project using an Arduino ESP-32 and a joystick!"
date: 2023-02-03
feature_image: images/digital-scrapbook/scrapbook-example-1.png
tags: []
---

For this project, I used an Arduino ESP-32 to read data from a joystick and button. Using this setup, the user can flip through an array of images uploaded to the software, move them around the screen, and set them where they want. When they are done, the software generates a PDF of their completed collage. See more below!

<!--more-->

[View this project on my GitHub](https://github.com/catherine-o-brien/module2)

# MY PROJECT

Being a computer science student, my peers are often surprised by how much time I spend in the English department. In fact, this year, I’ve taken more creative writing classes than computer science ones. I don’t see a lot of overlap of my classmates in those departments, which I’m sure won’t come as much of a surprise to many, but to me, these subjects aren’t as different as they seem. 

Poetry and programming are both fundamentally creative and generative pursuits, disciplines that allow me to create rather than consume. In the Age of Information, we have access to a huge base of knowledge in the very palm of our hands– and yet that often leads us to spend hours and hours a day devouring content online without making time for our own creativity. Writing and coding have both been ways for me to get out of that loop and to create more than I consume. 

For my first project with my ESP32, I wanted to combine my dual loves of poetry and programming. To do this, I wrote a simple program that prints the text of Sylvia Plath’s “Mad Girl’s Love Song”– but there’s a twist. The device first prints the text in its correct order, and then prints a scrambled version of the poem. This jumbling of Plath’s carefully curated words symbolizes her descent into madness through her life and through this poem, ultimately leading to her tragic death. By using the random number generator in \<cstdlib\>, the device creates a unique randomization of the lines each time it runs. 

If you’re new to the world of embedded systems and looking for a fun and creative way to start, this simple Arduino project is a great way to dip your toes in and learn the basics. Learn how to try this project out for yourself below!

<!--more-->

# MATERIALS

## HARDWARE

* **Arduino ESP-32 TTGO T-display** [like this one](https://www.amazon.com/LILYGO-T-Display-Arduino-Development-CH9102F/dp/B099MPFJ9M)
* **USB-C cord** (make sure that your cord support data transfer, not just power!) [see more about this here](https://www.dignited.com/50330/usb-data-cable-vs-usb-charging-cable/)
* **Joystick**
* **Button** 
* **Wires** Depending on your setup, you may need male-to-male, male-to-female, or female-to-female wires. My setup uses 7 male-to-female wires. 

## SOFTWARE

* **Arduino IDE** [download here](https://support.arduino.cc/hc/en-us/articles/360019833020-Download-and-install-Arduino-IDE) 
* **Processing IDE** [download here](https://processing.org/download)


# STEPS

## 1. Connecting the ESP-32 to the joystick and button with a breadboard and wires

## 2. Programming the ESP-32 to read and print joystick and button data numerically 

## 3. Using Processing to interpret the numeric joystick and button data

## 3. Making the enclosure

## 4. Finished product

Here is an example of a collage that I created with this software:
<img src="images/scrambled-poetry/TTGO-standard-display.png " alt="TTGO displaying green and red text of its factory settings." width="300"/>

And here is a video of how the software works!


# CREDITS

This project was completed for Module 2 of Mark Santolucito’s Creative Embedded Systems course at Barnard College. See more about the assignment and his work on his website [here](http://www.marksantolucito.com/COMS3930/spring2023/mod2)!