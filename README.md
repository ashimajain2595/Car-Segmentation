# Car-Segmentation
Car Segmentation

## Approach
Background removal and replacement in car images using UNet based model with vgg16 backbone

## Dataset
The dataset consists of a total 211 images of which 80% were randomly sampled for training and rest for validation

## Results
The best IOU score on validation set is 0.94 and F1 score of 0.97
Using the trained model, the segmentation masks were obtained for the provided test images. It takes 800ms per image to create mask.


For running on mobile devices, the model can be quantized and exported to suitable formats such as tflite.

We can expand the training dataset and also aim for bigger models such as ResNet or Inception to further improve the performance.
