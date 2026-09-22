## Vishwesh Venkatramani

Master in Financial Mathematics at MIT, finishing February 2027. I work on machine learning applied
to asset pricing, with a bias toward finding out where published results stop holding.

Previously BSc Software Engineering at RIT (valedictorian, 1/250), and software engineering at
Paychex and DataTech before graduate school.

**Now:** independent research with Prof. Leonid Kogan on machine-learning return prediction.
**Recruiting:** full-time quantitative research roles, available from February 2027.

---

### Selected work

**[virtue-of-complexity](https://github.com/vishwesh-V/virtue-of-complexity)** — replication and
stress-testing of the "virtue of complexity" in return prediction (Kelly, Malamud & Zhou 2024).

Random Fourier features of the 15 Goyal–Welch predictors, ridge regression across the full
complexity spectrum, 1926–2025. Reproduces the paper's central paradox: the timing strategy's Sharpe
ratio rises as the model becomes massively overparameterized while out-of-sample R² stays negative.

The critiques are implemented as counter-specifications rather than argued in prose. Buncic (2025) so
far: restoring an unpenalized intercept lifts Sharpe everywhere while worsening R², and reporting
per-draw rather than averaged Sharpe exposes dispersion spanning −0.08 to +0.23 at low complexity
that narrows as complexity grows. Both objections bite hardest where the headline result does not
live. Nagel (2025) and Cartea, Jin & Shi (2025) next, then a research note adjudicating the debate.

**Prediction-market microstructure** — large-move detection over the full Kalshi tick history: 72M
trade executions across 7.6M contracts, aggregated to per-ticker one-minute bars with strictly causal
features, then a 1D CNN per forward horizon under a leakage-safe protocol. The useful result was
negative: saliency and ablation showed the network had learned a price-level heuristic rather than
temporal structure, and that flat quotes in illiquid contracts were inflating AUC. Team project,
Harvard CS1090B.

---

### Tools

Python (pandas, NumPy, scikit-learn, PyTorch) · SQL · R · CRSP, Bloomberg, Fama–French and
Goyal–Welch data · Parquet · Git · LaTeX

---

[vv29@mit.edu](mailto:vv29@mit.edu) · [LinkedIn](https://linkedin.com/in/vishwesh-venkatramani)
