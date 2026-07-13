# Example project CLAUDE.md

This is an example of wiring the Double Diamond process into a Claude Code
project. Copy the "Process" section into your own CLAUDE.md and keep
PROCESS.md somewhere in the repo (here: docs/PROCESS.md).

---

# MyProject

Web service for X. Python 3.12, FastAPI, pytest. Run tests with `pytest -q`.

# Process

For any non-trivial task — a new feature, a design decision, research, anything
where the problem statement is not already fixed — follow the Double Diamond
process defined in [docs/PROCESS.md](../PROCESS.md).

Hard rules, restated:

- **Discover / Develop**: work with high autonomy. Bring me patterns and
  options, not questions you can answer yourself.
- **Define gate**: never finalize a problem statement yourself. Bring 3–5
  candidates with trade-offs and a recommendation, then stop and wait.
- **Deliver gate**: never select the final option or ship/submit/deploy
  without my explicit approval, and report verification results unembellished.
- **Rewind in the open**: if evidence overturns an earlier decision, say what
  flipped and why before proceeding.

For trivial tasks (typo fixes, small refactors, questions), skip the process
and just do it.
