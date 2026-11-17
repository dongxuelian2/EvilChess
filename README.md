# EvilChess

<p align="center">
  <img src="assets/what-evil.webp" alt="A deeply unimpressed catgirl asking what is so evil about chess" width="440">
</p>
<p align="center"><em>“What do you mean, train?”</em></p>

**NeuroChess:** A 155.7-million-parameter Transformer, carefully trained to understand the board.

**EvilChess:** *Have you considered simply calculating harder?*

EvilChess is an experimental chess-engine project and a deliberately contrary sibling to [NeuroChess](https://github.com/ddy314/NeuroChess). Where NeuroChess invests in learned representations, EvilChess explores explicit mathematics, search, algorithms, and unapologetically aggressive computation.

We are investigating the opposite end of the design space, not claiming that it will win. A weird idea that fails spectacularly is still a useful experiment. A weird idea that works is even funnier.

## Philosophy

- **Mathematics first, machinery second.** The theoretical work belongs in [chess-endgame-cgt](https://github.com/dongxuelian2/chess-endgame-cgt). We will let the research inform the engine rather than choose the algorithm in advance.
- **Zero training budget.** No machine-learning training pipeline. Explicit algorithms and direct computation take priority; existing pretrained components remain optional if an experiment genuinely calls for them.
- **All compute is fair game.** CPUs, GPUs, vector units, parallel systems, accelerators, intrinsics, and assembly are welcome. Silicon is meant to be used.
- **No sacred implementation.** The architecture may be elegant, grotesque, or both. A measurable result matters more than adherence to a favorite technique.
- **Extreme experiments encouraged.** Unconventional representations, unusual search regimes, exact subproblem solvers, and mathematically ambitious approaches are all on the table.
- **Keep the repository lean.** Retain working source, necessary build inputs, direct tests, and concise documentation when implementation begins. No administrative confetti.

## Status

**Research and design exploration.** We are reading the literature and examining possible mathematical foundations before committing to a search architecture.

There is no engine implementation here yet. For now, the project consists of this README, contributor instructions, and the meme that accurately represents our feelings about gradient descent.

---

*NeuroChess learned to think. EvilChess is asking whether thinking is strictly necessary.*
