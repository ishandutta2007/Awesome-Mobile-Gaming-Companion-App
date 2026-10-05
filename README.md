# Awesome-Mobile-Gaming-Companion-App

# Awesome-Mobile-Gaming-Companion-App

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Console Companion Apps, Controller Utilities, Game Server Panels & Crew Coordination*
**Last updated: October 2026**

This repository tracks notable **commercial companion apps** and **open-source projects** for **Mobile Gaming Companion Apps**. These tools help gamers manage consoles remotely, pair controllers, monitor game performance, run private game servers, and coordinate with their crew.

**Examples** include Xbox Mobile App, PlayStation App, Nintendo Switch App, Steam Mobile App, Battle.net Mobile, EA Mobile Companion, Discord Mobile, Razer Nexus, Backbone App, and GameBench (the category leaders).

**Open-source emphasis**: The open-source mobile gaming ecosystem is **exceptionally vibrant and community-driven**. **m3llo** provides a fully self-hostable crew app with voice, streaming, and a session feed — built in Rust with Apache 2.0 licensing . **Pelican Panel** and **GameAP** deliver modern, free game server management panels that replace Pterodactyl . **Squawk** is a private, self-hosted voice and text chat app designed for gaming groups over Tailscale . **Fresence** brings Discord-style presence to small friend groups with end-to-end encryption .

## 📖 Table of Contents

- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ SaaS/Hosted Platforms

