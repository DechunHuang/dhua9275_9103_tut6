# dhua9275_9103_tut6

#### 1.Imaging technique

I find that the Perlin Noise technique can be of help. Because as for this project, the chosen artwork is the Wheels of Fortune, which contains many circles. And this technique can be used to create an interesting rotation effect. There are two relevant figures shown below. First, they draw arcs to construct circles. Then they use this technique to change the locations of arcs. Therefore, the arcs can rotate around the center back and forth, so as to create such a rotation effect. So the elements in the chosen artwork can move in a similar way.



**The first figure**

https://openprocessing.org/sketch/1936445

![The first figure](https://github.com/DechunHuang/DechunHuang_Figures/blob/main/DechunHuang_Quiz8_Figure1.png)



**The second figure**

https://openprocessing.org/sketch/1881415

The original sketches of these two figures are dynamic, while the corresponding links are attached above.

![The second figure](https://github.com/DechunHuang/DechunHuang_Figures/blob/main/DechunHuang_Quiz8_Figure2.png)



#### 2.Coding technique

The noise() function can be used to get a value of the Perlin Noise. And there are some large circles in the chosen artwork, each of them has many small circles. These small circles can rotate around the center of the corresponding large circle, so as to create a similar rotation effect. This function can be called when recalculating the center coordinate of a small circle in the draw() function. The return value of the noise() function is used to calculate the rotation angle. Therefore, how the noise value changes can affect how the small circle moves.



**The figure of an example implementation**

https://p5js.org/examples/math-noise1d.html

This link contains the original dynamic sketch and the corresponding code.

![The figure of an example implementation](https://github.com/DechunHuang/DechunHuang_Figures/blob/main/DechunHuang_Quiz8_Figure3.png)

