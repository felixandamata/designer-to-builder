# Designer to Builder - Kalie Version 1.1.0

This is the working codebase for the Figma **Designer to Builder** livestream series: a beginner-friendly walkthrough of turning a Figma component into reviewable code with Figma MCP and a coding agent.

The project intentionally starts small. It uses native HTML and CSS, with no framework, JavaScript, dependencies, or build step, so every part of the implementation remains visible and understandable to designers who are new to code.

## Design source

The project uses the Accordion component from the [Designer to Builder Figma file](https://www.figma.com/design/JOGosTfupXEfUbaMeWTSKW/Figma-livestream--Designer--%3E-Builder--Community-?node-id=0-1).

The Figma file contains the component structure, open and closed states, content, variables, and light and dark examples used as the source of truth for the implementation.

## Repository structure

```text
.
├── AGENTS.md
├── README.md
├── index.html
└── src/
    ├── components/
    └── tokens/
```

| Path | Purpose |
| --- | --- |
| `index.html` | The browser preview and home for the component markup. |
| `src/components` | Styles for components created from the Figma design. |
| `src/tokens` | Design variables represented as CSS custom properties. |
| `AGENTS.md` | Working instructions for coding agents using this repository. |

The component and token directories are empty in the starting scaffold. The blank `index.html` page provides the browser entry point without introducing any design or implementation decisions in advance.

## View locally

Clone the repository and open `index.html` in a browser. No installation or build command is required.
first commit
