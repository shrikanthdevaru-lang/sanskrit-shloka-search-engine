# 🕉️ Sanskrit Shloka Finder

> **Search thousands of Sanskrit shlokas from all major scriptures — Bhagavad Gita, Ramayana, Mahabharata, Upanishads, Vedas, Chanakya Niti — instantly, by typing a single word.**

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-Sanskrit%20Shloka%20Finder-gold?style=for-the-badge)](https://shrikanthdevaru-lang.github.io/dr-saroj-kumar-padhi-portfolio/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-green?style=for-the-badge)](https://pages.github.com/)

---

## ✨ Features

| Feature | Description |
|---|---|
| ⚡ **Instant Search** | Results appear as you type — no submit needed |
| 🔤 **Multi-Script** | Search in Sanskrit (Devanagari), IAST transliteration, or English |
| 📚 **12+ Scriptures** | Bhagavad Gita, Ramayana, Mahabharata, Upanishads, Rig/Yajur/Atharva Veda, Chanakya Niti, and more |
| 📍 **Full Source** | Every shloka shows Scripture name + Chapter + Verse reference |
| 🎯 **Topic Browse** | Browse by Dharma, Karma, Bhakti, Jnana, Shanti, Yoga, etc. |
| 🌅 **Daily Shloka** | A different shloka featured every day |
| 📋 **Copy & Share** | One-click copy or share any shloka |
| 📱 **Responsive** | Works beautifully on mobile, tablet, and desktop |
| 🌙 **Dark Theme** | Premium deep-space dark UI with gold Devanagari aesthetics |

---

## 🔍 How to Use

1. **Type any word** in the search box — Sanskrit, IAST, or English
   - Example: `dharma`, `karma`, `अर्जुन`, `peace`, `light`, `tat tvam`
2. **Filter by scripture** using the tabs below the search bar
3. **Browse topics** like Karma, Bhakti, Yoga by scrolling down
4. **Copy or Share** any shloka using the action buttons on each card

---

## 📖 Scriptures Included

| Scripture | Shlokas | Language |
|---|---|---|
| Bhagavad Gita | 700 (all chapters) | Sanskrit + English |
| Valmiki Ramayana | Selected | Sanskrit + English |
| Mahabharata | Selected | Sanskrit + English |
| Brihadaranyaka Upanishad | Key verses | Sanskrit + English |
| Chandogya Upanishad | Key verses | Sanskrit + English |
| Mandukya Upanishad | All verses | Sanskrit + English |
| Katha Upanishad | Key verses | Sanskrit + English |
| Isha Upanishad | Key verses | Sanskrit + English |
| Mundaka Upanishad | Key verses | Sanskrit + English |
| Rig Veda | Selected hymns | Sanskrit + English |
| Yajur Veda | Selected | Sanskrit + English |
| Atharva Veda | Selected | Sanskrit + English |
| Chanakya Niti | Selected | Sanskrit + English |
| Yoga Sutras of Patanjali | Selected | Sanskrit + English |
| Hitopadesha | Selected | Sanskrit + English |
| Vishnu Sahasranama | Selected | Sanskrit + English |

---

## 🚀 Quick Start (Local)

No server or build step required! Simply open the HTML file:

```bash
git clone https://github.com/shrikanthdevaru-lang/dr-saroj-kumar-padhi-portfolio.git
cd dr-saroj-kumar-padhi-portfolio
open index.html   # Mac
# or
start index.html  # Windows
# or
xdg-open index.html  # Linux
```

---

## 🌐 Deploy to GitHub Pages

1. Go to your repository **Settings**
2. Click **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Choose **`main`** branch and **`/ (root)`** folder
5. Click **Save**
6. Your site will be live at `https://YOUR_USERNAME.github.io/REPO_NAME/`

---

## 🛠️ Tech Stack

- **Pure HTML5 + CSS3 + Vanilla JavaScript** — zero dependencies
- **Google Fonts**: Noto Sans Devanagari, Cormorant Garamond, Space Mono, Inter
- **Canvas API**: Particle animation with floating Sanskrit characters
- **No backend required**: All shlokas are embedded as JSON in the HTML
- **GitHub Pages compatible**: Static site, no server needed

---

## 📊 Search Algorithm

The search engine scores results across multiple fields:

```
Score = Sanskrit match (3pts) + IAST match (2pts) + Translation match (1pt)
```

- **Sanskrit (Devanagari)**: Direct substring match with highest priority
- **IAST transliteration**: Romanized Sanskrit match
- **English translation**: Word/phrase match in the translation
- **Keywords**: Pre-tagged semantic keywords for each shloka
- **Tags**: Topic tags (dharma, karma, yoga, etc.)

---

## 📁 Project Structure

```
sanskrit-shloka-search-engine/
├── index.html          ← Complete app (all-in-one)
├── hero-bg.png         ← Hero background image (AI generated)
├── README.md           ← This file
└── .github/
    └── workflows/
        └── deploy.yml  ← GitHub Pages auto-deploy
```

---

## 🙏 Data Sources & Attribution

Shloka data is compiled from public domain and openly licensed sources:
- **GRETIL** (Göttingen Register of Electronic Texts in Indian Languages)
- **Sacred-texts.com** (Public domain translations)
- **DharmicData** (GitHub, MIT License)
- **SanskritSahitya.org** (Open access)
- **Traditional scholarly editions**

All Sanskrit texts are in the public domain. English translations are adapted from public domain translations by scholars such as Swami Prabhupada (for Bhagavad Gita), Ralph T.H. Griffith (for Vedas), and others.

---

## 🤝 Contributing

Contributions are welcome! To add more shlokas:

1. Fork the repository
2. Add shlokas to the `SHLOKAS` array in `index.html`
3. Follow the schema: `{ id, source, scripture, ref, tags, sanskrit, iast, translation, keywords }`
4. Submit a pull request

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

**ॐ सर्वे भवन्तु सुखिनः। सर्वे सन्तु निरामयाः।**
*May all beings be happy. May all beings be free from illness.*

Made with 🙏 for the preservation of Sanskrit wisdom

</div>
