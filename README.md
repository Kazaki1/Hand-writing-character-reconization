# EMNIST Character Recognition with CNN

A handwritten character recognition project built with **Python, PyTorch, and OpenCV**.

The system trains a Convolutional Neural Network (CNN) on the **EMNIST ByClass** dataset and uses the trained model to recognize handwritten letters and digits from images or user drawings.

## Features

* Train a custom CNN model using the EMNIST ByClass dataset
* Recognize **62 character classes**

  * 10 digits (`0-9`)
  * 26 uppercase letters (`A-Z`)
  * 26 lowercase letters (`a-z`)
* Image preprocessing with OpenCV
* Character detection using thresholding and contour detection
* Resize and normalize input images to `28 × 28`
* Predict characters and display prediction confidence
* Support handwritten character input from an image
* Support drawing characters with a mouse
* Save the trained model as a `.pth` file
* Save prediction results for later review

## Technologies

| Technology  | Purpose                                   |
| ----------- | ----------------------------------------- |
| Python      | Main programming language                 |
| PyTorch     | Deep learning framework                   |
| Torchvision | EMNIST dataset and image transformations  |
| OpenCV      | Image processing and character extraction |
| NumPy       | Numerical and image data processing       |
| Matplotlib  | Image visualization and drawing interface |
| python-docx | Saving prediction results to Word         |
