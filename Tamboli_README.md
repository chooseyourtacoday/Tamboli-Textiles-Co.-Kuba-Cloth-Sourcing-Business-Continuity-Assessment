# DRC Conflict Supply Chain Risk Analysis
## Tamboli Textiles Co. — Kuba Cloth Sourcing & Business Continuity

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![pandas](https://img.shields.io/badge/pandas-Analysis-150458?logo=pandas)
![Excel](https://img.shields.io/badge/Excel-Risk%20Report-217346?logo=microsoft-excel)
![Conflict Data](https://img.shields.io/badge/Data-ACLED%20%7C%20UN%20OCHA-red)

---

## The Scenario

> *"A fabric and textile company imports Kuba cloth from the Kuba people in the Kasai region of the DRC. The ongoing civil war is expanding. The company wants to understand how this will affect their sales — and for ethical and humanitarian reasons, they do not want to use PMCs."*

Tamboli Textiles Co. (fictional) sources artisan textiles from five African countries, with **60% of revenue** tied to Kuba cloth from the Kasai region of the Democratic Republic of the Congo. The M23 conflict — concentrated in eastern DRC with Rwandan backing — is expanding. The Kasai region experienced its own devastating conflict in 2016-2018, which displaced 1.4 million people and provides a historical baseline for supply chain disruption.

This analysis asks and answers: **What do we do, how bad could it get, and what are our obligations to the people who make our products?**

---

## About Kuba Cloth

The Kuba Kingdom, centered in the Kasai region between the Sankuru and Kasai rivers, is one of Central Africa's most historically significant civilizations. Kuba cloth — woven from raffia palm fibers using techniques passed down for centuries — is among the most recognized African textile art forms globally:

- **"Kasai Velvet"** — the cut-pile variety, named by British Museum curator Emil Torday
- Woven by men (base cloth) and embroidered by women (surface decoration) — a communal art form
- Used in royal ceremonies, weddings, and funerals for centuries
- Retail price: $95–$275 per piece in Western markets
- In collections at the Smithsonian, Metropolitan Museum, Musée du quai Branly
- **At risk**: younger generations increasingly leaving weaving for wage labor — knowledge transmission threatened

---

## What This Analysis Covers

### Section 1: Revenue Exposure Assessment
- 60% DRC revenue concentration identified as core business risk
- 2017-2018 Kasai crisis visible in revenue data — historical precedent for disruption impact (~55% decline over 18 months)

### Section 2: Conflict Proximity Analysis
- Three DRC suppliers rated by distance to active conflict front
- SUP-003 (Kasai-Oriental): 195km from M23 advance — elevated risk
- SUP-001/002 (Kasai-Central): 280-310km — watch status

### Section 3: Financial Scenario Modeling
Four scenarios with probability estimates and revenue impact:

| Scenario | Probability | DRC Revenue Impact | Annual $ Impact |
|---|---|---|---|
| Status Quo | 30% | 0% | $0 |
| Moderate Escalation | 45% | -40% | -$116,400 |
| Severe Escalation | 20% | -85% | -$247,350 |
| Conflict at Kuba Homeland | 5% | -100% | -$291,000 |

Expected value impact: **-$103,000** (probability-weighted)

### Section 4: Humanitarian Impact Assessment
This section is deliberate. The analysis explicitly addresses what happens to artisan partners under each scenario and what the company's obligations are — fair trade pricing, emergency fund, NGO partnership, diaspora development framed as expansion not replacement.

### Section 5: Diaspora Supplier Network
Four Kuba diaspora collectives identified in Brussels, Paris, Brooklyn, and London:
- Combined capacity: 415 units/year (63% of current DRC volume)
- Cost premium: +35–55% vs DRC sourcing
- Lead time: 14-21 days vs 90 days from DRC
- Net advantage of proactive diaspora pivot over Scenario B: ~$228,000

### Section 6: Recommendation
**PAUSE + PIVOT** — Begin diaspora onboarding now, before disruption occurs. 90-day lead times mean waiting until the conflict arrives is already too late.

---

## Deliverables

| File | Contents |
|---|---|
| `drc_supply_chain_analysis.ipynb` | Full 6-section analysis notebook |
| `Tamboli_DRC_Risk_Report.xlsx` | 4-sheet Excel risk report |
| `generate_data.py` | Synthetic data generator |

**Excel sheets:**
- Risk Dashboard — KPI indicators with traffic light status
- Scenario Model — Financial impact with probability-weighted expected value formula
- Supplier Status — DRC suppliers + diaspora network comparison
- Revenue History — Full 5-year product revenue with Kasai disruption visible

---

## Data Sources

All company, supplier, and revenue data is synthetic. Conflict data is grounded in real events:

- **ACLED** — Armed Conflict Location & Event Data Project
- **UN OCHA** — Humanitarian situation reports
- **CFR Global Conflict Tracker** — DRC conflict timeline
- **UNHCR** — Displacement statistics (7.3M IDPs as of 2024)
- **British Museum / Smithsonian** — Kuba textile cultural documentation
- **Africa Direct / Meekono** — Artisan supply chain and cultural context

---

## Why This Project Exists

Most supply chain risk analyses stop at the financial model. This one doesn't. The Kuba people are not an abstraction — they are artisans whose livelihood, cultural tradition, and physical safety are all implicated in sourcing decisions made in Austin, Texas. A complete analysis has to hold both the P&L and the humanitarian dimension simultaneously.

That's what real business analysis looks like when the supply chain runs through a conflict zone.

---

## Author

**Alejandro (Alex) Molina**
GitHub: [@chooseyourtacoday](https://github.com/chooseyourtacoday)
Location: Dallas–Fort Worth, TX
Certifications: Codecademy BI Data Analyst | Databricks Analyst Associate (In Progress)
