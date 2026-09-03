# Black Palm Command Center — Demo Concept

Interactive prototype of the Black Palm Command Center: a unified security operating
layer integrating video intelligence (Scylla), emergency communications (AlertMedia),
incidents, intelligence and AI-assisted decision support.

## How to review

Open `index.html` in any browser (or via GitHub Pages if enabled).

1. Click **"Demo: firearm detection"** at the bottom of the left sidebar.
2. Watch the full loop: Scylla detection → posture change → Ask Black Palm
   correlates and recommends → create incident → draft AlertMedia notification →
   live acknowledgment tracking → after-action draft.
3. Explore the other screens: Intelligence, Operating Picture, Incidents, Video,
   Communications, Cyber (reserved module), Reports.

## Notes

- Scylla and AlertMedia data is mocked, but structured on the Black Palm common
  data model (Event / Incident / Communication / Intelligence Item) so real
  connectors slot in without a rebuild.
- The Ask Black Palm chat calls a live AI model when opened inside Claude;
  standalone it falls back to scripted demo answers.
- Single self-contained HTML file — no build step, no dependencies.

Feedback welcome — open an issue or comment directly.
