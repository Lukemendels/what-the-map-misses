# R-01 Cognition supply and demand

**Research review prepared 4 October 2026; independent substantive quality review passed.** Scope: C-001, C-006 and C-053. This is a literature assessment for *What the Map Misses*, not a chapter, a frozen thesis, a product recommendation or an author decision. Public sources only. The historical claim ledger and source corpus remain unchanged.

## What this review establishes

Machine inference has become substantially cheaper at several fixed benchmark performance levels. That is a consequential supply change. It is not yet a measured economy-wide decline of the same magnitude in the cost of useful completed work. The missing conversion requires task-specific capability, a workable definition of completion, verification, integration, human effort, delay, and the consequences of undetected mistakes.

The strongest defensible reading of C-001 is therefore conditional and heterogeneous: cheaper access to particular machine capabilities can increase their use within existing tasks and make additional tasks worthwhile where the full production system clears its economic and reliability thresholds. The evidence is strongest for the supply-side direction and selected applications; it does not identify a universal rate of demand expansion. Recent direct estimates of inference-demand elasticity conflict even within one platform. Neither the optimistic nor skeptical estimate identifies long-run demand for useful cognition throughout the economy.

C-006 receives support as a choice of analytical unit: a model's price and score are insufficient to evaluate the coupled workflow. It does not follow that large-scale redesign always beats a modest improvement to an inherited process. For C-053, this review establishes an economic reason to measure fallibility and complements. Whether particular institutions reproduce human capability, provide legitimate authority, or create adaptive capital requires the other programs and author judgment.

The narrower current C-001 must not inherit the stronger language of the predecessor *Cognitive Factory Floor*. Its “Jevons Paradox of the Mind” section asserts near-zero marginal thought cost, highly elastic corporate demand and exponentially greater required output. Those are separately tested predecessor propositions, associated with C-045, rather than the wording of C-001 itself.

## 1 The economically relevant unit

“Cognition” is a useful umbrella but an inadequate unit of measurement. A token is not a fixed quantity of reasoning, an accepted answer is not necessarily a correct one, and a correct answer is not necessarily a useful completed task. The following distinctions are analytical definitions used in this review.

| Quantity | What it measures | What it does not establish |
|---|---|---|
| Posted token price | A provider's tariff for a specified input, output, cache and service class | Cost of completing a task, underlying resource cost, or price actually paid |
| Inference expenditure per attempt | Tokens and tools used for one configured run | Successful delivery, integration, or downstream loss |
| Benchmark cost at fixed score | Expenditure needed to attain a specified result on a specified test distribution | Equivalent capability on a different task distribution |
| Task-completion capability | Probability of passing a task under stated instructions, tools, budgets and scoring | Autonomous duration, whole-job coverage, or safe deployment |
| Quality-constrained workflow cost | Full resource cost of a defined output at required reliability and timeliness | Consumer surplus, total factor productivity, or who captures gains |
| Realized value | Benefits of outcomes relative to the relevant counterfactual, net of appropriate costs | Something observable merely by counting outputs or purchases |

A sensible task boundary includes its terminal state. A draft accepted for further work, an answer checked against authoritative evidence, a booking actually made, and a maintained software change have different terminal states. Calling each a “task” obscures rather than solves the comparability problem. The book should identify whose objective is being satisfied, how success is assessed, and which downstream costs remain outside the boundary.

For a fixed evaluation population and horizon, define a workflow policy as the combination of model, tools, routing, human involvement and controls. A transparent accounting measure is:

**Cost per useful completion = (allocated setup cost + expected operating, human, recovery and delay costs across all assigned cases) / expected useful completions.**

This is a ratio of totals, not an average computed only among successful attempts. Record downstream losses separately, or add their expected monetary equivalent when that is a defensible decision rule; do not double count repair costs already included. Some catastrophic, legal or rights-based constraints belong outside a monetary objective as hard admissibility conditions. Human comparison policies need the same accounting treatment, including their failures and supervision.

The numerator should include specification, gathering permissible inputs, integration, tool fees, retries, review, exception handling and ongoing maintenance. Labor time should be valued at the relevant opportunity cost, not automatically at either zero or a worker's full billed hourly rate. Delay is costly when it blocks other work or misses a deadline; unattended overnight processing need not cost an employee's wage for every elapsed minute. A fixed investment should be spread over expected useful demand before obsolescence, not hypothetical infinite volume.

A unit-cost ratio is still insufficient when task values differ greatly. A system could lower the ratio by selecting trivial cases while abandoning high-value ones. Report coverage, value distribution, quality, loss severity and cost jointly. For optional tasks, compare expected incremental benefit with incremental full cost and risk. For a mandatory queue, compare feasible policies that serve the same queue. This distinction separates an efficiency improvement from selective refusal of expensive work.

## 2 What the price evidence actually measures

### A real supply improvement with changing denominators

**R01-S01 evidence capsule.** Cottier and colleagues' 2025 Epoch analysis follows minimum token prices among models clearing specified benchmark thresholds. Its six-benchmark estimates vary widely, with reported annualized declines from 9-fold to 900-fold; the authors warn against assuming the fastest short interval persists. It excludes reasoning models and separately checks a smaller set of evaluation-cost trends. These are not invoices for complete workflows. [S01]

