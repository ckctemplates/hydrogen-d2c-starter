# Contributing to Hydrogen D2C Starter

PRs and issues welcome. This is a starter, not a framework — small focused changes are best.

## Scope of changes I'll merge
- **Bug fixes** — any regression vs. a clean `pnpm install && pnpm dev` from a fresh clone
- **Hydrogen / React Router upgrades** — keeping the starter aligned with the latest stable Hydrogen
- **Generic UX polish** — better empty states, accessibility fixes, broken-link gracefulness
- **Better placeholder copy** — the post-scrub copy is workable but not great; better generic copy lands quickly

## Scope of changes I'll close
- **Vertical-specific copy or product** — this starter is intentionally vertical-agnostic. If you want a pet / supplement / fashion starter, fork and rebrand
- **Heavy framework swaps** — Hydrogen + RR7 is the bet. PRs replacing the data layer or routing aren't a good fit here

## Dev loop
```bash
pnpm install
pnpm dev
pnpm typecheck
pnpm lint
```

## Style
- TypeScript strict, no `any` without a comment justifying it
- Tailwind for new components, scoped CSS in `app/styles/app.css` for global utilities
- One concern per PR — easier to review and ship
