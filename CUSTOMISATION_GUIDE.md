# 🎨 Portfolio Customisation Guide
## Akhil Baluni — Data Analytics Portfolio

---

## 📁 How to Host on GitHub Pages (Step by Step)

1. Go to **github.com** → Sign up / Log in
2. Click **"New repository"** (green button)
3. Name it exactly: `your-username.github.io` (e.g. `akhilbaluni.github.io`)
4. Set it to **Public**, click **Create repository**
5. Click **"uploading an existing file"** → drag & drop your `index.html` file
6. Click **Commit changes**
7. Go to **Settings → Pages → Source → main branch → Save**
8. Your site will be live at `https://your-username.github.io` in ~2 minutes ✅

---

## ✏️ What to Customise (Search & Replace)

Open `index.html` in **Notepad** (right-click → Open with → Notepad)

Use **Ctrl+H** to Find and Replace:

| Find this | Replace with |
|-----------|-------------|
| `akhilbaluni1729@gmail.com` | Your actual email |
| `linkedin.com/in/akhilbaluni` | Your LinkedIn URL |
| `akhilbaluniportfolio.blogspot.com` | Your blog/portfolio URL |
| `Dehradun, India` | Your city |

---

## 📊 Adding Real Projects (Most Important!)

Find this section in the file:
```
<!-- CUSTOMISE: Replace these with your real projects -->
```

For each project card, change:
- **Project tag** (e.g. `Excel · Data Analysis`) → your tool combination
- **Title** → your project name
- **Description** → 2–3 sentences about what you did and what you found
- **Tool tags** → tools you actually used
- **`href="#"`** → link to your project file / Google Drive / GitHub

**Good project ideas to add:**
- Excel dashboard with real data (download free datasets from Kaggle.com)
- Data cleaning exercise (messy CSV → clean table)
- Any college assignment involving numbers or statistics

---

## 🔢 Updating Skill Percentages

Find the Skills section. Each bar looks like:
```html
<label>Microsoft Excel <span>80%</span></label>
<div class="bar-bg"><div class="bar-fill" style="width:80%"></div></div>
```
Change both the `80%` text AND the `width:80%` to match your honest level.

---

## 📈 Hero Stats (Top Numbers)

Find:
```html
<div class="stat-num">3<span>+</span></div>
<div class="stat-label">Projects Completed</div>
```
Update the numbers as your portfolio grows.

---

## 🎨 Changing the Colour Accent

Find this near the top of the file:
```css
--accent: #5B6AF5;   /* Main purple-blue */
--accent2: #8B5CF6;  /* Secondary purple */
```

Alternative colour combos:
- **Teal:** `--accent: #0EA5E9` + `--accent2: #22D3EE`
- **Green:** `--accent: #10B981` + `--accent2: #34D399`
- **Orange:** `--accent: #F59E0B` + `--accent2: #EF4444`

---

## 📬 Making the Contact Form Actually Send Emails

1. Go to **formspree.io** → Sign up free
2. Create a new form → Copy your form endpoint URL
3. In `index.html`, find the Send Message button and change it from:
```html
<a href="mailto:..." class="btn-primary" ...>
```
to a real `<form>` element pointing to your Formspree URL.
(Or just keep the mailto: link — it opens the visitor's email app)

---

## ➕ Adding More Sections Later

Suggested additions as you grow:
- **Certifications** section (Google Data Analytics, Excel on LinkedIn Learning, etc.)
- **Blog** section linking to your Blogger posts
- **Resume download** button (upload your PDF to GitHub, link to it)

---

## 💡 Free Resources to Add Real Projects

| Site | What to get |
|------|------------|
| kaggle.com/datasets | Free datasets to analyse |
| google.com/analytics/learn | Free Google Analytics course |
| learn.microsoft.com | Free Excel/Power BI courses |
| coursera.org | Google Data Analytics Certificate |

---

## 🚀 Quick Wins to Do Today

- [ ] Replace placeholder project descriptions with real ones
- [ ] Update the email, LinkedIn, and blog links
- [ ] Upload to GitHub Pages
- [ ] Share the live link on your LinkedIn profile ("Portfolio" section)

---

*Made with ❤️ — your portfolio will grow as you do. Update it every time you complete a new project or learn a new tool.*
