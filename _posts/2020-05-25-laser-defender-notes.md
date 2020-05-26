---
title: "Laser Defender: Notes"
date: 2020-5-25
categories:
  - General
tags:
  - Unity Game
---

Maybe have a try before you read! Please click [here](https://taichifox95.github.io/general/laser-defender/).

Some notes:

## Enemy Spawner

It's an empty object that takes in an array of waves. It recursively uses IEnumerator to start coroutines that calls waves objects. Each wave object includes the prefab enemy,  and a path prefab; a path prefab basically stores transforms.

It's really complicated in terms of structure, however it allows people generate waves without touching the code. I guess that's the point of a game engine.



## Particle system

For the first time we used some particle system. 