# Computer Vision Homework 2
## Training
### Training Progress
![](https://i.imgur.com/ynXxir4.png)
### Results
![](https://i.imgur.com/nUxBUSk.png)


## Style Transfer

Given a conten image and a style image, this style transfer application generate an output image with the original content but a new style. And this method focus on applying a new painting style on the original image.

### How does it works

1. Extract two layers from the input images respectively:
    * The style layer of the style image
    * The content layer of the content image
2. Define three loss function:
    * Content loss: The distance between the input and output images
    * Style loss: The distance between the style and the output images
    * Total loss: The combination of content loss and style loss
3. Minimize the total loss

### Results (using fast style transfer)
Original Image:
![](https://i.imgur.com/uFiwTnk.jpg)
Style Image 1:
![](https://i.imgur.com/ZdhUVNb.jpg)
Output Image 1:
![](https://i.imgur.com/r1qlyb7.jpg)
Style Image 2:
![](https://i.imgur.com/OjCB6EF.jpg)
Output Image 2:
![](https://i.imgur.com/MtNpCdQ.jpg)
Style Image 3:
![](https://i.imgur.com/pfXKqkS.jpg)
Output Image 3:
![](https://i.imgur.com/bMZhM6D.jpg)


### Link
https://github.com/keras-team/keras/blob/master/examples/neural_style_transfer.py