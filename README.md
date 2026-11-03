# ✋ Hand Connect – Real-Time Hand VFX System

A real-time computer vision application that tracks hand movements using a webcam and creates stunning neon visual effects. The project uses OpenCV and MediaPipe to detect hand landmarks and render glowing skeletons, energy beams, magical shields, and animated aura effects.

## 🚀 Features

- **Real-Time Hand Tracking:** Detects and tracks up to two hands using MediaPipe.
- **Neon Hand Skeleton:** Displays glowing neon lines connecting hand landmarks.
- **Dynamic Aura Effect:** Creates a pulsing neon aura around the palm.
- **Finger-to-Finger Energy Beams:** Connects corresponding fingertips of two detected hands with colorful neon beams.
- **Energy Join Effect:** Creates glowing energy bursts when corresponding fingertips come close.
- **Magic Shield Effect:** Displays an animated magical shield when one open palm is detected.
- **Cinematic Visual Effects:** Adds bloom, glow, and cinematic color effects.
- **Interactive Controls:** Enable or disable visual effects using keyboard shortcuts.

## 🛠️ Technologies Used

- Python 3.12
- OpenCV
- MediaPipe
- NumPy
- Math
- Random
- Time

## 📸 Project Features

### 1. Hand Tracking
Uses MediaPipe Hands to detect 21 landmarks on each hand in real time.

### 2. Neon Skeleton
Connects hand landmarks using multiple glowing layers to create a neon skeleton effect.

### 3. Magic Shield
Creates a rotating magical circular shield when an open palm is detected.

### 4. Energy Beam
Connects fingertips between two hands with colorful glowing energy beams.

### 5. Dynamic Aura
Creates a soft, pulsing aura around the palm center.

## ⚙️ Installation and Setup

### Prerequisites
- Python 3.12
- Webcam
- VS Code or any Python IDE

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

```bash
cd Hand-connect-project
```

### Step 2: Create a Virtual Environment

```bash
python3.12 -m venv mp_env
```

### Step 3: Activate the Environment

For macOS/Linux:

```bash
source mp_env/bin/activate
```

### Step 4: Install Dependencies

```bash
python -m pip install mediapipe opencv-python numpy
```

### Step 5: Run the Application

```bash
python main.py
```

Allow camera access if macOS asks for permission.

## ⌨️ Keyboard Controls

| Key | Function |
|---|---|
| `q` | Quit the application |
| `a` | Toggle Aura Effect |
| `b` | Toggle Energy Beam |
| `s` | Toggle Magic Shield |

## 📁 Project Structure

```text
Hand-connect-project/
│
├── main.py
├── mp_env/
└── README.md
```

`mp_env` is the local virtual environment. It should not be uploaded to GitHub.

## 🎯 How It Works

1. The webcam captures live video frames.
2. OpenCV processes the captured frames.
3. MediaPipe detects hand landmarks.
4. The application calculates landmark positions.
5. NeonRenderer draws glowing hand skeletons and aura effects.
6. BeamEffect connects fingertips between two hands.
7. MagicShieldEffect detects an open palm and renders an animated shield.
8. The final frame is displayed in real time.

## 🔮 Future Improvements

- Add more hand gesture recognition features.
- Introduce customizable neon colors.
- Improve tracking performance and frame rate.
- Add more interactive visual effects.
- Support gesture-based application controls.

## 👨‍💻 Author

**Daksh Gupta**

Computer Science Engineering Student

## ⭐ Acknowledgements

- [MediaPipe](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker)
- [OpenCV](https://opencv.org/)
- [NumPy](https://numpy.org/)

---

If you like this project, consider giving it a ⭐ on GitHub!
