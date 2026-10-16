# 🚚 Inbound Supplier Performance & TCO Diagnostic
### Uncovering Hidden Financial Leakage in Offshore Sourcing Networks

---

## 📌 Executive Summary (BLUF)
An end-to-end diagnostic of **10,000 Purchase Orders (POs)** across **15 global suppliers** revealed a critical operational breakdown: an **Inbound OTIF (On-Time In-Full) of just 36.93%**, which triggered **$5.29M USD in emergency expedited freight costs**.

While Contract Purchase Prices ($PPV$) suggested that Asian sourcing was up to 40% cheaper than local alternatives, the severe lead time volatility ($\sigma = 18\text{ days}$) from offshore suppliers repeatedly forced the operation into air freight contingencies to prevent production stoppages.

A **Total Cost of Ownership (TCO)** evaluation demonstrated that **94.3% of the financial leakage originated in Asia**, eroding nominal contract savings. To resolve this, a two-phase strategic proposal was designed: a **60/40 Dual-Sourcing transition to Nearshoring (USA/Mexico)** to reclaim **$3.5M USD in annual freight waste**, followed by a Vendor Development Program to elevate Nearshoring OTIF from 76% to world-class benchmarks (>90%).

---

## 🏗️ Project Architecture & Workflow

```text
inbound-supplier-performance-diagnostic/
├── data/
│   └── inbound_supplier_data.csv        # Synthetic dataset (10,000 POs, 15 suppliers)
├── images/
│   ├── 01_country_otif_vs_freight.png   # Diagnostic chart: Freight Leakage vs OTIF
│   └── 02_tco_contract_vs_landed.png    # Financial impact: Contract Price vs Landed Cost
├── notebooks/
│   └── 01_inbound_supplier_diagnostic.ipynb  # Complete EDA, KPI modeling, and visualizations
├── .gitignore
└── README.md                            # Executive case study