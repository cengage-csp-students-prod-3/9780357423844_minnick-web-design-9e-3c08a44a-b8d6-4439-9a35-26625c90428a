# Copilot Instructions for Wildlife Rescue Center Web Project

## Project Overview
This project is a simple static website for a Wildlife Rescue Center. It consists of HTML files with embedded CSS, designed for educational purposes. The main file is `rescue/index.html`, which serves as the homepage and primary content source. There is also a `template.html` file intended for student experimentation or extension.

## Key Files & Structure
- `rescue/index.html`: Main site, includes all content and styles inline. Use this as the reference for site structure, navigation, and design patterns.
- `rescue/template.html`: Blank template for new pages or exercises. Follow the conventions in `index.html` when adding content.
- `.vscode/settings.json`: Editor config for file exclusions; no build or test automation is present.

## Patterns & Conventions
- **Single-page design**: All navigation is handled via anchor links (`<a href="#section">`) pointing to sections within the same page.
- **Inline CSS**: All styles are written in a `<style>` block in the `<head>`. No external CSS or JS is used.
- **Semantic HTML**: Use `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` for layout. Follow the structure in `index.html` for new content.
- **Accessibility**: Use descriptive link text and section headings. Maintain proper HTML5 semantics.
- **No build/test workflow**: This is a static site; changes are made directly to HTML files. No npm, build tools, or automated tests are present.

## Developer Workflow
- Edit HTML files directly in the `rescue/` folder.
- Preview changes in a browser; no local server or build step is required.
- For new pages, copy the structure from `index.html` and use semantic tags.
- Keep all styles inline unless otherwise instructed.

## Examples
- To add a new section, follow the pattern:
  ```html
  <section id="new-section">
    <h2>Section Title</h2>
    <p>Section content...</p>
  </section>
  ```
- To add navigation:
  ```html
  <nav>
    <a href="#about">About Us</a>
    <a href="#new-section">New Section</a>
  </nav>
  ```

## External Dependencies
- None. Do not add external libraries or scripts unless explicitly required.

## Integration Points
- N/A. This project does not integrate with APIs, databases, or other services.

---

If any conventions or workflows are unclear, please request clarification or provide examples from the codebase for further documentation.
