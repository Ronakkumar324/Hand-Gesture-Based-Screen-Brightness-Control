# Hand-Gesture-Based-Screen-Brightness-Control

**Synopsis:** This project implements a real-time hand gesture-based system to control screen brightness using OpenCV, MediaPipe, and Screen Brightness Control (SBC). By tracking the distance between the thumb and index finger, the system dynamically adjusts brightness, providing a touchless and intuitive user experience.
**Objective:** To design an efficient and AI-powered hand tracking system that enables users to adjust screen brightness without physical contact. The project aims to enhance accessibility and usability, particularly for users with mobility limitations.
**Methodology:**
•	Utilized MediaPipe Hands for real-time hand landmark detection.
•	Processed video frames using OpenCV for gesture recognition.
•	Computed thumb-index finger distance using Euclidean distance formula.
•	Mapped distance to brightness levels using NumPy interpolation.
•	Integrated the SBC library to dynamically adjust screen brightness.
**Expected Outcome:** A functional gesture-controlled brightness adjustment system that responds smoothly and accurately to hand gestures. The system ensures seamless brightness control, reducing the need for manual adjustments.
**Impact:** This project introduces a contactless interface for brightness control, enhancing user convenience and accessibility. Future improvements may include multi-hand gesture recognition, AI-based gesture prediction, and voice control integration, further expanding its usability across devices.
