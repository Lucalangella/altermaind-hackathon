# Sample Contracts Guide — What the AI Extracts & Dashboard Visualizes

## Portfolio Summary

| # | Client | Industry | Annual Value | Duration | Expires | Key Anomalies |
|---|--------|----------|-------------|----------|---------|---------------|
| 001 | Meridian Group S.p.A. | Manufacturing | €417K | 36 mo | Jan 2027 | — Standard contract |
| 002 | Nexus Technologies GmbH | Technology | €1,075K | 48 mo | Feb 2028 | 22% discount, 99.99% SLA, unlimited liability |
| 003 | Salus Healthcare Network | Healthcare | €270K | 24 mo | May 2026 | Data residency, no auto-renewal |
| 004 | Aurora Bank S.p.A. | Finance | €900K | 60 mo | Aug 2028 | Uncapped AML penalty, 300% liability |
| 005 | Verde Energia S.p.A. | Energy | €170K | 12 mo | Jan 2026 | Standard, expiring soon |
| 006 | Logistica Express S.r.l. | Logistics | €88K | 24 mo | Apr 2026 | 35% discount, missing clauses, below-standard SLA |
| 007 | TelcoItalia Plus S.p.A. | Telecom | €1,230K | 36 mo | Nov 2026 | Framework agreement, minimum commitment |
| 008 | Fashion House Belmonte | Retail/Luxury | €428K | 36 mo | Jan 2028 | Net 90 days, seasonal SLA, unlimited trade secret liability |
| 009 | Regione Campania | Government | €265K | 24 mo | Jul 2026 | Public procurement rules, PNRR funding |
| 010 | Nexus Technologies (Addon) | Technology | +€395K | Co-terminus | Feb 2028 | Discount increased to 25%, AI accuracy penalties |

**Total Portfolio Annual Revenue: ~€5,238,000**

---

## Dashboard View → Contract Mapping

### 1. Strategic Client Concentration

**What to visualize:** Revenue share pie/treemap chart.

| Client | Annual Value | % of Portfolio |
|--------|-------------|----------------|
| Nexus Technologies (002+010) | €1,470,000 | 28.1% |
| TelcoItalia Plus (007) | €1,230,000 | 23.5% |
| Aurora Bank (004) | €900,000 | 17.2% |
| Fashion House Belmonte (008) | €428,000 | 8.2% |
| Meridian Group (001) | €417,000 | 8.0% |
| Salus Healthcare (003) | €270,000 | 5.2% |
| Regione Campania (009) | €265,000 | 5.1% |
| Verde Energia (005) | €170,000 | 3.2% |
| Logistica Express (006) | €88,000 | 1.7% |

**Insight:** Top 3 clients = 68.8% of revenue → high concentration risk.

---

### 2. Critical Contract Pipeline

**What to visualize:** Timeline/Gantt chart with color-coded urgency.

| Urgency | Contract | Expires | Auto-Renewal | Action Needed |
|---------|----------|---------|--------------|---------------|
| 🔴 CRITICAL | Logistica Express (006) | Apr 14, 2026 | Yes (30-day opt-out) | Expires in ~3 weeks |
| 🟡 UPCOMING | Verde Energia (005) | Jan 31, 2026 | Yes (60-day notice) | Already past opt-out window, auto-renewed |
| 🟡 UPCOMING | Salus Healthcare (003) | May 31, 2026 | No | Must actively negotiate renewal |
| 🟢 MONITORING | Regione Campania (009) | Jul 31, 2026 | No (optional 12mo extension) | Government renewal process takes time |
| 🟢 MONITORING | TelcoItalia Plus (007) | Nov 14, 2026 | No | New framework negotiation needed |

---

### 3. Commercial Condition Anomalies

**What to visualize:** Deviation-from-standard table with severity indicators.

