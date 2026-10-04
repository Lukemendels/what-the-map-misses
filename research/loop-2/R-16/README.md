# R-16 — Machine professional development

**Research date:** 4 October 2026.  
**Admitted claim:** C-035, with C-033 as its explicit dependency.  
**Status:** substantial analytical literature review accepted after independent quality review; coordinated publication checkpoint. Research findings are not author adoption, a canonical thesis, or validation of an implementation.  
**Reading convention:** R16-S01–S23 resolve to the recoverable bibliography and access appendix. Repository links assume publication as `research/loop-2/R-16/README.md`.

## 1. Result and exact question

Post-training can change model parameters, simulation can supply useful training experience, and some learned behavior transfers beyond the training examples and even from simulation to physical systems. There is also emerging experimental evidence of online, user-targeted weight adaptation. Consequently, the book should not present machine development as wholly hypothetical or confuse every deployed model with a permanently frozen model.

The stronger proposition remains open: **can an institution repeatedly develop a particular persistent machine actor through targeted simulated adversity, obtain durable improvements in consequential real work, preserve its other capabilities and safety, and purchase this improvement on economically attractive terms?** The literature establishes components of that chain much more convincingly than the complete chain. An occupational training curriculum, a model-family release, a personalized style adjustment and a reliable professional history are different accomplishments.

