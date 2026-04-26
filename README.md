# Iron Dash 3000

Iron Dash 3000 is a lightweight, dependency-free endless runner built using Vanilla JavaScript and the HTML5 Canvas API.

## Version 2 Updates

Version 2 introduces a character-first game flow.

- Added a dedicated character selection page.
- Added six playable Avengers:
	- Iron Man
	- Captain America
	- Hulk
	- Thor
	- Black Widow
	- Hawkeye
- Connected game flow so players choose a character first, then enter gameplay.
- Saved selected character in local storage and used it in-game.
- Updated player visuals and start screen text dynamically based on selected character.
- Added a Change Character button inside gameplay screen to return to selection.

## How It Works (v2 Flow)

1. Open character selection.
2. Pick a hero.
3. Start the game.
4. Play as that selected character while avoiding Thanos and collecting Infinity Stones.

If a character is not selected, the game automatically redirects to character selection.

## Files

- character.html
	- New entry page for character selection.
- index.html
	- Main game page, now wired to the selected character.

## Run Locally

No server setup is required.

1. Download or clone the project.
2. Open character.html in any modern browser (Chrome, Firefox, Safari, Edge).
3. Select a hero and start playing.

## Gameplay

- Jump with Spacebar, ArrowUp, click, or touch.
- Avoid Thanos obstacles.
- Collect Infinity Stones to increase score.
- Speed increases as score grows.

## License

This project is open-source and available for educational and personal use.
