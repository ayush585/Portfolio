# Ayushman Mukherjee — official personal website

A static, accessible, zero-dependency site for Ayushman (Ash) Mukherjee, co-founder and CTO of Loreflow.

## Current status
This branch is a review candidate, not a live website. It is intentionally not connected to a new domain or Search Console property.

## Content principles
- Full real name in title, content, metadata, and ProfilePage structured data.
- Company affiliation, published writing, and projects grounded in public links.
- No invented metrics, press, customer counts, or Knowledge Panel promises.
- No private email, school, birth date, contact forms, trackers, or third-party scripts.
- Keyboard-accessible navigation, reduced-motion support, semantic markup, mobile layout.

## Publishing checklist
1. Approve the public biography, company role, projects, and linked accounts.
2. Choose and verify one official domain; do not use a guessed domain.
3. Configure publicly accessible hosting with no authentication requirement.
4. Add a canonical URL and matching og:url pointing to the final verified domain.
5. Optionally add a real, approved professional portrait and social preview image.
6. Build sitemap.xml with only live canonical URLs and add its absolute URL to robots.txt.
7. Verify domain ownership in Google Search Console; submit sitemap and inspect the URL.
8. Test JSON-LD with Google's Rich Results Test; markup never guarantees special search features.
9. Link the official site from GitHub, LinkedIn, Medium, ORCID, and Loreflow's founders page.
10. Redirect old publicly hosted portfolio variants after verifying migration, rather than indexing duplicates.

## Existing Loreflow site issue
As checked October 2026, Loreflow's About page includes specific claims about team size, company history, financing, and design partners. Verify with the team and correct unsupported claims before amplifying the page.

## Technical notes
- Single index.html, no dependencies or build step.
- Any static host works. For local preview: python -m http.server 8000.
- SEO: descriptions, social metadata and JSON-LD included.
- Canonical URL, final og:url, preview image, and sitemap deferred until a real domain is confirmed.

## Editorial next steps
- Publish periodic engineering notes based on verifiable outcomes and evidence.
- Ask The AI Journal to provide a dedicated author profile for the 2026 article.
- Earn independent editorial coverage when there is a genuinely newsworthy story.
