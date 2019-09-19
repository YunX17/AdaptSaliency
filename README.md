# AdaptSaliency

******************************************************************************************************************
Title: Self-paced Online Learning: A Novel Weakly Supervised Scheme to Adapt Image Saliency Model for Video Data

The code is tested on windows 10 with MATLAB R2016b, CUDA 8.0
******************************************************************************************************************


Installation:
 

Set up our Caffe version, check that Caffe MATLAB wrapper is set up correctly and make sure the path of file "caffe_.mexw64" has been correctly set up.

The experimental model RADF is available in this code and we revise the files based on the original RADF Caffe verison, e.g., "euclidean_loss_layer.cu".
Thus, using other Caffe versions will lead to wrong detection.



Usage:
 
1. Our caffemodels can be downloaded from Google Drive. Please download them and put them to the identical path of the file "bat_RADF.m" .

  MotionSaliencyDetector: https://drive.google.com/file/d/1oKrQeADuJADcvLaS3GVeL73vqXVV8_HU/view?usp=sharing

  RADF original model: https://drive.google.com/file/d/1MGe6CtYoGQYJJYYggAKRjqfN8A50VMt7/view?usp=sharing


2. Video sequences should be copied to the path ".\Sequence\original\" with "jpg", "png" or "bmp" file formats.

3. Then, you can use file "bat_RADF.m" to predict saliency maps.



******************************************************************************************************************
It should be also noted that this code is NOT allowed for commercial purposes.

Thank you

Best Regards
