### elam0704_9103_tut6
# Week 8 Quiz


**Part 1** 

###### While watching ‘Spider-Man: Into the Spider-Verse’, I was inspired by the use of rasterized elements in the animation. Several scenes utilize this technique to convey a sense of speed and the transition between different dimensions while maintaining a comic book aesthetic *[1]*. The unique approach adds depth and energy to the storytelling, making the visuals more engaging *[2]*.
##### After some further research, I discovered a coding tutorial on rasterizing images and integrating them into a 3D space *[3]*. I believe this method could be beneficial for the major assessment because it offers creative pathways to blend 2D drawings or animations within an interactive 3D space. This approach could potentially provide a dynamic and visually rich experience.
*(This paragraph was assisted with ChatGPT for clarity and grammar check)*

**[1]**
![An example of a 3d space in the Spiderman movie](images/Spiderman_image_1.jpg)

**[2]**
![Another example of a 3d space Spiderman movie](images/Spiderman_image_2.jpg)

**[3]**
![An example of a rasterized image to a 3D space](images/3D_space.png)

**Part 2** 

###### The following coding technique utilizes an image into a 3D space.
###### In p5.js, change the rendered mode to WebGL (Web Graphics Library) for a 3D rendering declared in the canvas size. The main functions to achieve the inspirations includes:

###### rotate(): Rotate image to view 3D effects (x/y/z-axis rotations) of rendered rasterized image.
###### brightness(): To arrange how the dots will be placed for the z-axis, corresponding to the brightness of the image pixels. *[4]* 

**[4]**



* translate(): Allow object to move to any location within the windows.
    * Ellipse():  To generate the size of the ellipse corresponding to the brightness of the image pixel. [5]

**[5]**


```
function setup() {
    createCanvas
    (400, 400);
}
```

> This is a quote

###### Reference:

[Link Text](https://www.google.com)