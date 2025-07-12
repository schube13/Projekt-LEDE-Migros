# Projekt LEDE Migros
This is a personal project for LEDE at Columbia

# My Shopping Cart Got More Expensive, Right?

## 🛒 Project Summary

I wanted to choose a simple project that allowed me to apply many of the skills I’ve learned over the past weeks.

Recently, I noticed that the price of my coffee beans had risen significantly. I was genuinely surprised and wanted to understand why. Thanks to my loyalty card and the Migros app, I was able to download digital receipts from the last 2.5 years. My initial goal was to find out whether inflation in Switzerland, energy prices, or international coffee prices had any visible effect on the prices I was paying.

I had to limit the scope of the project, so I focused on three products that I buy regularly: Zopf (Swiss bread), pie dough, and coffee beans. I ignored currency fluctuations.

### ❓ What I Wanted to Find Out

I wanted to find out whether food prices in Switzerland have actually increased – in reality or only as a feeling.

---

## 🔍 Key Findings

- To my surprise, prices had mostly gone down, not up.
- Food prices appear to be quite volatile. This is something I would explore further if I had more time.

---

## 📊 Data Sources

- Personal digital receipts via [Migros App](https://customer.migros-service.ch/en/web/login)
- Swiss Federal Statistical Office (BFS):  
  [Consumer Price Index (CPI)](https://www.bfs.admin.ch/bfs/de/home/statistiken/preise/landesindex-konsumentenpreise.html)
- IMF commodity price database:  
  [legacydata.imf.org](https://legacydata.imf.org/?sk=471dddf8-d8a7-499a-81ba-5b332c01f8b9&sid=1547558078595)

### 🗃 Files and Coverage

- 3 CSV files from Migros (personal purchase history, 2.5 years)
- 1 CSV from BFS (Switzerland CPI)
- 1 CSV from the IMF (global coffee prices)

---

## 🧪 Data Analysis & Processing

I used two Jupyter notebooks for all data cleaning and exploration:

- `Migros_Projekt_BAFS.ipynb`
- `migros.ipynb`

This part of the project was especially fun – I used the notebooks not only to process the data but also when I later in the project needed more context. For example, I could check: when exactly did Migros rename the pie dough?

All downloads were manual – I didn’t need to scrape anything.

---

## 🛠 Tools, Skills, and New Things I Learned

This was the first time I…

- Collected and cleaned data
- Created and refined charts to explore early results
- Imported charts into Datawrapper, chose fonts and a color scheme
- Edited charts further in Adobe Illustrator – this was one of the more difficult parts, and it shows in the visuals
- Built a webpage using Soma’s scrollytelling template
- Created an AI-generated comic character that somewhat resembles me
- Wrote a README file
- Used GitHub to publish the project

---

## 🚧 What I Wanted to Do, But Didn’t Manage

I originally wanted the charts to animate as overlays above the scrollytelling background images.  
That didn’t work out. I eventually chose a simpler solution: embedding each chart as a static block in the scroll sequence.

---

## 📁 Project Files

- `/data/` – All CSV files used in the project
- `/notebooks/` – Jupyter notebooks for cleaning and analysis
- `/images/` – Exported charts and visuals (some edited in Illustrator)
- `/code/` – HTML & CSS files for the published webpage
- `/README.md` – This file

All notebooks include Markdown cells at the top to explain the structure, and inline comments for context.

---

## 🔗 Project Page

👉 You can view the published project here:  
**[https://schube13.github.io/Projekt-LEDE-Migros/](https://schube13.github.io/Projekt-LEDE-Migros/)**

---

## 🧹 .gitignore

Note: Any large data files (100MB+) were excluded via `.gitignore` as recommended.
