# Grammar Practice App

This is a web-based interactive grammar practice tool for students. It allows teachers to group questions by topic and enables students to track their progress locally in the browser.

---

## ✅ Features

- Local progress tracking per topic
- Student-friendly dashboard with progress bars
- Confetti animation on completion 🎉
- Reset progress button
- Loads questions dynamically from an external JSON file (`questions.json`)

---

## 📁 Files to Include

- `index.html` — the main student-facing app (rename `index-json-enabled.html` to `index.html`)
- `questions.json` — your external question bank (must be in the same folder as `index.html`)

---

## ✏️ Editing `questions.json`

Structure:
```json
{
  "Topic Name": [
    {
      "text": "The sentence to display.",
      "incorrectIndex": 3
    }
  ]
}
```

- `"text"`: the full sentence shown to students
- `"incorrectIndex"`: the index (starting from 0) of the incorrect word or punctuation mark, using the app's token preview

💡 You can use the **teacher tool** version of the app to help preview token indices.

---

## 🚀 Hosting on GitHub Pages

1. Create a new GitHub repository
2. Upload both `index.html` and `questions.json`
3. Go to **Settings > Pages**
4. Set source to `main` branch, folder = `/root`
5. Access your site at `https://yourusername.github.io/your-repo-name/`

---

## 📌 Note

- No login or account required for students
- Progress is saved locally in each student’s browser
- Compatible with Chrome, Safari, Firefox, and Edge

---

## 👩‍🏫 Created with ❤️ for educators
