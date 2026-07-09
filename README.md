# Mahesh Bojja — Personal Portfolio

A single-page personal portfolio built with plain HTML, CSS, and JavaScript — no
frameworks or build step required. Showcases my background, skills, projects,
resume, and contact details.

🔗 **Live site:** https://bojjcs027-cpu.github.io

## Sections

| # | Section  | What it contains                                                   |
|---|----------|---------------------------------------------------------------------|
| 00| Header   | Name/logo, nav, tagline, hero intro                                  |
| 01| About    | Portrait, bio, quick stats                                           |
| 02| Skills   | Languages / Frameworks / Tools, with animated proficiency bars       |
| 03| Projects | Featured projects — image, description, tags, live demo & source     |
| 04| Resume   | Download panel linking to my resume PDF                              |
| 05| Contact  | Email, GitHub, LinkedIn, location                                    |
|   | Footer   | Copyright + quick links                                              |

## Featured Projects

- **Personal Portfolio Website** — this site. [Source](https://github.com/bojjcs027-cpu)
- **Responsive Landing Page** — [Source](https://github.com/bojjcs027-cpu/CODSOFT)
- **Calculator Web Application** — [Live Demo](https://codsoft-calculator-jet.vercel.app/) · [Source](https://github.com/bojjcs027-cpu/CODSOFT-Calculator)
- **Job Board Website** *(in progress)* — full-stack MERN app with JWT auth. [Source](https://github.com/bojjcs027-cpu)

## Project structure

```
mahesh-portfolio-github/
├── index.html              Main page markup
├── css/
│   └── style.css           All styling (design tokens at the top)
├── js/
│   └── script.js           Mobile menu, scroll-reveal, active-nav-on-scroll
├── assets/
│   ├── img/
│   │   ├── profile.jpg      My portrait
│   │   ├── project-1.png    Project screenshots
│   │   ├── project-2.png
│   │   ├── project-3.png
│   │   ├── project-4.png
│   │   ├── favicon.png
│   │   └── favicon.ico
│   └── resume/
│       └── resume.pdf       My resume
└── README.md
```

## How to view it locally

No build tools needed. Just open `index.html` in a browser, or serve the folder locally:

```bash
cd mahesh-portfolio-github
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Tech stack

- HTML5, CSS3 (no frameworks)
- Vanilla JavaScript (mobile menu, scroll-reveal, active-nav-on-scroll)
- Fully responsive, with a mobile hamburger menu below 720px
- Respects `prefers-reduced-motion` (disables scroll-reveal animation)
- Google Fonts for typography — no other external JS dependencies

## Contact

- Email: maheshyadavbojja9@gmail.com
- GitHub: [github.com/bojjcs027-cpu](https://github.com/bojjcs027-cpu)
- LinkedIn: [linkedin.com/in/mahesh-bojja](https://linkedin.com/in/mahesh-bojja)
live demo link 
https://codsoft-calculator-jet.vercel.app/
