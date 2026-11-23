# KOMOREBI // SHELL — live interface demo

**Recorded:** November 23, 2026  
**Application:** https://gnomeman4201.github.io/komorebi-shell/  
**Source:** https://github.com/GnomeMan4201/komorebi-shell

This video was captured by running the publicly deployed KOMOREBI application in Chromium, driving the actual interface with browser automation and recording the display. It is **not** a synthetic UI animation, screenshot slideshow, or mockup.

## Files

- [KOMOREBI-SHELL-live-demo-1080p.mp4](KOMOREBI-SHELL-live-demo-1080p.mp4) — edited 79.3-second demo, 1920×1080, 24 fps, H.264, silent, with intro/outro and section labels.
- [KOMOREBI-SHELL-raw-live-capture.mp4](KOMOREBI-SHELL-raw-live-capture.mp4) — unedited browser recording, 73.5 seconds, 1366×768, 24 fps, H.264, silent.
- [cover.png](cover.png) — opening still.

## Real operations captured

1. Initialize the live shell, run Morse encoding and transmission, hash/encode a message.
2. Load USGS earthquake telemetry; switch to live ISS orbital telemetry; query public DNS; calculate a CIDR range.
3. Stamp and write on the browser-local infinite text wall.
4. Compose a public-domain advanced search query and save it to the browser-local vault.
5. Inspect a local PNG file's signature, entropy and hex bytes; inspect and scrub a URL; hide and recover a PNG steganographic message; encrypt and decrypt a local AES-GCM note.
6. Run actual built-in CLI commands.

The real network responses, including quake data, ISS coordinates, and DNS records, were recorded at capture time and will naturally change on subsequent runs. Browser console page-error checks returned zero errors for the recorded run.

## Add music later

Use your editor to add music under the **silent 1080p MP4**, or use a command like:

```bash
ffmpeg -i KOMOREBI-SHELL-live-demo-1080p.mp4 -i soundtrack.mp3 \
  -map 0:v:0 -map 1:a:0 -c:v copy -c:a aac -b:a 192k \
  -shortest KOMOREBI-SHELL-with-music.mp4
```

No music, voiceover, or sound effects were added in the master files.  
This branch contains demo assets only; it does not modify the deployed site's main branch.
