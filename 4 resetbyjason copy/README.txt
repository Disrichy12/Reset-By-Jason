RESET BY JASON — WEBSITE FILES
================================

This is the source for resetbyjason.com — a single-page static site.
No build step, no framework, no dependencies. Just HTML, CSS, and images.

FILES
-----
index.html    All the page content (text, structure, headings, copy)
styles.css    All the styling (colors, fonts, spacing, layout)
images/       All photos used on the site

HOW TO PREVIEW LOCALLY
----------------------
Just double-click index.html and it opens in any browser. That's it.

COMMON CHANGES — WHERE TO LOOK IN index.html
--------------------------------------------
Phone number:        search for  214-796-8695  or  (214) 796-8695
Hero headline:       search for  BRING IT IN
Tagline / subhead:   search for  boutique detailing studio
Prices:              search for  from $   (each price tag)
Hourly rate:         search for  $65/hr
Service descriptions: inside  <article class="service-card">  blocks
Customer quotes:     search for  customer-quote  or look in the Work section
About copy:          inside  <div class="about-text">
Email/Contact:       Contact section near the bottom

COMMON CHANGES — styles.css
---------------------------
Brand colors are defined at the TOP of styles.css in :root { ... }
  --bg              page background (currently very dark, #0b0b0d)
  --accent          the red used for "LEAVE IT BETTER" and buttons (#e63946)
  --text            main body text color
  --text-mute       secondary/grey text

Fonts are loaded from Google Fonts at the top of index.html:
  Anton  — used for big display text (the headlines)
  Inter  — used for body text

SWAPPING A PHOTO
----------------
Easiest: replace a file in /images/ with a new one using the SAME filename.
The site will pick it up automatically.

Otherwise: edit the src="images/whatever.jpeg" reference in index.html.

DEPLOYING / HOSTING
-------------------
The site is just static files. Any static host works:
- Cloudflare Pages (free, recommended)
- Netlify (free)
- GitHub Pages (free)
- Any web host that lets you upload HTML

Domain: resetbyjason.com is registered through GoDaddy.
Point the DNS at whatever host you choose.

QUESTIONS
---------
Built with Perplexity. Owner: Jason — (214) 796-8695
