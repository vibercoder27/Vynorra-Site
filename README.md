# Vynorra.org — What it is and what it does

Vynorra is a resource hub at the intersection of computer science and healthcare. It highlights AI uses in healthcare, programming guides for pre‑med students, and biotech topics. The goal is simple: help students and early trainees find clear, practical paths into tech‑enabled medicine.

## Who it serves
- Pre‑med and pre‑health students who also code
- CS students curious about healthcare
- Early researchers and builders in biotech and digital health

## What the site is for
- Show where CS meets healthcare in plain language
- Point to credible programs, courses, and communities
- Give starting points for projects and skills you can practice now
- Reduce guesswork on “what to learn next”

## Core capabilities
- **Curated topic pages**: AI in healthcare, programming paths for pre‑med, and biotech innovation themes
- **Guides**: short, skimmable explainers with links out to primary sources and reputable programs
- **Starter projects**: ideas you can ship in a weekend, listed with tools and example data
- **Checklists**: concrete steps for skills, internships, and research on‑ramps
- **Mobile‑first reading**: fast, clean pages that work on phones and low bandwidth
- **Accessible design**: readable type, keyboard‑friendly navigation, and clear contrast
- **Lightweight docs section**: longer reference pages when a single topic needs depth

## Information architecture
- **Home**: quick overview and recent additions
- **Topics**: AI in healthcare, pre‑med programming, biotech innovation
- **Guides**: practical “how to” pieces with links to trusted resources
- **Docs/Long‑form**: deep dives kept separate from quick guides

## How it was built (coding details)
- **Stack**: Vite + React + TypeScript
- **UI components**: shadcn/ui (headless components styled with Tailwind)
- **Styling**: Tailwind CSS utility classes with a small design token layer
- **State & data**: simple local state; content stored as flat pages and JSON where needed
- **Routing & layout**: client‑side routing with layout components for header, footer, sidebar
- **Performance**: route‑level code splitting, image/asset pruning, prefetch on common nav paths
- **Accessibility**: semantic HTML, consistent heading order, visible focus states, alt text on media
- **SEO basics**: per‑page title/description, clean URLs, social preview tags
- **Content model**: page templates for Topics, Guides, and Docs to keep structure consistent
- **Build output**: static assets suitable for any static host or CDN

## What I built and added
- **Frontend**: Vite + React with TypeScript and a modern component system for fast loads and smooth nav
- **UI system**: consistent design primitives (buttons, cards, nav, typography) for quick new‑page creation
- **Content model**: simple, flat pages that are easy to extend and keep consistent
- **Performance**: image and asset pruning, code‑split routes, prefetch for common nav paths
- **Accessibility pass**: heading order, focus states, alt text, and keyboard nav
- **Docs microsite**: a dedicated area for long‑form explainers so quick guides stay short
- **Quality bar**: a style guide for page length, link types, and citation rules

## How to use it (as a reader)
- Pick a topic. Read one short guide.
- Follow 1–2 links to a primary source you trust.
- Try one small project from the list.
- Repeat weekly. Keep notes.

## What “good” looks like
- Every page answers one question
- Every claim links to a source you can verify
- Every guide ends with a next step you can do this week

## Roadmap
- Basic site search across topics and guides
- Filterable project ideas by skill level and time
- Starter datasets and simple notebooks for each project
- “Programs and labs” directory with tags and quick filters
- Community contribution flow for small edits

## Contributors
Sukirtthan Elanjchezhiyan, Akarsh Dige
