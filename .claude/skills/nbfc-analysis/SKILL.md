---
name: nbfc-analysis
description: Framework and checklist for analysing an Indian NBFC, housing finance company, microfinance lender or bank (e.g. MAS Financial, Aavas, Five-Star, Bajaj Finance, SBI). Use whenever the user asks to discuss, evaluate, compare or value a lender, or asks about lender metrics such as ROA, ROE, NIM, GNPA, credit cost, leverage, capital adequacy or ALM. Not needed for non-financial companies.
---

# Analysing an NBFC (or bank) — reference framework

Use this guide whenever we analyse a lender. Work through every section, fill
the scorecard at the end, and add or update the stock in `WATCHLIST.md`.

> **Golden rule:** a good lender = **steady ROA + strong capital + low, stable
> bad loans + diversified funding**. ROE is the *result* of these, never a
> standalone reason to buy. ROE can be inflated or flattered (see §3).

---

## 1. How an NBFC makes money

An NBFC (non-banking financial company) borrows money (bank loans, bonds/NCDs,
commercial paper, securitisation) and lends it at a higher rate. Unlike a bank,
most NBFCs **cannot take public deposits**, so they live on borrowed money and
must manage liquidity carefully.

**"Revenue" for a lender = Total income**, made of:
1. **Interest income on loans kept on its own books** — usually 80–90%.
2. **Income on loans sold to banks** (direct assignment / co-lending). Under
   Ind AS, the expected gain is often booked **upfront on the day of sale**, so
   a quarter with heavy loan sales can show inflated revenue/profit.
3. **Fees** — processing fees, penal charges, servicing fees on sold loans.
4. **Other income** — treasury income on cash and investments.

Revenue alone is misleading: a big chunk goes straight back out as interest.
Read the P&L like this (Screener labels in brackets):

```
Total income                              (Revenue)
− Interest paid on borrowings             (Interest)
= Net interest income + fees              ← the real "gross profit"
− Staff, branches, other opex             (part of Expenses)
− Provisions / write-offs (credit cost)   (part of "Other expenses")
= Profit before tax                       (Financing Profit ≈ PBT)
− Tax (~25%)
= Net profit
```

Worked example — **MAS Financial, last 12 months to Sep-2026** (Screener,
consolidated, ₹ cr): Revenue 2,201 → Interest −954 → Expenses −671 (staff 178,
other 494) → Financing profit 575 (26% margin) → Net profit 423.

**Cash flow:** operating cash flow is normally **negative** for a growing lender,
because new loans disbursed count as an operating outflow, funded by borrowing
(financing inflow). It is only a warning if loan growth has stopped and CFO is
still negative. (MAS: CFO negative in 11 of 12 years; the one positive year was
FY20 when it slowed lending during COVID.)

---

## 2. Return on Assets (ROA) — the most important profitability metric

**ROA = Net profit ÷ average total assets** (average of opening and closing).

It shows how profitable each ₹100 *lent* is, **independent of leverage and of
equity raises**. Steady ROA across cycles = disciplined lending.

Variants:
- ROA on **balance-sheet assets** (standard).
- ROA on **AUM** (includes loans sold to banks but still serviced) — usually a
  little lower; managements often quote this one. Always check which basis.
