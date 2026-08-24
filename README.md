# Hi, I'm Husaam 👋

**ICAS Chartered Accountant | MSc Data Science & Artificial Intelligence, Queen Mary University of London | Former EY Financial Services**

I build applied finance and data projects across quantitative research, market risk, derivatives, securitised products, credit and private markets. My work combines financial analysis with Python, statistical methods, machine learning and reproducible software.

I am interested in problems where financial analysis, modelling and software meet.

## Featured Projects

### [Renewable Energy ABS Cashflow & Tranche Waterfall Engine](https://github.com/husaam-atq/renewable-energy-abs-waterfall-model)

Models a static £100.0m pool of 2,500 synthetic UK solar-energy loans from scheduled collateral cashflows, defaults, prepayments and lagged recoveries through a Class A/B/C waterfall. The model includes excess spread, a reserve, overcollateralisation, structural triggers, tranche IRR/WAL analytics and stress/sensitivity analysis.

In the configured downside, 9.57% net collateral loss is absorbed without note loss; under the 26.43% stress loss, Class C is fully impaired, Class B loses 34.73% of principal and Class A principal and interest remain whole. Outputs include a formatted Excel model, Streamlit dashboard, reconciliation checks and a 52-test suite. All collateral and securities are fictional and illustrative.

### [MSc Dissertation — Financial Transformers & Market Dynamics](https://github.com/husaam-atq/MSc-financial-transformer-market-dynamics)

An adversarial multi-asset forecasting study asking whether strong pooled Transformer performance reflects temporal forecasting skill or persistent cross-sectional structure. The evaluation combines leakage-aware chronological splits, static priors, within-asset estimands, identity diagnostics, chronology perturbations and controlled simulation.

On the final 21,514-window test set, the Transformer achieved pooled ROC-AUC 0.790, below a training-only static asset prior at 0.824, while pair-weighted within-asset ROC-AUC was 0.492. None of five learned models passed the full temporal-skill gate. A registered 1,040-run simulation confirmed that the framework can distinguish static prevalence effects from a planted ordered signal.

### [Derivatives Pricing & Risk Analytics Engine](https://github.com/husaam-atq/derivatives-pricing-engine)

A tested Python engine covering Black-Scholes-Merton pricing and Greeks, implied volatility, CRR trees, Monte Carlo with variance reduction, Heston simulation and calibration, volatility surfaces and delta hedging. All 26 committed validation checks pass: textbook BSM pricing errors are below 3e-5, the 1,000-step CRR error is approximately 0.0020 and synthetic Heston calibration RMSE is 3.12e-5. The package includes CI, reports, notebooks and a Streamlit interface.

### [Credit Cashflow, LBO Returns & Downside Case Model](https://github.com/husaam-atq/credit-cashflow-downside-model)

A five-year model of a synthetic leveraged company linking operating forecasts, debt schedules, covenants, liquidity, lender recovery, restructuring options, LBO returns and a value-creation bridge. Base-case net leverage declines from 4.0x to 1.7x with no covenant breach; downside breaches occur in FY2026–FY2027; stress exhausts liquidity, produces 54%–98% lender recovery across the modelled 5.0x–9.0x valuation range and wipes out sponsor equity. Outputs include an Excel workbook, investment memo, dashboard and tested Python model.

### [Volatility Risk Forecasting Platform](https://github.com/husaam-atq/volatility-risk-forecasting-platform)

A Python and DuckDB market-risk platform comparing rolling volatility, EWMA, HAR, GARCH-family, machine-learning and ensemble forecasts, then converting them into VaR and Expected Shortfall with Kupiec and Christoffersen testing. Across the committed ten-asset test, rolling-update HAR improves average QLIKE by 40.41% versus rolling 21-day volatility; average 95% and 99% VaR breach rates are 4.76% and 0.81%. The committed SQL benchmark covers 2.87m rows with 16.14ms dashboard-query p95 latency on the test machine.

### [Private Markets Screening & SEC Filing Intelligence](https://github.com/husaam-atq/private-markets-screening-dashboard)

A public-data diligence workflow combining SEC EDGAR/XBRL fundamentals, public comparable screening, peer benchmarking, filing retrieval and source-backed evidence. The current portfolio-mode snapshot screens 283 companies and indexes 15,965 chunks in total: 15,692 from 35 real SEC filings and 273 clearly labelled fallbacks. On a 96-question retrieval evaluation, Hit@5 is 100% and Precision@5 is 89.4%. The workflow runs deterministically without an LLM, with an optional local Ollama path, and does not present screening outputs as investment recommendations.

## Other Research & Modelling

- [Systematic Equity Factor Research](https://github.com/husaam-atq/systematic-equity-factor-backtester) — Cross-sectional momentum and low-volatility research with lagged weights, long/short and long-only construction, IC diagnostics, transaction costs, rebalance sensitivity and benchmark-relative analysis.
- [Systematic Portfolio Construction](https://github.com/husaam-atq/systematic-portfolio-construction) — Multi-asset comparison of equal weight, minimum variance, maximum Sharpe, risk parity, covariance shrinkage, trend and dual-momentum overlays, volatility targeting and stress/cost sensitivity.
- [Limit Order Book Trading Engine](https://github.com/husaam-atq/limit-order-book-trading-engine) — Price-time-priority matching, synthetic event replay, TWAP/VWAP/POV execution, slippage and transaction-cost analytics, backtesting and deterministic validation.
- [Trading Research Dashboard](https://github.com/husaam-atq/trading-research-dashboard) — Cointegration and OU-style pairs research with static, rolling and Kalman hedge ratios, nested walk-forward selection and cost/filter sensitivity.
- [QMML Market-Making Hackathon](https://github.com/husaam-atq/qmml-market-making-hackathon) — Team-built fair-value and uncertainty-aware quoting workflow for a nine-round live simulated competition, finishing just outside the top ten.
- [BM25F Search Engine](https://github.com/husaam-atq/BM25F_Search_Engine) — Team-built field-aware search engine with a positional SPIMI index, phrase/proximity scoring and controlled WordNet expansion, evaluated across 249 TREC Robust04 topics.

## Technical Toolkit

- **Programming & Data:** Python, pandas, NumPy, SciPy, scikit-learn, statsmodels, PyTorch, SQL, DuckDB
- **Finance & Quantitative Methods:** Financial modelling, valuation, credit analysis, securitisation, derivatives, portfolio construction, factor research, volatility modelling, VaR and Expected Shortfall, backtesting
- **Research & Engineering:** Time-series modelling, machine learning, leakage-aware evaluation, model validation and interpretability, Monte Carlo simulation, information retrieval, RAG, Git/GitHub, testing and CI, Streamlit

## Background

- MSc Data Science & Artificial Intelligence — Queen Mary University of London
- ICAS Chartered Accountant
- Three years at EY Financial Services, with experience across private equity, asset management, international banking and insurance
- CFA Level I Candidate — November 2026

## Contact

[LinkedIn](https://www.linkedin.com/in/husaam-atq) · [Email](mailto:husaam.ateeq@gmail.com)
