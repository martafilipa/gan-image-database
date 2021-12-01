# Test Images
Here are presented the images included in the subjective image quality assessment. The GAN-based solutions have 3 different quality levels associated with them Lo, Mi, Hi going from lowest to the highest quality. 

## Original
The reference material used in this experiment was the [JPEGAI](https://jpeg.org/jpegai/dataset.html) test set. 

## HiFiC
In the compression solution the quality was controlled changing the desired bitrate, as follows: 
- HiFiC Lo: `r_t=0,06 bpp`
- HiFiC Mi: `r_t=0,14 bpp`
- HiFiC Hi: `r_t=0,3 bpp` 

## ESRGAN
In the super-resolution solution, the quality was controlled changing the `λ` weight in the generator loss 

![image](https://user-images.githubusercontent.com/38942103/144244864-bee4c7db-52de-4d5d-b39e-d397c23f5055.png) 

As follows: 

- ESRGAN Lo: `λ = 0.05`  
- ESRGAN Mi: `λ = 0.01`
- ESRGAN Hi: `λ = 0.005`

## ArNet
In the artifact removal solution the quality was controlled changing the JPEG quality factor (QF), as follows: 
- ArNet Lo: `QF=7`
- ArNet Mi: `QF=14`
- ArNet Hi: `QF=21`
