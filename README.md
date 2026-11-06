# Madden

Franchise Hub: an ESPN-style stats site for my Madden franchise. One file (`index.html`), no build step, no dependencies.

Pages: scores, weekly matchups, standings, schedules, teams, players, league leaders, trades, injuries, retired players and awards.

## Run it

Open `index.html` in a browser, or serve the folder (GitHub Pages works). It starts with a made-up sample league.

## Connect a franchise

Open the **Connect** tab and load a league JSON file. The tab shows the expected format. Only `teams` and `games` are required. Exporter files (Snallabot, MyMadden and similar) need a small adapter to turn them into that format.

Team logos and player pictures are your own image files, uploaded on the Connect tab and kept in the browser only. Name logos after the team abbreviation (`BUF.png`) and pictures after the player (`Caleb Gaines.png`) or player id (`20.png`).
