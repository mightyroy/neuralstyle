# neuralstyle
convolutional network for restyling art style of images

requres VGG weights imagenet-vgg-verydeep-19.mat

To run in terminal, type: 
```
python neural_style.py --content monalisa.jpg --styles electronics.jpg --output out.jpg --iterations 2500
```

Sample styled image produced from logo bricks style on Van Gogh's Starry Night painting.
![alt text](https://github.com/mightyroy/neuralstyle/blob/master/Screen%20Shot%202016-04-12%20at%209.22.53%20PM.png)

Applying electronics image as style to monalisa:

<img src="https://github.com/mightyroy/neuralstyle/blob/master/greenelectronics.jpg" align="left" height="400" width="400" >

![alt text](https://github.com/mightyroy/neuralstyle/blob/master/tmp2.jpg)

Cool outcome^^
