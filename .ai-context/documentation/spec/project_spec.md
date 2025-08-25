# Thrive Wildly LLC Website - Project Specification

## Session Overview

This document summarizes the key decisions and implementation details for the Thrive Wildly LLC static website, developed during a pair programming session. The primary goal was to create a low-maintenance, SEO-friendly thin wrapper around existing POS and order form endpoints, with a mobile-first design approach and minimal JavaScript.

## Technology Stack

*   **HTML5 & CSS3:** Core structure and styling.
*   **Tailwind CSS (CDN-based):** Chosen for its utility-first approach, enabling highly customizable and professional designs without a complex build process or a heavy JavaScript framework. Custom green and brown color palettes were defined to avoid generic aesthetics.
*   **Pure JavaScript:** Used for interactive elements (e.g., toggling embedded forms) without relying on external JS frameworks, ensuring low overhead and easy maintenance.

## Core Features Implemented

1.  **Low-Maintenance Architecture:** Static HTML with Tailwind CSS (CDN) and minimal inline JavaScript, requiring no server-side logic or complex deployment.
2.  **SEO Optimization:** Control over meta tags (`<title>`, `description`), semantic HTML, and descriptive content around embedded forms to aid search engine indexing.
3.  **Branding & Aesthetics:**
    *   Custom logo (`<img>` tag) integrated into the header.
    *   Favicon set to the brand logo for browser tab identification.
    *   Social media links (Instagram, Facebook, TikTok) replaced with SVG icons for a polished look.
    *   Linktree link also converted to an SVG icon and placed with social media icons.
    *   Consistent color theme (custom greens and browns) applied using Tailwind CSS.
4.  **Centralized Access & Embedded Forms:**
    *   **Single-Page Application (SPA) feel:** Embedded Jotform (Standard & Custom Orders) and Square Appointments (Bloom Bar Booking) directly into the page using `<iframe>` and a Square Appointments JS widget.
    *   **Tabbed Interface for Forms:** Implemented a JavaScript solution to show only one embedded form at a time. Navigation links now toggle the visibility of the respective form sections, improving user experience by reducing clutter.
    *   External links (Linktree, Subscribe for Monthly Bouquets) are now clearly separated as promo links/badges, opening in new tabs.
5.  **Information Hierarchy:**
    *   Header: Logo, social/external icons, tagline (initially a concise one, later removed for extreme minimalism).
    *   Main Content: Dynamic display of embedded forms.
    *   Footer: Original, detailed tagline and copyright information.

## Future Considerations

*   Further refinement of Tailwind CSS classes for specific design elements.
*   Potential addition of more descriptive content around embedded forms for enhanced SEO.
*   Accessibility improvements.
*   Integration of Instagram feed for social media presence.

## Contact for Inquiries

thrivingwildlyfloraldesign@gmail.com
