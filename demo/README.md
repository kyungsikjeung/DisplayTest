# FreeRTOS vs Bare-metal Animation Demo

This example uses **React**, **Tailwind CSS**, **Three.js** and **anime.js**. It visualizes the difference between a FreeRTOS system with context switching and a bare-metal super loop.

Open `index.html` in a modern browser to see the animation:

- **Left**: multiple cubes rotate sequentially to demonstrate task switching under FreeRTOS.
- **Right**: a single cube continuously rotates, representing a simple super loop with no context switching.

The animation is intentionally simplified for beginners.
