
# ☀️ Solar Cost Analysis Tool

[![Made with: HTML/CSS/JS](https://img.shields.io/badge/Made%20with-HTML%20%7C%20CSS%20%7C%20JS-blue)](#)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Star this repo](https://img.shields.io/github/stars/Shrv03/Solar-Cost-Analysis-Tool?style=social)](https://github.com/Shrv03/Solar-Cost-Analysis-Tool/stargazers)

> A simple, browser-based tool to **compare on-grid vs off-grid solar systems**, estimate **net-metering credits**, and compute **payback period**—designed to be easily understood by anyone.

---

## 🌟 Live Demo (GitHub Pages)

Once enabled, your site will be here:  
`https://Shrv03.github.io/Solar-Cost-Analysis-Tool/`

> Enable it via **Settings → Pages → Branch: `main` / root → Save**.

---

## ✨ Features

- 🔋 **On-Grid vs Off-Grid** side-by-side cost & savings comparison  
- 💳 **Net-Metering Credits** estimation (exported energy → bill credit)  
- 📉 **Payback Period** & simple ROI  
- 📊 **Beginner-friendly UI** (single HTML file, no install)  
- 🌓 Built-in **dark mode** ready styles (optional)

---

## 🔧 How to Use

1. **Clone or download** the repo  
   ```bash
   git clone https://github.com/Shrv03/Solar-Cost-Analysis-Tool.git
   cd Solar-Cost-Analysis-Tool
````

2. **Open** `index.html` in any modern browser.
3. Enter:

   * System cost, incentives/rebates
   * Local tariff ($/kWh)
   * Annual generation (kWh) and self-consumption %
   * Export rate or net-metering rules
4. View results: **Annual savings, credits, net cashflow, payback years**.

---

## 🧮 Behind the Numbers (Formulas)

Let

* `CapEx` = upfront cost − incentives
* `Gen` = annual generation (kWh)
* `Self%` = % of Gen consumed on-site
* `Tariff` = grid electricity price ($/kWh)
* `ExportRate` = credit for exported energy ($/kWh)
* `FixedOM` = annual O&M ($)

Then

* `SelfUse = Gen × Self%`
* `Export = Gen − SelfUse`
* **Savings = SelfUse × Tariff**
* **Credits (net-metering) = Export × ExportRate**
* **Annual Net = Savings + Credits − FixedOM**
* **Simple Payback (yrs) = CapEx / Annual Net**

> You can adapt `ExportRate` to model full-retail net metering (set equal to `Tariff`) or reduced credit programs.

---

## 📂 Project Structure

```
Solar-Cost-Analysis-Tool/
├─ index.html      # Main web app (calculator UI + logic)
└─ README.md       # This file
```

---

## 🖼️ Screenshots

> Replace the placeholder below with a real screenshot after your first run.

![Demo Screenshot](https://via.placeholder.com/1200x520?text=Solar+Cost+Analysis+Tool+Demo)

---

## 🚀 Roadmap

* [ ] Interactive charts (cashflow, cumulative savings, payback)
* [ ] Region presets (typical irradiance & tariffs)
* [ ] Battery sizing helper (for off-grid/hybrid)
* [ ] Export results to CSV/PDF
* [ ] “What-if” sliders for sensitivity analysis

---

## 🤝 Contributing

1. **Fork** this repo
2. Create a feature branch: `git checkout -b feature/amazing-idea`
3. **Commit** changes: `git commit -m "Add amazing idea"`
4. **Push**: `git push origin feature/amazing-idea`
5. Open a **Pull Request** 🎉

---

## 📜 License

This project is released under the **MIT License**. See `LICENSE` for details.

---

## 💬 Acknowledgments

* Inspired by community efforts to simplify **solar economics** for homeowners and students.
* Icons/emoji via GitHub markdown.

---

## ❤️ Support

If this helps you, please **star ⭐ the repo** and share it with others interested in solar!

```

If you’d like, I can also provide a clean, ready-to-use `index.html` with inputs + live calculations and a minimal dark theme.
```
