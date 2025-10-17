# Hello World (Static Web App)

## Overview
A minimal static web page that displays “Hello World” using both an H1 heading and a preformatted text block, and now also shows the attached image file `hello.jpg`. Designed to be hosted on GitHub Pages with zero build steps.

- Features:
  - An H1 tag with “Hello World”
  - A pre tag with “Hello World”
  - An img tag referencing `hello.jpg` (responsive with caption)
  - Lightweight, responsive styling
  - Pure HTML/CSS/JS

## Setup
1. Create a new GitHub repository.
2. Add the following files to the repository root:
   - `index.html`
   - `README.md`
   - `hello.jpg` (the provided image attachment)
3. Commit and push the files to your default branch (e.g., `main`).
4. Enable GitHub Pages:
   - Go to Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` (root)
   - Save and wait for the published URL to appear.
5. Visit the GitHub Pages URL to see the page with the heading, preformatted text, and the image.

## Usage
- Local: Open `index.html` in your browser. Ensure `hello.jpg` is in the same directory so the image displays.
- Online: Navigate to your repository’s GitHub Pages URL (e.g., https://<username>.github.io/<repo>/).

## Improvements in Round 2
- Added display of the provided image `hello.jpg` via an `<img>` tag with a valid `src`.
- Included a semantic `<figure>` and `<figcaption>` for the image.
- Added minor visual polish and an accessibility-friendly status message that notifies if the image fails to load.

## License
MIT License

Copyright (c) 2025 The Hello World Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.