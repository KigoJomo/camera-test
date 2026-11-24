# Camera Test

**Live:** https://kigojomo.github.io/camera-test/

A single-page web app for playing with your laptop camera: pick a device and resolution, try live effects (thermal, edges, ASCII, pixelate and more), take snapshots and record clips. The page also shows stream info such as the actual resolution and fps.

## Run

The camera API only works on https or localhost, so serve the folder:

```bash
python3 -m http.server 8765
```

Then open http://localhost:8765.

Keys: `Space` snapshot · `r` record · `m` mirror.
