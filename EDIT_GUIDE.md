# Portfolio Edit Guide

Open `index.html` in a browser to view the portfolio.

Edit content in `data.js`:

- Name, headline, intro, contact links, and availability are near the top.
- The profile image is controlled by `profileImage.src`.
- Stats, skills, experience, impact cards, education, and awards are separate arrays.
- Project images are controlled by each project item's `image` value.
- Keep quotes around text values and commas between list items.

Edit design in `styles.css`:

- Main colors are defined at the top under `:root`.
- The hero visual is `assets/tech-grid.png`.
- Mobile layout rules are at the bottom in the media queries.

Edit behavior in `app.js`:

- The experience tabs, theme toggle, contact buttons, and reveal animations are rendered here.

No build step is required. The site is static and can be uploaded as-is to Netlify, Vercel, GitHub Pages, or any normal hosting provider.
