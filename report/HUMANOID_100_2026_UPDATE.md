# The Humanoid 100 — 2026 Update
### *How Morgan Stanley's map of the humanoid robot value chain reads 16 months on*

**Source paper:** Morgan Stanley Research, *The Humanoid 100: Mapping the Humanoid Robot Value Chain* (pricing as of 4 Feb 2025).
**This update:** InfraMosaic database, build of **13 June 2026** — 255-company universe, $40.7tn live market cap, 58 programs, 26 deployments, the IHCI cost index and the supply/demand order book.

**How to read this.** The original paper is walked in its own running order, exhibit by exhibit. Each block is:
> **MS (Feb 2025)** — what the paper said.
> **2026** — what InfraMosaic's current data shows.
> **Δ** — what a re-write would change.

Nothing here redistributes the MS list; the MS *Humanoid 100* is used only as the cross-check spine. The dataset is InfraMosaic's own.

---

## Part 0 — The index itself

> **MS (Feb 2025).** A curated **100-company** index — Brain, Body (64 names), Integrators — pitched as "the Nasdaq-100 of humanoids": one watchlist that spans the value chain. Pricing 4 Feb 2025.
>
> **2026.** The index is now a **255-name universe** (`companies.csv` 150 core + `companies_ext.csv` 105 tier-2). **All of MS's original 100 are inside it** — the cross-check column shows **89 ms_h100 = yes** after we folded the 20 constituents MS listed but our v1 had missed (see Appendix A). The other 166 names are InfraMosaic's own extension into the China component long-tail and the rest-of-world supply chain. Total tracked market cap: **$40.7tn, 255/255 live** (Yahoo crumb-flow, FX-converted).
>
> **Δ.** The paper would stop calling it "100." The interesting universe is ~2.5× bigger, and the action since Feb 2025 is in the **tier-2 Chinese parts makers** the original 100 mostly skipped. The headline index can stay at 100 as a "blue-chip" cut, but the working database is 255.

---

## Part 1 — Executive thesis

> **MS (Feb 2025).** Humanoids move from demo to deployment over the decade; a **~$5tn global market by 2050**, **>1bn units by 2040s** (Musk), the US alone reaching tens of millions of units. The supply chain — not the robot brands — is the durable investment, and it runs heavily through China. "52% of the Humanoid 100 have already been reported as involved; 48% have material potential."
>
> **2026.** The thesis aged well — and the boring half (the supply chain) is exactly where the value showed up. The robot brands are still mostly pre-revenue; the **picks-and-shovels re-rated**. Two things MS could not see in Feb 2025 now dominate the story:
> 1. **Deployment is real.** 26 tracked programs in paid pilots / early production, **122,302 cumulative units** on order or deployed (Figure→BMW, Apptronik→Mercedes, Agility→GXO, UBTech & AgiBot shipping by the thousand).
> 2. **A memory/AI-compute super-cycle** repriced the Brain layer violently (NVIDIA $4.97tn, Micron $1.1tn, SK Hynix $1.0tn — see Part 8).
>
> **Δ.** The re-write leads with **"deployment has started"** rather than "deployment is coming," and it splits the thesis cleanly: the *Brain* has already been paid for by the AI trade; the *Body* is where the humanoid-specific, not-yet-priced optionality still sits.

---

## Part 2 — Momentum & involvement (Exhibits 1–4)

**Exhibit 1–2 — transcripts/news mentioning "Humanoid" over time.**
> **MS.** A near-vertical 2023–24 ramp in company-transcript and media mentions — the "attention" leading indicator.
> **2026.** The curve kept climbing through 2025 then **plateaued at a high level** — humanoids are now a standing agenda item, not a novelty spike. The signal has matured from "mentions" to **order books and capex guidance**.
> **Δ.** Replace the mentions chart as the lead indicator with the **deployments + unit-orders** series. Mentions were the 2024 proxy; shipments are the 2026 proxy.

