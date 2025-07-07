# Omitted Variable Bias & Propensity Score Matching (PSM) Demo

This repository contains a simple, interactive web demo that illustrates **omitted variable bias** in regression analysis using **Propensity Score Matching (PSM)**. It allows users to explore how excluding important covariates can bias treatment effect estimates.

## 📁 Contents

- `DCL Final.html` – Main interactive HTML page containing the demo logic with checkboxes and Plotly visualizations.
- `DCL.qmd` – Source file likely written in Quarto Markdown used to generate the HTML version (not viewable directly here).
- `styles.css` – External CSS styles for UI enhancements.

## 🚀 Features

- Interactive variable selection for matching covariates.
- Dynamic visualization of regression estimates:
  - Biased model (omitting a confounding variable).
  - True model (including confounding variable).
- Educational use case demonstrating how omitting variables can distort causal inference.

## 📦 Usage

To run the demo locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/psm-omitted-variable-demo.git
   cd psm-omitted-variable-demo
   ```
2. Open the `DCL Final.html` file in your browser.

> **Note:** Ensure you have an internet connection as the demo uses the Plotly CDN.

## 🧠 Educational Context

This tool is great for:
- Econometrics or causal inference classes.
- Demonstrating the intuition behind omitted variable bias.
- Explaining the benefits of PSM in observational data analysis.

## 📄 License

MIT License. Feel free to use and modify.
