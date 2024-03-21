**Crowd Counter**

Crowd Counter is a Python application designed to count people in a video feed, particularly useful for monitoring crowd density in public spaces. Developed using Tkinter for the GUI and OpenCV for computer vision tasks, the application allows users to select a video file (.mp4, .mkv, .avi) and then analyzes it frame by frame.

**Features:**

Background subtraction technique to detect moving objects.
Contour detection and tracking to identify individuals.
Counting of people moving up and down within defined boundaries.
Real-time display of total counts and updates during video playback.

**How to Use:**

Run the application and click the "Select Video" button to choose a video file.
Click the "Count Crowd" button to initiate the analysis process.
The application will display the total counts of people moving up and down in the video.

**Requirements:**

Python 3.x
Tkinter
OpenCV
Pillow (PIL)

**Installation:**

Clone the repository to your local machine.
Install the required dependencies using pip install -r requirements.txt.
Run the application with python crowd_counter.py.

**Contributing:**

Contributions are welcome! Feel free to fork the repository, make improvements, and submit pull requests.
