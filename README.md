# Trust Your Sight — Demo App

**Tagline:** Trust Your Sight. Trust Your Future.

This repository contains a working **demo** of the Trust Your Sight retinal scanner flow.  
⚠️ **Disclaimer:** This demo is *not* a medical device and does not provide real diagnoses.  
It is intended to show the full user experience before live medical integrations.

---

## How It Works

1. **index.html** — scrolling onboarding
   - Branding
   - Age verification (must be 18+)
   - Plan selection (Individual, Family, Senior)
   - Disclaimers (checkboxes required)
   - Scan instructions

2. **Vision.html** — guided retinal scan
   - Uses device camera (front or rear)
   - 9-position guided scan (look straight, up, down, left, right, diagonals)
   - Controls: switch camera, mute/unmute, pause/resume, exit
   - Demo results: randomized set of 6+ outcomes with timestamp
   - Actions: Back, Start Again, Share, Print/Save PDF

---

## Demo Features

- Dark theme, professional flow  
- Full onboarding before scan  
- Audio + on-screen prompts for each position  
- Results vary between green (healthy), yellow (moderate), red (warning)  
- Always includes at least 2 positive (green) lines  
- Timestamp + sharing options  

---

## Future (Live Version)

- Replace demo results with **Google Vision API** (comparative AI)  
- Integrate **medical-grade AI partners** (FDA-cleared) for real diagnosis  
- Add **payment processing** (Stripe or Firebase)  
- Enable **Firestore** for user accounts, scan history, and testimonials  

---

## Usage

Open `index.html` in a browser (Chrome recommended).  
Follow the steps → the scanner will launch → demo results will display.
