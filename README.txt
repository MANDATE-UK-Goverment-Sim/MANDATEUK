MANDATE 4 — STATECRAFT
========================

FLAT GITHUB PAGES BUILD — keep every file in the repository root.

FILES
- index.html
- control.html
- styles.css
- app.js
- mandate-logo.svg
- uk-map.svg
- site-config.json
- README.txt

START FLOW
A new player MUST begin with the 25-week general election campaign. Government screens unlock after election night and government formation.

MANDATE PRIME
The advanced PRIME page is included. Public availability is controlled by site-config.json (primePublic).

SECRET OWNER CONTROL
Owner access is deliberately NOT shown in the normal navigation.
MANDATE CONTROL is now a completely separate page: control.html
It is not linked anywhere in the public simulator navigation. Open control.html directly and enter the owner code.

OWNER CODE
M4-7VQ9-KN3X-2RPL-8CWT

IMPORTANT SECURITY LIMITATION
This is a static GitHub Pages site with no backend/SQL, exactly as requested. The code gate uses a SHA-256 hash and session-only unlock, but client-side protection can NEVER be truly secret or tamper-proof because visitors can inspect downloaded JavaScript. Do not use this mechanism to protect personal, financial, school, or otherwise sensitive data.

HOW GLOBAL CONTROL WORKS WITHOUT SQL
MANDATE CONTROL changes the current browser immediately. For site-wide announcements, release flags, PRIME availability, maintenance status, etc., use “Export site-config.json” in MANDATE CONTROL and upload/replace site-config.json in the GitHub repository root. Every visitor will then receive that configuration when the page loads.

FEATURE RELEASE STATES
HIDDEN -> COMING -> LABS -> PRIME -> LIVE -> DISABLED

VERSION
4.0 Statecraft
Released feature catalogue: 172
Staged/unreleased feature catalogue: 156


HOTFIX 4.0.1
- Fixed sidebar labels showing as undefined.
- Sidebar navigation is now text-only as intended (no navigation icons).
- Cache version bumped so GitHub Pages browsers fetch the corrected JavaScript/CSS.

HOTFIX 4.0.2
- MANDATE CONTROL moved to a separate control.html page.
- Removed the public ?control=1 route and seven-click logo shortcut.
- Owner unlock is session-only.
- Exiting Control returns to index.html.
