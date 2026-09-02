# SAHAAY — Assistive Health & Emergency Safety AI Companion

> **"Help when you need it most."**  
> An accessible, multimodal health and safety companion built for campus emergencies, high-stress moments, and assistive first-aid guidance.

---

## 🌟 Key Features

- 🩹 **Step-by-Step Emergency Triage**: Calming, scannable first-aid guidance (*DO THIS NOW*, *AVOID*, *GET HELP IF*) with completion checkmarks.
- ⚡ **Multimodal & Voice Input**: Instant analysis of text descriptions, uploaded incident photos, and real-time microphone voice dictation (Web Speech API).
- 🌐 **7 Indian Local Languages**: Full native translations for **English, Hindi (हिन्दी), Bengali (বাংলা), Tamil (தமிழ்), Telugu (తెలుగు), Marathi (मराठी), and Kannada (ಕನ್ನಡ)**.
- 🔊 **Voice Audio Playback (TTS)**: Built-in Speech Synthesis audio player with animated equalizer waveforms.
- 🚨 **One-Tap Campus SOS**: Direct campus security dispatch beacon simulation with live emergency dialer (`tel:108` / `tel:112`).
- ♿ **Accessibility Suite ("Aa")**: Dynamic font scaling (100% to 130%), high-contrast WCAG AAA theme, reduce-motion toggle, and dyslexia high-legibility mode.
- 📖 **Offline Campus Safety Handbook**: 10 essential emergency & hazard guides searchable offline with zero network requirement.
- 🤖 **Hybrid Gemini AI Engine**: Integrated with Google Gemini 1.5/2.0 Flash for live multimodal intelligence with instant local heuristic fallback.

---

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS, Lucide Icons
- **APIs**: Web Speech Recognition, Web Speech Synthesis, Google Gemini Multimodal REST API
- **Deployment**: GitHub Pages / Vercel / Netlify

---

## 🚀 Getting Started

### 1. Clone & Install Dependencies
```bash
git clone https://github.com/<your-username>/sahaay.git
cd sahaay
npm install
```

### 2. Run Local Development Server
```bash
npm run dev
```
Open **`http://localhost:3000`** in your browser.

### 3. Build for Production
```bash
npm run build
```

---

## 🔒 Safety & Medical Disclaimer
SAHAAY provides general safety and first-aid guidance and does **not replace professional medical care, diagnosis, or emergency services**. In life-threatening emergencies, always dial national emergency dispatch (108 / 112 / 911) immediately.

---

## 📄 License
MIT License. Built for the Assistive Health & Emergency Safety Challenge.
