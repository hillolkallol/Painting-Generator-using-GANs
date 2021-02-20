# Painting-Generator-using-GANs
Explored Deep Convolutional Generative Adversarial Networks (GANs) by generating abstract cubism, portrait, landscape, and cityscape paintings using the Kaggle painting dataset. For most of my experiments I used a large varity of dataset and that's why my model was unable find a good pattern. So, I decided to pick a single painting (Cubism art titled as Contrast of Forms) and try to train my model to generate painting like that- https://github.com/hillolkallol/Painting-Generator-using-GANs/blob/master/Recreating%20Contrast%20of%20Forms.ipynb

I am focusing only on this experiment in the readme. Rest of the experiments can be found in separate notebooks. 

Dataset: https://www.kaggle.com/c/painter-by-numbers/data
Tensorflow Tutorial was a great help: https://www.tensorflow.org/tutorials/generative/dcgan



## Input Paintings
### Original Painting
![Original Painting](originalImage.png?raw=true "Title")

### Cropping the Original Painting
Cropped the original painting randomly thousand time to create my required training dataset.
![Original Painting](input.png?raw=true "Title")

### Output
And here is the output! My generator entertained me by creating cool paintings for me, LOL!
![Original Painting](outputs.png?raw=true "Title")