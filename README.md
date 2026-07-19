## 📂 Repository 4: `sustainable-product-design-lca-eco-audit`


```markdown
# Streamlined Life Cycle Assessment & Sustainable Redesign Feasibility Study

## 📌 Project Overview

This repository contains a streamlined Life Cycle Assessment (LCA) and sustainable redesign engineering study conducted via **Ansys Granta EduPack Eco Audit** logic. The study models, quantifies, and evaluates the environmental impacts (energy demand and greenhouse gas emissions) and unit costs of a consumer product (a commercial cat teaser wand) across its complete life cycle. The engineering objective is to replace high-impact, synthetic materials prone to microplastic generation with bio-based natural alternatives without causing manufacturing process friction or expanding commercial costs.

## 📏 System Boundaries & Functional Unit

* **Functional Unit**: One individual cat teaser wand asset manufactured within an automated commercial production batch of 50,000 units.
* **Product Service Life**: 1 Year.
* **System Boundaries**: Encompasses material production, primary manufacturing processing, distribution logistics (modeled as 18,000 km container sea freight transit from production in China to distribution hubs in the UK), product use (negligible energy phase), and end-of-life downcycling disposal pathways.

## 🧪 Comparative Product Material Architecture

The project applies a targeted engineering substitution, keeping the structural handle properties constant while eliminating synthetic textile risks:

| Component | Mass (kg) | Baseline Material/Process | Redesign Material/Process | End-of-Life Parameter |
| :--- | :--- | :--- | :--- | :--- |
| **Wand Handle** | 0.050 | ABS Plastic (Virgin Polymer Injection Molding) | ABS Plastic (Virgin Polymer Injection Molding - Unchanged) | 80% Downcycling Rate |
| **Flexible String** | 0.015 | **Nylon Synthetic Fiber** (Extruded Fabric Production) | **Hemp Natural Fiber Cord** (Continuous Braided Textile Process) | 90% Downcycling Rate |
| **Teaser Link** | 0.020 | Polyester + Synthetic Feathers | Polyester + Synthetic Feathers (Unchanged) | 90% Downcycling Rate |

## 📊 Streamlined Eco Audit Environmental Results

By substituting synthetic nylon with natural braided hemp cord, the product profile yields significant lifecycle optimizations across the 50,000-unit commercial batch:

| Lifecycle Performance Metric | Baseline Product Profile (ABS + Nylon) | Redesign Product Profile (ABS + Hemp) | Quantifiable Environmental Change |
| :--- | :--- | :--- | :--- |
| **Total Embodied Energy (MJ)** | 3.99e+05 | 3.19e+05 | **~20% Total Reduction** |
| **Climate Change Impact (kg CO2-eq)** | 1.95e+04 | 1.46e+04 | **~25% Total Reduction** |
| **Total Production Batch Cost (£)** | 1.165e+04 | 1.130e+04 | **~3% Financial Savings** |

### Hotspot Diagnostic Breakdown

The redesign data reveals that the **Material Production phase dominates the life cycle (78.8% of energy; 67.4% of climate impact)**, followed by the **Manufacturing phase (18.3% of energy; 27.9% of climate impact)**. Under the baseline architecture, ABS plastic manufacturing and polymer processing remain the single largest asset hotspots.

## ☀️ Renewable Energy Manufacturing Decarbonization Scenario

To further target the manufacturing energy emissions hotspot (5.83e+04 MJ total energy demand), a technical engineering scenario was calculated to completely offset grid-derived electricity using on-site solar photovoltaic infrastructure:

* **Total Manufacturing Electricity Required**: 16,194 kWh.
* **Solar PV Regional System Yield Assumption**: 894 kWh/kW-year (based on standard 10.2% regional solar load factor parameters).
* **Required Dedicated Solar PV Array Capacity**: **18.1 kW**.
* **Indicative Project CAPEX**: ~£22,738 (derived at a capital benchmark installation rate of £1,256.23 per kW).
* **Avoided Scope 2 Indirect Carbon Emissions**: **~3,353 kg CO2e** per batch run using standardized UK grid conversion indicators.
