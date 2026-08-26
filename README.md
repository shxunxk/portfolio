# Shaunak — Portfolio Site

A static, dependency-free portfolio site. No build step — just open `index.html`
in a browser, or deploy the folder as-is to GitHub Pages / Netlify / Vercel.

## Files

```
portfolio/
├── index.html      all content lives here (hardcoded, no CMS/backend)
├── css/style.css    design tokens + styles
├── js/main.js       nav toggle + scroll reveal animation
└── README.md
```

## Content

The portfolio is positioned around applied AI work, including agentic systems,
LLM fine-tuning, computer vision, MLOps, IEEE research, and the pending Indian
patent application `202541123233`. Contact, GitHub, LinkedIn, project, IEEE,
and resume links are wired in `index.html`.

Before publishing, confirm the patent status against the IP India portal and
replace or add any project links that become available.

## Deploying

Any static host works since there's no backend or build step:

- **GitHub Pages**: push this folder to a repo, enable Pages on the `main`
  branch (root or `/docs`).
- **Netlify / Vercel**: drag-and-drop the folder, or connect the repo — no
  build command needed.

## Customizing

- Colors, fonts, and spacing are all CSS custom properties at the top of
  `css/style.css` under `:root`.
- The hero diagram is inline SVG in `index.html` (`#dag`) — nodes and edges
  are plain `<circle>`/`<path>` elements, easy to add to.
