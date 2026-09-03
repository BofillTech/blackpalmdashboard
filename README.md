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
3. Explore the other screens: Intelligence, Common Operating Picture, Incidents,
   Video, Communications, Knowledge Library, Cyber (reserved module), Reports,
   and Administration (users, roles, groups and a live audit trail).
4. Note the decision layer on Home: enterprise posture with the "why" behind it,
   plus Recommended Attention items with one-click actions.
5. Try it on a phone — the layout is fully responsive.

## Notes

- Scylla and AlertMedia data is mocked, but structured on the Black Palm common
  data model (Event / Incident / Communication / Intelligence Item) so real
  connectors slot in without a rebuild.
- The Ask Black Palm chat calls a live AI model when opened inside Claude;
  standalone it falls back to scripted demo answers.
- Single self-contained HTML file — no build step, no dependencies.

Feedback welcome — open an issue or comment directly.
