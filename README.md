# Face-Mask-Detection
**Model summary and novelty**<br />
This includes detection of face mask in wild. It also provides live positive and negative samples of results along with accuracy scores. 

The project involves creating a dataset having 2 classes of without mask and with mask. 686 image samples are used for the class of images without mask and for those of the  class with mask, the images are created using the code of data augmentation with the help of the 3 sample face mask images under the images folder. 

The resultant dataset is then used to train the model by splitting the dataset into train set and test set and then made to loop over several layers of the convolutional neural network. After model training is done it is compiled and made to store in the disk (maskmodel.h5) and a respective classification plot of training loss and accuracy is obtained.

After the pretrained model and the face detector is loaded again the prediction of face mask on human face is done. For face detection the frame of the face is extracted and preprocessed and predictions of presence of mask on the face is made.

Usages: Face Recognition packages, Tensorflow is used as backend framework for machine learning, OpenCV library package for Computer Vision <br />

**Model Constraints**
No constraints.<br />

**Application**
Can be implemented in crowded places for safety purposes to ensure that majority people captured in the frame are wearing a mask. Helpful in pandemc times
