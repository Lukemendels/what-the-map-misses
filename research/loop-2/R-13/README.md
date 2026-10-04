# R-13 Institutional reliability and MKS mechanisms

**Analytical literature review for What the Map Misses**  
**Research date:** 4 October 2026  
**Admitted claims:** C-026, C-028, C-029, C-030, C-031, C-053  
**Status:** Substantive literature review accepted after independent quality review; neither an adopted thesis nor validation of an MKS implementation. Remote durability is verified separately after publication.

## 1 Findings and scope

The strongest defensible institutional claim is conditional: fallible models can be made more useful and some failures less consequential by changing the system around them. This does not establish that a particular institutional architecture is reliable, that oversight is inexpensive, or that better organization can compensate for every capability shortfall. Institutions also introduce failure modes: a mistaken specification, shared evidence, a compromised record, an overloaded reviewer, or a defective gate can distribute error more efficiently.

Three distinctions carry this review. A deterministic mechanism can enforce a precisely represented condition without establishing that the condition adequately describes the world. A reliable record of what a system did is different from a faithful explanation of why a model produced its answer. Recovery from one incident is different from learning that prevents its recurrence. These distinctions preserve the current synthesis's institutional argument while sharply qualifying several stronger claims in the historical MKS specifications.

The admitted texts are [V3](../../../source/theory/05-mks-v3-master-specification.md), [V4](../../../source/theory/06-mks-v4-trust-first-architecture.md), and [the current synthesis, §§8–9](../../../source/synthesis/2026-09-11-current-author-synthesis.md). They are objects of analysis, not instructions to execute. No private system, unpublished experiment, personal account, or claimed live implementation was inspected. References to tests below propose future public research; they do not report tests performed here.

The historical [claim ledger](../../../evidence/claims/CLAIM-LEDGER.md) is preserved. V3 calls its architecture a solution to the principal–agent problem, proposes generator/critic/enforcer cells, and suggests that logic traces convert a credence good into a search good. V4 shifts toward delegated initiative and local correction, yet retains categorical language about a reality discriminator, an absolute ruin barrier, and skill loading that eliminates instruction contamination. The current synthesis expressly separates enduring institutional functions from possibly premature machinery. That narrowing matters: evidence for one function cannot retrospectively validate the whole earlier package.

R-13 owns the detailed reliability evidence below. [R-01](../R-01/README.md) treats useful-task economics; R-04 treats model/code/human workflow redesign and PAL; R-07 treats human oversight, intervention and legitimacy; R-14 treats external state versus persistent learned capability. The latter programs are dependencies, not findings presumed complete by this review.

## 2 What a reliability claim must specify

### Reliability is a property of a defined system in an operating environment

“Reliable” must identify a task distribution, model and scaffold version, tools, permissions, time horizon, success criterion, failure severity and operating conditions. A model that usually answers correctly can be unsuitable for unattended action. Conversely, variable language or alternative successful plans may be desirable in creative work. Identical trajectories are not a universal objective.

