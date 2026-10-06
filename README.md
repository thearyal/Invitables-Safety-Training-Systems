# Spot the Hazard — Invitable Promo Website

A responsive static marketing website for Invitable's industrial safety platform, designed to showcase the Spot the Hazard product and its immersive warehouse training experience.

This project includes:
- a premium landing page for the product
- a live interactive hazard-training demo page
- modern UI styling and responsive layout
- form interactions and smooth-scrolling navigation

## Links

- [Live 360° prototype (LIVE URL)](https://spot-the-hazard-game.netlify.app/)
- [GitHub repository](https://github.com/thearyal/spot-the-hazard.git)
- 

## Project Overview

The site is built around the concept of a photorealistic digital twin training platform for warehouse and distribution environments. The brand messaging focuses on reducing workplace incidents by providing interactive safety training scenarios that feel realistic and measurable.

The experience is designed for enterprise audiences, especially:
- warehouse operators
- distribution center managers
- safety leaders and EHS teams
- learning and development teams
- industrial organizations exploring digital safety training

## Product Concept

Spot the Hazard is positioned as an AI-powered, browser-based safety training platform that helps employees identify hazards in an immersive 360° environment. It combines:

- real-world digital twins of industrial sites
- hazard detection scenarios
- adaptive training experiences
- measurable performance feedback
- enterprise-grade deployment flexibility

The landing page highlights the value proposition of making safety training more realistic, scalable, and accessible without relying on expensive hardware or isolated VR rooms.

## Website Structure

The project is deliberately lightweight and static. It does not require a complex framework or build process.

### Main Landing Page
- `index.html` — the primary promotional website
- Contains sections such as:
  - navigation bar
  - hero section
  - product feature highlights
  - company value proposition
  - stats and proof points
  - interactive scenarios and demo CTA
  - contact section and enterprise inquiry form

### Interactive Demo Page
- `spot_the_hazard.html` — a browser-based training simulation
- Provides a game-like hazard identification experience inside a warehouse-style environment
- Includes:
  - a floating crosshair pointer
  - hazard detection mechanics
  - scoring and feedback
  - quiz modal interactions
  - visual HUD elements

### Stylesheet
- `styles.css` — main styling file for the landing page
- Handles:
  - layout and responsiveness
  - color palette and theming
  - card layouts, buttons, nav, sections, and forms
  - mobile navigation behavior

### Assets
- `assets/` — graphics and images used throughout the website
- Includes product imagery, scenario visuals, logos, and hero artwork

## Features Included

### Landing Page Experience
- fixed top navigation
- smooth anchor scrolling
- hero call-to-action buttons
- modern dark theme UI with orange accent color
- responsive multi-column layout
- feature and scenario cards
- stats and social proof elements
- contact form with simulated submission behavior

### Interactive Hazard Demo
- 360°-style warehouse simulation environment
- hazard spotting gameplay and visual scoring
- toast notifications for correct or incorrect detection
- evaluation prompts and quiz interactions
- immersive industrial safety training presentation

### User Experience Enhancements
- mobile hamburger menu
- hover states and transitions
- dynamic navbar state on scroll
- form submit feedback animation
- accessible semantic HTML structure

## Technology Stack

This project uses:
- HTML5 for structure
- CSS3 for styling and layout
- Vanilla JavaScript for interactivity
- Google Fonts (Inter) for typography

No package manager, framework, or backend is required for the base project.

## Project Structure

```text
Website_Source_Files/
├── assets/
│   ├── hero-warehouse.png
│   ├── warehouse-twin.png
│   ├── experience-scene.png
│   ├── logo.png
│   ├── scenario-forklift.png
│   ├── scenario-racking.png
│   ├── scenario-chemical.png
│   └── ...
├── index.html
├── spot_the_hazard.html
├── styles.css
└── README.md
```

## How to Run the Website

Because this is a static website, there are multiple easy ways to view it locally.

### Option 1: Open Directly in a Browser
1. Navigate to the project folder.
2. Open `index.html` directly in your browser.
3. The page should load and display correctly.

### Option 2: Use a Simple Local Web Server
This is recommended for a smoother experience, especially if you want to test navigation or local asset loading consistently.

Using Python:

```bash
cd "d:\Second Years ClassWorks\E Project\Anil Team_Inevitables_PhishHook_Assignment2\B2_PromoWebsite\Website_Source_Files"
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

If you prefer using Node.js:

```bash
npx serve .
```

## How to View the Demo

From the main page:
- click the "Play Live Demo" button, or
- click "Launch Live Demo" within the experience section

This opens the interactive hazard spotting experience in a new browser tab.

## Styling and Brand Notes

The visual theme uses:
- dark navy/black industrial background
- orange accent color for CTA emphasis
- glassmorphism-inspired panels and overlays
- clean typography and modern card layouts

This aligns with a tech-forward enterprise safety brand and gives the product a polished, professional feel.

## JavaScript Behavior

The landing page includes small interactive behaviors such as:
- smooth scrolling between sections
- active navigation highlighting while scrolling
- mobile menu toggling
- navbar background change on scroll
- simulated contact form submission success state

The demo page includes game logic for:
- hazard identification
- score tracking
- success/failure feedback
- in-demo quiz prompts

## Customization Ideas

You can adapt the project for other branding or product use cases by updating:

- text content in `index.html`
- color variables in `:root` inside `styles.css`
- imagery in the `assets/` folder
- product-specific messaging and statistics
- CTA buttons and contact information

## Accessibility and Design Considerations

This project is designed to be visually modern and easy to use, with a focus on:
- crisp contrast for readability
- responsive layouts for different screen sizes
- simple interaction patterns
- straightforward browser-based deployment

## Notes for Future Expansion

This project is easily extendable for a more advanced marketing or product site. Potential upgrades could include:
- a real backend-powered contact form
- additional case study pages
- product documentation or pricing pages
- multi-page website architecture
- animated charts or product walkthroughs
- CMS or headless content integration

## License

This project is a front-end design and demo website created for educational and presentation purposes. If you plan to reuse it commercially or in a production environment, confirm branding, image licensing, and content ownership before publishing.

## Summary

The Spot the Hazard promo website is a polished single-page marketing experience for an industrial safety training product. It demonstrates how modern front-end design can communicate a complex product value proposition through visual storytelling, enterprise messaging, and interactive user engagement.

It is ideal for:
- concept presentations
- internship or coursework projects
- product showcases
- UI/UX mockups for safety technology products

## Maintainer / Credits

This project is built as a front-end promo website concept for Invitable's Spot the Hazard offering.

If you are using it within a team or academic setting, consider updating the branding, copy, and imagery to reflect your final project requirements and ownership.
