# Neural Style Transfer

This project aims to make art by using one image and then transferring the style of that image to the target image. This style transfer method is what made the smartphone apps like Prisma famous.

Neural style transfer is an optimization technique used to take two images—a *content* image and a *style reference* image (such as an artwork by a famous painter)—and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.

This is implemented by optimizing the output image to match the content statistics of the content image and the style statistics of the style reference image. These statistics are extracted from the images using a convolutional network.

For example, let’s take an image of Katherine-Langford and one normal painting beautiful painting.

<img src="Katherine-Langford.jpg" width="200px"/>


<img src="painting.jpg" width="200px" />


Now how would it look like if painter of this painting decides to paint Katherine? Something like this?

<img src="output.png" style="width: 200px;"/>

Google Colab link: https://colab.research.google.com/drive/1IBbcgEybTyZPhdoWaxXCh6LV0idoWUVL?usp=sharing


#### DCP 2021
