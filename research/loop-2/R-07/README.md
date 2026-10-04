# R-07 — Meaningful human authority

**Research review date:** 4 October 2026  
**Admitted claim:** C-014  
**Status:** Substantive literature review accepted after independent quality review; no author position or canonical manuscript is changed.  
**Scope:** Whether formal human approval supplies an effective opportunity to understand, challenge and change a decision, and how that opportunity relates to responsibility and legitimate authority.

## Result in brief

C-014 survives as a conditional possibility claim. A person can be formally responsible for reviewing automated work while the allocation of attention, information, time, skills and organizational powers makes adequate review unrealistic. Human presence and a recorded approval do not establish that the person could identify the relevant problem or obtain a different outcome. The evidence is strongest for particular cognitive and organizational failure mechanisms, rather than for an estimated prevalence of powerless approvers across contemporary workplaces.

The converse matters equally. Human–AI combinations sometimes improve decisions, including in experiments designed to make complementary performance possible. Targeted attention cues, opportunities for an independent first judgment and appropriately directed accountability can help. These interventions do not work uniformly; some improve behavior on erroneous recommendations without improving aggregate performance. Expert disagreement with an algorithm can correct error, introduce error, or reflect a legitimate disagreement about the objective. Neither a high acceptance rate nor a high override rate is an adequate measure of meaningful authority.

Three conclusions should remain separate:

1. **Capability:** Can this person or team recognize and repair the relevant failures under actual working conditions?
2. **Authority:** Can they change the case, slow or suspend the workflow, obtain assistance, and challenge its governing assumptions?
3. **Legitimacy and accountability:** Who is entitled to decide, whose interests must count, and which people or organizations should answer for the outcome?

An experiment can establish an improvement in a scored task without establishing the third conclusion. A statute can require oversight without demonstrating the first. A veto button supplies one possible instrument of the second, but is neither a sufficient test nor a universal design prescription.

## 1. Preserve the proposition and its boundaries

