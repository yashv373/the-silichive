# The Silichive

A minimalist terminal-style website for semiconductor writing, VLSI notes, research logs, project documentation, and technical archives.

**Silicon + Archive**

## Structure

```
├── index.html          # Homepage
├── about.html          # About page
├── style.css           # Terminal-inspired stylesheet
├── notes/              # The Silichive Archive (knowledge base)
│   ├── index.html
│   ├── cmos-basics.html
│   └── sram-design.html
├── research/           # Research logs
│   └── index.html
├── projects/           # Project documentation
│   └── index.html
└── papers/             # Papers worth reading
    └── index.html
```

## Adding Content

1. Create a new `.html` file in the appropriate directory
2. Copy the structure from an existing page (e.g., `notes/cmos-basics.html`)
3. Update the content, title, and breadcrumb
4. Add an entry to the section's `index.html`
5. Commit and push

## Design

- Terminal-inspired dark theme
- JetBrains Mono / IBM Plex Mono fonts
- Pure HTML/CSS, no JavaScript frameworks
- Fast loading, minimal dependencies
- Hosted on GitHub Pages

## Philosophy

> clarity > complexity  
> structure > decoration  
> writing > visual noise  
> longevity > trends
