# bio-rs

Open source Rust/WASM tools for biological AI models.

Python is where many bio-AI models are born. `bio-rs` is where the tooling
around them becomes portable, inspectable, and easier to use from CLIs,
browsers, servers, and agents.

## Current focus

The first layer is intentionally small:

```txt
FASTA -> validated protein sequence -> token ids -> model-ready input
```

## Projects

- [`bio-rs`](https://github.com/bio-rs/bio-rs): the main monorepo for core
  libraries, CLI tools, and future WASM/agent tooling.

## Direction

`bio-rs` is building toward:

- protein and biological sequence input contracts
- tokenizers and model-ready inputs
- CLI tools for local workflows
- WASM tools for browser-side demos
- portable model runners
- agent-callable biological AI tools

The goal is not to replace Python research workflows. The goal is to make the
tools around Python-born bio-AI models easier to package, inspect, and run
outside notebooks.
