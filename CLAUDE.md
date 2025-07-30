# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Development Commands

- `npm run dev` - Start development server
- `npm run build` - Build for production  
- `npm run preview` - Preview production build locally

## Architecture Overview

This is an Astro project with Tailwind CSS integration. The codebase follows Astro's file-based routing and component structure:

### Key Technologies
- **Astro 5.12.6** - Static site generator with island architecture
- **Tailwind CSS 4.1.3** - Utility-first CSS framework (configured via Vite plugin)
- **Canvas Confetti** - Interactive effects library

### Project Structure
- `src/pages/` - File-based routing (index.astro is homepage, markdown-page.md for markdown content)
- `src/components/` - Reusable Astro components (e.g., Button.astro with client-side interactivity)  
- `src/layouts/` - Page layout templates (main.astro for basic HTML structure)
- `src/styles/` - Global CSS imports (global.css imports Tailwind)

### Configuration
- Astro config uses Vite plugin for Tailwind integration (`astro.config.mjs`)
- TypeScript configured with Astro's strict preset (`tsconfig.json`)
- Tailwind imported via CSS (`@import "tailwindcss"` in global.css)

### Component Patterns
- Astro components use frontmatter for imports and logic
- Client-side JavaScript uses `<script>` tags in components
- Tailwind classes applied directly in templates
- Slot-based content projection for reusable components