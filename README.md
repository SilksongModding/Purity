# 🌸 Purity

**Purity** is a **mod launcher for Hollow Knight: Silksong**, built with **Rust + Tauri**.  
It provides a user-friendly interface to manage mods, interact with [Abyss](https://github.com/SilksongModding/Abyss), and launch the game in either vanilla or modded mode.

---

## ✨ Features (current & planned)

- 📂 **Mod library**: list installed mods, enable/disable, remove.  
- 🔍 **Mod explorer**: search & download mods from NexusMods/GameBanana.  
- ⚡ **One-click install**: automatic integration with Abyss & BepInEx.  
- 🎮 **Game launcher**: run Silksong in vanilla or modded mode.  
- 🔔 **Updates**: notifications for new versions of Abyss, BepInEx, and mods.  
- 🧩 Future: dependency/conflict detection with UI warnings.  
- ⬆️ Future: mod profiles & advanced configuration.  

---

## 📦 Installation

> ⚠️ Purity is under active development and not production-ready yet.

1. Clone the repository:
   ```bash
   git clone https://github.com/SilksongModding/Purity.git
   cd purity
   ```

2. Build with Cargo (Rust) & install frontend dependencies (if any):
   ```bash
   cargo build --release
   ```

3. Run Purity:
   ```bash
   ./target/release/purity
   ```

---

## 🚀 Usage

Purity offers a graphical interface with these main sections:

- **Library** → view and manage installed mods.  
- **Explorer** → browse & install mods directly from Nexus/GameBanana.  
- **Settings** → configure Abyss, BepInEx, and Silksong path.  
- **Launcher** → start Silksong (vanilla or modded).  

---

## 🧪 Development

### Requirements
- [Rust](https://www.rust-lang.org/) (latest stable)
- [Tauri](https://tauri.app/)
- Cargo (comes with Rust)
- Node.js + npm/yarn (for frontend if using React/Vue)
  - Frontend framework not decided yet.

### Run in dev mode
```bash
cargo tauri dev
```

### Build release
```bash
cargo tauri build
```

---

## 📖 Documentation

- [Abyss](https://github.com/SilksongModding/Abyss) — technical backend (mod loader wrapper).  
- [BepInEx Official Docs](https://docs.bepinex.dev/).  
- [Tauri Documentation](https://tauri.app/).  

We aim to provide **clear user & developer documentation** as the project grows.

---

## 🛠️ Roadmap

- [ ] MVP: Library + Settings + Launcher
- [ ] Explorer: NexusMods/GameBanana integration
- [ ] Updates: check for new versions of mods/Abyss/BepInEx
- [ ] Dependency & conflict management
- [ ] Profiles & advanced configuration

---

## 🤝 Contributing

Contributions are welcome!  
Please check our [issues](https://github.com/your-org/purity/issues) and open pull requests.  

Before submitting, make sure to:
```bash
cargo fmt
cargo clippy
cargo test
```

---

## 📜 License

MIT License © 2025 — Purity contributors
