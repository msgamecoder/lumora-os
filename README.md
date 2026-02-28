# lumora-os

Lumora is an experimental x86_64 operating system focused on speed and responsiveness,
especially on HDD-based systems. The long-term goal is a lightweight desktop, a simple
package format (.lum), and optional Windows PE/.exe experimentation later.

## Goals
- Fast boot + responsive UI
- HDD-first performance: caching, read-ahead, async I/O
- Lightweight desktop (window manager + icons)
- `.lum` package format for apps
- Optional: PE loader / limited `.exe` support research

## Current Status
- [ ] Boots in QEMU (UEFI)
- [ ] Framebuffer boot splash
- [ ] Interrupts + timer
- [ ] Memory management
- [ ] Processes + syscalls
- [ ] Storage driver + filesystem
- [ ] Cache + async I/O
- [ ] GUI + window manager + icons
- [ ] `.lum` packages
- [ ] Optional `.exe` experiments

## Build & Run (QEMU)
> Coming soon

## Project Layout
- `kernel/`  - kernel source
- `boot/`    - boot/UEFI loader
- `drivers/` - hardware drivers
- `fs/`      - filesystem + cache
- `gui/`     - window manager + rendering
- `docs/`    - design notes

## License
Apache-2.0
