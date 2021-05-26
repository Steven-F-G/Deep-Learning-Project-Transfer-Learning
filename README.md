# Deep-Learning-Project-Transfer-Learning
##Semester 6 Deep Learning Transfer Learning Mini Project-2

###Introduction
The problem taken is here is to classify the different images of monkeys
based on their species. To implement Transfer Learning here we
implement a trained model, VGG16 which was proposed by researchers
from University of Oxford. The aim here is to use the VGG16 model with
its pre-trained weights as a feature extractor and to add only our own
fully- connected layers and classifier pertaining to the dataset being
used. Moreover, to clearly show the ability to transfer a small dataset of
only less than 150 images per class is chosen. A pre-trained model will
eliminate the need to train the model from scratch.


###Dataset Details
This dataset contains 10 classes of monkey species, each corresponding
to a species from Wikipedia's monkey cladogram. Images are 400x300
px or larger and .jpeg format (almost 1400 images), with less than 150
images per class. Images were downloaded with help of the googliser
open source code. This dataset was intended as a test case for
fine-grain classification tasks, perhaps best used in combination with
transfer learning.

https://www.kaggle.com/slothkong/10-monkey-species
