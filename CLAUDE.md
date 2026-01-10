# NEMD Summer School 2026

Website for the NEMD for Fluid Dynamics and Interfacial Phenomena Summer School.

## Event Details

- **Dates**: 6-7 July 2026
- **Location**: King's Buildings Campus, University of Edinburgh
- **Fee**: £100 (includes free access to NEMD Conference 8-10 July)
- **Sponsors**: Tokyo Electron, CCP5

## Tech Stack

- **Framework**: Quarto
- **Styling**: Custom CSS with hero image
- **Hosting**: GitHub Pages (via GitHub Actions)

## Local Development

```bash
# Preview site
quarto preview

# Build site
quarto render
```

## Project Structure

```
_quarto.yml       # Site configuration
index.qmd         # Homepage with hero image
schedule.qmd      # Program/timetable
speakers.qmd      # Speaker profiles
registration.qmd  # Registration info
styles.css        # Custom styles (hero, cards)
images/
  hero.png        # Hero background image
```

## Deployment

GitHub Actions workflow automatically builds and deploys to GitHub Pages.

## Speakers

9 confirmed speakers - bios sourced from institutional websites. Photos to be added when received from speakers.

## Registration

Currently placeholder - awaiting university payment system details.
