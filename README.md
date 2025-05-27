# SatCom Dashboard

A real-time satellite constellation monitoring dashboard designed for engineers, enthusiasts, and aerospace mission teams.

## What It Does

SatCom Dashboard visualizes live or simulated satellite constellation data—like Starlink, OneWeb, or CubeSats—in an interactive dashboard. The system can display:

- Real-time orbital paths and position tracking
- Uplink/downlink latency mapping by region
- Constellation coverage heatmaps
- Predictive orbital projection (TLE-based)

## Tech Stack

- **Frontend:** React, D3.js, or Plotly for interactive visualizations
- **Backend:** Python (FastAPI or Flask), REST or WebSocket feed
- **Data Sources:** Public satellite APIs, TLE feeds (e.g. Celestrak), optional simulated feeds
- **Optional:** Dockerized deployment for on-prem / offline simulation use

## Why I Built This

Space is messy, fast-moving, and not always visible. As someone obsessed with real-world systems and mission control engineering, I wanted to build something that:
- Mirrors real mission dashboards
- Trains orbital prediction intuition
- Serves as an open-source tool for space-aware devs and educators

This is part of **Project VELA**, a long-term initiative to reinvent myself as a systems-level problem solver ready to contribute to organizations like SpaceX and OpenAI.

## Roadmap (see `/docs/roadmap.md` for task breakdown)
- [ ] MVP: Track a small set of TLE satellites on a 2D map
- [ ] Add coverage + latency visualization layer
- [ ] Add simulated “dead satellite” or “high latency” alerting
- [ ] Full orbital prediction overlay
- [ ] Deployable Docker image for mission replay/sandbox

## Core Themes

- Space systems intuition
- Visual systems thinking
- Real-time data + fault tolerance
- UI design for signal over noise

## 📎 License

MIT License
