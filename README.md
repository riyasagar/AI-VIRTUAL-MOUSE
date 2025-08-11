# AI Virtual Mouse 🖱️🤖

This project implements an **AI-powered virtual mouse** using computer vision and hand tracking.  
It allows you to control your computer's mouse pointer with **hand gestures**, removing the need for a physical mouse.

---

## 🚀 Features
- Hand tracking using OpenCV and Mediapipe.
- Real-time gesture recognition.
- Move the cursor with finger movements.
- Perform left and right clicks using gestures.
- Works with a standard webcam.

---

## 🛠️ Technologies Used
- **Python 3.x**
- **OpenCV** – Image processing and video capture.
- **Mediapipe** – Hand tracking and landmark detection.
- **PyAutoGUI** – Control mouse actions.
- **NumPy** – Mathematical operations.

---

## 📂 Project Structure
```

├── .gitattributes       # Git attributes configuration
├── .gitignore           # Files/folders to be ignored by Git
├── LICENSE              # Project license
├── README.md            # Project documentation
└── ai\_virtual\_mouse.py  # Main AI Virtual Mouse script

````

---

## 📦 Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/riyasagar/ai-virtual-mouse.git
   cd ai-virtual-mouse

2. **Install dependencies**:

   ```bash
   pip install opencv-python mediapipe pyautogui numpy
   ```

---

## ▶️ Usage

Run the script:

```bash
python ai_virtual_mouse.py
```

* Ensure your webcam is connected and working.
* Show your hand in front of the camera.
* Move your index finger to control the cursor.
* Pinch or tap gestures to click.

---

## 📜 License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

---

## 🙌 Acknowledgments

* [Mediapipe](https://mediapipe.dev/) for hand tracking solutions.
* [OpenCV](https://opencv.org/) for computer vision tools.
* [PyAutoGUI](https://pyautogui.readthedocs.io/) for mouse control.

```
