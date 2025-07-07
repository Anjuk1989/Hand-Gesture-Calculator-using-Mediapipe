✋ Gesture-Controlled Calculator using MediaPipe and OpenCV
This is a real-time gesture-based calculator built using MediaPipe and OpenCV. It allows users to perform arithmetic operations like addition, subtraction, multiplication, and division 
using just their hand gestures—no touch or voice input required!

📌 Features
🔢 Detects hand gestures for numbers 0 to 9
➕➖✖️➗ Recognizes operators: +, -, *, /
✅ Performs calculation on showing 'equal to' (=) gesture
🔄 Undo gesture to delete last input
🤚 Uses right hand for number input
✋ Uses left hand for operators and functions
⚡ Smooth and stable gesture detection using buffer and cooldown logic

🛠️ Tech Stack
Python
OpenCV
MediaPipe for hand tracking
NumPy

🧠 Gesture Mapping
Right Hand Fingers	Output
0 to 5	            Digits 0–5
1–4 + Left = 5	    Digits 6–9

Left Hand Fingers	Output
1	                  +
2                  	-
3                  	*
4	                  /
5	                  =
0                  	Undo

🙏 Acknowledgements
Special thanks to Dixson Sir for the guidance and to Rakesh Sir and Neethu Ma'am for the constant support throughout the project.

