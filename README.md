# TradeTerminal — Crypto Trading Dashboard (Showcase)

Web-based trading terminal and options bot (Bybit/Deribit) with live charts, ladder controls, risk management, and PnL monitoring.

> **Note:** This repo is a public **showcase** (screenshots, videos, docs). **No source code** is published.

## Features
- Live price chart with overlays
- Ladder/levels editor and TP presets (20/30/50)
- Orders, PnL, and status panels
- Paper & live modes, health/heartbeat
- Risk controls: max pair cost, cooldowns, stop-before-expiry, etc.

## Tech Stack
- **Client:** Flutter Web (Material 3, responsive UI, WS streaming)
- **Backend:** Python services, REST/WebSocket clients, auth/signing, retry/backoff
- **Exchanges:** Bybit & Deribit APIs
- **Infra:** Dockerized services, monitoring/logging

## Repository Structure
