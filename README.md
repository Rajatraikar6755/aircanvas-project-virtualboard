Here’s the updated README with the correct file name:  

---

# AirCanvas Project - Virtual Board 🎨✋  

This is a **Hand Gesture Drawing Application** built using **OpenCV** and **Mediapipe**. It allows users to draw on a virtual canvas using hand gestures detected by a webcam.  

## Features  
✅ **Hand Tracking** – Uses Mediapipe to detect hand landmarks.  
✅ **Drawing with Finger Gestures** – Draw by moving your index finger.  
✅ **Color Selection** – Choose colors from a predefined palette.  
✅ **Eraser Tool** – Erase parts of the drawing.  
✅ **Brush Size Selection** – Change brush thickness.  
✅ **Clear Canvas** – Reset the canvas.  

## Requirements  
Ensure you have **Python 3.x** installed along with the required dependencies:  

```bash
pip install opencv-python mediapipe numpy
```  

## How to Run  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/Rajatraikar6755/aircanvas-project-virtualboard.git
   cd aircanvas-project-virtualboard
   ```  
2. **Run the script**  
   ```bash
   python main.py
   ```  

## Usage Instructions  
- **Index Finger Up** → Draw on the canvas.  
- **Index & Middle Finger Up** → Select colors or tools.  
- **Thumb Gesture** → Detects extra movements (like thumb positioning).  
- **"Eraser" Button** → Allows erasing drawings.  
- **"Clear" Button** → Clears the entire canvas.  

## Demo  
![Demo GIF](demo.gif)  

## Future Enhancements  
🔹 Adding gesture-based undo/redo functionality.  
🔹 Implementing shape recognition (circles, squares, etc.).  
🔹 Saving the drawing as an image file.  

---

Let me know if you need any modifications! 🚀
