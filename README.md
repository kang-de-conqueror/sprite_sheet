# Sprite Sheet

## Project Description

A sprite is a small raster graphic (a bitmap) that represents an object such as a character, a vehicle, a projectile, etc.

Sprites are a popular way to create large, complex scenes as you can manipulate each sprite separately from the rest of the scene. This allows for greater control over how the scene is rendered, as well as over how the players can interact with the scene.

Sprites are mainly used in 2D video games, such as Shoot'em up in which the hero combats a large number of enemies by shooting at them while dodging their fire.

## Project Goal

- Waypoint 1: Find the Most Common Color in an Image
- Waypoint 2: Write a Class Sprite
- Waypoint 3: Find Sprites in an Image
- Waypoint 4: Draw Sprite Label Bounding Boxes
- Waypoint 5: Write a Class SpriteSheet
- Waypoint 6: Package and Distribute the Python Library

## Project Benefit

Three main features of this project, more useful in Computer Vision:

- Find the Most Common Color in an Image
- Find Sprites in an Image
- Draw Sprite Label Bounding Boxes

It can split your image with many sprites and you can improve it to work in Computer Vision.

## Technology

- Python (PIL, Numpy)

## Project Team

- Lam Khang Tran

## Feature

### Find the Most Common Color in an Image

Returns the pixel color that is the most used in this image.

### Find Sprites in an Image

Returns a tuple (sprites, label_map) where:

- sprites: A collection of key-value pairs (a dictionary) where each key-value pair maps the key (the label of a sprite) to its associated value (a Sprite object);

- label_map: A 2D array of integers of equal dimension (width and height) as the original image where the sprites are packed in. The label_map array maps each pixel of the image passed to the function to the label of the sprite this pixel corresponds to, or 0 if this pixel doesn't belong to a sprite (e.g., background color).

### Draw Sprite Label Bounding Boxes

Draws the masks of the sprites at the exact same position that the sprites were in the original image. Draws each sprite mask with a random uniform color (one color per sprite mask). Also draws a rectangle (bounding box) around each sprite mask, of the same color used for drawing the sprite mask.

## Usage

### Install packages: pillow (PIL), numpy, python 3.7.4

You have to install packages above:

```bash
pip install pillow
```

and

```bash
pip install numpy
```

### Install New Python 3.7.4

Go to this link and download new python version: https://www.python.org/downloads/

### Install my package

```bash
pip install spriteutilkangkang
```

## Contact (Author & Maintainer)

- Name: Khang TRAN
- Email: haphongpk12@gmail.com
- Facebook: https://www.facebook.com/haphongpk12
- Phone: (+84) 909 77 8046
