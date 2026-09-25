MANDATE — Government & Election Simulator v3.1 HOTFIX
===========================================

UPLOAD TO GITHUB PAGES
1. Extract this ZIP.
2. Upload every file directly to the ROOT of your repository.
3. Do not create folders.
4. Ensure index.html is in the repository root.
5. Commit and wait for GitHub Pages to redeploy.

FILES
- index.html
- styles.css
- app.js
- mandate-logo.svg
- uk-map.svg

FIRST-LAUNCH FLOW
The simulation now starts with a mandatory General Election campaign. The player creates a leader/party and begins 25 weeks before polling day. Government-only navigation stays locked until the election is completed and a government is formed.

MAJOR SYSTEMS
- 25-week campaign with weekly decisions and milestone events
- election night with exit poll, live declarations, speed controls, key seats and Finish Election
- majority / hung parliament / coalition / minority government formation
- interactive multi-mode UK political map (game schematic)
- 650 generated constituency records and 650 generated MPs after election
- MP loyalty, popularity, influence, ideology, role, resignations and defections
- cabinet appointments, reshuffles, resignations, scandals and loyalty
- random autonomous events and crises
- government stability, political capital, party unity, trust and approval
- bills, readings, amendments, rebellions and Royal Assent progression
- economy and budget controls
- public opinion, national/regional polling and issue tracking
- media interviews, press conferences, leaks and investigations
- PMQs, confidence votes, leadership pressure and leadership challenges
- world / diplomatic incidents and security alerts
- constitutional options and referendums
- premiership/election archive with headline statistics
- full working light and dark modes
- browser-local save state using localStorage

NOTES
- The UK map is intentionally a game schematic, not an official boundary dataset.
- All politicians and most place names are fictional/generated for gameplay.
- No server is required; it is a static GitHub Pages application.


V3.1 HOTFIX
- Fixed campaign launch crash caused by the UK map trying to read government polling before a government existed.
- Existing v3.0 browser saves are migrated automatically.
- Added cache-busting query strings so GitHub Pages browsers fetch the corrected JS/CSS.
