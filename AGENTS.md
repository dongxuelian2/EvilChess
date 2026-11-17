# EvilChess — AGENTS.md

## Project identity

EvilChess explores a deliberately contrary, experimental chess-engine architecture: explicit mathematics, search, and direct computation instead of machine-learning training. The goal is to investigate an extreme design point, including approaches with high theoretical or engineering risk. Chess mathematics and proofs belong in [chess-endgame-cgt](https://github.com/dongxuelian2/chess-endgame-cgt).

## Current phase

The project is in concept and literature exploration. Keep the repository limited to `README.md`, `AGENTS.md`, and the single image asset embedded by the README. Do not create engine code, scaffolding, workflows, benchmarks, directories of proposals, or placeholder infrastructure before implementation is explicitly requested.

## Implementation principles (for the later engineering phase)

- Do not create a training pipeline, train a chess model, or introduce learning dependencies as a default solution. Existing pretrained components may be considered only when an experiment justifies them.
- Do not preselect a mathematical formalism, evaluation function, search method, implementation language, or hardware target. Investigate available research first.
- Prioritize computational performance and experimentally relevant playing strength. Hardware is unrestricted: CPU, GPU, SIMD, parallelism, assembly, and specialized accelerators are available choices.
- Favor end-to-end measurements over isolated throughput claims. Measure costs of memory access, synchronization, evaluation, search, and data movement.
- Keep mathematics and implementation separate. The engineering repository should ultimately contain the program and files directly necessary to build, test, and run it; proofs and literature reviews remain in the mathematical repository.
- Runtime position hashes, transposition tables, and other structures that directly aid computation are legitimate. Do not add checksum manifests, decorative SHA inventories, audit logs, ceremonial status documents, or unneeded CI/CD scaffolding.
- When an engine exists, validate move generation, legality, special moves, game termination, and UCI behavior. Support Linux and portable toolchains where practical.
- Write source and technical documentation in English. Describe implemented behavior, measured results, and necessary limitations plainly. Keep the README entertaining without letting jokes replace technical facts.
- Prefer decisive experiments and working changes to process-oriented documents. Remove superseded clutter as the design evolves.

## Tone

Technical work is serious; the README may be irreverent. A playful jab at NeuroChess is part of the project's identity. The measurements and implementation must remain precise.