**R01-S02 evidence capsule.** Gundlach and colleagues instead multiply input, output, reasoning and cache usage by historical prices. Their March 2026 revision finds roughly 5–10-fold annual cost declines at fixed benchmark performance, while the cost of obtaining frontier performance rises roughly 3–18-fold annually. The primary price window is April 2024–November 2025. GPQA has 93 unique models; SWE-bench Verified only 19. Lowest-provider prices, nonrandom coverage and logit-score regressions constrain interpretation. Some cache prices are contemporary substitutes; exclusions include increases following withdrawal of cheap providers, limiting inference about realized user costs. The open-model/hardware decomposition of algorithmic progress relies on pricing assumptions, not a randomized separation of causes. [S02]

**R01-S03 evidence capsule.** Emberson and Roodman's September 2026 Epoch report estimates about a 13-fold annual decline across five mathematics, science and game benchmarks. It traces cost-performance curves using reasoning settings and simulated token-budget truncation, with direct-hardware costing for some open models. The authors explicitly avoid formal standard errors because frontier selection and the data-generating process make them difficult to justify. This extends the evidence beyond token prices but remains a rough benchmark-frontier estimate requiring active model switching. [S03]

These studies support the direction of cheaper access much more strongly than any single universal multiplier. Their estimates are not competing readings of an identical basket. Dates, domains, quality thresholds, model selection and treatment of reasoning effort differ. Greater coverage and accounting for generated tokens can reduce the apparent rate without negating technical progress. Conversely, a slower estimate need not describe every domain, especially a newly reached performance level that competitors rapidly commoditize.

There is also no contradiction between falling cost for yesterday's capability and rising expenditure on today's best result. The first asks how cheaply an old target can now be met; the second permits the target to improve. A customer might buy more quality, more attempts or longer contexts as prices fall. Treating that decision as evidence that efficiency did not improve is mistaken. Treating the resulting increase in tokens as evidence of proportionately greater useful cognition is equally mistaken.

### A tariff is a dated input to an economic calculation

**R01-S04 evidence capsule.** On 4 October 2026 OpenAI's official standard tariff lists GPT-6.1 Sol short-context input at $2 and output at $10 per million tokens, with distinct cache, long-context and service-tier prices. The page separately prices tools. These are public list prices, not observed transactions or a capability-adjusted comparison. [S04]

An illustrative calculation makes the scale issue concrete. At that tariff, 10,000 ordinary input tokens and 2,000 billed output tokens cost $0.04, before other charges. Suppose, purely for illustration, that preparing and checking the result requires ten minutes of labor valued at $60 per hour. Direct labor then costs $10. A 90% reduction in the inference charge saves $0.036, about 0.36% of the combined $10.04. Eliminating five minutes of necessary human work instead saves $5. Neither saving is a measured outcome of this model. The example shows why the cost share determines the leverage of a price cut.

This does not mean inference cost is always negligible. High-volume services, expensive reasoning, repeated tool use and long-context processing can make it the dominant expense. The economically relevant object is a frontier over quality, total cost, latency and coverage. There is no generally cheapest model independent of the task and its constraints.

**R01-S05 evidence capsule.** Kapoor and colleagues experimentally show why accuracy-only agent rankings can mislead. In HumanEval, simple retry and escalation baselines challenge the contribution attributed to elaborate architectures; in HotPotQA, joint optimization reduces expenditure without sacrificing comparable accuracy. The work also distinguishes model-development evaluation from downstream procurement and documents holdout/reproducibility problems. These are controlled benchmark comparisons, not enterprise return estimates. [S05]

A further methodological consequence follows. “Cheaper cognition” should not combine a price reduction from one provider, an accuracy score from a different scaffold, and a human productivity estimate from a third domain. Each ingredient may be sound separately while the constructed economic claim is unsupported. A comparison needs the same task mix and terminal state, or an explicit, testable mapping between them.

## 3 Capability expansion and the verification problem

### Time horizons are difficulty measures

**R01-S06 evidence capsule.** Kwa and colleagues' software-task study fits success probabilities against human completion times and reports a roughly seven-month historical doubling of the 50% time horizon. It combines software, machine-learning and cybersecurity tasks with expert baselines. The study finds worse performance on messier tasks, though similar growth trends within its messiness split, and explicitly conditions extrapolation on generalization. Its historical growth estimate is neither a law of future progress nor an estimate of how long a model runs without oversight. [S06]

**R01-S07 evidence capsule.** METR's current documentation explains that human baselines resemble low-context expert work, rather than the daily work of a professional already familiar with a project. Tasks are deliberately self-contained and scoreable. The page warns that estimates above sixteen hours are unreliable with the current suite and that coverage of recent models is incomplete. Its 50% metric is a task-success probability threshold, not a 50% confidence interval or a general employment-replacement rate. [S07]

**R01-S08 evidence capsule.** METR's March 2026 sensitivity analysis records the March 3 correction of unintended regularization and investigates alternative curves, task subsets and noisy human-time estimates. Recent 50% horizons can move materially under reasonable choices; the author identifies task distribution and human time as a difficulty proxy as larger uncertainties. The sensitivity exercise does not show that progress disappeared, but it prevents treating a particular high-end point estimate as exact. [S08]

The distinction matters economically even if the fitted trend continues. A 50% success probability can be attractive for a reversible, easily checked attempt with a valuable upside. It is inadequate by itself for an unattended consequential action whose errors are expensive or hard to detect. Higher reliability requires a different threshold and evidence. A task-time metric also does not include the customer's cost of describing the task, supplying context, granting access, checking results or handling failed attempts.

