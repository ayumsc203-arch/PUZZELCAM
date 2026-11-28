# 🧩 PUZZELCAM – AI Webcam Puzzle Challenge

<p align="center">
  <b>Turn your webcam photos into interactive puzzles!</b>
</p>

PUZZELCAM is a Python-based interactive puzzle game that transforms webcam captures into scrambled image puzzles. Players can solve puzzles using interactive controls, customize their gaming experience, and track their performance through scores and statistics.

The application combines computer vision, webcam integration, and an interactive desktop interface to create an engaging puzzle-solving experience.

## ✨ Features

- 📸 **Webcam Integration:** Capture images directly using your webcam.
- 🧩 **Image Puzzle Generation:** Convert captured images into scrambled puzzle grids.
- 🎮 **Interactive Gameplay:** Arrange puzzle pieces to reconstruct the original image.
- 🔄 **Rotation Mode:** Enable additional puzzle challenges with rotation.
- 📐 **Adjustable Difficulty:** Customize the puzzle grid size.
- ✋ **Hand Tracking:** Optional hand-tracking support for gesture-based interaction.
- 🎨 **Multiple Themes:** Choose from different interface styles.
- 🔊 **Sound Effects:** Interactive sounds for clicks, movements, countdowns, and victories.
- 🏆 **Leaderboard:** Save and view puzzle scores.
- 📊 **Game Statistics:** Track gameplay performance and achievements.
- ⚙️ **Custom Settings:** Configure camera, sound, themes, filters, and gameplay preferences.
- 📖 **Game Guide:** Built-in instructions to help players understand the game.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core application development |
| PyQt6 | Desktop GUI development |
| OpenCV | Webcam integration and image processing |
| NumPy | Image and array operations |
| Pillow (PIL) | Image processing |
| MediaPipe (Optional) | Hand tracking |
| JSON | Configuration and leaderboard data |

## 🎨 Available Themes

PUZZELCAM provides multiple visual themes:

- Dark Mode
- Cyber Neon
- Frost Glass
- 8-Bit Retro

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/ayumsc203-arch/PUZZELCAM.git
```

### 2. Navigate to the Project Folder

```bash
cd PUZZELCAM
```

### 3. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate it:

**Windows:**
```bash
venv\Scripts\activate
```

**macOS / Linux:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
python main.py
```

## 📁 Project Structure

```text
PUZZELCAM/
│
├── assets/
│   └── sounds/
│
├── core/
│   ├── camera.py
│   └── ui.py
│
├── utils/
│   ├── helpers.py
│   └── generate_sounds.py
│
├── config.json
├── leaderboard.json
├── main.py
├── requirements.txt
└── README.md
```

*Note: Additional modules and screens are organized within the project directories.*

## 💻 System Requirements

- Python 3.10 or compatible version
- Windows / macOS / Linux
- Webcam
- Working microphone is not required
- Internet connection is not required for the core gameplay after dependencies are installed.

**Recommended:** A desktop or laptop with a webcam for the best experience.

## 🎯 Project Objectives

- Explore computer vision and real-time webcam processing.
- Develop an interactive desktop application using Python.
- Understand image manipulation and puzzle generation.
- Implement game logic, scoring, and statistics tracking.
- Experiment with gesture-based interaction.
- Improve GUI development and user experience skills.

## 🔮 Future Improvements

- Add more puzzle grid sizes and difficulty levels.
- Improve gesture recognition and hand controls.
- Introduce additional image filters and effects.
- Add more puzzle-solving challenges.
- Improve animations and visual feedback.
- Add more gameplay achievements.

## 👩‍💻 Developer

**Ayushi Sindha**

MSc IT Student | Python Developer | Aspiring Software Developer

- GitHub: [@ayumsc203-arch](https://github.com/ayumsc203-arch)
- LinkedIn: [Ayushi Sindha](https://www.linkedin.com/in/ayushi-sindha/)
- Portfolio: [Visit My Portfolio](https://ayucraft.netlify.app)

---

<p align="center">
  ⭐ If you like this project, consider giving it a star!
  <br>
  <b>Built with Python, creativity, and a passion for problem-solving. ❤️</b>
</p>
