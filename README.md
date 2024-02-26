**README**

**Video Capture and Recording with OpenCV**

This Python script demonstrates how to capture video from the default camera using OpenCV, display it in real-time, and save it to a file. The script utilizes the OpenCV library, which provides a comprehensive suite of tools for computer vision tasks, including video processing.

**Requirements:**
- Python 3.x
- OpenCV library (`opencv-python`)

**Installation:**
1. Ensure you have Python installed on your system. If not, download and install it from [python.org](https://www.python.org/downloads/).
2. Install the OpenCV library by running the following command in your terminal or command prompt:
   ```
   pip install opencv-python
   ```

**Usage:**
1. Clone or download the repository containing the script.
2. Open a terminal or command prompt and navigate to the directory containing the script.
3. Run the script using the following command:
   ```
   python video_capture_and_record.py
   ```
4. Once the script is running, it will capture video from the default camera and display it in a window titled "frame".
5. Press the 'q' key to exit the video capture loop.
6. After exiting the loop, the captured video will be saved to a file named "output.avi" in the same directory as the script.

**Notes:**
- Ensure that your system has a camera connected and properly configured.
- The default codec used for video encoding is XVID. You can change it by modifying the `fourcc` variable in the script according to your requirements.
- Adjust the frame size and frame rate as needed by modifying the parameters in the `cv2.VideoWriter` constructor.
- This script captures video until the 'q' key is pressed. Modify the exit condition in the `while` loop as per your application's requirements.

**References:**
- OpenCV Documentation: [https://docs.opencv.org](https://docs.opencv.org)
- Python Package Index (PyPI) - `opencv-python`: [https://pypi.org/project/opencv-python/](https://pypi.org/project/opencv-python/)

For any issues or inquiries, please feel free to contact [Musa Tahawar/musahero1999@gmail.com/musatahawar.epizy.com]. 

**Author:** [Musa Tahawar]

**License:** This project is licensed under the [MIT], see the LICENSE file for details.

**Acknowledgements:**
Special thanks to the OpenCV development team for providing such a powerful library for computer vision tasks.