| Contract | Anomaly | Standard | Actual | Severity |
|----------|---------|----------|--------|----------|
| 006 Logistica | Discount: 35% | Max 20% promo | 35% promo | HIGH |
| 002+010 Nexus | Discount: 25% | Max 15% volume | 25% strategic | HIGH |
| 008 Belmonte | Payment terms: Net 90 | Net 30 | Net 90 | MEDIUM |
| 006 Logistica | Missing late payment clause | Always included | Omitted | MEDIUM |
| 006 Logistica | Missing termination for convenience | Standard clause | Omitted | MEDIUM |
| 006 Logistica | SLA uptime: 99.0% | 99.5% (SME) | 99.0% | LOW |
| 002 Nexus | SLA uptime: 99.99% | 99.5% | 99.99% | HIGH (cost) |
| 008 Belmonte | Seasonal enhanced SLA | Not offered | Custom | MEDIUM |
| 006 Logistica | Auto-renewal opt-out: 30 days | 90 days | 30 days | LOW |

---

### 4. Product/Service Trends

**What to visualize:** Stacked bar chart showing product adoption over time.

| Product/Service | # Contracts | Total Annual Revenue | Trend |
|----------------|-------------|---------------------|-------|
| Cloud Platform (all editions) | 8 | €2,398,000 | Core product, universal |
| AI/ML Solutions | 3 (002, 007, 010) | €675,000 | Growing — newest contracts |
| Data Analytics | 3 (001, 003, 004) | €280,000 | Stable |
| Cybersecurity | 1 (002) | €95,000 | Emerging |
| Consulting/Professional Services | 2 (007, 008) | €108,000+ T&M | Stable |
| Custom Development | 3 (003, 009, 007) | varies | Project-based |
| Training | 3 (001, 005, 009) | €37,000 | Low-value add-on |

**Insight:** AI/ML is the fastest-growing category — drove the Nexus expansion (010) and appears in the 2 largest accounts.

---

### 5. Risk & Exposure Dashboard

**What to visualize:** Risk matrix (likelihood × impact) or severity-sorted list.

| Risk | Contract | Severity | Financial Exposure |
|------|----------|----------|--------------------|
| Unlimited liability (AML failure) | 004 Aurora Bank | CRITICAL | Uncapped |
| Unlimited liability (data breach) | 002 Nexus | CRITICAL | Uncapped |
| Unlimited liability (trade secrets) | 008 Belmonte | CRITICAL | Uncapped |
| Uncapped SLA credits | 002 Nexus | HIGH | Uncapped |
| Data breach penalty (€500K/incident) | 002 Nexus | HIGH | €500K/incident |
| Data breach penalty (€250K/incident) | 004 Aurora Bank | HIGH | €250K/incident |
| Fashion Week downtime penalty | 008 Belmonte | HIGH | €50K/incident |
| Regulatory fine pass-through | 004 Aurora Bank | HIGH | Up to €1M |
| CV false positive liability | 010 Nexus Addon | HIGH | Up to €500K |
| Client concentration (top 3 = 69%) | Portfolio-wide | HIGH | €3.6M at risk |
| Missing contract clauses | 006 Logistica | MEDIUM | Operational |
| Non-standard payment terms (Net 90) | 008 Belmonte | MEDIUM | Cash flow |
| IP joint ownership ambiguity | 002 Nexus | MEDIUM | Legal |
| PNRR compliance requirements | 009 Regione Campania | MEDIUM | Reputational |
| Below-standard SLA delivery | 006 Logistica | LOW | Customer sat. |

---

## Extraction Fields Summary

The AI should extract these fields from every contract (see `extraction_schema.json` for the full JSON schema):

**Core Identity:** contract_id, client_name, client_industry, contract_type
**Financial:** annual_value, total_value, currency, discount (% + type + is_anomalous), payment_terms (frequency, net_days, late_interest)
**Temporal:** start_date, end_date, duration, auto_renewal (enabled, period, opt-out_notice)
**SLA:** uptime_guarantee, response_times (P1/P2/P3), resolution_times, sla_credits, is_non_standard
**Risk:** penalty_clauses (trigger, type, amount, severity), liability_cap, unlimited_liability_areas, indemnification
**Termination:** notice_period, convenience_termination, early_termination_fee
**Products:** list of products/services with category and pricing
**Compliance:** jurisdiction, data_residency, regulatory_requirements
**Flags:** auto-generated risk flags based on extraction results
