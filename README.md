# maker-lean-canvas

> The One-Page Business Plan for Makers

A streamlined, interactive business planning tool designed for makers, artists, and small-batch manufacturers.

---

## Overview

Most business plans are too long and never get used.

**Maker GPS** is a one-page "living" document that helps you navigate the transition from a great idea to a sustainable income — structured around the proven Lean Canvas framework, adapted for the maker context.

### What you can do

- Map your strategy across the **9 essential Lean Canvas blocks**
- Calculate product viability instantly using the **Cost × 3 Rule**
- Export your plan as a **clean, high-quality PDF** for records or mentor meetings

---

## The Cost × 3 Rule

One of the biggest reasons maker businesses fail is underpricing labor and overhead. The built-in calculator ensures your retail price covers all three cost layers:

| Cost Layer | What It Includes |
|------------|-----------------|
| **Materials** | Every screw, gram of filament, or sheet of wood |
| **Labor** | Your time is a real expense — pay yourself fairly |
| **Overhead & Fees** | Shipping, platform fees (Etsy/Shopify), tool maintenance |

```
(Materials + Labor + Fees) × 3 = Minimum Retail Price
```

---

## Tech Stack

A fully self-contained single file with zero backend dependencies — no build step, no npm, no install.

| Technology | Purpose |
|------------|---------|
| [Tailwind CSS](https://tailwindcss.com) | Responsive UI |
| [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) | Client-side PDF export |
| [Font Awesome](https://fontawesome.com) | Iconography |

---

## How to Use It

**1. Start with the Problem — not your product**
Identify the pain your customer feels before defining your solution.

**2. Define your Customer Segment**
Who is your Early Adopter? Be specific.
> *Example: "Homeowners in Toronto who love mid-century modern decor"*

**3. Test your Assumptions**
Apply the **"Talk to 5 Strangers"** rule from the Innovation Week session before committing to any block.

**4. Save and Iterate**
Your canvas is never finished. Update it as you learn more about your market.

---

## Deployment

This project is a single `index.html` file hosted on GitHub Pages.

1. Push `index.html` to the root of your `main` branch
2. Go to **Settings → Pages**
3. Under **Source**, select `Deploy from a branch` → `main` → `/ (root)`
4. Your canvas will be live at `https://yourusername.github.io/maker-lean-canvas`

> Changes go live within 1–2 minutes of pushing to `main`.

---

## Project Structure

```
/
└── index.html    # The entire application — fully self-contained
```

---

## License

For educational use. All linked external resources and libraries remain the property of their respective owners.
