# Square Survival

A simple browser-based survival game built with HTML5 canvas and vanilla JavaScript.

## How to Play

- You are the white square.  
- Move the mouse (or finger on touch devices) to control the square.  
- Collect white squares for +1 point. Every 10 whites reduce your size by 1.  
- Avoid black squares. Touching them makes you grow and lose 1 point. Every 10 blacks reduce your size by 1.  
- Avoid red squares. They end the game on contact.  
- Collect green circles to shrink and gain +2 points.  
- Pink "glitch" blocks vanish after spawning.  

The game ends when you hit a red block. A spill animation covers the screen, showing your final score and rules. A restart button allows you to try again without refreshing.

## Project Structure
squares-game/
├── index.html   # main HTML entry point
├── style.css    # styles for page and rule bar
├── game.js      # main game logic
└── README.md    # documentation

## Development

This game does not require any frameworks or build tools. Open `index.html` in any modern browser.

- `index.html` sets up the canvas and includes `style.css` and `game.js`.
- `style.css` contains global styles and rule bar styles.
- `game.js` contains all rendering and game logic.

## Future Plans

- Split game logic into modules (engine vs gameplay) for scalability.
- Add backend integration to store global top scores.
- Optional framework migration (Phaser or PixiJS) if more complex features are needed.

## License

MIT License