# KOMOREBI // SHELL — recorded live demo

A **music-free screen recording of the actual public application**, captured in Chromium on November 23, 2026. No replacement or simulated interface was used.

## Videos

| File | Use | Technical details |
| --- | --- | --- |
| `KOMOREBI-SHELL-live-demo-1080p.mp4` | Main upload/editing master | 79.292 s; 1920×1080; 24 fps; H.264; no audio. **Upscaled** from 1366×768 browser capture, not native 1080p recording. |
| `KOMOREBI-SHELL-live-demo-music-free.mp4` | Native-resolution edited cut | 79.292 s; 1366×768; 24 fps; H.264; no audio. Includes title/outro and brief chapter labels. |
| `komorebi-live-capture.mp4` | Unedited browser recording | 73.5 s; 1366×768; 24 fps; H.264; no audio. |

All videos were recorded or rendered from the publicly deployed application at https://gnomeman4201.github.io/komorebi-shell/ . The `main` branch remains unchanged.

## Chapters in edited cut

- 00:00 — Opening title
- 00:02 — Initialize shell and run real boot checks
- 00:09 — Morse audio, SHA-256 and Base64
- 00:18 — Live quake map, ISS orbital telemetry, DNS and CIDR
- 00:33 — Infinite text wall, text and panning
- 00:41 — OSINT query compilation and local saved vault
- 00:49 — Magic bytes/entropy, URL analysis, PNG steganography, AES-GCM encrypt/decrypt
- 01:06 — Interactive CLI commands and navigation
- 01:16 — Closing title / site URL

## Verified browser outputs

- USGS earthquake layer rendered with 49 events in its then-current 24-hour feed; ISS layer returned location, altitude, and velocity data. These are time-sensitive readings.
- Cloudflare DNS-over-HTTPS returned A records for `example.com`.
- Local file inspection recognized a real PNG (`64,572 B`), with Shannon entropy reported as `7.852 bits/B`.
- Steganography decode recovered `proof in the pixels` from the edited carrier.
- AES-GCM unlock recovered the original note `Local encryption. No server.`.
- No page JavaScript exceptions were observed in the recorded browser session.

The encryption passphrase and test content were synthetic demo inputs, not production secrets. No private accounts were accessed. Live network responses are not guaranteed to be identical at playback time.

## File checksums (SHA-256)

- 1080p edited: `0dcc1df0dbf2efb798af29949d67194f3fa0ab96715676c009e4c04cf3b8a241`
- Native edited: `680a3f5be3d1018c611f77300cef63b3f421e0815a66f4bc0775a8c73e9dc671`
- Unedited capture: `93da328f2d67ceb33279a7b9873e085f46283d407824c4da4e7c82affa1cef85`

## Editing

The MP4 files contain **no audio track**, so a separate soundtrack can be added without stripping existing audio. No user application source files were changed for the recording.
