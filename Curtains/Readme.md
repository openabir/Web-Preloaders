# GSAP Curtain Reveal Animation 🎬
A smooth and performant splash screen animation that simulates a flipping counter and a "curtain opening" effect to reveal the main content. This project is built with HTML, CSS, and the GreenSock Animation Platform (GSAP).
> Note: This animation is optimized for desktop environments only. Mobile support is not currently implemented and will be introduced in a future update.

## Features
### Flipping Counter: 
A dynamic number counter that flips through several values before the main animation begins.

### Logo Reveal: 
The "Marvel Studios" logo text animates into view and then splits apart.

### Curtain Effect: 
Two overlaying blocks wipe away from the center, revealing the content underneath like a curtain opening.

### Smooth Hero Scaling: 
The background hero image smoothly scales into place as the curtains open.

### Performance Optimized: 
Uses GSAP's timeline for efficient, sequenced animations and caches DOM elements to prevent re-querying the document.

## Technologies Used
### HTML5: For the basic structure of the loader and content.

### CSS3: For styling, layout, and initial element states (e.g., hiding elements before they are animated).

### JavaScript (GSAP): The core animation logic is handled by the GreenSock Animation Platform (GSAP) for high-performance, complex timeline-based animations.

## Getting Started
To run this project locally, follow these simple steps.

### Prerequisites
You just need a modern web browser that can run HTML, CSS, and JavaScript.

### Installation
Clone the repository or download the source code.

```git clone https://github.com/openabir/Web-Preloaders.git```
Navigate to the project directory.


```cd Web-Preloaders/Curtain```
Ensure you have the following file structure:

```.```\
```├── index.html```\
```├── styles.css```\
```└── hero.jpg      <-- (Add your own hero image)```\

Open the index.html file in your web browser. That's it!

## Code Overview
- index.html: This file contains all the HTML elements for the loader (counter, spinner, logo, overlay blocks) and the main container with the hero image. It also includes the CDN links for GSAP and the final animation script.

- styles.css: This file sets up the initial visual state. It uses absolute positioning to layer the loader elements and sets initial properties like transform: translateY(100%) or opacity: 0 to hide elements before GSAP animates them into view.

- JavaScript (inline script): The core logic resides in a ```<script> ```tag within index.html. It uses ```gsap.timeline()``` to create a master timeline that sequences all the animations in a precise order for a seamless effect.

## License
This project is licensed under the MIT License. See the LICENSE file for details.