# Art-Blender-Neural-Style-Transfer

The goal of this project is implementation of Neural style Transfer Algoritm. The Model uses two images as input:
- Content Image- The image you want to style.
- Style Reference Image- Style of the image you want to blend(such as an artwork by a famous painter)

Finally the output is te blend of these two images such that the input image is transformed to look like the content image, but “painted” in the style of the style image.

**Approach**
- Visualize data
- Basic Preprocessing/preparing our data
- Set up loss functions
- Create model
- Optimize for loss function

**Input**
<p align="left">
  <img src="images\eiffel.jpg" width="350" title="Input"> 
  <img src="images\starrynight.jpg" width="350" title="Input">
</p>

**Output**

<p align="left">
  <img src="outputs\starrynight_onto_eiffel_at_iteration_0.png" width="350" alt="accessibility text">
</p>

**References**
- https://www.tensorflow.org/tutorials/generative/style_transfer
- https://blog.tensorflow.org/2018/08/neural-style-transfer-creating-art-with-deep-learning.html
- https://www.v7labs.com/blog/neural-style-transfer
