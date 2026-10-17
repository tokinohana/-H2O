# -H2O — Water Quality & Conservation

> An interactive educational website exploring water quality, water conservation, and sustainable solutions.

**PersonaEdu Web Design Competition — 3rd Place**

[**Live Demo**](https://tokinohana.github.io/-H2O/) · [**Source Code**](https://github.com/tokinohana/-H2O)

## Overview

-H2O is an educational web experience designed to make learning about water quality and conservation more engaging through interactive content, data visualization, games, and immersive visual design.

The project combines scientific information with practical water-saving solutions, encouraging users to understand water-related challenges and explore ways to address them.

Developed by **Node at 25:00** for the PersonaEdu web design competition, the project earned **third place**.

## Features

- **Educational Homepage** — Introduces water-related challenges through an illustrated, visually engaging interface.
- **Water Science** — Explores scientific concepts related to water quality and hydrology.
- **Conservation Solutions** — Presents practical approaches to water conservation, efficient water use, and rainwater collection.
- **Interactive Data Visualization** — Uses custom charts to make data easier to explore and understand.
- **Rainwater Collection 3D Model** — Embeds a 3D model of a rainwater collector concept for interactive exploration.
- **Interactive Quiz** — Reinforces learning through questions about water sustainability and environmental awareness.
- **Rainwater Catching Game** — Provides a game-based experience to make environmental learning more engaging.
- **Immersive Visual Design** — Features layered artwork inspired by Hokusai, parallax effects, scroll animations, and a blue-and-cream color palette.
- **Responsive Navigation** — Provides navigation across the website's educational pages and interactive experiences.

## Pages

| Route | Description |
|---|---|
| `/` | Homepage and introduction |
| `/science` | Water science and quality |
| `/solution` | Water conservation solutions |
| `/3d` | Interactive 3D rainwater collector model |
| `/game/quiz` | Educational quiz |
| `/game/rainwater` | Rainwater-catching game |

## Tech Stack

| Technology | Purpose |
|---|---|
| React 18 | Component-based user interface |
| Vite 5 | Development server and production build |
| Material UI | UI components, layout, and styling |
| React Router | Client-side navigation |
| Recharts | Data visualization |
| React Scroll Parallax | Parallax effects |
| AOS | Scroll-triggered animations |
| Remix Icon | Iconography |
| GitHub Pages | Static website hosting |

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) — version 20 recommended
- npm

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/tokinohana/-H2O.git
cd -H2O
npm install
```

### Development

Start the local development server:

```bash
npm run dev
```

Open the local URL displayed in your terminal.

### Production Build

Build the project for production:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

### Linting

Run ESLint to check the codebase:

```bash
npm run lint
```

## Project Structure

```text
-H2O/
├── public/                 # Images and static assets
├── src/
│   ├── assets/             # Styles, illustrations, and audio
│   ├── components/         # Reusable UI components
│   ├── pages/              # Main website pages
│   ├── App.jsx             # Shared application layout
│   └── main.jsx            # Entry point and routing
├── index.html
├── package.json
└── vite.config.js
```

## Design Philosophy

The design aims to make environmental education feel exploratory rather than purely instructional.

- **Visual storytelling:** Artwork and layered backgrounds help establish the atmosphere of the experience.
- **Interactive learning:** Quizzes, games, charts, and a 3D model provide different ways to engage with the subject.
- **Consistent visual identity:** Blue tones, cream backgrounds, and reusable components maintain a cohesive interface.
- **Progressive exploration:** Dedicated pages separate scientific explanations, practical solutions, and interactive activities.

## Competition Achievement

**3rd Place — PersonaEdu Web Design Competition**

This project brought together frontend engineering, visual design, interactive educational content, and data visualization in a single web application.

## Team

**Node at 25:00**

- [@44120N](https://github.com/44120N)
- [@Benedict02](https://github.com/Benedict02)
- [@natalius-g](https://github.com/natalius-g)

## License

No license has been specified for this repository. Contact the project contributors for permission before redistributing or reusing the source code.