**Exhibit 3–4 — "52% reported involved / 48% potential."**
> **MS.** Just over half of the 100 had publicly confirmed humanoid involvement.
> **2026.** That share has **risen sharply** — across InfraMosaic's universe, confirmed involvement (programs, supply contracts, named design-ins) is now the majority for the core names; the "potential" bucket shrank as suppliers disclosed humanoid design-wins through 2025 earnings.
> **Δ.** The 52/48 split becomes roughly **70/30 confirmed/potential** for the blue-chip cut.

---

## Part 3 — The Brain (Exhibits 10–12)

> **MS (Feb 2025).** The "Brain" = foundation models, AI compute, EDA, simulation, vision. US- and Taiwan-led: Alphabet, Microsoft, NVIDIA, TSMC, Arm, Cadence, Synopsys, Palantir, Oracle, plus memory (Micron, SK Hynix, Samsung) and vision (Hexagon).
>
> **2026.** Brain = **67 of 255 names**, China share **41.8%** by count but the *value* and *moat* sit in the US/Taiwan core. The segment's internal concentration is the highest of the three (**HHI 3,232**) — compute is an oligopoly. The 12 largest companies in the entire universe are now almost all Brain: **NVIDIA $4.97tn · Alphabet $4.39tn · Apple $4.28tn · Microsoft $2.90tn · Amazon $2.57tn · TSMC $2.20tn · Broadcom $1.82tn · Tesla $1.53tn · Meta $1.44tn · Samsung $1.40tn · Micron $1.11tn · SK Hynix $1.01tn.**
>
> **Δ.** Two corrections to Exhibit 11. (1) **Memory is no longer a footnote** — Micron and SK Hynix are now trillion-dollar names on the HBM/AI cycle (Micron's 52-week range is **$103 → $1,089**); they deserve top billing in the Brain, not the memory annex. (2) The Brain has effectively **already been re-rated by the AI trade** — its humanoid optionality is now a rounding error on valuations set by data-center demand. The re-write would caveat that owning the Brain for *humanoid* exposure is buying a lottery ticket stapled to an already-expensive AI stock.

---

## Part 4 — The Body (Exhibits 13–15) — *the heart of the paper*

> **MS (Feb 2025).** The "Body" (64 companies) is the electro-mechanical stack and **where China has built an almost unassailable position**. Parts walked one by one: bearings, screws, reducers, motors + rare-earth magnets, encoders, sensors (vision/lidar/magnetic/force-torque), batteries, analog semis, structure/wiring/thermal. "Joint drive modules are 60–70% of a humanoid's cost."
>
> **2026.** Body = **147 of 255 names** (the universe's centre of gravity), China share **41.5%**, HHI 2,425. Every MS parts-bucket is now an InfraMosaic value-chain node with a **live exposure score** and a **supply/demand utilisation**. The single highest-conviction read in the whole database is here: the **top of the exposure table is entirely Body** —
>
> | Rank | Company | IMES | Why |
> |---|---|---|---|
> | 1 | Harmonic Drive Systems | 92 | strain-wave reducer near-monopoly |
> | 1 | Moog | 92 | precision actuation |
> | 3 | Symbotic | 88 | warehouse automation pull |
> | 4 | Renishaw | 85 | encoders / metrology |
> | 5 | Nabtesco | 84 | cycloidal reducers |
> | 5 | Intuitive Surgical | 84 | dexterous precision analog |
> | 7 | UBTech | 83 | only listed pure-play maker |
>
> **Δ — the one material correction to the paper's economics.** MS's own **Exhibit 54** (Optimus Gen-2 BOM by component) shows **sensors are the #1 cost line at 37%**, ahead of motors (20%) and screws (20%) — yet the narrative throughout the paper still anchors on "joint modules = 60–70%." InfraMosaic now **re-bases the BOM on Exhibit 54** (sensors 37 / motor 20 / screw 20 / reducer 13 / encoder 4 / compute 4) and the re-write would foreground the **six-axis force-torque sensor in the hands and feet as both the top cost and the tightest bottleneck** (ATI/Novanta near-monopoly; our supply/demand model flags F-T sensors at **440% of 2030 capacity**). The paper buries its own most important number.

**Parts ledger — MS bucket → 2026 read:**

| Part (MS Exhibit 14/15 bucket) | MS constituents | 2026 node read |
|---|---|---|
| **Bearings** | NSK, RBC, Regal Rexnord, Schaeffler, Timken | China ~rising; commoditising; low IMES |
| **Screws** (ball + planetary roller) | Hengli, Hiwin, NSK, SKF, Shanghai Beite, THK | **Deficit-risk: 770% of 2030 capacity** — the single tightest mechanical bottleneck |
| **Reducers** (harmonic + cycloidal) | Harmonic Drive, Nabtesco, LeaderDrive, Shuanghuan, Zhongda, Hiwin, Hota | **Highest-IMES node** (Harmonic 92, Nabtesco 84); China share climbing fast via LeaderDrive/Zhongda |
| **Motors + magnets** | Estun, Leadshine, Moons', Nidec, Inovance, Zhaowei + JL Mag, Lynas, MP, Northern RE | **Rare-earth magnets ~100% China**; the binding *physical* constraint (Dy/Tb export controls) |
| **Encoders** | Nidec, Novanta, Sensata | Renishaw IMES 85; precision moat intact |
| **Sensors — F/T** | Keli, Novanta, Sensata, TE | **#1 BOM cost; 440% deficit-risk** — the re-write's hero chart |
| **Vision/lidar** | ADI, Hexagon, Keyence, Onsemi, Robosense, Sony, TE, Teledyne, Will, Aptiv, Magna, Valeo | LiDAR now in **glut (5.5% util)** — auto over-capacity spilled in |
| **Batteries** | CATL, EVE, LG ES, Samsung SDI | **Glut (0% util headroom)** — humanoid demand is a rounding error on EV cells |
| **Analog semis** | Allegro, Infineon, Melexis, NXP, Onsemi, Renesas, ST, TI, Will | Steady; auto-cycle linked |
| **Structure/wiring** | Amphenol, Aptiv, Magna, TE, Xusheng, Sanhua, Tuopu | China die-casters (Xusheng/Tuopu/Sanhua) scaling |

---

## Part 5 — Integrators (Exhibits 16–17)

> **MS (Feb 2025).** Five integrator archetypes: autos/OEM (BYD, GAC, Hyundai/Boston Dynamics, Tesla, Toyota, XPeng), tech/consumer (Apple, Foxconn, LG, Samsung, Sony, Xiaomi), cloud (Alibaba, Amazon, Naver, Tencent), industrial robotics (ABB, Midea/KUKA, Teradyne), pure-play (Rainbow Robotics, UBTech).
>
> **2026.** Integrators = **41 of 255**, China share 34.1%, the *least* concentrated segment (HHI 2,064) — many credible assemblers, no winner yet. The pure-plays are pulling ahead on shipped units: **UBTech** (Walker S2, 3-minute autonomous battery-swap, >800m-yuan orders) and **AgiBot/Zhiyuan** (A2, #1 by 2025 volume, ~5,168 units per Omdia) now out-ship the Western brands.
>
> **Δ.** The re-write promotes two things MS under-weighted: (1) **Foxconn/Hon Hai as the contract-manufacturing kingmaker** — whoever wins the OEM race likely builds at Foxconn; (2) **Tesla's status as both Brain and Integrator** with the only credible 1M-unit line (Optimus Gen-3, Fremont). It also notes the Western "OEM brands" (Figure, Apptronik, Agility) are *integrators that don't appear in the MS-100* because they're private — captured here in the **12-name private watchlist** (Figure ~$39bn, plus newcomer **Humanoid / HMND 01**, London, $50m, 20,500 pre-orders).

---

## Part 6 — Composition & regional (Exhibits 18–23)

> **MS (Feb 2025).** Humanoid-100 skewed China & Taiwan on the Body, US on the Brain. China = 63% of the *supply chain*. Analyst-surveyed AI exposure / materiality / pricing-power scatter.
>
> **2026 (universe of 255).** Regional split by name: **China 40.4% (103) · North America 24.3% (62) · Japan 14.5% (37) · Europe 7.8% (20) · Korea 5.9% (15) · Taiwan 4.3% (11) · Asia-other 2.4% · Oceania 0.4%.** Overall country concentration **HHI 2,468**. Segment China-share: Brain 41.8%, Body 41.5%, Integrator 34.1%.
>
> **Δ.** MS's "63% China" was a *supply-chain-weighted* figure; our by-name figure is 40.4%, but the **Body component nodes reproduce MS exactly** — rare-earth magnets ~100% China, actuators ~64%. The thesis holds and, if anything, **intensified**: the Dy/Tb export-control regime now sits directly on the highest-criticality nodes. The re-write's regional message is sharper — *"China's dominance isn't broad, it's surgical: it owns the three or four parts that can't be substituted."*

---

## Part 7 — *(reserved — see Part 8 for valuation)*

---

## Part 8 — Valuation & performance (Exhibits 24–34)

> **MS (Feb 2025).** P/E rank of the Humanoid 100, P/E vs 3-yr revenue CAGR, and LTM performance of the index and its Brain/Body/Integrator and regional sleeves vs benchmarks. Pricing 4 Feb 2025.
>
> **2026.** This is the section that changed the **most**. Since Feb 2025 the universe lived through an **AI/memory super-cycle**:
> - **NVIDIA $4.97tn**, the gravitational centre of the index.
> - **Micron $1.11tn** (52-wk $103→$1,089) and **SK Hynix $1.01tn** (KRW 238k→2,407k) — memory went from the paper's footnote to two of its twelve biggest names.
> - Total index cap **$40.7tn** across 255 names; the top 12 alone are ~$28tn.
>
> **Δ.** Every valuation exhibit is stale and must be re-struck. More important, the re-write would add a **warning the original lacks**: the index's return since Feb 2025 is **overwhelmingly an AI-compute/memory story, not a humanoid story**. A reader buying "the Humanoid 100" today is mostly buying the AI trade. The genuinely *humanoid-levered* return sits in the small/mid Body names (Harmonic, Nabtesco, Moog, Renishaw, the Chinese reducer/screw makers) — which is exactly where InfraMosaic's IMES points and where the index-cap weighting points away.

---

## Part 9 — Pop culture, pros/cons, hurdles (Exhibits 35–47)

**Exhibit 35 — humanoids in pop culture.** Unchanged; still a fun framing device. No update needed.

**Exhibit 36 — pros/cons vs specialised robotics.**
> **MS.** Humanoids are general-purpose but expensive/immature vs purpose-built automation.
> **2026.** The cost gap **closed faster than the con-side assumed** — see the IHCI (Part 12): a Western reference robot fell from ~$200k to **~$95k** in 18 months. The "too expensive" objection is weakening on schedule.
> **Δ.** Move "cost" from the con column toward neutral; keep "reliability/autonomy in unstructured environments" as the live con.

**Exhibits 37–46 — labor & TAM (US jobs with humanoid optionality, labor availability vs AI/robotics).**
> **MS.** ~$3tn US humanoid TAM by 2050 built on labor-substitution of jobs with "humanoid optionality"; adoption negligible to ~2035, then an S-curve.
> **2026.** InfraMosaic's market model keeps the **same S-curve shape** and brackets the MS path: **base 550k units / $13bn (2030) → 1.4M units / $30bn (2035)**, with scenarios spanning the MS/Goldman/Bain ranges. The 2028-onward inflection MS drew is intact; nothing in 2025–26 deployment data argues for pulling it earlier *at scale* (pilots are hundreds-to-thousands of units, not millions).
> **Δ.** Keep the TAM architecture; tighten the **near-term** units with real 2025–26 order data (which MS had to guess). The long-run $tn TAM is unfalsifiable either way and should be flagged as such.

**Exhibit 47 — adoption hurdles.** Add **rare-earth export controls** and **force-torque sensor supply** as named, near-term hurdles — both are 2026-specific and absent from the original list.

---

## Part 10 — Hardware & BOM (Exhibits 48–55)

> **MS (Feb 2025).** Optimus Gen-2 hardware: 28 actuators (14 rotary + 14 linear), ~50 DoF, 22-DoF hand (Gen-3). **Exhibit 54: BOM by component — Sensor 37%, Motor 20.3%, Screw 20.2%, Reducer 12.6%, Encoder 3.9%, FSD+chips+camera 3.8%, Bearing 0.8%, Battery 0.5%.**
>
> **2026.** InfraMosaic's reference BOM is now **re-based directly on Exhibit 54** (material BOM ~$55,000): **Sensors $20.4k (37%) · Motors $11.2k (20%) · Screws $11.1k (20%) · Reducers $6.9k (13%) · Encoders 4% · Compute 4%.** The whole-robot cost curve: **Western $200k (2024) → $40k (2030)**, **China $46k → $18k**. A regression test (`test_sensors_are_top_cost`) now *locks* sensors as the #1 line so the correction can't silently revert.
>
> **Δ.** This is the paper's biggest internal inconsistency to fix: its prose says "joint modules 60–70%," its own Exhibit 54 says "sensors 37% #1." The 2026 re-write resolves it in favour of the data — **sensors lead** — and ties it to the supply story (F-T sensors are *also* the tightest bottleneck). Also flag the **planetary roller screw cost-down** ($3,000 → $800 at Tesla scale) as the proven template the rest of the BOM will follow.

---

## Part 11 — Unveils tracker (Exhibits 61–64)

> **MS (Feb 2025).** ~67 notable humanoid unveils since 2022; **2024 = 51 unveils (China 35, US 8, EMEA 4, Rest-Asia 4)**; China 61% of all unveils, US/Canada 24%. General-purpose 56% of use-cases.
>
> **2026.** InfraMosaic folded that tracker into a **58-program curated database** with specs, status and pricing — then carried it forward through 2025–26. By region: **China 32 · North America 16 · Europe 4 · Japan 3 · Korea 1 · Middle East 1 · India 1.** By maturity: **Prototype 22 · Limited-production 17 · Pilot 12 · Mass-production 4 · Pre-production 1.** New since the paper: Unitree R1 ($5,800), 1X NEO (consumer, $20k), XPeng Iron (mass-prod end-2026), UBTech Walker S2 (battery-swap), AgiBot A2 (#1 by volume), Booster T1 (RoboCup champ), and non-MS entrants like **Humanoid / HMND 01** (London).
>
> **Δ.** The unveils chart graduates from "who showed a robot" to **"who shipped one."** Four programs are already at **mass-production** — a status that didn't exist when MS drew Exhibit 61. China's lead in *count* persists; the re-write adds a **status axis** (China also leads in *units shipped*, via Unitree/UBTech/AgiBot).

---

## Part 12 — What's genuinely NEW since the paper

Three datasets exist in 2026 that MS could not build in Feb 2025 because the underlying reality hadn't happened yet:

1. **Deployment tracker** — **26 programs, 122,302 cumulative units** in paid pilots / early production. In Feb 2025 there was essentially nothing to count; the re-write adds a whole section on *who is actually being paid to put robots on floors*.
2. **IHCI — InfraMosaic Humanoid Cost Index** — monthly, 2024-01 = 100. Now **Western 47.3 / China 65.0** (i.e. the Western reference robot is **down ~53%** to ~$95k; China down ~35% to ~$30k). MS gave point estimates; InfraMosaic gives the *track*.
3. **Supply/demand order book** — robot ramp × per-robot bill-of-quantities vs assessed capacity. 2030 verdicts: **deficit-risk** — roller screws **770%**, F-T sensors **440%**, integrated actuators **385%**; **glut** — LiDAR 5.5%, batteries ~0%, magnets 0.5% (capital-glut, but the rare-earth *input* is the real constraint). This converts the paper's qualitative "China dominates the Body" into a quantified, node-by-node tightness map.

---

## Part 13 — Scorecard: what MS got right, wrong, and couldn't know

| Call | Verdict 2026 |
|---|---|
| "The supply chain, not the brands, is the trade" | ✅ **Right** — picks-and-shovels re-rated; brands still pre-revenue. |
| "China owns the Body / 63% of the supply chain" | ✅ **Right and intensified** — surgical dominance on magnets/reducers/screws + export controls. |
| "Sensors are 37% of BOM (Exhibit 54)" | ✅ **Right in the data, wrong in the prose** — paper's narrative under-weighted its own number; now corrected & locked. |
| "$5tn by 2050 / S-curve from ~2028" | 🟡 **Unfalsifiable but intact** — near-term units now real and on-trajectory; long-run TAM still a guess. |
| "Joint modules = 60–70% of cost" | 🟠 **Superseded** — true at the *sub-system* cut, misleading at the *component* cut where sensors lead. |
| Memory as a Brain footnote | ❌ **Missed** — Micron & SK Hynix are now trillion-dollar index members. |
| No deployment / cost-track / order-book data | ⚪ **Couldn't know** — these are the 2026 additions, not MS errors. |

---

## Appendix A — The 20 names a 2026 re-write *must* add to be MS-100-complete

These were in MS's own Exhibit 11/14/16 enumerations but absent from InfraMosaic v1; now added (ms_h100 = yes), with live caps:

Aptiv · Oracle · Palantir · Micron · SK Hynix · Toyota · Magna · Honeywell · Hon Hai/Foxconn · Timken · Teledyne · Valeo · Hexagon · Dassault Systèmes · Naver · GAC · Midea/KUKA · RBC Bearings · Shanghai Beite · Xusheng.

## Appendix B — Provenance & method

- **Universe & caps:** `data/companies.csv` + `companies_ext.csv`; live caps `data/market_caps.csv` (Yahoo crumb-flow, FX→USD, 255/255). Memory-supercycle outliers (Micron, SK Hynix) flagged and **verified real** via 52-week range + prev-close before ingest.
- **Source paper:** `research/humanoid100/humanoid100.md` (86-page transcription) + `humanoid100_firecrawl_full.md/.json` (clean export; the Exhibit 11/14/16 "Companies in the Humanoid 100" enumerations are the authoritative roster used for the cross-check).
- **Live evidence layer:** `scrape/ledger.db` (deep site corpus) → `scrape/extract_fields.py` → `company_facts` → `scrape/build_citations.py` → **[`report/SOURCED_EVIDENCE.md`](SOURCED_EVIDENCE.md)** (per-company citations, every line carrying the company's own source URL; refreshed each scrape pass). The deep census is in progress at build time; the evidence file grows with it.
- **Provenance guardrails (QA).** The resolver rejects finance-aggregator, broker, exchange and social hosts and prefers a company-name-token domain (so *Cambricon → cambricon.com*, never *en.cicc.com*); a hand-curated `scrape/domain_overrides.csv` seeds the few names that don't rank in English search. Extraction drops aggregator pages before mining a fact, so one firm's numbers can never be misattributed to another (the failure mode that first surfaced *General Motors' revenue on Moons' page*). Only own-domain `Sourced` facts are cited; single-value regex reads of revenue/employees/HQ are held back as `Hint` pending a verified pass.
- **Models:** IMES, HHI, IHCI, supply/demand order book — see `docs/METHODOLOGY.md`. 52 integrity tests pass.

*InfraMosaic — the price-reporting agency and asset-level database for the humanoid economy. Not affiliated with Morgan Stanley; the MS Humanoid 100 is used solely as a published cross-reference.*
