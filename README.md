# Mylene — Developer Portfolio

A responsive personal portfolio website built with semantic HTML5, CSS, and vanilla JavaScript. The design uses a dark navy background, cyan accents, reusable design tokens, project cards, responsive navigation, and subtle reveal animations.

## Project structure

```text
mylene-portfolio/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
└── README.md
```

## Run locally

1. Download and extract the project ZIP.
2. Open `index.html` in a browser.
3. For a smoother development workflow, open the folder in VS Code and use the Live Server extension.

No build step or package installation is required. Google Fonts need an internet connection; fallback fonts are included.

## Personalize before submission

Search the files for `Mylene`, `mylene@example.com`, and `https://github.com/`.

- Replace the name and introduction with your own details.
- Update the email address in both `index.html` and `js/script.js`.
- Replace placeholder social links with your own profiles.
- Replace the sample project descriptions and links with real work. Do not claim a sample project is fully functional unless you have built and tested it.
- Adjust the self-assessed skill bars to match your actual experience.
- Add your own profile photo or project screenshots to `images/` if desired, and include descriptive `alt` text for any content images.

## Accessibility and responsive design

- Semantic landmarks: `header`, `nav`, `main`, `section`, and `footer`.
- Logical heading hierarchy and a skip-to-content link.
- Keyboard-visible focus states and an accessible mobile navigation toggle.
- Reduced-motion preference support.
- Mobile-first layout with breakpoints at 560px, 760px, 1024px, and 420px.
- CSS Grid and Flexbox for layout.

## Contact form behavior

The contact form opens the visitor's default email app using `mailto:`. It does not send data to a server. For a production form that sends messages without opening an email app, connect a trusted form backend/service and update the form code.

## Test checklist

- [ ] Open `index.html` in Chrome and Firefox or Edge.
- [ ] Test navigation links and mobile menu.
- [ ] Test the contact form with sample values (it should open an email draft).
- [ ] Check at phone, tablet, and desktop widths.
- [ ] Confirm there is no horizontal scrolling.
- [ ] Replace all sample details and placeholder links.
- [ ] Open the deployed public URL on another device or a private/incognito window.

## Deploy using GitHub Pages

1. Create a **public** GitHub repository, for example `mylene-portfolio`.
2. Upload `index.html`, `css/`, `js/`, `images/`, and `README.md` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for GitHub Pages to publish. The URL normally looks like `https://YOUR-USERNAME.github.io/mylene-portfolio/`.
7. Open the URL in a private/incognito window and on your phone to verify it works.
8. Submit both the public website URL and the public repository URL.

## Five-minute defense outline

- **0:00–0:40 — Introduction:** Explain who the portfolio is for and what it contains.
- **0:40–1:20 — HTML structure:** Show semantic landmarks, headings, sections, and accessible labels.
- **1:20–2:00 — CSS design system:** Explain the CSS variables, palette, typography, spacing, cards, and focus styles.
- **2:00–2:40 — Responsive design:** Show the mobile navigation and explain the breakpoints and Grid/Flexbox.
- **2:40–3:30 — JavaScript:** Demonstrate the menu, active navigation, reveal animations, and email-draft form.
- **3:30–4:15 — Projects and content:** Explain what each project demonstrates; distinguish real work from concepts.
- **4:15–5:00 — Testing and deployment:** Show browser/device testing and the live URL/repository. Mention any known limitations honestly.
