---
name: govt-infra-lenders
description: Framework and peer list for analysing Indian government-owned infrastructure lenders — REC, PFC, IRFC, IREDA, HUDCO, IFCI and similar NBFC-IFCs / public financial institutions. Use when the user asks to discuss, evaluate, compare or value any of these, or asks about power/railway/renewable/urban-infrastructure financiers. For general lender basics (ROA, ROE, leverage, NIM, asset quality, ALM) also apply the nbfc-analysis skill. Not for PSU banks (SBI, PNB — use nbfc-analysis) or retail NBFCs.
---

# Government infrastructure lenders — analysis guide

Companies like **REC** are NBFCs on paper (RBI-registered, usually as
**Infrastructure Finance Companies, NBFC-IFC**), but they behave like
**bond-funded lending arms of the government**. The general `nbfc-analysis`
framework still applies — this guide explains what to read differently and what
extra to check.

> **Golden rule:** for these lenders the questions are (1) will the government
> programmes they fund keep growing, (2) can they hold their margin against
> banks and prepayments, (3) are the few big borrowers (mostly states) paying,
> and (4) what will the government, as owner, take out (dividends, stake sales)?
> Cheap P/E and high dividend yield are normal here — they are not, on their
> own, a reason to buy.

---

## 1. The peer group

### Listed (live figures — Screener, fetched 8-Nov-2026; refresh before use)

