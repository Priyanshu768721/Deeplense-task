# Specific Test III. Image Super-resolution
## Task III A
The task required training a deep learning-based super-resolution model to upscale low-resolution (LR) strong lensing images using the provided high-resolution (HR) images as ground truth. 

### My Approach
To tackle this, I used SRGAN and RCAN models for their effectiveness in super-resolution tasks. 

### SRGAN Architecture  ( from srgan paper)
![SRGAN Architecture](https://github.com/Priyanshu768721/Deeplense-task/blob/main/Task%203/Model_image/srgan.png)

### RCAN Architecture (from rcan paper)
![RCAN Architecture](https://github.com/Priyanshu768721/Deeplense-task/blob/main/Task%203/Model_image/rcan.png)


### Evaluation Results  

| Model  | MSE   | PSNR   | SSIM  |  
|--------|--------|--------|--------|  
| SRGAN(Without Perceptual loss)  | 8.524e-05  | 40.72 | 0.946  |  
| SRGAN(With Perceptual loss) |  0.000132  | 38.81 |  0.906 |
| RCAN   | 0.0001   | 42.17  | 0.976  |  
