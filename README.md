# XARCv2 (Project Xarc Revived)

**Status: 🚧 Just restarted — nothing built yet. Design phase.**

---

## Origin

XARCv2 is a complete rebuild of my original XARC project (mid-2025 to December 2025). The original was an LLM experiment. That source code is permanently gone.

**Why restart?**  
I need a strong IT portfolio for my long-term goal: engineering roles in Shenzhen (2030). This project will be my primary showcase.

---

## What This Project Will Become

A **physical sorting system** using computer vision + lightweight AI, running on RISC-V hardware (VisionFive 2).

**Planned functionality:**
- Camera captures an object
- Vision pipeline processes the image
- Lightweight classifier decides destination
- Servo motors physically sort the object

---

## Planned Tech Stack

| Component | Technology | Why |
|-----------|------------|-----|
| Core logic | Rust (no_std) | Memory safety, embedded target |
| AI training | Python (scikit-learn) | Fast prototyping |
| Inference | Rust (pure, no Python) | Runs on RISC-V |
| Database | SurrealDB | Weight storage, logging |
| Target hardware | StarFive VisionFive 2 (RISC-V) | Open architecture, full Linux |
| Development host | Windows 11 + WSL2 (Debian 12) | Linux toolchain on Windows |

---

## Current Status (April 2026)

| Component | Status |
|-----------|--------|
| Project planning | 🔄 In progress |
| Rust environment setup | ⏳ Not started |
| Python training pipeline | ⏳ Not started |
| Vision pipeline | ⏳ Not started |
| RISC-V cross-compilation | ⏳ Not started |
| Hardware purchasing | ⏳ Not started (awaiting digital banking) |

**Nothing is built yet. This README will update as progress happens.**

---

## Timeline (Estimated)

| Milestone | Target |
|-----------|--------|
| Rust basics complete | June 2026 |
| Python training script (dummy data) | July 2026 |
| Rust JSON parser for weights | August 2026 |
| First working inference (x86_64) | September 2026 |
| Cross-compile to RISC-V (QEMU test) | October 2026 |
| Purchase VisionFive 2 board | Late 2026 |
| Hardware demo (camera + servo) | 2027 |

---

## Project Structure (Planned)
xarcv2/
├── src/
│ ├── main.rs # Entry point, GPIO init
│ ├── classifier.rs # AI inference engine
│ ├── servo.rs # Motor control
│ └── db.rs # SurrealDB logging
├── training/
│ ├── train.py # Python training script
│ └── weights.json # Exported weights
├── Cargo.toml
├── README.md
└── LICENSE

Contact
Justin Wiltshire (O7NGuy)

Website: torxen.co.uk

GitHub: github.com/O7NGuy

Acknowledgements
Built independently as part of my IT portfolio. Targeting Shenzhen tech sector (2030).
