# Bingo

**Bingo** is an interactive browser-based Bingo game where the board contains IT-related terms, programming languages, and technology concepts. Players mark fields and try to complete five in a row. The project also includes a quiz and random tech quotes.

---

## Features

- **Random Bingo board**: 25 cells with programming languages, IT terms, and tech concepts.
- **Marking cells**: Click a cell to select or deselect it.
- **Win detection**: The game detects when the player completes 5 in a row (horizontal, vertical, diagonal) and triggers a confetti animation and a congratulatory message.
- **Dark/Light mode**: Switch the theme of the page with a button.
- **Random tech quotes**: Displays random programming and technology-related quotes.
- **Informatics quiz**: Modal window with random questions and answer checking.
- **Game state saving**: The board and selections are stored in `localStorage`, allowing continuation after page refresh.

---

## Technologies

The project uses standard web technologies:

- HTML5
- CSS3
- JavaScript (ES6+)
- [Canvas-confetti](https://www.npmjs.com/package/canvas-confetti) for visual effects

No backend or additional setup is required — it runs directly in the browser.

---

## Installation & Usage

1. Clone the repository:
```bash
   git clone https://github.com/misiakfilip/bingo.git
```

2. Open `index.html` in your browser.
3. Click the cells to mark them. Complete 5 in a row to win!
4. Use the buttons to:

   * Toggle the theme
   * Start a new board
   * Randomize quotes
   * Play the quiz

---

## File Structure

```
Informatics-Bingo/
│
├─ index.html           # Main HTML file
├─ README.md            # This file
└─ win.mp3              # Sound played when you complete bingo 
```

---

## Notes

* The project is responsive and works on both desktop and mobile devices.
* You can expand the Bingo phrases or quiz questions by editing the `phrases` and `pytania` arrays in `index.html`.
* The confetti animation can be customized in the `launchConfetti()` function in JavaScript.

---

## License

This project is released under the MIT License.
You are free to use, modify, and distribute it.

---

## Demo

You can optionally host the project with GitHub Pages:

```
https://misiakfilip.github.io/bingo/
```
