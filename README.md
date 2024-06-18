# Number_Plate_Generator
This Python script utilizes OpenCV to detect number plates from a webcam stream and save the extracted regions as separate JPEG images.

Features:
Leverages a pre-trained Haar cascade classifier (haarcascade_russian_plate_number.xml) for efficient number plate detection.
Visualizes detected plates with green rectangles and labels.
Allows saving extracted number plate regions as images (format: plates/scanned_img_<count>.jpg) by pressing the 's' key during execution.

Requirements:
Python 3.x
OpenCV (pip install opencv-python)


Usage:
The script will display a window titled "Result" showing the webcam feed.
Detected number plates will be highlighted with green rectangles and labeled.
Press the 's' key to save the currently displayed number plate region as a separate JPEG image in the plates directory.
A green rectangle and "Plate Saved" message will confirm successful saving.


Notes:
The pre-trained Haar cascade classifier (haarcascade_russian_plate_number.xml) is optimized for Russian license plates. 
