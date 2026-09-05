# Hikari

```text
██╗  ██╗██╗██╗  ██╗ █████╗ ██████╗ ██╗
██║  ██║██║██║ ██╔╝██╔══██╗██╔══██╗██║
███████║██║█████╔╝ ███████║██████╔╝██║
██╔══██║██║██╔═██╗ ██╔══██║██╔══██╗██║
██║  ██║██║██║  ██╗██║  ██║██║  ██║██║
╚═╝  ╚═╝╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝
```

Hikari a lightweight Japanese study dashboard for building N5 foundations one clear step at a time.

## Features

- Guided learning path with lessons and progress cards
- Vocabulary dictionary with live search
- Hiragana and katakana charts with recall quizzes
- N5 references for kanji, grammar, numbers, time, dates, question words, and more
- Responsive layout for desktop and mobile

## Run locally

No build step or dependencies are required. From this directory, start a local server:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

You can also open `index.html` directly, though a local server is recommended for consistent browser behavior.

## Project files

- `index.html` - application markup and lesson content
- `style.css` - layout, responsive styles, and visual design
- `app.js` - navigation, dictionary search, kana charts, and quiz interactions