[R13-S01: Rabanser et al.](#r13-s01) evaluate 15 models on GAIA's 165 validation tasks and a corrected 26-task airline subset of τ-bench, using one scaffold per benchmark and five runs per task. Their June 2026 v3 separates consistency, robustness, predictability and safety. Capability gains did not yield comparable gains across these dimensions; confidence calibration and discrimination also differed. Safety is excluded from the overall aggregate and assessed with LLM judging. Prompt perturbations and injected tool faults probe particular vulnerabilities, not every deployment stressor. The narrow benchmarks, scaffold dependence, subjective aggregation and fallible safety judge limit generalization. Provider compute credits and institutional/philanthropic funding are disclosed. This is evidence against treating task accuracy as sufficient, not proof that reliability cannot improve or that institutional design is the exclusive remedy.

A useful implication is to separate completion, compliance, recoverability and cost. “Passed the task” can coexist with unauthorized intermediate actions. “No prohibited action” can mean the system refused every useful task. “Recovered” can mean a second attempt succeeded after a first attempt already caused harm. These are different outcome variables and require separate denominators.

The synthesis's probability-times-consequence expression is an intelligible design aspiration, not a calculated safety bound. The probability of a failure propagating depends on detection, containment, exposure and common causes. Some consequences are reversible only in a narrow database sense: reversing a record cannot necessarily retract a disclosure or undo another person's reliance on a false statement. Expected loss alone can also conceal an unacceptable tail or unequal exposure. Deciding acceptable consequences remains a human and institutional judgment.

### Observable success and open-world truth

A test can settle whether a checksum matches, a file exists, an authorized identifier is present, a proof checker accepts a derivation, or a transaction satisfies an encoded limit. Such observations are valuable precisely because their semantics are narrow. A parser accepting `risk_level = safe` establishes a field value; it does not establish safety. A deterministic comparison between `map_state` and `territory_reality` requires a trustworthy representation of both. Naming the second variable does not create access to reality.

The distinction is not between fallible AI and infallible conventional software. Specifications, parsers, sensors, databases and human labels can all be wrong. The practical question is which uncertainty has been removed, which has been relocated and which remains unmeasured.

## 3 Deterministic enforcement and its limits

### External gates can have real force

[R13-S02: Saltzer and Schroeder](#r13-s02) provide the classical engineering foundation: simple protection mechanisms, permission-based defaults, complete mediation, separation of privilege and least privilege. Their discussion includes recovery, initialization, revocation and dynamically changing authority. These are design principles developed from security experience, not an experimental estimate of LLM safety. They nevertheless identify what an MKS orchestrator would need to do to make action restrictions more than prompting: all relevant effects must pass through a protected enforcement path.

For example, code can restrict an agent to a read-only interface or require a separately issued authorization for a write. The strength of the restriction depends on the actual interface and its bypasses, not on the model's willingness to obey a negative axiom. If a worker can change its own permissions, alter the evaluator, substitute a recipient, or reach the same effect through another tool, an apparently hard gate may be incomplete. Checking a proposed action also may not settle the state at execution time. Concurrent changes and retries require fresh authorization checks or an atomic commitment mechanism.

Formal verification is a stronger but still bounded comparison. [R13-S03: Klein et al.](#r13-s03) demonstrated machine-checked refinement from an abstract specification to the seL4 kernel's C implementation. The 2009 proof explicitly assumed compiler, assembly and hardware correctness and excluded boot initialization from its principal theorem. This is evidence that substantial guarantees can be achieved for well-defined software behavior. It is not a guarantee that the specification captures every policy objective, that arbitrary applications are correct, or that natural-language explanations reveal cognition. Current seL4 configurations have evolved; this review uses the historical paper's stated theorem and assumptions only.

For MKS, the useful design requirement is a guarantee inventory. Each proposed gate should say: the observable predicate; who supplies each input; which actions it mediates; what assumptions make the predicate relevant to a hazard; how uncertainty is represented; and what remains outside its coverage. The code can be deterministic while one of its inputs is an uncertain model classification. The resulting control is a hybrid, and should be evaluated as one.

### Prompt separation has empirical and architectural limits

[R13-S04: AgentDojo](#r13-s04) operationalizes indirect prompt injection through stateful tool use. Its November 2024 version contains 97 user tasks and 629 security cases, with separate measures for benign utility, useful completion under attack and attacker success. Deterministic checks over environment state avoid asking a potentially injectable simulator alone to judge security. Attacks and defenses remain bounded by the curated tasks, attack access and tool implementations. The relevant result is that defense effectiveness and useful-task completion must be measured together; a low attack-success rate is insufficient if legitimate work is mostly blocked.

[R13-S05: CaMeL](#r13-s05) supplies a constructive comparison. Its revised June 2025 Table 2 reports 77.3% utility versus 84.5% with native tool calling for o3 High on 97 AgentDojo tasks, using separated planning and untrusted-data handling plus externally enforced information-flow policies. This is a concrete mechanism for restricting consequences without requiring the model itself to be injection-proof. Its guarantees depend on the defined threat model, policies and implementation. Data-dependent plans, insufficient context, API documentation, side channels, policy maintenance and user declassification are material limits. The paper expressly rejects the claim that prompt injection is fully solved. Its version changes and inconsistent overhead summaries are recorded in the appendix; no universal cost multiplier is adopted here.

These studies do not directly test MKS. They do defeat the inference that loading selected Markdown headings *by itself* guarantees precision or eliminates cross-contamination. Loading fewer instructions may reduce irrelevant context and conflicting rules; it does not authenticate the module, resolve its authority, prove that relevant rules were selected, or prevent hostile content in later tool results from influencing generation. Isolation of privileges and information flows is a different mechanism from selective inclusion in a shared text context.

The strongest version of V4's discriminator is therefore unsupported. Belief weighting can determine what an application admits into a state store. It cannot, solely by that act, turn admitted material into objective truth. A practical discriminator must be described as a fallible source-validation or decision procedure with measurable false acceptances, false rejections and uncovered cases.

## 4 Criticism and redundancy under correlated failure

V3's generator/critic/enforcer division separates proposing from authorizing. That is useful only if the critic contributes information or capability the generator lacks, and the enforcer preserves the relevant restriction. Duplicating a model under a different role name does not establish independent errors. Different providers are also not automatically independent: they may share tasks, training material, misleading evidence or a deficient specification.

[R13-S06: Kim et al.](#r13-s06) examine responses from 349 models on one leaderboard and 71 on another, as well as an offline résumé-rating exercise. In HELM, model pairs selected the same wrong answer about 60% of the time *conditional on both being wrong*, compared with one-third under uniform choice among three wrong answers. This is not a 60% overall failure probability. Regression associations with provider, architecture and accuracy do not identify their causal effects. Multiple-choice scoring and shared question difficulty restrict extrapolation to open-ended agent work, but observed agreement plainly cannot be equated with independent corroboration.

An older technical comparison provides a useful qualification. [R13-S07: Knight's NASA report](#r13-s07), following the Knight–Leveson experiment, describes 27 independently produced student programs tested on one million inputs. Different faults could be triggered by the same difficult inputs. Yet multiversion arrangements still reduced failures in the studied application: correlation reduced the expected protection without making redundancy worthless. This is an analogy about common-cause error, not a numerical estimate for LLM ensembles. The distinction prevents the opposite overstatement that correlated critics can never help.

The institutional interpretation is to measure *conditional detection*: when a generator is wrong, how often does this particular critic catch the error before commitment? Overall critic accuracy is inadequate. A critic can score well on easy correct outputs and miss exactly the difficult errors that escape the generator. Blind review, independent evidence retrieval, distinct tools and a different model can be candidate treatments; none deserves an independence assumption merely because it is differently named.

[R13-S08: Cemri et al.](#r13-s08) add evidence about coordination rather than just model error. Their October 2025 v3 assembles 1,642 annotated traces from seven multi-agent frameworks; a taxonomy developed from 150 traces distinguishes system design, inter-agent alignment and verification failures. Most large-scale annotations use an LLM pipeline, and the smaller human-annotation exercises are different denominators. Interventions suggest some failures are repairable through changed roles or workflows with the base model held fixed. Framework/task selection, annotation uncertainty and limited interventions prevent a general causal claim that organization dominates model quality. A taxonomy of failure is not proof that its proposed categories exhaust causes.

For MKS, hierarchy can reduce some coordination costs while adding routing errors, stale instructions, duplicated actions and false consensus. The desired comparison is a resource-matched single-agent baseline, a simple generator/checker arrangement, and the more elaborate graph architecture. Adding components is a hypothesis about net system performance, not evidence of it.

## 5 Local repair and reset are conditional alternatives

V3 §5 genuinely entertains two alternatives. Theory A redrafts using criticism; Theory B terminates a repeatedly failing *specific kernel instance* and resumes from a last known good state. V4 §2.3 rejects systemic resets in response to localized failure and retains the failure history while redrafting a node. The historical supersession should remain intact, but the comparison must not falsely turn V3's component reset into a proposal always to erase the whole institution. A component restart that preserves trustworthy durable state can itself be a local repair.

[R13-S09: Candea et al.](#r13-s09) empirically demonstrate microrebooting in an auction application on JBoss. Fault injection and emulated workloads showed that restarting isolated components could recover many failures faster and with less lost work than process-wide restarts. The necessary architecture separated recoverable execution from important stored state. Failures below the component layer, persistent corruption and inaccurate localization could require broader recovery. This is controlled systems evidence for matching repair scope to fault boundaries, not evidence that deleting an LLM context cures hallucination.

Three different states must be distinguished in an AI recovery policy: the process executing the next step; the evidence and plan in the current context; and durable artifacts already written or actions already committed. Resetting one does not necessarily repair the others. If a false assumption has reached downstream artifacts, replacing the immediately failing node leaves contamination. If only a connection has failed, erasing validated work may be unnecessary. If a record is malicious, retaining it uncritically can reintroduce the same failure after every restart.

The redraft alternative also has limits. [R13-S10: Huang et al.](#r13-s10) tested intrinsic correction on reasoning tasks using 2023-era GPT and Llama models. Removing oracle correctness feedback frequently eliminated improvements or worsened answers; equal-response-budget comparisons and initial-prompt quality mattered. Their ICLR 2024 paper used full GPT-3.5 evaluation sets but smaller samples for other models, at most two correction rounds, and specific prompting regimes. It does not establish that all models or all forms of self-correction are incapable of improvement.

[R13-S11: Silver et al.](#r13-s11) provide contrary evidence under a different design: seven open-weight models could sometimes recover within a single continuation after synthetic perturbations to a reasoning stub. Performance varied substantially, and many introduced errors still defeated correction. The perturbations may be easier to detect than naturally generated mistakes; the grader was itself a model, and provider support for continuation was imperfectly established. This is evidence for a bounded capacity, not a contradiction of every earlier result. “Intrinsic correction” denotes different tasks when one study critiques a completed answer and another continues a visibly perturbed partial solution.

An appropriate repair policy would therefore diagnose the failure class, retain verified evidence, quarantine suspect state, invalidate dependent products, and compare a bounded redraft with a clean-context retry. It would stop or escalate when the action is irreversible, the relevant state cannot be reconstructed, or the failure repeats without new evidence. Neither endless deliberation nor automatic erasure is justified by the literature as a universal default.

## 6 Records are evidence of behavior and inputs to learning

### What logs can and cannot establish

A useful audit trail can identify the input artifact, requested action, authorization, executed tool call, returned result, accepted revision and evaluator version. If captured by an independently controlled logger, it can establish observable events with substantially greater confidence than an agent's narrative that it complied. It does not by itself establish that the evidence was accurate, the authorization legitimate, the action harmless or the model's stated rationale causally faithful.

[R13-S12: Turpin et al.](#r13-s12) experimentally manipulated biases in prompts to GPT-3.5 and Claude 1.0. Explanations could rationalize changed answers without disclosing the influential cue. The NeurIPS 2023 study uses controlled prompt comparisons on BBH and BBQ; it identifies instances of unfaithfulness, not a complete account of internal computation or the share of every model explanation that is unreliable.

The concern persists, but it is important not to discard useful signals. [R13-S13: Chen et al.](#r13-s13) tested Claude 3.7 Sonnet and DeepSeek R1 using paired multiple-choice prompts and six hint types. Used hints were often not acknowledged. Their synthetic reward-hacking experiments concern behaviors that need little extended reasoning, limiting extrapolation to more deliberative tool use. [R13-S14: Baker et al.](#r13-s14), in contrast, found that chain-of-thought access improved a GPT-4o monitor's recall of two systemic coding reward hacks from 60% to 95% relative to action/output monitoring. Direct optimization against the monitor could induce obfuscation. These are provider-run experiments in different environments, not competing estimates of one universal faithfulness parameter.

The synthesis is that explanatory text can help diagnosis and detection without proving the absence of concealed failure. A machine-checkable proof or replayable action log verifies a specified relationship between artifacts; a plausible paragraph explaining an answer is a different evidential object. V3's conversion of a credence good into a search good overstates what telemetry achieves. Some dimensions become easier to inspect; others remain expensive, expert-dependent or unverifiable before consequences occur.

A useful record should preserve failures and uncertainty, not just approvals. But preserving everything is not costless: volume can hide relevant evidence, sensitive records create exposure, and a mutable logger can share the same compromise as the acting system. Audit design needs sampling, retention, access controls, integrity checks and a defined investigator, rather than an assumption that more recorded text necessarily lowers monitoring cost.

### External continuity is a mechanism rather than a guarantee

Reflexion provides a bounded demonstration of agents using verbal feedback stored in external memory to alter later attempts without weight updates; the fuller evidence and persistence limits belong to R-14 [R13-S15](#r13-s15).

For C-031, the existential word *can* is crucial. A new test can block a previously accepted defect, or revised instructions can change a later instance's behavior, even if the base model is unchanged. Merely archiving an incident does neither. The record must be retrievable, relevant, correctly interpreted and connected to an action rule or decision. A remembered false lesson can systematically worsen later performance. A changed test may improve compliance while missing the substantive error it was meant to catch.

“Institutional learning” is consequently a defensible functional description when the organization changes a persistent practice and later outcomes improve. It should not be inferred from record growth, a numerical trust increment, or the linguistic appearance of reflection. In particular, a +1 permission record is not evidence that RLHF occurred. Actual weight learning, contextual adaptation, retrieval and administrative authority are distinct mechanisms; R-14 owns that technical taxonomy.

## 7 Organizational reliability is more than an enforcement diagram

### Systems safety and the institutional comparison

[R13-S16: Reason](#r13-s16) distinguishes approaches that blame individuals from approaches that change working conditions and layered defenses. His discussion of active failures and latent conditions explains why removing the last person who erred may leave the causal structure intact. This influential synthesis is not a randomized demonstration that any named safety culture works. Its value here is diagnostic: a repeated cognitive failure can be a symptom of how work is allocated, measured or escalated.

[R13-S17: Leveson and colleagues](#r13-s17) formulate STAMP around constraints, feedback and controller process models, illustrating it with the Walkerton water-contamination accident. Harm can arise from interactions and inadequate control even without a simple chain of broken components. Their retrospective analytical application helps interrogate missing feedback, conflicting authority and inaccurate world models; it does not estimate an AI architecture's prospective incident rate. This is especially relevant to V4: a control graph still needs reliable observations and coordinated responses when local models of the situation diverge.

[R13-S18: LaPorte and Consolini](#r13-s18) draw on field observations of air-traffic control and naval aviation. They describe organizations combining formal procedures, expertise-sensitive high-tempo coordination and rehearsed emergency responses. Reliability-oriented operations also had resource commitments and limits on trial-and-error learning where consequences were intolerable. Selection of successful, unusually resourced organizations and observational analysis limit causal identification and transfer to ordinary firms. These cases support the possibility of organized reliability; they do not make “trust first” or centralization alone a transferable recipe.

Normal-accident arguments challenge the optimistic inference that an organization can always add enough rules and redundancy to master complex, tightly coupled hazards. A useful primary encounter between the schools is [R13-S19: the Columbia Accident Investigation Board](#r13-s19). Its 2003 report explicitly draws on both high-reliability and normal-accident perspectives, while finding that neither alone fully explains the case. Chapters 7–8 identify eroded checks, communication failures and normalized anomalies alongside physical causation. This is a detailed official investigation, not a controlled comparison across organizations. The case warns that records and formal safety offices can coexist with ineffective challenge; it does not establish inevitable failure for all complex systems.

These literatures disagree about how far organization can overcome complexity, but they converge on a requirement often absent from an architecture diagram: maintaining reliability is continuing work. Who detects drift in the rules? Who can challenge a manager's interpretation? Who funds a pause? Who checks the evaluator? Who can revise the objectives rather than repeatedly patching output? Human institutions have resources, incentives, occupational knowledge and power relations that a graph of model roles does not automatically reproduce.

### Fast recovery can inhibit learning

[R13-S20: Tucker and Edmondson](#r13-s20) observed 26 nurses for 239 hours across nine hospitals and subsequently interviewed 12 nurses at seven sites. Short-term workarounds restored care but frequently prevented underlying process failures from reaching people able to redesign the system. Their qualitative, unevenly distributed observations develop a mechanism rather than estimate a universal effect of local repair. The finding matters because successful completion can hide the cost of repeatedly compensating for the same defect.

V4's local correction is therefore strongest when paired with a second, separate decision: does this event require changing a shared rule, tool or organizational arrangement? A local fix can preserve useful momentum while a later causal investigation changes the institution. The alternatives need not be immediate systemwide reset or silent local repair. Nor should every incident trigger global redesign, which can create instability and overload. Severity, recurrence, spread and common dependencies should determine the response.

This also changes interpretation of incident counts. More recorded failures may mean worsening performance or improved detection. Fewer escalations may indicate better autonomy or suppressed reporting. The denominator, discovery process and severity distribution must accompany the count. Reliability metrics themselves can create incentives to conceal failures if they are treated as performance scores without independent outcome checks.

### Trust and the principal–agent claim

[R13-S21: Holmström](#r13-s21) analyzes hidden actions and incentives under imperfect information. His theoretical model shows how informative observations can improve a contract while preserving the distinction between imperfect monitoring and a first-best outcome. It presupposes economic actors, preferences, actions and contracting conditions. Applying its vocabulary to a language model requires an argument about those mechanisms; stochastic error is not by definition shirking, and a named identity is not by itself a resolution of asset specificity.

MKS can be understood as attempting to reduce a class of delegation and monitoring costs. Its V3 claim to *solve* the principal–agent problem is unestablished and substantially stronger. The designer still must choose objectives, specify observables, maintain enforcement, pay for verification, resolve conflicts among legitimate principals and determine acceptable risk. Suppliers, employees, managers and deployers may also have genuine incentive conflicts that are not removed by placing an LLM behind a gate.

Trust is most useful here as a bounded delegation policy: authority over particular actions under particular conditions, based on relevant evidence and subject to revision. Successful low-stakes tasks do not automatically justify high-stakes authority, and a new model, tool or environment can invalidate earlier calibration. A single cumulative score can conceal failure concentration and exposure differences. The “human-controlled boundary” must also be something humans can actually understand, monitor and change. R-07 addresses that requirement; an approval box or nominal right to intervene cannot be assumed sufficient.

## 8 Verification overhead and the correct economic comparison

The relevant counterfactual is not an ungoverned model with no verification costs. It is another feasible way of completing the same work at an acceptable level of quality and risk. The alternatives might include conventional software, a smaller model with a stronger checker, a skilled human, a bounded agent workflow, or no action. R-01 supplies the broader useful-task cost framework and R-04 the allocation-of-function comparison.

A proposed governance architecture should count initial specification, integration and evaluator development; per-task model/tool/monitor expense; latency; review and escalation; false rejections; repeated repair; incident response; and maintenance when models or policies change. A critic that reduces bad outputs but adds enough delay to make a deadline impossible may lower system usefulness. An inexpensive check can also save expert attention for the few questions where it is needed. Neither sign should be assumed.

Several reviewed studies expose different parts of this accounting: resource-matched comparisons alter conclusions about self-correction; architectural injection defenses impose implementation and interaction costs; and local recovery experiments count lost work rather than recovery speed alone. Their numerical results cannot be combined into a general MKS return-on-investment estimate. There is no examined public experiment comparing the historical MKS package with simpler alternatives over an entire operational lifecycle.

Scale is particularly important. A small per-action failure probability may produce frequent incidents over many actions, while retries and reviewers can share common causes. A high average completion rate can coexist with unacceptable failure on one group of tasks. Increasing delegation changes both the volume of exposure and the consequences available to the agent. It therefore changes the required evaluation rather than merely increasing the sample size of an unchanged activity.

## 9 Claim-level evidence ledger

Judgments below concern precisely stated scopes. They do not rewrite the Loop 1 ledger or imply author adoption. “Supported” for a normative claim means its empirical design rationale is supported, not that research proves the value judgment.

| Claim | Exact admitted proposition and provenance | Research judgment | Evidence and remaining boundary |
|---|---|---|---|
| C-026 | Institutions **should** make ordinary cognitive error observable, recoverable and unlikely to propagate into unacceptable consequences. Synthesis §8; V3 §§1–3; V4 §§1,3. | **Supported within stated scope as a design objective; effectiveness qualified.** | S01–S05 and S16–S20 support distinct containment and organizational mechanisms. No reviewed source proves general observability, recoverability or an acceptable-risk bound. Tolerance remains an author/institutional choice. |
| C-028 | V3 **entertains** terminating and resetting a persistently failing kernel as safer and cheaper than repeated redrafting. V3 §5, Theory B. | **SUPERSEDED scope preserved; comparative empirical claim unresolved.** | V4 rejects systemic resets for localized failure, not every restart. S09–S11 justify neither blanket reset superiority nor blanket redraft superiority. V3's specific-kernel reset must not be misdescribed as necessarily erasing the whole system. |
| C-029 | V4 shifts toward trust within human-controlled boundaries, reversible exploration, synthesis and local correction with retained failure history. V4 §§1–3; synthesis §8. | **Supported as textual evolution; revised/qualified as an efficacy proposition.** | S02–S05, S09 and S17–S20 make boundary enforcement, recovery scope, causal learning and operating resources decisive. “Trust” and a declared ruin barrier are not independent safety mechanisms. |
| C-030 | V4's reality discriminator, skill routing and trust-based RLHF progression assert technical guarantees **not established by the specifications**. V4 §§1.4,4; V3 §6.2. | **Supported within stated scope.** | The specification omits the needed truth oracle, formal contamination guarantee and training mechanism. S03–S05 and S12–S14 distinguish bounded enforcement and useful observability from stronger guarantees. R-14 resolves the learning taxonomy. No private implementation was evaluated. |
| C-031 | External durable records, tests, process rules and correction history **can** change subsequent model behavior **without changing model weights**. Synthesis §9; V3 state/telemetry; V4 correction. | **Supported within existential and conditional scope.** | S05 and the brief S15 bridge establish external mechanisms; S20 limits the inference from recovery or record-keeping to organizational learning. Improvement, transfer, durability and robustness require separate evidence. |
| C-053 | The coherent shared thesis combines revisable production design, reproduced human capability and institutions around fallible cognition; future adaptive capital extends it **conditionally**. Synthesis §§2–14 and related admitted sources. | **Supported/qualified for the institutional component; composite judgment remains cross-program.** | This review supports studying production at system level while preserving failure, cost and authority conditions. It does not independently establish apprenticeship, value capture, future adaptive capital or the complete economic thesis. |

### Auxiliary tests of stronger specification clauses

These are research subclaims, not new or renumbered author claims.

| Auxiliary ID | Stronger assertion tested | Judgment and permissible replacement |
|---|---|---|
| R13-A1 | V3 §1 “solves” the principal–agent problem. | **Unresolved and unsupported as a universal solution.** May reduce specified delegation costs; requires explicit objective, information and incentive assumptions. S21; §§3,7–8 above. |
| R13-A2 | V4 §1.4's discriminator separates influence from objective truth. | **Unestablished.** Enforcing acceptance of evidence is not establishing its truth. State observable predicates, uncertainty and external validation separately. |
| R13-A3 | V4 §4.1's selective skill loading guarantees precision and eliminates cross-contamination. | **Unestablished as a guarantee.** The reviewed evidence does not directly test MKS modules; context selection is not privilege or information-flow isolation. S02, S04–S05. |
| R13-A4 | V3 §6.2 logs transform a credence good into a verifiable search good. | **Revised/qualified.** Logs can make defined actions inspectable; complete reasoning and substantive quality do not follow. S03, S12–S14. |
| R13-A5 | V4 §3 declares an absolute barrier against existential ruin. | **Unestablished.** No complete hazard model, detector, coverage argument or verified implementation is supplied. S01–S05, S17–S19. |
| R13-A6 | More critics, hierarchy or retained incidents necessarily improve reliability. | **Contradicted as an unconditional inference.** Measure conditional detection, correlated errors, coordination defects and actual rule changes. S06–S11, S20. This quantifier is an auxiliary stress test, not a claim newly attributed to the author. |

## 10 Testable implications and evidence gaps

### Proposed evaluation programme

The following designs are **auxiliary proposals only; none was executed for this review**. They would test institutional functions before committing to the entire historical architecture.

1. **External enforcement versus instructions.** Randomize matched sandbox tasks between prompt-only constraints and externally mediated action permissions. Keep model, tools and task distribution fixed. Measure prohibited effects, successful authorized completion, bypasses, false blocks and implementation effort. Include malformed metadata, permission changes and alternate tool paths. A result about this sandbox would not certify semantic truth.
2. **Marginal value of the critic.** Compare generator-only, same-model critique, blind cross-model critique and independent-tool checking under equal token, time and human-review budgets. Use held-out seeded and naturally occurring defects. Measure detection conditional on generator error, false rejection of correct work and escaped-harm severity. Report clustered uncertainty by task and shared source, not just by generated answer.
3. **Repair scope.** Within a safe simulation, assign transient tool failures, localized context errors, persistent corrupt records, wrong task specifications and shared-service failures. Compare local redraft, clean-context component restart and checkpoint restoration. Count invalidated downstream work, repeated errors, irreversible simulated effects and time to verified recovery. Classify failure before averaging across categories.
4. **Institutional learning beyond record growth.** Randomize whether an incident merely enters a log, updates a retrievable lesson, produces a regression test, or changes an enforced workflow. Test unseen related tasks with fresh instances and later model versions. Require a held-out improvement and regressions audit; count maintenance burden and harmful lesson transfer. This distinguishes archival continuity from beneficial institutional learning.
5. **Audit usefulness without assumed faithfulness.** Give reviewers outcome-only, independently logged actions, explanations, or combined evidence. Measure diagnosis accuracy, time, missed incidents and unwarranted confidence. Audit the logger separately. Where proofs are available, score proof validity apart from whether the natural-language problem was correctly formalized.
6. **Delegation under distribution shift.** Estimate task-specific performance and failure severity before increasing permissions. Test changes in model, tool schema, document trust and workload. Compare a scalar trust score with scope-specific permission policies. Measure whether revocation and escalation happen in time, including when the human cannot respond. R-07 supplies human-control measures.
7. **Organizational maintenance.** In a prospectively observed deployment with an appropriate comparison group, record near misses, workarounds, evaluator changes, escalation queues and verified substantive outcomes. Check whether rapid local fixes suppress reporting or reduce recurring causes. A before/after incident count alone is inadequate because detection and reporting can change.

### Detection and statistical limits

Absence of observed catastrophic failures does not demonstrate a zero rate. As an elementary auxiliary calculation, under independent identically distributed Bernoulli trials with perfect detection, zero failures in n trials gives a one-sided 95% upper bound of `1 - 0.05^(1/n)`, approximately `3/n`. Those assumptions are substantial: shared task difficulty, adaptive attacks, environmental drift and incomplete detection can invalidate the simple interpretation. This calculation is not a safety certification and is not derived from an MKS test.

The most important gaps are prospective, multi-month comparisons of governed systems against simpler baselines; independently labeled semantic failures; realistic recovery when external state has already changed; correlated generator/critic error on actual work; and the full human cost of designing and maintaining checks. The public evidence does not establish a general detector for existential risk, a universal truth filter, or a universal conversion of explanations into verifiable reasoning.

Author-only decisions remain separate: what outcomes are unacceptable even when expected benefits are high; which decisions require legitimate human authority irrespective of model capability; and whether MKS should remain a historical worked example or become a proposed technical programme with explicit validation burdens. Research can clarify those choices without choosing them.

## 11 Bibliography and source access appendix

All sources below were accessed on **4 October 2026**. “Inspected” means substantive text at the specified locations, not an abstract-only search. This is a targeted analytical review, not a preregistered systematic review or exhaustive census. Search discovery used public scholarly, author, university, conference and government sources; inaccessible publisher pages were not bypassed. No paid APIs, accounts, third-party contacts or experiments were used. Technical studies were read in their primary versions. Official investigations and theoretical/field research are identified separately from controlled experiments.

### R13-S01

Rabanser, Stephan, Sayash Kapoor, Peter Kirgis, Kangheng Liu, Saiteja Utpala and Arvind Narayanan. 2026. *Towards a Science of AI Agent Reliability*. [arXiv 2602.16666v3, 2 June](https://arxiv.org/html/2602.16666v3). Inspected §§3–6, Appendix B and experimental protocols F. Version-specific benchmark study; no rerun or underlying-trace audit. Earlier model counts or uncorrected airline denominators should not be substituted.

### R13-S02

Saltzer, Jerome H., and Michael D. Schroeder. 1975. *The Protection of Information in Computer Systems*. Proceedings of the IEEE 63(9):1278–1308. [Author-hosted text, Part I](https://web.mit.edu/Saltzer/www/publications/protection/Basic.html). Inspected protection dynamics and design principles; classical engineering synthesis, not contemporary deployment measurement.

### R13-S03

Klein, Gerwin, et al. 2009. *seL4: Formal Verification of an OS Kernel*. SOSP '09, 207–220. [Project-hosted paper](https://sel4.systems/Research/pdfs/sel4-formal-verification-os-kernel.pdf). Inspected §§2,4.3–4.5 and conclusions, particularly pp.7–8 assumptions and refinement theorems. Proof result and engineering case study; historical scope only, not a claim about every current configuration.

### R13-S04

Debenedetti, Edoardo, Jie Zhang, Mislav Balunović, Luca Beurer-Kellner, Marc Fischer and Florian Tramèr. 2024. *AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents*. NeurIPS Datasets and Benchmarks. [arXiv 2406.13352v3, 24 November](https://arxiv.org/html/2406.13352v3). Inspected §§3–4 and Appendix C/D. The early v1 was encountered but replaced with v3. Curated stateful benchmark; no independent replication. Internal headline/table differences counsel against a single general attack percentage.

### R13-S05

Debenedetti, Edoardo, et al. 2025. *Defeating Prompt Injections by Design*. [arXiv 2503.18813v2, 24 June](https://arxiv.org/html/2503.18813v2). Inspected threat model, architecture, §§6–9, Table 2 and Appendix F. Google/DeepMind/ETH author-led system evaluation. V1's 67% headline is superseded here. The overhead prose/Figure 13 and Appendix F tables differ in reported medians; this review reports no reconciled multiplier. Security claims are conditional, not unrestricted deployment guarantees.

### R13-S06

Kim, Elliot, Avi Garg, Kenny Peng and Nikhil Garg. 2025. *Correlated Errors in Large Language Models*. ICML 2025. [arXiv 2506.07962v1, 9 June](https://arxiv.org/html/2506.07962v1). Inspected §§3–6 and dataset details. Observational response analysis and downstream simulation. Résumé results are not treated as real hiring outcomes. Shared inputs and unobserved training differences constrain causal explanations.

### R13-S07

Knight, John C. 1986. *Detection of Faults and Software Reliability Analysis*. Annual progress report, University of Virginia, UVA/528243/CS87/101, August, NASA grant NAG-1-605. [NASA primary report](https://ntrs.nasa.gov/api/citations/19870002808/downloads/19870002808.pdf). Inspected printed pp.1–8, sections I–V. Primary follow-up to Knight and Leveson's 1986 IEEE experiment. The journal paper itself was not recovered in substantive form; student-summary PDFs were excluded. The report supports both correlated failures and remaining redundancy benefits.

### R13-S08

Cemri, Mert, et al. 2025. *Why Do Multi-Agent LLM Systems Fail?* [arXiv 2503.13657v3, 26 October](https://arxiv.org/html/2503.13657v3). Inspected §§3–5, Table 1 and annotation/intervention descriptions. Version distinguishes initial taxonomy development, human agreement exercises and expanded machine annotation. No claim that all 1,642 traces were independently human-labeled or that framework selection represents all agent deployments.

### R13-S09

Candea, George, Shinichi Kawamoto, Yuichi Fujiki, Greg Friedman and Armando Fox. 2004. *Microreboot—A Technique for Cheap Recovery*. OSDI '04, 31–44. [USENIX full text](https://usenix.org/legacy/events/osdi04/tech/full_papers/candea/candea_html/index.html). Inspected architecture, evaluation framework, failure-injection results and limitations, §§2–6. Prototype experiment with emulated users; not production randomized evidence or an LLM study.

### R13-S10

Huang, Jie, Xinyun Chen, Swaroop Mishra, Huaixiu Steven Zheng, Adams Wei Yu, Xinying Song and Denny Zhou. 2024. *Large Language Models Cannot Self-Correct Reasoning Yet*. ICLR 2024. [arXiv 2310.01798v2, 14 March](https://arxiv.org/pdf/2310.01798v2). Inspected §§2–5, setup and Tables 2–3. Prompt-based benchmark experiments; title must retain its time and intrinsic-correction qualification. Sample and correction-budget limits described in §5 above.

### R13-S11

Silver, Sam, Jimin Sun, Ivan Zhang, Sara Hooker and Eddie Kim. 2025. *Language Models can perform Single-Utterance Self-Correction of Perturbed Reasoning*. [arXiv 2506.15894v1, 18 June](https://arxiv.org/html/2506.15894v1). Inspected §§3–4 and Table 1. UC Santa Cruz/Cohere-associated authors; synthetic perturbation study, with acknowledged grading, prefill and provider limitations. Not a natural-error field experiment.

### R13-S12

Turpin, Miles, Julian Michael, Ethan Perez and Samuel R. Bowman. 2023. *Language Models Don't Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting*. NeurIPS 2023. [arXiv 2305.04388v2, 9 December](https://arxiv.org/pdf/2305.04388v2). Inspected experimental framing, BBH/BBQ manipulations and limitations. Controlled cue interventions; tests can expose unfaithfulness but cannot certify every unflagged explanation.

### R13-S13

Chen, Yanda, et al. 2025. *Reasoning Models Don't Always Say What They Think*. [arXiv 2505.05410v1, 8 May](https://arxiv.org/html/2505.05410v1). Inspected §§2–5 and §7. Anthropic research; paired-prompt experiments and synthetic RL environments. Accessible reasoning models and selected hint behaviors define scope; no inference about models whose hidden traces were unavailable.

### R13-S14

Baker, Bowen, et al. 2025. *Monitoring Reasoning Models for Misbehavior and the Risks of Promoting Obfuscation*. [arXiv 2503.11926v1, 14 March](https://arxiv.org/html/2503.11926v1). Inspected §§2–3, §5 and monitor definitions. OpenAI provider study. Two detectable systemic hacks supply a narrow ground truth; broader misbehavior lacks equally complete labels. Useful detection does not imply complete introspective access.

### R13-S15

Shinn, Noah, et al. 2023. *Reflexion: Language Agents with Verbal Reinforcement Learning*. [arXiv 2303.11366v4, 10 October](https://arxiv.org/html/2303.11366v4). Inspected §3, evaluator definitions, ALFWorld protocol and limitations. **Cross-program bridge only:** the fuller capsule and persistent-capability interpretation belong to R-14; no benchmark percentage is duplicated here.

### R13-S16

Reason, James. 2000. *Human Error: Models and Management*. BMJ 320:768–770. [Open full text](https://pmc.ncbi.nlm.nih.gov/articles/PMC1117770/), [DOI](https://doi.org/10.1136/bmj.320.7237.768). Inspected person/system approaches, active/latent failures, defenses and high-reliability discussion. Conceptual synthesis rather than new causal estimation; not medical advice.

### R13-S17

Leveson, Nancy, Mirna Daouk, Nicolas Dulac and Karen Marais. 2003. *Applying STAMP in Accident Analysis*. Second Workshop on the Investigation and Reporting of Incidents and Accidents, pp.177–198. [NASA-hosted paper](https://shemesh.larc.nasa.gov/iria03/p13-leveson.pdf). Inspected model, control/process-model discussion and Walkerton application framing. NASA/NSF-supported conceptual and retrospective case analysis; no prospective MKS validation.

### R13-S18

LaPorte, Todd R., and Paula M. Consolini. 1991. *Working in Practice But Not in Theory: Theoretical Challenges of “High-Reliability Organizations.”* Journal of Public Administration Research and Theory 1(1):19–48. [Author-university PDF](https://polisci.berkeley.edu/sites/default/files/people/u3825/LaPorte-WorkinginPracticebutNotinTheory.pdf). Inspected pp.19–35, especially field scope, resources, bounded learning and modes of authority. ONR/NSF and university support disclosed. Observational theory-building; not a controlled test of an organizational recipe.

### R13-S19

Columbia Accident Investigation Board. 2003. *Report*, Volume I, August. [NASA-hosted official report](https://www.nasa.gov/wp-content/uploads/static/history/columbia/reports/CAIBreportv1.pdf). Inspected chapter 7 theory/control findings, chapter 8 comparisons and Appendix A investigation-method description; not all 248 pages. Primary official inquiry integrating documentary, technical and organizational evidence. This review's comparison of normal-accident and HRO perspectives uses the Board's engagement with them, not a claim to have read Perrow's entire book.

### R13-S20

Tucker, Anita L., and Amy C. Edmondson. 2003. *Why Hospitals Don't Learn from Failures: Organizational and Psychological Dynamics that Inhibit System Change*. California Management Review 45(2):55–72. [University-hosted published reprint](https://www.utsouthwestern.edu/employees/leadership-programs/leadership-foundations/why-hospitals-dont-learn.pdf). Inspected research base, Table 1, first-/second-order problem solving and managerial implications. HBS-supported qualitative field research; original publication used rather than an encountered 2002 author draft.

### R13-S21

Holmström, Bengt. 1979. *Moral Hazard and Observability*. Bell Journal of Economics 10(1):74–91. [University-hosted scan](https://personal.utdallas.edu/~nina.baranchuk/Fin7310/papers/Holmstrom1979.pdf). Inspected printed pp.74–75 visually; the PDF text layer contained only cover metadata. Use is limited to the introduction's model scope and monitoring distinction, not a claim to have checked every proof or independently derived its informativeness theorem.

### Access exclusions and evidential discipline

The exact journal version of the original Knight–Leveson independence experiment and full publisher access to some organizational articles were unavailable through the routes tried. Primary accessible alternatives are identified rather than concealed. ResearchGate summaries, student notes, search snippets and later blog summaries were discovery leads only. Broken arXiv version URLs were corrected by checking submission histories. For CaMeL, AgentDojo and MAST, the revised inspected versions govern; an earlier abstract's denominator or headline was not carried forward.

No new API calls or benchmark runs tested the studies' results. No literature result validates private MKS machinery by resemblance. Selected quantitative claims are paired with their actual denominators and comparators. Source-specific discussion is deliberately compact; the integrated argument and proposed tests are this review's analytical synthesis, not claims of new empirical findings.

## 12 Conclusion

The public evidence supports investigating the institution around a model as a consequential unit of design. It also requires treating that institution as fallible. Deterministic gates can constrain observable behavior; critics can contribute useful checks; records can support recovery and later improvement. Their effectiveness depends on evidence quality, complete mediation, task-specific evaluation, resources and maintained authority.

The historical specifications overreach when those bounded functions become claims to settle truth, eliminate contamination, reveal reasoning or solve agency. The current synthesis can retain its institutional direction without retaining those guarantees. What remains to be established is the comparative performance of specific arrangements, over realistic tasks and time, including the failures introduced by governance itself.