Repeated attempts deserve particular care. With independent attempts of constant cost c, constant success probability p, perfect recognition of success, no deadline and retry until success, expected cost is c/p. Real cases violate these assumptions: some remain unsolvable across retries; faults correlate; verification itself can err; a failed attempt can damage the environment; and the next attempt may be longer. A benchmark pass-at-k statistic is not a deployment success rate unless a feasible selector can identify the good attempt. The formula is a useful limiting case, not a conversion factor to apply blindly to a leaderboard.

### Accuracy and economic reliability can rank systems differently

**R01-S09 evidence capsule.** Zellinger and Thomson formalize model choice using prices of errors, latency and abstention. Their experiments compare six models on numeric-answer MATH problems and show that confidence-based routing can change economic rankings. The framework is useful, but the tests use the MATH training split and an LLM judge with reference answers. They do not validate the paper's extrapolation to professional domains with different loss distributions and verification problems. [S09]

Consider a reviewer who accepts a correct answer with probability a and an incorrect answer with probability b. If a generator is correct with probability p, the fraction of accepted answers that are correct is pa/[pa + (1−p)b]. This elementary identity highlights two independent levers: generation quality and review discrimination. Increasing throughput while holding review capacity fixed need not preserve a or b. A nominal human approval step is not a costless guarantee, and agreement among similar models is not independent evidence.

Nor should uncertainty be hidden inside an average loss estimate. Rare consequential errors can be absent from a small evaluation. A deployment may face model updates, new clients, adversarial input, or changed tools unlike its validation sample. Operationally relevant research therefore reports uncertainty about both frequency and severity, coverage of the tested distribution, and what happens when the system declines. Declining a query can be economically sensible if a fallback exists; if no qualified reviewer is available, “human in the loop” only names an unfilled requirement.

The campaign's [R-13 institutional reliability review](../R-13/README.md) is responsible for the detailed evidence on consistency, correlated failures, recovery and enforceability. R-01's contribution is the accounting implication: every control has both a benefit and a resource requirement, and must be included in the policy being compared. Institutional cost does not refute cheap inference; it determines how much of that cheapness reaches useful output.

## 4 From controlled performance to work in organizations

**R01-S10 evidence capsule.** Dillon and colleagues' November 2025 revision analyzes randomized Copilot access for 7,137 workers in 66 large firms. In months 4–6, Table 2 reports weekly Outlook-session reductions of 1.37 hours by assignment and 2.03 hours by instrumented use; the email analysis includes 6,441 workers. It detects no broad shift in task quantity or composition. Telemetry measures activity, not output quality or full productivity, and firm participation and worker selection limit transport. The updated estimand should replace the earlier May headline when citing this version. [S10]

This experiment offers a useful middle ground between a benchmark and an economy-wide claim. The integrated tool reduces the friction of access; randomized availability identifies a change under that organizational arrangement. But a saved session minute is not automatically an additional minute of valuable output. It could become concentrated attention, shorter hours, additional unmeasured work, or slack. The absence of measured task expansion over this interval is evidence against treating expansion as automatic; it does not establish permanent demand saturation.

Three shared source capsules supply essential comparisons without duplicating their evidence here:

