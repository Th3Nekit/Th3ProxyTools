# Th3ProxyTools

> [Русская версия](README.md)

Plugin for [exteraGram](https://exteragram.app/) — advanced proxy manager.

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![exteraGram](https://img.shields.io/badge/exteraGram-plugin-6C3FE0)
![Platform](https://img.shields.io/badge/platform-Android-3DDC84?logo=android&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

## Features

- **Mass ping** — check all proxies with one tap, live status updates
- **Native / TCP / HTTP** — three ping modes to choose from
- **Country flags** — automatic geolocation & ISP detection (ip-api.com)
- **Import/Export** — import from clipboard, export to Saved Messages
- **Sort by ping** — one tap
- **Live UI** — statuses refresh every second during checks

## Stack

- [exteraGram Plugin API](https://plugins.exteragram.app/) — plugin platform
- `ConnectionsManager` — native proxy ping
- `ip-api.com` — batch geolocation & ISP
- `SharedConfig` — Telegram proxy list management

## Installation

1. Download `Th3ProxyTools.plugin`
2. Send the file to your Saved Messages in exteraGram
3. Tap the file → "Install plugin"

## Plugin Settings

| Setting | Description |
|---|---|
| Ping mode | Native / TCP / HTTP (SOCKS) |
| URL (HTTP) | URL for HTTP check via SOCKS |
| Country flags | Show flag and ISP |
| Buttons | Ping all / Sort / Import / Export |

## Structure

```
Th3ProxyTools/
├── Th3ProxyTools.plugin   # Plugin file
├── README.md              # Documentation (RU)
├── README_EN.md           # Documentation (EN)
└── LICENSE                # MIT
```

## Author

[@th3_nek1t](https://t.me/th3_nek1t)

## License

MIT © 2026 Th3Nekit