| Company (NSE) | What it finances | Govt / parent stake | Price ₹ | Mkt cap ₹ cr | P/E | P/B | Div. yield | ROE | Leverage (assets ÷ equity) | ≈ROA (ROE ÷ leverage) | 5-yr profit CAGR | 3-yr profit CAGR | Last-12-m profit growth | 1-yr share price |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **REC (RECLTD)** | Power: state discoms, generation, transmission, renewables; infra & logistics | 52.63% (PFC) | 297 | 78,180 | 5.2× | 0.82× | 6.2% | 20.1% | 7.7× | ~2.6% | 14% | 14% | −12% | −19% |
| **PFC (PFC)** | Power sector (same business as REC; REC's parent — figures consolidated incl. REC) | 55.99% (Govt of India) | 331 | 1,09,367 | 4.2× | 0.74× | 5.6% | 20.7% | 9.7× | ~2.1% | 17% | 18% | +6% | −13% |
| **IRFC (IRFC)** | Railways: rolling stock & projects leased to the Ministry of Railways | 82.90% | 80.3 | 1,04,836 | 14.2× | 1.73× | 2.6% | 12.8% | 9.2× | ~1.4% | 10% | 3% | +8% | −34% |
| **IREDA (IREDA)** | Renewable energy: solar, wind, hydro, storage, green hydrogen | 71.76% | 111 | 31,275 | 15.9× | 2.18× | 1.2% | 15.6% | 7.1× | ~2.2% | 40% | n/a (listed 2023) | +14% | −25% |
| **HUDCO (HUDCO)** | Housing & urban infrastructure: state agencies, urban bodies, roads, water | 75.00% | 164 | 32,771 | 7.4× | 1.43× | 3.7% | 20.0% | 7.4× | ~2.7% | 20% | 33% | +59% | −29% |
| **IFCI (IFCI)** | Legacy development financier (industry); now small, restructuring | 72.57% | 61.9 | 16,686 | 93× | 1.86× | 0% | 2.0% | 3.0× | ~0.7% | 16% | 41% | −44% | +14% |

Notes:
- P/B computed as price ÷ Screener book value; ≈ROA = Screener ROE ÷ my leverage calculation (FY26 average balance sheet) — approximate.
- PFC is consolidated, so it includes REC.
- IFCI is a **cautionary example** (weak ROE, history of bad loans, government support-dependent) — not a like-for-like peer.

### Unlisted (useful context; cannot be bought)
- **IIFCL** — India Infrastructure Finance Co (long-term infra loans, takeout finance).
- **NaBFID** — National Bank for Financing Infrastructure and Development (new DFI, 2021).
- **NABARD** (rural), **SIDBI** (MSME refinance), **EXIM Bank** (exports), **NHB** (housing refinance).

### Retail-investor proxies sometimes mixed in (not lenders)
- **IRCON, RVNL, NBCC** — construction/EPC companies, not financiers. Do not use this guide for them.

---

## 2. How they differ from retail NBFCs (MAS, Aavas)

| | Govt infra lender (REC-type) | Retail NBFC (MAS-type) |
|---|---|---|
| Borrowers | A few hundred: **state utilities, central PSUs, large projects** | Lakhs of individuals / small businesses |
| Ticket size | ₹100s–1,000s of crore | ₹ lakhs |
| Funding | Domestic **AAA-equivalent** bonds, **54EC capital-gain bonds**, foreign borrowings (ECB), banks | Bank loans, NCDs at AA/A ratings |
| NIM | **2.5–3.5%** (thin) | 6–9%+ |
| Opex | Tiny (a few hundred staff) | Branch-heavy |
| Leverage | 6–10× assets/equity | 3–5× |
| ROE driver | **Leverage** (ROA 1.5–2.7% × 7–10×) | ROA (2.5–4% × 3–5×) |
| Main risk | **Concentration**, policy, margin squeeze, prepayment | Granular defaults, funding access |
| Typical valuation | **0.7–1.5× book**, 4–8× P/E, 3–6% dividend yield | 1.5–5× book |

---

## 3. Analysis framework (apply after nbfc-analysis basics)

### 3.1 Ownership, policy and mandate
- **Government stake** and any planned **offer-for-sale (OFS)** — stake sales add supply and usually cap the price short term (IRFC, IREDA, HUDCO all had OFS/QIP talk).
- **Dividend policy** — the government needs dividends; payouts are usually ≥30% of profit (REC/PFC ~30%). High payout supports yield but slows book growth.
- **Mandate lending** — the company may be asked to fund schemes (e.g. discom liquidity packages, the Revamped Distribution Sector Scheme) at thin margins.
- **Status:** Maharatna / Navratna (autonomy), Public Financial Institution (54EC bond eligibility), RBI layer under scale-based regulation (government NBFCs are kept out of the Upper Layer — verify current rules).
- **Group structure:** REC is a PFC subsidiary — PFC's results include REC; a merger has been discussed in the past.

### 3.2 Who the borrowers are — concentration
- **Split of book:** state sector vs central PSU vs private; generation vs transmission vs distribution vs renewables vs non-power infra.
- **Top 10 / top 20 borrower share** (often 40–60% of the book) and **single-state exposure**.
- **Security:** state-government guarantees, escrow of utility receivables, ability of the Centre to withhold funds from a defaulting state, payment-security rules for power dues (Late Payment Surcharge rules).
- **Private-sector book:** legacy NPAs came mostly from private thermal (coal) plants — check how much private exposure is still on book and how new private renewable loans are being underwritten.

### 3.3 Growth drivers (macro-policy, not branches)
- Power: peak-demand growth, transmission build-out, distribution upgrades (smart meters), renewables targets (500 GW non-fossil by 2030), storage, pumped hydro, nuclear.
- Railways (IRFC): whether the Ministry of Railways keeps borrowing via IRFC or funds capex from the budget — the single biggest driver.
- Urban (HUDCO): state housing and urban infrastructure programmes.
- **Sanctions → disbursements → loan book:** track all three; large sanctions with weak disbursement = slow conversion.
- **Prepayments & refinancing:** states refinance with banks when bank rates fall — this caps book growth (REC FY26: loan book only ~+3%).
- Guidance: disbursement target and loan-book growth guidance each year; check delivery.

### 3.4 Margins — the key swing factor
- **NIM trend** (REC: 3.43% FY26 → 3.22% H1 FY27) and **spread** (yield − cost of funds).
- **Cost of funds** advantage vs banks; share of cheap 54EC bonds; foreign-currency borrowing and **hedging cost / FX losses**.
- **Fixed vs floating** loans and borrowings; repricing lag when rates move.
- **Competition** from banks for state-utility loans compresses yields.
- **IRFC is different:** a **cost-plus leasing model** with the Ministry of Railways — margin is contractually fixed and NPAs are ~nil, so growth depends entirely on new borrowing volumes.

### 3.5 Asset quality
- Gross / Net Stage-3, **Stage-2 trend**, **provision coverage (PCR)** — REC's PCR fell ~72% → ~51% while Stage-2 dropped 80% (Q2 FY27).
- **Resolutions and write-backs** of legacy private NPAs can boost profit (one-offs) — strip them out.
- **Regulatory provisioning:** RBI's project-finance rules (draft 2024, finalised 2025) require higher standard-asset provisions on under-construction projects — check the current rule and its impact.
- Credit cost is usually near zero or negative (write-backs) — so a *rise* in credit cost is a meaningful signal.

### 3.6 Capital, leverage and funding
- **CRAR** (comfortable 20%+) and Tier-1.
- **Leverage 6–10×** is normal; rising leverage + falling NIM = ROE getting riskier.
- **Credit rating** (domestic AAA; international ratings tied to India's sovereign rating).
- **ALM** — long-dated loans (10–20 years) funded by 3–10 year bonds: check refinancing gaps.
- **Concentration exemptions** — government NBFCs often get relaxations on single-borrower limits for state entities; know which apply.

### 3.7 Valuation
- Use **P/B and dividend yield** first; P/E second.
- Justified P/B ≈ (ROE − g) ÷ (cost of equity − g), then apply a **PSU discount** (government control, mandate lending, stake-sale overhang).
- Historic range for REC/PFC: roughly **0.5–1.5× book**; the 2023–24 PSU rally pushed them to the top of that range; 2025–26 de-rated them back.
- Compare **dividend yield vs 10-year G-sec yield** — when the yield gap is wide, downside is usually limited; when it closes, upside is limited.
- **Total return view:** for these stocks, a large part of the return is dividends — model yield + book growth.

### 3.8 Red flags
- [ ] Profit falling YoY for 2+ quarters while the book grows (margin squeeze).
- [ ] NIM falling for 3+ quarters.
- [ ] PCR falling sharply without a matching fall in Stage-3.
- [ ] Rising private-sector exposure at thin spreads.
- [ ] Large sanctions not converting into disbursements.
- [ ] Policy shift moving capex funding to the budget (IRFC risk).
- [ ] Government OFS / QIP announcements (supply overhang).
- [ ] Rising FX/hedging losses.
- [ ] Mandate lending to weak discoms at below-market rates.

---

## 4. Scorecard (fill for every REC-type lender)

| # | Parameter | Value | Benchmark | ✅/⚠️/❌ |
|---|---|---|---|---|
| 1 | Loan-book growth YoY (and guidance) | | 10–15% | |
| 2 | Disbursement growth; sanctions pipeline | | rising | |
| 3 | Profit growth YoY (ex one-offs) | | ≈ book growth | |
| 4 | NIM / spread trend | | stable | |
| 5 | Cost of funds trend | | stable/falling | |
| 6 | ROA | | ≥2% (IRFC-type ≥1.3%) | |
| 7 | Leverage (assets ÷ equity) | | ≤10× | |
| 8 | ROE (as ROA × leverage) | | ≥15% | |
| 9 | Gross / Net Stage-3 | | <2% / <0.5% | |
| 10 | Stage-2 trend; PCR | | falling / >60% | |
| 11 | Top-borrower / state concentration | | falling | |
| 12 | Private-sector share & quality | | controlled | |
| 13 | CRAR / Tier-1 | | >20% | |
| 14 | Rating; FX/hedging exposure | | AAA; hedged | |
| 15 | Government stake changes / OFS | | none pending | |
| 16 | Dividend payout & yield vs 10-yr G-sec | | yield ≥ G-sec | |
| 17 | P/B vs history and peers | | low end of range | |
| 18 | Policy tailwinds for the funded sector | | intact | |

**Verdict:** KEEP / ADD / HOLD / TRIM / EXIT — tie it to growth (book + profit), margin trend and valuation/dividend, not to ROE alone (ROE here is mostly leverage).

---

## 5. Worked example — REC (Q2 FY27, Oct-2026)

- Loan book ₹6.17 lakh cr (+5% QoQ); disbursements ₹53,541 cr (H1 ₹79,207 cr); FY27 target ~₹2 lakh cr; pipeline ~₹2.56 lakh cr sanctioned (₹65–70k cr near disbursement — broker note).
- Profit ₹3,478 cr (−21% YoY); H1 ₹7,541 cr (−15%); NIM 3.22% (vs 3.43% FY26); funding costs higher.
- Stage-2 ₹3,235 cr (−80% YoY); GNPA 0.88% / NNPA 0.20% (Dec-2025, latest found); PCR ~51%.
- Guidance ~10–12% loan growth (Motilal Oswal note; one report says cut to 10–11%).
- ROA ~2.6%, leverage ~7.7×, ROE ~20%; P/E 5.2×, P/B 0.82×, dividend yield ~6.2%.
- Verdict in portfolio: **TRIM 50%** — volumes recovering but profit and margin still falling.

---

## 6. Data sources
- **Screener.in** — P&L, balance sheet, shareholding (use consolidated; PFC includes REC).
- **Investor presentations** — book mix by sector/state, Stage-2/3, PCR, NIM, cost of funds, borrowing mix, CRAR.
- **Earnings-call transcripts** and broker result notes (Motilal Oswal, Emkay, ICICI Sec).
- **Ministry of Power / Railways budget documents** — capex plans and funding route.
- **RBI** — NBFC scale-based regulation, project-finance provisioning rules.
- **Rating rationales** (CRISIL, ICRA, CARE, India Ratings).
- Network note (cloud sessions): screener.in is allowed in the "Market data (Yahoo Finance)" environment; nseindia.com, bseindia.com, careratings.com and broker sites may need allowing.
