# Bake Off Fantasy League

A fantasy-football-style scoreboard for The Great British Bake Off, built so my wife and I could score each episode as we watch.

**Live app:** https://ohmchristopherj-del.github.io/bake-off-fantasy/
Visitors see the league in demo mode: every control works, but nothing is saved.

## How it works
- Each player drafts bakers onto their team. Bakers earn points for their team throughout the season.
- Each episode, players guess outcomes like Star Baker, the Technical winner, and who goes home. Correct guesses earn points for whoever made them, no matter whose baker it was.
- Episode 1 is preseason for scouting bakers before the draft. Scoring starts in episode 2.
- Handles show quirks like double-elimination weeks.
- Scores export to a spreadsheet, and the full league can be downloaded as a backup.

## Built with
- HTML, CSS, and JavaScript in a single file
- Firebase for Google sign-in and real-time syncing between devices
- GitHub Pages for hosting
