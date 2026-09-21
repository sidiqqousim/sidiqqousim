# Sidiq Muhammad Qousim: Portfolio Website

A single-page portfolio for **Sidiq Muhammad Qousim**: Computer Engineer, Web Developer, ICT Consultant and Arabic Tutor, based in Ibadan, Oyo State, Nigeria. Sidiq is the founder and CEO of IRFC-ICT (established 2016) and has over five years of IT teaching experience.

The site presents his services, skills, live projects, experience, certification and contact details in one fast, responsive page.

## Page structure

Hero → Key facts → About (and What I Do) → Skills → Featured Projects → Experience → Education, Certification and Languages → Why Work With Me → Contact

The first three projects a visitor sees are the School Management System, ToyeenCrestTech and HTML Learner, so a recruiter sees different kinds of work straight away.

## Featured projects

| Project | Type | Status | Link |
|---|---|---|---|
| School Management System | Full school management web application | Live | https://irfc-ict.web.app |
| ToyeenCrestTech | Client website (electrical engineering and smart energy) | Completed client project | https://www.toyeencresttech.com.ng |
| HTML Learner and HTML Game Platform | Interactive HTML learning website | Live | https://html-learner-app.web.app |
| IRFC-ICT Website | Business and technology services website | Live prototype | https://www.irfc-ict.com.ng |
| No-Code Web Development Tutorial | Educational web development platform | Live | https://nocode-1web.web.app |
| Mahadul-Hudal Al-Adabii | School website, UI/UX development | In progress | https://www.mahadulhudal-adabii.com.ng |

## Features

- Single self-contained HTML file with inline CSS and JavaScript (no build step, no dependencies)
- Responsive layout for desktop, tablet and mobile
- Automatic light and dark theme based on the visitor's system setting
- Real screenshots for the School Management System, HTML Learner and No-Code Tutorial, shown in browser frames with a click-to-enlarge preview
- CSS-drawn browser mockups for the projects that do not have screenshots yet (ToyeenCrestTech, IRFC-ICT, Mahadul-Hudal Al-Adabii)
- Dropdown menu with a colour and icon for each section
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
- **Adding a project:** copy an existing `<article class="card">` block, change the URL text, title, description and link, then either use a screenshot (see below) or one of the CSS mockups (`m-toy`, `m-irfc`, `m-mahad`).
- **Replacing a screenshot or adding one for a mockup project:** screenshots are embedded directly in the HTML as base64 data (the hosting blocks external image links). Resize the image to about 960px wide, convert it to a base64 JPEG data URI, and use it as the `src` of an `<img>` inside a `<button class="shot">`, as in the School Management System card. Give each image a unique `id` if you want it to appear in the hero stack.
- **Contact details:** search for `irfcict@gmail.com`, `08117613997`, `07069178114` and `2348117613997` (the WhatsApp link) and update them if they change.
- **Experience and education:** each role is a `<div class="role">` block and each credential is a `<div class="cred">` block. Copy one to add another.
- **Mockup placeholder text:** the headline in the ToyeenCrestTech mockup is placeholder text. Replace it with a real screenshot when you have one.

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

- **GitHub Pages:** push `index.html` to a repository, then enable Pages in the repository settings. The existing portfolio address, `sidiqqousim.github.io/my-portfolio`, can be updated this way by replacing its `index.html`.
- **Netlify or Vercel:** drag and drop the folder, or connect the repository.
- **Custom domain:** add it in your host's dashboard (for example a `.com.ng` domain) and follow its DNS instructions.

## Browser support

Current versions of Chrome, Edge, Firefox and Safari, on desktop and mobile.

## Contact

- **Name:** Sidiq Muhammad Qousim
- **Location:** Ibadan, Oyo State, Nigeria
- **Email:** irfcict@gmail.com
- **Phone / WhatsApp:** 08117613997 / 07069178114
- **Website:** www.irfc-ict.com.ng

## License

© Sidiq Muhammad Qousim. All rights reserved.3. Open it in any browser to preview it locally. No server is required.

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
