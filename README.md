# 🌻 Garden Notebook

**Grow your days, one garden at a time.**

Garden Notebook transforms boring productivity tracking into a delightful, visual garden ecosystem. Each of your life areas becomes a unique garden space that grows as you make progress.

---

## 🌲 Four Gardens, One Notebook

| Garden | Purpose | Visual Reward |
|--------|---------|----------------|
| **To-Do Forest** | Task management | Complete tasks → trees grow from sprouts |
| **Habit Greenhouse** | Weekly habit tracking | Fill daily circles → plants flourish from seedling to lush |
| **Monthly Flowerbed** | Event & memory logging | Each event blooms as a colorful flower on your calendar |
| **Weekly Meadow** | Social & goal planning | Add plans → adorable animal friends visit |

---

## ✨ Features

- 🎨 **Beautiful visual feedback** — watch your gardens grow in real-time
- 💾 **Local storage** — your data stays in your browser, no account needed
- 📄 **Landscape PDF export** — preserves the full layout as horizontal A4 pages
- 🌍 **Timezone-aware** — shows your correct local date (no off-by-one errors)
- 📱 **Responsive design** — works on desktop, tablet, and mobile
- 🎭 **Four interactive tabs** — each with unique animations and mechanics

---

## 🛠️ How to Use

1. Open `index.html` in any modern browser
2. Add tasks, habits, events, and weekly plans
3. Complete items to see your garden flourish
4. Click "Export Gardens to PDF" for a printable landscape report

No installation, no dependencies — just pure HTML/CSS/JS.

---

## 📸 Visual Preview

*(Add actual screenshots here)*

| To-Do Forest | Habit Greenhouse |
|--------------|------------------|
| 🌲🌳🌴 | 🌱🌿🌳 |

| Monthly Flowerbed | Weekly Meadow |
|------------------|---------------|
| 🌸🌹🌷🌼🌻🌺 | 🐇🦋🦊🐸 |

---

## 🧩 File Structure
garden-notebook/
├── garden-notebook.html
├── README.md # This file
└── sample-export.pdf # sample document exported from the web
---

## 🔧 Local Development

Just clone and open:

```bash
git clone https://github.com/your-username/garden-notebook.git
cd garden-notebook
# Open index.html in your browser
Or use Live Server in VS Code.
```
---
## 📄 PDF Export
The app uses html2pdf.js to generate landscape A4 PDFs that preserve:
1. All four garden sections with page breaks
2. Visual plant growth states
3. Calendar grids and timelines
4. Meadow animal positions

---

## 🗃️ Data Persistence
All data is saved to localStorage under the key garden-notebook-v1. Clear your browser data to reset.

## 🎨 Customization
You can easily modify:
Colors — Edit CSS variables in :root
Plant icons — Change emoji mappings in the TREES, FLOWERS, ANIMALS objects
PDF layout — Adjust orientation and margin in the export function

## 📝 License
MIT — free to use, modify, and share.

## 🙏 Acknowledgments
Icons via Unicode emojis 🌱
PDF generation by html2pdf.js
Inspired by gamified productivity and nature-themed planners

## 📬 Feedback
Found a bug or have an idea? Open an issue or submit a pull request.

### Plant today. Bloom tomorrow. 🌸
