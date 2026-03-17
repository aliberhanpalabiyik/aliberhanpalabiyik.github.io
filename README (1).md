# aliberhanpalabiyik.github.io

Personal academic website — Ali Berhan Palabıyık

B.Sc. Mathematics student at the University of Bonn, currently in the fourth semester. Interests: Mathematical Logic, Model Theory, and Formalized Mathematics with Lean.

🔗 **Live site:** [aliberhanpalabiyik.github.io](https://aliberhanpalabiyik.github.io)

---

## Pages

| Page | Description |
|---|---|
| `index.html` | Home — intro, current courses, tutoring overview |
| `cv.html` | Curriculum vitae — education, seminars, skills, languages |
| `notes.html` | Lecture notes, problem solutions, LaTeX projects |
| `blog.html` | Posts on mathematics, proofs, study tips, university life |
| `contact.html` | Email, LinkedIn, GitHub, tutoring inquiries |

## Current Courses (4th Semester)

- Algebra I
- Number Theory
- Topology / Geometry
- Advanced Mathematical Logic
- Complex Analysis

## Tech Stack

- Plain HTML, CSS, and vanilla JavaScript — no frameworks or build tools
- Fonts: [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) + [Source Sans 3](https://fonts.google.com/specimen/Source+Sans+3) via Google Fonts
- Hosted on GitHub Pages

## Structure

```
/
├── index.html
├── cv.html
├── notes.html
├── blog.html
├── contact.html
├── style.css
├── profile.jpg
├── cv.pdf
└── primitive-element-theorem.pdf
```

## Accessibility & SEO

- Skip-to-content link on every page
- Accessible mobile menu with `aria-expanded`, `aria-controls`, Escape key support, and focus management
- Open Graph and Twitter Card meta tags on every page
- JSON-LD `Person` structured data on the home page
- Canonical URLs on every page
- Google Fonts loaded via `<link>` (not `@import`) to avoid render blocking
- Lazy-loaded profile image with explicit dimensions to prevent layout shift
- Dynamic copyright year
