project detailes:
to initialize:
python -m venv venv
venv\Scripts\activate
pip install opencv-python numpy scipy


what i use:
OpenCV → Video capture, drawing, Haarcascade.

Haarcascade classifier → Face detection.

SSD MobileNet v3 model (.pb + .pbtxt) → Object detection.

COCO dataset classes (coco.names) → Object class names.

Focal Length Method → Camera-to-object distance estimation.

Scipy Euclidean Distance → Object-to-object distance measurement.
