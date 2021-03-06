# Texture synthesis using convolutional neural network
Texture syntesis is the process of generating a new texture that captures all the visual characteristics from the original texture, but the two textures are not identical.


The aim of this project is to study a texture synthesis technique based on Convolutional Neural Network VGG-19.

The key idea of the method is to generate the new texture by minimizing the error between the gram matrix of feature maps of the original texture and the gram matrix of feature maps of a random noise through gradient descent algorithm.

The technique is described then as follows [1]: 
![alt text](https://github.com/LefdRida/texture_synthesis/blob/main/imagetest/Capture.JPG)

# Results 

![alt text](https://github.com/LefdRida/texture_synthesis/blob/main/imagetest/res1.png)


![alt text](https://github.com/LefdRida/texture_synthesis/blob/main/imagetest/res2.png)


![alt text](https://github.com/LefdRida/texture_synthesis/blob/main/imagetest/res3.png)

## Reference
<a id="1">[1]</a> 
Gatys, L., Ecker, A. S., & Bethge, M. (2015). Texture synthesis using convolutional neural networks. Advances in neural information processing systems, 28.
