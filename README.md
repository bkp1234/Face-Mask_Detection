### Face Mask Detector
#### It detect's whether the persons are wearing mask or not.
Demo 

<img src="https://github.com/np-n/Face-Mask_Detection/blob/master/output/face-mask-detection.gif">

#### It is built with the following frameworks and libraries using the concepts of Computer Vision and Deep Learning.

#### Frameworks:
<ul><li>Tensorflow as Deep Learning</li></ul>

#### Libraries:
<ul>
<li>OpenCV</li>
<li>Matplotlib</li>
<li>Sklearn</li>
<li>NumPy</li>
<li>Seaborn</li>
<li>mtcnn</li>
</ul>

#### Installation Guides:
**Note**: You must have `python 3.x` installed in your system.

* Download the zip file of this repository or clone the repository using git
* Make a new virtual-environment(recommended)
* Install dependencies and libraries using `pip install -r requirements.txt`

#### Training/Testing Guides:
* Datasets are available in both splitted(train/val/test) and unsplitted form.
* Here, I am using unsplitted datasets.
* Dataset credit goes to <a href="https://github.com/prajnasb/observations/tree/master/experiements/data">Prajna Bhandary </a>because she created this datasets.
* Then go along the notebook `Face_Mask_Detection_VGG16.py`
* It is trained with VGG16 network model. VGG16 is a convolutional neural network model proposed by K. Simonyan and A.Find more about VGG16 <a href="https://neurohive.io/en/popular-networks/vgg16/">here</a>
* Perform hyperparameter tuning to get more accurate model.

#### Working Guides:
- Open terminal/command prompt inside the downloaded/cloned directory</li>
- Run python script `face_mask_detection_on_realtime.py`</li>
    - Enter `python face_mask_detection_on_realtime.py` in terminal
- Your webcam will open,test it by wearing mask</li>
- It will detect face-mask in real-time</li>

