# Bluebell Health 🏥🦷

> **Bluebell Health** is a modern, responsive website tailored for dental clinics, wellness centers, and specialized healthcare practices. Designed with an elegant, patient-centric UI, the platform highlights treatments, professional medical staff, 24/7 emergency care, patient reviews, health articles, and streamlined appointment scheduling.

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Contact & Location Directory](#-contact--location-directory)
- [Technology Stack](#-technology-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Sections & Layout](#-sections--layout)
- [Customization](#-customization)
- [Browser Support](#-browser-support)
- [License](#-license)

---

## 🌟 Overview

**Bluebell Health** delivers a welcoming digital presence for patients seeking top-tier oral and general wellness care. The website is crafted with modern semantic HTML5, utility-first Tailwind CSS styling, dynamic Swiper.js carousels, and modular JavaScript animations.

---

## ✨ Key Features

- **Responsive Design**: Flawlessly adapts to smartphones, tablets, laptops, and 4K desktop screens.
- **Appointment Booking**: Clean, accessible form enabling patients to quickly request appointments or send inquiries.
- **24/7 Emergency Care Callout**: Prominent emergency hotline and alternative contact channels for urgent dental and medical care.
- **Interactive Service Cards**: Highlights specialized services (Dentures, Implants, Teeth Whitening, Root Canal treatments) with hover feedback.
- **Patient Testimonials Slider**: Touch-enabled, autoplaying testimonial carousel powered by Swiper.js with star ratings.
- **Health & Dental Blog**: Magazine-style carousel spotlighting dental hygiene tips, technology innovations, and remedies.
- **Interactive Clinic Map & Locations**: Clear visual map card showcasing primary clinic headquarters and alternative branch information.
- **Smooth Navigation & Mobile Drawer**: Off-canvas slide-out navigation for mobile devices and animated smooth-scrolling for all anchor links.
- **Performance Optimized**: Lightweight SVG vectors, high-compression WebP images, and custom preloader.

---

## 📞 Contact & Location Directory

Bluebell Health provides multiple direct and alternative contact options for patient convenience and emergency response:

| Detail | Primary Information | Alternative Details |
| :--- | :--- | :--- |
| **Brand Name** | **Bluebell Health** | Bluebell Medical & Dental Clinic |
| **Phone Line** | `+1 (800) 555-0199` | `+1 (555) 234-5678` |
| **Emergency Line** | `+1 (800) 555-0199` *(24H Hotline)* | `+1 (555) 234-5678` |
| **Email Support** | `info@bluebellhealth.com` | `care@bluebellhealth.com` |
| **Main Clinic** | 142 Bluebell Avenue, Suite 400, New York, NY 10016 | *Medical Plaza 4th Floor* |
| **Branch Clinic** | 78 Meadow Lane, Brooklyn, NY 11201 | *Wellness District Annex* |
| **Clinic Hours** | **Mon – Fri**: 08:30 AM – 18:00 PM | **Sat**: 09:00 AM – 14:00 PM *(24/7 Emergency)* |

---

## 🛠 Technology Stack

- **Markup**: [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) (Semantic, Accessible, SEO-friendly)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) & Custom CSS (Flexbox, CSS Grid, Custom Fonts)
- **Typography**: Custom Eudoxus Sans font family
- **Scripting**: Vanilla JavaScript (ES6+) with Intersection Observer API
- **Sliders & Carousels**: [Swiper.js v11](https://swiperjs.com/) (CDN)
- **Icons & Graphics**: Inline SVG symbols, crisp vector logos, and optimized WebP images

---

## 📁 Project Structure

```text
Bluebell-Health/
├── index.html                   # Primary landing page
├── README.md                    # Project documentation
├── assets/
│   ├── fonts/                   # Eudoxus Sans typography files (woff2)
│   │   ├── EudoxusSans-Light.woff2
│   │   ├── EudoxusSans-Regular.woff2
│   │   ├── EudoxusSans-Medium.woff2
│   │   └── EudoxusSans-Bold.woff2
│   └── images/                  # Visual assets, clinic photography & icons
│       ├── logo.svg             # Bluebell Health brand header logo
│       ├── logo-footer.svg      # Bluebell Health brand footer logo
│       ├── favicon.png          # Browser favicon
│       ├── map-image.webp       # Clinic location map
│       ├── top-main.webp        # Hero section graphic
│       ├── emergency-desktop.webp
│       ├── dentures.webp
│       ├── implants.webp
│       ├── whiting.webp
│       ├── rootcanal.webp
│       ├── blog-post-*.webp     # Blog article thumbnails
│       └── user-avatar-*.webp   # Testimonial patient avatars
├── scripts/
│   └── main.js                  # Preloader, sliders, mobile menu, and smooth scrolling
└── styles/
    └── main.css                 # Compiled styles, font faces, and custom utility classes
```

---

## 🚀 Getting Started

No build step or package installation is required. You can run the website immediately using any modern web browser.

### Option 1: Direct File Opening
Double-click `index.html` or open it with your preferred browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).

### Option 2: Local HTTP Server

#### Using Python
```bash
# Python 3
python -m http.server 3000
```
Then visit `http://localhost:3000` in your browser.

#### Using VS Code Live Server
1. Install the **Live Server** extension in VS Code.
2. Right-click `index.html` and select **"Open with Live Server"**.

#### Using Node.js (npx)
```bash
npx serve .
```

---

## 🏛 Sections & Layout

1. **Header**: Features the **Bluebell Health** brand logo, desktop navigation menu, appointment booking CTA, and mobile hamburger toggle.
2. **Hero Section (`#main`)**: Compelling headline, introduction, primary call-to-action button, and medical illustration.
3. **Services (`#services`)**: Four key dental care services with descriptions and quick inspection hover states.
4. **Emergency Care (`#emergency`)**: Dedicated 24/7 dental emergency announcement and direct booking action.
5. **Features & Highlights (`#features`)**: Quality indicators including *Safety First*, *Insurance Accepted*, *Full-Service Dentistry*, and *No Judgment Ever*.
6. **Dental Specialists (`#experts`)**: Credential highlights and dental expertise badges.
7. **Patient Reviews (`#testimonials`)**: Dynamic Swiper carousel showcasing patient feedback and 5-star ratings.
8. **Health Blog (`#blog`)**: Multi-card carousel with dates, categories, article titles, and previews.
9. **Contact & Appointment (`#contact`)**: Interactive booking form, clinic map overlay with physical address, and emergency phone channels.
10. **Footer**: Brand statement, quick site links, complete contact directory (phone, email, hours, addresses), and social media handles.

---

## 🎨 Customization

### Modifying Contact Information
To update phone numbers, emails, addresses, or opening hours, edit the contact block in `index.html`:
- **Map Overlay Address**: Locate the `<!-- Absolute Address -->` card inside the `#contact` section.
- **Emergency Helpline**: Locate the `<!-- Phone number -->` element beside the form submit button.
- **Footer Contact Details**: Update the `<!-- Contact us in Footer -->` list.

### Branding & Logo
- Header logo: [`assets/images/logo.svg`](./assets/images/logo.svg)
- Footer logo: [`assets/images/logo-footer.svg`](./assets/images/logo-footer.svg)
- Update brand colors in `styles/main.css` (primary brand color: `#583FBC`).

---

## 🌐 Browser Support

- Google Chrome (latest)
- Mozilla Firefox (latest)
- Microsoft Edge (latest)
- Apple Safari (latest)
- Opera (latest)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). You are free to customize, adapt, and deploy it for medical, dental, and health clinic web projects.
