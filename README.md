# Structure Capital Quiz (live)

8-bit team quiz for the GoClimate team session. One static file, no backend, no CDN dependencies.

- **Host (presenter screen):** open the host link with the key: `/?host#key=…` (Emil has it). The questions are encrypted in this file and only unlock with the key; the key is remembered in that browser afterwards.
- **Players (phones/laptops):** scan the QR code on the host screen, or open `/` and enter the 4-letter code plus a nickname.
- **Keys on the host:** Space / → / clicker = next, ← = back, U = undo the last reveal.
- Phones and host talk through a free public message relay (MQTT over WebSocket, broker.emqx.io:8084). Add `&p2p` to both links for direct peer-to-peer, or `&broker=wss://...` for another relay.
- **Try it alone:** host link in one tab, player link in another tab or on your phone.
- **Credits only:** `/?credits`

Questions are built from Slack, Notion, Drive, Miro and the labeling guide (Oct 2025 – Oct 2026). Delete this repo after the session.
