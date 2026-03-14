Research brief

Title: Do Prediction Markets Lead the Polls? A Time-Series Analysis of Polymarket and Traditional Polling Aggregates During High-Volatility Election Events

Bottom line
- The hypothesis is plausible and testable.
- Existing literature supports that prediction markets can incorporate information quickly and can be complementary to polls.
- Current evidence does not yet prove a universal 48-72 hour Polymarket lead; this must be estimated empirically on event windows.

What the strongest available evidence says
1) Foundational market-efficiency evidence (Wolfers & Zitzewitz, JEP) indicates prediction markets often produce accurate forecasts and can outperform common benchmarks.
2) Election-focused literature (Electoral Studies; International Journal of Forecasting metadata) suggests markets and polls each carry useful signal, with evidence of information-flow structure rather than perfect redundancy.
3) Recent election forecasting work (arXiv 2102.04936) finds time-varying relative performance: markets stronger earlier, model/poll-informed approaches stronger near election day; averaging helps.
4) Polymarket-specific preprint (arXiv 2507.08921) reports better 2024 predictive performance than polling in swing states, but this is non-peer-reviewed and should be treated cautiously.

Implications for your specific hypothesis (48-72h lead)
- Most likely outcome is conditional, not universal: lead may appear during abrupt, high-salience news shocks and in high-liquidity contracts.
- Poll aggregates can lag because of survey fieldwork windows, publication delays, and smoothing rules.
- Market moves can also be noisy or sentiment-driven; therefore, event-study controls and liquidity filters are essential.

Recommended empirical design
- Frequency alignment: convert all series to consistent hourly or 4-hour bins; preserve poll field dates when available.
- Event definition: debates, indictments/court rulings, candidate exits, major macro shocks.
- Core tests:
  a) Cross-correlation function to identify lead structure.
  b) Distributed-lag regressions (poll change on current and lagged market moves).
  c) VAR + Granger causality with robust standard errors.
  d) Event-study abnormal move windows (t-72h to t+72h).
- Robustness:
  a) Alternative poll aggregators.
  b) Liquidity and spread filters on Polymarket.
  c) Excluding overnight windows and low-volume periods.
  d) Placebo windows outside major events.

Potential outcomes to pre-register
- H1: During high-volatility events, lagged Polymarket returns (24-72h) significantly predict subsequent polling-average changes.
- H2: The lead effect is larger in swing states and in periods of high market liquidity.
- H3: Outside event windows, lead effects attenuate materially.

Evidence quality note
- High-credibility academic sources support the general mechanism (information aggregation and potential timing advantages).
- Polymarket-specific causal timing claims remain under-developed in peer-reviewed literature; treat findings as provisional until replicated with transparent, event-level time-series analysis.
