# CCI_S2_Coding2_Final-Project

## Project Summary

Use opencv, numpy, matplot, scikit-image in Python to create different image filters to show the beautiful scenery of London, then use dash to show before after as an album.

‘When a man is tired of London, he is tired of life.’  Everytime I walk on the streets of London, I feel that every landscape is an oil painting. This reminds me of one of my favourite impressionism artists -Claude Monet. 

As a overseas student, the life of studying in London is a memory that I will never forget in my life.  So I hope to record the beautiful scenery of London in the form of paintings and make it into 'an album'.

![image](https://miro.medium.com/max/1400/1*8-M1SqpIR4UpcLnscn7WWw.png)

## Process

**Oil Painting Effect filter** [link](https://github.com/YIDAI1111/CCI_S2_Coding2_Final-Project/tree/main/image_Oil%20Painting%20Effect)

It is included in cv2.xphoto() which also has several other cool functions like image inpainting, white balance, image denoising, etc.
Step 1: Superpixel segmentation of the area
Step 2: Substitute the original pixel for the material sample of the segmented area

![image](https://miro.medium.com/max/1400/1*r7_dhyCAC6mPncjOHk7dMQ.png)


**Pointillist Art filter** [link](https://github.com/YIDAI1111/CCI_S2_Coding2_Final-Project/tree/main/image_Pointillist%20Art)

To do this in Python, our first step is to compute the most used colors for which Kmeans is used. I used a color palette of 20 which means that the dots will be made by 20 most used colors will be present in the image. A suitable radius size is calculated for the dots according to the image size. Then we loop over the image and find the color closest to the dot, using which the circle is drawn.

![image](https://miro.medium.com/max/1400/1*VfvGC5eNRuYeQsJizL7Jsg.png)


**Frosted glass filter** [link](https://github.com/YIDAI1111/CCI_S2_Coding2_Final-Project/tree/main/image_Frosted%20glass)

![image](https://miro.medium.com/max/1400/1*ie1b0x8yxKmloAI0YSd0Aw.png)


**Pencil sketch filter** [link](https://github.com/YIDAI1111/CCI_S2_Coding2_Final-Project/tree/main/image_%20Pencil%20sketch)

![image](https://miro.medium.com/max/1400/1*_6J_nq__k5HLbH3AO2sgNA.png)


**Light ripple filter**  [link](https://github.com/YIDAI1111/CCI_S2_Coding2_Final-Project/tree/main/image_Light%20ripple)

![image](https://miro.medium.com/max/1400/1*uS8T0rLg45ZP5prHZ06aRw.png)


[More details in blog](https://www.froyodai.com/post/cci-s2-coding2_final-project_my-album-of-london)

[Video](https://www.youtube.com/watch?v=HIquP0WDUDQ&t=11s)

