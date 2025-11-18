# OmniMyth Static Website

Static website for OmniMyth, an indie tabletop RPG publishing company. Built with Astro.

## Description

This is a static website showcasing tabletop RPG content, projects, products, and free resources. The site features a tab-based navigation system and uses Astro's content collections for managing markdown-based content.

## Prerequisites

- Node.js (version 18 or higher recommended)
- npm or your preferred package manager

## Installation

```bash
npm install
```

## Development

Start the development server:

```bash
npm run dev
```

The site will be available at `http://localhost:4321`

## Build

Build the static site for production:

```bash
npm run build
```

The built site will be generated in the `dist/` directory.

## Preview

Preview the production build locally:

```bash
npm run preview
```

## Project Structure

- `/src/pages/` - Page routes
- `/src/components/` - Reusable Astro components
- `/src/layouts/` - Layout templates
- `/src/content/` - Content collections (markdown files)
- `/public/` - Static assets

## Technology Stack

- Astro 4.0
- TypeScript
- Static site generation
