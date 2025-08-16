**Hand Gesture Controlled Gaming Interface**

This project implements a real-time hand gesture controlled gaming system using Python and a standard webcam. By leveraging computer vision and gesture recognition, players can control games without a physical controller, making the experience more interactive and immersive.
How It Works
Mediapipe + OpenCV are used to detect and track 21 hand landmarks in real-time.
Autopy allows smooth cursor movement across the screen, enabling precise control.
PyDirectInput maps finger gestures to in-game actions like accelerate, brake, jump, and click.
Gestures such as raising fingers, closing the fist, or combining multiple fingers are recognized and converted into respective key presses.
Key Features
Real-time hand detection and tracking with high accuracy.
Smooth cursor movement using interpolation techniques.
Gesture-based controls for:
Thumb up → Left-click
Open palm → Accelerate
Closed fist → Brake
Three fingers up → Jump
Controller-free and contactless gaming experience.
Application
The system has been tested on Hill Climb Racing (PC), where the player can accelerate, brake, and jump using only hand gestures. The same setup can be extended to other PC games or even general computer interactions.
Tech Stack
Python
OpenCV – Image processing
Mediapipe – Hand landmark detection
Autopy – Cursor control
PyDirectInput – Keyboard/mouse automation
Conclusion
This project demonstrates how gesture recognition and computer vision can create an innovative way of interacting with games. With further development, it can be extended for broader use cases such as virtual mouse control, accessibility tools, and gesture-based navigation.
