Fraud and audit analytics by day. Systems architecture, open-source tooling, and homelab experiments by night.

---

## What I Work On

Professionally, I work in fraud and audit analytics — digging through transaction data, behavioral signals, and process flows to find where the happy path breaks down. Turns out a brain that defaults to skepticism and gravitates toward edge cases is useful in that context.

Outside of work: data pipeline tooling, format libraries, self-hosted infrastructure, and ML experiments on local hardware.

## Stack

**Languages:**
- **Rust** — when performance and correctness are the point
- **Python** — data work and scripting, Polars-first
- **TypeScript** — frontend when necessary
- **Go** — certain backend use cases

**Tooling:** strong preference for tools that do their job and stay out of the way. Current favorites: [`uv`](https://docs.astral.sh/uv/) for Python, [`bun`](https://bun.sh) for JS, [`rustup`](https://rustup.rs) for Rust toolchains, [`pixi`](https://pixi.sh) for reproducible environments. The common thread is fast, portable, and project-isolated.

**Infrastructure:** Arch Linux everywhere. Self-hosted Postgres, object storage, and various services on a homelab server. Docker for isolation and reproducibility.

## How I Think About Systems

Most systems are information flows. Data in, transformation, data out. The model holds for data pipelines, AI systems, organizational structure, application architecture — trace the flow and you can usually understand what's going wrong.

The fraud and audit background reinforces this: you develop a habit of asking "what does this system assume is true?" and then going to find where that assumption fails. Useful for debugging. Occasionally exhausting otherwise.

---

<details>
<summary><b>Hardware Setup</b></summary>

**Server:** Arch Linux, AMD Ryzen 7 5700G, 64GB RAM, Nvidia RTX 3060 12GB, 100TB+ storage  
**Workstation:** Arch Linux, AMD Ryzen 7 5700G, 64GB RAM, AMD Radeon RX 6700X  
**Laptop:** Arch Linux, Intel Core i5 8th Gen, 8GB RAM (SSH into Workstation)

</details>
