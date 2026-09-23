# Match the dashboard to the public Clinexus design

## Scope
- Restyle the shared clinic dashboard shell so every dashboard page inherits the public site’s polished medical-software look.
- Keep all existing pages, data, permissions, and workflows unchanged.
- Support both light and dark appearance through the same semantic color system.

## Visual changes
- Use the public site’s typography throughout the dashboard: Plus Jakarta Sans for headings and DM Sans for interface/body text.
- Replace the heavy dark gradient treatment with crisp clinical surfaces, teal accents, fine borders, restrained shadows, and compact geometry matching the public site.
- Refine the sidebar, top bar, page canvas, cards, controls, tables, dialogs, and mobile navigation as one coherent app interface.
- Preserve clear status colors and dense, scannable medical information.

## Technical details
- Scope dashboard styling under a dashboard theme class so public pages remain unchanged.
- Update shared dashboard layout, header, sidebar, and global semantic tokens/utilities rather than rewriting individual pages.
- Add a light/dark appearance control in the dashboard header and persist the selected preference locally.
- Verify the dashboard shell and representative content at desktop and mobile sizes.
