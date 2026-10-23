![Mingju Zhang: Quantitative Finance](assets/header.svg)

# Mingju Zhang

I am an MSFE candidate at Columbia Business School, interested in quantitative research, systematic investing, derivatives and financial data science. I build Python studies that connect financial assumptions to statistical evidence and inspectable implementations.

My work asks three connected questions: **Can the validation be trusted? Does the account make economic sense? How do numerical error and hedging costs interact?**

## Selected work

| Study | What I built | Skills demonstrated |
| --- | --- | --- |
| [Financial ML Validation](projects/financial-ml-validation.md) · [Code](https://github.com/Mingju-Zhang-CBS/financial-ml-validation) | Three classifiers, nine feature/model configurations and a separate confirmation stage. | Financial data preparation, model comparison, leakage controls and uncertainty. |
| [Systematic Strategy Lab](projects/systematic-strategy-lab.md) · [Code](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab) | Four allocation controls with delayed execution, cash, fees and dividend receivables. | Portfolio construction, account modeling, risk analysis and invariants. |
| [Derivatives Pricing Lab](projects/derivatives-pricing-lab.md) · [Code](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab) | Analytical prices/Greeks, Monte Carlo and nine common-path hedge experiments. | Mathematical finance, numerical verification, simulation and performance measurement. |

## Evidence over a headline metric

- **ML:** the synthetic confirmation advantage has a 95% interval spanning zero; probability log loss is retained even when it worsens.
- **Strategies:** 5,040 strategy-day records reconcile cash, holdings, entitlements and fees.
- **Pricing:** the antithetic experiment reduces estimated sampling error, while finer hedging exposes a clear risk/cost tradeoff.

The studies above include workflows, result snapshots, worked reasoning and explicit limitations. Public demonstrations use synthetic data or simulated paths; the numbers are conditional experiments rather than live investment performance.

## Technical focus

| Capability | Where to inspect it |
| --- | --- |
| Statistical learning and validation | Fold-fitted preprocessing, grouped/forward evaluation, model ablations and paired uncertainty. |
| Financial modeling and accounting | Signal timing, constrained trades, corporate actions and a self-financing daily ledger. |
| Numerical methods and derivatives | Analytical sensitivities, variance reduction, simulation and discrete hedging. |
| Research software | Explicit input contracts, behavioral tests, standalone packaging, manifests and reproducible artifacts. |

**Tools used in these studies:** Python, NumPy, pandas, SciPy, scikit-learn, LightGBM, CatBoost, Matplotlib and pytest.

## Explore

[Research overview](https://github.com/Mingju-Zhang-CBS/Quant) · [GitHub repositories](https://github.com/Mingju-Zhang-CBS?tab=repositories)

<details>
<summary>Reproducibility and attribution</summary>

Each case study links to the recorded synthetic/simulation metrics and source fingerprints. The standalone implementations contain runnable examples, tests, locked dependencies and research reports. Development and documentation were AI-assisted. Public methods, task definitions and third-party libraries retain their original attribution; restricted employer/course materials are outside the portfolio.

</details>
