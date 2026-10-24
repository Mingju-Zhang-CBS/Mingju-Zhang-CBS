![Mingju Zhang](assets/header.svg)

# Mingju Zhang

**Quantitative Research & Financial Machine Learning**  
Columbia Business School MSFE ’27 · USC Applied & Computational Mathematics + Cognitive Science

I build testable research systems that connect financial data, model validation and trading decisions. My mathematical and cognitive-science training shapes how I turn ideas into testable questions.

[LinkedIn](https://www.linkedin.com/in/mingju-zhang-611b00223/) · [Research directory](https://github.com/Mingju-Zhang-CBS/Quant) · [Methods and background](#research-background)

**Research thread:** Financial Data → Signals → Validation → Portfolio & Execution.

![From financial data to trading decisions](assets/research-map.svg)

## Selected research

### 01 · Agentic Quant Research

**Can a research workflow learn from an unsuccessful result?** I built proposal validation, past-only factors, date partitions, frozen selection and sealed-stage recovery. The synthetic development winner fails confirmation; that result stays visible.

*Research engineering · temporal validation · lineage*  
[Code](https://github.com/Mingju-Zhang-CBS/agentic-quant-research) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/agentic-quant-research/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/agentic-quant-research/blob/main/reports/demo/REPORT.md)

### 02 · Financial ML Validation

**How much trust does a financial classifier earn?** I compare logistic regression, LightGBM and CatBoost with keyed labels, train-fitted transformations and date-level uncertainty. The synthetic accuracy interval includes zero.

*Financial ML · data preparation · uncertainty*  
[Code](https://github.com/Mingju-Zhang-CBS/financial-ml-validation) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/reports/demo/REPORT.md)

### 03 · Financial Text Validation

**Does policy text add information beyond prices?** I compare TF-IDF text, price and fusion models on real public FOMC statements and first-published EUR/USD references, separating measurement dates from release availability and freezing confirmation choices.

*Financial NLP · real-data provenance · publication clocks*  
[Code](https://github.com/Mingju-Zhang-CBS/financial-text-validation) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/financial-text-validation/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/financial-text-validation/blob/main/reports/demo/REPORT.md)

### 04 · Market Making Lab

**What changes when fair value becomes an affordable quote?** I connect backward dynamic programming to three inventory/collateral-aware policies across nine shared-path simulations. Every result can be traced through trade cash flows, markouts and settlement.

*Probability · market microstructure · inventory risk*  
[Code](https://github.com/Mingju-Zhang-CBS/market-making-lab) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/market-making-lab/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/market-making-lab/blob/main/reports/demo/REPORT.md)

### 05 · Systematic Strategy Lab

**Does a signal still make sense inside a funded account?** I model delayed decisions, integer trades, fees, paid cash and dividend receivables. Four controls reconcile daily NAV before cost and execution-delay sensitivity is interpreted.

*Portfolio construction · accounting · execution assumptions*  
[Code](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/reports/demo/REPORT.md)

### 06 · Derivatives Pricing Lab

**How do numerical error and hedge costs interact?** I connect analytical prices and Greeks to Monte Carlo variance reduction and common-path delta hedging. The study separates sampling uncertainty, model assumptions and the cost of more frequent trades.

*Mathematical finance · numerical methods · risk*  
[Code](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab/blob/main/reports/demo/REPORT.md)

### 07 · Defined-Outcome Research

**What does a buffer mean for a later buyer?** I connect public issuer terms to funded option claims, entry-time scenarios and fee conventions, keeping model marks separate from observed quotes.

*Derivatives · product research · funded decisions*  
[Code](https://github.com/Mingju-Zhang-CBS/defined-outcome-research) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/defined-outcome-research/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/defined-outcome-research/blob/main/reports/demo/REPORT.md)

## Research background

My work connects AI-assisted research, financial text, equity signals and portfolio implementation, with academic interests in point-in-time data, credit and real estate. The [research map](https://github.com/Mingju-Zhang-CBS/Quant#research-map) explains these connections through original method notes, with restricted source materials kept private.

I was a **Top 15 finalist in the Akuna Capital 2026 Virtual Quant Trading Challenge**. The public market-making lab is a separately designed simulation; its results are not official contest scores. I am exploring **2027 full-time opportunities in North America, Hong Kong and China**, primarily in quantitative research and financial ML, with a continuing interest in trading and derivatives.

Outside research, I enjoy Go, Formula 1 and karting, basketball and hiking. For professional background and contact, please use [LinkedIn](https://www.linkedin.com/in/mingju-zhang-611b00223/).

<details>
<summary>How to read the evidence</summary>

Seven studies include real FOMC/FX research, issuer-grounded product scenarios and five synthetic/simulated studies. Methods, configuration, source fingerprints and tests accompany results; unfavorable outcomes remain visible. Prior academic and professional experience is distinguished from these independent implementations. Development and documentation were AI-assisted, and upstream methods and libraries retain attribution. [Further extensions](https://github.com/Mingju-Zhang-CBS/Quant#next-research) remain separately labeled.

</details>
