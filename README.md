# StatIQ — Statistical Data Analysis Platform

> 🚀 **Live Demo:** [Your GitHub Pages link will appear here after deployment]

A powerful, browser-based statistical data analysis platform built with pure HTML, CSS, and JavaScript. No backend required — everything runs in the browser.

## ✨ Features

- **19+ Statistical Metrics** — Mean, Median, Mode, Variance, Std Dev, Skewness, Kurtosis, IQR, SEM, 95% CI, and more
- **Interactive Charts** — Histogram with normal curve, Line chart, Box plot, Doughnut (quartiles), Scatter + Regression line
- **Outlier Detection** — Automatic IQR-based outlier flagging with visual badges
- **Linear Regression** — Trend line, R, R², slope, intercept analysis
- **CSV / JSON Upload** — Drag and drop or click to upload your own data
- **Export** — Download enriched CSV with Z-scores, percentiles, and deviations
- **4 Sample Presets** — Exam scores, Sales data, Temperature, Normal distribution

## 🚀 Deployment (GitHub Pages)

1. Fork or upload this repo to GitHub
2. Go to **Settings → Pages**
3. Set Source to **Deploy from branch → main → / (root)**
4. Click **Save** — your site will be live at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

## 🛠 Tech Stack

- **Chart.js 4.4** — Interactive charts
- **PapaParse 5.4** — CSV parsing
- **Google Fonts** — Inter + JetBrains Mono
- **Vanilla JS** — No frameworks, no build step

## 📊 How to Use

1. Click **"Load Sample Data"** for an instant demo
2. Click **"Enter Data Manually"** to type or paste your numbers
3. Upload any `.csv` or `.json` file containing numeric data
4. Explore charts, switch between Histogram / Line / Box Plot views
5. Copy the stats summary or export enriched CSV

## 📁 Project Structure

```
index.html    ← Entire app (self-contained, CSS + JS inlined)
README.md     ← This file
.nojekyll     ← Disables Jekyll processing on GitHub Pages
```

## License

MIT — free to use, share, and modify.
