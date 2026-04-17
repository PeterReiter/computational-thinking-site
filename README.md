# Computational Thinking – Course Website

Source code for the [Quarto](https://www.quarto.org)-based course website for **Computational Thinking**, taught at [FHV – Vorarlberg University of Applied Sciences](https://www.fhv.at) as part of the **Bachelor Informatics – Software Engineering** study program.

## About the Course

Computational Thinking is a foundational course that introduces students to the core problem-solving principles used in computer science and software engineering. Topics typically include:

- Decomposition and abstraction
- Pattern recognition
- Algorithm design and analysis
- Data representation
- Complexity and efficiency

## About this Repository

This repository contains the source files for the course website, built with [Quarto](https://quarto.org). The site serves as the central hub for course materials, including lecture slides, exercises, and supplementary content.

## Prerequisites

- [Quarto CLI](https://quarto.org/docs/get-started/) (latest version recommended)
- A terminal / command-line interface

## Getting Started

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd computational-thinking-site
   ```

2. **Preview the site locally**

   ```bash
   quarto preview
   ```

   The site will be served at `http://localhost:4200` (or the next available port) and automatically reloads on changes.

3. **Render the site**

   ```bash
   quarto render
   ```

   The rendered output is written to the `_site/` directory.

## Project Structure

```
computational-thinking-site/
├── _quarto.yml          # Site configuration
├── index.qmd            # Home page
├── lectures/            # Lecture materials
├── exercises/           # Exercise sheets
├── assets/              # Images, styles, and other static files
└── _site/               # Rendered output (generated, not committed)
```

## Deployment

The site can be published using any of Quarto's supported publishing targets (e.g., GitHub Pages, Quarto Pub, Netlify). Refer to the [Quarto publishing documentation](https://quarto.org/docs/publishing/) for details.

## Contributing

Contributions and corrections are welcome. Please open an issue or submit a pull request.

## License

Course materials are intended for educational use within the FHV Bachelor Informatics – Software Engineering program. Please contact the course instructor before redistributing any content.