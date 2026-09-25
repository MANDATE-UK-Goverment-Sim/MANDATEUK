MANDATE 5 — WESTMINSTER (Career Update)
=======================================
Version: 5.0.0

FLAT GITHUB PAGES BUILD
-----------------------
Upload every file in this ZIP directly into the root of your GitHub Pages repository.
There are no folders.

FILES
-----
index.html          Public game
control.html        Separate MANDATE CONTROL owner page
styles.css          Complete modern UI / dark mode / responsive layout
app.js              Career, diary, elections and simulation engine
mandate-logo.svg    MANDATE logo
site-config.json    Static release/status configuration
uk-map.svg          Local map asset / fallback
README.txt          This file

MANDATE CONTROL
---------------
Open control.html directly.
Owner code: M4-7VQ9-KN3X-2RPL-8CWT

IMPORTANT: This is a static GitHub Pages project. Browser-only code protection is not secure server authentication. Do not put real secrets, personal data, credentials, or sensitive information in the control room.

MAJOR 5.0 FEATURES
------------------
- Completely redesigned text-only navigation and responsive UI
- PM Career Mode
- MP Career Mode
- Chancellor Career Mode
- Electioneer Mode
- Voter Career with party switching / policy reactions
- News Reporter Career
- Political-career transitions across one save
- Winston Churchill through Keir Starmer PM scenario selector
- Era-sensitive press / letters / broadcast feedback
- Monarch audience diary events
- Mandatory weekly diary: required tasks must be completed before week advance
- Opposition career after losing a general election
- Leadership resignation and leadership-election continuation
- 50/50 player leadership contest outcome with option to remain MP or follow the new leader
- Four-week PM-career general election campaign
- 25-week Electioneer campaign retained
- Live election night with 650 simulated constituency declarations
- Exit poll / seat totals / live result feed
- Government / Parliament / MPs / legislation / economy / public opinion / media / elections / world / history
- House of Lords legislation stage
- Bills through First Reading to Royal Assent
- Random resignations, defections, scandals, rebellions, strikes, by-elections, crises and polling shocks
- Pressure-on-leader mechanics
- Premiership / career archive
- Premiership sharing summary
- Daily political-report archive
- Restart / New Game
- Save export
- Light and dark theme
- Separate control.html owner console
- Better UK map with 650 clickable simulated constituency points and multiple display modes
- Optional CURRENT COMMONS ROSTER SYNC from the official UK Parliament Members API

REAL PARLIAMENT DATA
--------------------
The People page can attempt to load the current House of Commons roster directly from the official UK Parliament Members API:
https://members-api.parliament.uk/

The game keeps simulation traits (loyalty, influence, popularity, pressure, etc.) separate from real-world facts. Those values are fictional gameplay variables and are not factual claims about real people.

UK Parliament states that the UK has 650 parliamentary constituencies, each represented by one MP.
Official public data is available through Parliament's developer APIs.

ELECTION TIMING
---------------
PM Career uses a simplified four-week campaign for gameplay. The real UK Parliamentary general-election timetable has a statutory minimum of 25 working days; the game rounds this into a four-week career sequence.

HISTORICAL / CONTEMPORARY SCENARIOS
-----------------------------------
Historical PM names are scenario starting points. After a scenario begins, game events and decisions are simulated and should not be treated as claims about the real officeholder.

SAVE MIGRATION
--------------
MANDATE 5 intentionally uses a new local save key (mandate-v5) because the career engine is structurally different from MANDATE 4. MANDATE 4 saves remain in the browser but are not automatically imported.
