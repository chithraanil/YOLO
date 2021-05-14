### YOLO
YOLO (You only look once) is a state of the art object detection algorithm that has become main method of detecting objects in the field of computer vision. Previously people used techniques such as sliding window object detection, R CNN, Fast R CNN and Faster R CNN. But after its invention in 2015, YOLO has become an industry standard for object detection due to its speed and accuracy
The algorithm applies a single neural network to the full image, and then divides the image into regions and predicts bounding boxes and probabilities for each region

### files to be downloaded

yolo.cfg - Configuration file  
yolo.weights - pre-trained weights  
coco.names - 80 classes names




For each bounding box, the network also predicts the confidence that the bounding box actually encloses an object, and the probability of the enclosed object being a particular class.

Most of these bounding boxes are eliminated because their confidence is low or because they are enclosing the same object as another bounding box with very high confidence score(non-maximum suppression)  
![spoon detected](https://user-images.githubusercontent.com/71581864/118238747-944c2d80-b4b6-11eb-80a3-abcd6bb4f783.PNG)
.


