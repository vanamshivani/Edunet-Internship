# Edunet-Internship


In modern computing environments, user interaction with systems largely depends on traditional input devices such as keyboards, mice, and touchscreens. While effective, these methods can be limiting in situations where hands-free interaction is needed—for example, during presentations, while cooking, for users with physical disabilities, or in gesture-controlled smart environments.

To address the limitations of physical volume control methods, the proposed system introduces a real-time.gesture-based interface that allows users to control the system volume using hand movements detected through a standard webcam.

🖐️ Gesture Volume Control Gesture Volume Control is a computer vision project that lets you control your system's audio volume using simple hand gestures. Using a webcam, the program detects your hand in real time and calculates the distance between your thumb and index finger. This distance is then mapped to the system volume level, allowing you to increase or decrease volume by simply moving your fingers.

The project uses OpenCV for video processing, MediaPipe for hand landmark detection, and Pycaw to interface with the system's audio control (on Windows). It's a practical demonstration of how AI and computer vision can be applied to create touch-free, intuitive user interfaces.

💾 REQUIREMENTS

opencv-python

mediapipe

comtypes
