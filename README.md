# Anime Origins Ultimate

**Language:** **English** | [Tiếng Việt](./README.vi.md)

[![Price](https://img.shields.io/badge/price-free-22c55e)](#free--open-source)
[![Source](https://img.shields.io/badge/source-open-3b82f6)](#free--open-source)
[![Language](https://img.shields.io/badge/language-Luau-00a2ff)](https://luau.org/)
[![License](https://img.shields.io/badge/license-MIT-f59e0b)](./LICENSE)

**Anime Origins Ultimate** is a free and open-source Luau automation script for Anime Origins on Roblox. It combines lobby automation, in-game macro tools, rift and challenge farming, auto join, shop, summon, craft, webhook, and local config management in one interface.

The script has no key system, no paywall, and no user fee.

> This is a community project and is not affiliated with or endorsed by Roblox or the developers of Anime Origins. Use third-party software at your own risk and follow the platform's terms of service.

## Features

- Lobby and in-game UI for Anime Origins Ultimate.
- Auto Join with mode, world, act, difficulty, artifact, and card priority options.
- In-game macro recording, optimization, import, playback, auto replay, and infinite restart support.
- Auto Quest, Auto Story, Auto Challenge, and Auto Rift workflows.
- Auto Claim for supported rewards and progression systems.
- Auto Craft, Auto Shop, Auto Summon, and Auto Redeem Codes.
- Rift and Challenge timer persistence across lobby/game sessions.
- Discord webhook support for automation notifications.
- Igris/Clash helpers including parry, chest, book, frag, and clash automation where supported.
- Auto reconnect, FPS limit, Anti-AFK, mobile button, and local config save/load.

## Installation

Run the following loader in a compatible Luau environment after joining the game:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/Truyem/Anime-Origins/refs/heads/main/AnimeOriginsUltimate.lua"))()
```

## Requirements

- A Luau execution environment with `loadstring` and `game:HttpGet` support.
- HTTP requests through `request`, `http_request`, or `syn.request` for webhook/API features.
- File APIs such as `readfile`, `writefile`, `isfile`, `isfolder`, and `makefolder` for config and timer persistence.
- Advanced features may require executor APIs such as `hookmetamethod`, `hookfunction`, `getconnections`, and debug APIs.
- An internet connection for loading external UI libraries and remote resources.

Compatibility depends on the execution environment. Missing APIs may prevent individual features from working even if the interface loads successfully.

## Basic Usage

1. Run the script in Anime Origins.
2. Configure the lobby or in-game tab that matches your task.
3. Save your settings in Configs after setup.
4. Verify map, macro, webhook, and auto leave options before going AFK.
5. Use the mobile button or configured hotkey to reopen the interface when needed.

Configs and runtime data are stored in folders named `AnimeOrigins_<UserId>` inside the executor workspace.

## Repository Files

- [`AnimeOriginsUltimate.lua`](./AnimeOriginsUltimate.lua): main Anime Origins automation script.
- [`README.vi.md`](./README.vi.md): Vietnamese documentation.
- [`LICENSE`](./LICENSE): MIT License.

## Free & Open Source

The main source is available in [`AnimeOriginsUltimate.lua`](./AnimeOriginsUltimate.lua) for the community to inspect, improve, and contribute to at no cost.

- Do not pay anyone to obtain this script.
- Do not trust reuploads that require a key or payment.
- Download the latest version directly from the official GitHub repository.
- Keep the copyright and license notices when sharing or forking the project.

This project is released under the [MIT License](./LICENSE).

## Contributing

Bug reports and pull requests are welcome.

1. Fork the repository.
2. Create a branch for your change.
3. Keep changes focused and do not add obfuscated code.
4. Check the Luau syntax before opening a pull request.
5. Describe the changed behavior and how you verified it.

Never publish webhook URLs, account tokens, or personal data in issues or pull requests.

## Credits

- **Truyem789**: creator of Anime Origins Ultimate.
- [Fluent](https://github.com/dawid-scripts/Fluent): UI library and config addons.
- The Anime Origins community for testing, macro knowledge, and feedback.

## Disclaimer

This software is provided as-is and may stop working after a game update. The author is not responsible for data loss, account disruption, or other consequences resulting from its use.
