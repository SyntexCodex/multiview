# MultiView

A simple static web page that plays several **different** YouTube videos side by side in a responsive grid.

## How it works

1. Open the page (hosted with GitHub Pages).
2. Paste a YouTube link into the input and press **Add video** (or Enter).
3. The video appears as a tile on the wall — click any tile to play it.
4. Your list is saved in the browser's `localStorage`, so it survives reloads.

## Notes

- Videos play through official YouTube embeds (click-to-play).
- Adding the same video twice is ignored — the wall is for watching different videos together, e.g. comparing content or monitoring several sources at once.
- No build step, no dependencies — just `index.html`.

## Run locally

Open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```
