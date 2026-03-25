# Project Brief — Excalidraw

## Overview

Excalidraw is an open-source, MIT-licensed virtual whiteboard application for creating hand-drawn style diagrams, sketches, and visual designs. It is built as a React component library that can be embedded in other applications, alongside a standalone web application.

## Goals

- Provide an intuitive, browser-based drawing tool with a hand-drawn aesthetic
- Offer a reusable React component (`@excalidraw/excalidraw`) for embedding in third-party apps
- Support real-time collaborative editing between multiple users
- Enable multi-format export (PNG, SVG, JSON) and import
- Deliver a performant, accessible, and extensible drawing experience

## Project Structure

The project is organized as a **Yarn workspaces monorepo**:

```
/
├── packages/
│   ├── excalidraw/     # Core React component library (main package)
│   ├── element/        # Element data structures, types, and manipulation
│   ├── common/         # Shared utilities (colors, constants, fonts, i18n)
│   ├── math/           # Geometry and mathematical utilities
│   └── utils/          # Export/import utility functions
├── excalidraw-app/     # Standalone web application (hosted version)
├── examples/           # Integration examples for embedding
├── scripts/            # Build and automation scripts
└── public/             # Static assets
```

## Key Stakeholders

- Open-source community (contributors and users)
- Developers embedding Excalidraw in their own applications
- End users drawing diagrams collaboratively

## Success Criteria

- Smooth, responsive drawing experience across browsers
- Reliable real-time collaboration with conflict resolution
- Clean, well-typed API for third-party integrations
- Active community contributions and ecosystem growth
