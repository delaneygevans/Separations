# Beyond Filtration

An educational membrane-separation website for a chemical engineering separations project, covering membrane fundamentals, membrane types, engineering calculations, and environmental applications.

## Technology

This project is designed as a Rust + Leptos 0.6 WebAssembly application built with Trunk for `wasm32-unknown-unknown` and deployed to GitHub Pages.

## Local development

Install Rust, the `wasm32-unknown-unknown` target, and Trunk. Then run:

```bash
rustup target add wasm32-unknown-unknown
cargo install trunk
trunk serve
```

Build with:

```bash
trunk build --release
```

The Trunk base path is configured for `/Separations/` so the production build can be hosted at `https://delaneygevans.github.io/Separations/`.

## Topics

- Microfiltration, ultrafiltration, nanofiltration, and reverse osmosis
- Flux, observed rejection, recovery, and simplified resistance relationships
- Membrane bioreactors, water reuse, and industrial wastewater treatment

## Model assumptions

The interactive calculator uses user-entered values and idealized definitions. The resistance equation is a simplified teaching relationship; real membrane systems may require concentration-polarization, fouling, osmotic-pressure, and module-specific corrections.
