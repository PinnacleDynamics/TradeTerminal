# TradeTerminal — Crypto Trading Dashboard (Showcase)


Public showcase of a **Flutter Web trading terminal** (Bybit) and an **options bot** (Deribit/Bybit).
This repository contains **screenshots, videos, and documentation only** — no proprietary source code.

**Live (demo UI):** `https://trade.bitspinner.io` *(if available)*

---

## Features

### Trading Terminal (Flutter Web)
- Futures/Spot/Options selector, quote chooser, symbol list.
- Live WS price with throttling; candlestick chart with overlays (entry ladder, TP lines, Fib).
- Budget/position calculator, multi-level entries, separate TP upsert (20/30/50).
- “Send to exchange”, “Cancel all”, “Market close”.
- Mobile-first Material 3 UI; responsive; safe UI freeze during scroll for smooth updates.

### Options Bot (Deribit/Bybit)
- Python worker: REST/WebSocket clients with auth/signing, reconnect/backoff, rate-limits.
- Paper/live modes with safety toggles.
- Parametrized strategies (symbol, TP multiplier, distance to strike, contracts/side, cooldown,
  stop-new-before-expiry), risk caps (max pair cost USD), heartbeat/health, error handling.
- Monitoring & PnL: ladder snapshots, bid/mark tracking, realized & intraday PnL.
- Flutter Web dashboard: live charts, state panels, history/logs, settings.

---

## Tech Stack
- **Frontend:** Flutter Web (Material 3)
- **Exchanges:** Bybit (REST/WS), Deribit (REST/WS)
- **Bot:** Python services (workers, schedulers)
- **Infra:** Docker, HTTP adapters/proxies

---

## Media
- Screenshots: `/media/screens`
- Videos: `/media/videos` (via Git LFS)

> This repo is a **showcase** (screens, videos, docs). No source code is published.

---

## Contact
Gennady Mikhaylov — software developer (Unity/Flutter, backend & integrations).
