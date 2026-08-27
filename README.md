# GLP‑1 — курс на устойчивость

GitHub Pages deployment of the GLP‑1 course workspace and participant preview.

- Public URL: https://olymarkes.github.io/sekta-glp1-course/
- Repository: https://github.com/OLYMARKES/sekta-glp1-course

- Canonical map source: `../build/2026-08-19_glp1_course_pages_map_v3.html`
- Participant preview source: `../build/2026-08-14_glp1_intro_program_flow_preview_v3.html`
- Current nutrition source: `../build/2026-08-14_glp1_nutrition_week_ksenia_v4.html`
- Published routes include `index.html`, `constructor.html`, `nutrition-week.html`, `course-entry-preview.html`, `course-preview.html`, and the public course landing `glp1-landing.html`.
- Branch: `main`
- Pages source: repository root

Build the directory reproducibly with `node ../source/scripts/2026-08-14_glp1_build_github_pages_workspace_v1.mjs` from this directory's parent project.

Build the standalone public landing and its allowlisted assets with:

```sh
node projects/glp1_course/source/scripts/2026-08-27_glp1_build_landing_preview_v4.mjs
node projects/glp1_course/source/scripts/2026-08-27_glp1_build_landing_pages_v1.mjs
```
