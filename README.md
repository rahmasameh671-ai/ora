# ORA Developers — Premier Portfolio Landing Page
**By properties-z.com**

An ultra-luxurious, modern, mobile-responsive real estate landing page engineered for **ORA Developers** showcasing their premier portfolio:
1. **Silversands North Coast** (The Cove Lagoon Launch)
2. **ZED East** (New Cairo)
3. **ZED West** (Sheikh Zayed)

---

## 🏛️ Aesthetic Architecture & Guidelines

- **Strict Zero Gold Policy**: Absolutely NO gold, bronze, brass, or yellow tones anywhere across the layout.
- **Calm Luxury Architectural Palette**:
  - **Dominant**: Crisp pure white (`#FFFFFF`), clean alabaster (`#FAFBFD`), subtle stone grey (`#F8F9FA` / `#F1F3F5`).
  - **Accents**: Deep rich charcoal/slate (`#1A202C` / `#2D3748`) for razor-sharp typography and contrast.
  - **Cards & Modules**: Translucent frosted white cards (`rgba(255, 255, 255, 0.92)`) with delicate 1px cool borders (`#E2E8F0`) and backdrop blur.
  - **Typography**: High-end editorial Serif headlines (`Cinzel`) paired with ultra-readable modern Sans-serif (`Plus Jakarta Sans`) for specs, data points, and pricing.
- **Header & Navigation**:
  - **No Sticky Header**: The Hero section starts directly at `top: 0` without fixed headers.
- **Price Formatting**: Strictly formatted with capital 'M' (e.g. `9M EGP`, `17M EGP`).
- **Mobile-First Responsiveness**: 100% thumb-friendly layout collapsing smoothly into single-column modules.

---

## 📲 Direct Contact & WhatsApp Integration

- **Floating WhatsApp Button**: Round green icon-only button (`#25D366`) linking directly to `+201033373331` (no text labels).
- **Inline Action Buttons**: Solid vibrant WhatsApp Green (`#25D366`) reading `CONTACT US` linked directly with dedicated inquiry pre-filled messages:
  - **Silversands**: `https://wa.me/201033373331?text=Hello%2C%20I%20would%20like%20to%20inquire%20about%20Silversands%20The%20Cove`
  - **ZED East**: `https://wa.me/201033373331?text=Hello%2C%20I%20would%20like%20to%20inquire%20about%20ZED%20East`
  - **ZED West**: `https://wa.me/201033373331?text=Hello%2C%20I%20would%20like%20to%20inquire%20about%20ZED%20West`
  - **Naguib Sawiris Section**: `https://wa.me/201033373331?text=Hello%2C%20I%20would%20like%20to%20inquire%20about%20ORA%20Developers%20projects`
  - **Strategic Partner**: `https://wa.me/201033373331?text=Hello%2C%20I%20would%20like%20to%20consult%20with%20an%20expert%20about%20ORA%20Developers`

---

## 📬 Backend Lead Routing & Webhooks

Every lead submitted through the **Register Your Interest** form is routed to:
1. **Zapier Webhook**: `https://hooks.zapier.com/hooks/catch/25429357/uclzmpn/` (with `fullName`, `phoneNumber`, `countryCode`, `landingPageUrl`, `submissionDate`, `portfolio`)
2. **Multi-Recipient Email Dispatch**:
   - `Rahma@irtkaz.com`
   - `Mostafa.a.ashmawy@gmail.com`
   - `Mostafa.ashmawy@irtkaz.com`
3. **Local Storage Archive**: Backed up locally in `localStorage` under `ora_inquiries` for high reliability.

---

## 📄 Standalone Legal Routed Pages

- **Terms & Conditions**: `terms.html`
- **Privacy Policy**: `privacy.html`

Both pages are standalone routed HTML pages (not modals) designed in a formal, centered layout with 100% white text on a solid black background.

---

## 📁 Project Structure

```
ora/
├── index.html               # Main landing page
├── terms.html               # Standalone routed Terms & Conditions page
├── privacy.html             # Standalone routed Privacy Policy page
├── README.md                # Documentation
└── assets/
    ├── css/
    │   └── styles.css       # Calm Luxury stylesheet (Zero Gold Policy)
    ├── js/
    │   └── main.js          # Form handling, country selector & visual galleries
    └── images/
        ├── ora_logo.png
        ├── ora_logo_white.png
        ├── silversands_logo.png
        ├── silversands_logo_white.png
        ├── zed_east_logo.png
        ├── zed_east_logo_white.png
        ├── zed_west_logo.png
        ├── zed_west_logo_white.png
        ├── hero.jpg
        ├── silversands.jpg
        ├── silversands_gallery_1.jpg
        ├── silversands_gallery_2.jpg
        ├── zed_east.jpg
        ├── zed_east_gallery_1.jpg
        ├── zed_east_gallery_2.jpg
        ├── zed_west.jpg
        ├── zed_west_gallery_1.jpg
        ├── zed_west_gallery_2.jpg
        └── naguib_sawiris.jpg
```
