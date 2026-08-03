# jomy-t-j.github.io

Personal portfolio site for **Jomy T J** — Cambridge Global Perspectives &amp; Research specialist, CAIE Approved Examiner, and sustainability/peace educator.

**Live site:** [jomy-t-j.github.io](https://jomy-t-j.github.io)

## About

A multi-page static site documenting an 8+ year teaching and academic-leadership career: Cambridge Global Perspectives &amp; Research (IGCSE, AS &amp; A Level), Biology, sustainability education, monitoring &amp; evaluation, and international peace education.

Built as a plain HTML/CSS site — no build step, no framework, no dependencies beyond two Google Fonts. Designed to be readable, fast, and easy for anyone (including non-developers) to edit directly on GitHub.

## Structure

```
.
├── index.html            Home — summary, impact stats, quick links
├── experience.html        Full career timeline
├── skills.html             Core competencies by domain
├── education.html          Degree + ongoing professional development
├── certifications.html    Verified credentials
├── achievements.html      Measurable outcomes (exam results, programme reach)
├── writing.html            Publications & thought-leadership essays
├── resources.html          Free Cambridge GP study guides + custom packs
├── contact.html            Contact details & availability
├── css/
│   └── style.css           Shared design system (all pages import this)
└── jomy_profile.jpg        Profile photo
```

## Design system

Shares its visual language — dark ink background, parchment/brass/sage/ember accents, Fraunces + Inter + IBM Plex Mono typography, and the compass/route motif — with the classroom teaching resources built for the same author, so the professional site and the teaching material feel like one consistent body of work.

Colour tokens and component patterns (`.card`, `.tl-row`, `.panel-head`, `.route`) are defined once in `css/style.css` and reused across every page.

## Local preview

No build tooling required — clone and open `index.html` directly in a browser, or serve locally:

```bash
git clone https://github.com/Jomy-T-J/jomy-t-j.github.io.git
cd jomy-t-j.github.io
python3 -m http.server 8000
# visit http://localhost:8000
```

## Deployment

Served automatically via **GitHub Pages** from the `main` branch — any push to `main` updates the live site within a few minutes.

## Related

- [Rolling Through the Odds](https://github.com/Jomy-T-J/Rolling-through-the-odds) — a 6-module, SDG-aligned sustainability curriculum, referenced from the [Resources](resources.html) page.

## Contact

- [LinkedIn](https://www.linkedin.com/in/jomy-t-j-bb360168/)
- [WhatsApp](https://wa.me/919629427522)
- starjomy@gmail.com

## License &amp; attribution

Content is shared for professional and educational purposes. Cambridge® is a registered trademark of Cambridge Assessment International Education; materials here are independent educator resources, not official Cambridge publications.

