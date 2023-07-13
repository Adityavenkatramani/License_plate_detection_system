
# License Plate Detection System

The License Plate Detection System is a computer vision project that aims to detect and extract license plate information from images. This system utilizes the EasyOCR library for optical character recognition (OCR) to extract text from the detected license plate regions.

## Features

- Detects license plate regions in images using computer vision techniques.
- Extracts the license plate region from the image.
- Performs OCR on the extracted license plate region to recognize and extract the alphanumeric characters.
- Displays the detected license plate and the extracted characters on the image.

## Installation

To use the License Plate Detection System, you need to install the following dependencies:

```
!pip install easyocr
!pip install imutils
!pip install opencv-python-headless
```

## Usage

1. Place your image file in the same directory as the code file.
2. Replace `'image1.png'` with the filename of your image in the following line of code:

```python
img = cv2.imread('image1.png')
```

3. Run the code, and the license plate detection and recognition results will be displayed on the image.

## Example Output

The License Plate Detection System performs the following steps:

1. Reads the image file and converts it to grayscale.
2. Applies noise reduction and edge detection to the image.
3. Finds the contours of the license plate regions in the image.
4. Selects the license plate region based on contour analysis.
5. Extracts the license plate region from the image.
6. Performs OCR on the extracted license plate region using EasyOCR.
7. Displays the detected license plate and the extracted characters on the image.

![Example Output](output.png)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

The License Plate Detection System is based on the tutorial [here](https://www.pyimagesearch.com/2020/09/14/getting-started-with-easyocr-for-optical-character-recognition/).
