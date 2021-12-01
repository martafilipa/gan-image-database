# Subjective Assessment 
In the subjective assessment there were `8` reference images and a total of `10` different test scenarios. To have a complete design of the subjective test, 
that is every image is compared with every other image, each subject would need to perform `3160` comparisons. 
evaluations which would lead to a test with an unacceptably long duration. To lower the number of comparisons and thus the time needed for a subject to perform the pairwise 
comparison test, an image is not compared to all other images and thus the test follows an incomplete design.

The pairs of images compared were carefully selected as described next:
- **Within content across test conditions**: For each content (reference and all GAN processed images), all possible pairs are considered; this means that all images produced for 
  different test conditions are compared among themselves for the same content.
- **Cross-content across test conditions**: Cross-content pairs can increase the accuracy of the obtained psychovisual scores
- **HEVC Intra benchmark**: The HiFiC solution was compared against a conventional compression solution, namely, HEVC Intra. The pairs used compared each HiFiC image 
  with a HEVC image obtained for similar bitrates.

This amounts to a total of `456` test pairs. 
In [jdg.csv](/jdg.csv) file are presented the binary results of the subjective assessment. 

# Objective quality metric 
In [metrics.csv](/metrics.csv) file are available the results the following metrics: 
- MSE
- PSNR
- SSIM
- MS-SSIM
- VIF
- FSIM
- UIQ
- BRISQUE
- NIQUE
- hyperIQA
- UNIQUE
