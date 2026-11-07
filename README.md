# New Service Pages + Quote Form - Jacksonville Pressure Wash

## Files in this folder (9 files - upload ALL of them)
1. `index.html` - UPDATED homepage. More Services list now links to the new pages, hero button now goes to quote.html, nav and footer have a Get a Quote link.
2. `window-cleaning.html` - Window Cleaning Jacksonville, FL
3. `gutter-cleaning.html` - Gutter Cleaning Jacksonville, FL
4. `pool-deck-cleaning.html` - Pool Deck Cleaning Jacksonville, FL
5. `screen-enclosure-pool-cage-cleaning.html` - Screen Enclosure & Pool Cage Cleaning Jacksonville, FL
6. `dryer-vent-cleaning.html` - Dryer Vent Cleaning Jacksonville, FL
7. `rust-stain-removal.html` - Rust & Stain Removal Jacksonville, FL
8. `commercial-exterior-cleaning.html` - Commercial Exterior Cleaning Jacksonville, FL
9. `quote.html` - 3-step quote form

## What is in each service page
Same header, footer, colours and style as your house-washing page. Each page has:
- Hero, intro, What We Clean (5 cards), Common Problems (6), Our Process (5 steps), FAQ (5 questions)
- 7-Day Satisfaction Check, Working Hours Monday-Friday 9:00 AM - 4:00 PM ET, 24-hour reply
- Phone 877-367-5979, email info@flpressurewashingjacksonville.com
- Updated date November 7, 2026
- No Licensed & Insured claim, no fake reviews, no fake photos, no invented prices.

## Quote form - how it works (important)
- Step 1: Choose services (all 13 services, tick boxes)
- Step 2: Property type, service area, address, details, photo upload box
- Step 3: Name, phone, email, best contact method, best time
- On Send, it opens an email to info@flpressurewashingjacksonville.com with everything filled in. The customer just presses Send in their email app.
- Photos: email cannot attach photos automatically from a form. The form tells the customer clearly to attach their photos in the email before sending. This is normal for a static HTML site with no backend.
- If you later get a backend / Formspree / Netlify Forms, the same form can be connected to it. For now, mailto is the honest way.

## How to upload (same as last time)
1. Copy ALL 9 files into your VS Code project folder, Replace when asked.
2. Save, then commit and push to GitHub origin/main. Commit message suggestion:
   `Add 7 new service pages and quote form`
3. Check Vercel Deployments - a new deployment must appear for this commit. If not, Redeploy from the latest deployment.
4. If your domain is also on Hostinger, upload the same 9 files to public_html.
5. Test: open https://flpressurewashingjacksonville.com/quote.html and try the form. Click a new service link from the homepage More Services list.

## Sitemap - add these 8 URLs to sitemap.xml
Add one entry for each new page, same format as your other pages:
- https://flpressurewashingjacksonville.com/window-cleaning.html
- https://flpressurewashingjacksonville.com/gutter-cleaning.html
- https://flpressurewashingjacksonville.com/pool-deck-cleaning.html
- https://flpressurewashingjacksonville.com/screen-enclosure-pool-cage-cleaning.html
- https://flpressurewashingjacksonville.com/dryer-vent-cleaning.html
- https://flpressurewashingjacksonville.com/rust-stain-removal.html
- https://flpressurewashingjacksonville.com/commercial-exterior-cleaning.html
- https://flpressurewashingjacksonville.com/quote.html
Use lastmod 2026-11-07 for these 8.
