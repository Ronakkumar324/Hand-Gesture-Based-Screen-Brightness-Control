# ✋💡 Hand-Gesture-Based-Screen-Brightness-Control

**📌 Synopsis:** This project implements a real-time, hand gesture-based system to control screen brightness using OpenCV, MediaPipe, and Screen Brightness Control (SBC).
👉 By tracking the distance between the thumb and index finger, the system dynamically adjusts brightness, providing a touchless and intuitive user experience.


**🎯 Objective:** To design an efficient and AI-powered hand tracking system that enables users to adjust screen brightness without physical contact. The project aims to enhance accessibility and usability, particularly for users with mobility limitations.


**🧰 Methodology:**

1. 	✋ Used MediaPipe Hands for real-time 21-point hand landmark detection.

2. 	📹 Processed video frames with OpenCV.

3. 	📏 Calculated Euclidean distance between thumb and index finger tips.

4. 	🔁 Mapped distance to brightness levels via NumPy interpolation.

5. 	💻 Controlled brightness using the SBC (Screen Brightness Control) library.


**🎯 Expected Outcome:** 
A functional gesture-controlled brightness adjustment system that:

1. 🎛️ Responds smoothly and accurately to hand gestures

2. 🔄 Provides seamless brightness control

3. 🖥️ Reduces the need for manual interaction


**🌍 Impact:** 
This project introduces a contactless interface for brightness control, enhancing both convenience and accessibility.

Benefits:

1. 🙌 Improves accessibility for users with physical disabilities

2. ⚙️ Enhances user experience in smart environments

3. 📈 Paves the way for gesture-controlled UI systems


**🚀 Future Enhancements:**

1. 👐 Multi-hand gesture support

2. 🧠 AI-based gesture prediction

3. 🎙️ Integration of voice commands

4. 📱 Expansion to mobile and tablet platforms


**🙌 Acknowledgments**
1. [MediaPipe by Google](https://ai.google.dev/edge/mediapipe/solutions/guide)
2. [OpenCV](https://opencv.org/)
3. [screen-brightness-control](https://pypi.org/project/screen-brightness-control/)
