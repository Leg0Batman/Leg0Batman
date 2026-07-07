# Tim Suskov

Berlin. Incoming mathematics student, interested in machine learning systems built from first principles.

Portfolio: [tsuskov.github.io](https://tsuskov.github.io)

## Selected projects

### LLM stack from scratch (Rust)

A complete language-model pipeline, written by hand without ML frameworks:

| Stage | Repository | |
|---|---|---|
| Tokenization | [Cadmus](https://github.com/Tsuskov/Cadmus) | Byte-level BPE tokenizer — the merge-learning algorithm implemented from scratch |
| Training | [Hephaistos](https://github.com/Tsuskov/Hephaistos) | GPT/Llama-style model with hand-written forward pass and backpropagation, every gradient numerically verified; exports to GGUF |
| Inference | [Talos](https://github.com/Tsuskov/talos) | Minimal inference engine with an opt-in Metal GPU backend (2.8–3.7× the CPU path) |
| Deployment | [Talos Forge](https://github.com/Tsuskov/talos-forge) | The full stack compiled to WebAssembly — [live demo](https://tsuskov.github.io/talos-forge) |

### Other work

- [raytracing](https://github.com/Tsuskov/raytracing) — real-time CPU raytracer in Rust: multithreaded, BVH-accelerated, 4K export
- [strange-attractors](https://github.com/Tsuskov/strange-attractors) — interactive 3D visualization of the Lorenz and Rössler attractors, RK4 integration
- [AloeGarden](https://github.com/Tsuskov/AloeGarden) — SwiftUI focus-reading app for iOS with Home and Lock Screen widgets
- [orbitale](https://github.com/Tsuskov/orbitale) — hydrogen-atom orbitals (s, p, d, f) rendered as electron-density plots in the terminal

## Currently

Learning theorem proving in Lean 4 ([Mathematics in Lean](https://leanprover-community.github.io/mathematics_in_lean/)) in preparation for university mathematics.
