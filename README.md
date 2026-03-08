# Trading Control Template

A reusable React + TypeScript + Vite dashboard template for trading, monitoring, and operations interfaces.

This repository is a front-end snapshot only. It keeps the layout system, shell, cards, tables, filters, and glass-panel styling, but removes the original product branding so you can adapt it to your own app.

## What This Template Includes

- multi-page dashboard shell with sidebar and top status bar
- KPI cards, section frames, tables, filters, and empty states
- a system/control page for runtime actions and configuration
- Zustand state stores for UI and filter persistence
- React Query hooks and a typed API client structure
- Tailwind CSS with reusable UI primitives

## What You Should Replace

- `lib/api/client.ts` and `lib/api/endpoints.ts`
  Connect the template to your own backend.
- `lib/hooks/*`
  Swap the current dashboard/runtime hooks for your own data adapters.
- `lib/types/*`
  Update the view models to match your domain.
- route and section copy in `pages/*`
  Rename labels and descriptions to fit your product language.

## Local Development

```bash
npm install
npm run dev
```

Build for production:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## Suggested Adaptation Path

1. Replace the API client and hooks.
2. Rename page titles and navigation to your product language.
3. Keep the shared shell and UI primitives as the design system base.
4. Remove any remaining crypto-specific wording you do not need.

## Notes

- `dist/` is intentionally ignored.
- This repo is a UI template, not a complete backend-integrated product.
- If you want demo data, add it in a separate adapter layer instead of hardcoding it into view components.
