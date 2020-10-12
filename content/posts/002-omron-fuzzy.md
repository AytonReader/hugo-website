+++
author = "Paul Tomoiaga"
title = "Fuzzy Logic for PLCs - Omron Engineering"
date = "2020-10-12"
description = "I built a fuzzy logic library using structure text language."
categories = [
    "professional",
]
draft = false
+++

> While at Omron I worked to develop a fuzzy logic framework for Omron PLCs using Structure Text language.

## Context
From June, I spent three months working with Omron Australia as an engineering intern. I used my short time with Omron as an opportunity to build my professional network, and further put my name out as a professional contractor. I was fortunate enough to spend the first two months in-office, and got to know some of the Omron Melbourne staff on a deeper level. As well as completing PLC training, I worked on two larger projects:
  1. Building a PLC library to handle fuzzy logic.
  2. [Improving the UI for a bootstrapping software.](/posts/003-omron-vbnet)

# Fuzzy logic for PLCs
A fuzzy logic framework makes it easier to build smart, **reactive** PLC applications. In some cases, it can even be practical as an alternative to PID loops. This article does not dive too deep into what Fuzzy Logic is used for, or how it works. There are a number of videos on YouTube that will explain the details much better than I could. While at Omron I worked to develop a fuzzy logic framework for Omron PLCs using Structure Text language.

## Result
In the end, a real proof of concept was created. It was minimally valid, complete with all the necissary function-blocks to develop a fuzzy library, and defuzzify using a Centre-of-Gravity method. This project was a milestone for me, and a real proof of my adaptability. However, I wish I had more time to brute-force test the application. 

## Lesson: Design before writing code
You wouldn't build a bridge without a solid design, so why do we get so eager to start coding without a plan? It is incredibly important to write flow-diagrams and psuedo-code *before* writing computer code. The advantage to designing your program **on paper**, is in the fact you can abstract your code and look at the program flow from a high-level.

