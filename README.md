# APEXIFFY — Premium Fitness Platform

⚡ Premium 3D fitness web platform — custom training splits, BMI & health scoring, calorie/macro engine, monthly progress gallery, weekly reports with Instagram Story sharing, live notifications, 3-day free trial, and an owner database console. Vanilla JS + Three.js, fully responsive with a native app-style mobile UI.

## Structure

| Folder | Deploys to | What it is |
|---|---|---|
| `apexiffy-main/` | https://apexiffy.vercel.app | The platform users see |
| `apexiffy-database/` | https://apexiffydatabase.vercel.app | Owner console (password-protected) |

Both connect to one Supabase database. Signups on the main site appear in the console within 1 second.

## Setup

See **SETUP-GUIDE.md** — the only manual steps are creating a free Supabase project and pasting two values:

- `apexiffy-main/index.html` → **lines 1174–1175**
- `apexiffy-database/index.html` → **lines 170–171**

## Features

Landing: Three.js 3D hero, bento features, transformations gallery, testimonials, FAQ, 3-tier pricing, newsletter.
App: onboarding with BMI + health score, custom split builder with daily reminders, calorie/macro calculator, meal log, water tracker, rest timer, PRs, leaderboard, achievements, before/after photo slider, weekly/monthly reports, IG Story share, notifications, admin panel.
Console: live 1s sync, trial countdowns, red highlighting for expired non-subscribers, gym-wise grouping (Home Gym separated), health-score pills, search/filters, CSV export.

## Demo access

- Any username + phone + password → 3-day trial account
- Username `admin` → in-app admin panel
- Database console password: `apexiffythebrandofitness`

Built by Sharjeel Ahmed.
