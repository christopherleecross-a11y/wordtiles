# WordTiles

A crossword tile game that runs in the browser. Play against the computer (Easy, Medium, Hard) or pass-and-play with up to 4 people.

## Files
- `index.html` – the whole game (HTML, CSS, JavaScript)
- `words.txt` – the dictionary (ENABLE word list, public domain)

## Put it on GitHub Pages
1. Create a new repository and upload `index.html` and `words.txt` to the root.
2. Go to **Settings → Pages**, set the source to the `main` branch, root folder, and save.
3. After a minute, the game is live at `https://<your-username>.github.io/<repo-name>/`.

Note: opening `index.html` directly from your computer blocks the dictionary from loading. Use GitHub Pages, or run `python3 -m http.server` in the folder and visit http://localhost:8000.
