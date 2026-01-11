# Project Description
This repository hosts Seonwoo Kim's personal academic website and CV.
The goal is to present my research in robotic manipulation, AI-driven robot learning, and control for construction equipment in a clear, well-structured way.

# Content Sources
- Main source of truth for my profile: `./CV/My_CV.pdf` in the root directory.
- Sections to reflect on the website:
  - Research Interests
  - Education (MS, BS at Korea University)
  - Research Experience (KIST, Korea University)
  - Publications (Journal + Conference)
  - Teaching Experience
  - Awards
  - Technologies / Skills

# Site Structure Guidelines
- Use a clean single‑column layout suitable for academic CVs.
- Top‑level navigation:
  - Home (short bio + research interests)
  - Publications
  - Research
  - CV (downloadable PDF link)
- Do NOT introduce cute or informal wording; keep the tone professional and concise.
- Target audience: robotics/AI faculty in US PhD programs and industry research labs.

# Implementation Rules
- Keep styling simple; no heavy animations.
- Prefer Markdown content files over hard‑coded HTML.
- If using Jekyll:
  - Put profile and sections in `_pages/` or `_posts/` as appropriate.
  - Keep global settings in `_config.yml` and avoid breaking existing GitHub Pages configuration.
- Any large structural change (new theme, major navigation change) should be proposed first as a plan and only applied after I confirm.

# Tasks Claude Can Help With
- Parse `My_CV.pdf` and create structured data files:
  - `_data/publications.yml`
  - `_data/experience.yml`
  - `_data/teaching.yml`
- Generate Markdown pages:
  - `index.md` with short bio and research interests.
  - `research.md` summarizing key projects (excavator control, disturbance observer, humanoid manipulation).
  - `publications.md` listing journal and conference papers in reverse chronological order.
- Keep the wording consistent between the website and `My_CV.pdf`, but improve clarity and flow in English where needed.

# Style of Writing
- Third‑person short bio on the front page.
- Elsewhere, first‑person is acceptable but keep it formal (no slang).
- Emphasize:
  - Robotic manipulation, contact‑rich/whole‑body manipulation.
  - Combination of model‑based control and learning.
  - First‑author publications in IEEE RA‑L and IEEE TIM.

