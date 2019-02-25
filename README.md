[![HitCount](http://hits.dwyl.io/sudheerachary/Manga_Colorization.svg)](http://hits.dwyl.io/sudheerachary/Manga_Colorization)

# Manga Colorization
  - **`models/`** consists the cGAN models & visualizations.
  	- run **`train.py`** to train on images stored in **`datasets/train`**.
  	- run **`test.py`** to generate colorization for images in **`datasets/test`**.
  	- **`datasets/generated_Images`** contains generated images and trained model weights.
  	- **`datasets/test`** contains testing images.
  	- **`datasets/train`** contains/put dataset for training.
  	- **`datasets/validation`** contains validation set of images for training.
	
  - **Segmentation and post-processing**
  	- **`segmentation/input_images`** contains test images
  	- **`segmentation/bw_images`** contains the black and white images after screentone removal
	- **`Results`** contains results for postprocessing and final outputs  	
  	- run **`segmentation.m`** in **MATLAB** to segment the input image (Monochrome Original)
	
  - **cGAN**
	<img src="models/generator_visualization.png" height="1024px"> + <img src="models/generator_visualization.png" height="1024px"> = <img src="models/cGAN_visualization.png" height="1024px">

 a. <img src="segmentation/input_images/7.jpeg" height="512px" width="256px">  b. <img src="datasets/generated_images/2.jpg" width="256px" height="512px"> c. <img src="segmentation/results/7_final_result.jpg" height="512px" width="256px">

  - **a** - input: monochrome original
  - **b** - output: cGAN output
  - **c** - output: Post Processed output
