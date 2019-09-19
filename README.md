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
 

1. Video sequences should be copied to the path ".\Sequence\original\" with "jpg", "png" or "bmp" file formats.

2. Then, you can use file "bat_RADF" to predict saliency maps.



It should be also noted that this code is NOT allowed for commercial purposes.

Thank you

Best Regards
