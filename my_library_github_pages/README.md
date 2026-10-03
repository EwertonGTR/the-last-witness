# My Library — Interactive English Reader

A multi-book library hosted for free with GitHub Pages.

## Publishing
Upload **the contents of this folder** to the repository root. Configure Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

## Add another book
1. Create `books/<book-id>/index.html` containing the new book reader.
2. Create `covers/<book-id>.svg` or `.webp`.
3. Add the book metadata to `books.json` **and** to the `catalog` array embedded in the root `index.html` (for reliable offline/local viewing).
4. Commit your changes. GitHub Pages will publish them.

The Last Witness reader retains its original interactive JavaScript and embedded illustrations. Saved vocabulary and progress use browser-local storage and are not automatically synchronized across devices.
