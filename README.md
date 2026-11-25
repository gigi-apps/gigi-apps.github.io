# Gigi Apps

The website for Gigi Apps: free apps . Live at **https://gigi-apps.github.io**.

## Apps

- **[Widglass](https://github.com/gigilucas/Widglass)**: macOS-style glass widgets for the Windows desktop.
  [Download](https://github.com/gigilucas/Widglass/releases/latest/download/Widglass.exe)

## Adding an app

1. Put its icon and screenshots in `assets/<app-name>/`.
2. In `index.html`, copy the `<article class="app">` block of Widglass and change the texts, images and links.
3. Point the Download button to `https://github.com/<owner>/<repo>/releases/latest/download/<file>.exe`, so it always gets the newest version.

The site is plain HTML and CSS (no build step), served by GitHub Pages. Light and dark mode follow Windows, and the moon button switches them.
