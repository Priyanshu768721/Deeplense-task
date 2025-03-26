# Specific Test III. Image Super-resolution
## Task III A
The task required training a deep learning-based super-resolution model to upscale low-resolution (LR) strong lensing images using the provided high-resolution (HR) images as ground truth. The implementation had to be in PyTorch or Keras, and performance was evaluated using MSE, SSIM, and PSNR.

My Approach
To tackle this, I chose [Model Name] (e.g., SRGAN/ESRGAN/EDSR) for its effectiveness in generating high-quality images. My approach involved:

Model Architecture – Used a convolutional neural network (CNN) with residual blocks for feature learning.

Training – Minimized MSE loss and incorporated perceptual loss for sharper details.

Evaluation – Computed MSE, SSIM, and PSNR on test images to assess reconstruction quality.

The results showed [mention improvement], demonstrating the model's ability to enhance lensing images.
