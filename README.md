StepQuest — Multiplayer Step Tracker with Loot Crates
Problem

Step-count and fitness goals are easy to abandon because most step-tracking apps offer no social accountability or reward beyond a number going up. Engagement drops off fast without a game-like incentive.

Solution

A multiplayer web app where users log steps, compete on a shared leaderboard, and earn a randomized loot crate (Common → Mythic rarity) every 1000 steps — similar to gacha-game reward systems. Step entry is manual/simulated for this project rather than pulled from real phone sensors.

Tech Stack
Python
Flask (backend/web routes)
SQLite (database)
Setup
bash
git clone <this-repo-url>
cd stepquest-tracker
python -m venv .venv
source .venv/bin/activate   # or .venv\Scripts\activate on Windows
pip install -r requirements.txt
python app.py
Current Plan
Sprint 1 (MVP): manual step logging, 1000-step crate trigger, 6-tier rarity roll, per-user crate history, basic multi-user leaderboard
Sprint 2: refactor crate logic with design patterns, pity system (guaranteed Rare+ every 10 crates), streaks/achievements, friend/team groups

Full plan and progress tracked on my Canvas Individual Project page.

Course Context

ASE420 Software Design — Individual Project, Northern Kentucky University.
