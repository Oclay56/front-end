Trading Control Template
========================

Purpose
-------
Reusable dashboard UI scaffold for trading, risk, execution, and operations products.

Stack
-----
- React 18
- TypeScript
- Vite
- Tailwind CSS
- Zustand
- TanStack Query
- TanStack Table
- Recharts

Template Areas
--------------
- `components/shell/`
  App chrome, top bar, sidebar
- `components/cards/`
  KPI and status cards
- `components/tables/`
  Reusable data tables
- `components/ui/`
  Base controls and wrappers
- `pages/`
  Route-level layouts
- `lib/hooks/`
  Data adapters to replace
- `lib/types/`
  View-model contracts to adapt

Conversion Notes
----------------
- Branding has been neutralized for reuse.
- Persisted storage keys are genericized.
- The data layer is still dashboard/runtime oriented; swap the hooks before using this in another product.
