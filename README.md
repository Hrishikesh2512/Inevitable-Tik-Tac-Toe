# InevitableTickTacToe

A terminal-based implementation of Tic-Tac-Toe powered entirely by a pure Minimax algorithm.

No randomness.  
No heuristics.  
No machine learning.  

Only recursive logic and mathematically optimal play.

---

## Overview

InevitableTTT is a minimal demonstration of deterministic game intelligence.

The AI evaluates every possible future board state recursively and always chooses the optimal move. It does not guess, improvise, or rely on probability.

Every decision is computed through exhaustive logical evaluation.

Result:
- The AI can never lose
- The best possible human outcome is a draw
- Perfect play emerges from mathematics alone

---

## Features

- Pure Minimax implementation
- Matrix-only board logic
- Terminal-based gameplay
- Human input using `1–9` mapping
- Deterministic AI decisions
- Impossible-to-defeat opponent
- Zero external libraries

---

## Board Layout

```text
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9
