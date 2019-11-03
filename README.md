# Computer-Vision-Yolo
CV-YOLO-Object-Detector
YOLO is an extremely fast real time multi object detection algorithm. YOLO stands for “You Only Look Once”. The algorithm applies a neural network to an entire image. The network divides the image into an S x S grid and comes up with bounding boxes, which are boxes drawn around images and predicted probabilities for each of these regions. The method used to come up with these probabilities is logistic regression. The bounding boxes are weighted by the associated probabilities. For class prediction, independent logistic classifiers are used.

Implementation
YOLO is single stage detector, which is less accurate than 2 stage detector but is faster. In the code, we have used command line arguments so we have to supply them at the time of execution. There is another alternative but it requirres use of darknet.

For execution, write: python yolo.py --image 'image name not in quotes' --yolo yolo-coco Here yolo-coco is pre-trained model downloaded from reference link.

For reference use
https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/


