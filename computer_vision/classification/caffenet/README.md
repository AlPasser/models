*******************************************************************************
Model Path Description:

|--models

   |--computer_vision
         |-- classification   
             |-- {scene_name}       
                  |--{scene_name}.om            
                  |--model_desc.txt            
         |-- object_detect   
         |-- segmentation

Scene Name: Om file Name and upper directory name should be scenes to be used.
*******************************************************************************

Original Network Link:
https://github.com/BVLC/caffe/blob/master/models/bvlc_reference_caffenet/deploy.prototxt

Pre-trained Model Link:
http://dl.caffe.berkeleyvision.org/bvlc_reference_caffenet.caffemodel

Input Description:
The input image should be resized to 227*227 pixels, and padding to 256*224 pixels, YUV420SP_U8.

Output Description:
The pre-trained model is trained for image recognition, and its results follow 1000 lables of ImageNet.

Custom Operator:
Custom operator is included or not: No


Tested Version List:
-Atlas 200