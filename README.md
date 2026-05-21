# Time Sink Calculator

A simple, single-page web calculator that helps you see what your daily routines really cost — in time, over weeks, months, and years.

## Project structure

```
.
├── src/
│   └── index.html   # The calculator (HTML, CSS, and JS in one file)
├── .gitignore
└── README.md
```

## Usage

The calculator is a self-contained static HTML file. To run it locally, open `src/index.html` directly in your browser:

```sh
# macOS
open src/index.html

# Linux
xdg-open src/index.html

# Windows
start src/index.html
```

Alternatively, serve the `src/` directory with any static file server, for example:

```sh
python3 -m http.server --directory src 8000
```

Then visit <http://localhost:8000>.

## Contributing

This repo is intentionally minimal. Edit `src/index.html` to change the markup, styles, or behaviour — everything lives in that single file.
