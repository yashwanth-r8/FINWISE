# Finwise Lab 💰

**Make clearer decisions with your money.**

Finwise Lab is a free, interactive financial literacy website designed to help students, young adults, and first-time earners understand everyday money decisions. It brings simple financial lessons and practical calculators together in one place.

> Learn about money. Plan your spending. Make informed decisions.

## 🌐 Live Website

After enabling GitHub Pages, add your published website URL here:

`https://YOUR-USERNAME.github.io/finwise-lab/`

## ✨ Features

### Interactive financial tools
- **Asset or Liability Checker** – Explore whether an item can generate income, appreciate in value, or create ongoing costs.
- **Inflation Simulator** – Estimate how inflation can affect the purchasing power of money over time.
- **SIP Calculator** – Estimate the potential future value of regular monthly investments.
- **EMI Calculator** – Estimate monthly loan payments and total interest.
- **Discount & GST Calculator** – Calculate discounts, GST, and the final amount payable.
- **Split Bill Calculator** – Divide a bill between people, including an optional tip or service charge.
- **Goal Saver** – Estimate how much to save each month to reach a target.

### Budget Lab
- Enter monthly income and spending.
- Compare needs, wants, and savings with the 50/30/20 budgeting guideline.
- View an estimated six-month emergency-fund target.

### Learn
- Explore beginner-friendly topics such as budgeting, saving, inflation, debt, insurance, investing basics, and scam awareness.
- View upcoming course previews.

### Financial Challenges Survey
- Complete an anonymous financial decision-making survey.
- Explore the project's displayed survey findings and visual summaries.
- The displayed results are based on a small sample of eight respondents and should be treated as indicative, not statistically conclusive.

### Responsive experience
- Mobile-friendly navigation and layouts.
- Light and dark theme support based on the device preference.
- Interactive controls, visual feedback, and accessible labels.

## 🛠️ Built With

- **HTML5** – Website structure
- **CSS3** – Styling, responsive layouts, themes, and animations
- **Vanilla JavaScript** – Navigation, calculators, simulations, and interactions
- **Google Fonts** – Bricolage Grotesque, DM Sans, and Share Tech Mono

No frontend framework, package manager, or build step is required for the core website.

## 📁 Project Structure

```text
finwise-lab/
├── index.html
└── README.md
```

The current version is a single-page website, with its HTML, CSS, and JavaScript contained in `index.html`.

## 🚀 Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/finwise-lab.git
   ```

2. Open the project folder:

   ```bash
   cd finwise-lab
   ```

3. Start a local server with Python:

   ```bash
   python -m http.server 5500
   ```

4. Open this address in your browser:

   ```text
   http://localhost:5500
   ```

You can also open `index.html` directly in a browser for basic testing.

## 🌍 Deploy with GitHub Pages

1. Push `index.html` and `README.md` to the root of your GitHub repository.
2. Open the repository on GitHub.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and the `/ (root)` folder.
6. Click **Save**.
7. Wait for GitHub Pages to publish the website. Your URL will appear in the Pages settings.

Whenever you push changes to the selected branch, GitHub Pages will publish the updated site.

## ⚠️ Important Notes

- The calculators and main interactive website features run in the browser.
- The optional **Finwise AI** chat currently calls `window.claude?.use('sample')`. This is a host-specific integration, not a standard browser API. It will not work on a regular GitHub Pages deployment unless it is replaced with a properly configured AI service and a secure backend. Do not put private API keys in frontend JavaScript.
- Survey response saving currently calls `window.claude?.use('db')`, which is also host-specific. On a normal GitHub Pages deployment without that integration, the site provides a copy-and-share fallback rather than storing responses in a hosted database.
- The survey charts display the project's existing sample results; they are not automatically updated by new survey submissions.
- Financial calculations are educational estimates. SIP returns are not guaranteed, and actual loan, tax, GST, and investment terms may vary.

## 🎯 Project Objective

Finwise Lab aims to make basic financial knowledge easier to understand and apply. Instead of presenting only theory, it gives users simple tools to experiment with budgets, savings, inflation, loans, and everyday spending decisions.

## 👤 Creator

**Rithick** — Creator of **Hey Rithick** and builder of Finwise Lab.

- Instagram: [@hey.rithick](https://instagram.com/hey.rithick)
- YouTube: [Hey Rithick](https://youtube.com/@heyrithick-r)

## 📌 Disclaimer

Finwise Lab is an educational project. It does not provide personalised financial, investment, tax, or legal advice. Check information with qualified professionals before making important financial decisions.

---

**Built to make money easier to understand.**
