# Nitya Mungalpara, portfolio

My personal portfolio site: https://nitya-mungalpara.netlify.app

Final-year Computer Science (Professional) student at RMIT. The site covers my industry client project, team and
coursework projects (full-stack, cloud, machine learning), experience and skills.

## How it's built

A static site with no framework and no build step:

- `index.html`: the whole page. HTML for content, CSS in the `<style>` block, plain JavaScript in the `<script>` block
- `assets/`: photos, project screenshots, the Campus Hub demo video and my CV (PDF)

The JavaScript handles the screenshot slideshows, the demo video popup, building the project and course lists from
arrays, and fading sections in as you scroll (IntersectionObserver). It is hosted on Netlify and redeploys on every
push to `main`.

## History

1. First version with a dark theme
2. Redesigned as an editorial layout with project case studies and slideshows, because the first version looked too
   generic
3. New colour scheme, a Cloud Operations slideshow, updated results and CV
