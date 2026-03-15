# Price Optimization & Complementary Pricing Models

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel%20%2B%20Solver-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-Pricing%20Analytics-E8472A?style=flat)
![Method](https://img.shields.io/badge/Method-Elasticity%20%7C%20Optimization-0078D4?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-2ea44f?style=flat)

## Overview

Two pricing models built using demand elasticity theory and Excel Solver optimization — one for single-product profit maximization and one for **complementary product pricing** (where two products have interdependent demand). This is the type of analysis used by e-commerce pricing teams, retail analytics groups, and fintech companies optimizing subscription bundles.

---

## Models Included

### Model 1 — Single Product Price Optimization (Vitality Inc.)
**Business problem:** Vitality Inc. sells magnetic bracelets across 6 stores at 3 price points. Find the price that maximizes total profit.

**Approach:**
- Modeled demand as a linear function of price using store-level test data
- Derived demand slope: **-2,848,000 units per $1 price increase**
- Built profit function: `Total Profit = (Price - Unit Cost) × Demand(Price)`
- Used Excel Solver to find profit-maximizing price point
- Validated across multiple price scenarios

**Result:** Identified optimal price point that maximized profit vs. the three tested price points, with full sensitivity table showing profit at every $0.50 increment.

---

### Model 2 — Complementary Product Pricing (Dress Shoes + Belt)
**Business problem:** Two products with cross-price elasticity — raising the price of one reduces demand for both. Find the joint pricing strategy that maximizes combined profit.

| Product | Elasticity | Current Price | Current Demand | Unit Cost |
|---------|-----------|---------------|----------------|-----------|
| Dress Shoes | 7.4 | $189 | 300/mo | $90 |
| Belt | 12.5 | $50 | 0.88 units/shoe | $7 |

**Approach:**
- Modeled demand interdependence using cross-price elasticity coefficients
- Built joint profit function capturing both direct and cross-product effects
- Ran Excel Solver on the combined objective function
- Compared optimized pricing vs. naive single-product optimization to show the cost of ignoring complementarity

---

## Key Findings

> Optimizing dress shoe and belt prices **independently** vs. **jointly** produces meaningfully different results — naive single-product optimization underprices the belt by ignoring the multiplicative effect of shoe sales volume on belt demand. Joint optimization captures an additional ~15% margin vs. treating them as separate products.

---

## Skills Demonstrated

- Price elasticity modeling (own-price and cross-price)
- Profit maximization using Excel Solver (nonlinear optimization)
- Demand function estimation from empirical price-test data
- Complementary goods pricing theory applied to real product scenarios
- Sensitivity analysis and scenario comparison

---

## Relevance to Industry Roles

| Role | Relevance |
|------|-----------|
| Pricing Analyst | Core skillset — elasticity + optimization |
| E-commerce Analytics | Direct application to product bundle pricing |
| Data Scientist (Retail) | Foundation for ML-based dynamic pricing |
| Analytics Engineer | Pricing model pipeline design |

---

## Tools Used

- Microsoft Excel
- Excel Solver (nonlinear optimization)
