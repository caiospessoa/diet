```
███╗   ███╗███████╗ █████╗ ██╗     
████╗ ████║██╔════╝██╔══██╗██║     
██╔████╔██║█████╗  ███████║██║     
██║╚██╔╝██║██╔══╝  ██╔══██║██║     
██║ ╚═╝ ██║███████╗██║  ██║███████╗
╚═╝     ╚═╝╚══════╝╚═╝  ╚═╝╚══════╝
         P L A N  A P P             
```

![HTML](https://img.shields.io/badge/HTML-pure-orange?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-dark_theme-1a1a2e?style=flat-square&logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/JS-vanilla-yellow?style=flat-square&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-installable-6ee7b7?style=flat-square)
![No Dependencies](https://img.shields.io/badge/dependencies-zero-brightgreen?style=flat-square)
![Carb Cycling](https://img.shields.io/badge/strategy-carb_cycling-fb923c?style=flat-square)
![Location](https://img.shields.io/badge/calibrated_for-🇳🇱_Netherlands-blue?style=flat-square)

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

## Stats

```
📊 Macros tracked    →  kcal · protein · carbs · fat
🍽️  Meal slots       →  4 per day (breakfast, lunch, snack, dinner)
🔀  Options per meal →  up to 4
📅  Training days    →  5x/week PPL + Upper/Lower
⚡  Carb high days   →  Wednesday (Legs) + Saturday (Lower)
🏋️  Daily burn       →  ~2700 kcal (88kg · 192cm · 1h lift + 50min cardio)
```

---

> 💡 **Pro tip:** Add to iPhone home screen via Safari → Share → Add to Home Screen for full app experience with dark status bar.

---

*Built for personal use. Nutritional values are estimates based on product labels and food composition tables. Always consult a registered dietitian for medical nutrition advice.*
