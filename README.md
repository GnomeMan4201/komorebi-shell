# KOMOREBI // SHELL

Single-file browser toolkit. Everything runs client-side; nothing is simulated.

- **Signal** — Morse encoder/decoder with Web Audio synth and live scope; SHA-256/SHA-1, Base64, hex, ROT13
- **Telemetry** — live USGS M2.5+ quakes (24h) and ISS position; Cloudflare DoH resolver; HTTPS latency probe; CIDR calculator
- **Text Wall** — infinite pannable text canvas with image→ASCII, saved to localStorage
- **Dork Lab** — search-operator compiler for Google/Bing/DDG plus crt.sh, Wayback and RDAP pivots
- **Forensics** — magic bytes + Shannon entropy + hex dump, URL homograph/tracker scrubber, LSB PNG stego, AES-GCM dead drop

On start it shows the entry menu; **INITIALIZE** runs a boot sequence of real capability and network checks.
Type `help` in the bottom CLI (Ctrl+K). `burn` wipes all local data.

Needs HTTPS for WebCrypto features (GitHub Pages provides it).
