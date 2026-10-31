# Kirklin Poss - Personal Portfolio

Three linked pages styled with a shared CSS file, using the palette in `wireframe.svg`.

## Design

- Colors: #F8FAFC background, #FFFFFF surfaces, #172033 text, #1D4ED8 accent.
- Google Fonts: Lora headings and Inter body/navigation; system fallbacks when offline.
- Spacing variables follow an 8px scale: 8, 16, 24, 32, 48, and 64px.
- Selector examples: `body` (type), `.project-grid` (class), `#main-content` (ID).
- Grid and Flexbox handle page layouts, project cards, and navigation.
- Breakpoints: 640px and 1024px; reduced-motion preference also supported.
- SQL inventory is a planned project, not completed experience.
- Contact details remain private until the owner chooses what to publish.

## Publish with GitHub Pages

Upload these files to the repository root. Under Settings > Pages, choose
Deploy from a branch, select main and / (root), then Save. After deployment,
the expected URL is https://reptileboy.github.io/Personal-Portfolio/.
The URL is only live after GitHub Pages is enabled and the deployment succeeds.

## Required browser checks

Open each of index.html, projects.html, and about.html in DevTools device mode.
At 320px: stacked navigation, cards, and content.
At 768px: horizontal wrapping navigation, two project columns, two home columns.
At 1200px: header in one row, two project columns, biography beside contact.

At each size, check navigation and keyboard focus, and confirm there is no
horizontal scrolling, clipped text, or overlapping content. Allow Google Fonts
to load; also check that the fallback fonts remain readable when offline.
Browser verification was not completed in the preparation environment because
the browser download failed. Complete these checks before submission.
