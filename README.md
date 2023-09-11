# Neural Style Transfer from Scratch
This project was a part of my home assignmnet for the computer vision course. In this project I explored and implemented a technique for image style transfer known as Neural Style Transfer.

Neural Style Transfer is a technique that merges two images, namely, a "content" image and a "style" image, to create a new, "stylized" image. The new image retains the "content" from the content image and the "style" from the style image. The process includes feature extraction from two images using a pre-trained neural network and further modification of the target image by minimizing the difference between features of the content and style images.

Neural Style Transfer method is not computationally efficient, therefore, in the second part of the work I investigated impact of hyperparameter values on execution time and quality of the output image. In addition, I experimented with postprocessing methods. Finally, I achieved comparable output quality with a model that stylizes an image in 5 seconds, compared to another model that takes 49 seconds to stylize the same image.
