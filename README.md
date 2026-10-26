# Hi, I'm Jeremy 👋

**AI Systems Builder · Systems & Protocols Engineer · Open Source Developer**  
*Building agentic developer tools, local-first systems, and hardware interfaces.*

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/thrtysxty)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeremy-thiessen-1314b720)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:jeremy.m.thiessen@gmail.com)

---

## 🚀 Projects & Open Source

### 🪐 [Copernicus IDE](https://github.com/thrtysxty/copernicus)
> **An open-source agentic development environment where LLM agents work as peers on engineering teams.**  
> `TypeScript` · `React 18` · `Electron 33` · `Python` · `Apple MLX` · `sqlite-vec`

- Architected a desktop IDE orchestrating autonomous LLM agents (Claude, Gemini, Google Jules) via an automated Plan → Delegate → Review loop.
- Built a visual SVG workflow canvas with node-based task routing and time-travel state rollback (`SnapshotManager`).
- Implemented local code intelligence using 768-dim `sqlite-vec` embeddings and AST/LSP symbol-aware chunking.
- Integrated native on-device Apple Silicon inference via Apple MLX (`mlx-lm`) alongside real-time CapEx token telemetry logging inference cost and latency to SQLite.

---

### 💈 [Claude Code Barber (ccb) & yasr](https://github.com/thrtysxty/claude-code-barber)
> **High-performance Rust context-optimization and token management layer for agentic coding sessions.**  
> `Rust 2021` · `Tree-sitter` · `SQLite` · `Clap` · `Tokio`

- Slashes LLM token consumption by 50% to 94% using hook-based command output trimming (`ccb trim`) that intercepts verbose build/test streams (`cargo`, `npm`, `pytest`, `git`) before they hit model context.
- Implemented on-demand skill indexing and lazy-loading (`ccb fade`), SQLite-backed expert persona knowledge graphs (`ccb expert`), and Tree-sitter AST symbol indexing.
- Includes `yasr`, a clean-room Rust terminal statusline delivering live session telemetry, context token burndown, and customizable ANSI themes.

---

### 🖨️ [CatPrinter Swift](https://github.com/thrtysxty/catprinter-swift)
> **Native macOS CoreBluetooth driver & HTTP relay daemon for portable BLE thermal mini-printers.**  
> `Swift` · `CoreBluetooth` · `CoreGraphics` · `Python 3` · `Reverse-Engineered Protocols`

- Pure Swift implementation interfacing directly with 58mm BLE micro thermal printers (Cat Printer / POS-58) without third-party drivers or CUPS filters.
- Implemented binary packet framing with CRC-8 checksumming, dynamic printhead heating energy modulation (`0xAF`), drawing mode control, and bitmap raster graphics rendering.
- Built a lightweight Python HTTP relay daemon bridging webhooks, browser frontends, and ERP systems to physical Bluetooth print hardware.

---

### 🏷️ NFC Inventory Engine & Warehouse Appliance
> **Local-native, zero-dependency warehouse intake and crate tracking system with multimodal AI appraisal.**  
> `Python 3 Standard Library` · `SQLite` · `NTAG213/215 NFC` · `Google Gemini Vision` · `Docker`

- Built a zero-pip-dependency inventory engine using only Python 3 standard library and SQLite, designed for local servers and embedded appliances.
- Features physical NTAG213/NTAG215 NFC tote routing with automated crate-prefix SKU generation and dynamic capacity allocation.
- Integrates Google Gemini Vision for rapid multimodal appraisal, maker identification, and metadata extraction.

---

### 🧠 Self-Hosted Local AI Fleet & Knowledge Pipeline
> **Multi-node local compute fleet for open-weights reasoning and automated knowledge distillation.**  
> `CUDA` · `llama.cpp` · `Ubuntu` · `RTX 3060` · `Obsidian` · `Docker` · `Apple Silicon MLX`

- Multi-node compute fleet running CUDA-accelerated `llama.cpp` serving open-weights reasoning models (DeepSeek-R1, Qwen 2.5/3.5, GLM) with 131K context and flash attention over OpenAI-compatible endpoints.
- Automated Obsidian knowledge-distillation pipeline extracting and linking atomic concepts via background daemons.
- Implemented multi-provider model routing, GGUF quantization, and LoRA/QLoRA fine-tuning pipelines.

---

### 🍎 Apple Toolchain MCP & Edge ML
> **Model Context Protocol servers wrapping Apple's core developer toolchain and on-device vision.**  
> `Model Context Protocol (MCP)` · `Swift` · `xcodebuild` · `CoreML` · `Apple Vision`

- Designed MCP servers wrapping Apple developer tooling (`xcodebuild`, `simctl`, `codesign`, `notarytool`), enabling autonomous AI agents to build, test, and package Swift applications headlessly.
- Prototyped on-device multimodal CoreML and Apple Vision pipelines (VisionScanner, FastVLM, DepthAnything) for Apple Neural Engine (ANE) execution.

---

## 🛠️ Stack & Tooling

```
  Systems & Protocols    │ Web APIs (REST), CoreBluetooth (BLE), NFC (NDEF), DNS, Networking, Linux/Ubuntu
  Languages              │ Rust, Swift, TypeScript, Python, SQL, Bash
  Agentic AI & LLMs      │ Multi-Agent Orchestration, Model Context Protocol (MCP), Prompt Engineering
  Local Inference & ML   │ llama.cpp (CUDA), Apple MLX (mlx-lm), CoreML (ANE), Quantization (GGUF)
  AI Coding Tools        │ Claude Code, OpenAI Codex, ChatGPT, Google Jules
  Infrastructure & Ops   │ Docker, Systemd, SQLite, PostgreSQL, Git/GitHub Actions
```

---

## 📬 Contact & Links

- **GitHub:** [github.com/thrtysxty](https://github.com/thrtysxty)
- **LinkedIn:** [linkedin.com/in/jeremy-thiessen-1314b720](https://www.linkedin.com/in/jeremy-thiessen-1314b720)
- **Email:** [jeremy.m.thiessen@gmail.com](mailto:jeremy.m.thiessen@gmail.com)
