[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/Borahb/Custom-OCR-YOLO.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/Borahb/Custom-OCR-YOLO/context:python)
# Custom-OCR-YOLO

This is a Custom OCR built by combining YOLO and Tesseract, to read the specific contents of a Lab Report and convert it into an editable file.
Here I have used YOLO_V3 trained on personal dataset. Then the coordinates of the detected objects are passed for cropping the deteted objects and storing them in another list. This list is passed through the Tesseract to get the desired output.

## Model
- Download the weights file from this link : https://drive.google.com/file/d/1o6_3dcsMd9sUFblvyWyraeuMEifzE1YA/view?usp=sharing
- Make a folder named model and put the weights file inside it.

## Dependencies
- Install Tesseract OCR Engine in the system
- Install Pytesseract library ` pip install pytessercat `
- Install OpenCV ` pip opencv `

## Workflow


   <img src = "asset/workflow.png" height = 400, width = 700>

## Getting Started

`python Custom_OCR.py --image <yourimage.jpg>`

## Contributing
Currently it is still in R&D Phase.

### Step 1

- **Option 1**
    - 🍴 Fork this repo!

- **Option 2**
    - 👯 Clone this repo to your local machine using `https://github.com/Borahb/Custom-OCR-YOLO.git`

### Step 2

- **HACK AWAY!** 

### Step 3

- 🔃 Create a new pull request 
