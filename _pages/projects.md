---
layout: page
title: Projects
permalink: /projects/
description: 
nav: true
nav_order: 3

---

<style>
p {
text-align: justify;
}
</style>


## Quantitative Research 

---

**Black-Karasinski Parameter Estimation (2026)** BDO UK 

**Findings:** Designed a parameter estimation methodology for credit volatility and mean reversion speed from historical credit spreads alone, exploiting the equivalence between Ornstein-Uhlenbeck and first order autoregressive processes. Unlike rates, where liquid instruments allow parameters to be implied directly, illiquid or private credits offer no such instruments; this approach enables stochastic credit modelling for path-dependent credit-linked exotics on names with limited market data. 

---

**Discount for Lack of Marketability "DLOM" (2025)** BDO UK

**Findings:** Formulated a 'Hybrid Put' DLOM framework accounting for both the full extent of downside-risk as well as some measure of lost upside potential, avoiding the pathologies of established models. Derived analytic approximation using a novel Asian-style exotic, and evaluated numerical performance to show solution is well behaved and offers practitioners a tractable, defensible discount.

---

**SABR Interpolation Error (2025)** BDO UK

**Findings:** Investigated how volatility surfaces should be interpolated across expiries where market quotes are unavailable, originally prompted by a client mispricing options at non-tenor dates. Through literature review and independent analysis benchmarking methods across regimes and data-generating processes (rough Bergomi), showed that total variance interpolation and probabilistic methods consistently outperform SABR parameter space interpolation directly, judged on recovered volatilities and static-arbitrage consistency. 

---

**Hidden Losses during the CME Trading Halt (2025)** Independent Research

**Findings:** Following the 28 Nov 2025 CME trading outage, developed methodology leveraging treatment of outage as a temporary illiquidity shock, identifying the optimal DLOM model by benchmarking against synthetic outages and using the optimal model, estimating hidden losses of approximately $10 mln across NASDAQ and S&P e-mini futures.

---

**Monte Carlo Scheme Study (2025)** CQF

**Findings:** Derived and compared closed-form solutions and Monte Carlo simulation schemes (Euler-Maruyama and Milstein) for vanilla and exotic options. Numerical results aligned with analytic solutions for certain plain-vanilla and binary options, where Milstein scheme diverges from Euler-Maruyama in barrier and Asian options for certain volatility-tenor regions.

---

**Experimental Fluid Dynamics Dissertation (2022)** University of Warwick

**Findings:** Designed experimental methodology leveraging Particle Image Velocimetry techniques and computer vision to identify the presence of particular inertial waves resulting from uneven structures on highly rotational vortex cores, contributing novel findings to the field.

 

<br><br>

## Quantitative Development 

---

**Automated Exotics Extension (2026)** BDO UK 

**Outcome:** Designed and implemented extension to the prior automated valuation system, to include range of exotics across commodities, credit, equities, inflation, and volatility, broadening coverage to more complex, higher-value instruments. 

---

**Automated Derivative Valuations Engine (2026)** BDO UK 

**Outcome:** Developed and productionised a fully automated derivatives valuation and risk engine for vanilla products, significantly improved team-wide efficiency, project timelines, tunraround, and pitch competitiveness for previously inaccessible mandates.

---

**Automated Convertible Bond Risk Metrics (2026)** BDO UK

**Outcome:** Developed an automated system for parameter-specific risk sensitivity metrics for previously unaddressed parameters, minimising model risk and improving result integrity.

---

**Black-Karasinski Automation (2026)** BDO UK

**Outcome:** Leveraged OU/AR(1) equivalency in stochastic credit modelling as outlined in my 2026 BK Parameter Estimation working paper towards an automated system sourcing Refinitiv historical credit spreads, estimating the appropriate parameters, and generating model-specific risk metrics to be used in subsequent pricing.

--- 

**Automated Reporting System (2025)** BDO UK

**Outcome:** Developed a system to automatically generate technical reports, expanding automation pipeline and significantly improving team-wide efficiency, freeing junior member time to focus on high-complexity projects.



<br><br>

## Machine Learning & Systematic Trading 

---

**Generating Directional Signal from IV Metrics (2025)** CQF

**Outcome:** Utilised SVM systems to generate a trading signal based on the implied volatility metrics across one-day-to-expiry options, displaying meaningful predictive power (Accuracy: 0.99, Macro F1: 0.97) and yielding out of sample returns 2.1 times greater than buy-and-hold.

---

**Synthetic Derivatives Exchange Arbitrage (2024)** Independent Research 

**Outcome:** Developed an automated trading strategy exploiting mispricing of derivatives across crypto-exchanges. Strategy successfully identified arbitrage opportunities by identifying mispricing both across exchanges for a given instrument, as well as between particular instruments and their synthesised equivalents.

---

**Optimised Windows Momentum Strategy (2024)** Independent Research 

**Outcome:** Designed an automated trading system for digital assets, using realised volatility to predict the optimal window configuration for a traditional momentum strategy. Strategy achieved approx. 1.7 times greater returns (21%) than a buy-and-hold strategy across the same period in live trading.

---

**Currency Identification CNN (2021)** University of Warwick

**Outcome:** Developed a system to identify a variety of currency types from a live webcam input. Trained a CNN employing computer vision techniques to reach an overall accuracy of 96%.

