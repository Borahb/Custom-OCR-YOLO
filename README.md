[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/Borahb/Custom-OCR-YOLO.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/Borahb/Custom-OCR-YOLO/context:python)

# Custom-OCR-YOLO

This is a Custom OCR built by combining YOLO and Tesseract, to read the specific contents of a Lab Report and convert it into an editable file.
Here I have used YOLO_V3 trained on personal dataset. Then the coordinates of the detected objects are passed for cropping the deteted objects and storing them in another list. This list is passed through the Tesseract to get the desired output.
