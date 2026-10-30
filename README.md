# Ling Qi

Quantitative trading research, strategy implementation and execution engineering.

## Current work

### IBKR strategies and execution

The recent work is the strategy pipeline: how signals are generated, tested, admitted by cost and risk checks, and passed to execution. The monitoring dashboard is a supporting component.

The private IBKR working repository records October 2026 changes to execution evidence, recovery checks and isolation of monitoring/audit work from the execution path. Those are code changes, not a claim of measured speedups or profitable results.

**Core strategy source is not yet public.** It is being separated from account configuration, tuned private parameters and operating records for an accurate public presentation. The reusable Workbench export is supporting infrastructure, not a substitute for that strategy code.

### [Agent Control Center — Native Multi-Agent Workspace](https://github.com/LQ-09/multi-agent-control-center)

**Tauri 2 · React / TypeScript · Python · SQLite**

An open-source native desktop app for coordinating Codex CLI, Claude Code and compatible text-model APIs through planning, execution and review. Start on one computer and add SSH execution environments when needed, with task timelines, structured handoffs and explicit acceptance of results.

The current preview includes an Apple Silicon macOS app, signed in-app updates, Chinese/English interfaces and adjustable text sizes. Account usage panels display CLI-reported subscription limits when available, and task-level model/effort controls support configurable agent defaults. Agent execution is currently read-only; broader orchestration and cross-host recovery remain active engineering work.

[Source and setup guide](https://github.com/LQ-09/multi-agent-control-center#readme) · [Download releases](https://github.com/LQ-09/multi-agent-control-center/releases)

## Earlier projects

### [Polymarket — Order-Book & Execution Research](https://github.com/LQ-09/PolyMarket)

**Python · REST/WebSocket · market microstructure · simulation**

Collect complementary binary-market books and test paired-contract opportunities after a simplified cost allowance. January 2026 iterations fixed token discovery and expanded history collection.

[Research design and dated maintenance](https://github.com/LQ-09/PolyMarket#maintenance-record) · [Synthetic example](https://github.com/LQ-09/PolyMarket/blob/main/examples/synthetic_snapshots.json) · [Accounting checks](https://github.com/LQ-09/PolyMarket/blob/main/tests/test_synthetic_accounting.py)

Immediate two-leg fills are a modeling assumption. The live engine sends no orders; no verified profitability claim is made.

### [Crypto — Factor & Position-Sizing Research](https://github.com/LQ-09/Crypto)

**Python · pandas/NumPy · rolling factors · cost-aware backtesting**

A July 2025 iteration studying standardized factors, quantile-based long/short sizing, and transaction costs. Timing alignment, fee consistency and out-of-sample robustness remain explicit validation tasks.

---

Maintained by [Ling Qi](https://github.com/LQ-09). Projects are ordered by actual research/engineering activity, not returns or today's documentation edits.
