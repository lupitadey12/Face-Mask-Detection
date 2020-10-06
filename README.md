# Face-Mask-Detection
This includes detection of face mask in wild. It also provides live positive and negative samples of results along with accuracy scores. 

The project involves creating a dataset having 2 classes of without mask and with mask. Over 600+ image samples are used for the class of images without mask and for those of the  class with mask, the images are created using the code of Data Augmentation with the help of 3 samples face mask images under the images folder. 

These images in the dataset are used to train the model by splitting the dataset into train set and test set and then made to loop over several layers of the convolutional neural network. After model training it is compiled and made to store in the disk and a respective classification plot of training loss and accuracy is obtained.

After the pretrained model and the face detector is loaded again the prediction of face mask on human face is done. For face detection the frame of the face is ectracted and preprocessed and predictions of presence of mask on the face is made.

Usages: Face Recognition packages, Tensorflow is used as backend framework for Machine Learning, OpenCV library package for Computer Vision
