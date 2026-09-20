# Privacy

Short version: **Lumen collects nothing.** No account, no analytics, no
telemetry, no crash reporting, nothing sent to us, ever.

## What actually touches the network

Lumen has no language model and stores nothing about you. These are the
**only** things that ever reach the internet, and only when you trigger them:

| When | What happens |
|---|---|
| **First time Lumen speaks** | Downloads its voice model (a public, open-source model) once. After that, voice synthesis is fully offline. |
| **Weather…** | The city name you type is sent to [Open-Meteo](https://open-meteo.com/), a free public weather API, to look up conditions. Nothing else is sent. |
| **Web Search…** | Your default browser opens a search on DuckDuckGo for whatever you typed — the same as if you'd typed it into your browser yourself. |

That's the complete list. Every other command — the clock, your system
status, your battery, opening an app, adjusting volume, listing running
apps — runs entirely on your own machine and never touches the network.

## What Lumen stores

Nothing, beyond the one-time voice model file cached locally on your own
disk (so it doesn't have to download again). Lumen keeps no logs, no
history, no settings tied to an account — because there is no account.

## Third parties

- **Open-Meteo** (Weather) and **DuckDuckGo** (Web Search) are independent
  services with their own privacy practices; Lumen only sends them what's
  described above, and only when you use those specific commands.
- The voice model is downloaded from its public hosting; no personal data
  is included in that request.

## Questions

This document describes the app as published. If anything here is ever
unclear, open an issue on the [GitHub repository](https://github.com/Alex-Stark-industries/Lumen-Desktop-Orb).
