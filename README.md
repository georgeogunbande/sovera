# Sovera Global

Website for Sovera Global, a premium business hub in Edmonton, Alberta: offices, coworking, meeting rooms, memberships and a professional network. Rebuilt from the Figma Make file and extended with LinkedIn-style elements.

Vite + React 18 + TypeScript + Tailwind CSS v4 + React Router 7.

## Run

```bash
npm install
npm run dev      # http://localhost:5173
npm run build    # typecheck + production build into dist/
npm run preview
```

## Routes

| Path | Page |
| --- | --- |
| `/` | Home, including the LinkedIn company-page block |
| `/memberships` | Plans, partnership programs |
| `/services` | Offices, coworking, virtual office, meeting rooms |
| `/contact` | Contact form and FAQ |
| `/get-started` | 7-step membership flow |
| `/dashboard` | MySovera member dashboard (sample data) |
| `/linkedin` | Paid-traffic landing page with lead form; keeps `utm_*` and `li_fat_id` |

## Before launch

- Forms (`/contact`, `/linkedin`) and checkout only log to the console. Connect them to a CRM, webhook or payment provider.
- Set the real company page URL in `src/data.ts` (`LINKEDIN_URL`).
- LinkedIn feed posts, member counts and testimonials are sample content.
- Photos load from Unsplash; swap in your own assets.
