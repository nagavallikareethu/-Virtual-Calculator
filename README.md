# 🧮 Virtual Calculator ✨

This is a **Virtual Calculator** built with **Streamlit**, **OpenCV**, **MediaPipe**, and **Google Generative AI**.
You can draw equations in the air with your fingers, and the app will analyze and solve them using Google Gemini!

---

## 📸 **Features**

✅ Hand gesture tracking with MediaPipe  
✅ Live webcam feed with OpenCV  
✅ Draw, erase, and reset with simple finger gestures  
✅ Analyze handwritten equations using Generative AI (Gemini)  
✅ Built with Streamlit for easy deployment

---

## 🚀 **Installation**

1️⃣ Clone the repository:
```bash
git clone https://github.com/nagavallikareethu/virtual-calculator.git
cd virtual-calculator
```
2️⃣ Create a virtual environment and activate it:
python -m venv venv
# Windows:
venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate


3️⃣ Install dependencies:
pip install -r requirements.txt

4️⃣ Set up your .env:
cp .env.example .env

▶️ Run the App
streamlit run calculator.py

💡 How It Works
The webcam captures your hand movements.

MediaPipe detects your hand landmarks.

Specific finger gestures let you:

Draw 🖊️

Erase 🧽

Clear 🗑️

The drawing is analyzed with Google Gemini to extract the equation and solve it.

📌 Finger Gestures
Thumb + Index Up: Draw mode

Thumb + Middle Up: Erase mode

Thumb + Pinky Up: Clear canvas

Index + Middle Up: Analyze equation
