---
layout: page
title: research
permalink: /projects/
description: 
nav: true
nav_order: 3
---

## quantitative research 

---

**Black-Karasinski Parameter Estimation (2026)** BDO UK 

**Aim:** Investigate the BK short-rate model in the context of credit default intensity, following observation of calibration difficulties arising from data scarcity and market illiquidity

**Findings:** Designed a parameter estimation methodology for credit volatility and mean reversion speed based exclusively on historical credit spreads, exploiting the equivalence between Ornsetin-Uhlenbeck and first order Autoregressive processes

**Publication:** Under review

---

**Discount for Lack of Marketability "DLOM" (2025)** BDO UK

**Aim:** Following observation of naive treatment of illiquidity by practitioners, seek to understand core issuesEstablished DLOM models are flawed, overly stylised, or otherwise explosive, meaning practitioners are often left to rely on averages

**Findings:** Formulated a 'Hybrid Put' framework encompassing full extent of downside-risk as well as some lost upside potential, without assuming perfect market-timing ability. Derived analytic approximation and evaluated numerical performance to show solution as well behaved

**Publication:** Under review

---

**SABR Interpolation Error (2025)** BDO UK

**Aim:** Following observation of model error resulting from parameter treatment at non-tenor dates, identify and validate superior alternative

**Findings:** Performed literature review and independent analysis, validating total-variance interpolation and recalibration as more accurate, consistently outperforming linear and cubic SABR parameter interpolation with RMSEs approx. 1.7 and 1.9 times higher, respectively

**Impact:** Motivated further analysis and publication of systematic review and comprehensie evaluation of interpolation frameworks 

**Publication:** Under review 

---

**Hidden Losses during the CME Trading Halt (2025)** Independent Research

**Aim:** Following the 28 Nov 2025 CME trading outage, develop an estimation framework to quantify the hidden losses resulting from the interruption

**Findings:** Developed methodology leveraging treatment of outage as a temporary illiquidity shock, identifying the optimal DLOM model by benchmarking against synthetic outages, and using the optimal model, estimating hidden losses of approximately $10 mln across NASDAQ and S&P e-mini futures

**Impact:** Validated the proposed Hybrid Put Framework as best performing across synthetic outages

**Publication:** Working Paper available; Shared on LinkedIn 

---

**Monte Carlo Scheme Study (2025)** CQF

**Aim:** Derive and compare closed-form solutions and Monte Carlo simulation schemes (Euler-Maruyama and Milstein) for vanilla and exotic options

**Findings:** Numerical results aligned with analytic solutions for certain plan-vanilla and binary options; Milstein diverged from Eueler-Maruyama in barrier and Asian options for certain volatility-tenor regions 

**Further Research:** Investigate the numerical performance and limitations of Henderson and Wojakowski's (2001) symmetry relationship in floating vs. fixed-strike Asian options 

---

**Experimental Fluid Dynamics Dissertation (2022)** University of Warwick

**Aim:** Visualise the effects of uneven structures on highly rotational vortex cores

**Findings:** Designed methodology leveraging Particle Image Velocimetry techniques to identify the presence of inertial waves under particular setups, contributing novel findings to the field

--- 

## quantitative development 

---

**Automated Derivative Valuations Engine (2026)** BDO UK 

**Aim:** Develop and productionise a fully automated derivatives valuation and risk engine

**Impact:** Drastically improved team-wide efficiency, impriving project timelines and turnover, and pitch competitiveness

---

**Automated Convertible Bond Risk Metrics (2026)** BDO UK

**Aim:** Develop an automated system for parameter-specific risk sensitivity metrics for previously unaddressed parametres

**Impact:** Launched new system, minimising model risk and improving result integrity


---

**Black-Karasinski Automation (2026)** BDO UK

**Aim:** Leverage OU/AR(1) equivalency in stochastic credit modelling as outlined in my 2026 BK Parameter Estimation working paper towards an automated system 

**Findings:** Designed and implemented an automated system sourcing Refinitiv historical credit spreads, estimating the appropriate parameters, and generating model-specific risk metrics to be used in subsequent valuations

**Impact:** Addressed existing practitioner limitations, expanding BDO's suite of offerings

--- 

**Automated Reporting System (2025)** BDO UK

**Aim:** Develop a system to automatically generate technical reports, expanding automation pipeline 

**Impact:** Significantly improved team-wide efficiency, freeing junior member time to focus on high-complexity projects

---

## machine learning & systematic trading 

---

**Generating Directional Signal from IV Metrics (2025)** CQF

**Aim:** Develop a machine learning system to predict asset price directionality

**Findings:** Utilised SVM systems to generate a trading signal based on the implied volatility metrics across one-day-to-expiry options, displaying meaningful predictive power (Accuracy: 0.99, Macro F1: 0.97) and yielding out of sample returns 2.1 times greater than buy-and-hold 

---

**Synthetic Derivatives Exchange Arbtirage (2024)** Independent Research 

**Aim:** Develop an automated trading strategy exploiting mispricing of derivatives across crypto-echanges

**Findings:** Strategy successfully identified arbitrage opportunities by identifying mispricing both across exchanges for a given instrument, as well as between particular instruments and their synthesised equivalents.

**Further Research:** Leverage system for dynamic hedging

---

**Optimised Windows Momentum Strategy (2024)** Independent Research 

**Aim:** Design an automated trading system for digital assets, using realised volatility to predict the optimal window configuration for a traditional momentum strategy

**Findings:** Utilised linear regression approach relating realised volatility to tested window-length combinations, achieving approx. 1.7 times greater returns (21%) than a buy-and-hold strategy across the same period in live trading

**Further Research:** Leverage CNNs to evaluate realised volatility across varying degrees of granularity to better capture the asset 'momentum' 

---

**Currency Identification CNN (2021)** University of Warwick

**Aim:** Develop a system to identify a a variety of currency types from a live webcam input

**Findings:** Trained a CNN, which, after achieving a confidence threshold, employs computer vision techniques in tandem to reach an overall accuracy of 96%

