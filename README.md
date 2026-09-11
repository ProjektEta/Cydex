# Cydex

**Cydex** is a free, Lua-based Roblox macro project designed to automate repetitive gameplay tasks across supported Roblox experiences.

Currently supported:

- **Anime Vanguards**
- **Wild Horse Islands**

Cydex is designed around **free and open-source solutions**, with no paid SDK or macro software required.

> ⚠️ **Disclaimer:** Cydex is an independent community project and is not affiliated with Roblox or the developers of the supported games. Automation may violate the rules of individual Roblox experiences and could result in gameplay restrictions. Use responsibly and at your own risk.

---

## ✨ Features

- Completely free
- Lua-based
- Modular game profiles
- Anime Vanguards support
- Wild Horse Islands support
- Configurable actions and delays
- Repeating macro sequences
- Easily expandable to other experiences
- Designed around free/open-source tooling

---

## 🎮 Supported Experiences

### Anime Vanguards

Cydex can provide configurable automation for repetitive gameplay routines in Anime Vanguards.

Game-specific actions are kept inside their own profile, making them easier to update when the game changes.

### Wild Horse Islands

The Wild Horse Islands profile is designed for repetitive, predictable gameplay actions such as movement and routine interactions.

Profiles can be customized independently from the Cydex core.

---

## 🧠 Architecture

Cydex uses a modular Lua structure:

```text
Cydex/
├── README.md
├── LICENSE
│
├── Cydex.lua
│
├── sdks/
│   ├── anime_vanguards.lua
│   └── wild_horse_islands.lua
│
└── macro_profiles/
    └── av_summer2026.lua
```

The **core** handles common functionality, while individual games have their own modules.

This makes it possible to add another supported experience without rewriting the entire project.

---

## Free & Open-Source

Cydex aims to remain completely free.

The project can make use of free/open-source Lua libraries and macro solutions where appropriate.

The goal is to avoid requiring users to purchase:

- Paid macro applications
- Proprietary SDKs
- Subscription automation services
- Closed-source dependencies

---

## ⚙️ Configuration

Cydex profiles can exposes SDKs to make it easy to make modular macros with ease such as:

```lua
local sdk = require(Cydex.SDK)

sdk.place_unit_1(vector2.new(0,0))
```

---

## 🔐 Security

Cydex will never **never require users to provide**:

- Roblox passwords
- `.ROBLOSECURITY` cookies
- Authentication tokens
- Browser credentials
- Payment information

Do not use or distribute features intended to steal credentials, bypass authentication, or circumvent Roblox security systems.

> ⚠️ **Disclaimer:** Although Cydex will not ask for user info, it could be possible that peoples macro profiles could potentially contain malicious code. Please make sure what you are running and that for maximum safety stick to Cydex Official Profiles.

---

## 🤝 Contributing

Contributions are welcome.

Ideas include:

- Adding new game profiles
- Improving Lua architecture
- Improving configuration
- Adding new macro actions
- Fixing bugs
- Improving documentation
- Adding accessibility features

---

## 📜 License

Cydex is intended to remain free and open source.

See [`LICENSE`](LICENSE) for the full license.

---

## ⭐ Disclaimer

Cydex is an independent project and is not affiliated with **Roblox**, **Anime Vanguards**, or **Wild Horse Islands**.

Roblox and the respective game names are trademarks/property of their respective owners.

Users are responsible for following the rules of the Roblox experiences they use Cydex with.
