# CloudVault

A Next.js application environment scaffolded with the App Router. The project is currently a minimal starter app, intended as a foundation for a cloud-themed web experience or future product work.

## Overview

This project contains the following:

- Next 16
- React 19
- TypeScript
- Tailwind CSS
- Biome for linting and formatting

At this stage, the app renders a simple welcome page and provides the basic project structure needed to extend it with additional pages, components, and features.

## Project Structure

```text
.
├── app/
│   ├── globals.css        # Global styling and theme variables
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Home page component
├── .gitignore
├── next-env.d.ts
├── package.json
├── postcss.config.mjs
├── tsconfig.json
├── README.md
├── package-lock.json
└── node_modules/
```

## Key Files

- `app/page.tsx`: Entry page for the application.
- `app/layout.tsx`: App shell that wraps all pages.
- `app/globals.css`: Tailwind import and CSS custom properties for branding colors.
- `package.json`: Dependency and script configuration.

## Getting Started

### Prerequisites

- Node.js 20 or newer
- npm

### Installation

```bash
npm install
```

### Run in Development Mode

```bash
npm run dev
```

Then open the app in your browser at:

```text
http://localhost:3000
```

## Available Scripts

```bash
npm run dev     # Start the Next.js development server
npm run build   # Create a production build
npm run start   # Run the production server
npm run lint    # Run Biome lint checks
npm run format  # Format code with Biome
```

## Current State

For now, this project is a starter codebase rather than a full product implementation. The homepage currently displays a basic "Welcome to CloudVault!" screen, and the app is ready for customization.

## Next Steps


- Replacing the default landing page with a custom landing page
- Adding routes and reusable components
- Connecting to an API or backend service
- Implementing authentication, storage, or billing-related flows
- Expanding the design system and styling

## Notes

- The project uses the Next.js App Router pattern.
- Tailwind CSS is configured and ready for component styling.
- The current codebase is intentionally minimal and suitable as a foundation for future development.
