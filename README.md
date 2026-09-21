# RetroBrowser TV

A responsive, single-page TV archive browser for exploring curated television by era and network. It includes:

- Era filters for the 2000s and 2010s
- Date picker that switches eras and updates the on-screen year
- Curated program cards and network filter buttons
- A functional HTML5 preview player with play state and metadata
- Responsive retro editorial design

## Run locally

Open `index.html` in a browser, or serve the directory with any static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Video and licensing

Adobe Flash Player was discontinued by Adobe in 2020 and is blocked by modern browsers. It is not installed here because it is insecure and cannot provide reliable playback. The app uses the native HTML5 `<video>` element instead. Replace the sample MP4 source in `index.html` with licensed MP4/HLS streams from your own archive or broadcaster CDN. Only use content and logos you have permission to display.
