# Innosenta Brand Assets Guide

> **Brand Name:** Innosenta  
> **Tagline:** Dzīvā kosmētika (Living Cosmetics)  
> **Website:** https://innosenta.com/  
> **Industry:** Natural/organic skincare cosmetics  
> **Company:** SIA "Spring Breath" (Reg. Nr. 40203384113)  
> **Contact:** info@innosenta.lv  
> **Social:** [Facebook](http://facebook.com/innosenta.cosmetics) | [Instagram](https://www.instagram.com/innosenta_cosmetics/)

---

## 1. COLOR PALETTE

### Primary Colors (from Elementor CSS variables)

| Color Name | Hex Code | CSS Variable | Usage |
|---|---|---|---|
| **Primary Blue** | `#8AACC1` | `--e-global-color-primary` | Header, buttons, primary accents, section backgrounds |
| **Secondary Grey** | `#54595F` | `--e-global-color-secondary` | Secondary text, dark elements |
| **Text Grey** | `#7A7A7A` | `--e-global-color-text` | Body/paragraph text |
| **Accent Blue-Grey** | `#6C7E90` | `--e-global-color-accent` | Accent elements |
| **White** | `#FFFFFF` | `--e-global-color-0030b2a` | Backgrounds, text on dark |
| **Lavender Grey** | `#EEE5E9` | `--e-global-color-c320776` | Soft section backgrounds |
| **Black** | `#000000` | `--e-global-color-ca90b27` | Primary text, headings |
| **Transparent** | `#02010100` | `--e-global-color-714315c` | Transparent overlays |
| **Dark Teal** | `#395C6B` | `--e-global-color-37196ef` | Deep accent, footer elements |
| **Muted Sage** | `#77928B` | `--e-global-color-1c9885a` | Tertiary accent |
| **Off-White** | `#FAFAFA` | `--e-global-color-1d63fb0` | Light backgrounds |
| **Duplicate Primary** | `#8AACC1` | `--e-global-color-4b98934` | Same as primary |
| **Duplicate Accent** | `#6C7E90` | `--e-global-color-77454b4` | Same as accent |
| **Light Blue** | `#E8F5FD` | `--e-global-color-0833caa` | Very light blue backgrounds |

### Page Transition Color
| Color | Hex | Usage |
|---|---|---|
| **Warm Gold** | `#FFBC7D` | Page transition animation background |

### Summary of Key Brand Colors
```
Primary:     #8AACC1  (Soft blue — the main Innosenta brand color)
Dark Teal:   #395C6B  (Deep supporting color)
Accent:      #6C7E90  (Muted blue-grey)
Sage:        #77928B  (Natural green-grey)
Lavender:    #EEE5E9  (Warm grey backgrounds)
Light Blue:  #E8F5FD  (Lightest background tint)
Off-White:   #FAFAFA  (Clean background)
Text:        #7A7A7A  (Body text)
Dark:        #54595F  (Secondary dark)
Black:       #000000  (Headlines)
White:       #FFFFFF  (Contrast)
Gold:        #FFBC7D  (Transition/highlight accent)
```

---

## 2. TYPOGRAPHY

### Font Files (downloaded to `/fonts/`)

| Font Name | CSS Family Name | File | Weight | Usage |
|---|---|---|---|---|
| **Gill Sans Nova Light** | `Virsrakstiem Gill Sans` | `Gill-Sans-Nova-Light.woff` | 600 (primary), 400 (h1) | Headings (h1-h4), primary typography |
| **Clear Sans Light** | `Clear Sans Thin Aprakstiem` | `ClearSans-Light.woff` | 400 | Body text, descriptions, secondary text |
| **Vogue** | `Vogue Regular` | `Vogue.woff2` | normal | Buttons, calls-to-action — gives a sophisticated, high-end feel |
| **Roboto** | `Roboto` | *(Google Font)* | 500 | Accent/UI typography |

### Font-Face Declarations
```css
@font-face {
    font-family: 'Virsrakstiem Gill Sans';
    font-style: normal;
    font-weight: normal;
    font-display: auto;
    src: url('./fonts/Gill-Sans-Nova-Light.woff') format('woff');
}

@font-face {
    font-family: 'Clear Sans Thin Aprakstiem';
    font-style: normal;
    font-weight: normal;
    font-display: auto;
    src: url('./fonts/ClearSans-Light.woff') format('woff');
}

@font-face {
    font-family: 'Vogue Regular';
    font-style: normal;
    font-weight: normal;
    font-display: auto;
    src: url('./fonts/Vogue.woff2') format('woff2');
}
```

### Typography Hierarchy
- **Base font:** `"Clear Sans Thin Aprakstiem", Sans-serif` (weight 400)
- **H1:** `"Virsrakstiem Gill Sans", Sans-serif` (weight 400)
- **H2-H4:** `"Virsrakstiem Gill Sans", Sans-serif`
- **Buttons:** `"Vogue Regular", Sans-serif`
- **Accent/UI:** `"Roboto"` (weight 500)

---

## 3. IMAGES & ASSETS

### Logo
| File | Description | Format |
|---|---|---|
| `images/logos/logo-white.webp` | Full white logo (1536×700) | WebP |
| `images/logos/winner-badge.webp` | "Natural Beauty Winner" award badge (1024×1024) | WebP |

### Background / Hero Images
| File | Description | Usage |
|---|---|---|
| `images/backgrounds/hero-flower.jpg` | Transparent blue flower — main hero image | Homepage hero section |
| `images/backgrounds/background-floral-1.jpg` | Floral background pattern | Section backgrounds |
| `images/backgrounds/background-floral-2.jpg` | Second floral background | Section backgrounds |

### Product Images (1024×1024)
| File | Product Name (LV) | Product Name (EN) | Price |
|---|---|---|---|
| `images/products/hydrapeptide-serum.webp` | HydraPeptide Serum | HydraPeptide Serum | €33.00 |
| `images/products/lip-balm.webp` | Barojošs lūpu balzāms | Nourishing Lip Balm | €5.00 |
| `images/products/probiobalance-fluid.jpg` | ProbioBalance Fluid | ProbioBalance Fluid | €35.00 |
| `images/products/face-foam.webp` | Sejas putas | Face Foam | €12.00 |
| `images/products/face-tonic.webp` | Sejas toniks | Face Tonic | €10.00 |
| `images/products/antioxidant-serum.webp` | Mitrinošs antioksidantu serums | Moisturizing Antioxidant Serum | €29.00 |
| `images/products/mama-beauty-keratin.jpg` | MaMa BEAUTY uzacu/skropstu keratīns | MaMa BEAUTY Eyebrow/Lash Keratin | €14.00 |

### Screenshots (page captures for design reference)
| File | Description |
|---|---|
| `screenshots/homepage-full.png` | Full homepage capture |
| `screenshots/homepage-bottom.png` | Homepage footer/bottom section |
| `screenshots/shop-page-top.png` | Shop page — top products |
| `screenshots/shop-page-products.png` | Shop page — scrolled/more products |
| `screenshots/about-page.png` | About page (Par mums) |

---

## 4. WEBSITE STRUCTURE & NAVIGATION

### Main Navigation
```
├── Sākums (Home)
├── Veikals (Shop)
│   ├── Visi produkti (All Products)
│   ├── Produkta veids (Product Type)
│   │   ├── Sejas attīrtošie līdzekļi (Face Cleansers)
│   │   ├── Toniki (Toners)
│   │   ├── Serumi & fluīdi (Serums & Fluids)
│   │   ├── Krēmi (Creams)
│   │   └── Acu zona (Eye Zone)
│   └── Īpašie piedāvājumi (Special Offers)
│       ├── Best sellers
│       ├── Idejas dāvanām (Gift Ideas)
│       ├── Dāvanu kartes (Gift Cards)
│       └── Paraugu komplekti (Sample Kits)
├── Blogs
├── Par zīmolu (About Brand)
└── Kontakti (Contacts)
```

### Language Support
- Latvian (LV) — primary
- English (EN)
- French (FR)
- German (DE)
- Swedish (SV)
- Russian (RU)

### Top Banner
"Bezmaksas piegāde Latvijā no 40 EUR" (Free delivery in Latvia from €40 EUR)

---

## 5. PAGE CONTENT (LATVIAN)

### Homepage Sections

**Hero Section:**
> Innosenta dzīvā kosmētika  
> Iepazīsti jaunu ādas kopšanas pasauli un uzzini, kāpēc Innosenta dzīvā kosmētika ir tik liels retums dabīgās kosmētikas pasaulē, un tāpēc – vērtīgs atradums.

**Section: DABAS PIELĀGOTA KOSMĒTIKA / Tavai ādai**
> Innosenta veido savu produktu pievienoto vērtību, izmantojot dabas izejvielas to iespējami dabiskākajā formā, saglabājot tām dabas dotās īpašības, nevis cenšoties tās tehnoloģiski pārveidot.
> Innosenta produkti netiek "uzlaboti" ar mākslīgi veidotām piedevām.
> Atšķirībā no "dabīgās kosmētikas" ar piejaukumiem, kuri palīdz radīt ātrāk vēlamo vizuālo efektu, taču piesārņo šūnas, Innosenta dzīvā kosmētika harmoniski aktivizē ādas šūnu darbību un harmoniski mijiedarbojas ar tām.

**Value Propositions:**
- PREMIUM KVALITĀTE — SVAIGI PRODUKTI TIKAI NO DABĪGĀM IZEJVIELĀM
- ĀTRA IZPILDE — PASŪTĪJUMI TIEK IZPILDĪTI 1-3 DIENU LAIKĀ
- IEPAZĪŠANĀS CENAS! — IZDEVĪGA IESPĒJA IEPAZĪT LIELISKOS INNOSENTA PRODUKTUS

**Featured Products Section:** "Pašlaik aktuālais" (Currently trending)
- Barojošs krēms (Nourishing Cream)
- Acu krēms (Eye Cream)
- INNOSENTA 'TRAVEL-SET'

### About Page (Par mums)

**Section: Kas ir Innosenta dzīvā kosmētika?**
> Īsumā – īsts retums. Dzīvo kosmētiku raksturo tas, ka visas tās radīšanā izmantotās izejvielas ir patiešām dabīgas.

**Section: Kā tā top? (How it's made)**
> Innosenta veido savu produktu pievienoto vērtību, izmantojot dabas izejvielas to iespējami dabiskākajā formā.

**Section: Kā tā darbojas? (How it works)**
> Cilvēka organisms ir dabas sastāvdaļa, tāpēc uz to efektīvāk iedarbojas viss dzīvais, vitālais.

**Section: "Dabīgās kosmētikas" ilūzija ("Natural cosmetics" illusion)**
> Critical messaging about why most "natural" cosmetics aren't truly natural.

### Footer Content
- Company: SIA "Spring Breath"
- Reg. Nr. 40203384113
- Email: info@innosenta.lv
- Links: Privātuma politika, Veikala noteikumi, Preču piegāde, Preču atgriešana, Kontakti
- Social: Facebook, Instagram
- Newsletter signup: "Pieraksties jaunumiem" (Subscribe to updates)

---

## 6. DESIGN CHARACTERISTICS

### Visual Style
- **Clean & minimalist** with ample white space
- **Nature-inspired** — floral imagery, soft blue tones
- **Premium/luxurious** feel through elegant typography (Vogue font) and muted color palette
- **Science-meets-nature** aesthetic

### Layout Patterns
- **Header:** Sticky navigation with white logo on blue-grey (#8AACC1) background
- **Hero:** Large transparent floral graphic on left, text + CTA on right  
- **Product cards:** 1024×1024 square product photos, uppercase product type labels, serif pricing
- **Sections:** Alternating white and light backgrounds with subtle floral overlays
- **Footer:** Dark teal (#395C6B) with three columns (company info, legal links, brand statement)
- **Max container width:** 1140px

### UI Elements
- **Buttons:** Outlined style with "Vogue Regular" font, uppercase text
- **Cards:** Clean product cards with hover states
- **Language switcher:** Flag icons with country codes
- **Cart:** Simple cart icon with item count and total
- **Newsletter:** Email signup form in footer area

---

## 7. CSS VARIABLES (copy-paste ready)

```css
:root {
    /* Brand Colors */
    --color-primary: #8AACC1;
    --color-secondary: #54595F;
    --color-text: #7A7A7A;
    --color-accent: #6C7E90;
    --color-white: #FFFFFF;
    --color-lavender: #EEE5E9;
    --color-black: #000000;
    --color-dark-teal: #395C6B;
    --color-sage: #77928B;
    --color-off-white: #FAFAFA;
    --color-light-blue: #E8F5FD;
    --color-gold: #FFBC7D;
    
    /* Typography */
    --font-heading: "Virsrakstiem Gill Sans", Sans-serif;
    --font-body: "Clear Sans Thin Aprakstiem", Sans-serif;
    --font-button: "Vogue Regular", Sans-serif;
    --font-ui: "Roboto", Sans-serif;
    
    /* Layout */
    --container-max-width: 1140px;
}
```

---

## 8. PRODUCT CATALOG

| # | Product (LV) | Product (EN) | Category | Price | URL |
|---|---|---|---|---|---|
| 1 | Sejas putas | Face Foam | Cleansers | €12.00 | /product/sejas-putas/ |
| 2 | Sejas toniks | Face Tonic | Toners | €10.00 | /product/sejas-toniks/ |
| 3 | Barojošs lūpu balzāms | Nourishing Lip Balm | Special | €5.00 | /product/barojoss-lupu-balzams/ |
| 4 | HydraPeptide Serum | HydraPeptide Serum | Serums | €33.00 | /product/hydrapeptide-serum/ |
| 5 | Mitrinošs antioksidantu serums | Moisturizing Antioxidant Serum | Serums | €29.00 | /product/mitrinoss-antioksidantu-serums/ |
| 6 | ProbioBalance Fluid | ProbioBalance Fluid | Fluids | €35.00 | /product/prebiobalance-fluid/ |
| 7 | MaMa BEAUTY uzacu/skropstu keratīns | Eyebrow/Lash Keratin | Special | €14.00 | /product/mama-beauty-uzacu-un-skropstu-keratins-ar-fiksaciju/ |
| 8 | Barojošs krēms | Nourishing Cream | Creams | — | /product/barojoss-krems-2/ |
| 9 | Stimulējošs acu krēms | Stimulating Eye Cream | Eye Zone | — | /product/stimulejoss-acu-krems/ |
| 10 | INNOSENTA Travel-Set | INNOSENTA Travel Set | Sample Kits | — | /product/paraugu-komplekts/ |
| 11 | Dāvanu karte | Gift Card | Gift Cards | — | /product/davanu-karte/ |

---

## 9. ORIGINAL CSS FILE

The full Elementor theme CSS is saved alongside this document. Key excerpt:

```css
.elementor-kit-13 {
    --e-global-color-primary: #8AACC1;
    --e-global-color-secondary: #54595F;
    --e-global-color-text: #7A7A7A;
    --e-global-color-accent: #6C7E90;
    --e-global-color-0030b2a: #FFFFFF;
    --e-global-color-c320776: #EEE5E9;
    --e-global-color-ca90b27: #000000;
    --e-global-color-714315c: #02010100;
    --e-global-color-37196ef: #395C6B;
    --e-global-color-1c9885a: #77928B;
    --e-global-color-1d63fb0: #FAFAFA;
    --e-global-color-4b98934: #8AACC1;
    --e-global-color-77454b4: #6C7E90;
    --e-global-color-0833caa: #E8F5FD;
    
    --e-global-typography-primary-font-family: "Virsrakstiem Gill Sans";
    --e-global-typography-primary-font-weight: 600;
    --e-global-typography-secondary-font-family: "Clear Sans Thin Aprakstiem";
    --e-global-typography-secondary-font-weight: 400;
    --e-global-typography-text-font-family: "Clear Sans Thin Aprakstiem";
    --e-global-typography-text-font-weight: 400;
    --e-global-typography-accent-font-family: "Roboto";
    --e-global-typography-accent-font-weight: 500;
    
    font-family: "Clear Sans Thin Aprakstiem", Sans-serif;
}
```
