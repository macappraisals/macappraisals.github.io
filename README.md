# MAC Appraisals — website skeleton

This is an initial static-site skeleton, not final production copy.

## Architecture

Primary navigation is intentionally limited to:
- About
- Services
- Appraisal Information
- Service Area
- Resources
- Contact

The detailed appraisal material is grouped into collapsible sections rather than creating dozens of menu items.

## Before publishing

1. Replace the placeholder email and phone values.
2. Replace `hero-placeholder.jpg` with an appropriate licensed image or original graphic.
3. Confirm the actual appraisal services offered.
4. Rewrite the biography and service descriptions from the appraiser's actual practice.
5. Add legal/privacy/accessibility details as appropriate.
6. Add a real contact form using a server-side or hosted form service.
7. Test mobile layout, links, forms, and SEO metadata.

## Hosting direction

This is deliberately plain HTML/CSS/JavaScript. It can be hosted on Cloudflare Pages, GitHub Pages, or conventional web hosting. That keeps the site portable and avoids locking the content into a site builder.

A later version can add server-side functionality, APIs, databases, authentication, and custom appraisal tools without rebuilding the public site from scratch.
