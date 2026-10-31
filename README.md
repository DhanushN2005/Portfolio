# Dhanush N — Portfolio

Personal portfolio of **Dhanush N**, an AI & Data Science undergraduate and Software Developer Intern at Adya AI, working across LLMs, RAG, agentic AI, computer vision and full-stack development.

A single-page, dependency-free static site: plain HTML, CSS and JavaScript in one file, with no build step.

## Sections

- **Home** – introduction and quick links
- **About** – summary and education
- **Experience** – Software Developer Intern, Adya AI (Castlewise, RAS)
- **Skills** – languages, AI/ML, backend, data & streaming, databases, visualization
- **Projects** – TalentAI, Flexie 2.0, TNEA Pro AI, 3D Molecule Visualizer, E-Waste Deconstructor
- **GitHub** – live stats and top repositories (GitHub API)
- **Coding Profile** – LeetCode stats
- **Achievements** – animated timeline of hackathon wins and rankings
- **Certificates** and **Contact**

## Features

- Dark and light themes with a toggle (choice is remembered)
- Animated achievements timeline, scroll progress bar and staggered reveal animations
- Flip cards for projects, keyboard accessible
- Responsive layout with a mobile menu and active-section highlighting
- Respects `prefers-reduced-motion`

## Project structure

```
index.html              # the whole site (markup, styles, scripts)
Dhanush_N_Resume.pdf    # resume linked from the nav button
README.md
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

An internet connection is needed for fonts, icons and the GitHub/LeetCode stats.

## Updating content

Everything lives in `index.html`:

- Text and sections: edit the HTML under the matching `<section id="...">`
- Colors and themes: edit the CSS variables in `:root` and `[data-theme="light"]`
- GitHub stats username: `GITHUB_USERNAME` in the script
- Resume: replace `Dhanush_N_Resume.pdf`

## Contact

- Email: dhanushnataraj06@gmail.com
- LinkedIn: https://www.linkedin.com/in/dhanushnataraj/
- GitHub: https://github.com/DhanushN2005
