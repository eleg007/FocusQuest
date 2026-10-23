# FocusQuest — Components

Single-file static web app (focus/productivity quest UI). **No build system,
no services, no external libraries.**

## systemd services

None.

## Libraries / dependencies

None. Fully self-contained: no CDN scripts, no external stylesheets, no fonts
fetched over the network.

## Contents

| File | Description |
|---|---|
| `index.html` | The entire app — HTML + inline CSS + inline JavaScript |
| `preview.png` | Screenshot preview of the UI |

## Notes

- Runs by opening `index.html` in any browser (or serving the directory with any static file server).
- No server-side state; everything is client-side.
