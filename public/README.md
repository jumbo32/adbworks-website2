# ADBWORKS LLC - Corporate Hub & Mobile App Landing Pages

This repository contains the source code for the official **ADBWORKS LLC** corporate website and individual landing pages for our iOS applications. The site is structured as a lightweight, lightning-fast static website optimized for deployment on **Cloudflare Pages**.

## 📂 Directory Structure

The project utilizes a flat directory architecture combined with **domain-absolute routing (`/`)** to completely eliminate complex relative pathing issues (e.g., `../../assets`). 

Everything deployed to the web must sit inside the `public/` folder.

```text
adbworks-website2/
└── public/                 # Deployment directory for Cloudflare Pages
    ├── index.html          # Main Company Hub (adbworks.com)
    │
    ├── global/             # Shared assets used across multiple applications
    │   └── images/         # App icons, screenshots, corporate logos
    │
    ├── legal/              # Compliance documentation
    │   └── privacy.html    # App Store compliant Privacy Policy
    │
    ├── support/            # Customer Service & Help Centers
    │   ├── index.html      # Simple Corporate Contact form link
    │   └── app-support.html# Granular App FAQ, Data Deletion & Restore procedures
    │
    ├── app-one/            # App One Landing Page ([adbworks.com/app-one/](https://adbworks.com/app-one/))
    │   └── index.html      
    │
    └── app-two/            # App Two Landing Page ([adbworks.com/app-two/](https://adbworks.com/app-two/))
        └── index.html

        end