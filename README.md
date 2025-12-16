Real-Time Sign Language to Text Editor ✋📝

This project is a computer vision application that translates hand gestures into text in real-time. It uses OpenCV for video processing and MediaPipe for hand landmark detection.

🌟 Features

- Sign Detection: Recognizes 5 alphabet signs: A, B, L, V, Y.

- Smart Typing: Hold a sign for 1.5 seconds to type the character.

- Space & Delete: * Show an Open Hand (5 fingers) to add a Space.

- Show a Fist (0 fingers) to Delete the last character.

- Visual Interface: Shows a live loading bar and the current sentence on screen.

🛠️ Requirements

-Python 3.x

-OpenCV

-MediaPipe

🚀 How to Run (The Easy Way)

I have created a one-click launcher to make this easy!

1 .Download this repository.

2. Double-click the run.bat file.

     - 🪄 It will automatically install all required libraries.

     - 🎥 It will launch the camera application instantly.


🎮 How to Use

1. Show a sign to the camera.

3. Hold it until the green loading bar fills up.

4. The letter will be added to your sentence!

5. Press 'q' to quit the application.

🛠️ How it Works
We will check the "state" of each finger (Up or Down).

- Sign 'A': All fingers folded, Thumb is Up (or tucked).

- Sign 'B': All 4 fingers Up, Thumb tucked in.

- Sign 'L': Thumb and Index Finger Up.

- Sign 'V': Index and Middle Finger Up.

- Sign 'Y': Thumb and Pinky Finger Up.

🧠 Tech Stack

- OpenCV: For video capture and image processing.

- MediaPipe: For extracting 21 hand landmarks.

- Python: Core logic using geometric rules (Cartesian coordinates).
