<div align="center">

# 🌍 Macro Regime Classification Dashboard

### Economic Cycles • Asset Allocation • Regime-Aware Investing

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FRED-Macro_Data-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Random_Forest-Regime_Classification-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Plotly-Dashboard-3F4F75?style=for-the-badge&logo=plotly">
</p>

<p align="center">
  <b>Expansion</b> • <b>Recovery</b> • <b>Recession</b> • <b>Stagflation</b>
</p>

</div>

---

## Overview

Markets react differently depending on the state of the economy.

Equities thrive during expansions. Bonds often outperform during recessions. Commodities frequently benefit from inflationary environments.

This project builds a macroeconomic intelligence platform that classifies economic regimes using leading and coincident indicators, then maps historical asset performance to each regime to support allocation decisions.

---

## Macro Intelligence Pipeline

<div align="center">

```text
      Economic Indicators
               │
               ▼

      Feature Engineering
               │
               ▼

      Regime Detection
               │
               ▼

      Random Forest

               │

     ┌─────────┼─────────┐

     ▼         ▼         ▼

 Expansion  Recovery  Recession

               │

               ▼

          Stagflation

               │

               ▼

 Asset Allocation Insights
```

</div>

---

## Economic Regime Framework

<div align="center">

```text
              Economy

                  │

                  ▼

        Growth vs Inflation

                  │

      ┌───────────┼───────────┐

      ▼                       ▼

 High Growth            Low Growth

      │                       │

      ▼                       ▼

 Expansion            Recession

      │                       │

      ▼                       ▼

 Recovery            Stagflation
```

</div>

---

## Data Universe

<table>
<tr>
<td width="50%">

### 📊 Growth Indicators

- PMI
- Industrial Production
- GDP Growth
- Yield Curve Slope

</td>

<td width="50%">

### 📈 Inflation Indicators

- CPI
- Core CPI
- Inflation Expectations
- Commodity Trends

</td>
</tr>

<tr>
<td width="50%">

### 👷 Labour Market

- Unemployment Rate
- Payroll Growth
- Labour Participation

</td>

<td width="50%">

### 🏦 Monetary Conditions

- Treasury Yields
- Fed Funds Rate
- Credit Conditions

</td>
</tr>
</table>

---

## Regime Classification Engine

<div align="center">

```text
 CPI
 PMI
 Yield Curve
 Unemployment

      │

      ▼

 Feature Matrix

      │

      ▼

 Random Forest

      │

      ▼

 Regime Prediction
```

</div>

---

## Regime Definitions

### 🟢 Expansion

```text
Growth     ↑
Inflation  Stable
Employment Strong
```

### 🔵 Recovery

```text
Growth     Improving
Inflation  Moderate
Employment Recovering
```

### 🔴 Recession

```text
Growth     Weak
Inflation  Falling
Unemployment Rising
```

### 🟠 Stagflation

```text
Growth     Weak
Inflation  High
Employment Weak
```

---

## Asset Allocation Framework

<div align="center">

```text
 Economic Regime

         │

         ▼

 Historical Returns

         │

         ▼

 Asset Performance

         │

         ▼

 Allocation Decisions
```

</div>

---

## Asset Class Analysis

### Regime Overlay

<div align="center">

```text
          Regime

             │

             ▼

 ┌───────────┼───────────┐

 ▼           ▼           ▼

Equities   Bonds   Commodities

             │

             ▼

 Historical Performance
```

</div>

The dashboard reveals how different asset classes historically behaved under each economic environment.

---

## Machine Learning Workflow

<div align="center">

```text
 Historical Macro Data

           │

           ▼

 Feature Engineering

           │

           ▼

 Random Forest Training

           │

           ▼

 Regime Labels

           │

           ▼

 Classification Model
```

</div>

---

## Regime Transition Analysis

<div align="center">

```text
 Expansion
      │
      ▼

 Slowdown

      │
      ▼

 Recession

      │
      ▼

 Recovery

      │
      ▼

 Expansion
```

</div>

Understanding regime transitions is often more valuable than identifying the current regime itself.

---

## Asset Performance Dashboard

### Example Framework

```text
Expansion

Equities      ██████████
Bonds         ███
Commodities   █████

Recession

Equities      ██
Bonds         █████████
Commodities   ███
```

---

## System Architecture

<div align="center">

```text
┌─────────────────────────┐
│ FRED Economic Data      │
└────────────┬────────────┘
             │
             ▼

┌─────────────────────────┐
│ Data Engineering Layer  │
└────────────┬────────────┘
             │
             ▼

┌─────────────────────────┐
│ Regime Classification   │
├─────────────────────────┤
│ Feature Engineering     │
│ Random Forest           │
│ Regime Detection        │
└────────────┬────────────┘
             │
             ▼

┌─────────────────────────┐
│ Asset Return Engine     │
└────────────┬────────────┘
             │
             ▼

┌─────────────────────────┐
│ Plotly Dashboard        │
└─────────────────────────┘
```

</div>

---

## Dashboard Components

| Module | Purpose |
|----------|---------|
| Regime Monitor | Current Economic State |
| Macro Indicators | Economic Dashboard |
| Classification Engine | ML Predictions |
| Transition Matrix | Regime Shifts |
| Asset Allocation View | Portfolio Insights |
| Historical Analysis | Regime Backtesting |
| Performance Overlay | Asset Returns by Regime |

---

## Quantitative Foundation

<div align="center">

```text
      Macroeconomics

            │

            ▼

 Economic Indicators

            │

            ▼

 Machine Learning

            │

            ▼

 Regime Classification

            │

            ▼

 Asset Allocation
```

</div>

---

## Example Research Workflow

<div align="center">

```text
 FRED Data

      │

      ▼

 Indicator Selection

      │

      ▼

 Regime Detection

      │

      ▼

 Asset Mapping

      │

      ▼

 Allocation Signals
```

</div>

---

## Technology Stack

```text
Python
│
├── Pandas
├── NumPy
├── Scikit-Learn
├── Plotly Dash
└── FRED API
```

---

## Real-World Applications

### Macro Hedge Funds

- Regime Detection
- Tactical Allocation
- Economic Forecasting

### Global Asset Allocators

- Asset Allocation
- Portfolio Rotation
- Risk Management

### Sovereign Wealth Funds

- Strategic Asset Allocation
- Long-Term Portfolio Planning
- Economic Scenario Analysis

---

## Skills Demonstrated

✅ Macroeconomic Analysis

✅ Machine Learning

✅ Random Forest Classification

✅ Economic Regime Detection

✅ Asset Allocation

✅ Financial Data Engineering

✅ FRED API Integration

✅ Quantitative Research

✅ Dashboard Development

✅ Investment Strategy Design

---

## Repository Structure

```text
macro-regime-classification-dashboard/
│
├── data/
│
├── indicators/
│   ├── cpi.py
│   ├── pmi.py
│   ├── unemployment.py
│   └── yield_curve.py
│
├── regime_engine/
│   ├── classifier.py
│   └── transitions.py
│
├── asset_analysis/
│
├── dashboard/
│
├── notebooks/
│
└── README.md
```

---

<div align="center">

### 🌍 Understand The Economy. Position The Portfolio.

*"Markets move daily. Regimes move portfolios."*

</div>
