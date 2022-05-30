# Object-Detection
## RetinaNet_MobileNetV2
## RetinaNet_custom_dataset

## global-wheat-detection
The data is images of wheat fields, with bounding boxes for each identified wheat head. Not all images include wheat heads / bounding boxes. The images were recorded in many locations around the world.

The CSV data is simple - the image ID matches up with the filename of a given image, and the width and height of the image are included, along with a bounding box (see below). There is a row in train.csv for each bounding box. Not all images have bounding boxes.

Most of the test set images are hidden. A small subset of test images has been included for your use in writing code.

### Columns

image_id : the unique image ID.

width, height : the width and height of the images.

bbox : a bounding box, formatted as a Python-style list of [xmin, ymin, width, height]
