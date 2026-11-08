# Dial-Up Studios

Website for Dial-Up Studios, makers of Out of Office. Served by GitHub Pages at https://bushbrother.github.io/dialupstudios/

- `privacy.html`: privacy policy for Out of Office
- `help.html`: the Out of Office staff handbook (how to play), opened from Settings → Help in the game
- `content/game_content.json`: the game's live content (events, prices, text). The app checks it on launch and uses it when its contentVersion is newer. Publish with `tools/publish_content.py` in the game repo.
- `img/`: pictures for the pages, rendered from the game's own pixel art
