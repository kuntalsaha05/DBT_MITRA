# DBT Mitra

### Enhancing Student Awareness on Aadhaar & DBT (SIH25059)

A Smart India Hackathon solution to bridge the awareness gap between:

-   **Aadhaar-Linked Bank Account**
-   **DBT-Enabled Aadhaar-Seeded Bank Account**

Government scholarships are transferred **only through DBT-enabled
Aadhaar-seeded accounts via NPCI mapper**.

------------------------------------------------------------------------

## Problem Statement

Many students applying for **Pre-Matric & Post-Matric Scholarships (SC
students)** face delays in receiving funds because they do not
understand the difference between:

-   Aadhaar-linked account (used for identity verification)\
-   DBT-enabled Aadhaar-seeded account (used for receiving government
    benefits)

This project solves that awareness gap using an interactive and gamified
platform.

------------------------------------------------------------------------

## Objectives

-   Increase awareness about DBT and Aadhaar seeding\
-   Reduce scholarship disbursement delays\
-   Promote digital financial literacy\
-   Provide clear step-by-step guidance

------------------------------------------------------------------------

## Project Structure

    dbt-mitra/
    │
    ├── index.html
    ├── response-yes.html
    ├── response-no.html
    ├── response-maybe.html
    ├── response-idk.html
    └── README.md

------------------------------------------------------------------------

## Key Features

### 1. Awareness Slideshow

-   Explains Aadhaar-Linked vs DBT-Enabled
-   NPCI Mapper concept
-   Why only ONE account can be DBT-enabled at a time

### 2. Gamification System

-   Awareness Score
-   Progress bar
-   Page visit tracking
-   LocalStorage-based rewards

### 3. Multi-Language Support

-   English
-   Hindi
-   Marathi
-   Bengali
-   Tamil
-   Telugu

### 4. DBT Wallet Dashboard (Prototype UI)

-   Scholarship credit status
-   Pending payments
-   Linked DBT account

### 5. DigiLocker Verification (Prototype)

-   Simulated DBT certificate
-   Awareness about official verification

### 6. Step-by-Step DBT Enable Guide

-   Online seeding via NPCI
-   Offline bank branch process
-   USSD method (*99*99*1#)

------------------------------------------------------------------------

## Tech Stack

-   HTML5
-   Tailwind CSS (CDN)
-   Vanilla JavaScript
-   LocalStorage API
-   Fully Responsive Design

------------------------------------------------------------------------

## How to Run Locally

``` bash
git clone https://github.com/yourusername/dbt-mitra.git
cd dbt-mitra
open index.html
```

No backend required --- fully static website.

------------------------------------------------------------------------

## Deployment

You can deploy using:

-   GitHub Pages
-   Netlify
-   Vercel
-   Firebase Hosting

------------------------------------------------------------------------

## SIH25059 Alignment

This solution directly addresses:

> Enhancing Student Awareness on difference between Aadhaar linked and
> DBT-enabled Aadhaar seeded bank account.

By:

-   Educating students clearly
-   Providing actionable steps
-   Reducing DBT payment failures
-   Promoting digital inclusion

------------------------------------------------------------------------

## Author

**Kuntal Saha**\
B.Tech Student\
Smart India Hackathon 2025 Participant

------------------------------------------------------------------------

## License

This project is created for academic and hackathon purposes.
