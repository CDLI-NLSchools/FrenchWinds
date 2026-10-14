# FrenchWinds

Interactive HTML quiz for learning about planetary winds and atmospheric circulation in a French-language science context.

## Overview

This project is a single-page web application designed to help students practice and demonstrate understanding of:

- Solar angle and unequal heating
- Global convection cells
- Pressure belts and calm zones
- Coriolis effect and wind naming
- Prevailing westerlies and polar easterlies
- Jet streams and weather/aviation impacts

The content is written in French and includes diagrams, multiple-choice questions, immediate feedback, and a final mastery screen.

## Files

- `index.html` — main application
- `README.md` — project overview and usage instructions

## Features

- French-language UI and question content
- Interactive SVG diagrams
- Multiple-choice quiz flow
- Immediate correct/incorrect feedback
- Score tracking with a target of 10 correct answers
- Proof-copy function intended for Brightspace submission
- KaTeX rendering for scientific notation and equations

## How to run

Because this project is a static HTML page, you can open it directly in a browser:

1. Download or clone the repository.
2. Open `index.html` in a browser.

Optional local web server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/
```

## Notes

This repository is intentionally lightweight and does not require a build step or package installation. It is designed for browser-based classroom or assessment use.

## License

This project does not currently include a license file. If you plan to share or distribute it publicly, you may want to add an appropriate open-source license.