- **Pre-tax ROA** — removes tax-rate changes (India's tax cut in FY20 lifted
  everyone's post-tax ROA).

| Lender type | Typical ROA |
|---|---|
| Large banks (SBI, PNB) | 0.8–1.2% (>1% good) |
| Private banks (top tier) | 1.5–2% |
| Affordable housing finance | 2.5–3.5% |
| MSME / small-business NBFCs | 2.5–4% |
| Top-tier NBFCs (Bajaj Finance) | 4%+ |

**ROA tree** (per ₹100 of average assets):
```
Yield on loans            e.g. 15–16
− Cost of funds           e.g. −7
= NIM                     e.g. ~8–9 (on assets) 
− Opex                    e.g. −3
− Credit cost             e.g. −1 to −1.5
= Pre-tax ROA             e.g. ~4
− Tax
= ROA                     e.g. ~3
```
When ROA moves, find which line moved.

MAS ROA history (computed from Screener): FY19 4.5% (peak) → FY21 2.9% (COVID,
costly funding post-IL&FS) → flat **~2.9% FY21–FY26**. Management targets ~3%.

---

## 3. Return on Equity (ROE) — useful, but NOT a standalone factor

**ROE = Net profit ÷ average shareholders' equity.**

**DuPont: ROE = ROA × Leverage** (leverage = average assets ÷ average equity).
ROE can only rise if each loan earns more (ROA ↑) or the lender borrows more
against its capital (leverage ↑).

### Why ROE alone can be misleading / manipulated
1. **Leverage inflates ROE.** Borrowing more against the same equity raises ROE
   *and* risk. Example: SBI ROE ~19% comes from ROA ~1.1% × leverage ~17×;
   MAS ROE ~13.5% comes from ROA ~2.9% × leverage ~4.7×. MAS earns more than
   twice as much per loan; SBI just runs with far less equity.
2. **Under-provisioning inflates ROE.** Delaying recognition of bad loans keeps
   profit — and ROE — high until losses surface. Yes Bank (~FY18) and DHFL
   looked profitable before collapsing; the warnings were in asset quality and
   funding, not ROE.
3. **Upfront gains on loans sold** (Ind AS) can front-load profit.
4. **One-offs** (stake sales, tax refunds, recoveries of written-off loans)
   distort a single year. (IDBI's Q2FY27 profit looked −39% only because the
   prior year had a one-off gain.)
5. **Capital raises temporarily depress ROE** even when the business is fine
   (MAS 2024 QIP: ROE 15.4% → 13.5%). Don't punish balance-sheet strengthening.
6. **IPO / pre-listing distortion:** tiny pre-IPO equity gives absurd ROE
   (MAS FY16 45%) that collapses after listing — not a real decline.
7. **Backward-looking:** says nothing about the quality of loans made today.

### When ROE is useful
- It is what shareholders actually earn and **drives the price-to-book multiple**.
- **Sustainable growth ≈ ROE × (1 − payout).** If loan growth runs well above
  ROE, the lender will need fresh equity every few years (dilution). MAS: ~23%
  growth vs ~13.5% ROE → raised equity in 2017 (IPO) and 2024 (QIP).
- Compare ROE to the **cost of equity (~13–14% in India)**. ROE at or below it
  earns no valuation premium.

Always read ROE **together with** ROA, leverage, asset quality and capital.

---

## 4. Leverage / Debt-to-Equity

- **Debt-to-equity = Borrowings ÷ Shareholders' equity.**
- **Leverage (assets ÷ equity)** is the DuPont version (~D/E + 1).

| Lender type | Comfortable D/E |
|---|---|
| MSME / unsecured-heavy NBFC | 3–5× |
| Housing finance / secured | 5–8× |
| Banks (deposit funded) | 10–15×+ (regulated by capital ratios instead) |

Higher leverage = higher ROE but thinner loss cushion. Rising leverage with
falling ROA is a red flag (management chasing ROE).
MAS (Sep-2026): borrowings ₹11,787 cr ÷ equity ₹3,221 cr ≈ **3.7×** (conservative).

**What equity is:** total assets − total liabilities = shareholders' claim.
= Share capital (shares × face value) + Reserves (securities premium from
IPO/QIP + retained profits + RBI statutory reserve, ≥20% of profit).
Equity is *not* cash — it is lent out alongside borrowings. It absorbs losses
first, and RBI caps lending at a multiple of it.
**Book value per share = equity ÷ shares** (MAS Sep-26: 3,221 ÷ 18.1 cr = ₹178).

---

## 5. NIM, yield, cost of funds, spread

- **Yield on advances** = interest income ÷ average loans.
- **Cost of funds (CoF)** = interest expense ÷ average borrowings.
- **Spread** = yield − CoF.
- **NIM (Net Interest Margin)** = (interest income − interest expense) ÷ average
  interest-earning assets (or AUM). The core earning power.

| Lender | Typical NIM |
|---|---|
| Banks | 3–4% |
| Housing finance | 4–6% |
| MSME / vehicle NBFCs | 6–9% |
| Microfinance / unsecured | 10%+ |

Watch: CoF rising faster than yield (squeeze), rating changes (AA vs AAA costs
~0.5–1%), RBI rate cycle, share of fixed vs floating loans.
MAS: CoF ~9.2% (Q2FY27) guided to 9.4–9.5% → margin headwind. Interest is ~43–46%
of revenue (vs 37% in FY19) — this is the main reason ROA fell from 4.5% to 2.9%.

---

## 6. Operating efficiency

- **Cost-to-income** = opex ÷ (NII + fees). Lower is better (<35–40% good for NBFCs).
- **Opex-to-AUM** — typically 2–4% for branch-heavy MSME lenders.
- Rising opex can be investment (new branches) or inefficiency — check whether
  AUM growth follows.

---

## 7. Asset quality — where lenders actually fail

- **Gross NPA / Gross Stage-3** = loans overdue 90+ days ÷ total loans.
- **Net NPA / Net Stage-3** = after provisions.
- **Stage-2** (30–90 days overdue) — early warning of future NPAs.
- **Provision Coverage Ratio (PCR)** = provisions ÷ gross NPA (>50–70% good).
- **Credit cost** = provisions + write-offs ÷ average loans (<1% banks;
  <1.5–2% MSME NBFCs).
- **Write-offs** — high write-offs can make GNPA look artificially low; always
  check GNPA *and* write-offs *and* credit cost together.
- **Collection efficiency** — % of dues collected (should be 98%+ for most books).
- **Restructured book** — loans given relief; may hide stress.

| | Comfortable |
|---|---|
| Gross NPA | <3% (MSME up to ~3.5%) |
| Net NPA | <1–1.5% |
| Credit cost | <1.5% |

Proxy on Screener when NPA rows are blank: **"Other expenses" as % of revenue**
(usually includes provisions). MAS: 15% (FY24) → ~24% (Q2FY27) — the main
thing to watch. MAS guides Gross Stage-3 at 2.5–2.75%.

---

## 8. Capital adequacy

- **CRAR / CAR** = capital ÷ risk-weighted assets. RBI minimum **15%** for NBFCs
  (Tier-1 ≥ 10%). Comfortable: 18–25%+.
- Banks: **CET1** (core equity) >12% comfortable; CRAR minimum ~11.5%.
- Low capital + high growth → near-term equity raise (dilution).
- RBI raised risk weights on bank loans to NBFCs and on unsecured consumer
  credit in Nov-2023 — sector-wide headwind; check the latest RBI rules.

---

## 9. Funding & liquidity (ALM) — what kills NBFCs fastest

IL&FS (2018) and DHFL (2019) failed on funding/liquidity before asset quality
was fully visible.

Check:
1. **Borrowing mix** — term loans vs NCDs vs CP vs securitisation vs CC/OD.
   Too much short-term **commercial paper** funding long loans = danger.
   MAS (Mar-2026, CARE): term loans 62.7%, capital-market instruments 22.6%,
   CC/OD 14.3%, PTC 0.5%.
2. **Number and type of lenders** — 40+ lenders, PSU + private banks + DFIs
   (SIDBI, NHB) = diversified. MAS: 40+ incl. SBI, SIDBI, BoB, Union, Canara,
   PNB, HDFC Bank, IndusInd.
3. **Credit rating & outlook** — AAA/AA+ cheap funding; AA- decent; A or below
   costly/fragile; watch for downgrades or "negative outlook".
   MAS: CARE AA- (Stable), CP A1+ (Jun-2026).
4. **Liquidity Coverage Ratio (LCR)** = high-quality liquid assets ÷ 30-day
   stressed net outflows; RBI minimum 100%. MAS Mar-2026: 342%.
5. **Cash + liquid investments + undrawn sanctioned lines** vs next 3–12 months
   of debt repayments. MAS Sep-2026: cash ₹990 cr + investments ₹929 cr.
6. **ALM maturity buckets** — cumulative positive gaps in every bucket up to
   1 year is the minimum; MAS shows positive gaps up to 5 years.
7. **Off-book share** — loans sold to banks (direct assignment/co-lending)
   reduce funding need; CARE expects MAS ≤ ~25% of AUM off-book.

Disclosures: company website "Public disclosure on liquidity risk" / LCR PDFs
(quarterly), rating rationales (CARE, ICRA, CRISIL, India Ratings, Acuité).

---

## 10. Growth quality

- **AUM growth** and **disbursement growth** (YoY, QoQ).
- **On-book vs off-book** split.
- **Growth vs ROE**: growth far above ROE ⇒ future dilution.
- Growth should be **steady (15–25%)** — very fast growth (40%+) in risky
  segments often precedes NPA spikes (watch microfinance/unsecured).
- **Profit growth should track AUM growth**; if profit grows much faster, look
  for one-offs, lower provisions or upfront DA gains.
- Consistency: MAS grew profit in 13 consecutive quarters; revenue +21–29% YoY
  every quarter.

---

## 11. Business mix, collateral and concentration

- **Secured vs unsecured share** — secured (property, vehicle, gold) recovers
  better in a downturn; unsecured earns more but defaults first.
- **Collateral by product:**
  - Loan against property / secured business loan → mortgage (LTV up to ~90% is aggressive; <60% conservative)
  - Vehicle loans → hypothecation of vehicle
  - Home loans → mortgage of house
  - Loans to partner NBFCs/MFIs → hypothecation of the partner's receivables (+ cash collateral / first-loss guarantee)
  - Unsecured MSME → none (cash-flow based)
- **Segment risk ranking (high → low):** microfinance / unsecured personal >
  MSME unsecured > used vehicle > MSME secured (LAP) > gold > affordable housing > prime housing.
- **Geographic concentration** — a single state >40–50% of AUM is a risk
  (floods, politics, local stress). MAS is Gujarat-heavy.
- **Partner / channel concentration** — lending through other NBFCs spreads reach
  but a partner failure can turn a whole pool bad at once.
- **Ticket size** — smaller tickets = more granular, but costlier to service.

---

## 12. Management, governance, ownership

- Promoter track record through crises (2008, 2016 demonetisation, 2018 IL&FS,
  COVID, FY25 microfinance stress).
- **Promoter holding and pledging** — falling holding through open-market selling
  is a warning; falling via a QIP (new shares) is not. MAS: 73.7% → 66.66% via 2024 QIP.
- Institutional holding trends (DII/FII). MAS: DII 8% → 20%; FII fell 3.7% → 2.7% (Sep-26).
- Auditor qualifications / emphasis of matter, related-party lending,
  frequent accounting changes, RBI penalties or business bans
  (e.g. IIFL's gold-loan ban 2024).
- Management guidance vs delivery — note guidance each quarter and check it.

---

## 13. Valuation

- Lenders are valued mainly on **Price-to-Book (P/B)**, also P/E.
- **Justified P/B ≈ (ROE − g) ÷ (Cost of equity − g)** — higher sustainable
  ROE ⇒ higher P/B.

| Sustainable ROE | Typical P/B |
|---|---|
| 18–20%+ | 3–5× |
| 13–15% | 1.5–2× |
| <12% | ~1× or below |

- **P/ABV** (price ÷ book adjusted for net NPAs) for banks with bad-loan baggage.
- Compare with peers in the same segment (MSME, housing, vehicle, MFI).
- **Derating case study — MAS:** EPS +161% (Mar-2021 → Nov-2026) but P/E fell
  30× → 11.5× (P/B 3.7× → 1.5×) ⇒ share price flat. Reasons: starting valuation
  too rich, ROE fell 18% → 13.5%, rising credit-cost proxy, 10% dilution from QIP,
  sector-wide derating (RBI tightening, MFI stress), FII selling in 2026.

---

## 14. Banks — additional checks (vs NBFCs)

- **CASA ratio** (current + savings deposits ÷ total deposits) — cheap, sticky
  funding; >35–40% is strong.
- **Deposit growth vs loan growth**, **credit-deposit (CD) ratio** (<80% comfortable).
- **CET1** capital, **LCR**, **NSFR**.
- **Treasury gains** can flatter profit in falling-rate years.
- **Slippage ratio** (new NPAs ÷ loans) and recoveries/upgrades.
- PSU banks: government ownership, dividend policy, recapitalisation history.

---

## 15. Reading Screener.in for a lender

- Use the **consolidated** view where subsidiaries exist.
- P&L rows: Revenue (total income) → Interest (interest paid) → Expenses (opex
  + provisions) → **Financing Profit** (≈ PBT) → Financing Margin %.
- Click **Expenses** → Employee cost % and **Other expenses %** (track as credit-cost proxy).
- Balance sheet: Equity Capital + Reserves = equity; Borrowing; Other Assets →
  click to see **Cash Equivalents** and **Loans n Advances**.
- Ignore Screener's **"low interest coverage"** con for lenders — interest is
  their main cost by design.
- **"Promoter holding decreased"** — check whether it was a QIP (fine) or selling (not fine).
- Gross/Net NPA rows are often blank — get them from the investor presentation.
- Compute ROA/leverage yourself: NP ÷ avg Total Assets; avg Total Assets ÷ avg (Equity Capital + Reserves).

---

## 16. Red flags checklist

- [ ] ROE rising while ROA falls (leverage-driven).
- [ ] Profit growing much faster than AUM (one-offs, low provisions, upfront DA gains).
- [ ] Credit cost / other-expense % rising for 3+ quarters.
- [ ] Stage-2 rising; collection efficiency falling; large restructuring.
- [ ] GNPA flat but write-offs rising.
- [ ] Heavy short-term CP funding; negative ALM gaps within 1 year.
- [ ] Rating downgrade / negative outlook; lenders cutting lines.
- [ ] Very fast growth (>35–40%) in unsecured/MFI segments.
- [ ] Single-state or single-partner concentration.
- [ ] Promoter selling or pledging; auditor qualifications; RBI action.
- [ ] Frequent equity raises at falling prices (growth outrunning ROE).

---

## 17. Scorecard template (fill for every lender)

| # | Parameter | Value | Benchmark | ✅/⚠️/❌ |
|---|---|---|---|---|
| 1 | AUM growth YoY | | 15–25% steady | |
| 2 | Profit growth YoY (vs AUM growth) | | ≈ AUM growth | |
| 3 | ROA (trend 5 yrs) | | NBFC >2.5–3%, bank >1% | |
| 4 | Leverage / D-E | | NBFC 3–6× | |
| 5 | ROE (as result of 3×4) | | >15% | |
| 6 | NIM / spread | | segment norm | |
| 7 | Cost of funds trend | | stable/falling | |
| 8 | Cost-to-income | | <40% | |
| 9 | Gross / Net NPA | | <3% / <1% | |
| 10 | Credit cost | | <1.5% | |
| 11 | PCR | | >50–70% | |
| 12 | CRAR / Tier-1 | | >18% / >12% | |
| 13 | Borrowing mix & #lenders | | diversified, low CP | |
| 14 | Rating & outlook | | AA or better, stable | |
| 15 | LCR / liquidity vs 12-month repayments | | >100% / covered | |
| 16 | Secured share & collateral | | majority secured | |
| 17 | Geographic / partner concentration | | no state >40% | |
| 18 | Promoter holding / pledge / governance | | stable, no pledge | |
| 19 | P/B vs sustainable ROE | | fair per §13 | |
| 20 | Management guidance vs delivery | | delivered | |

**Verdict:** KEEP / ADD / HOLD / TRIM / EXIT — with 2–3 lines tied to ROA trend,
asset quality, funding and valuation (not ROE alone).

---

## 18. Data sources

- **Screener.in** (consolidated) — 10-yr P&L, balance sheet, cash flow, shareholding.
- **Company investor presentation** (quarterly) — AUM mix, NIM, CoF, Stage-2/3,
  collection efficiency, borrowing mix, CRAR.
- **Earnings call transcript** — guidance (AUM growth, CoF, credit cost, ROA).
- **Rating rationales** — CARE, ICRA, CRISIL, India Ratings, Acuité (funding
  mix, liquidity, lender list, asset quality).
- **Company website** — LCR / liquidity-risk disclosures.
- **NSE/BSE filings** — results, shareholding, pledges, corporate actions.
- Yahoo Finance — prices and quick fundamentals (its "revenue" basis can differ
  for lenders; cross-check with Screener).

Network note (Claude Code cloud sessions): screener.in, careratings.com,
nseindia.com, bseindia.com may need to be added to the environment's allowed hosts.
