# Sw203project

# Smart Health and Fitness Tracker

CSAI 203 - Introduction to Software Engineering, Fall 2026
Zewail City of Science, Technology and Innovation

## Team members

| Name | ID |
Youssef abdelaal | 202400563
Eyad Eslam Ibrahim | 202401218
Eyad Al-Saeed Ahmed  | 202508209


Team number: [#]
Team contact:  s-youssef.abdelaal@zewailcity.edu.eg

## Description

A simple, offline web application for tracking health and fitness data. A user can log workouts, body measurements, meals, water, sleep, and mood; use calculators (BMI, BMR, TDEE, heart rate zones, one-rep max); set goals and reminders; view progress summaries; and browse, search, share, and import workouts. All data is stored locally, and users can choose their preferred unit system.

Results are estimates for general information and are not medical advice.

## Setup and run

```bash
# 1. Clone the repository
git clone https://github.com/TR4INED/Sw203project.git
cd Sw203project

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r deployment/requirements.txt

# 4. Run the application  [update the path once the app exists]
python src/app.py
```

Then open http://127.0.0.1:5000 in a web browser.

## Repository structure

| Folder | Contents |
|---|---|
| `/docs` | Submitted documents (SRS, design, reports, testing evidence) |
| `/src` | Source code |
| `/tests` | Test cases (unit tests, manual test reports) |
| `/deployment` | Deployment instructions, configuration files, environment setup scripts |

## Documents

- [Software Requirements Specification (SRS)](docs/SRS.pdf) `[add after export]`
- [Design document](docs/) `[add later]`
- [Testing evidence](docs/) `[add later]`
