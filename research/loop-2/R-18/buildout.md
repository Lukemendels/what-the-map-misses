# R18 AI buildout and historical investment booms

Research subreview for *What the Map Misses*  
Evidence cutoff and access date: 4 October 2026  
Status: research judgment ready for integration; historical series and proprietary microdata replication remain explicitly incomplete

## Finding and scope

The recalled comparison cannot establish that AI will have a greater economic effect than canals, railroads and electrification combined. The evidence/arithmetic block below fixes its scope. Transformative effects, private returns, productivity, employment and welfare require different evidence.

This subreview audits the newly admitted WSJ/Mint–Brookings lead and places it beside historical research on financing, network benefits, diffusion and investment failures. It informs C-045 and the R-04 treatment of C-043, with downstream implications for R-05, R-11, R-12 and R-15. It does not resolve the other R-18 anecdotes, revise the protected claim ledger, establish a canonical thesis, or adopt a normative position for Luke.

The principal research judgment is **revised/qualified**: retain the buildout as evidence of a consequential capital-allocation problem and an illustration of the distinction between investment and economic value. Do not use it as a measured ranking of technological revolutions. A harmonized, independently replicated ranking remains **unresolved**.

## Recovering the news lead

R18-BA01 is the accessible Mint republication of Konrad Putzier and Justin Lahart’s Wall Street Journal article, dated 24 September 2026, 07:14 IST. Its summary invokes canals, railroads and the grid together. Its quantitative lead points to the research reconstructed below. It separately reports Goldman Sachs’s 1.9% estimate for 2026 and acknowledges that realized spending could be lower. The article’s additional employment, inflation, wealth and construction claims rely on other sources; those claims are not validated merely by recovering the Brookings reference. [R18-BA01](https://www.livemint.com/ai/the-ai-build-out-is-becoming-the-biggest-economic-bet-in-us-history-11790213972265.html)

The Brookings landing page is dated 23 September 2026. Its short summary is credited to David Skidmore; the research author is Van Nieuwerburgh. It identifies a BPEA conference draft and provides the underlying PDF. The page supplies provenance and access, not an independent replication. [R18-BA02](https://www.brookings.edu/articles/financing-the-ai-buildout/)

## Evidence and arithmetic

BA03 is a conference scenario. Annual capex/GDP (Table 1): canals 1836–41, 0.66%; railroads 1870–90, 2.24%; electrification 1905–25, 0.50%; highways 1956–73, 1.13%; telecom 1996–2003, 1.10%; AI 2025–32, 3.63%.

Appendices A–B: July 23 Cleanview data; 2,933 uncanceled projects, 432 capacities imputed using regularized regression, smearing and bounds. Assumed completion rates yield 182.8 GW by 2032. Cost: $41 million/MW; costs/GDP grow 4%. Spending three years before completion through completion: 10/25/40/25%. Table 5: investment/GDP totals $10.279/$283.448 trillion; 2026 share 4.5%.

Appendix C: Cranmer canals/current-dollar GDP; Gallman–Rhode rail construction/1860-dollar national product, omitting some rolling stock; Ulmer utilities/current-dollar GDP, excluding users’ electrical machinery. Hardware refreshes omitted; facility/IT power definitions mixed. Undated completions differ: B, 2028–32; D, 2029–32. D’s $3.725 trillion revenue requirement assumes a 10% return, 50% cash-flow margin and six-/twenty-year IT/other lives; it is not a forecast.

Recalculation: historical trio 3.40; all five 5.63; AI exceeds the trio by 0.23 percentage points (6.8%). Table 5 yields 3.6264% (ratio of totals), 3.6266% (mean annual ratio): both round correctly. This checks arithmetic, not inputs, harmonization or forecasts. [R18-BA03, Tables 1–7 and Appendices A–D](https://www.brookings.edu/wp-content/uploads/2026/09/4c_Van-Nieuwerburgh.pdf)

## Interpreting the calculation

Adding intensities from separate episodes does not construct a jointly existing historical economy. Nor does successful arithmetic validate a project inventory, classifications, imputation, assumed schedules or denominators.

Contemporary investment measures also require boundary reconciliation. A measure attributed specifically to AI, a company-capex aggregate, construction put in place, equipment purchases and a modeled campus program can differ legitimately. Their boundaries and vintages must be matched before numerical disagreement can be interpreted.

Revenue and spending calculations must describe a consistent deployment path before their outputs can be combined. Any correction should be documented rather than silently imposed.

## The denominator and forecasting problem

A comparison of capital expenditures to GDP is a comparison of resource commitment against the economy’s output flow. It is not a benefit-cost ratio. A larger numerator can reflect more useful capacity, expensive inputs, redundancy, construction difficulty, rapid replacement or errors. Those possibilities point in different welfare directions. The price of creating an asset and the value of its subsequent services therefore must remain separate.

Several tests are necessary before strengthening the historical ranking:

1. **Match the asset perimeter.** Compare network infrastructure with network infrastructure, or complete production systems with complete production systems. If computing equipment is counted for one episode, justify whether locomotives, motors, vehicles, customer equipment and complementary structures are counted for the others. Expanding every perimeter is not automatically better: doing so can double-count shared assets.
2. **Match valuation.** A current-price expenditure share measures contemporaneous opportunity cost. A ratio whose numerator and denominator have been separately deflated measures something else unless relative-price effects are addressed. Fixed-base historical national-product series also need a documented bridge to contemporary GDP. The word “GDP” cannot do that harmonization by itself.
3. **Match time.** Short construction bursts, long diffusion periods and peak years answer different questions. Averaging over a longer interval often absorbs more ordinary years. A credible comparison should publish equal-window and peak-window sensitivities, rather than assume that selected episode dates are innocuous.
4. **Separate stocks, gross flows and services.** Annual purchases, installed capital, depreciation-adjusted net accumulation and useful compute are distinct. Identical gross spending with different asset lives produces different future service streams. Neither gross nor net investment by itself measures final social benefit.
5. **Separate plans from expenditure.** Announcement, permitted project, financing commitment, construction start, energized capacity, fitted equipment and paid utilization are separate milestones. Summing them as though each were a completed operating asset creates false precision. Conversely, excluding an ultimately abandoned project entirely can miss money spent before abandonment.
6. **Separate a scenario from a predictive distribution.** Conditional spending paths are useful stress tests. A central path without empirically validated realization rates is not a probability-weighted expectation, and decimal precision is not a confidence interval.

The small margin over the selected trio makes sensitivity analysis especially consequential. An upward adjustment to omitted historical equipment or a downward adjustment to modeled deployment might reverse that particular inequality. This is a statement about the comparison’s required robustness; it is not an estimate that either adjustment will occur.

The superlative also needs a defined universe. A table of selected infrastructure episodes cannot, by itself, establish the maximum across every U.S. investment category and historical period. The safe scope is the enumerated comparators under the stated construction conventions.

## Independent evidence on the modern measurement problem

Cleanview’s September update describes a transition to building-level coverage and separate measures of facility power and IT load, with satellite checks supplementing records. Its current public map includes crypto-mining facilities and reports a different project universe from the research vintage. This makes the October website unsuitable as a silent replacement for the July input. The vendor has commercial incentives and the update is a methodological description, not an independent accuracy audit. [R18-BA04](https://newsletter.cleanview.co/p/announcing-cleanviews-biggest-update), [R18-BA05](https://cleanview.co/data-centers/us)

**Inference:** a replication needs a frozen, deduplicated project file with workload type and capacity definitions, including whether a campus and its phases coexist as records. A representative training-cluster cost should be tested against alternative mixes of training, inference, conventional cloud and other computing. The existence of non-AI records does not establish their share in the particular scenario, nor prove that the estimate is inflated.

Soto, Thieu and Allen’s Federal Reserve note supplies a useful independent accounting framework. It distinguishes company property-and-equipment purchases, Census construction and BEA equipment investment, each with coverage limitations. It warns that hyperscaler capex includes non-AI activity, while leases can move investment outside those firms’ reported capex. Its GDP-growth proxy explicitly considers imported equipment; imported inputs can offset gross investment’s apparent domestic growth contribution. This is descriptive measurement guidance, not causal identification of AI productivity. [R18-BA06, “Firm Investment and Adoption,” Figures 4–7 and appendix](https://www.federalreserve.gov/econres/notes/feds-notes/the-ai-buildout-and-the-economy-publicly-available-data-to-assess-ais-impact-20260717.html)

The distinction matters directly to the book. Domestic expenditure on a productive imported machine can increase future domestic productive capacity even when the machine’s production occurred abroad. Counting the purchase as if its full amount were current U.S. value added is a separate error. Likewise, a firm’s operating cash flow, its global investment, and a U.S. investment/GDP ratio cannot be combined without geographic reconciliation. These are accounting constraints on a macro argument, not reasons to dismiss the physical buildout.

## What the historical literature actually compares

### Network benefits and the railroad counterfactual

The railroad debate is valuable because it asks what would have happened without a technology. In the accessible March 2012 Donaldson–Hornbeck draft, a network of railways and waterways generates least-cost freight routes; Census land values and population supply outcomes. A balanced panel of 2,161 counties in 1870 and 1890 links market access to agricultural land values using county and state-year effects, geographic controls and instrumental-variable checks. The authors explicitly confront endogenous placement and spillovers. Their model requires assumptions about trade costs, mobility and production. It is not an experiment in randomly assigning railroads. [R18-BA09, §§II–IV](https://conference.nber.org/confer/2012/CS12/Hornbeck_Donaldson.pdf)

The 2016 journal version was recoverable only as publisher metadata and abstract; its reported land-value counterfactual differs from earlier drafts. No preliminary numerical estimate is presented here as the final result. Fogel’s 1964 book was not substantively inspected, so its conclusions are represented only as the debate reconstructed in the accessible Donaldson–Hornbeck paper, not as a fresh verification of Fogel. [R18-BA10](https://doi.org/10.1093/qje/qjw002)

The methodological contribution is more important here than a headline percentage. A locality without a new railway may still benefit from distant improvements. A simple treated-versus-untreated comparison can therefore fail to recover aggregate gains. Applied as a research question for AI, the same problem arises when suppliers, customers or competitors adopt a technology: exposure is not exhausted by whether a particular firm bought a subscription. But a trade-network model cannot be copied into cognitive production without identifying the actual transmission mechanism.

Land values introduce another distinction: capitalized rents are a stock valuation. Turning them into an annual aggregate benefit requires assumptions. They also identify a particular beneficiary. A rise in landowners’ assets cannot simply be relabeled the gain to all workers or consumers. This is why an investment-share table and a market-access counterfactual answer different questions even when both use “railroads” as their subject.

### Electrification as complementary change rather than a universal timetable

David and Wright’s historical synthesis associates the U.S. manufacturing surge with unit drive, altered material flow, capital savings, central-station supply and labor-market changes. It explicitly rejects a purely technological explanation. Its comparison with Britain finds related patterns under different macroeconomic and institutional conditions. The evidence combines reconstructed industry productivity, historical engineering accounts and cross-industry correlations; it does not isolate factory layout through randomized or quasi-random assignment. [R18-BA11, §§1–3](https://www.nuffield.ox.ac.uk/economics/history/paper31/a4.pdf)

Moser and Nicholas challenge the canonical story using a different outcome. Their sample comprises 1,867 patents of publicly traded U.S. companies from selected 1920s years and 3,400 later citations. Electrical patents look broad at grant but less general and less persistent on several forward-citation measures. This is evidence against identifying a general-purpose technology from an appealing anecdote alone. Selection of listed firms, survival into late-century citations and the long unobserved interval limit the inference. Their analysis does not measure all benefits of using purchased electricity. [R18-BA12, §§I–IV and Tables 1–3](https://web.mit.edu/moser/www/GPT40110.pdf)

These approaches need not be mutually exclusive. A factory may use electricity to reorganize production without producing an electrical patent cited decades later. Conversely, an aggregate productivity acceleration cannot establish that one celebrated engineering innovation caused all of it. The relevant disagreement concerns measurement and attribution, not simply whether electricity mattered.

For R-04, preserve redesign as a plausible and historically grounded mechanism while discarding the inference that every technology must wait the same number of years or that managers were uniformly too unimaginative to move machines. Replacement economics, complementary skills, supply systems and labor institutions supply alternative explanations and interacting causes. A valuable book argument should specify which constraints are currently binding and what evidence would show that changing the workflow actually removed them.

### Highways and the difference between building a network and extending it

Fernald’s industry-level study examines 29 U.S. private-business sectors, excluding agriculture and mining, over 1953–1989. Vehicle intensity proxies road dependence. The relative response of more road-dependent industries supports a productive role for road building more convincingly than a single aggregate correlation. However, post-1973 marginal-return estimates are imprecise and specification-sensitive, with little variation in road growth. The evidence is consistent with large benefits from forming a network without demonstrating indefinitely exceptional returns to extensions. The inspected source is the 1997 working-paper version, subsequently published in 1999. [R18-BA13, §§II–III](https://www.federalreserve.gov/pubs/ifdp/1997/592/ifdp592.pdf)

The general lesson is a distinction between inframarginal and marginal value. A technology can be indispensable at existing scale while its next increment is overpriced or poorly located. Equally, diminishing returns to a mature application do not rule out a different application with high returns. Neither extrapolation can be decided by the historical size of the first buildout. For AI, capacity, utilization and revenue by use matter more than assuming that the returns to the earliest deployment apply to every later project.

### Canals and financing institutions

Wallis reconstructs state borrowing, legislative debates and constitutional changes surrounding early infrastructure finance. Geographic benefits and broad tax burdens made canal projects politically difficult; arrangements promising no immediate tax increase could leave taxpayers with contingent obligations. Fiscal distress then helped motivate debt procedures and changes in incorporation rules. The evidence is institutional and comparative historical analysis rather than a clean treatment-control estimate. The paper itself leaves portions of the long-run decentralization effect unquantified. [R18-BA08, pp. 211–217, 228–230, 234–237, 245–247](https://www.econweb.umd.edu/~wallis/Papers/Wallis_JEH_1%2028%2005.pdf)

This history makes guarantees and incidence central to an analogy, but does not establish equivalence between state canal debt and modern corporate project finance. The taxing authority, creditor remedies, beneficiaries, revenue contracts and government role differ. An ownership diagram should therefore be paired with a loss-allocation diagram: who must pay if demand disappoints, who can exit, and whose apparent gain rests on someone else’s guarantee?

A contemporary primary disclosure supplies a concrete test. Meta’s Hyperion announcement describes an 80/20 Blue Owl-funds/Meta ownership split, four-year initial leases, a sixteen-year capped residual-value guarantee and private debt funding. The announcement separates long-lived infrastructure development from the general AI ambition. It verifies specified contractual features as disclosed by a participant; it is not an independent valuation, complete covenant package or system-wide exposure census. [R18-BA07, transaction paragraphs](https://about.fb.com/news/2025/10/meta-blue-owl-capital-develop-hyperion-data-center/)

The inference for the book is conditional. Legal ownership, operational use and downside exposure can belong to different parties. An asset-light operating company can still bear contractual risk; an asset owner can receive fixed payments while another participant captures more upside. None of these arrangements proves fraud or inevitable instability. Their significance depends on correlated tenants, leverage, collateral, term structure and the ability of counterparties to perform. This supports keeping D-002’s conditional value-capture account open to empirical analysis rather than reinstating ownership as a universal winning position.

### Telecommunications and the coexistence of technical success and financial failure

Couper, Hejkal and Wolman document the late-1990s U.S. telecom expansion and collapse using investment, employment, price and financial series alongside regulatory history. They emphasize forecasting mistakes, advances that increased fiber capacity, and delayed complementary adoption at the local connection. They resist attributing the episode simply to a speculative bubble or WorldCom fraud. Their explanatory account is retrospective and explicitly tentative, not an identified causal decomposition. Their price evidence also separates local, long-distance and wireless services rather than finding one uniform deflationary trajectory. [R18-BA14, §§2–4](https://www.richmondfed.org/-/media/richmondfedorg/publications/research/economic_quarterly/2003/fall/pdf/wolman.pdf)

This is a direct challenge to a deterministic sequence in which capital first wins, labor next wins and consumers finally inherit the surplus. Faster technical progress can improve service while destroying the asset value supporting yesterday’s business plan. One part of a network can have excess capacity while a complementary part remains bottlenecked. The existence of a useful surviving infrastructure does not prove that every dollar committed to it was socially efficient, nor that the investors who financed it retained the gains.

Railroad financial distress similarly cannot be inferred from technological usefulness alone. Richardson and Sablik’s Federal Reserve historical account explains how nineteenth-century securities losses, refinancing problems and reserve-network withdrawals could propagate through banking. It also shows that some disturbances were contained. This is a strong secondary institutional account, not a new causal estimate of the railroad contribution to panics. [R18-BA15](https://www.federalreservehistory.org/essays/banking-panics-of-the-gilded-age)

For an AI analogy, those are mechanisms to investigate, not a predicted crash date. The amount of building is insufficient to establish systemic risk: one must trace liabilities and determine whether losses impair payments, intermediation or essential services. Equity investors absorbing losses is different from forced liquidation by leveraged intermediaries. Continued productivity gains and financial disruption can coexist; so can impressive technical capability and commercially unsuccessful projects.

## Claim level evidence ledger

These local IDs supplement rather than renumber the historical C-ledger.

| Local claim | Proposition tested | Judgment | Basis and safe use |
|---|---|---|---|
| R18-BL01 | The remembered news lead exists and traces to the named Brookings work | Supported within stated scope | BA01–BA03 establish provenance; use the actual publication dates and draft status |
| R18-BL02 | The recalled combined comparison describes technological effects | Contradicted in stated scope | The recovered quantity is expenditure intensity; no effect-size calculation supports that reading |
| R18-BL03 | The selected-trio arithmetic works | Supported within stated scope | See evidence/arithmetic block; do not treat separate episodes as one economy |
| R18-BL04 | The ranking is a harmonized historical accounting result | Unresolved | Asset coverage, valuation, timing and underlying-series replication remain open |
| R18-BL05 | The investment scenario establishes realized spending or a probability-weighted forecast | Contradicted in stated scope | Conditional assumptions cannot be promoted into observations or forecast probabilities |
| R18-BL06 | The required-revenue exercise predicts realized market demand | Contradicted in stated scope | A break-even requirement is not an estimated demand curve |
| R18-BL07 | Large infrastructure spending proves eventual high private returns | Contradicted as a general rule | BA08, BA14 and BA15 separate financing outcomes from useful technology |
| R18-BL08 | C-043 can use electrification to motivate complementary redesign | Revised/qualified | BA11 supports a mechanism; BA12 challenges narrow attribution; R-04 must examine additional evidence |
| R18-BL09 | C-045’s fixed capital/labor/consumer phase law follows from these booms | Unresolved as a general empirical claim; not supported here | Different outcomes and institutions do not establish a universal order; BA14 is material contrary evidence |
| R18-BL10 | Ownership alone identifies value capture and risk bearing | Revised/qualified | BA07–BA08 motivate separate analysis of contracts, control and incidence; consistent with testing D-002 rather than treating it as a finding |
| R18-BL11 | Comparing local adopters and nonadopters identifies total economic benefits | Revised/qualified | BA09 exposes network spillovers; BA13 offers a different exposure-based strategy with its own limits |
| R18-BL12 | The investment headline can establish AI systemic financial risk | Unresolved | Need creditor exposures, covariance, liquidity and loss-absorption evidence; a historical resemblance is insufficient |

## What remains open and how to resolve it

The narrow provenance question is resolved. The stronger quantitative ranking is not. A publication-grade extension would require:

- The frozen research-vintage Cleanview input, transformation code, developer aliases, project/phase deduplication and imputation diagnostics. This review did not obtain paid microdata or create an account.
- A public sensitivity grid for completion rates, capacity definitions, workload mix, hardware price paths, replacement and expenditures on failed projects. A fit statistic for imputation does not validate the completion scenario.
- Resolution of the consistency issue recorded in the evidence/arithmetic block, and reconciliation with contemporary investment observations. Backcast years should be labeled and checked against actual expenditure rather than simply treated as future cohorts.
- Full row-level reconstruction of Cranmer, Gallman–Rhode and Ulmer and their output denominators, together with matched-perimeter alternatives. Their bibliographic provenance was traced, but the original tables could not be substantively recovered in this access pass.
- The final Donaldson–Hornbeck text before using its numerical welfare counterfactual. The early version establishes a methodological debate; it does not license quoting its estimates as settled publication results.
- A separate financial-network study before claiming aggregate contagion, and a separate productivity/welfare study before ranking the effects of AI against historical technologies.

These are evidence gaps, not author decisions. Luke alone decides whether the narrowed comparison belongs in the book and how much argumentative weight it should carry. Nothing in this subreview requires replacing the book’s argument with either optimism about inevitable returns or pessimism about an inevitable bust.

## Downstream use

**R-04:** investigate redesign and adoption complementarities without imposing a fixed historical lag or attributing the entire productivity residual to layout.

**R-05 and R-15:** distinguish useful contribution, ownership, residual control, contractual guarantees, rents and actual compensation.

**R-11:** preserve the separation between acquisition expenditure, asset services, net accumulation, value added and welfare.

**R-12:** require a counterfactual and an aggregation mechanism before translating task gains, investment or lower service prices into employment, wages, aggregate deflation or shared prosperity.

## Source access and method appendix

All sources below were checked on 4 October 2026. Accessible substantive text, not search snippets alone, supports the synthesis. PDF locators refer to printed pages where available; PDF-page indices are stated where ambiguity matters. No full copyrighted article or book has been redistributed. No paywall was bypassed, no author or vendor was contacted, and no paid data were purchased.

| Source ID | Type and inspection | Method and inference limit |
|---|---|---|
| R18-BA01 | Accessible Mint article body, byline, date, summary, financing section and remaining body | Reported journalism; underlying non-Brookings claims not independently audited |
| R18-BA02 | Entire substantive Brookings landing-page summary, download and disclosure | Editorial summary; author and summary-writer identities kept distinct |
| R18-BA03 | Conference PDF introduction, §II, financing/risk/policy passages, Tables 1–7 and Appendices A–D; especially printed pp. 4–6, 12–14, 18–28 | Conditional accounting/scenario and institutional-finance analysis; no project-file replication; tables inspected through text extraction, without visual verification |
| R18-BA04 | Full September vendor methodology announcement | Primary statement about the vendor’s own changes; self-reported accuracy not validated |
| R18-BA05 | Current public map text, update date, definitions, displayed facility examples | Dynamic current snapshot; not a substitute for the archived input |
| R18-BA06 | Introduction, investment/adoption discussion, Figure 4–7 descriptions | Official research note using multiple public indicators; descriptive and classification-sensitive |
| R18-BA07 | Full transaction terms and forward-looking disclaimer in issuer announcement | Primary participant disclosure; contracts, independent valuation and later amendments not inspected |
| R18-BA08 | Journal-format author PDF; opening argument, debt table, Indiana and constitutional evidence, later institutional discussion, printed pp. 211–217, 228–230, 234–237, 245–247 | Archival comparative institutional history; not randomized identification; NSF support acknowledged |
| R18-BA09 | March 2012 conference draft, historical background, data, model and identification/results, printed pp. 1–17 | Preliminary structural/reduced-form historical research; final numerical results not inferred |
| R18-BA10 | Publisher page with final-version metadata and abstract only | Access-limited version check; not counted as a substantively read final paper |
| R18-BA11 | Oxford discussion paper, substantive §§1–3, printed pp. 4–13 | Historical synthesis and comparative industry evidence; causal contributions not separately isolated |
| R18-BA12 | Author-posted paper, data, definitions, statistical findings and conclusion, PDF pp. 1–10 and table descriptions | Patent/citation analysis; selected firms and long citation window limit coverage |
| R18-BA13 | Federal Reserve working paper, introduction, model setup, data/econometric issues, results and marginal-return discussion, PDF pp. 2–6, 11–20 | Industry exposure strategy; road-use proxy, model and specification restrictions matter |
| R18-BA14 | Richmond Fed paper, descriptive series, regulation/technology mechanism and conclusion, pp. 1–9 and 14–21 | Comparative narrative and official/financial series; alternative explanations retained, no causal decomposition |
| R18-BA15 | Entire substantive Federal Reserve History essay | Institutional secondary synthesis; primary archival works in its bibliography were not newly read |
| R18-BA16–BA18 | Bibliographic records and references traced; full NBER PDF fetches returned 403 | Historical raw series not independently inspected or reproduced |
| R18-BA19 | Citation traced from the conference draft; methodological-history page timed out | Historical GDP series vintage and transformations unverified |
| R18-BA20 | Primary bibliographic and author-page leads; NBER access failed and author-linked file unavailable | Background lead only; no substantive claim rests on its abstract |

## Recoverable bibliography

### Sources substantively inspected

- **R18-BA01.** Putzier, Konrad, and Justin Lahart. 2026. “The AI Build-Out Is Becoming the Biggest Economic Bet in U.S. History.” *The Wall Street Journal*, republished by *Mint*, September 24. [Accessible republication](https://www.livemint.com/ai/the-ai-build-out-is-becoming-the-biggest-economic-bet-in-us-history-11790213972265.html).
- **R18-BA02.** Brookings Institution. 2026. “Financing the AI buildout.” September 23. Summary credited to David Skidmore, research by Stijn Van Nieuwerburgh. [Landing page](https://www.brookings.edu/articles/financing-the-ai-buildout/).
- **R18-BA03.** Van Nieuwerburgh, Stijn. 2026. “Financing the AI Buildout.” BPEA Fall 2026 conference draft; title-page draft date September 4; conference cover September 24–25. [PDF](https://www.brookings.edu/wp-content/uploads/2026/09/4c_Van-Nieuwerburgh.pdf).
- **R18-BA04.** Thomas, Michael. 2026. “Announcing Cleanview’s Biggest Update Yet.” *Cleanview Newsletter*, September 16. [Methodology announcement](https://newsletter.cleanview.co/p/announcing-cleanviews-biggest-update).
- **R18-BA05.** Cleanview. 2026. “Data Centers in the United States.” Dynamic page labeled October 2026. [Public tracker](https://cleanview.co/data-centers/us).
- **R18-BA06.** Soto, Paul E., Mason Thieu, and Jeffrey S. Allen. 2026. “The AI Buildout and the Economy: Publicly Available Data to Assess AI’s Impact.” *FEDS Notes*, July 17. DOI 10.17016/2380-7172.4119. [Federal Reserve text](https://www.federalreserve.gov/econres/notes/feds-notes/the-ai-buildout-and-the-economy-publicly-available-data-to-assess-ais-impact-20260717.html).
- **R18-BA07.** Meta. 2025. “Meta Announces Joint Venture With Funds Managed by Blue Owl Capital to Develop Hyperion Data Center.” October 21; webpage also displays November 14. [Issuer announcement](https://about.fb.com/news/2025/10/meta-blue-owl-capital-develop-hyperion-data-center/).
- **R18-BA08.** Wallis, John Joseph. 2005. “Constitutions, Corporations, and Corruption: American States and Constitutional Change, 1842 to 1852.” *Journal of Economic History* 65(1): 211–256. [Author-posted journal-format PDF](https://www.econweb.umd.edu/~wallis/Papers/Wallis_JEH_1%2028%2005.pdf). Earlier NBER Working Paper 10451 (2004) is a different version.
- **R18-BA09.** Donaldson, Dave, and Richard Hornbeck. 2012. “Railroads and American Economic Growth: A ‘Market Access’ Approach.” March conference draft, explicitly preliminary and incomplete. [NBER conference copy](https://conference.nber.org/confer/2012/CS12/Hornbeck_Donaldson.pdf). Do not identify this file as the 2016 final article.
- **R18-BA11.** David, Paul A., and Gavin Wright. 1999. “General Purpose Technologies and Surges in Productivity: Historical Reflections on the Future of the ICT Revolution.” Oxford Discussion Papers in Economic and Social History, No. 31, September. [Oxford PDF](https://www.nuffield.ox.ac.uk/economics/history/paper31/a4.pdf). Later chapter versions exist; the inspected text is this 1999 paper.
- **R18-BA12.** Moser, Petra, and Tom Nicholas. 2004. “Was Electricity a General Purpose Technology? Evidence from Historical Patent Citations.” *American Economic Review* 94(2): 388–394. DOI 10.1257/0002828041301407. [Inspected author manuscript](https://web.mit.edu/moser/www/GPT40110.pdf); [publication record](https://www.aeaweb.org/articles?id=10.1257%2F0002828041301407).
- **R18-BA13.** Fernald, John. 1997. “Roads to Prosperity? Assessing the Link between Public Capital and Productivity.” Federal Reserve IFDP 592, October. [Inspected working paper](https://www.federalreserve.gov/pubs/ifdp/1997/592/ifdp592.pdf). Published as Fernald, John G. 1999, *American Economic Review* 89(3): 619–638, DOI 10.1257/aer.89.3.619; published text not substituted for the inspected version.
- **R18-BA14.** Couper, Elise A., John P. Hejkal, and Alexander L. Wolman. 2003. “Boom and Bust in Telecommunications.” *Federal Reserve Bank of Richmond Economic Quarterly* 89(4): 1–24. [PDF](https://www.richmondfed.org/-/media/richmondfedorg/publications/research/economic_quarterly/2003/fall/pdf/wolman.pdf).
- **R18-BA15.** Richardson, Gary, and Tim Sablik. 2015. “Banking Panics of the Gilded Age.” *Federal Reserve History*, written as of December 4. [Essay](https://www.federalreservehistory.org/essays/banking-panics-of-the-gilded-age).

### Traced sources with access or replication limits

- **R18-BA10.** Donaldson, Dave, and Richard Hornbeck. 2016. “Railroads and American Economic Growth: A ‘Market Access’ Approach.” *Quarterly Journal of Economics* 131(2): 799–858. [DOI and publisher record](https://doi.org/10.1093/qje/qjw002). Final abstract inspected; full text offered for purchase, not accessed.
- **R18-BA16.** Cranmer, H. Jerome. 1960. “Canal Investment, 1815–1860.” In *Trends in the American Economy in the Nineteenth Century*, 547–570. Princeton University Press for NBER. [Chapter record](https://www.nber.org/books-and-chapters/trends-american-economy-nineteenth-century/canal-investment-1815-1860); [PDF target](https://www.nber.org/system/files/chapters/c2489/c2489.pdf).
- **R18-BA17.** Rhode, Paul W. 2002. “Gallman’s Annual Output Series for the United States, 1834–1909.” NBER Working Paper 8860. DOI 10.3386/w8860. [PDF target](https://www.nber.org/system/files/working_papers/w8860/w8860.pdf). Further source lineage: Gallman (1966); original datasets were not re-estimated here.
- **R18-BA18.** Ulmer, Melville J. 1960. *Capital in Transportation, Communications, and Public Utilities: Its Formation and Financing*. Princeton University Press for NBER. [Book record](https://www.nber.org/books-and-chapters/capital-transportation-communications-and-public-utilities-its-formation-and-financing); [appendices PDF target](https://www.nber.org/system/files/chapters/c1498/c1498.pdf).
- **R18-BA19.** Johnston, Louis D., and Samuel H. Williamson. 2026. U.S. GDP series, MeasuringWorth; cited in the AI draft, accessed there July 2026. Exact input vintage was not recovered. The [historical-methods lead](https://mswth.org/U.S.GDPproject/historyofGDP.php) timed out and is not represented as inspected evidence.
- **R18-BA20.** Jovanovic, Boyan, and Peter L. Rousseau. 2005. “General Purpose Technologies.” *Handbook of Economic Growth* 1B: 1181–1224; NBER Working Paper 11093. DOI 10.3386/w11093. [NBER PDF target](https://www.nber.org/system/files/working_papers/w11093/w11093.pdf); [author’s bibliography](https://sites.google.com/a/nyu.edu/boyan-jovanovic-home-page/research). Full-text retrieval unsuccessful; excluded from substantive evidentiary support.

## Publication boundary

This is an analytical research artifact prepared from the admitted public corpus and public sources. Source access limits are part of the finding. It is neither a chapter draft nor an assertion that this subreview alone completes R-18. Protected repository files were not changed, and no remote-durability claim is made by this artifact.
