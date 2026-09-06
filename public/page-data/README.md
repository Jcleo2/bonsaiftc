Per-page resource data

This folder contains one JSON file per page. Edit the matching JSON to update images, PDFs, and content for that page.

Filename conventions:
- `index.json` — resources for the main landing (`bonsai.exe.html`)
- `portfolio.json` — portfolio-specific resources (PDFs, items)
- `blog.json` — blog posts and per-post images
- `coaches.json` — list of coaches/mentors and their photos
- `gallery.json` — gallery images
- `outreach.json` — outreach resources
- `sponsor.json` — sponsor page resources

Notes:
- The site expects images as PNG files per your request (e.g. `images/coaches/coach1.png`). If you don't have PNGs yet, you can point to external images or leave the fields blank.
- Place PDF files under the `pdfs/` folder and reference them by relative path (e.g. `pdfs/drivebase-review.pdf`). Only `portfolio.json` needs a PDF entry.