- [R-09 on AI-mediated transfer](../R-09/README.md#ai-mediated-transfer-and-its-limits) examines a deployed customer-support system and its outcome measurement. For R-01 the question is which parts of its task, information environment and measured completion process transport to other settings.
- [R-10 on P&G cross-functional work](../R-10/README.md#pg-cross-functional-innovation-capsule) and [the BCG task boundary](../R-10/README.md#bcg-task-boundary-capsule) show why a capability claim needs the task distribution and treatment package. Comparing results requires keeping assessed proposals, correctness and completed operational outcomes separate.
- [R-05 on the Danish evidence](../R-05/README.md#the-danish-test-work-changes-before-pay) relates changed work practices to labor-market outcomes. It cannot be treated as a direct estimate of completed-task unit cost, just as a successful task experiment cannot be treated as a wage estimate.

The findings can coexist. A useful tool in a standardized information environment, a poor match to another reasoning task, and limited organizational reallocation are different observations. Generalization requires a mechanism: availability of relevant information, task decomposability, user skill, feedback, incentives and integration. “AI helps” and “AI fails” are too coarse to explain the comparison.

The system boundary also changes the apparent result. Saving a writer an hour while requiring a reviewer an extra hour shifts work. Saving both hours but increasing downstream errors changes quality. Replacing a costly attempt with a cheap failed attempt changes neither completed output nor welfare in the claimed direction. A rigorous study must include rejected drafts, abandoned cases, rework and other people's time, rather than condition its cost estimate on visible successful use.

An elementary workflow calculation illustrates the aggregation limit. If a component uses share s of baseline task time and becomes a times faster, unchanged serial components leave total time at (1−s)+s/a of baseline. Doubling a component that consumed one fifth of time saves one tenth of total time. Real workflows can do better through redesign or worse through new coordination costs, but the result cannot be inferred from the component speedup alone. This is an analytical boundary, not an estimate of AI's average organizational effect.

## 5 Why some feasible tasks remain uneconomical

**R01-S11 evidence capsule.** Li and colleagues' March 2026 model makes automation intensity a cost-minimizing choice. A vision-model scaling experiment, occupational survey of 3,778 respondents and GPT-4o task decomposition feed a calibration in which fixed development cost and required accuracy limit firm-level adoption; partial automation can dominate full automation. Its approximately 11% result concerns vision-exposed compensation under its firm-scale assumptions, not observed generative-AI adoption. Output, wages and the set of tasks are held fixed, excluding the extensive-demand question by construction. [S11]

This provides a substantive alternative to the view that partial automation is only an awkward transition toward complete replacement. If the last increment of reliability costs more than the residual human work it saves, an interior division can remain economical even while models improve. Conversely, shared infrastructure and better general models can reduce setup costs, changing that division. The model's mechanism does not justify predicting a permanently fixed human share. Its numerical calibration cannot decide the economics of a new task whose information, quality standard or market value differs from the measured vision setting.

The following are boundary conditions deduced from the full-cost framework, rather than asserted prevalence estimates:

1. **Low repetition and high setup.** A bespoke analysis performed once may never amortize data preparation, permission work or integration, even if its final model call is almost free.
2. **Cheap execution but expensive verification.** If the only reliable check recreates most of the expert work, generation savings can be small. An independently testable output has different economics.
3. **High consequences with weak detection.** A small residual error probability can dominate the expected saving; an unacceptable tail risk can bar a workflow independently of expected value.
4. **Missing inputs or authority.** More inference cannot recover unavailable facts, establish consent or create a valid institutional right to act. A model may help acquire information, but acquisition belongs in the cost.
5. **Latency or coordination constraints.** An otherwise good answer that arrives after the decision has no equivalent value. Faster generation does not remove waiting for an external actor.
6. **Low incremental benefit.** Additional drafts, monitoring messages or recommendations can have diminishing value and create attention costs for recipients. An output can be technically competent and socially unwanted.
7. **Fragile reuse.** A workflow that requires frequent redevelopment or model revalidation has a smaller effective utilization base than a demonstration suggests.
8. **Scarce complements.** Reviewers, trustworthy data, implementation capacity, customer attention and physical capacity can bind. Their scarcity is task- and time-specific; it is not an eternal human monopoly.

Each condition admits improvement. Better validation, richer context, reusable interfaces or organizational learning can shift the threshold. The research implication is to measure those shifts rather than assume either universal automation or a permanent barrier. A low present benefit-cost ratio can also rationally support waiting when capabilities and switching costs are uncertain. Nonadoption therefore need not mean inability to recognize an opportunity.

<a id="demand-expansion-is-conditional"></a>

## 6 Demand expansion is conditional

### Intensive and extensive margins require different evidence

The intensive margin increases useful work within a previously served activity: more candidate solutions, wider testing, more frequent checks or deeper analysis. It should be measured in what those additional operations accomplish, not simply in token length. The extensive margin adds activities, users or services that were not previously economical. Those are related but distinct: switching an existing workflow from one provider to another is neither a new task nor evidence of aggregate expansion.

For a candidate activity j, let B_j be expected incremental benefit and K_j the relevant full cost, including the scarce complements above. A falling K_j can bring activities across the B_j ≥ K_j threshold. The magnitude depends on how many activities lie near that threshold and whether sufficient complementary capacity exists. A very large stock of conceivable questions is not a measured distribution of positive-value opportunities. Demand can also grow because capability, awareness, income or organizational access changes rather than because price alone falls.

The strongest optimistic mechanism is therefore not that everyone wants infinitely more text. It is that cheaper, sufficiently reliable operations expose useful applications previously excluded by setup and execution costs. The skeptical mechanism is not that such applications cannot exist. It is that the residual costs, low willingness to pay and diminishing benefits may dominate many potential uses. The empirical disagreement should be tested at the level of those mechanisms.

### Direct inference-demand evidence does not settle the aggregate question

**R01-S12 evidence capsule.** Demirer, Fradkin, Tadelis and Peng's December 2025 working paper uses OpenRouter and Azure evidence. Its preferred open-model provider–model–day regression reports a prompt-price coefficient of −1.11 (SE 0.22; 32,539 observations), with model-date and model-provider fixed effects. Provider switching, routing algorithms and endogenous service conditions complicate causal interpretation. The authors interpret near-unit provider elasticity as evidence against short-run aggregate/model-level Jevons effects (§7.3/conclusion), while leaving long-run expansion open; this is their interpretation, not direct identification of aggregate elasticity. Its statistical uncertainty includes unit elasticity. [S12]

**R01-S13 evidence capsule.** Borri, Liu and Tsyvinski's September 2026 revision provides a direct countercomparison using granular licensed OpenRouter data. Appendix IA.6, Table IA.19, Panel C reports −1.170 with date and model effects, but +0.280 (t=0.79; 53,800 observations) with model-date and model-provider effects. This is not a significant upward-sloping demand curve. It shows that the negative estimate is not robust across these observational reconstructions; the exact source of the discrepancy remains unresolved here. [S13]

**R01-S14 evidence capsule.** OpenRouter's own August 28, 2026 report states that heavily discounted GPT-5.6 Terra and Luna saw a 13.8-fold token increase, mixing additional usage with substitution. This is relevant contrary descriptive evidence to a claim that users never respond strongly to price. The public statement does not supply a randomized counterfactual, a full-cost measure or a useful-completion denominator. [S14]

Together these sources justify a more careful conclusion than either “Jevons is proven” or “demand is inelastic.” The first regression is preliminary and market-specific; the second raises a material robustness question; the platform example observes a large joint change without identifying its cause. None directly measures all final users' willingness to pay for additional verified outcomes over a long adjustment period. The larger licensed dataset is not automatically the right causal design, and public availability of a regression table does not make its restricted underlying data independently replicable in this review.

There are also three different outcomes often collapsed into “demand”: completed services, spending on inference, and physical resources such as compute or electricity. They need not move together. Under the elementary constant-elasticity assumption Q=A C^(−ε), lower effective service cost C raises Q if ε is positive; spending on that service rises only if ε exceeds one. This mathematical assumption does not estimate ε, and constant elasticity need not persist as costs approach a floor or wants saturate.

For resource rebound, suppose r units of compute are required per completed service and let s be the local elasticity of its total service cost with respect to r. Holding quality, other prices and task composition fixed, total resource use R=rQ has local elasticity 1−sε with respect to r. An efficiency improvement raises total resource use only when sε>1. If inference is a small share of effective cost, the required demand response is correspondingly larger. This derivation assumes a particular pass-through and technology structure; it is not a claim that market price cuts identify physical efficiency.

Even verified compute rebound would not imply more human work, better wages or a particular distribution of surplus. Human labor per service can fall, rise through complementary activity, or move elsewhere. [R-12](../R-12/README.md#the-expanding-volume-of-cognition-is-not-the-same-as-expanding-human-employment) owns the macroeconomic and labor-demand analysis, including its Bessen source capsule; [R-18](../R-18/README.md) owns the historical Jevons audit. Their mechanisms are not substitutes for the missing contemporary useful-task elasticity.

Finally, exponential price decline and constant positive elasticity can algebraically produce exponential volume growth over a specified interval. That is a conditional model, not proof of S-07's categorical prediction. Finite budgets, heterogeneous tasks, changing complements and diminishing benefits can change both parameters and functional form. “Exponential” should not function as a synonym for “large.”

## 7 What follows for the coupled production system

The research supports a system-level evaluation principle without selecting a universal architecture. Specification can constrain tasks, deterministic software can cheaply check some properties, and routing can direct scarce attention toward difficult cases. These are candidate ways to improve the joint cost-quality frontier. They can also introduce new failure modes, coordination work and fixed costs. A small organization with a stable, low-volume task may rationally prefer a modest assistive tool to an elaborate agent system.

The relevant comparison is between complete feasible arrangements, including the preexisting system. “Model versus human” can omit the code, databases, procedures and supervision that make either productive. “Redesign versus no redesign” can omit the transition costs and embodied knowledge in the inherited process. A redesign earns its place through lower full costs, improved outputs or expanded beneficial coverage under acceptable risk, not through its architectural novelty.

The book's more durable claim is thus about **revisable allocation under changing relative capabilities and costs**. A model can become cheaper, yet a workflow can still need more expert attention because it has expanded into harder cases. An expert can become more productive while the institution fails to capture the gain because another stage binds. A firm can capture value without a large volume increase. These possibilities preserve the production-system insight while blocking unwarranted inference from one attractive metric.

This review also identifies a distinction for C-053: maintaining present output and maintaining the capacity to judge future output are different investment problems. Treating review labor as an expense today does not reveal whether the institution is reproducing it. The [R-08 apprenticeship review](../R-08/README.md) and R-09 supply the learning and labor-stock evidence. Their conclusions must be incorporated before a full-cost analysis is used to recommend reducing developmental work.

## 8 Claim-level evidence ledger

Judgments apply to the stated proposition and scope. “Researcher-derived test” marks an inference examined by this review, not a claim silently attributed to Luke.

| Review ID | Admitted claim or explicit test | Judgment | Evidence and limit |
|---|---|---|---|
| R01-C01 | C-001: useful machine cognition is becoming a cheap, provisionable input | **Revised/qualified** | §§1–3, S01–S08. Strong direction for selected capabilities; no uniform useful-task price index. |
| R01-C02 | C-001: cheaper provisionable cognition is expanding cognition applied per existing task | **Mechanism supported; ongoing intensive-margin expansion is incompletely measured** | §§2–4. Feasibility and selected usage evidence do not establish a representative quality-adjusted cognition-per-task trend or its magnitude. |
| R01-C03 | C-001: cheaper provisionable cognition is expanding the set of tasks worth attempting | **Threshold mechanism supported; realized extensive-margin expansion and population magnitude remain qualified/unresolved** | §§5–6. Full costs below expected benefits define the threshold; technical possibility alone does not measure actual diffusion or net new useful work. |
| R01-C04 | Researcher-derived test: token-price decline measures an equal decline in completed-work cost | **Contradicted as a measurement identity** | §§1–2. Different units and omitted complements. |
| R01-C05 | Researcher-derived test: fixed-performance and frontier-performance prices must move together | **Contradicted in stated scope** | §2, S02–S03. Different quality targets. |
| R01-C06 | Researcher-derived test: a successful output alone identifies economic substitution for a worker | **Contradicted as an inference** | §§1, 3–4. Coverage, context, losses and full task boundaries missing. |
| R01-C07 | Researcher-derived test: METR time horizon is autonomous wall-clock duration | **Contradicted in stated scope** | §3, S06–S08. Human-time task-difficulty metric. |
| R01-C08 | Researcher-derived test: an exponential time-horizon fit proves future whole-job automation | **Unresolved forecast; inference not established** | §3. Distribution, reliability and organizational mapping required. |
| R01-C09 | Researcher-derived test: retries turn observed pass-at-k into equally reliable deployment | **Revised/qualified** | §3. Requires selection, affordable checking and dependence analysis. |
| R01-C10 | C-006: the coupled system is the relevant economic object | **Supported as an evaluation principle** | §§1–5, 7. Joint costs and outcomes determine feasibility. |
| R01-C11 | Researcher-derived overextension of C-006: organizational redesign always dominates task assistance | **Unresolved and not warranted universally** | §§4, 7. Transition cost and baseline alternatives matter. |
| R01-C12 | S-07/C-045: the marginal cost of thought approaches zero in economically relevant work | **Revised/qualified** | §§1–2, 5. Some inference inputs are very cheap; complete-work costs need not converge to zero. |
| R01-C13 | S-07/C-045: highly elastic corporate demand yields exponentially greater output | **Unresolved as an empirical generalization** | §6, S12–S14. Direct estimates conflict and have narrower units. |
| R01-C14 | Researcher-derived test: inference demand has a settled elasticity of −1.11 | **Contradicted as a settled empirical characterization** | §6. An estimate and a material counterestimate require reconciliation. |
| R01-C15 | Researcher-derived test: no observed immediate task expansion proves no extensive-margin potential | **Contradicted as an inference** | §§4–6. Horizon, coverage and fixed-cost adjustment differ. |
| R01-C16 | Researcher-derived test: full automation is always cheaper than partial automation when technically feasible | **Contradicted as a universal economic proposition** | §5, S11. Accuracy and deployment scale can create an interior optimum. |
| R01-C17 | Researcher-derived test: task productivity improvements establish more labor demand or higher wages | **Unresolved without additional demand and distribution evidence** | §§4, 6; R-12. |
| R01-C18 | C-053: fallible cognition requires evaluation of institutional complements | **Supported in this economic scope** | §§1, 3, 7. This does not validate any particular MKS mechanism. |
| R01-C19 | Researcher-derived overextension related to C-053: reproduced human capability and future adaptive capital follow from cheaper inference | **Unresolved here; separate evidentiary burdens** | §7; R-08/R-09/R-13/R-14. |
| R01-C20 | Researcher-derived test: technically competent but uneconomical tasks can persist | **Supported as conditional mechanisms; prevalence unresolved** | §5. Explicit cost, information, value and constraint cases. |
| R01-C21 | C-053: the shared thesis combines revisable production design, reproduced human capability and institutions around fallible cognition, with adaptive capital a conditional extension | **R-01 assesses the input-cost and feasibility component only; the full synthesis requires other programs** | §7 and cross-program synthesis. No implication that cheaper inference alone supplies learning, institutional reliability or adaptive capital is attributed to C-053. |

## 9 Investigated gaps and discriminating research designs

These are evidence gaps after examining price studies, technical evaluations, deployment telemetry, economic models and direct demand estimates. They are not labels for unperformed parts of this review.

**A quality-constrained useful-task price index.** No examined source supplies a representative longitudinal basket of completed workflows with all failed attempts, review and integration included. A useful design fixes terminal states and measures several feasible policies on recurring samples, repricing cash inputs while separately measuring resource use. It should publish a fixed-quality index and a changing-quality frontier, rather than force them into one series. Benchmark saturation and changes in the economically relevant task mix require explicit treatment.

**Causal long-run extensive demand.** The observed price studies do not isolate durable new tasks from model switching, more verbose reasoning, platform growth and altered capability. Randomized discounts for the same model and service quality could identify a short-run price response. Longer follow-up with preregistered task portfolios could identify new sustained activity. Separately varying integration assistance would distinguish execution cost from setup cost. Useful-completion quality, other-provider substitution and abandoned attempts must be observed.

**The conflicting OpenRouter estimates.** Reconciliation requires a common period, identical model/provider matching, price definitions, zero/free-tier handling, weights, fixed effects, clustering and the same dependent variable. The licensed microdata were not available to this review. Neither selecting the larger dataset by authority nor averaging the two coefficients would resolve identification. A clean supply-side price shock or experiment remains valuable after descriptive reconciliation.

**Verification economics across stakes.** Studies should randomize generation and review policies separately while auditors assess latent output quality. Measure false acceptance, false rejection, review time, fallback availability and downstream rework. Accuracy improvements may reduce review cost, while expansion to harder tasks may raise it. The appropriate counterfactual includes human error. High-consequence domains require suitable safeguards rather than exposing real users to intentionally unsafe treatment.

**Utilization and obsolescence.** A fixed integration investment can be worthwhile at high volume but uneconomical for a short-lived local need. Longitudinal samples should include firms that considered but declined adoption and projects that failed. Tracking only launched projects selects on success. Measure how frequently model changes, data changes and institutional changes require revalidation, and whether reusable components lower future setup costs.

**Scarce complements and network effects.** A factorial design comparing individual access, team access and workflow changes would separate private task gains from coordination effects. Reviewer queues, management attention and implementation capacity are observable constraints. Firm-level randomization may be needed when spillovers contaminate individual comparisons. A redesign treatment must include its implementation cost and learning curve.

**Welfare and demand quality.** More generated material may serve a valuable unmet need, displace an existing service, or impose unwanted attention costs. These outcomes require beneficiary-level evaluation and, where appropriate, willingness-to-pay or outcome measures. They cannot be distinguished by higher token use. R-11 and R-12 address accounting and general equilibrium; neither inference revenue nor a low posted price should be substituted for welfare.

## 10 Dependencies and author decisions

- **R-02:** use the price and time-horizon distinctions here; own the coding experiments, lifecycle evidence, nondeveloper diffusion and admitted OpenAI delegation leads. User-reported delegation duration is a separate measurement from benchmark time horizon.
- **R-04:** test whether redesign causally improves completed work and which historical analogy survives; do not use component price change as proof of the redesign mechanism.
- **R-05/R-11/R-12/R-15:** distinguish full cost, revenue, surplus, labor demand and capture. R-12 can reference the demand section rather than repeat the source capsules.
- **R-06/R-07/R-13:** identify which information and authority constraints can actually be changed, at what cost, and how verification and intervention function.
- **R-08/R-09/R-10:** ensure cheaper assisted output is not mistaken for reproduced independent skill or effortless cross-domain judgment.
- **R-14/R-16/R-17:** distinguish persistent records, learning and relationship-specific productivity from simply purchasing more inference.

Luke retains the decision whether “abundant cognition” should name a comparative supply shift, a future conjecture, or a claim about completed work. The evidence favors specifying which meaning is intended. How much residual risk is acceptable, which developmental investments should be protected, and how human authority should be allocated are substantive author choices; this review does not settle them by minimizing an accounting ratio.

## 11 Recoverable bibliography and source-access appendix

All sources were inspected on 4 October 2026. Dates below identify the versions actually used, not merely the latest date on a search result. Main source-derived findings are concentrated in capsules to avoid repetitive restatement. Public full text was read in HTML or extracted PDF at the locators below; no paid service, account creation, third-party contact, private author material or restricted source data was used. Downloaded publications were inspection copies, not proposed republication. Regressions, benchmark runs and licensed datasets were not independently replicated.

**R01-S01.** Ben Cottier, Ben Snodin, David Owen and Tom Adamczewski. 2025. [LLM inference prices have fallen rapidly but unequally across tasks](https://epoch.ai/data-insights/llm-inference-price-trends). Inspected narrative, threshold table, methods/footnotes and download metadata; downloadable series marked updated 20 November 2025. Research-organization data analysis; source populations are models chosen for benchmarks, not firms. No independent reconstruction of the underlying series.

**R01-S02.** Hans Gundlach, Jayson Lynch, Matthias Mertens and Neil Thompson. [The Price of Progress: Price Performance and the Future of AI](https://arxiv.org/html/2511.23455v2). arXiv:2511.23455v2, 23 March 2026, initially 28 November 2025. Read §§2–6 and dataset/preprocessing appendix. MIT FutureTech preprint; not a transaction-price or workplace experiment. Prices are reconstructed from Artificial Analysis snapshots with Epoch token counts; the smallest benchmark sample makes extrapolation especially uncertain.

**R01-S03.** Luke Emberson and David Roodman. [The plunging price of thought](https://epoch.ai/publications/the-plunging-price-of-thought). Epoch AI report, 22 September 2026. Read Data, Modeling, On bootstrapping, Results and Limitations. Five primary benchmarks; model-setting coverage is nonrandom, with truncation/guessing conventions and mixed API/hardware costing. Methods and code are public, but no replication was performed. The report is not a peer-reviewed workflow study or a reliable basis for an exact historical-superlative claim.

**R01-S04.** OpenAI. [API Pricing](https://developers.openai.com/api/docs/pricing), standard pricing snapshot retrieved 4 October 2026; [machine-readable page](https://developers.openai.com/api/docs/pricing.md). Inspected model/context/service tables and tool tariffs. Vendor source authoritative for its posted terms, not an independent effectiveness assessment. Current rates cannot retrospectively reprice a study without its token and tool counts.

**R01-S05.** Sayash Kapoor, Benedikt Stroebl, Zachary S. Siegel, Nitya Nadgir and Arvind Narayanan. [AI Agents That Matter](https://arxiv.org/html/2407.01502v1). arXiv:2407.01502v1, 1 July 2024. Inspected §§2–6, including cost-accuracy experiments and benchmark-design discussion. HumanEval/HotPotQA and selected agents delimit inference; the public version's old prices are not presented as current.

**R01-S06.** Thomas Kwa and colleagues. [Measuring AI Ability to Complete Long Software Tasks](https://arxiv.org/html/2503.14499v4). NeurIPS 2025; arXiv:2503.14499v4, 10 July 2026. Inspected §§2–4, horizon computation, baseline/scaffold and external-validity material. The paper describes a 170-task suite; baseline text refers to 169 tasks, so no synthetic denominator is imposed here. Version 4 records an author-list correction; current dashboard updates are separately sourced.

**R01-S07.** METR. [Task-Completion Time Horizons of Frontier AI Models](https://metr.org/time-horizons/). Live methodology/FAQ snapshot, 4 October 2026. Read task construction, baselining, reliability and coverage caveats, elicitation and update log. This page's evolving suite and six-run protocol should not silently replace the original paper's approximate eight-run protocol. Model records do not constitute complete frontier coverage.

**R01-S08.** METR. [Impact of modeling assumptions on time horizon results](https://metr.org/notes/2026-03-20-impact-of-modelling-assumptions-on-time-horizon-results/). 20 March 2026. Read regularization, alternative fits, private-task restriction, noisy-length/SIMEX analysis and conclusion. Exploratory sensitivity analysis, not a new representative labor sample. Its uncertainty correction is itself uncertain; no precise alternative horizon is adopted here.

**R01-S09.** Michael J. Zellinger and Matt Thomson. [Economic Evaluation of LLMs](https://arxiv.org/html/2507.03834v1). arXiv:2507.03834v1, 4 July 2025. Read §§3–4, limitations and cascade derivation. Numeric-answer samples have 500 problems at each of three difficulty levels; cascade tuning/evaluation splits them. Abstract/conclusion and §4.3/Figure 3 report different error-cost crossover figures; they are not harmonized into a universal threshold here. Estimated loss prices are application inputs, not observed losses in the experiment.

**R01-S10.** Eleanor Wiske Dillon, Sonia Jaffe, Nicole Immorlica and Christopher T. Stanton. [Shifting Work Patterns with Generative AI](https://arxiv.org/html/2504.11436v4). arXiv:2504.11436v4, 13 November 2025; NBER Working Paper 33795. Read §§1–3, Tables 2–3, appendices A–B and telemetry/quality caveats. Multinational large firms, mainly US/European workers; September 2023–October 2024 experiment. Three authors worked at Microsoft, which reviewed privacy; authors report discretion over results. Session-based telemetry can overlap across applications; use/assignment estimands differ.

**R01-S11.** Wensu Li, Atin Aboutorabi, Harry Lyu, Kaizhi Qian, Martin Fleming, Brian C. Goehring and Neil Thompson. [Economics of Human and AI Collaboration: When is Partial Automation More Attractive than Full Automation?](https://arxiv.org/html/2603.29121v1). arXiv:2603.29121v1, 31 March 2026. Read §§3.2–5.5 and survey/cost appendices. MIT/EPFL/IBM affiliations; US occupational calibration, 2023 survey, vision fine-tuning, entropy-to-labor mapping and model-generated decompositions. Engineering costs come from one IBM forecasting deployment. Perfect-substitution and classification assumptions limit extension to organizational knowledge work.

**R01-S12.** Mert Demirer, Andrey Fradkin, Nadav Tadelis and Sida Peng. [The Emerging Market for Intelligence: Pricing, Supply, and Demand for LLMs](https://nadavtadelis.com/files/EmergingMarketForIntelligence_12_12_2025.pdf). Author PDF dated 12 December 2025; NBER Working Paper 34608. Read §3, §7, introduction and conclusion, particularly pp. 34–38/Table 2. OpenRouter is startup/developer-heavy; provider disaggregation begins in 2025. Microsoft/Amazon affiliations disclosed. NBER retrieval failed; the publicly linked author copy was accessible. The [2026 three-author JEP companion](https://doi.org/10.1257/jep.20261506)'s metadata was checked, not its inaccessible full text; its publication does not validate the earlier elasticity estimate.

**R01-S13.** Nicola Borri, Yukun Liu and Aleh Tsyvinski. [The Cross-Section of Stock Returns and AI Exposure](https://arxiv.org/html/2606.30583v3). arXiv:2606.30583v3, 24 September 2026; earlier title *AI Premium*. Inspected data definition, introduction and Appendix IA.6/Table IA.19. The January 2024–April 2026 platform panel is licensed and not independently accessible here; research relies only on the public paper. The equity-return results are outside this review's evidence claim. Its inference users are not a representative economic population.

**R01-S14.** OpenRouter. [OpenRouter Data](https://openrouter.ai/data), snapshot 4 October 2026, especially statements dated 28 August 2026. Inspected the public platform report through web retrieval; direct download returned 403. Vendor marketing/telemetry statement, not an independently audited natural experiment. No raw data or claims of causal attribution are supplied here.

### Shared sources and access limits

The detailed customer-support, P&G/BCG, Danish, Bessen and historical capsules remain with R-09, R-10, R-05, R-12 and R-18 respectively, as linked above. This review uses their analytical relevance without reprinting their summaries. The [R-13 review](../R-13/README.md) should own detailed reliability synthesis; Rabanser et al.'s [June 2, 2026 v3](https://arxiv.org/html/2602.16666v3), including experimental setup and limitations, was examined as a coordination lead rather than a separate quantitative result here.

The Noy–Zhang writing study was investigated as a potential additional causal source. The accessible March 2023 MIT manuscript differs from the final Science record, whose full text returned 403. Because other accessible causal evidence and the shared reviews already cover the required contrast, no final-version effect size is inferred from that older manuscript. The Stanford AI Index headline was likewise treated as a lead to underlying price research rather than an additional independent observation.

### Method discipline and unresolved source issues

Searches targeted effective inference cost, benchmark price-performance, task horizons, workflow experiments, automation feasibility and inference-price elasticity, including contrary and newer results. This was a purposive analytical review, not a preregistered exhaustive systematic review. Sources were selected for their ability to distinguish denominators and mechanisms; working papers are labeled accordingly. Rapidly changing technical and tariff evidence is date-bounded.

The most important repairs during research were replacing old Dillon headlines with the November version, separating the METR paper from the corrected live method, finding the newer Borri counterestimate, distinguishing the Demirer working paper from its JEP companion, and declining to adopt a universal Zellinger numeric threshold. These are provenance and interpretation repairs, not changes to protected author material.

No claim is made that the downloaded data, published estimates or mathematical implementations were independently replicated. The formulas in §§1, 3, 4 and 6 are transparent analytical illustrations with stated assumptions. They are not fitted to the book's author experience. Outstanding empirical gaps remain in the ledger and research agenda rather than being resolved by rhetoric or author preference.
