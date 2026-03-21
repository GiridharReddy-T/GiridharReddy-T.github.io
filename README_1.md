# Giridhar Reddy — Portfolio

Live portfolio with **auto-updating GitHub repos** and a single `data.json` config file.

---

## 📁 Files

```
portfolio/
├── index.html      ← The website (never need to touch this)
└── data.json       ← YOUR SOURCE OF TRUTH — edit this for all updates
```

---

## 🚀 Go Live in 3 Steps (GitHub Pages — Free)

### Step 1 — Create a GitHub repo
1. Go to github.com → click **New repository**
2. Name it exactly: `GiridharReddy-T.github.io`  
   *(replace with your actual GitHub username)*
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload your files
1. Click **Add file → Upload files**
2. Drag both `index.html` and `data.json`
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to repo **Settings → Pages**
2. Under Source, select **main branch**
3. Click **Save**

✅ Your site will be live at:  
`https://GiridharReddy-T.github.io` within 2 minutes!

---

## ✏️ How to Update Content

### Add a new certification
Open `data.json`, find `"certifications"` and add a new entry:
```json
{
  "title": "Your New Certification Name",
  "issuer": "Issuing Organization",
  "icon": "🏆",
  "year": "2025"
}
```
Save → push to GitHub → site updates automatically.

---

### Add new work experience
Find `"experience"` array and add at the top (most recent first):
```json
{
  "company": "Company Name",
  "badge": "",
  "role": "Your Role",
  "period": "Jan 2026 – Present",
  "duration": "X mos",
  "location": "City, State, India",
  "tags": ["Tech1","Tech2","Tech3"],
  "bullets": [
    "What you did and the <strong>impact it had</strong>.",
    "Another bullet with <strong>key metric</strong>."
  ]
}
```

---

### Add a new project
Find `"projects"` array and add:
```json
{
  "title": "Your Project Name",
  "type": "Personal Project",
  "icon": "🔥",
  "github_repo": "https://github.com/GiridharReddy-T/your-repo",
  "description": "One sentence about what it does.",
  "bullets": [
    "What you built and <strong>how</strong>.",
    "What technologies you used.",
    "What results or impact it had."
  ],
  "tags": ["Python","Spark","Kafka"]
}
```

---

### GitHub repos — FULLY AUTOMATIC
No action needed. The website calls the GitHub API live every time someone visits.  
Any new public repo you create on GitHub will appear on the site automatically.

---

### Update your stats / headline numbers
Find `"stats"` array and edit the values:
```json
{ "value": "15M+", "label": "Daily Transactions", "sub": "New project context" }
```

---

## 🔄 Publishing Updates

After editing `data.json`:
1. Go to your GitHub repo
2. Click `data.json` → click the ✏️ pencil icon
3. Make your changes
4. Click **Commit changes**

Site updates in ~30 seconds. No code knowledge needed.

---

## 💡 Tips

- **Icons**: Use any emoji as the `"icon"` field for certs/projects
- **Bold text**: Wrap words in `<strong>text</strong>` inside bullet strings  
- **Core skills** (shown highlighted in yellow): edit the `"core_skills"` array
- **Order matters**: Items appear in the order listed in the JSON arrays

---

*Built with pure HTML/CSS/JS — no frameworks, no build step, no dependencies.*
