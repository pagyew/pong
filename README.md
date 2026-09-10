<div align="center">
  <h1>Pong</h1>
  <p><strong>One paddle, one ball, one more rally.</strong></p>
  <p>
    <img src="https://img.shields.io/badge/JavaScript-vanilla-f7df1e?style=flat-square" alt="JavaScript: vanilla" />
    <img src="https://img.shields.io/badge/rendering-Canvas%202D-0f766e?style=flat-square" alt="rendering: Canvas 2D" />
  </p>
  <p><a href="#play-locally">Play locally</a> · <a href="#controls">Controls</a> · <a href="#code-guide">Code</a></p>
</div>

---

> [!NOTE]
> This repository is archived. The code is preserved as a reference and learning project.

A small browser game written in plain JavaScript and rendered on an HTML canvas. No package installation or build step is required.

## Play locally

```sh
git clone https://github.com/pagyew/pong.git
cd pong

```

Open `index.html` in your browser.

## Controls

| Input                         | Action                          |
| ----------------------------- | ------------------------------- |
| Move the mouse over the court | Move your paddle                |
| Click the court               | Serve, or restart after a point |

## Features

- Play against a computer-controlled paddle.
- Keep score with a pixel-style scoreboard.
- Ball speed increases after paddle collisions.

## Code guide

| File                     | Purpose                                  |
| ------------------------ | ---------------------------------------- |
| [index.html](index.html) | Page and canvas                          |
| [main.js](main.js)       | Game loop, input, rendering, and scoring |
| [main.css](main.css)     | Page styles                              |

<!-- Сообщение сформировано агентом -->
