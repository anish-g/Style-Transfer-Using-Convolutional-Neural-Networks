# Style Transfer Using Convolutional Neural Network

This notebook is derived from a project exercise of Deep Learning Nanodegree from Udacity. This notebok is based on the style transfer method outlined in the paper, [Image Style Transfer Using Convolutional Neural Networks, by Leon A. Gatys](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf).

This notebook utilizes VGG19 Network same as the paper and contains code with brief step-by-step explanation for easier understanding.


### Note

Train the model in GPU if available for faster training.
Experiment by tuning epochs and hyperparameters. Generally training in higher epochs gives better result. Play around with `content_weight` and `style_weight` ratio to see variations in results. If GPU is not available, training takes much longer but does provide result. So, if you are just trying out the model then train with fewer epochs (at least 2000 recommended for good result, though). Test different variations content and style images.
No need to change any code to run on GPU or CPU, snippet notebook automatically detects the availability of GPU and run accordingly.


### Frameworks / Tools used
* PyTorch
* NumPy
* Matplotlib
* Jupyter Notebook
