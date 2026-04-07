# drsnehaldhumal.com

Official website source for **Dr. Snehal S. Dhumal** and **Sahyadri Holistic Clinic**, a homeopathic clinic based in **Ichalkaranji, Maharashtra, India**.

This repository contains a lightweight static website designed to present the clinic clearly to patients, improve local search visibility, and make it easy for visitors to call, message, find the clinic on Google Maps, and learn about treatments offered.

## Website Purpose

The website is built to support:

- Patients searching for a **homeopathic doctor in Ichalkaranji**
- Local discovery for treatments related to **thyroid**, **skin conditions**, **kidney stones**, **piles and fissure**, **PCOS**, **infertility support**, and other chronic concerns
- Direct appointment actions through **phone**, **WhatsApp**, **email**, and **callback request**
- Trust-building through clinic details, doctor credentials, patient reviews, frequently asked questions, and structured contact information

## About The Clinic

**Sahyadri Holistic Clinic** is led by **Dr. Snehal S. Dhumal**, a consulting physician with qualifications including:

- `BHMS`
- `MD Medicine (Hom)`
- `EMS`
- `CGO`
- `CCH`
- `CSD`

The clinic offers **OPD and IPD care** and focuses on personalized homeopathic treatment with a holistic approach to healing and wellness.

## Tech Stack

This is a simple static site with no framework dependency.

- `index.html`: main website page
- `dr-snehal.webp`: doctor image used on the site
- `favicon.png`: browser and search-result favicon
- `apple-touch-icon.png`: icon for Apple devices
- `sahyadri-logo.png`: clinic brand logo used in the footer
- `robots.txt`: crawler rules
- `sitemap.xml`: sitemap for search engines
- `CNAME`: custom domain configuration for GitHub Pages

## SEO Setup

The site includes:

- page title and meta description
- canonical URL
- Open Graph and Twitter metadata
- JSON-LD structured data for the clinic and doctor
- `robots.txt`
- `sitemap.xml`
- favicon and touch icon assets
- local-business-focused content and treatment keywords relevant to Ichalkaranji and the Kolhapur region

Primary domain:

- `https://www.drsnehaldhumal.com/`

## Contact Information Used On The Website

- Phone: `+91 8208103369`
- Email: `drsnehaldhumal.md@gmail.com`
- Instagram: `https://www.instagram.com/dr.snehaldhumal`
- Google Maps: `https://maps.app.goo.gl/JR4nL4tVW9hygZWN9`

## Local Preview

Because this is a static site, you can preview it locally in any browser.

Open directly:

```bash
open index.html
```

Or run a local server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deployment

This repository is intended to be deployed through **GitHub Pages** with the custom domain configured via `CNAME`.

After pushing changes:

1. Wait for GitHub Pages to publish
2. Verify the live homepage
3. Verify:
   - `/robots.txt`
   - `/sitemap.xml`
   - `/favicon.png`
4. If SEO metadata changed, re-request indexing in Google Search Console

## Editing Guidelines

When updating this website, keep these rules in mind:

- Preserve the clinic’s calm, trustworthy, classic visual tone
- Do not add clutter or overuse logos/icons
- Keep layout responsive across common mobile and desktop screen sizes
- Maintain consistent contact information everywhere
- If changing metadata, keep all SEO fields aligned with the live clinic details
- If changing branding assets, verify favicon, logo, and footer/header usage together

## Repository Goal

The goal of this repository is to maintain a fast, clear, mobile-friendly, and search-friendly website for **Dr. Snehal Dhumal** and **Sahyadri Holistic Clinic**, helping patients quickly understand the clinic, trust the doctor, and contact the practice without friction.
