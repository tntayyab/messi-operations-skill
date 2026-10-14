# ⛔ KYROS Zero-Tolerance QA Standards

This document outlines the strict quality criteria supervised by **Messi** across all web properties developed by **Leo**, optimized by **Nur**, or driven by **TNT**.

---

### 1. Dual Search Bar Prohibition
- Many themes render a default search form in the header and another inside the homepage hero section.
- **Rule:** Under no circumstances should more than ONE search input be present. If hero has search, remove header search. If neither is needed, disable both.

---

### 2. Symmetrical 3-Column Footer
- **Column 1 (`About Us`):**
  - Company editorial bio (40-60 words).
  - Business address.
  - Official contact email.
- **Column 2 (`Top Categories`):**
  - Native WP `nav_menu` widget.
  - Top 5-6 core content pillars.
- **Column 3 (`Legal & Transparency`):**
  - Native WP `nav_menu` widget with 6 mandatory pages:
    1. About Us
    2. Contact Us
    3. Privacy Policy
    4. Terms & Conditions
    5. Disclaimer
    6. Affiliate Disclosure
  - Followed by FTC disclosure text block.

---

### 3. Visual Assets & Image Guidelines
- **Format:** Strict WebP.
- **Hero / Category Images:** 800x533 px, compressed < 100 KB.
- **Typography Rule:** 100% textless. No titles, subtitles, or watermarks baked into the image.
- **Author Avatars:** 400x400 to 500x500 px, compressed < 40 KB. Each site must feature a unique persona.

---

### 4. Cross-Site Visual Asset Reuse Prohibition (Critical QA)
- ❌ **NEVER REUSE BANNERS OR CATEGORY IMAGES:** Reusing visual assets between different KYROS domains (e.g. Autoverse Authority assets placed on CarSpeedNest) destroys individual domain identity and brand credibility.
- Every website MUST have 100% uniquely sourced and curated textless WebP images (<100 KB) tailored strictly to its distinct angle and audience.

---

### 5. Mandatory Logo Contrast & 5-Point Frontend QA Audit
- ❌ **NO LOW-CONTRAST LOGOS:** Logo typography must be razor-sharp and easily readable. White/light text on a light header bar is strictly prohibited (e.g. white "SPEEDNEST" on a light header).
- **Transparent Canvas Only:** Logos must use transparent alpha channels (PNG/WebP) with zero opaque bounding boxes clashing with header backgrounds.
- **Mandatory 5-Point Frontend QA Check:** Leo must personally open the live URL and visually verify:
  1. Header logo contrast and transparent background.
  2. Navbar item padding and line-wrapping cleanliness.
  3. Hero slider visual uniqueness and textless imagery.
  4. Category cards and WebP compression (<100 KB).
  5. Symmetrical 3-column footer leveling.
