# Ling Qi

Quantitative trading research and execution engineering.

I work on market-data pipelines, explicit strategy hypotheses, and the reliability of the path from signal to execution. My project notes distinguish code changes, offline checks, simulated results, and broker evidence.

## Featured project

### [Polymarket — Order-Book & Execution Research](https://github.com/LQ-09/PolyMarket)

**Python · REST/WebSocket data · market microstructure · simulation**

Collect complementary binary-market order books and test paired-contract opportunities after a simplified cost allowance. The code separates token discovery, snapshots, signals, execution and position accounting.

- **Inspect:** [research design and maintenance log](https://github.com/LQ-09/PolyMarket#maintenance-record), [synthetic example](https://github.com/LQ-09/PolyMarket/blob/main/examples/synthetic_snapshots.json), [accounting checks](https://github.com/LQ-09/PolyMarket/blob/main/tests/test_synthetic_accounting.py).
- **Recorded iterations:** token-ID parsing fixes, batch history collection, and clearer API-response handling in January 2026.
- **Current limit:** immediate two-leg simulated fills; no live-order implementation or verified profitability claim. Depth, partial fills and legging risk are next research questions.

## Execution engineering

**IBKR workbench — private implementation; public export under validation**

October 2026 work includes moving quote-audit file writes to a background queue, coalescing concurrent monitoring snapshots, and adding state-commit latency measurements. These changes address specific sources of execution-path interference; no measured order-latency improvement is claimed. Tuned strategies, account data and execution records stay private.

## Earlier strategy research

**Crypto factor and position-sizing experiments — private pending publication confirmation**

Rolling standardized factors, quantile-based long/short sizing, and transaction-cost comparisons. The repository records a July 2025 research iteration. Timing alignment, cost conventions and out-of-sample robustness still need validation.

---

Maintained by [Ling Qi](https://github.com/LQ-09). Each project documents its evidence, current limitations and next checks.
