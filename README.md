# Sales Showdown — Oaks / Graves Exterior Sales Battle

A Jeopardy-inspired 1v1 sales-roleplay game show for Oaks Roofing & Siding + Graves Bros
Home Improvements sales meetings. Everything lives in one file.

## Run it
1. Double-click `index.html` (Chrome or Edge recommended; Safari/Firefox also work).
2. Press **F** for fullscreen and **P** for Presentation Mode once it is on the TV.
3. **Start Showdown** → confirm participants → **Begin Session** → **SPIN**.

No install, no server, no internet, no accounts. All data (roster, custom questions, standings,
coaching history, the live session) is saved automatically in the browser's localStorage under
`oaksGravesSalesShowdown_v1`. Refreshing mid-battle restores the match.

## Team Showdown (default) — under a minute to set up
1. **Start Showdown** → **Who's here today?** shows every active rep as a chip. Click names on/off
   (Select All · Clear All · Invert · Use Last Session · search · **+ Quick Add** for a walk-in).
2. Pick **2 / 3 / 4 teams** → **Randomize Teams** (or **Balance by History**). Sizes never differ by
   more than one. **Randomize Again**, 🔒 lock a player, ⇄ swap two players, or move with the menu.
   Rename a team or change its color from the card. **Use Default Teams** loads Team Manager teams;
   **Save as Default Teams** keeps today's teams for next time (otherwise they are session-only).
3. **Start Showdown**. The game bounces team to team: *GREEN TEAM — YOU'RE UP* (a wheel of only Green
   players) → *BLUE TEAM — YOU'RE UP* → VS → the normal 1v1 Best-of-3 battle. Every point a rep earns
   is mirrored to their team; team records, a compact live team scoreboard, Team Standings, a Team
   Champion (with a Team Sudden Death tiebreak) and individual awards round out the meeting.
   **Participants** (on the wheel screen) adds a late arrival or removes someone who has to leave.

**Classic Showdown** (individual 1v1 selection from the whole group) is still available from the
mode switch at the top of Session Setup.

## The 1v1 loop
SPIN → SPIN → VS → board control picks a tile → moderator reads the homeowner line →
both reps roleplay (respond-first alternates each round; use **Customer Pushback**) →
**Judge the Round** (Connect · Clarify · Create Value · Control · Close, 0–2 each) →
**Award Round** (full tile value; ties go to Sudden Death) → first to 2 rounds (Best of 3) wins →
standings update → spin again. The board persists across matches until it runs out or you
generate a new one. Two hidden **Double Down** tiles double the value.

## Moderator shortcuts
`Space` timer · `R` reset timer · `+` add 15s · `C` pushback · `W` wheel · `B` board ·
`S` standings · `T` team manager · `H` home · `U` undo · `M` mute · `P` presentation · `F` fullscreen · `?` help

## Data safety
- **Settings → Export Data** downloads a JSON backup (roster, custom questions, history, stats,
  settings, current session). **Import Data** validates before replacing anything.
- **Question Bank → Export / Import** moves custom scenarios between laptops.
- Use the same browser on the same laptop for continuity; localStorage is per-browser.
- **Factory Reset** requires typing `RESET`.

## Editing content
- Teams: **Team Manager** (create/rename/recolor/delete teams, assign or randomize the roster into default teams).
- Roster: **Roster** screen (add, edit, bulk paste, activate/deactivate, markets, companies).
- Questions: **Question Bank** (search, disable, add/edit/delete custom scenarios, preview coach keys).
- Default scenarios are recoverable at any time via **Reset Defaults**.
