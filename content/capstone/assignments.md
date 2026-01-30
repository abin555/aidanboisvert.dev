---
title: "Assignments"
---

## Intro to AI - Stock Trader Bot
![Stock Bot In Action](/capstone/StockBot.png)

In my Junior year, I took a course called Introduction to Artificial Intelligence. One of the projects that I was most proud of was a genetic algorithm to perform stock market trading. It used several possible algorithms, such as Sample Moving Average (SMA) or Exponential Moving Average (EMA). Each agent has a genetic sequence which represents their favoring towards and logic about the available averages. I implemented the AI agent and environment in C, pulling historical stock market data from the internet.

The genetic algorithm worked quite well, and was fairly performant. Overall, I was quite proud of my work here. It may not have been the most sophisticated AI agent, but for one of my first forays into the field, it was very educational and enlightening. I don't think I'd like to work in the AI industry, but the technology was worth learning.

## Software Engineering 1 - Text Adventure Game
![Text Adventure Game](/capstone/TextGame.png)

Also in my Junior year, I took Software Engineering 1, where we created a text adventure game in Java while (attempting) to fully follow Agile design tenants. While Agile was nominally an important part of the course, I didn't care so much about that. More important to me was the use of Maven as a build system, implementing audible context sounds as the story progresses, and slow typing.

This may seem like a bit of a more boring project, but this was one of the first cases where I've had to work on a (moderately) large project with other people. This was a bit of a challenge at first, because my group was made up of people with a variety of different skill sets and abilities. Additionally, the academic excercise of writing a properly designed Object-Oriented Program in Java using Agile, was intriguing.

## Operating Systems - Custom Network Stack (For my own OS)
![Greenwood OS](/capstone/GWOS.png)

Last semester, during the Fall of my Senior year, I took Operating Systems. For an honors contract, I decided to implement a rudimentary network stack for the custom OS I had been slowly building over the past few years. It implemented ethernet drivers, several protocols like TCP/IP, UDP, and ICMP, as well as DHCP and HTTP. It required massive amounts of research, effort, and reworking of existing systems in the OS. But, it worked, and I implemented a simple ping application, http client, and download utility.

The photo above shows the ping application's output in the terminal, and an editor window open showing its source code. This project felt like a culmination of several years of intermittent effort in a project that was driven by the ethos "that looks hard, lets do it." And through the application of work and time, I was able to create a functional networking interface. It has a few issues, and I wouldn't call it a good system, but it does work, and I am quite proud of it.

## Intro to Embedded Systems - Tetris
![Tetris Schematic](/capstone/Tetris.png)

Also last semester, I took Introduction to Embedded Systems and its associated lab. For the final project in the course, we were to build an embedded game, such as pong, frogger, or in my case, Tetris. There are only three requirements beyond the game, it must use the small OLED screen (128x64 pixels), use the joystick, and use the ATTiny1627 microcontroller. I ran into an interesting issue with the Analog Digital Converter, causing random resets of the MCU. I was not able to determine the precise cause, but I bypassed it by using two OPAMPs to create a digital signal representing the position of the joystick. Then, just had to implement Tetris, and it was genuinely quite fun.

This project was actually very meaningful to me, it took several weeks to put together, and lots of trial and error (for the Joystick), but I was able to pull it off. Above is a picture of the schematic I created to document how the embedded system was put together. I view this as one of the few projects I've done that actually fully uses both parts of my degree plan, software development, and electrical engineering. 