# OSAP Optimizer 🦉
**DeltaHacks 2026** - A Stardew Valley-inspired OSAP loan repayment calculator

## What it does
Helps Ontario students visualize and optimize their OSAP debt repayment with:
- 📊 Three payment scenarios (minimum, balanced, aggressive)
- 🛡️ RAP (Repayment Assistance Plan) eligibility checker
- 📈 Interactive payoff timeline chart
- 💬 AI-powered advice from Professor Hootsworth (Gemini)
- 🔊 Text-to-speech dialogue (ElevenLabs)
- 💾 Save/load plans via MongoDB Atlas
- 👥 Community comparison stats

## Tech Stack
- **Backend:** Flask, Python
- **Frontend:** HTML/CSS/JS, Chart.js
- **Database:** MongoDB Atlas
- **AI:** Google Gemini API
- **TTS:** ElevenLabs API

## Team
- Shayan Jalali
- Frank Lin
- Avaansh Nanda

## Run locally
```bash
pip install -r requirements.txt
python app.py
```

Then visit `http://localhost:5000`