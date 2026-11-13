# RD Estate

Premium residential plot developments in Pune, designed to showcase trusted land investment opportunities with a modern, conversion-focused web experience.

<p align="center">
  <img src="https://img.shields.io/badge/Type-Static%20Website-4CAF50?style=for-the-badge" alt="Static Website" />
  <img src="https://img.shields.io/badge/Stack-HTML%20%2B%20CSS%20%2B%20JS-263238?style=for-the-badge" alt="HTML CSS JS" />
  <img src="https://img.shields.io/badge/Focus-Real%20Estate-8C6C3F?style=for-the-badge" alt="Real Estate" />
</p>

## Overview

RD Estate is a premium property marketing website for a Pune-based real-estate business focused on residential plots, plotted developments, and long-term land investment opportunities. The project presents a curated portfolio of high-potential locations with the goal of helping buyers evaluate, compare, and enquire about available properties.

The site includes a strong property presentation layer with:

- premium landing-page design
- multiple project-specific detail pages
- property pricing and plot-size highlights
- searchable, filterable plot listings and side-by-side comparison
- project locality links, brochures where available, and site-visit inquiries
- buyer due-diligence guidance and a privacy notice

## Customer Features

- Filter the featured projects by name, locality, published rate, and listed plot size; sort by rate or plot size.
- Select up to three projects to compare their published location, sizes, rates, and features.
- Use locality-level map searches. These do not identify exact plot boundaries; request a confirmed site pin from the business.
- Choose a project and preferred site-visit date in the inquiry form. It opens a prefilled WhatsApp draft; the visitor must review and send it.
- Read the [Privacy Notice](privacy-policy.html) before sharing inquiry details.
- Request current inventory, dated written pricing, and plot-specific legal/approval documents directly. The site does not validate or guarantee those documents.

The website is static: inquiries are not saved to a website backend, availability is not live, and prices/fees must be confirmed. Only the Gurudatta Park brochure is currently linked from the listings. Project-specific legal records, exact directions, and independently verifiable customer references need to be supplied and maintained by the business.

## Featured Projects

The website highlights multiple residential and plotted development projects across Pune, including:

- Vasant Park
- Mayuresh Park
- Gurudatta Park
- Narayan Park
- Balaji Vishwa
- Additional project listings in emerging Pune locations

## Why This Project Matters

This project is crafted to support real-estate sales and engagement by emphasizing:

- prime Pune plot locations
- ready-to-build infrastructure
- legal and transparent property positioning
- premium buyer trust and credibility
- clear investment-oriented communication

## Key Highlights

- Fully responsive real-estate landing page
- Modern UI with premium property branding
- Detailed project pages with amenities and plot specifications
- Search, filtering, comparison, and a WhatsApp-based inquiry flow
- Responsive buyer checklist and privacy disclosure
- Clean static architecture for easy deployment and maintenance
- Optimized for lead generation and brochure-style marketing

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Font Awesome Icons
- Google Fonts
- Static site hosting

## Project Structure

```text
RD-Estate/
├── index.html                 # Main landing page
├── balaji.html                # Balaji Vishwa project page
├── gurudatta.html             # Gurudatta Park project page
├── Narayan.html               # Narayan Park project page
├── ramdara.html               # Mayuresh Park / Ramdara project page
├── vasant-a.html              # Vasant Park project page
├── vasant.html                # Vasant Park project page
├── vasant2.html               # Secondary Vasant development page
├── privacy-policy.html
├── assets/
│   ├── images/                # Project photos, logos, and graphics
│   └── videos/                # Project videos
├── documents/
│   └── Gurudatta-Park-Broucher.pdf
├── README.md
├── .gitattributes
└── .vscode/
```

HTML pages remain in the repository root to keep their existing page URLs working. Media and the brochure are stored in the folders above; asset URLs now use those paths.
Page-specific CSS and JavaScript remain inline in their HTML files; extracting and consolidating those would be a separate refactor.

## Getting Started

This is a static website, so there are no package installs or build steps required.

### Open directly

Open `index.html` in a browser.

### Run a local server

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deployment

The website is compatible with:

- GitHub Pages
- Netlify
- Vercel
- Any standard static hosting provider

## Local Development Notes

- All pages are plain HTML/CSS/JS and easy to customize
- Media assets are stored locally or linked from hosted sources
- Content updates, property pricing, and project details can be adjusted directly in the HTML files

## Brand Positioning

The visual language is designed to reflect:

- trust and reliability
- premium property value
- investment opportunity
- family-focused residential planning

## Contact & Inquiry

The website includes lead-generation actions for:

- site visits
- consultation requests
- brochure downloads
- direct property inquiries

## License

This project currently does not include a formal public software license. All branding, copy, and property-related assets are intended for the project owner’s use unless otherwise specified.

## Summary

RD Estate is a polished, lead-focused property website that presents real-estate inventory in a premium, trustworthy, and conversion-ready format for the Pune residential market.
