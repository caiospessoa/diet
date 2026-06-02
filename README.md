# 🥗 Meal Plan App — Plano Alimentar

> Personal nutrition reference app built for daily use — dark theme, mobile-first, interactive macros.

## Overview

A single-file web app for tracking a carb cycling meal plan, calibrated to real Dutch/European nutritional labels. Built as a personal tool for body recomposition at high training volume (PPL + Upper/Lower split, 5x/week + daily cardio).

## Features

- **Two modes** — Normal Days (~1951 kcal) and High Carb Days (~1824 kcal)
- **Multiple meal options** per meal slot (breakfast has 3 options, dinner has 3 variants)
- **Live macro totals** — selecting a different option recalculates the daily total in real time
- **Accurate macros** — calibrated against real Dutch product labels (Skyr Arla, ON Whey EU label, Dutch chicken, etc.) and TACO (Brazilian carioca beans)
- **Dark theme** — readable in any lighting, preserves OLED battery
- **Mobile-first** — designed for quick daily reference, installable as PWA

## Carb Cycling Schedule

| Day | Type | Training |
|-----|------|----------|
| Monday | Normal | Push |
| Tuesday | Normal | Pull |
| Wednesday | **High Carb** | Legs 🦵 |
| Thursday | Normal | Rest |
| Friday | Normal | Upper |
| Saturday | **High Carb** | Lower 🦵 |
| Sunday | Normal | Rest |

## Nutritional Sources

| Food | Source |
|------|--------|
| Skyr 0% | Dutch label (Arla) |
| Whey ON Gold Standard | EU label |
| Chicken breast cooked | Dutch label |
| Beef | Dutch label |
| Oat bran | Dutch label |
| Banana | Dutch label (Chiquita) |
| Potato | Dutch label |
| Rice (cooked) | Dutch label (calculated) |
| Tortilla | Dutch label (Rap10) |
| Whole grain bread | Dutch label |
| Carioca beans | TACO (Brazil) |
| Mozzarella | TACO (Brazil) |

## Usage

Open `index.html` in any browser. On mobile (Safari/Chrome), add to home screen for app-like experience:

**iOS Safari:** Share → Add to Home Screen  
**Android Chrome:** Menu → Add to Home Screen

## Tech Stack

Pure HTML/CSS/JS — no dependencies, no build step, no backend.

---

*Built for personal use. Nutritional values are estimates based on product labels and food composition tables. Always consult a registered dietitian for medical nutrition advice.*
