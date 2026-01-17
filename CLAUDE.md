# NEMD Summer School 2026

Website for the NEMD for Fluids and Interfaces Summer School.

## Event Details

- **Dates**: 6-7 July 2026
- **Location**: King's Buildings Campus, University of Edinburgh
- **Fee**: £100 (includes free access to NEMD Conference 8-10 July, lunches all 5 days)
- **Capacity**: 40 participants
- **Sponsors**: Tokyo Electron, CCP5, EPCC
- **Custom domain**: nemd-school.org

## Application Process

Applications via Microsoft Form (linked from website). Rolling review - successful applicants invited to pay. Applications close 31 March 2026.

- **Form**: https://forms.cloud.microsoft/e/8USEaip43H
- **Contact**: nemd2026@ed.ac.uk

## Tech Stack

- **Framework**: Quarto
- **Styling**: Custom CSS with hero image
- **Hosting**: GitHub Pages (via GitHub Actions)
- **Domain**: nemd-school.org (Porkbun, DNS → GitHub Pages)

## Local Development

```bash
# Preview site
quarto preview

# Build site
quarto render
```

## Project Structure

```
_quarto.yml       # Site configuration, navbar
index.qmd         # Homepage with hero image
schedule.qmd      # Program/timetable (Day 1 & 2)
speakers.qmd      # 9 speaker profiles with countries
registration.qmd  # Application info, fees, key dates
styles.css        # Custom styles (hero, cards, navbar)
CNAME             # Custom domain config
images/
  hero.png        # Hero background image
  tel-logo.png    # Tokyo Electron sponsor logo
  ccp5-logo.png   # CCP5 sponsor logo
  epcc-logo.png   # EPCC sponsor logo
  favicon.png     # Browser tab icon
```

## Key Features

- Application-based registration (not direct payment)
- Hands-on sessions using LAMMPS on ARCHER2 (EPCC support)
- Free conference attendance included
- Rolling application review

## Speakers

9 confirmed speakers from Denmark, France, Australia, UK, Japan, Italy. Bios sourced from institutional websites.

## Deployment

GitHub Actions workflow automatically builds and deploys to GitHub Pages. Custom domain configured via CNAME file and Porkbun DNS.
