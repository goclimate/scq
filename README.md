# Structure Capital Quiz (live)

8-bit team quiz for the GoClimate team session. One static file, no backend.

- **Host (presenter screen):** open `/?host`. Shows a game code and a QR code.
- **Players (phones/laptops):** scan the QR code or open `/`, enter the code and a nickname.
- Phones and host talk through a free public message relay (MQTT over WebSocket, broker.emqx.io). Add `&p2p` to both links for direct peer-to-peer instead, or `&broker=wss://...` for another relay.
- **Try it alone:** `/?host&local` in one tab and `/?local` in another tab of the same browser.

Questions are built from Slack, Notion, Drive and Miro (Oct 2025 – Oct 2026). Delete this repo after the session.
