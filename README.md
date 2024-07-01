# ROADLANE-LINE-DETECTION
LANE LINE DETECTION USING PYTHON ,OPENCV,NUMPY
Finding Lane Lines on the Road
Combined Image

This project detects lane lines using Python and OpenCV. A video of the end-result can be found at:

https://www.youtube.com/watch?v=EZcHGsPX55Y

Dependencies
Python 3.5
NumPy
OpenCV
Matplotlib
MoviePy
How to run
To run the script stand-alone:

Usage: lane_lines.py [options]

Options:
  -h, --help            show this help message and exit
  -i INPUT_FILE, --input_file=INPUT_FILE
                        Input video/image file
  -o OUTPUT_FILE, --output_file=OUTPUT_FILE
                        Output (destination) video/image file
  -I, --image_only      Annotate image (defaults to annotating video)
For example, to detect lanes lines on the video 'challenge.mp4', run:

python lane_lines.py -i challenge.mp4 -o extra.mp4

To detect lane lines on a single image (e.g. for debugging), run:

python lane_lines.py -i input_image.jpg -o output_image.jpg -I

For detailed explanation of what the code does, and example images of intermediate steps, refer to P1.ipynb via jupyter notebook

About
Find lane lines on the road using Python and OpenCV, applying Canny edge detectors and Hough line transforms

www.youtube.com/watch?v=EZcHGsPX55Y
Topics
python opencv computer-vision
Resources
 Readme
 Activity
Stars
 304 stars
Watchers
 15 watching
Forks
 160 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
Jupyter Notebook
97.6%
 
Python
2.4%
Footer
