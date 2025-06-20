# 📋 កម្មវិធីកត់ត្រាកិច្ចប្រជុំឆ្លាតវៃ (Smart Meeting Notes App)

A modern Khmer-language smart meeting note app with speech-to-text, Gemini AI summary, and Firebase integration.

## 🌟 Features

- 🎙️ Record voice (Khmer) using your microphone
- ✍️ Live transcript into editable note
- 🔐 Firebase anonymous auth & Firestore data storage
- ✨ Gemini AI: Summarize and extract action items
- 💾 Save, edit, and delete notes (auto-sync)
- 📦 Responsive UI with Tailwind CSS

## 🚀 Live Demo

👉 Visit: [https://your-username.github.io/smart-meeting-notes/](https://your-username.github.io/smart-meeting-notes/)

> Note: You must configure your Firebase credentials and Gemini API key inside `index.html`.

## 📦 How to Deploy on GitHub Pages

1. Clone this repo:
    ```bash
    git clone https://github.com/your-username/smart-meeting-notes.git
    cd smart-meeting-notes
    ```

2. Add your `index.html` inside the `/docs` folder.

3. Push to GitHub:
    ```bash
    git add .
    git commit -m "Initial deploy"
    git push origin main
    ```

4. Go to **Settings > Pages** → Source: `/docs` → Save

## 🛡️ Security Notes

- **Do NOT expose your Gemini API key** in public repositories.
- Use Firestore Rules to protect read/write based on `auth.uid`.

## 🧠 Built With

- HTML5 / Tailwind CSS
- Firebase Auth & Firestore
- Gemini 1.5 Pro API
- Vanilla JavaScript
- Khmer language support (SpeechRecognition `km-KH`)

## ✨ License

MIT © 2025
