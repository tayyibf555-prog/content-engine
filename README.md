# Content Engine

Demo dashboard for the Azen content engine, with the Reel Cortex editing studio built in.

- `index.html` is the dashboard, with two sides:
  - **Organic**: ideas (hooks, scripts, framing), upload (drag and drop clips), trials (brain prediction and trial reels), winners (go live, recut, send to ads).
  - **Ads**: dashboard, Monday report, creatives, ad library, what we're changing, funnel, build a campaign.
- `studio.html` is the Reel Cortex editor. "Edit with AI" on the upload page opens it, and its buttons link back into the dashboard.
- `media/` holds the ten edited versions of the DRAW reel (video, poster and frame strip for each).

All numbers are sample data for Tayyib and Ritesh, built around the real DRAW reel and the Business Brain free training.

To view it locally, serve the folder and open `index.html`:

```bash
python3 -m http.server 8000
```
