# Pyramid Loader

## Overview

The **Pyramid Loader** is a custom animated component designed for the website **Famesmisth.com**, an advertising company. This component features three pyramid-shaped loaders that rotate continuously, creating an engaging visual effect. The loaders are implemented using HTML and CSS, utilizing 3D transformations and animations.
![image](https://github.com/user-attachments/assets/f5619169-76cc-45af-aa71-75245347ca1a)

### HTML Structure

The HTML file includes the following structure for the pyramid loaders:


### Description
.pyramid-container: A flex container that holds all the pyramid loaders, aligned in a row with no gaps.

.pyramid-loader: A block representing each individual loader. There are three loaders with different sizes and animations.

.wrapper: A container for the sides of the pyramid. It is animated to create the spinning effect.

.side: Represents each side of the pyramid. There are four sides per loader, each styled to create a 3D pyramid effect.

.shadow: Represents the shadow beneath the pyramid to give a sense of depth.

### Description
Container Styles:

.pyramid-container: Uses flexbox to center the loaders. The gap property can be adjusted to increase or decrease spacing.
Loader Styles:

.pyramid-loader: Each loader has a rotateX(80deg) transformation to give a perspective view.
Sizes:

Loaders have different dimensions (loader1, loader2, loader3) to create visual variety.
Animation:

The spin animation rotates the .wrapper elements around the Y-axis, creating a continuous spinning effect.
Side Styles:

Each side of the pyramid uses clip-path to create a triangular shape and is styled with linear gradients to enhance the 3D effect.
Shadow Styles:

Shadows are positioned and blurred to add depth to the loaders, enhancing the 3D appearance.
Usage Notes
To implement the Pyramid Loader, simply copy the HTML structure into the desired location in your webpage and include the CSS styles in your stylesheet.

You can customize the colors and sizes by modifying the gradient values and width/height properties as needed.

Ensure that the containing element has enough space to accommodate the loaders, especially since the animation may change their appearance.
