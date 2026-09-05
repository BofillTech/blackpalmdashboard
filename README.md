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

## Demo walkthrough — the flagship firearm scenario

Black Palm Command Center is not another security dashboard. It is a security
workflow, domain-awareness and response-orchestration platform:
SENSE → UNDERSTAND → DECIDE → ACT → DOCUMENT → IMPROVE (RADAR).

Run it end to end:

1. Press **"▸ Demo: firearm scenario"** in the sidebar. Scylla detects a visible
   firearm on NYC HQ lobby camera 4 (96%). Posture escalates GUARDED → CRITICAL.
2. **VIEW EVENT.** Black Palm assembles the situation automatically (people,
   resources, cameras, doors, SOP, comms) and Ask Black Palm delivers a situation
   brief with action buttons.
3. **Open relevant cameras → confirm.** Unverified event becomes a confirmed
   incident; BP-2026-001 opens in the Incident Command workspace.
4. **Activate SOP-7** — the procedure runs as a live playbook with automatic
   timestamps. Ask Black Palm can answer "what step are we on?"
5. **Dispatch Officer James Smith** (85 ft). Field acknowledgment, en-route and
   on-scene updates arrive from the mobile concept and land on the timeline.
6. **Lock selected doors** — review the 4 affected doors, approve, and receive
   4/4 system confirmation, logged and attributed.
7. **Notify the security team**, then **draft + approve the employee alert**
   (AlertMedia template T-12) — acknowledgments track live. Nothing high-impact
   sends autonomously.
8. A **correlated forced-door event** appears 94 seconds later — add it to the
   incident with one click.
9. Check the **Executive view**, then **Resolve** — Black Palm blocks closure
   until doors are restored and the all-clear is sent.
10. The **after-action review drafts itself**: metrics, gaps (camera 7 offline,
    ack rate), and two corrective actions that become tracked tasks on approval.
    Posture returns to GUARDED and the loop is closed.

Also try: click the posture chip ("Why are we critical?" — explainable scoring),
click any facility on the map for its security snapshot, the universal search in
the top bar, and the correlation funnel on Home (5,012 → 37 → 6 → 1).
