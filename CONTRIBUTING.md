# Contributing to Purity

Thank you for considering contributing to **Purity**! 🌸  
Purity is a mod launcher for *Hollow Knight: Silksong*, built with Rust + Tauri.  
It provides a user-friendly interface to manage mods, integrate with [Abyss](https://github.com/SilksongModding/Abyss), and launch the game.

---

## 📜 Code of Conduct

Please note that this project follows a [Code of Conduct](CODE_OF_CONDUCT.md).  
We expect all contributors to respect it to ensure a welcoming and inclusive environment.

---

## 🤝 How to Contribute

There are many ways to help:

- 🐛 Reporting bugs
- 💡 Suggesting new features
- 📝 Improving documentation
- 💻 Submitting code changes (UI improvements, backend integration, tests)

Check our [issues](https://github.com/SilksongModding/Purity/issues) to see what needs work.

---

## 🛠️ Development Setup

### Prerequisites
- [Rust](https://www.rust-lang.org/) (latest stable)
- [Tauri](https://tauri.app/)
- Node.js + npm/yarn (for frontend if using React/Vue)
- Git

### Build the project
```bash
git clone https://github.com/SilksongModding/Purity.git
cd purity
cargo build
```

### Run in dev mode
```bash
cargo tauri dev
```

### Build release
```bash
cargo tauri build
```

### Run tests
```bash
cargo test
```

---

## 🎨 Code Style

- Format code with:
  ```bash
  cargo fmt
  ```

- Run linter with:
  ```bash
  cargo clippy
  ```

- For frontend code, use Prettier/ESLint if applicable.  

- No warnings should remain in merged code.

---

## 🌿 Git Workflow

- **Branches**:
  - `main` → stable branch
  - `dev` → development branch
  - `feat/xxx` → feature branches

- **Commits** should be clear, in English, and follow a conventional style. Examples:

  ```
  feat(ui): add mods library page
  fix(tauri): correct path resolution for game directory
  docs(readme): add usage instructions
  ```

---

## 🔀 Pull Requests

- Open PRs against the `dev` branch.  
- Ensure that before submitting:
  - Code is formatted (`cargo fmt` / Prettier)
  - No warnings remain (`cargo clippy` / ESLint)
  - All tests pass (`cargo test`)

- Clearly describe the purpose of the PR.  
- Link to related issues when possible.

---

## 🧪 Testing

- Add unit tests for new backend logic.  
- Use integration tests for Abyss communication.  
- Frontend code should have at least basic component tests if using a framework.  
- Make sure tests pass before opening a PR.

---

## 📖 Documentation

- Document public functions with `///` Rustdoc comments.  
- Update the `README.md` if your change affects the user workflow.  
- Add screenshots or examples for new UI features when possible.

---

## 🚀 Release Process

- We follow **Semantic Versioning (semver)**: `MAJOR.MINOR.PATCH`.  
- Each release must include an updated `CHANGELOG.md`.  
- GitHub Actions ensure cross-platform builds and tests.

---

Thank you for helping make Purity better! 🌸
