---
layout: project
type: project
image: img/replit.png
title: "RPG Simulation"
date: 2021-05-05
published: true
labels:
  - Java
summary: "A simulator written in Java that runs 100 matches between 2 characters."
---

When I was taking AP Computer Science A in high school, the biggest assignment we had over the year was the RPG project. The goal of this project was to showcase our understanding of object oriented programming, class hierarchy/inheritance, and just Java programming as a whole. This was achieved by creating 3 RPG classes (Mage, Assassin, Swordfighter) which all derived from a parent class called "Classes" and each class is given stats (health, armor, damage) that are represented using instance variables. To create diversity, each class was given a special move and unique stat values. 

Since all classes differ from one another, the ultimate end goal of this assignment was to make sure that no class was significantly stronger than another. To verify this, we had to pair each class with every other class and have them fight one another in 100 battles. If both classes were to have a winrate between 48% to 52% (inclusive), then we can conclude that we have minimized balance issues. If not, we would have to tamper with the stat values until we get satisfactory results. 

All of this was done in repl.it, a free browser IDE.
