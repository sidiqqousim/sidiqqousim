# Sidiq Muhammad Qousim: Portfolio Website

A single-page portfolio for **Sidiq Muhammad Qousim**, Computer Engineer, Web Developer and Digital Solutions Developer based in Ibadan, Nigeria.

The site presents his services, skills, live projects, experience, certification and contact details in one fast, responsive page.

## Page structure

Hero → About (and What I Do) → Skills → Featured Projects → Experience → Certification and Education → Why Work With Me → Contact

The first three projects a visitor sees are the School Management System, ToyeenCrestTech and HTML Learner, so a recruiter sees different kinds of work straight away.

## Featured projects

| Project | Type | Status | Link |
|---|---|---|---|
| School Management System | Full school management web application | Live | https://rfc-ict.web.app |
| ToyeenCrestTech | Client website (electrical engineering and smart energy) | Completed client project | https://www.toyeencresttech.com.ng |
| HTML Learner and HTML Game Platform | Interactive HTML learning website | Live | https://html-learner-app.web.app |
| IRFC-ICT Website | Business and technology services website | Live prototype | https://www.irfc-ict.com.ng |
| No-Code Web Development Tutorial | Educational web development platform | Live | https://nocode.1web.web.app |
| Mahadul-Hudal Al-Adabii | School website, UI/UX development | In progress | https://www.mahadulhudal-adabii.com.ng |

## Features

- Single self-contained HTML file with inline CSS and JavaScript (no build step, no dependencies)
- Responsive layout for desktop, tablet and mobile
- Automatic light and dark theme based on the visitor's system setting
- CSS-drawn browser mockups for each project (no image files needed)
- Sticky navigation with smooth scrolling
- One-tap email, WhatsApp and copy-email contact actions
- Accessibility basics: semantic HTML, visible keyboard focus, sufficient colour contrast and reduced-motion support

## Tech

- HTML5, CSS3 (custom properties, grid, flexbox), vanilla JavaScript
- Fonts: [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque) and [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts, with system-font fallbacks

## Getting started

1. Download `sidiq-portfolio.html`.
2. Rename it to `index.html` if you are deploying it as a website.
3. Open it in any browser to preview it locally. No server is required.

## Customising the content

Everything lives in `index.html`.

- **Colours:** edit the variables at the top of the `<style>` block (`--brand`, `--accent`, `--bg`, and so on). Dark-mode values are in the two dark blocks right below.
- **Text:** each section is marked with a comment such as `<!-- ABOUT -->` or `<!-- PROJECTS -->`.
- **Adding a project:** copy an existing `<article class="card">` block, change the URL text, title, description and link, and pick a mockup class (`m-school`, `m-toy`, `m-html`, `m-irfc`, `m-nocode`, `m-mahad`) or build a new one.
- **Contact details:** search for `irfcict@gmail.com` and `2348117613997` and update them if they change.
- **Mockup placeholder text:** the sample numbers in the School Management mockup (for example "1,240 Students") and the headline in the ToyeenCrestTech mockup are placeholders. Replace them with real details if you prefer.

## Deployment

Any static host works. Since the other projects use Firebase, here is the Firebase Hosting route:

```bash
npm install -g firebase-tools
firebase login
firebase init hosting     # choose a public folder, e.g. "public", single-page app: No
# put index.html inside the public folder
firebase deploy
```

Other options:

- **GitHub Pages:** push `index.html` to a repository, then enable Pages in the repository settings.
- **Netlify or Vercel:** drag and drop the folder, or connect the repository.
- **Custom domain:** add it in your host's dashboard (for example a `.com.ng` domain) and follow its DNS instructions.

## Browser support

Current versions of Chrome, Edge, Firefox and Safari, on desktop and mobile.

## Contact

- **Name:** Sidiq Muhammad Qousim
- **Location:** Ibadan, Nigeria
- **Email:** irfcict@gmail.com
- **Phone / WhatsApp:** +234 811 761 3997

## License

© Sidiq Muhammad Qousim. All rights reserved.
