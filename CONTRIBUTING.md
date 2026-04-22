# Contributing to Nigeria Solar Load Calculator

Thank you for wanting to contribute! This tool exists to help Nigerians make better solar decisions — every improvement matters.

---

## Ways to Contribute

### 1. Report a Bug
If something calculates incorrectly or looks broken:
- Go to [Issues](https://github.com/YOUR-USERNAME/nigeria-solar-calculator/issues)
- Click **New Issue** → select **Bug Report**
- Include: what you expected, what happened, and your browser/device

### 2. Suggest a Feature
Have an idea that would help users?
- Go to [Issues](https://github.com/YOUR-USERNAME/nigeria-solar-calculator/issues)
- Click **New Issue** → select **Feature Request**
- Describe the feature and why it would be useful

### 3. Update Prices
Market prices change frequently with the NGN/USD rate. If you notice prices are out of date:
- Open `solar_calculator.html` and search for `INV_PRICES`, `BAT_PRICE_PER_KWH` or `PANEL_PRICES`
- Update the values with current market data
- Include a source or date reference in your Pull Request

### 4. Submit Code
1. **Fork** this repository (top right button on GitHub)
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/nigeria-solar-calculator.git
   ```
3. **Create a branch** for your change:
   ```bash
   git checkout -b fix/battery-calculation
   ```
4. **Make your changes** to `solar_calculator.html`
5. **Test thoroughly** — open in browser, enter appliances, click Calculate, verify results make sense
6. **Commit** your changes:
   ```bash
   git add solar_calculator.html
   git commit -m "Fix: battery sizing now correctly uses night load"
   ```
7. **Push** to your fork:
   ```bash
   git push origin fix/battery-calculation
   ```
8. Open a **Pull Request** on GitHub with a clear description

---

## Code Style Guidelines

- Keep everything in the single `solar_calculator.html` file — no external JS or CSS files
- Add comments when changing calculations so others understand the logic
- Test on both desktop and mobile before submitting
- Keep the tool working offline (no new CDN dependencies without discussion)

---

## Good First Issues

Look for issues labelled `good first issue` — these are well-scoped tasks suitable for first-time contributors:

- Adding new appliances to the default list
- Updating market reference prices
- Fixing mobile layout issues
- Improving the disclaimer text
- Adding tooltips to explain technical terms

---

## Questions?

Open a [Discussion](https://github.com/YOUR-USERNAME/nigeria-solar-calculator/discussions) or raise an Issue — happy to help.
