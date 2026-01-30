# Live Text Parser (Web)

This is a single‑file webpage that parses the text exported from YouTube Studio (the `live.txt` format), lists the video titles with timestamps, and shows the total duration. It also supports filtering by year.

## Files

- `index.html` — the webpage (paste input, filter, get results)

## How to use locally

1) Open `index.html` in a browser.
2) Paste the contents of video data into the textarea.
3) (Optional) enter a year filter like `2025`.
4) Click **Parse**.

## Publish with GitHub Pages

1) Push this folder to a GitHub repo.
2) In the repo settings, enable **Pages**:
   - Source: `main` branch
   - Folder: `/ (root)`
3) GitHub will give you a public URL for the page.

## Notes

- The page runs entirely in the browser (no server).
- It ignores `Kommande` entries.
