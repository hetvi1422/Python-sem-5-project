# 🧟 Zombie Math Run

An interactive **math-based survival game** built with **Python (FastAPI)** and **HTML/CSS/JavaScript**. Solve math questions within limited chances—every wrong answer brings the zombie closer. Answer correctly, gain points, and survive. Fail too often… and the zombie catches you. 😱

---

## 🎮 Game Concept

* Random math questions are generated (Addition, Subtraction, Multiplication)
* The **player** and a **computer opponent** answer questions
* Correct answers keep the zombie away ❌🧟
* Wrong answers reduce your distance from the zombie
* If the zombie comes too close → **Game Over**
* Answer **10 questions** to determine win or loss

---

## 🛠️ Tech Stack

* **Backend**: Python, FastAPI
* **Frontend**: HTML, CSS, JavaScript
* **Server**: Uvicorn
* **Game Logic**: Python

---

## 📁 Project Structure

```text
Zombie_Math_Run/
│
├── temp/
│   ├── __pycache__/
│   │   ├── main.cpython-311.pyc
│   │   └── main.cpython-313.pyc
│   │
│   ├── images/                 # Game images
│   │   ├── zombai.png
│   │   └── man.jpeg
│   │
│   ├── index.html              # Frontend UI
│   ├── main.py                 # FastAPI backend & game logic
│   └── commands to run.txt     # Command to start the server
│
├── requirements.txt            # Python dependencies
├── venv/                       # Virtual environment (ignored)
└── README.md
```

> ⚠️ **Note:** `__pycache__`, `temp/`, and `venv/` folders should be ignored using `.gitignore`.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/zombie-math-run.git
cd zombie-math-run
```

### 2️⃣ Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate # macOS/Linux
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run the Project

Use the following command (already provided in `commands to run.txt`):

```bash
uvicorn main:app --reload
```

Then open your browser and go to:

```
http://127.0.0.1:8000
```

---

## 🧠 Game Rules

* You start at a safe distance from the zombie
* Each **wrong answer** decreases your distance
* If distance `< 3` → Zombie attacks 🧟💀
* Correct answers increase your score
* Win condition:

  * Answer at least **7 out of 10** correctly
  * Zombie must not reach you

---

## ✨ Features

* 🎲 Random math question generation
* ⏱️ Turn-based gameplay
* 🧟 Animated zombie attack when close
* 📊 Live stats: distance, score, status
* 🧠 Computer opponent with configurable accuracy
* 🔄 Reset & restart game anytime

---

## 🚀 Future Improvements

* Add difficulty levels (Easy / Medium / Hard)
* Add timer-based answering
* Add sound effects & background music
* Add leaderboard system
* Convert frontend to React

---

## 📌 Notes

* This project is ideal for:

  * Python beginners
  * FastAPI practice
  * Game logic implementation
  * Mini-project / college submission

---

## 👨‍💻 Author

**Hetvi Belani**
IT Student | Python Developer | Game & AI Enthusiast

---

🧟‍♂️ *Run fast. Think faster. Math saves lives.* 🧠
