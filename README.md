# Affinity-Based Product Segmentation for Product & Portfolio Strategy

This repository presents an end-to-end affinity-based consumer segmentation project that demonstrates how preference data can be translated into concrete product, pricing, and positioning decisions.

The project is structured as a standalone analytics case study, focusing on segmentation, interpretation, and strategic implications rather than academic exposition. It showcases how segmentation can be used not just to describe customers, but to validate and stress-test product strategy.

---

## Problem Context

An initial product optimization exercise identified the following configuration as a profit-maximizing product:

> $30 | 3-hour insulation | 20 oz | Easy Clean | Leak Resistant

This project asks a practical follow-up question:

> *Which types of consumers actually value this product — and what does that imply for portfolio and brand strategy?*

Using affinity-based, preference-driven segmentation, the analysis identifies distinct consumer segments, compares their attribute trade-offs, and translates those insights into actionable recommendations.

---

## Analysis Flow

The analysis follows a structured, decision-oriented workflow that starts from individual consumer preferences and culminates in concrete product, pricing, and positioning recommendations.

The end-to-end flow of the analysis is illustrated below:

![Analysis Flow](affinity_segmentation_flow.png)

Each stage builds on the previous one, ensuring that segmentation and personas remain grounded in observed preference patterns.

---

## Key Insights

- The profit-maximizing product configuration ($30 price, 3-hour insulation, 20 oz capacity, easy clean, leak resistant) is validated by consumer segmentation rather than driven purely by optimization logic.
- Two distinct premium segments converge on the same optimal configuration for different reasons: performance reliability for Brand A and lifestyle-driven convenience for Brand C.
- Brand B explains market share dominance through high price sensitivity, but does not meaningfully contribute to profitability.
- Segmentation acts as a validation layer, confirming that the optimized product reflects genuine preference structures rather than modeling artifacts.

---

## Methodology Overview

- **Inputs:** Individual-level preference data across price, insulation, capacity, cleanability, spill resistance, brand affinity, and demographics
- **Segmentation Approach:** Affinity-based (preference-driven) segmentation
- **Evaluation Logic:**
  - Mean differences relative to the overall population
  - Lift analysis to identify over- and under-indexed attributes
- **Design Principle:** Prioritize interpretability and strategic clarity over black-box clustering

The methodology is intentionally transparent and business-facing.

---

## Segment Insights (Summary & Validation)

- **Brand A – Performance-Driven Quality Seekers**  
  Higher-income, older consumers with a strong emphasis on insulation performance, leak resistance, and durability. Low price sensitivity and high alignment with premium configurations.

- **Brand B – Value-Driven Pragmatists**  
  Highly price-sensitive consumers prioritizing affordability and basic functionality. Drives volume and market share, but not profit.

- **Brand C – Urban Mobility Professionals**  
  A smaller, lifestyle-driven segment valuing cleanability, portability, and spill prevention. Willing to pay a premium when the product fits daily mobility needs.

### Segment A — Performance-Driven Quality Seekers (~40%)

 > **Best-Fit Product:** $30 | 3 hrs | 20 oz | Easy Clean | Leak Resistant

- Higher-income, older, more educated consumers
- Strong emphasis on insulation performance and leak-proof reliability
- Low price sensitivity and strong brand loyalty

**Strategic Takeaway:** This segment fully validates the premium, profit-maximizing configuration. High performance and profitability are aligned.

### Segment B — Value-Driven Pragmatists (~55%)

> **Best-Fit Product:** $10 | 1 hr | 20 oz | Fair Clean | Spill Resistant

- Younger, more price-sensitive consumers
- Focused on affordability and basic functionality
- Weak attachment to premium brands

**Strategic Takeaway:** This segment maximizes volume, not margins. It explains market share dominance without driving profitability.

### Segment C — Urban Mobility Professionals (~5%)

>**Best-Fit Product:** $30 | 3 hrs | 20 oz | Easy Clean | Leak Resistant

- Highly mobile, urban consumers
- Strong preference for cleanability, portability, and spill prevention
- Motivated by lifestyle fit rather than pure performance

**Strategic Takeaway:** Despite its small size, this segment independently reinforces the same premium configuration — for different reasons.

---

## Strategic Implications

- A single premium product configuration can be scaled across multiple segments through differentiated positioning rather than differentiated design.
- Brand B should be treated as a volume and access strategy, while Brands A and C anchor profitability.
- Portfolio strategy should prioritize maintaining premium product integrity while varying messaging to reflect performance-driven versus lifestyle-driven motivations.
- Segmentation confirms that profitability and consumer relevance are not in tension when product design is aligned with real preference patterns.

The analysis highlights the importance of portfolio balance rather than one-size-fits-all product design.

---

## Skills & Concepts Demonstrated

- Preference modeling and attribute importance analysis
- Affinity-based consumer segmentation
- Lift and mean-difference interpretation
- Persona construction
- Translating analytics into product, pricing, and positioning decisions

---

> **This repository demonstrates how segmentation can be used as a strategic tool — not just a descriptive exercise — to validate real-world product decisions.**

---
