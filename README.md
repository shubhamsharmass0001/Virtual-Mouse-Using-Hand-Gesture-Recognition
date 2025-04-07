🖱️ Virtual Mouse using Hand Gestures (OpenCV + MediaPipe + PyAutoGUI)

This project turns your hand gestures into mouse controls using your webcam and computer vision. No need for a physical mouse — control your cursor with your fingers!

⸻
🚀 Features
	•	Move Mouse: Move your hand to control the mouse cursor.
	•	Left Click: Pinch your index finger while keeping middle finger relaxed.
	•	Right Click: Pinch your middle finger while index finger is relaxed.
	•	Double Click: Pinch both index and middle fingers.
	•	Take Screenshot: Bring thumb close to index base while both fingers are pinched.
	•	Smooth, real-time gesture recognition using MediaPipe and OpenCV.
	•	Relative cursor movement to avoid sudden jumps.

⸻
🧰 Tech Stack
	•	Python
	•	OpenCV - for webcam access and image processing
	•	MediaPipe - for hand tracking and gesture detection
	•	PyAutoGUI - to simulate mouse events and screenshots
	•	pynput - alternative mouse control
	•	Custom util.py - utility functions for angle and distance calculations

⸻
📦 Requirements
	•	Python 3.6+
	•	OpenCV
	•	MediaPipe
	•	PyAutoGUI
	•	pynput

Install all dependencies:
pip install opencv-python mediapipe pyautogui pynput

🖥️ How It Works
	1.	OpenCV captures frames from your webcam.
	2.	MediaPipe detects your hand and landmarks.
	3.	Based on angles and distances between fingers, the code identifies gestures.
	4.	PyAutoGUI & pynput simulate mouse actions like move, click, double-click, or screenshot.

⸻
📸 Gestures Explained
Gesture              Action
Index finger up      Move cursor
Index pinch          Left Click
Middle pinch         Right Click
Both pinched         Double Click
Pinch + thumb near   Screenshot


▶️ Run the Project
python 1.py
Make sure your util.py is present in the same directory with correct angle and distance functions.

🧠 Future Improvements
	•	Add scroll gestures
	•	Support for drag-and-drop
	•	Multi-hand control
	•	GUI overlay for gesture feedback

⸻
📷 Preview
You can also add a GIF or image of your project in action here for a better showcase.

⸻
🤝 Contributing
Pull requests are welcome! For major changes, open an issue first to discuss what you would like to change.
