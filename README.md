# 2026 Half-PPR Draft Assistant

A single-page fantasy football draft helper for a 12-team, half-PPR league with this starting lineup:

- 1 QB
- 2 RB
- 3 WR
- 1 RB/WR FLEX
- 1 TE
- 1 K
- 1 DST

The embedded 2026 player board combines ten independent expert rankings from ten publishers. Click a player's consensus rank to inspect every contributing rank. The consensus is a trimmed mean (highest and lowest ranks removed when enough sources are available), and coverage is shown for every player.

Draft state is stored only in the browser's `localStorage`. Everyone can use the same GitHub Pages URL while keeping a separate draft board on their own device.

## Use

Open `index.html`, search for players, and mark each pick as **Taken** or **Mine**. The app updates the available-player board, top-five recommendations, your roster, and the draft log. **Undo** removes the most recent pick; **Reset** clears the local draft.

## Data date

Rankings were refreshed from public 2026 Half-PPR expert pages dated August 28–September 5, 2026. The source list and direct links are available inside the app.