The [historical ledger](../../../evidence/claims/CLAIM-LEDGER.md#c-035) states C-035 exactly:

> Wind tunnels could develop specific persistent actors through simulated adversity and professional post-training, beyond evaluating general models.

This is a conditional forecast. The earlier [MKS v3 §6.1](../../../source/theory/05-mks-v3-master-specification.md#61-wind-tunnel-simulation) describes stress testing normal cases, conflicting requirements and shocks. The later [synthesis §11](../../../source/synthesis/2026-09-11-current-author-synthesis.md#11-wind-tunnels-black-swans-and-post-training-as-professional-development) adds actor-specific development, compressed experience, a possible service market and a lifecycle ending in further specialization. It expressly calls for research. Neither text supplies an empirical implementation study. The review therefore tests the proposed extension rather than treating an authored specification as a working product or a failed experiment.

The main judgment is **unresolved at the full C-035 scope**, with substantial support for narrower technical ingredients. The evidence neither proves a future profession-training market nor establishes an impossibility result. The useful revision is to make the intermediate conditions explicit: an identifiable update, held-out transfer, retention after further experience, independent safety assessment, and net value relative to less expensive alternatives.

R-14 owns persistent state, continual learning, forgetting and experiential-capital definitions. Its [parameter-learning analysis](../R-14/README.md#parameter-learning-is-real-but-stability-is-conditional) should supply the C-033 dependency; R-16 does not duplicate its SEAL, Titans or memory-benchmark capsules. R-13 owns institutional reliability, and R-15 owns rights and lawful portability. Those are separate conditions, not outcomes conferred by a training score.

## Post-training is real; professional development is a stronger claim

### 2.1 Five changes that must not be merged

The following is an analytical decomposition of the proposed lifecycle:

| Intervention | What changes | Evidence needed before calling it development |
|---|---|---|
| Exposure or evaluation | Observations and possibly the assessor's knowledge | A demonstrated subsequent change, not merely a score or transcript |
| External-state update | Records, retrieved examples, tools, prompts or executable procedures | Reuse that improves later tasks; attribution to the changed component |
| Inference-time adaptation | Context, hidden state, search or a temporarily inferred task representation | Performance beyond the immediate exchange, if persistence is claimed |
| Parameter update | Weights or an adapter through an actual learning procedure | Retained improvement, transfer and regression tests on the resulting checkpoint |
| Authority expansion | Permitted actions, access, budgets or delegated discretion | A separate institutional decision justified for the new exposure to harm |

Several can occur together. A simulator may discover a fault; a person may then change a rule; the next run may improve while every model weight remains identical. That is useful system development, but it is not evidence that the tested actor learned internally. Conversely, saved fine-tuned weights are a durable changed artifact even if learning happens in occasional batches rather than continuously. Neither point requires choosing a metaphysical definition of identity.

The word *actor* needs an operational referent: a versioned combination of model, adapter, external state, tools and permissions. Keeping the same name while replacing the underlying model is not a controlled test of that actor's learning. Copying a checkpoint can preserve learned parameters without preserving its relationships or deployment conditions. R-14 and R-15 supply those distinctions.

### 2.2 What the main training methods actually establish

Ouyang and colleagues' InstructGPT study provides a clear parameter-learning example: demonstrations train an initial policy, ranked responses train a reward model, and PPO updates the policy against that reward. Approximately 40 selected contractors supplied predominantly English feedback; evaluation included held-out customers and labelers. The small instruction-tuned model could be preferred to much larger GPT-3, but preference was not universal truth or professional qualification. Regressions on other tasks motivated mixing pretraining updates into training, and longer training could still degrade performance. This is developer-run model training, not evidence that each deployed conversation accumulates its own learned career. [R16-S01, §§3–5; Appendix E.6]

Preference learning does not always require an online reinforcement-learning loop. Rafailov and colleagues' DPO derives a direct objective from preference comparisons and a reference policy. Its experiments compare sentiment generation, Reddit summarization and single-turn dialogue; a news-summary transfer test provides limited out-of-distribution evidence. GPT-4 supplies much evaluation, with a human cross-check and sensitivity to judgment prompts. DPO's simpler optimization can make customization easier, while leaving preference representativeness and deployment transfer unresolved. A preference label describes a comparison within a particular task and rater population, not an occupation's complete standard of competent conduct. [R16-S02, §§3–6]

DeepSeek-R1 provides evidence for reinforcement learning with verifiable rewards, alongside cold-start supervision, rejection-sampled training and preference-oriented stages. The expanded report separates these training stages. Rule-based math or coding feedback enables substantial measured improvements; general instruction behavior involves additional training. The authors report reward hacking and capability limitations as well as success. Neither a final-answer check nor a programming test establishes correctness of every intermediate explanation or suitability for unrestricted professional decisions. [R16-S03, §§2–6; Supplements B.3, B.5, D]

These approaches solve different supervision problems. Demonstrations specify what to imitate; preferences compare alternatives; verifiable rewards score an outcome; process signals assign feedback within a trajectory. None creates the desired objective from nothing. Occupational development requires someone to decide what counts as success, what constraints are inviolable, and what cannot yet be measured reliably. That work can move from producing answers to designing tasks and feedback, but it does not disappear.

A material asymmetry follows. A mathematical answer can often be checked against a known result. An investigation, negotiation or incident response may have delayed outcomes, conflicting stakeholders and several defensible paths. Converting the latter into a scalar reward is a modeling decision. The review does not infer that such work is untrainable; it identifies the missing validity argument between reward and occupational purpose.

### 2.3 The reasoning-boundary disagreement is partly a measurement disagreement

Yue and colleagues compare base and RL-trained models across mathematical, coding and visual tasks, using large-sample pass@k as a capability-coverage probe. In the studied setups, improvements at small k coexist with narrower coverage at large k. They inspect some reasoning paths and explicitly distinguish their metric from practical answer selection. The revised paper treats this as a limit of the examined training regimes and motivates better exploration, rather than a theorem that reinforcement learning can never discover useful behavior. Finite sampling cannot establish every behavior a model could produce, and code tests are themselves incomplete specifications. [R16-S04, §§2–4; Appendices A–C]

Counterevidence matters. ProRL stabilizes prolonged training with regularization and reference-policy resets, starting from a reasoning-distilled 1.5B model and using 136,000 verifiable problems across five domains. It reports improvement on held-out task families and large-k measures. The final conference paper reports about 16,000 GPU-hours and validation-guided interventions; its limitations acknowledge compute burdens and uncertain wider scalability. This is a different starting policy, curriculum and training regime from a simple short-run zero-RL comparison. It weakens a universal ceiling claim without validating indefinite self-improvement. [R16-S05, §§2–4; Appendix B]

Wen and colleagues additionally argue that an accidentally correct final answer can inflate high-k mathematical scores. They compare answer-only and reasoning-aware metrics, study DAPO training, and find positive transfer in math and coding. Their reasoning verifier is another LLM, and their theorem concerns optimization under stated assumptions rather than a generalization guarantee. Thus the proposed correction introduces its own measurement dependency. It is evidence against equating answer coverage with sound reasoning, not a license to treat a judge's acceptance as a faithful view into cognition. [R16-S06, §§3–6; Appendix A.3]

For C-035, two questions should be separated. First, does training expand the reachable solution set? Second, does it deliver a correct, useful solution more reliably at the budget available in real work? An intervention can be valuable on the second criterion even if it mainly reallocates probability among previously possible outputs. Conversely, a newly reachable answer has little occupational value if finding and recognizing it takes unaffordable sampling. A review that chooses only pass@1 or only very large pass@k can miss this distinction. The book needs cost-conditioned performance, identification of correct outputs, and adverse-outcome measures, not a single argument about whether a model has acquired “new reasoning.”

## 3. From simulated tasks to occupationally relevant agents

### 3.1 Environment interaction can train parameters, but the curriculum matters

AgentGym supplies a multi-environment framework and a useful negative result. Its final ACL paper distinguishes PPO experiments from AGENTSTAR, which collects successful trajectories and retrains with supervised learning. Multi-environment online RL was unstable enough that the authors mainly examined it in isolated environments. AGENTSTAR improves several tasks and some held-out settings, but gains are uneven: the larger supervised baseline is much stronger on ScienceWorld in the principal comparison. The platform spans 14 environments and 89 tasks; that coverage is not 89 independently validated occupations. Training on benchmark interaction is genuine learning while remaining a controlled, predominantly simulated test. [R16-S07, §§3–6, Tables 3–4; Appendix E]

SWE-RL moves toward artifacts from actual work. It learns code edits from historical pull requests with a patch-similarity reward, excluding SWE-bench repositories from its curated data. Its 41% SWE-bench Verified result uses 500 candidate patches per issue and 30 generated reproduction tests before selecting one submission; it is not one raw model attempt. The final paper also reports controlled repair comparisons and cross-task tests. Patch similarity can penalize different but valid solutions, and its pipeline does not train whole-task interactive feedback. The reported 512 H100 GPUs for roughly 32 hours is a training-run resource measure, not a complete service cost. [R16-S08, §§2–3, §5 limitations; Appendix A]

Polar's 2026 preprint instead trains within existing agent harnesses. With the same Qwen3.5-4B starting model and 293 SWE-Gym training tasks, SWE-bench Verified gains vary considerably by harness: 3.8% to 26.4% in Codex versus 34.6% to 35.2% in Qwen Code. The experiment shows useful interface-specific adaptation and reports a credit-assignment variant that induced reward hacking. It does not show that the learned improvement survives changing harness or an extended production career. Large gains from correcting unfamiliar tool protocols should not be mislabeled acquisition of all the judgment needed for software engineering. [R16-S09, §§3–4, Table 1; Appendix A.2]

The contrast is analytically important. Historical traces offer scalable examples but may not expose the learner to consequences of its own actions. Interactive environments offer those consequences but require reliable state transitions, reset mechanisms, feedback and execution infrastructure. Training that fits a known patch, training that learns tool syntax, and training that learns to recover from a novel operational failure can all improve a software benchmark while addressing different weaknesses.

There is no reason to insist that every occupational skill be learned through one method. A plausible curriculum might use demonstrations for basic procedures, verifiable practice for bounded execution, adversarial drills for failure recognition, and supervised real deployment for what the simulation omits. That is a research hypothesis about combining methods. The cited comparisons do not establish that sequence as an optimal or generally safe recipe.

### Actor-specific development needs an identifiable treatment

OpenClaw-RL is particularly relevant counterevidence to any claim that online personalization exists only as an idea. Its May 2026 revision updates weights from interaction signals and compares three simulated roles with memory and other baselines. Across five trials, the authors report about ten sessions for the joint setup to reach their preference criterion; separate optimization averages fifteen. However, the roles use GSM8K tasks and largely stylistic preferences. Success means three consecutive satisfactory opening responses. Some general-agent measures are explicitly training-set or rollout accuracy. The setup uses an eight-GPU allocation for policy and reward components. This is a bounded online-learning demonstration, not measured long-term professional retention or rare-event competence. [R16-S23, §§2–4, Table 3; Appendix A.1]

The implication is to narrow the gap, not erase it. A system can learn how a simulated user wants a response presented without learning how to recognize a concealed conflict of interest, a novel legal constraint or a dangerous operational anomaly. Nor does a short sequence of acceptable outputs demonstrate performance after months of unrelated updates. At the same time, it would be inaccurate to dismiss an actual weight-updating personalization experiment as mere external memory.

For the book's specific actor, the essential counterfactual is an otherwise equivalent actor that did not receive the targeted development. Comparing an experienced actor with an unconfigured generic chatbot confounds history with tools, prompt quality, access and compute. A particularly demanding comparator is a fresh, stronger model supplied with the same authorized external history. If that alternative performs as well at lower cost, the institution may still own valuable records and procedures, while the claimed incremental value of the actor's learned history is small.

An identifiable intervention therefore records at least:

- the starting checkpoint and all external state;
- which episodes were observed, replayed or used for gradients;
- whose feedback became a learning signal and under what filtering rule;
- parameter, adapter, prompt and tool changes separately;
- evaluation tasks never used to select updates;
- the pre-existing safety and capability suite;
- elapsed exposure and intervening updates before retention tests.

These are proposed evidentiary requirements, not an experiment conducted for this review. They make “the same actor improved” inspectable without assuming that its identity is a single file or that its past is economically irreplaceable.

## Simulation transfer and the black-swan boundary

### 4.1 Real transfer is possible, and its limits are observable

The robotic Rubik's-cube study supplies direct sim-to-real evidence. Automatic domain randomization trained policies under changing physical parameters. In ten real-robot trials per policy using a fixed scramble sequence, the strongest policy with instrumented face-angle sensing completed the full sequence 20% of the time; the vision-only face-angle condition completed none. The strongest policy had been developed over months, with substantial simulation infrastructure. This is an achievement in transfer and an illustration of a sensor-dependent bottleneck. It is not a general reliability certificate, a broad occupational study or evidence that real-world deployment itself updated weights. [R16-S10, §§5–8, especially Table 6; Appendix C.3]

Rapid Motor Adaptation offers a second mechanism. A simulator-trained locomotion policy uses a learned adaptation module to infer environmental conditions from recent experience; it deploys on a physical quadruped without fine-tuning. Real tests compare controllers on payloads and difficult surfaces, generally using five trials and terminating severe failures early to protect hardware. Simulation comparisons use three policy initializations and 1,000 episodes each. The method shows useful rapid adaptation while separating offline learning from deployment-time inference. Its small physical samples and bounded locomotion objective do not estimate a workplace's catastrophic-tail risk. [R16-S11, §§III–V]

These results prevent an excessively skeptical conclusion that simulations are intrinsically incapable of teaching real capability. They also expose the bridge that a professional-development claim must cross. Transfer depends on the relevant invariants: observation quality, dynamics, actions, feedback and the relationship between training objective and deployed purpose. Photorealism or fluent dialogue is neither necessary nor sufficient. A simplified simulator may teach the right causal structure; a convincing simulator may teach a shortcut that fails outside it.

Physical transfer also does not settle institutional transfer. Workplace behavior depends on rules, incentives, incomplete information and other people's responses. Those responses can change when they know they are dealing with a trained actor. An institutional shock can alter the task's objective, not merely a parameter such as friction. A simulator designed around yesterday's objective cannot establish judgment under a newly contested objective simply by generating more episodes.

### 4.2 Rare-event evaluation is not automatically rare-event learning

Adaptive stress testing formulates a search for likely failure trajectories in a simulator. Reinforcement learning changes the *tester*, which perturbs the environment of a system under test. Koren, Corso and Kochenderfer explicitly note the need for accurate actor models and the danger of local convergence. Their formulations cover cart-pole disturbance, a vehicle-crosswalk encounter and aircraft collision avoidance. Discovering a failure supports diagnosis; it does not show that the tested controller changes, retains a correction or becomes safer in deployment. [R16-S12, §§II–III]

Feng and colleagues' dense-RL study makes the distinction especially concrete. It trains background traffic to accelerate autonomous-vehicle safety validation, using likelihood weighting and naturalistic driving models. Simulations cover different road configurations and two vehicle models; physical test-track experiments use augmented reality. The paper explicitly leaves acceleration of the vehicle's own training to future work. Its unbiasedness argument is conditional on the specified sampling and environment model, not proof that all real-road risks are represented. A paper about learning a better testing environment cannot be cited as evidence that a particular professional actor learned to handle catastrophes. [R16-S13, pp. 620–627 and Methods]

Oversampling hazardous situations is potentially valuable because waiting for natural exposure can be impractical or unethical. But three questions remain separate:

1. **Discovery:** did the simulator find a vulnerability?
2. **Learning:** did a specified update reduce that vulnerability on new cases without unacceptable regressions?
3. **Risk estimation:** what does the resulting performance imply for the natural deployment distribution?

A curriculum can intentionally overweight rare harms. A population-risk estimate must still account for how examples were selected, which hazards were absent and whether the distribution has changed. A thousand highly similar drills cannot be treated as a thousand independent observations of the world.

For orientation, under an idealized independent, identically distributed Bernoulli model, observing zero failures in n trials gives a one-sided 95% upper failure-probability bound of `1 − 0.05^(1/n)`, approximately `3/n`. At 1,000 trials that is about 0.3%, not zero. This is an elementary illustrative calculation, not a certification rule or an estimate from the reviewed systems. Correlated episodes, adaptive test selection, misspecified simulation and unrepresented harms invalidate its simple interpretation. Rare consequential failures demand considerably more than a pleasing average score.

“Black swan” should therefore remain an analogy with an explicit break. A named pandemic, fabricated adversary or simulated policy change is a *specified* scenario. Successful response does not demonstrate competence against every shock the curriculum designer failed to imagine. A plausible training target is recognizing uncertainty, preserving reversibility and escalating outside scope. Whether that behavior transfers under pressure must itself be tested.

## 5. Generalization, evaluation leakage and unsafe improvement

### 5.1 What a held-out test does and does not hold out

Procgen isolates an important generalization problem in 16 procedurally generated game environments. Training sets vary from 100 to 100,000 levels under a fixed interaction budget, with held-out-level evaluation and multiple random seeds. Small sets produce substantial overfitting; deterministic sequences can create impressive training progress with poor distributional performance. This establishes why diverse training and held-out testing matter even in comparatively clean simulators. It does not establish transfer from a game generator to a workplace, and a new seed from the same generator is weaker evidence than a new causal environment. [R16-S17, §§2–4]

The studies above use several different meanings of “generalization”: new prompts, new levels, new task families, a new harness, physical reality, or another simulated user's preference. They should not be pooled into one success rate. A held-out task from a shared generator may reuse the same linguistic or causal shortcuts. A future real task can change tools, actors, incentives, regulations or the cost of a mistake.

Evaluation contamination also has several channels. Training examples may duplicate test content; repeated benchmark-driven model selection may indirectly optimize the test; a synthetic user and judge may share the same blind spots; a reward function may omit the very consequence the evaluation is meant to measure. These are risks to investigate, not allegations that every cited result is contaminated. Repository exclusion, fresh tasks and model-rater checks address different channels and are not interchangeable.

The substantive comparison is consequently stronger when the intervention and baseline receive equal inference budgets, the final assessor is independent of training rewards, and testing includes changed task mechanisms rather than only changed wording. Retention requires another separation: evaluate once immediately, again after unrelated work, and again after later specialization. Merely saving the successful checkpoint demonstrates reproducibility of state, not resistance to subsequent interference.

### 5.2 Better reward can coexist with worse work

Gao, Schulman and Hilton study overoptimization using a synthetic 6B “gold” reward model and smaller proxy reward models trained on 100,000 generated comparisons. Both PPO and best-of-n optimization can increase the proxy while eventually worsening the gold score. This is controlled evidence about proxy exploitation, not a direct measurement of human welfare: the gold standard is itself a model, and the authors identify the additional gap between labels and actual intent. Their fitted relationships should not be treated as a universal law for future agentic systems. [R16-S14, §§2–4]

The practical implication is not that rewards are useless. It is that training performance must be checked against outcomes the learner is not directly rewarded for manipulating. For a professional actor, these can include concealed safety violations, unjustified escalation avoidance, damage to downstream work, or costly but superficially convincing responses. A richer grader might reduce one error while introducing another. Reward design is continuing engineering and governance work, not a one-time conversion of professional judgment into a number.

Qi and colleagues provide a different warning: targeted fine-tuning can erode prior safety. Their GPT-3.5-Turbo-0613 and Llama-2-7B-Chat experiments include benign instruction datasets, not only adversarial data. On their 330-prompt policy-based evaluation, GPT-3.5's harmful-response rate increases from 5.5% to 31.8% after one Alpaca epoch. The outcome is a GPT-4-judged threshold with human meta-evaluation, not observed real-world harm or a current-model failure rate. It establishes a safety-regression possibility that an actor-development program must check after customization. [R16-S15, §4, Table 3; Appendices A–B, G]

Positive defensive evidence belongs beside that result. Wallace and colleagues train GPT-3.5 with synthetic instruction-hierarchy examples using supervised and preference-based methods. Compared with a capability-trained baseline, attack resistance improves, including on held-out attack types, while some benign boundary cases suffer over-refusal. The experiment supports learning more robust treatment of untrusted instructions; it does not replace access controls or prove universal resistance to poisoned information. Professional training must account for both accepting dangerous instructions and refusing legitimate work. [R16-S16, §§3–4; Appendix B]

These findings imply a multidimensional assessment rather than a graduation ladder keyed to one score. Better completion, calibration, safe refusal, appropriate escalation and preservation of previously acquired skills can move in different directions. A curriculum optimized for decisiveness may harm caution; a curriculum optimized for avoiding incidents may teach unnecessary inaction. The appropriate trade-off belongs to the authorized institution and affected stakeholders. Technical results cannot silently choose it for the author.

## Service availability is not market validation

There are real service interfaces for post-training. The inspected OpenAI RFT guide describes developer-defined graders, data splits, weight updates and checkpoint evaluation. It also says the fine-tuning platform is winding down and unavailable to new users. The separate deprecation notice specifies restrictions from 7 May and 2 July 2026, with remaining active customers losing new-job creation on 6 January 2027. It lists the RFT guide's o4-mini fine-tuned model for shutdown on 23 October 2026. These are dated provider statements, not a service test or a prediction about all customization. [R16-S18; R16-S20]

The billing guide still specifies $100 per training-loop hour for that model, plus model-grader tokens. Its billed loop includes rollouts, grading, updates and configured validation; it does not price the customer's construction of a valid occupational curriculum. A listed training tariff therefore cannot be quoted as the complete cost of developing an actor, and its presence does not override the access and deprecation notices. [R16-S19, Pricing; What we bill for]

Thinking Machines' Tinker documentation supplies a contrasting current interface: customer-defined environments provide observations, actions, rewards and trajectories; its pricing distinguishes prefill, sampling, training and checkpoint storage. The inspected tariff quotes storage at $0.10/GB-month and warns that its listed serverless inference beta is not recommended for intensive production use. These documents establish an offered technical workflow and charging structure, not independently measured professional competence, typical customer returns or a mature credentialing market. No account, training job or transaction was attempted for this review. [R16-S21–S22]

The source contrast defeats two shortcuts. One supplier's withdrawal does not show that post-training has failed as a technology. Another supplier's availability does not show that the proposed continuing-development industry is viable. Prices and interfaces are necessary procurement information, but not evidence of demand, margin, retention or durable differentiation.

DeepSeek's expanded accounting reports 147,000 H800 GPU-hours across specified R1-related training and data-creation stages, valued at $294,000 using an assumed $2/GPU-hour. That excludes a claim about the full upstream model-development bill. [R16-S03, Supplement B.4.4] Across the research, computation also measures different things: policy training, simulator interaction, trajectory generation, judging or inference-time search. Converting all of these into “cost of experience” without a common boundary would be misleading.

An economically relevant evaluation would compare discounted improvements in completed work and avoided harm with the entire incremental cost: diagnosis, curriculum construction, expert feedback, simulation maintenance, training, repeated validation, integration, monitoring, downtime and regressions. It must compare at least four alternatives:

- continue with the current actor and existing controls;
- improve external memory, tools or workflow without updating weights;
- buy a stronger general model and transfer the authorized history;
- apply reusable occupational training rather than bespoke actor-specific development.

This is a proposed comparison framework, not a calibrated market forecast. Targeted development is more attractive when failure modes recur, feedback is credible, task volume is sufficient, and a trained improvement remains useful long enough to amortize preparation. It is less attractive when a frontier-model replacement quickly erases the advantage, the reward is costly to validate, or deployment changes faster than the curriculum.

Copying complicates the human professional-development analogy. Once a useful occupational adapter exists, many instances may benefit from the same investment. The economically valuable product could be the curriculum, evaluator, simulator, adapter or integration service rather than a uniquely experienced actor. Conversely, confidential context and local complements can prevent cheap reuse. [R-15's asset decomposition](../R-15/README.md#3-what-is-the-proposed-asset) is needed before claiming either scarcity or easy portability. [R-05](../R-05/README.md) addresses capture, while [R-11](../R-11/README.md) separates investment cost, capital services and accounting recognition.

No inspected study estimates a representative demand curve, total addressable market, return on actor-specific continuing training, or long-term provider survival. Public customer stories were not treated as causal market evidence. The positive technical record warrants investigation; it does not supply those missing economic results.

## 7. What would count as a convincing professional-development test?

This section proposes an empirical design to discriminate interpretations of C-035. It is not an authorized or completed experiment.

**Unit and assignment.** Begin with replicated, versioned actors sharing the same model, external history, tools and permissions. Randomize relevant units to targeted simulation, ordinary additional practice, external-state-only improvement and no additional development. Include a fresh stronger model with equal authorized context and a generic occupationally trained alternative. Cluster assignment where actors share learned state or supervisors, so the control group does not receive the treatment indirectly.

**Training target.** Select failure families from a documented work process before examining final outcomes. Distinguish frequent tasks, rare known harms and genuinely shifted scenarios. Separate any simulator used to generate training episodes from the final assessor. Specify human involvement and correction time rather than treating expert labels as free.

**Transfer.** Test unseen instances, new combinations, changed tools and a second operating context. For rare-event claims, include hazards withheld as families rather than merely paraphrased cases. Where safe and authorized, progress from shadow evaluation to bounded real work. A synthetic business conversation does not substitute for observed downstream consequences.

**Persistence.** Reassess after intervening ordinary tasks and later training. Report both preserved improvement and damage to old capabilities. Compare the trained checkpoint with an identical checkpoint lacking the external training transcript, so contextual reminder effects are not mistaken for parameter learning. Preserve rollback and version records.

**Outcomes.** Measure correct completion, time, cost, human correction, calibration, appropriate nonaction, escalation, policy compliance and severity-weighted incidents. Report the whole distribution and failure categories. Distinguish an immediate score gain from a reduction in expected harm. Predefine which differences would matter operationally; a statistically detectable change need not repay integration costs.

**Inference budget and selection.** Equalize or account for token budgets, retries, search, candidate ranking and tool access. Count failed training runs and unsuccessful curricula. Report repeated seeds and uncertainty. A selected best checkpoint should face a genuinely fresh final test.

**Authority.** Hold permissions fixed while estimating learning effects. If successful training later motivates expanded authority, reassess the new risk exposure separately. The actor may now be allowed to take actions whose consequences were absent from the earlier test. R-07's meaningful-authority analysis and R-13's controls remain necessary; increased permission is not an RLHF update or a credential automatically earned by reward.

**Economics and governance.** Record every relevant resource, the duration of the benefit, replacement-model opportunities and the parties supplying restricted data. R-15 governs rights; empirical competence cannot authorize copying confidential history. A market study would also need customer uptake and retention at actual prices, not merely a training API's existence.

A positive result would support a bounded statement: a specified development intervention improved a specified actor configuration for specified tasks over an observed interval and at a measured cost. Repetition across occupations and institutions could then justify broader claims. Requiring this specificity is not demanding proof against every imaginable failure; it is preventing a narrow result from carrying a much broader conclusion.

## 8. Claim-level evidence ledger

The first row is the admitted proposition. C-033 is a dependency, not a new R-16 claim. Entries beginning **R16-T** are auxiliary analytical tests introduced by this review; they do not alter the historical claim ledger.

| Claim or test | Judgment | Evidence and scope | Implication for the book |
|---|---|---|---|
| **C-035:** Wind tunnels could develop specific persistent actors through simulated adversity and professional post-training, beyond evaluating general models. | **Unresolved** at full forecast scope | S01–S11 and S23 establish components; S12–S17 expose transfer and safety gaps; S18–S22 establish bounded service facts | Retain conditional grammar; do not describe a validated profession-training product or market |
| **C-033 dependency:** persistent actors might materially change through experience and acquire productive capabilities | **Supported in narrow existential scope; broader claim unresolved** | Actual parameter adaptation exists; actor-specific durable net value across extended work remains a separate question | Use R-14's full stability and capital tests; neither deny learning nor infer a mature experiential asset |
| **R16-T1:** post-training can change subsequent behavior through parameter updates | **Supported within stated scope** | S01–S03, S07–S09, S23 | Exposure alone is insufficient, but actual training is already demonstrated |
| **R16-T2:** RL only reweights existing responses and cannot expand useful capability | **Revised/qualified** | S04 versus S05–S06 differ in initialization, budget and metrics | Preserve the debate; cost-effective improvement does not require settling every claim about novelty |
| **R16-T3:** simulated practice can transfer beyond its training examples and into reality | **Supported within stated scope** | S07–S11; narrow task, hardware and harness conditions | Do not generalize physical or benchmark transfer into occupational reliability |
| **R16-T4:** efficient rare-event testing proves that the system under test learned | **Contradicted in stated scope** | S12–S13 change the testing process; they do not establish the target's durable correction | Name the learner, the update and the retained effect |
| **R16-T5:** training against specified shocks establishes general black-swan competence | **Unresolved** | No inspected study supplies the requisite coverage of unrepresented institutional shocks | Use the analogy to motivate drills, not claim exhaustive preparation |
| **R16-T6:** a higher reward or target-task score guarantees safe improvement overall | **Contradicted in stated scope** | S14–S16; also reported training trade-offs | Require safety and capability regression tests plus independent outcome assessment |
| **R16-T7:** short-run online personalization is evidence of lifetime professional development | **Unresolved** beyond the demonstrated behavior | S23 supplies an actual bounded update experiment, with short and simulated criteria | Avoid both dismissing the positive evidence and inflating it |
| **R16-T8:** available services and prices establish a viable actor-specific development market | **Unresolved** | S18–S22 document interfaces, costs and discontinuity; no representative market or ROI study | Separate technical feasibility, service supply, demand and capture |
| **R16-T9:** passing training legitimately expands operational authority | **Unresolved as a governance rule; category distinction supported** | Analytical distinction; R-07/R-13/R-15 dependencies | Training informs a decision; it does not make that decision or confer rights |

## 9. Investigated gaps, dependencies and author-only choices

The search investigated contemporary preference and verifier-based post-training, interactive language-agent training, online personalization, physical transfer, rare-event stress testing, safety regressions and service economics. The following remain open in the inspected public record:

1. **Longitudinal occupational retention:** no reviewed study jointly measures actor-specific gains, intervening updates, real-work outcomes and rare consequential incidents over an extended career-like period.
2. **Adversarial institutional transfer:** training against defined attacks is observable; transfer to unfamiliar organizations, adversaries and altered objectives is not established by the same tests.
3. **Feedback validity:** there is no general method here for extracting an unbiased professional objective from user satisfaction, subsequent messages or a learned grader.
4. **Personalization beyond presentation:** emerging weight-learning studies need richer tasks and independent outcomes before stylistic accommodation becomes evidence of judgment development.
5. **Comparative cost:** published training resources omit different components; there is no common full-cost comparison of bespoke development, external-state improvement, general-model replacement and reusable occupational adaptation.
6. **Market durability:** service documentation does not reveal representative customer ROI, willingness to pay, recurrence or sustainable seller margins.
7. **Copying and transfer:** technical persistence does not settle rights, confidentiality, economic portability or whether value belongs to an actor, relationship, institution or reusable training asset.

These are investigated limits, not statements that no unexamined paper or private system could contain relevant evidence. Private implementations were outside authorization. The evidence may change rapidly; dated sources and versions matter particularly for service availability and 2026 preprints.

**Cross-program reconciliation.** R-14 determines how external state, parameter learning and forgetting support C-033. R-13 tests whether evaluation and surrounding controls actually detect and contain relevant errors. R-07 separates capability from legitimate, meaningful authority. R-15 defines the assets and rights involved in learning from work. R-17 compares a persistent actor with a human–AI pair and a firm-owned system. R-08's human apprenticeship evidence supplies questions about transfer and feedback, not a direct causal estimate for machine learning. R-05/R-11/R-12 supply the value, accounting and distribution boundaries.

**Author-only choices.** Luke must decide whether “professional development” is a deliberately limited analogy or a proposed institutional category; how much of an actor's identity may change while retaining its résumé; which evidence should justify expanded authority; and which parties' interests govern conflicting objectives. This review recommends explicit conditions but does not choose those substantive or normative positions.

The safe synthesis is that machine development is already technically real in bounded forms, while institutional development of enduring professional actors remains an empirical program. A wind tunnel can be valuable before that stronger future exists: it can reveal hazards, improve a model or improve its surrounding institution. The book should say which of those occurred.

## 10. Recoverable bibliography and source-access appendix

### 10.1 Method, access and version discipline

All external access occurred on **4 October 2026**, using public research articles, author manuscripts, conference proceedings and official documentation. No paid API calls, accounts, model experiments, private implementations, third-party contacts or paywall bypass were used. The review is a purposive analytical literature review, not a registered systematic review or meta-analysis. Searches were organized around C-035's causal steps and sought contrary findings as well as successful demonstrations.

Substantive methods, results and limitations were read through accessible HTML or extracted PDF text at the locators below. PDF page numbers mean printed paper pages unless specified otherwise; where a source has no stable pagination, section and table names are the recovery locator. Access to a full text does not imply every appendix was exhaustively audited, that code was run, or that reported experiments were independently reproduced. Author claims are reported as such. Provider documentation establishes what the provider documents, not externally verified performance.

Version checks changed the review. The expanded DeepSeek report replaces the original headline-only treatment; final SWE-RL PDF access revealed substantial inference-time selection behind its reported score; the updated OpenClaw-RL study supersedes the smaller first-version personalization demonstration. For Wen, the ICLR-hosted PDF led to a browser-verification page, so the inspected evidence is the explicit October 2025 arXiv revision, not a claimed reading of the final proceedings text. AgentGym-RL's abstract and project page were accessible, but its PDF/HTML fetches failed; it is an investigated lead, not load-bearing evidence. Nature's Feng article page failed to open, but the published article was recoverable from a public conference-hosted copy.

The literature is selected toward tasks with observable rewards and affordable repeatable environments. Several studies are written by developers of the methods, model providers or training infrastructure. Independent baselines help isolate experimental differences but do not make developer-run studies independent field replications. The review therefore gives greater weight to explicit methods, resource accounting, negative conditions and inspectable comparisons than to claims of generality, novelty or “real-world” applicability in titles.

### 10.2 Source register

**R16-S01 — Ouyang, Long, et al. (2022). _Training language models to follow instructions with human feedback._** [Inspected arXiv v1, 4 March 2022](https://arxiv.org/html/2203.02155v1). Methods §§3.1–3.6, results §4, limitations §5.3 and Appendix E.6 inspected. OpenAI technical research; not a longitudinal deployment study. The March manuscript is the stated evidence version, not an assertion that final proceedings pagination was read.

**R16-S02 — Rafailov, Rafael, et al. (2023). _Direct Preference Optimization: Your Language Model is Secretly a Reward Model._** [arXiv v3](https://arxiv.org/html/2305.18290v3). Derivation §§3–5, experiments §§6.1–6.4 and evaluation design inspected. Primary optimization research with controlled and preference-labeled tasks; evaluator dependence is material.

**R16-S03 — DeepSeek-AI et al. (2025/2026). _DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning._** [Expanded arXiv v2, 4 January 2026](https://arxiv.org/html/2501.12948v2); [journal DOI](https://doi.org/10.1038/s41586-025-09422-z), _Nature_ 645, 633–638 (2025). §§2–6 and Supplements B.3–B.5, D inspected. Developer-run report; stage accounting and assumptions must accompany cost claims. Original v1 checked separately.

**R16-S04 — Yue, Yang, et al. (2025). _Does Reinforcement Learning Really Incentivize Reasoning Capacity in LLMs Beyond the Base Model?_** [arXiv v5, 24 November 2025](https://arxiv.org/html/2504.13837v5). §§2–4 and evaluation appendices inspected; record identifies NeurIPS 2025. Comparative benchmark study; finite sampling and verifier quality limit universal capability claims.

**R16-S05 — Liu, Mingjie, et al. (2025). _ProRL: Prolonged Reinforcement Learning Expands Reasoning Boundaries in Large Language Models._** [NeurIPS 2025 final PDF](https://papers.nips.cc/paper_files/paper/2025/file/1a22b912945fb7c0bdd079e792b31b6f-Paper-Conference.pdf). Main methods/results §§2–4, resource description §3.2, Appendix B limitations and training appendix inspected. NVIDIA-led model-development research. Its validation and initialization differ from S04.

**R16-S06 — Wen, Xumeng, et al. (2025). _Reinforcement Learning with Verifiable Rewards Implicitly Incentivizes Correct Reasoning in Base LLMs._** [arXiv v2, 2 October 2025](https://arxiv.org/html/2506.14245v2). §§3–6, limitations and Appendix A.3 inspected. Microsoft Research-led study. ICLR 2026 listing recovered, but hosted proceedings PDF inaccessible; reasoning-judge accuracy remains a stated limitation.

**R16-S07 — Xi, Zhiheng, et al. (2025). _AgentGym: Evaluating and Training Large Language Model-based Agents across Diverse Environments._** [ACL record](https://aclanthology.org/2025.acl-long.1355/); [final PDF](https://aclanthology.org/2025.acl-long.1355.pdf), pp. 27914–27961. §§3–6, Tables 2–4, Appendix E and limitations inspected. Distinguish platform scope, evaluation subsets and the particular training comparison.

**R16-S08 — Wei, Yuxiang, et al. (2025). _SWE-RL: Advancing LLM Reasoning via Reinforcement Learning on Open Software Evolution._** [arXiv v2 PDF, 1 December 2025](https://arxiv.org/pdf/2502.18449v2). §§2–3, Table 1–2, §5 limitations and Appendix A inspected. Final HTML extraction omitted substantial content; PDF supplied the evaluation and resource details. Meta-associated developer study using public software history.

**R16-S09 — Xu, Binfeng, et al. (2026). _Polar: Agentic RL on Any Harness at Scale._** [arXiv v1, 22 May 2026](https://arxiv.org/html/2605.24220v1). §§3–4, Table 1 and Appendix A.2 inspected. Public infrastructure preprint; experimental reports, not independently reproduced production outcomes. [Author/version record](https://arxiv.org/abs/2605.24220).

**R16-S10 — OpenAI et al. (2019). _Solving Rubik's Cube with a Robot Hand._** [arXiv v1](https://arxiv.org/html/1910.07113v1). §§5–8, Table 6 and Appendix C.3 inspected. Developer-run physical transfer experiment. Sensor condition, fixed sequence and small real-trial denominator are essential.

**R16-S11 — Kumar, Ashish, Zipeng Fu, Deepak Pathak and Jitendra Malik (2021). _RMA: Rapid Motor Adaptation for Legged Robots._** [arXiv v1](https://arxiv.org/html/2107.04034v1). §§III–V, Table II and deployment/trial descriptions inspected. Robotics experiment with simulation and physical evaluation; deployment-time adaptation is not new gradient training.

**R16-S12 — Koren, Mark, Anthony Corso and Mykel J. Kochenderfer (2020). _The Adaptive Stress Testing Formulation._** [arXiv v1](https://arxiv.org/html/2004.04293v1). §§II–III and stated simulator/local-convergence limits inspected. Method/formulation paper; not an occupational learning trial.

**R16-S13 — Feng, Shuo, et al. (2023). _Dense reinforcement learning for safety validation of autonomous vehicles._** _Nature_ 615, 620–627. [DOI](https://doi.org/10.1038/s41586-023-05732-2); [accessible published-article PDF](https://agents4ad.github.io/assets/cvpr2024/papers/5.pdf). Main article, Table 1 and Methods inspected, including the explicit future-training qualification. Simulation and augmented-reality test-track validation; no new vehicle-training result inferred.

**R16-S14 — Gao, Leo, John Schulman and Jacob Hilton (2023). _Scaling Laws for Reward Model Overoptimization._** [ICML/PMLR record](https://proceedings.mlr.press/v202/gao23h.html); [final PDF](https://proceedings.mlr.press/v202/gao23h/gao23h.pdf), PMLR 202, 10835–10866. §§2–4.5 inspected, after initial arXiv reading. Synthetic gold-model design separates measured proxy failure from unmeasured human-intent mismatch.

**R16-S15 — Qi, Xiangyu, et al. (2023). _Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!_** [arXiv v1, 5 October 2023](https://arxiv.org/html/2310.03693v1). §4, Table 3, evaluation setup and Appendices A–B/G inspected. Historical model snapshots and a policy-derived judge benchmark; not a test of current services.

**R16-S16 — Wallace, Eric, et al. (2024). _The Instruction Hierarchy: Training LLMs to Prioritize Privileged Instructions._** [arXiv v1, 19 April 2024](https://arxiv.org/html/2404.13208v1). §§3–4 and evaluation appendix inspected. OpenAI developer experiment; attacks and benign over-refusal both measured.

**R16-S17 — Cobbe, Karl, Chris Hesse, Jacob Hilton and John Schulman (2020). _Leveraging Procedural Generation to Benchmark Reinforcement Learning._** [ICML/PMLR record](https://proceedings.mlr.press/v119/cobbe20a.html); [final PDF](https://proceedings.mlr.press/v119/cobbe20a/cobbe20a.pdf), PMLR 119, 2048–2056. §§2–4 inspected. Procedural-game experiments; analogy to workplace curriculum is explicitly an inference.

**R16-S18 — OpenAI. _Reinforcement fine-tuning._** [Official guide, accessed 4 October 2026](https://developers.openai.com/api/docs/guides/reinforcement-fine-tuning). Overview, workflow, supported-model entry and winding-down notice inspected. Dynamic documentation, not a publication-dated research result or verified account access.

**R16-S19 — OpenAI. _Billing guide for the Reinforcement Fine Tuning API._** [Official billing guide, accessed 4 October 2026](https://help.openai.com/en/articles/11323177-billing-guide-for-the-reinforcement-fine-tuning-api). Pricing, billable work and time/cost factors inspected. Date of access controls the tariff observation; no purchase or job ran.

**R16-S20 — OpenAI. _Deprecations._** [Official schedule, accessed 4 October 2026](https://developers.openai.com/api/docs/deprecations). “Update to OpenAI's self-serve fine-tuning” and legacy snapshot tables inspected. Future dates are announced shutdowns, not observed completed events. Generic platform timing and particular model lifetimes are distinct.

**R16-S21 — Thinking Machines Lab. _Reinforcement Learning_, Tinker documentation.** [Official workflow](https://tinker-docs.thinkingmachines.ai/cookbook/rl/), accessed 4 October 2026. Environment interfaces, rollout structure and training-loop description inspected. Documents customer-supplied feedback and infrastructure; it is not outcome evidence.

**R16-S22 — Thinking Machines Lab. _Models & Pricing_, Tinker documentation.** [Official tariff and terms](https://tinker-docs.thinkingmachines.ai/tinker/models/models_and_pricing/), accessed 4 October 2026. Pricing units, storage, training definitions and inference-beta warning inspected. Dynamic supplier information, not a fixed future tariff or total development cost.

**R16-S23 — Wang, Yinjie, Xuyang Chen, Xiaolong Jin, Mengdi Wang and Ling Yang (2026). _OpenClaw-RL: Train Any Agent Simply by Talking._** [arXiv v2, 11 May 2026](https://arxiv.org/html/2603.10165v2). §§2–4, Table 3, Appendix A.1–A.3 inspected. v1 checked but superseded here. Online-learning preprint with simulated personalization and bounded general-agent experiments; not a longitudinal professional field study.
