Atomic Workspace Implementation Plan

1. Overview

A static web application hosted on GitHub Pages that acts as a frontend for Markdown files stored in a OneDrive-synced folder. Rebranded as Atomic Workspace.

2. Technical Architecture

Framework: React (Single File via CDN)

Styling: Tailwind CSS (Maroon & White Palette)

Icons: Lucide React

Assets: External logo.svg for branding and favicon integration.

Persistence: Browser LocalStorage (session) + Manual File Export (OneDrive Sync).

3. Data Schema (Markdown-based)

Tasks: Standard - [ ] and - [x] syntax with #priority tags.

Notes/Docs: Frontmatter-enabled markdown files.

Calendar: Event lists parsed from markdown headers or frontmatter.

4. Build Phases

[x] Phase 1: Branding & Identity (Atomic Workspace logo, Maroon/White palette)

[x] Phase 2: Task Module (CRUD operations, priority filtering)

[x] Phase 3: Notes & Docs (Editor with live preview)

[x] Phase 4: Calendar Module (Agenda view and event creation)

[ ] Phase 5: PWA Integration (Adding manifest.json for mobile "Add to Home Screen" support)

[ ] Phase 6: Automated OneDrive API (Future upgrade)