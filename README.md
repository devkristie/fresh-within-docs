# Fresh Within™ Website Documentation

This repository contains internal documentation for the Fresh Within™ website, a UK wellness brand offering the first internal deodorant capsule.

## Overview

- **Website Purpose:** E-commerce platform for Fresh Within™ products, with informational pages, blog/articles, FAQs, and preorder functionality (currently active; standard purchase flow will replace preorder once products are in stock).
- **Page Builder:** Elementor
- **Theme:** Hello Elementor (lightweight, minimalist theme built to work seamlessly with Elementor)
- **Custom CSS:** Added via Appearance → Customize → Additional CSS
- **SEO:** Titles, meta descriptions, and focus keyphrases configured per page using Yoast SEO plugin.

## Technologies & Permissions

- **User Role:** Editor with Admin access (Design Admin)
- **Technologies Used:** WordPress, Elementor, HTML, CSS
- **Legal Notes:** All content, branding, and customizations (including Custom CSS) belong to **Rava Books Ltd / Fresh Within™**. WordPress core, themes, and plugin code remain the property of their respective developers.

## Pages

- Home
- About Us
- Our Product
- Shop
- Cart
- Blog & Articles
- FAQs
- Contact Us
- Checkout
- Subscribe
- Refund & Returns
- Terms & Conditions
- Privacy Policy

> Note: Pages are built with Elementor templates. The default Privacy Policy template cannot be edited by editors—only viewed or duplicated. A duplicate was created, and navigation links were updated to point to the editable version.

> Note: The original Privacy Policy page must remain for legal reasons. A duplicate was created for editable design purposes, and the footer link now points to the duplicate. The Checkout Page privacy policy link currently points to the original page; client action is required to update this link.

## Notes

- SEO keyphrases are configured per page. Yoast SEO status (green/orange) depends on content and keyphrase match.

- Mobile responsiveness: Some Custom CSS adjustments were made for mobile optimization, particularly for the preorder progress bar.

## Custom CSS

All custom styling edits were made via Appearance → Customize → Additional CSS in WordPress.

## Theme Information

- **Theme:** Hello Elementor

- **Version:** 3.4.6

- **Author:** Elementor Team

- **Notes:** Lightweight, minimalist WordPress theme optimized for use with Elementor. Provides a flexible foundation for building custom designs. Auto-updates enabled.

## SEO Improvements Implemented

- Standardised SEO title structure across all core pages.
- Configured unique focus keyphrases aligned with search intent.
- Optimised meta descriptions for clarity and click-through potential.
- Improved keyword consistency across headings and content.

## Design Implementation

### Colour Palette (Site Usage)

| Usage                        | Hex Code |
| ---------------------------- | -------- |
| Primary Brand Colour         | #003366  |
| Secondary Brand Colour       | #009345  |
| Primary Accent (CTA)         | #4EA72E  |
| Secondary Accent (Highlight) | #F2295B  |
| Secondary Accent (Promotion) | #FEC803  |
| Primary Background           | #EFE1C7  |
| Secondary Background         | #F4F4F4  |
| Tertiary Background          | #F2F1ED  |
| Primary Text                 | #000000  |

Colours were implemented consistently across buttons, headings, links, and call-to-action elements to maintain brand cohesion.

### Typography

- **Primary Font:** Arial
- **Secondary Font:** Helvetica
- **Headings:** Font weight 600 (Semi-Bold)
- **Body Text:** Normal weight (400)

Typography was configured via Elementor Global settings to ensure consistency across all templates and pages.

### Site Structure

- **Header:** Appears on all pages; includes primary navigation and a call-to-action button.
- **Content Placement:**  
  Ensured that Home and About Us content were correctly separated and placed on their respective pages, improving clarity and preventing content from visually merging.
- **Footer:** Appears on all pages; includes contact information, social media links, legal links (Privacy Policy, Terms & Conditions), and newsletter signup.
- Both header and footer are global Elementor templates, ensuring consistent branding and navigation across the site.

## Issues & Observations During Implementation

- **Investor Information Container**
  - Added a legal/Investor Information statement to the designated container on the site to clarify SEIS status and company focus.

- **Add To Cart Button UX**
  - Observed no visible cart indicator on the product page.
  - Suggested adding a cart icon or “Your Cart” link near the button to improve user awareness.
  - Client decided to place the cart link in the main navigation bar instead, which temporarily caused a minor responsiveness issue on smaller screens; issue was later resolved.

- **Product Title Formatting**
  - Noted minor formatting issue: extra space in “Fresh Within™ Internal Deodorant Formula (60 Capsules )”.
  - Raised issue with client due to restricted WooCommerce access. Client updated the title accordingly.

- **Product Description / Shortcode Visibility**
  - [preorder_countdown] shortcode appeared in the short description at the top of the product page.
  - Identified limitation due to restricted content editing access; client updated the short description and moved content as needed.

- **Product Information Message**
  - The following text appeared in the product section:
    “Due to the difference between different monitors, the image may not reflect the actual color of the item. Thank you very much!”
  - Suggested removing “Thank you very much!” as it was unnecessary within this context.
  - The feedback was provided to improve clarity and professionalism of the product messaging.

- **Product Description Content**
  - Recommended adding additional detail to top and bottom product descriptions to improve clarity and user understanding.
  - Feedback provided; content updates implemented by client.

- **Global Text Colour Update**
  Updated site-wide default text color from WordPress’s blue to black using Custom CSS:

  ```css
  /* Global font color */
  body {
    color: #000000 !important;
  }
  ```

- **Refund & Returns Policy:**
  - Policy included a physical address (5 Brayford Square, London, E1 0SG) for returns, despite instructions not to send items back to the manufacturer.
  - Clarified with client that this is their registered business address, not the contract manufacturer, but with limited capacity for receiving returns.
  - Recommended either confirming the address can reliably process returns or removing it until confirmed. No final decision received at the time of documentation.

## Legal / Permissions

This repository is for **internal documentation and project tracking purposes only**.

- All content, branding, and customizations (including Custom CSS) of the Fresh Within™ website remain the property of **Rava Books Ltd / Fresh Within™**.

- WordPress core, themes, and plugin code remain the property of their respective developers.

- **No proprietary content** (full page content, images, plugin code) should be shared publicly without explicit permission. Only documentation, notes, and non-proprietary code snippets may be referenced outside the company.
