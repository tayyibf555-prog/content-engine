# Content Engine

Demo dashboard for the Azen content engine, with the Reel Cortex editing studio built in.

- `index.html` is the dashboard: an overview, then the ten steps (hooks and script, framing, AI edits, brain prediction, trials and learning, go live, recut, winners as ads, track and adjust, funnel).
- `studio.html` is the Reel Cortex editing studio. Steps 3, 4, 5 and 7 link into it, and its "Content engine" button links back.
- `media/` holds the ten edited versions of the DRAW reel (video, poster and frame strip for each).

All numbers are sample data built around the real DRAW reel.

To view it locally, serve the folder and open `index.html`:

```bash
python3 -m http.server 8000
```
