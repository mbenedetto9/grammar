# Grammar Practice App (Self-Contained Version)

This is a web-based interactive grammar practice tool for students. It allows teachers to group questions by topic and enables students to track their progress locally in the browser.

This version is completely self-contained — all questions are embedded directly into the HTML file.

---

## ✅ Features

- Local progress tracking per topic
- Student-friendly dashboard with progress bars
- Confetti animation on completion 🎉
- Reset progress button
- No external files required

---

## 📁 Files to Include

- `index.html` — the full app with questions built in (you can rename `index-embedded.html` to `index.html`)

---

## ✏️ Editing the Questions

Inside the `index.html` file, scroll to the very bottom. You’ll see this block:
```html
<script id="questions-json" type="application/json">
{
  "Pronouns": [
    {
      "text": "Everyone should bring their own pencil.",
      "incorrectIndex": 4
    }
  ],
  ...
}
</script>
```

To add or edit questions:
- Copy or change entries within the JSON object
- Be careful to match the formatting (quotes, commas, brackets)
- Save the file and re-upload to GitHub

💡 You can use a free online tool like [https://jsonlint.com](https://jsonlint.com) to validate your changes before saving.

---

## 🚀 Hosting on GitHub Pages

1. Create or open a GitHub repository
2. Upload `index.html`
3. Go to **Settings > Pages**
4. Set source to `main` branch, folder = `/root`
5. Access your site at:  
   `https://yourusername.github.io/your-repo-name/`

---

## 🧠 Notes

- No login or account required for students
- Progress is saved in the student’s browser
- Compatible with Chrome, Safari, Firefox, Edge
- Designed for classroom simplicity and reliability

---

## 👩‍🏫 Built for Teachers, Powered by HTML + JS
