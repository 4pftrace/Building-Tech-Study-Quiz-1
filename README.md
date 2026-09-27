# Laundry Sabotage

A live browser multiplayer party game for 2–6 players.

## How to play
- One player creates a room and shares the 5-character room code.
- Other players open the same website on their own phones/computers and join with the code.
- One player is randomly assigned as the secret Saboteur.
- Laundry Crew sorts whites, darks, and colors.
- The Saboteur secretly contaminates loads.
- Crew can pull suspicious items before they reach the washer.
- Crew wins at 40 clean items. Saboteur wins at 20 ruined items.
- The round lasts 90 seconds; if time expires, the side with the higher percentage of its goal wins.

## Multiplayer
The game uses PeerJS/WebRTC for live browser-to-browser multiplayer. The host's browser is the authoritative game state, so the host must keep the game tab open during the match.

## GitHub Pages
This repository contains a GitHub Actions workflow that deploys the static game to GitHub Pages.
