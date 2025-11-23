# Copilot Instructions for 2smr-web

## Project Overview
This repository contains HTML and CSS exercises for web development learning, organized by activity and topic. The structure is designed for educational use, with each folder representing a distinct exercise or concept.

## Directory Structure
- `index.html`, `index2.html`, `inicio.html`: Entry points or general pages.
- `actividad1/`, `actividadesCSS/`: Main folders for exercises.
  - Each subfolder (e.g., `actividad4-flex/`, `actividad3-selectores y cajas/`) contains:
    - An HTML file for the exercise
    - A `css/` folder for styles
    - An `img/` folder for images

## Key Patterns
- **Separation of Concerns**: HTML files reference CSS via relative paths (e.g., `css/estilos.css`).
- **Naming Conventions**: Folder and file names reflect the exercise topic and order (e.g., `actividad4-flex`, `Ej2Texto.html`).
- **No Build System**: Files are static; no build, test, or package management tools are present.
- **Direct Editing**: Changes are made directly to HTML/CSS files. No transpilation or bundling.

## Developer Workflow
- Open HTML files in a browser to view results.
- Edit corresponding CSS in the `css/` subfolder for each activity.
- Use images from the local `img/` folders as needed.
- No automated tests or scripts; manual verification only.

## Integration Points
- No external dependencies or frameworks detected.
- All resources are local; no API calls or backend integration.

## Examples
- To update styles for the flexbox exercise, edit `actividadesCSS/actividad4-flex/css/estilos.css` and view changes in `actividadesCSS/actividad4-flex/index.html`.
- For selector exercises, modify `actividadesCSS/actividad3-selectores y cajas/css/estilos.css` and open `festival.html`.

## Recommendations for AI Agents
- Maintain the existing folder and naming conventions.
- Ensure relative paths are correct when linking CSS and images.
- Avoid introducing build tools or frameworks unless explicitly requested.
- Document any new patterns or conventions in this file.

---
If any section is unclear or missing, please provide feedback to improve these instructions.