> **📊 Market Context**: The global mobile gaming companion app market is estimated at **~$2B in 2026**, growing toward **~$5B by 2032**. The sector is **moderately fragmented** — first-party console apps (Xbox, PlayStation, Nintendo) dominate by user count, while specialized tools (Razer Nexus, Backbone, GameBench) serve controller and performance niches. **Pricing varies dramatically**: **Xbox Mobile App**, **PlayStation App**, **Nintendo Switch App**, **Steam Mobile App**, and **Battle.net Mobile** are **completely free** . **Razer Nexus** is **free with no subscription** . **Backbone** is **free with an optional Backbone+ subscription** for party chat and streaming . **GameBench** requires a **paid account** for performance testing . No single vendor holds a winner-take-all position.

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Xbox Mobile App](https://www.xbox.com/)** | **Microsoft's console companion.** Game Pass access, remote installs, parties, achievements, and Remote Play. | **Free** — no paid tier  | **Unlimited** — free with Xbox account  | **~$281B revenue (Microsoft FY2025)** |
| **[PlayStation App](https://www.playstation.com/)** | **Sony's console companion.** Trophy tracking, PSN store, Remote Play launching, and friend activity. | **Free** — no paid tier  | **Unlimited** — free with PSN account  | **~$30B gaming revenue (Sony FY2025 est.)** |
| **[Nintendo Switch App](https://www.nintendo.com/)** | **Nintendo's companion.** Friend status, QR code adding, media viewing, and game-specific features (Zelda, Splatoon, GameChat). | **Free** — no paid tier  | **Unlimited** — free with Nintendo account  | **~$12B revenue (Nintendo FY2025 est.)** |
| **[Steam Mobile App](https://store.steampowered.com/)** | **Valve's companion.** Steam Guard authentication, remote downloads, store browsing, and chat. | **Free** — no paid tier | **Unlimited** — free with Steam account | **~$6.5B revenue (Valve est.)** |
| **[Razer Nexus](https://www.razer.com/)** | **Controller companion for Razer Kishi/Prio.** Firmware updates, button remapping, Virtual Controller Mode for touch-only games. | **Free** — no subscription  | **Unlimited** — free with Razer controller  | **~$1.5B revenue (Razer FY2025 est.)** |
| **[Backbone App](https://backbone.com/)** | **All-in-one library and clip management.** Indexes native Android games, cloud subscriptions, and Bluetooth pads. Overlay capture, party chat, friends feed. | **Free** — with optional **Backbone+ subscription** for advanced features  | **Free tier**: Day-to-day use, library, pairing. **Backbone+**: Party chat, Twitch streaming, extended capture  | **Private (~$100M+ raised)** |
| **[GameBench](https://www.gamebench.net/)** | **Mobile game performance profiling.** FPS, power consumption, memory usage, and stability testing. | **Paid account** required  | **No free tier** — requires account  | **Private (GameBench)** |

## 🔓 Open-Source GitHub Projects

| Repo | Description | Stars |
|------|-------------|-------|
| **[m3llo](https://github.com/mollohq/mello)** — **Free, open-source app for gaming crews.** **Voice chat** (low latency, neural noise cancellation), **1080p60 streaming** (hardware encoded), **text chat** (markdown, replies, reactions, GIFs), and a **crew feed** that remembers gaming sessions. Perfect for crews up to **100 people**. **Apache 2.0**, self-hostable with no dependency on external infrastructure. **Alpha software** — building in public . | [![Stars](https://img.shields.io/github/stars/mollohq/mello?style=social&color=white)](https://github.com/mollohq/mello/stargazers) | ~500 |
| **[Pelican Panel](https://github.com/parkervcp/panel)** — **Free, open-source game server control panel.** Modern web UI for creating and managing game servers, running each in isolated Docker containers via Wings. Supports **Minecraft, SteamCMD games, databases, bots, voice servers, and more**. **Pterodactyl alternative** for communities, hosts, and self-hosters. Built by volunteers . | [![Stars](https://img.shields.io/github/stars/parkervcp/panel?style=social&color=white)](https://github.com/parkervcp/panel/stargazers) | ~2,000 |
| **[GameAP](https://github.com/gameap/gameap)** — **High-performance, free and open-source game server management panel.** **Pterodactyl and Pelican alternative**. Embedded **Let's Encrypt ACME** client with in-process certificate management, **Docker support**, and multi-instance deployments via S3 file storage. Go-based . | [![Stars](https://img.shields.io/github/stars/gameap/gameap?style=social&color=white)](https://github.com/gameap/gameap/stargazers) | ~1,500 |
| **[OpenKruiseGame (OKG)](https://github.com/openkruise/kruise-game)** — **CNCF Kubernetes workload specialized for game servers.** Multicloud-oriented, open-source. Supports **hot update**, **in-place update**, management of **specified game servers**, multiple network models (fixed IP/port, lossless direct connection), auto scaling, and complex game server orchestration. Go-based . | [![Stars](https://img.shields.io/github/stars/openkruise/kruise-game?style=social&color=white)](https://github.com/openkruise/kruise-game/stargazers) | ~1,000 |
| **[GameServerManager (GSM)](https://github.com/GSManagerXZ/GameServerManager)** — **Modern one-click game server deployment panel.** **React + TypeScript + Node.js** architecture. Supports **40+ Steam games** including Palworld, Rust, Valheim, 7 Days to Die, and Project Zomboid. Features: real-time Web terminal (Xterm.js), resource monitoring, JWT authentication, WebSocket communication, and graphical config editing . | [![Stars](https://img.shields.io/github/stars/GSManagerXZ/GameServerManager?style=social&color=white)](https://github.com/GSManagerXZ/GameServerManager/stargazers) | ~500 |
| **[Squawk](https://github.com/shynsec/squawk)** — **Private, self-hosted voice and text chat app for gaming groups.** Accessible only via **Tailscale VPN** — no accounts, no ads, no data leaving your machine. **Low-latency WebRTC audio**, always-on channels, text chat with typing indicators, channel ownership controls, and mobile responsive layout. **Docker-ready** with two commands . | [![Stars](https://img.shields.io/github/stars/shynsec/squawk?style=social&color=white)](https://github.com/shynsec/squawk/stargazers) | ~300 |
| **[Fresence](https://github.com/Berupor/Fresence)** — **Presence for a small group of friends.** Discord-style status bar without Discord. Every device gets a card with tiles (focused app, track, Steam game, weather, clock, photo). **End-to-end encrypted** — server stores blobs but cannot read them. Invite-only, works on phone and desktop . | [![Stars](https://img.shields.io/github/stars/Berupor/Fresence?style=social&color=white)](https://github.com/Berupor/Fresence/stargazers) | ~200 |
| **[Cobalt](https://github.com/artorias-developer/cobalt)** — **Self-hosted game server dashboard for friend groups.** Web dashboard for running game servers on your own VPS/VDS. Supports **Minecraft, Terraria, Don't Starve Together, Factorio, RimWorld, 7 Days to Die, Project Zomboid, Barotrauma**. Each server runs in isolated Docker containers. Real-time CPU/RAM monitoring, file manager, multi-user roles . | [![Stars](https://img.shields.io/github/stars/artorias-developer/cobalt?style=social&color=white)](https://github.com/artorias-developer/cobalt/stargazers) | ~200 |
| **[LunaChron](https://github.com/Garemat/lunachron)** — **Companion app for the Moonstone tabletop miniatures game.** Track health, energy, moonstones, and abilities during games. Troupe builder with QR code sharing, local multiplayer over Wi-Fi, and campaign tracking. **Fully offline**, no accounts, no ads, no tracking. Available on F-Droid . | [![Stars](https://img.shields.io/github/stars/Garemat/lunachron?style=social&color=white)](https://github.com/Garemat/lunachron/stargazers) | ~100 |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[Fresence Agent](https://github.com/Berupor/Fresence)** — Linux agent CLI for the Fresence presence app. `fresence join`, `fresence status`, `fresence watch` . |
| **[GameBench SDK](https://docs.gamebench.net/)** — Integrate performance monitoring into CI/CD pipelines . |
| **[AccelByte Grafana Integration](https://docs.accelbyte.io/)** — Real-time game health, matchmaking, and server monitoring dashboards via Grafana Cloud . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Companion apps handle account credentials and gaming activity data; ensure compliance with platform terms of service and privacy regulations.
- **Open-source reality**: The open-source ecosystem for mobile gaming companions is **exceptionally vibrant and community-driven**. **m3llo** provides a fully self-hostable crew app with voice, streaming, and session history . **Pelican Panel** and **GameAP** deliver production-grade game server management . **Squawk** and **Fresence** bring private communication to gaming groups . However, **commercial platforms** (Xbox App, PlayStation App, Razer Nexus) provide **first-party console integration, polished mobile experiences, and seamless hardware pairing** that open-source alternatives cannot match. The open-source path is **genuinely viable** for self-hosted game servers, private voice chat, and crew coordination.

---

**Made for mobile gamers, private server operators, crew leaders, and open-source enthusiasts.**
Let's make mobile gaming companions more open, transparent, and community-driven.