The historical [claim ledger](../../../evidence/claims/CLAIM-LEDGER.md#c-014) states C-014 exactly:

> A nominal approver overwhelmed by output can bear responsibility without meaningful agency.

Its source is [S-04, “The human place is not whatever AI leaves behind”](../../../source/drafts/04-the-production-function-is-becoming-writable-v3.md#the-human-place-is-not-whatever-ai-leaves-behind). The surrounding passage explicitly rejects preserving a human checkpoint everywhere. C-014 therefore does **not** assert that all automated production overwhelms its reviewers, that every approval is ceremonial, or that every human must understand an entire model internally before using it.

“Bear responsibility” requires disaggregation. Being assigned a prospective duty, being blamed after a failure, being morally culpable, and being legally liable are different states. Evidence that organizations or public narratives focus blame on an operator does not establish that the blame is deserved or that a court would impose liability. Conversely, an operator's inability to fix a problem at the last moment does not eliminate possible earlier duties or the responsibility of others who created the conditions.

This review treats **meaningful agency** as a question about a person's effective, informed influence over a relevant class of decisions. It can be partial and distributed. A reviewer need not author every intermediate step. They may exercise substantial agency by defining objectives, authorizing a bounded operating policy, controlling exceptions, commissioning an audit or stopping deployment. Those forms require assessment at their own time scale. Batch-level governance cannot be described as individual case review, and a final click cannot silently stand in for upstream governance.

[D-001](../../../decisions/resolved/D-001-middle-seat-apprenticeship.md) remains the author's revisable commitment to foundational understanding, informed tool use and supervised consequential judgment. R-07 examines whether a station permits that judgment; it does not prove the developmental sequence. [D-002](../../../decisions/resolved/D-002-ownership-dominance.md) distinguishes consequential operation from architecture, education and ownership. An operator's title or assigned liability supplies no evidence of productive contribution, bargaining leverage or compensation.

## 2. Why review can become a different and harder job

### 2.1 Residual work is not automatically an appropriate human task

Bainbridge's “Ironies of Automation” concerns industrial process control and flight-deck examples. Its central design criticism is that automating the easier or more regular work can leave operators with an ill-supported collection of monitoring and exceptional-recovery duties. Routine operation, skill maintenance and readiness for an abnormal event need not survive that reallocation. This is a conceptual human-factors synthesis, not a randomized estimate of modern AI's effects. The useful analogy is the mismatch between the residual assignment and the conditions needed to perform it. Its process-control setting does not establish that text review has the same time dynamics, or that every skill must be maintained through continued manual production. [R07-S01](#r07-s01)

For the book, the relevant question is not simply whether “review” is less demanding than “creation.” Checking a spelling correction, evaluating a proposed investment assumption and detecting an omitted counterargument impose very different requirements. Some outputs contain locally checkable defects; others require rebuilding the underlying analysis. A convincing explanation can reduce search cost or add another object that must itself be verified. Output length alone is therefore a poor workload denominator.

### 2.2 The systematic evidence supports risks and qualifications

Goddard, Roudsari and Wyatt's systematic review included 74 studies from 13,821 deduplicated records, searched through early 2010. Its four-study healthcare meta-analysis estimated a risk ratio of 1.26 for incorrect decisions under erroneous advice versus a no-support comparison (95% CI 1.11–1.44). That is conditional on erroneous advice, not a 26% increase in overall clinical error from using decision support. The review also found overall benefits in many studies and cases without automation bias. Measures and interventions were heterogeneous; much bias reporting was incidental. This combination supports a real failure channel while rejecting the inference that identifying automation-induced errors settles the system's net value. [R07-S02](#r07-s02)

Lyell and Coiera's later review included 40 studies covering 17 task types, using a search through July 2015. Its inclusion criteria required that users could verify the automation, perform the task manually and intervene: failures therefore occurred even with those nominal capacities. Studies were generally small (median sample 30; range 5–181). The authors challenged the claim that automation bias requires multitasking, finding it in complex single-task diagnosis as well. Their verification-complexity ratings and cross-study comparison support an attentional explanation but do not independently randomize complexity. Several studies lacked a clear significance test against a manual baseline. [R07-S03](#r07-s03)

These reviews should not be counted as independent replications of every underlying finding; their evidence overlaps. Nor do they justify a fixed numerical rule for how many AI outputs an employee can review. Their shared contribution is to make **verification demand**, rather than the presence of a human, an object of investigation.

### 2.3 Vigilance and overload can coexist

The reviewer can face too little informative activity during normal operation and too much work when exceptions cluster. A stream that is usually correct can encourage sensible economizing on attention; the resulting monitoring policy may nevertheless be inadequate for a rare, consequential failure. Alternatively, one difficult verification can consume the available attention without any large stream of outputs. These are distinct routes to inadequate review, consistent with the task distinctions above.

It would be a mistake to describe all reliance as laziness or all acceptance of wrong advice as irrational. The participant may lack better information, or the recommendation may be the best available choice before its truth is known. An evaluation must ask whether the person had a feasible better action, what information they could actually see, and what the relevant error costs were. Hindsight labels such as “wrong advice accepted” are useful outcome measures, but are not sufficient explanations of behavior or moral fault.

A simple **researcher-derived capacity accounting test**, not an empirical law, is useful here. Estimate required reviewer minutes per hour, including ordinary checks, escalations, correction, coordination and breaks; compare them with staffed minutes genuinely available. If required review persistently exceeds that capacity, some combination of delay, unreviewed work, thinner review or additional capacity must result. Whether the required review is itself well designed remains open. Better triage, smaller consequential decision surfaces and reliable automated checks can change the requirement; increasing output does not mechanically imply increasing human effort in the same proportion.

## 3. Explanation, understanding and reliance are different outcomes

Mehrotra and colleagues' 2024 systematic review maps 65 papers published from 2012 through June 2022. It separates beliefs, intentions and actions and documents heterogeneous definitions and measures of “appropriate trust.” Interventions such as transparency, uncertainty presentation and cognitive prompting yield mixed results; better trust measures need not imply better joint performance. Its proposed conceptual mapping is not itself empirically validated, and its search predates the public generative-AI wave despite the 2024 publication date. It is useful for keeping constructs separate, not for estimating the effect of current chatbots. [R07-S12](#r07-s12)

This distinction matters for nominal approval. A person may report high confidence because an interface appears intelligible, yet fail to identify when its advice is inappropriate. They may distrust AI in a questionnaire while following its recommendation. They may accurately predict what a model will say without knowing whether the model's conclusion is sound.

### 3.1 Showing more of the model can help one ability and harm another

Poursabzi-Sangdeh and colleagues conducted four preregistered experiments involving 3,800 US Mechanical Turk participants estimating apartment prices. The work manipulated model transparency and feature count, keeping predictions matched in the first three experiments. Simple transparent models were easier to simulate, but transparency could impair correction of conspicuous outlier mistakes. An outlier-focused prompt removed that disadvantage in the fourth experiment. Information overload is a plausible explanation, not a directly measured cognitive mediator. The authors explicitly limit generalization from short, one-shot tasks, laypeople and linear models; they did not establish that participants understood *why* an outlier prediction failed. [R07-S06](#r07-s06)

The comparison falsifies a strong design shortcut: giving a reviewer more accessible internal detail does not necessarily make their final decision better. It also supplies a successful intervention rather than an argument for withholding all information. The appropriate target may be identifying the assumption or exceptional feature that matters for the decision, with deeper inspection available when useful.

### 3.2 Cognitive forcing is promising, but its endpoint matters

Buçinca, Malaya and Gajos analyzed 199 participants from 260 recruited US crowdworkers in a mixed randomized design. Participants chose ingredient substitutions; a simulated AI misidentified the principal carbohydrate source on 25% of trials. Forcing designs included deciding first, requesting advice and waiting before seeing it. Compared with ordinary explanation conditions, forcing reduced erroneous source-selection reliance from .64 to .48 and improved accuracy on AI-error trials. But aggregate performance did not significantly improve; the reduction in overreliance on the complete two-part decision was also nonsignificant. Benefits varied with need for cognition. These short, low-stakes tasks establish neither workplace uptake nor retained professional learning. The study supports testing friction selectively, rather than declaring that slowing every approval is beneficial. [R07-S05](#r07-s05)

This is especially relevant to D-001. Requiring an initial judgment can reveal what a junior actually believes and create a teachable comparison. That potential is separate from proof of later independent skill. It can also be a wasteful duplicate for a routine, reliably checked operation. The learning and production objectives must be measured separately.

### 3.3 Complementarity is possible without an explanation effect

Bansal and colleagues recruited 1,626 crowdworkers across beer-review sentiment, book-review sentiment and LSAT-style tasks; screening and filtering produced roughly 100 participants per condition, rather than 1,626 retained observations in every analysis. Models and task sets were chosen to make human and AI accuracy comparable. Recommendation-plus-confidence teams exceeded both solo baselines across tasks. Additional explanations did not significantly improve on that confidence baseline and increased acceptance of both correct and incorrect advice. The screening, immediate feedback and selected complementary tasks are important boundary conditions; this is not evidence that any professional team will outperform either member. [R07-S07](#r07-s07)

Together these experiments make a more precise design debate possible. “Explainability works” and “explainability fails” are both too coarse. An intervention can improve comprehension, error detection, speed, satisfaction, average accuracy or appealability, with different effects on each. A legal right to an explanation may also have reasons independent of a measured accuracy gain. The right evidentiary question is which explanation, for whom, in which decision process, serving which objective.

## 4. Counterevidence: humans are not uniformly obedient, and disagreement is not uniformly corrective

Gaube and colleagues studied 138 radiologists and 127 internal/emergency-medicine physicians recruited in the US and Canada. Each reviewed eight chest-X-ray cases with accurate or inaccurate advice, described as coming from either AI or an experienced radiologist; all advice was actually expert-authored. Inaccurate advice reduced diagnostic accuracy regardless of the stated source. Radiologists rated AI-labelled advice less favorably without a corresponding difference in final diagnostic accuracy. Some participants rejected every inaccurate recommendation. The small case set, younger-skewed physician sample and online simulation limit clinical generalization. Crucially, the study identifies susceptibility to advice, not a uniquely machine-induced deference effect. [R07-S08](#r07-s08)

Alon-Barkat and Busuioc's Dutch hiring-vignette studies used analytical samples of 605 and 904 citizens and 1,345 civil servants. They found no greater overall adherence to algorithmic than equivalent human-expert advice. In study 2, the ethnicity manipulation, analyzed among 792 Dutch-descent participants, showed stereotype-consistent adherence; its unadjusted main effect passed a one-sided test but not the conventional two-sided .05 threshold (p=.083). Study 3, after the childcare-benefits scandal, showed a different pattern, including less reliance on algorithmic advice. The scandal explanation is observational: timing and participant population changed together. No significant advice-source interaction established AI-specific selective adherence. A vignette without real employment consequences is not a field hiring outcome. [R07-S09](#r07-s09)

These results qualify two different overstatements. First, one cannot presume a general preference for machine advice from the existence of automation bias in other tasks. Second, restoring discretion does not establish fair or appropriate use of it. A person can selectively reject accurate advice, accept advice that confirms a stereotype, or override a system for an irrelevant reason. But the same capacity for disagreement can be essential when the model lacks information, misstates the decision's purpose, or cannot legitimately determine the trade-off.

There is also a measurement trap. Comparing AI-labelled with human-labelled advice estimates a **source-label effect**. Comparing assistance with unaided work estimates something different. Finding no label effect does not show that advice has no anchoring effect; finding that erroneous advice worsens decisions does not show that the AI label caused the worsening. Neither design, by itself, identifies the effect of an employer's workload policy or of sustained exposure to a reliable production system.

## 5. Successful interventions and modern clinical comparisons

### 5.1 Accountability can direct attention productively

Skitka, Mosier and Burdick's experiment assigned 181 undergraduates to simulated flight-monitoring work with an imperfect automated aid, reliable verification information and different accountability instructions. Accountability for overall performance or accuracy reduced omission and commission errors relative to no accountability; accountability aimed at tracking instead increased commission errors and improved tracking. The manipulation required later justification of strategies, not exposure to actual legal liability. It demonstrates that the *object* of accountability affects behavior. It does not establish that threatening sanctions improves professional judgment, or that assigning responsibility can compensate for unavailable information or impossible workloads. [R07-S04](#r07-s04)

The institutional inference is conditional but important. “Accountability” is not one treatment. A dashboard that rewards rapid clearance, a supervisor who asks for reasons, a compensation system tied to accuracy, and a disciplinary policy after failure can create different incentives. A review regime must identify what its operator is actually asked to optimize. Requiring an explanation for every departure from AI while requiring none for acceptance could make compliance cheaper than challenge; that is a mechanism to test, not a universal finding established by this experiment.

### 5.2 Access to a strong model is not a stable recipe for stronger human performance

Goh and colleagues' 2024 randomized trial assigned 50 US physicians, half per arm, to conventional diagnostic resources with or without GPT-4 access. On up to six curated vignettes within one hour, the adjusted difference in diagnostic-reasoning score was 2 percentage points (95% CI −4 to 8), not a significant improvement. The separately prompted model performed better, but that comparison did not test autonomous patient care: clinicians had already curated the case information. The study evaluates access with limited instruction and scored written reasoning, not a standardized final-approval interface or a causal account of why individual physicians relied as they did. [R07-S10](#r07-s10)

A related 2025 trial supplies positive counterevidence. Ninety-two physicians were randomized to conventional resources with or without GPT-4 for five management-reasoning vignettes with sequential information. Assistance improved rubric scores by an adjusted 6.5 percentage points (95% CI 2.7–10.2) while adding about 119 seconds per case (95% CI 17–221). The assisted group was not significantly different from the model-only comparator. The rubric rewarded appropriate content without penalizing incorrect answers; an exploratory harm assessment did not establish a clinical safety gain. Outcomes therefore support a bounded performance improvement, not fewer real patient harms or proven human–AI superiority over AI alone. [R07-S11](#r07-s11)

These results should be compared, not averaged into a generic “doctor plus AI” effect. The tasks, rubrics, case presentation and samples differ. Their juxtaposition makes it untenable to infer usefulness or uselessness merely from professional expertise plus tool availability. It also shows why time is not always a cost to eliminate: extra deliberation may accompany a quality gain, while in another task duplication may add little. The choice requires the institution's actual outcome and risk criteria.

The broader human–AI synergy synthesis is assigned to R-17 in the [program register](../README.md); the P&G and BCG experiments belong to [R-10](../R-10/README.md). They should enter cross-program synthesis through their source-owning reviews, rather than being recounted here as additional independent evidence.

## 6. Authority is a property of the institution as well as the interface

### 6.1 Meaningful control does not require a finger on every action

Santoni de Sio and van den Hoven offer a philosophical account with two necessary conditions: the system should respond to relevant human moral reasons, and its behavior should be traceable to appropriately understanding human agents in its design or use. Control can consequently reside upstream and across roles. They expressly distinguish meaningful control from the moral acceptability of a system's goals. Their account supplies normative design criteria, not experimentally validated thresholds or a legal rule that assigns liability. [R07-S13](#r07-s13)

That framework helps distinguish an operator's permission to press “reject” from the institution's capacity to act on the reasons for rejection. If the person cannot obtain the underlying facts, modify the objective, access a qualified escalation path or prevent execution, a formal veto may offer little useful influence. Conversely, an institution can exercise substantial prospective control over a bounded, automatically executed process without requiring a human to approve every instance. Whether that delegation is legitimate is an additional question.

### 6.2 Blame can settle downstream of control

Elish's “moral crumple zone” analysis examines selected accidents and their public interpretation, including Three Mile Island and Air France 447, before considering autonomous vehicles. It identifies how blame can concentrate on a visible operator while design and organizational choices disappear from view. This is interpretive case analysis, not a representative study of liability judgments or proof that those operators had no responsibility. Its contribution is an explicit hypothesis about misalignment between control and attributed responsibility. [R07-S14](#r07-s14)

A bounded primary case sharpens the distinction. The NTSB's investigation of the fatal 2018 Tempe developmental automated-driving crash identified the distracted vehicle operator's failure to monitor as the probable cause. It separately identified Uber ATG's deficient risk assessment, oversight and treatment of automation complacency, and insufficient state oversight, as contributing factors. It also found that removing the second operator increased task demands and reduced redundancy. This was a particular accident investigation, not a randomized staffing study or legal verdict. It supports multi-level causal analysis without either exonerating the operator or treating the operator as the entire explanation. [R07-S16](#r07-s16)

For C-014, the safe inference is not that organizations always deliberately manufacture scapegoats. Formal duties can become disconnected from practical control through ordinary procurement, staffing and incentive decisions as well as through strategic blame-shifting. The empirical task is to reconstruct those decisions and their consequences. An approval log identifies an event and actor; it does not, by itself, demonstrate understanding, feasible alternatives or the distribution of control.

### 6.3 Institutional oversight changes the object of scrutiny

Green analyzed 41 government-algorithm policies using document collection and inductive coding. He criticized reliance on human oversight requirements unsupported by evidence that people can perform the stipulated functions, and proposed institutional review of whether systems should be adopted and whether their safeguards work. This is a policy analysis and normative proposal, not an estimate that every covered system fails. Its 2022 policy corpus must not be treated as a description of all 2026 law. [R07-S15](#r07-s15)

The strongest synthesis joins rather than collapses the levels. Interface design may improve an individual's decisions, yet leave a bad objective, discriminatory eligibility rule or inaccessible appeal process untouched. Institutional authorization may settle who has responsibility for deployment, yet fail to give operators workable evidence and escalation procedures. Good governance needs to examine both. An institutional committee is itself human and fallible; moving approval upstairs is not proof that review has become substantive.

## 7. Legal illustration, versioned to the review date

The EU AI Act's Article 14 concerns **high-risk systems**, not all AI use. It connects proportionate oversight with understanding relevant capabilities and limitations, awareness of automation bias, interpretation, decisions to disregard or override outputs, and intervention or safe stopping. Article 26(2) assigns deployers responsibility for choosing overseers with competence, training, authority and support. Those are legal design obligations, not empirical demonstrations that a particular intervention works. [R07-S17](#r07-s17)

The application timeline is easy to misstate. The inspected EUR-Lex consolidation is dated **27 July 2026** and records amendment by Regulation (EU) 2026/1744. Amended Article 113(c) sets application of Chapter III Sections 1–3, except Article 6(5), at **2 December 2027** for Article 6(2)/Annex III systems and **2 August 2028** for Article 6(1)/Annex I systems. The Commission's entry-into-force notice corroborates the changed dates. As of this review, these provisions are enacted with deferred application, not merely a pending proposal or universally applicable August 2026 duties. [R07-S17](#r07-s17)

This is an EU-scoped illustration of separating provider design from deployer organization. It is not individualized compliance advice, a complete statement of all transitional or sectoral rules, or a civil-liability determination. The consolidation is a documentation instrument; the underlying Official Journal acts remain authoritative. Normative agreement with an oversight requirement must not become empirical confidence that a signed review meets it.

## 8. Researcher-derived tests of meaningful authority

The following operationalization is **stronger than, and not a replacement for, C-014**. It is a proposed evaluation design assembled from the preceding distinctions. No cited paper validates the whole battery, supplies universal pass marks, or establishes that passing it settles legitimacy.

### 8.1 Measure the contribution at the right decision boundary

Compare at least unaided qualified humans, the automated system alone where a safe offline comparison is possible, the existing human–AI workflow, and the proposed review design. Preserve equal case information or explicitly measure the value of information held only by humans. Randomize cases or workflow assignment where feasible; account for repeated decisions by the same people and repeated use of the same cases. Evaluate real representatives of the intended workforce, including novices and experts, rather than substituting an undifferentiated crowd sample.

Report at least:

- Correct initial judgments maintained, correct initial judgments changed to wrong ones, wrong initial judgments corrected, and wrong judgments retained
- Acceptance when the recommendation is sound and rejection when it is unsound, with separate denominators; distinguish a correct rejection from a different wrong answer
- Missed problems when the system emits no alert, and false alarms that create extra work
- Consequence-weighted errors and subgroup outcomes, alongside aggregate accuracy
- Time, queue delay, escalation workload and downstream correction cost

High agreement can be appropriate for an excellent system. Frequent disagreement can indicate useful independent information or unreliable interference. The desired result is not an arbitrary override quota.

### 8.2 Test understanding through decisions, not confidence alone

Give reviewers cases containing relevant missing information, plausible but false explanations, conflicting sources, unusual combinations and changes in a governing assumption. Ask them to identify what would change their decision and where they would seek verification. Compare behavior with their expressed confidence. Where an initial independent assessment is useful, record it before advice to avoid reconstructing it after exposure.

The required understanding is **task-relative**. A reviewer may need to know what evidence is absent and when a capability should not be used without being able to reconstruct its weights. Conversely, fluency in the tool's vocabulary does not establish competence to judge the substantive domain. Explainability and learning interventions should be evaluated separately from a requirement to generate longer rationales.

### 8.3 Test intervention as an end-to-end event

Inject known, safe-to-test failures and record whether an authorized reviewer detects them, recognizes the need to act, finds the control, obtains any necessary permission and actually changes the downstream state before the relevant deadline. Include the time needed to regain context, not just the click latency. Verify that stopping leaves a safe or recoverable state and that escalation has staffed recipients.

A functioning button can still be practically unusable if its consequences are unclear, it stops too much unrelated work, or its use exposes the reviewer to an unexamined penalty. Those hypotheses require observation, interviews and policy inspection as well as interface tests. Absence of past interventions cannot distinguish a safe system from an ineffective intervention channel.

### 8.4 Test load and persistence

Measure arrival rates and review-time distributions, including bursts and difficult cases. Observe full working periods and repeated use, not only a fresh participant's first dozen decisions. Assess recovery following interruptions and unusual failures. For tasks where retaining independent skill matters, use delayed unaided tests and transfer cases with different surface features; this is a dependency on R-08, not a benefit inferred from current approval accuracy.

Do not infer that a slow review is thoughtful or a fast review is careless. An expert may recognize an obvious problem quickly; a novice may spend a long time following an unhelpful explanation. Time measures need performance and process evidence beside them.

### 8.5 Evaluate selective review rather than assuming universal review

Selective review may conserve scarce attention for consequential or uncertain cases. But selection itself is a decision system. Test whether its scores identify cases where the human can add value, not merely cases difficult for both. Measure high-confidence machine failures, correlated errors between selector and generator, subgroup coverage and the consequences of errors outside the review queue.

A bounded proposal is to combine risk-based referral with independently sampled audits of cases that would otherwise bypass review. The audit can estimate what the referral rule misses; it does not make rare catastrophic failures safe by arithmetic. Some domains may instead require prevention, restricted execution or a different deployment decision. Where resources are fixed, compare this design with full review on the *same total resource budget*, including false alarms and administrative overhead. These are design tests, not demonstrated optimal staffing policies.

### 8.6 Trace responsibility to powers and resources

For each material failure class, identify who chooses objectives, approves deployment, supplies data, sets staffing and throughput, maintains the system, handles exceptions, can suspend it, and provides remedy to affected people. Record who can change each constraint. Compare the formal responsibility map with observed practice and incentives.

A reviewer can responsibly disagree with an output but be unable to alter the policy that requires it. A manager may authorize a risk while never seeing an individual case. Both facts matter. Prospective delegation, retrospective investigation and legal liability should be documented separately rather than compressed into “the human is accountable.” Whether the resulting allocation is just remains a normative question, even if its causal operation is well measured.

## 9. Claim-level evidence ledger

Only C-014 below is an admitted historical claim. R07-T labels identify **researcher-derived tests or stronger extrapolations**, not additional claims attributed to Luke.

| ID | Proposition assessed | Judgment | Evidentiary basis and boundary |
|---|---|---|---|
| C-014 | **A nominal approver overwhelmed by output can bear responsibility without meaningful agency.** | **Supported within stated scope** as a conditional possibility; field prevalence unresolved | S01–S06 establish relevant task/attention mechanisms; S14–S16 distinguish organizational control from attributed responsibility. No single study identifies the complete chain for all contemporary knowledge work. “Responsibility” must not silently mean deserved blame or adjudicated liability. |
| R07-T1 | A recorded approval or available veto proves meaningful control. | **Revised/qualified**: insufficient evidence of meaningful control | Verification and intervention opportunities coexist with errors in S03–S08. Error alone does not prove absence of agency; the opportunity, understanding and effective control must be assessed. S13 adds a separate normative account. |
| R07-T2 | More model detail or explanation necessarily improves decisions. | **Contradicted in stated scope** as a universal | S05–S07 separate comprehension, acceptance and outcome measures; targeted aids can help without a general explanation benefit. |
| R07-T3 | People invariably defer more to AI than to equivalent human advice. | **Contradicted in stated scope** | S08–S09 supply source-label counterevidence. These are not tests of every type of assistance, workload or repeated exposure. |
| R07-T4 | Requiring human judgment necessarily improves over both solo alternatives. | **Revised/qualified** | S07 shows designed complementarity; S10–S11 show different professional-task results. Sufficient authority and net performance are distinct criteria. |
| R07-T5 | Accountability improves oversight regardless of what is rewarded or demanded. | **Contradicted in stated scope** | S04 shows task-directed trade-offs. Extrapolation to employment sanctions or liability remains unresolved. |
| R07-T6 | Effective review capacity must be assessed against actual verification demand. | **Supported within stated scope** as an analytical requirement | Capacity accounting and S01–S06 motivate the test. No universal rate, staffing ratio or critical output threshold is established. |
| R07-T7 | Selective review plus audit is generally superior to universal review. | **Unresolved** | Section 8 supplies a comparative protocol, not an estimated general advantage. Selection quality, harms and cost matter. |
| R07-T8 | A legally compliant or highly accurate system thereby has legitimate authority. | **Unresolved as a normative conclusion; not an empirical inference** | S13, S15 and S17 distinguish control, governance and legal obligations. Author judgment and jurisdiction-specific analysis remain necessary. |
| R07-T9 | Occupying a meaningful review role produces durable skill and higher wages. | **Unresolved** | Current task results do not identify retained skill, career effects or surplus distribution. Reconcile with R-08, R-09 and D-002. |

## 10. Implications, investigated gaps and author-only choices

### R-08: apprenticeship

The critical learning variable is the work the station actually elicits. Independent first judgments, diagnosis of disagreement and substantive feedback can make a review role developmentally different from rapid acceptance. However, the short experiments here do not establish retained learning or the necessary amount of manual foundations. D-001 should remain an explicit author commitment tested by R-08's learning evidence, rather than be presented as a result of automation-bias research. A supervisor also needs capacity and authority: adding a senior signature does not resolve the same problem one level higher.

### R-09: senior stocks and incentives

Present correction, coaching and readiness for rare events consume partly different resources. Staffing calculations should include each where the workflow depends on it. The accountability experiment makes metric design a plausible mechanism, while the accident case makes organizational allocation visible. Neither identifies the wage return to judgment, the optimal senior/junior ratio or inevitable expertise collapse. D-002's distinction between contribution and compensation remains essential. Evidence of nominal accountability alone cannot support a prediction that consequential operators will gain bargaining power.

### R-13: institutional reliability

Treat the human review channel as a fallible, capacity-limited component. Test correlated failures, omissions, intervention latency, bypass routes and recovery. Deterministic checks may reduce verification demand, but only for properties they actually test. Additional model critics may improve the evidence presented to a human or reproduce the same error. A trace shows what was recorded, not necessarily what was understood. A successful risk gate and a legitimate allocation of authority are different deliverables.

### What remains genuinely unknown

The research investigated interface interventions, advice-source effects, workload/verification mechanisms, professional simulations, responsibility case studies and enacted oversight rules. It did **not** find a defensible universal review-volume threshold, a broadly validated scale combining capability and authority, or a causal workplace estimate linking approval loads to blame allocation and compensation. The reviewed systematic searches also leave a recency gap: S12 ends in 2022, while S10–S11 add particular generative-AI experiments rather than a comprehensive update of the entire field.

Important next studies would follow actual organizations through repeated use and model changes, compare risk-based with universal review under equivalent resources, examine whether staff can exercise escalation without career penalty, and measure delayed independent skill. They should sample failures missed by the system as well as flagged disagreements, preserve outcomes for affected people, and avoid treating researcher-set correctness labels as resolutions of legitimate value conflicts. The clinical studies' mixed results are a reason for task-specific evaluation, not a reason to generalize either optimism or pessimism.

Author-only questions remain: Which decisions require accountable human authorization even if a narrow accuracy benchmark favors automation? What delays or costs are acceptable to preserve contestability and recourse? Whose reasons determine the objective, and which powers must affected people possess? The literature can reveal consequences of answers, but cannot choose the book's normative commitments.

**Recommended use in the book:** retain C-014, explain the difference between assigned responsibility and effective agency, and place the burden of demonstration on the actual workflow. Do not replace it with a universal “human in the loop is a fiction” thesis or a claim that meaningful human authority is permanently secured by superior human capability.

## Bibliography and source-access appendix

All sources below are public and were inspected on 4 October 2026. “Inspected” identifies the substantive material actually used, not a claim to have read every cited reference, supplementary file or underlying dataset. Downloading a full document did not convert its conclusions into verified facts. Source IDs are local to R-07.

### R07-S01

Bainbridge, Lisanne. 1983. “Ironies of Automation.” *Automatica* 19(6):775–779. [DOI](https://doi.org/10.1016/0005-1098(83)90046-8); [public scan](https://gwern.net/doc/sociology/technology/1983-bainbridge.pdf). Inspected the primary article's task, monitoring and solution discussion, pp.775–779. Public mirror, not publisher-hosted. Historical conceptual synthesis; no new participant sample.

### R07-S02

Goddard, Kate, Abdul Roudsari, and Jeremy C. Wyatt. 2012 [online 2011]. “Automation bias: a systematic review of frequency, effect mediators, and mitigators.” *JAMIA* 19(1):121–127. [Full text](https://pmc.ncbi.nlm.nih.gov/articles/PMC3240751/); DOI 10.1136/amiajnl-2011-000089. Inspected methods, findings, indicative meta-analysis, mitigation and limitations. EPSRC-supported doctoral research; no competing interests declared. Supplements not reanalyzed.

### R07-S03

Lyell, David, and Enrico Coiera. 2017 [online 2016]. “Automation bias and verification complexity: a systematic review.” *JAMIA* 24(2):423–431. [Full text](https://pmc.ncbi.nlm.nih.gov/articles/PMC7651899/); DOI 10.1093/jamia/ocw105. Inspected inclusion criteria, quality assessment, Tables 1–2, discussion and limitations. HCF Research Foundation doctoral support. Review-level complexity coding is not an independent intervention.

### R07-S04

Skitka, Linda J., Kathleen L. Mosier, and Mark D. Burdick. 2000. “Accountability and automation bias.” *International Journal of Human-Computer Studies* 52(4):701–717. [DOI](https://doi.org/10.1006/ijhc.1999.0349); [public author-posted text](https://www.researchgate.net/publication/222529002_Accountability_and_automation_bias). Inspected §§4–6 and Tables 1–4. Author-hosted and CiteSeer PDF retrievals failed; the public article transcription supplied methods/results. No account or access-control bypass used.

### R07-S05

Buçinca, Zana, Maja Barbara Malaya, and Krzysztof Z. Gajos. 2021. “To Trust or to Think: Cognitive Forcing Functions Can Reduce Overreliance on AI in AI-assisted Decision-making.” *PACM HCI* 5(CSCW1), Article 188. [Author PDF](https://kgajos.seas.harvard.edu/papers/bucinca21trust.pdf); DOI 10.1145/3449287. Inspected §§3–6, especially Tables 1–3 and participant exclusions. The nine randomized designs included exploratory conditions outside the six reported designs.

### R07-S06

Poursabzi-Sangdeh, Forough, Daniel G. Goldstein, Jake M. Hofman, Jennifer Wortman Vaughan, and Hanna Wallach. 2021. “Manipulating and Measuring Model Interpretability.” *CHI '21*. [Author PDF](https://www.jennwv.com/papers/manipulating.pdf); DOI 10.1145/3411764.3445315. Inspected experiments 1–4, outlier intervention, limitations and conclusion in the final CHI paper with appendices. Microsoft Research authors; registration links inspected as reported, not independently audited.

### R07-S07

Bansal, Gagan, et al. 2021. “Does the Whole Exceed its Parts? The Effect of AI Explanations on Complementary Team Performance.” *CHI '21*. [University-hosted PDF](https://aiweb.cs.washington.edu/ai/pubs/bansal-chi21.pdf); DOI 10.1145/3411764.3445717. Inspected §§3–6, recruitment/filtering and Fig.4. Funding includes ONR, NSF, UW, AI2 and Microsoft Research. Recruitment totals are not retained participant counts.

### R07-S08

Gaube, Susanne, et al. 2021. “Do as AI say: susceptibility in deployment of clinical decision-aids.” *npj Digital Medicine* 4:31. [Publisher full text](https://www.nature.com/articles/s41746-021-00385-9); DOI 10.1038/s41746-021-00385-9. Inspected methods, results, Figs.2–5 and limitations. Source-label manipulation used expert-authored advice; not a deployed machine-performance test. Supplementary datasets were not inspected.

### R07-S09

Alon-Barkat, Saar, and Madalina Busuioc. 2023 [advance online 8 February 2022]. “Human–AI Interactions in Public Sector Decision Making: ‘Automation Bias’ and ‘Selective Adherence’ to Algorithmic Advice.” *JPART* 33(1):153–169. [DOI](https://doi.org/10.1093/jopart/muac007); [accessible article PDF](https://arxiv.org/pdf/2103.02381). Inspected all three studies and Tables 1–10 in the 17-page advance-access PDF; final publisher HTML confirms metadata and Table 5. The original 2021 submission was not substituted.

### R07-S10

Goh, Ethan, et al. 2024. “Large Language Model Influence on Diagnostic Reasoning: A Randomized Clinical Trial.” *JAMA Network Open* 7(10):e2440969. [Full text](https://pmc.ncbi.nlm.nih.gov/articles/PMC11519755/); DOI 10.1001/jamanetworkopen.2024.40969. Inspected methods, Tables 1–3, model-only comparison and limitations. US academic-site recruitment; Microsoft-affiliated coauthor disclosed. No raw transcripts or participant-level reanalysis performed.

### R07-S11

Goh, Ethan, et al. 2025. “GPT-4 assistance for improvement of physician performance on patient care tasks: a randomized controlled trial.” *Nature Medicine* 31:1233–1238. [Publisher record](https://www.nature.com/articles/s41591-024-03456-y); [PMC author manuscript](https://pmc.ncbi.nlm.nih.gov/articles/PMC12380382/). Inspected methods, results and limitations in PMC; compared principal estimates with publisher record. [17 February correction](https://www.nature.com/articles/s41591-025-03586-x.pdf) restores contribution footnotes. Moore Foundation support and Microsoft affiliation are disclosed.

**S11 version caution:** PMC gives inconsistent completed-case arm counts (176/199 versus 178/197; both total 375). We retain the consistent randomized denominator, 92, and matching published effect estimates. Supplements were not reanalyzed; the manuscript is not the final typeset article.

### R07-S12

Mehrotra, Siddharth, Chadha Degachi, Oleksandra Vereschak, Catholijn M. Jonker, and Myrthe L. Tielman. 2024. “A Systematic Review on Fostering Appropriate Trust in Human-AI Interaction: Trends, Opportunities and Challenges.” *ACM Journal on Responsible Computing* 1(4), Article 26. [Final published PDF](https://pure.tudelft.nl/ws/portalfiles/portal/235594298/3696449.pdf); DOI 10.1145/3696449. Inspected §§3–6 and 8–9. Dutch Hybrid Intelligence funding; explicitly limited search through June 2022.

### R07-S13

Santoni de Sio, Filippo, and Jeroen van den Hoven. 2018. “Meaningful Human Control over Autonomous Systems: A Philosophical Account.” *Frontiers in Robotics and AI* 5:15. [Full text](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2018.00015/full); DOI 10.3389/frobt.2018.00015. Inspected tracking/tracing definitions, implications and conclusion, especially pp.6–12 of the PDF. Philosophical analysis; no empirical validation sample.

### R07-S14

Elish, Madeleine Clare. 2019. “Moral Crumple Zones: Cautionary Tales in Human-Robot Interaction.” *Engaging Science, Technology, and Society* 5:40–60. [Journal record](https://estsjournal.org/index.php/ests/article/view/260); [PDF](https://estsjournal.org/index.php/ests/article/download/260/177/); DOI 10.17351/ests2019.260. Inspected framing, case analyses and implications. Data & Society affiliation. Selected public cases and media narratives; original accident archives not independently reconstructed here.

### R07-S15

Green, Ben. 2022. “The flaws of policies requiring human oversight of government algorithms.” *Computer Law & Security Review* 45:105681. [Author-hosted final article](https://www.benzevgreen.com/wp-content/uploads/2022/04/22-clsr.pdf); DOI 10.1016/j.clsr.2022.105681. Inspected §§3–5 and policy-document appendix. Interpretive policy analysis, not a systematic causal evaluation of 41 deployments.

### R07-S16

National Transportation Safety Board. 2019. *Collision Between Vehicle Controlled by Developmental Automated Driving System and Pedestrian, Tempe, Arizona, March 18, 2018*. HAR-19/03. [Official report](https://www.ntsb.gov/investigations/accidentreports/reports/har1903.pdf); [investigation record](https://www.ntsb.gov/investigations/Pages/HWY18MH010.aspx). Inspected executive findings, §§2.2.2–2.2.3 and §3.2, especially printed pp.44–47 and 59. Web text accessible despite failed direct download. Case-specific safety investigation; not a liability judgment.

### R07-S17

European Union. Regulation (EU) 2024/1689, as amended by Regulation (EU) 2026/1744. [EUR-Lex consolidation dated 27 July 2026](https://eur-lex.europa.eu/eli/reg/2024/1689/2026-07-27/eng). Inspected Arts.14, 26 and 113 and amendment metadata; compared original 2024 text. European Commission, [“AI Omnibus enters into force,” 27 July 2026](https://digital-strategy.ec.europa.eu/en/news/ai-omnibus-enters-force), updated 31 July. Direct access to the amending act encountered a bot check; no bypass attempted. Consolidated text and official notice establish the version used, with authoritative-act caveat above.

## Method, exclusions and reproducibility

This is a **focused analytical literature review**, not a newly registered systematic review or pooled meta-analysis. Searches on 4 October 2026 targeted automation bias, verification complexity, cognitive forcing, explanation and complementary performance, advice-source comparisons, meaningful human control, institutional responsibility and current EU oversight provisions. Search results were leads; substantive claims above were checked against primary studies, full review text, official investigation findings or statutory text. Source-hosted PDFs and public full-text repositories supplied methods and results where publisher routes failed. No paid access, new accounts, private records, third-party contacts or circumvention was used.

The search strategy deliberately sought counterevidence: successful assistance, targeted interventions, non-significant effects and less-than-universal algorithmic deference. It did not attempt exhaustive retrieval of every aviation, clinical, public-administration or human–AI study. The synthesis gives more weight to a controlled comparison for a narrow causal claim than to a general assertion in a discussion section, while retaining field and institutional evidence for questions laboratory designs do not identify. Systematic reviews overlap with each other and with the primary studies described here; they are mapping and triangulation, not extra independent votes.

No numerical pooling across these tasks is appropriate without a separate harmonization exercise. Samples, units, error prevalence, control conditions and outcomes differ. The review also avoids promoting laboratory “correctness” into legitimacy, professional simulations into patient outcomes, observed post-scandal behavior into a randomized awareness treatment, or policy language into demonstrated protection.

The broad Parasuraman–Manzey 2010 review was investigated as a lead; full-document retrieval did not succeed and it is not an independently analyzed evidentiary capsule here. Its attentional thesis is discussed only insofar as S03 explicitly evaluates it. Vaccaro's 2024 synergy meta-analysis and the P&G/BCG studies are reserved to their source-owning programs. MASAI and other workflow-redesign clinical evidence belong in R-04. These exclusions avoid duplicate source summaries, not contrary findings.

The source and decision corpus, historical ledger and author decisions remain unchanged. The stronger operational tests in this review are research proposals. Their adoption, the book's normative claims and publication into the authoritative repository remain separate decisions.
