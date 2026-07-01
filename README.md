# Awesome Local AI Android

A curated list of Android-first local AI apps, runtimes, Termux add-ons, and mobile coding workflow tools.

This repository is intentionally list-first. It is not a framework, SDK, or app shell.

## Why This List Exists

Android has become a practical place to experiment with on-device AI, lightweight coding workflows, and portable shell environments. The goal here is to keep one high-signal list for people who want to run models locally, automate phone workflows, or turn a phone into a usable development companion.

## What Belongs Here

- Projects that run local AI on Android or help you do it.
- Termux tools and add-ons that make mobile coding or automation real.
- Documentation and reference lists that help people ship or understand the stack.
- Official upstream links, not mirrors, reposts, or affiliate pages.

## Selection Criteria

- Clear Android or Termux relevance.
- Real local/offline/mobile workflow value.
- Maintained upstream project, or an archival project that still has lasting value.
- One-line descriptions that explain what the project is for.
- No spam, no self-promotion, and no duplicate entries.

## Android Apps And Frontends

- [Termux](https://github.com/termux/termux-app) - Android terminal emulator and Linux environment for shell-first workflows.
- [Termux:API](https://github.com/termux/termux-api) - Android API bridge that exposes device features to shell scripts.
- [Termux:Boot](https://github.com/termux/termux-boot) - Start scripts automatically when the device boots.
- [Termux:Widget](https://github.com/termux/termux-widget) - Put frequently used commands on your Android home screen.
- [Termux:Tasker](https://github.com/termux/termux-tasker) - Connect Termux scripts to Tasker automations.
- [Termux:X11](https://github.com/termux/termux-x11) - X server add-on for graphical Linux apps inside Termux.
- [Acode](https://github.com/Acode-Foundation/Acode) - Lightweight Android code editor with a strong plugin ecosystem.
- [AndroidIDE](https://github.com/AndroidIDEOfficial/AndroidIDE) - Full-featured IDE for developing Android apps on-device. Archived upstream; keep that maintenance status in mind before adopting it as a primary workflow.
- [Google AI Edge Gallery](https://github.com/google-ai-edge/gallery) - Experimental local model gallery for on-device ML and GenAI demos.
- [PocketPal AI](https://github.com/a-ghorbani/pocketpal-ai) - Local LLM chat app for downloading, loading, and benchmarking models on mobile.
- [Twent](https://github.com/Unselfisheologism/Twent) - Agentic Android app with local-model support (or BYOK), Linux Terminal, UI Automation, MCP, Agentic memory, Knowledge base, mini-apps, genUI, Bots, Subagents, etc.

## Local Runtimes And Inference Stacks

- [llama.cpp](https://github.com/ggml-org/llama.cpp) - Popular C/C++ inference engine for running quantized models locally.
- [MLC LLM](https://github.com/mlc-ai/mlc-llm) - Universal deployment engine for compiling and running LLMs across mobile platforms.
- [ExecuTorch](https://github.com/pytorch/executorch) - PyTorch's on-device runtime for mobile, embedded, and edge targets.
- [ONNX Runtime](https://github.com/microsoft/onnxruntime) - Cross-platform inference runtime with Android support.
- [ONNX Runtime GenAI](https://github.com/microsoft/onnxruntime-genai) - Generative AI extensions for ONNX Runtime.
- [MediaPipe](https://github.com/google-ai-edge/mediapipe) - Cross-platform ML and on-device media pipelines, including Android-ready solutions.
- [LiteRT Torch](https://github.com/google-ai-edge/litert-torch) - Convert PyTorch models for on-device execution with the Google AI Edge stack.
- [LiteRT](https://github.com/google-ai-edge/LiteRT) - Google's on-device framework for high-performance mobile ML and GenAI deployment.

## Termux And Mobile Workflow Tools

- [termux-packages](https://github.com/termux/termux-packages) - Package build system for the Termux ecosystem.
- [GitHub CLI](https://github.com/cli/cli) - Official `gh` client for issues, pull requests, and repo automation from the terminal.
- [Neovim](https://github.com/neovim/neovim) - Extensible editor that fits well in a mobile SSH or Termux workflow.
- [tmux](https://github.com/tmux/tmux) - Terminal multiplexer for keeping long-lived sessions alive on mobile devices.
- [fzf](https://github.com/junegunn/fzf) - Fuzzy finder that makes terminal navigation and selection much easier.
- [ripgrep](https://github.com/BurntSushi/ripgrep) - Fast recursive search tool for code, notes, and config on-device.

## Docs, Lists, And Related Projects

- [Termux wiki](https://wiki.termux.com/wiki/Main_Page) - Practical background on installation, package management, and environment setup.
- [Awesome TensorFlow Lite](https://github.com/margaretmz/awesome-tensorflow-lite) - Broad curated reference for mobile and edge ML around TensorFlow Lite and related tooling.
- [aeewws/codex-mobile](https://github.com/aeewws/codex-mobile) - A related companion project that explores a touch-first Android shell around a local coding runtime.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for the contribution format and inclusion rules.

## License

This project is licensed under the [MIT License](LICENSE).
