# Logoipsum Landing Page

A responsive landing page for a subscription analytics SaaS, built from a Figma design using HTML, CSS and vanilla JavaScript.

The product helps subscription businesses track market trends, benchmark their metrics against competitors, reduce churn and optimize pricing.

## Features

- **Responsive layout** with breakpoints at 1200px, 1024px, 768px and 480px
- **Mobile navigation** with a hamburger menu (pure CSS checkbox toggle)
- **Scroll-spy navigation**: the header link for the current section is highlighted while scrolling
- **Pricing toggle**: switch between Monthly and Yearly billing, prices update via JavaScript
- **Smooth scrolling** to anchor sections

## Page Structure

- **Header**: fixed navigation with section links and a call-to-action button
- **Hero**: main headline, description and call to action
- **Company logos**: partner logo strip
- **Features**: two alternating feature blocks with illustrations
- **Mini features**: three cards (Benchmarks, Pricing Audit, Retention Audit)
- **Pricing**: three plans with a Monthly / Yearly switch
- **Footer**: navigation columns, legal links and social icons

## Tech Stack

- HTML5
- CSS3 (custom properties, flexbox, grid, media queries)
- Vanilla JavaScript (DOM manipulation, event listeners, scroll-based section tracking)
- Google Fonts: DM Sans and Mulish

## Color Palette

| Variable  | Color     | Usage                  |
|-----------|-----------|------------------------|
| `--black` | `#19191B` | Headings, active links |
| `--gray`  | `#696871` | Body text, inactive links |
| `--orange`| `#FF7143` | Primary buttons        |
| `--purple`| `#5454D4` | Button hover state     |
| `--white` | `#FFFFFF` | Background             |

## Getting Started

No build step or dependencies are required.

1. Clone the repository:
   ```bash
   git clone https://github.com/karqintxa/test-landing-page.git
   ```
2. Open `index.html` in your browser.

For a local server, use the Live Server extension in VS Code or run `npx serve`.

## Known Issues

- The `Images/` folder (logo, icons, illustrations, favicon) is not included yet, so images will not display until it is added.
- Placeholder text (logo name, footer copyright) should be replaced before production use.

## Author

Danieel: front-end development and landing page layout.
