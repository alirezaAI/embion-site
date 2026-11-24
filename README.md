# EMBION landing page
Static HTML/CSS/JavaScript. No dependencies, build step, or API keys.

## Local preview
Open index.html in a browser, or run `python -m http.server 8000` in this directory and visit http://localhost:8000.

## Vercel
1. Unzip the project and push the contents of embion-site to a new GitHub repository.
2. In Vercel, choose Add New → Project and import that repository.
3. Select the Other framework preset, leave build command empty and use the repository root as output (or `.` if an output directory is requested).
4. Deploy. Alternatively, run `npx vercel` from the directory and follow the prompts.

## Customize
The hero SVG is a conceptual illustration, not a product photo. Replace it with an actual device photo when available. Edit index.html for copy, links and contact details, style.css for appearance, app.js for the sensor grid and synthetic visualization. The current CTA links to the author's Medium article/profile; it does not collect leads. All animation is synthetic, with a pause control and reduced-motion support. Research directions are explicitly qualified.
