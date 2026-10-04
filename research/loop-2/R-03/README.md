# R-03 — Economic definitions and trade reasoning

**Claims:** C-004 and C-046, with definitional dependencies to C-001–C-009, C-010–C-014, C-024–C-025 and C-033–C-041  
**Research date:** 4 October 2026  
**Status:** Analytical literature review accepted after independent quality review. No manuscript revision or normative thesis adoption; remote durability verified separately after publication.

## Findings and scope

The production-system argument can be made economically precise without requiring either a permanent human monopoly or a newly discovered primitive factor of production. Its promising object is the **design and adaptation of a productive system**, including information, tasks, software, people and authority. That object can affect a production function, but it is not ordinarily identical to one. The distinction matters because more input, a better choice among existing techniques, improved execution, new technical possibilities and a different output are different explanations of an observed gain.

C-004 accurately records the author's operational definition. The problem is S-04's assertion that this is simply what economists mean by a production function. Formal production theory generally represents feasible input–output combinations and their frontier; an actual workflow is an implementation that may or may not attain that frontier. Organization can be modeled explicitly rather than hidden in a residual. Indeed, the organizational-economics literature already supplies several ways to do so. “Writable” remains a possible, expressly identified operational metaphor; whether to retain it is Luke's choice.

C-046 accurately records an inconsistency in the predecessor essay. Its closing requirement that both parties specialize in absolute advantage is contradicted by comparative-advantage reasoning. Its inference from a widening absolute productivity gap to the disappearance of the other party's comparative advantage is also invalid without relative-cost information. [R-18's Portugal review](../R-18/portugal.md#ricardos-actual-demonstration) establishes these corrections and their historical-source basis. This review does not repeat that historical capsule. It asks the further question that the analogy leaves open: under which capacity, price, ownership and market conditions does relative-cost reasoning actually allocate work between a human and provisionable machine services?

The answer is conditional. Finite capacity creates opportunity costs even for the absolutely more capable producer. Cheaply expandable machine supply changes those opportunity costs. Comparative advantage is not a promise of employment at an unchanged wage, and greater total productive capacity does not allocate the proceeds. None of those points chooses a normative place for humans.

The review preserves the current, revisable [D-001 apprenticeship position](../../../decisions/resolved/D-001-middle-seat-apprenticeship.md) and [D-002 conditional ownership/labor position](../../../decisions/resolved/D-002-ownership-dominance.md). The permanent-monopoly language in S-01 remains historical evidence; S-10 §4 explicitly disavows making the book depend on it. Research on the actual capability boundary belongs to R-06/R-14. The definitions below do not declare that boundary either permanent or nonexistent.

## 1. Exact authored propositions and the question each raises

In [S-04, “What a production function really is”](../../../source/drafts/04-the-production-function-is-becoming-writable-v3.md#what-a-production-function-really-is), the relevant sentences are:

> “Economists call the arrangement a production function.”
>
> “A production function is simply the way people, tools, information, rules, and machinery are combined to produce an outcome.”
>
> “Every one of those outcomes has a production function behind it: an arrangement that determines who does what, in what order, using which information, with which tools, and under which rules.”

These are not merely claims that organization matters. They assert a definitional identity. The formal mapping must therefore preserve both the arrangement and the input–output relation instead of silently replacing one with the other.

[S-10 §2](../../../source/synthesis/2026-09-11-current-author-synthesis.md#2-the-second-transformation-software-is-becoming-plastic) makes the stronger combined formulation:

> “AI introduces a new factor of production at the same moment the production function becomes writable.”

“New factor” can mean a newly purchasable service, a useful new variable in a model, a new capital good, or a basic category irreducible to labor and produced inputs. Those are not equivalent claims. “Writable” can mean cheaper implementation, newly feasible designs, faster experimentation, or freedom to determine institutions. Only the first three are technological propositions; the last additionally involves authority, law and other participants.

In [S-01](../../../source/essays/01-we-were-portugal-all-along.md), “Most readings of this analogy get it wrong” says that “England's comparative advantage weakens as the productivity gap widens.” The closing prescription says mutual gain occurs “only when both parties specialize into what they have absolute advantage in.” The opening instead explicitly distinguishes comparative from absolute advantage. These quantifiers and their conflict must remain visible. Replacing “only when” with “often when” would be a substantive correction, not a faithful quotation.

The adjacent S-01 assertion that machine production of tacit knowledge is “structurally zero” is a separate capability premise. If true for a specified necessary input, it would change the feasible set. It is neither the definition nor a consequence of comparative advantage. A capability premise cannot acquire proof by being called a factor endowment.

## 2. From workflow to production possibilities

### 2.1 The conventional distinction

In standard producer theory, a **production plan** is a vector of inputs used and outputs produced; the **production set** contains feasible plans. For one output, a **production function** gives the maximum attainable output for each input bundle, where that maximum exists. With suitable free disposal, the set also contains points below the frontier. Profit maximization then selects a plan using prices; the frontier itself does not specify that selection. Stein's graduate-course exposition makes these objects and the price-taking, given-technology assumptions explicit. These are definitions within a model, not empirical assertions that every organization already operates efficiently. [R03-S01, slides 34–45, 83–87]

That textbook usage is not the only usage in economics. Empirical researchers also estimate average production relations, or specify stochastic frontiers with separate noise and inefficiency components. Aigner, Lovell and Schmidt explicitly distinguish these objects and model a two-sided disturbance alongside a one-sided inefficiency term. [R03-S09, §§1–3] An estimated relation need not be an error-free engineering maximum. Nor can an analyst identify organizational inefficiency simply by labeling an unexplained residual that way. The correction to S-04 is thus not “every economist always means a deterministic frontier”; it is that a workflow architecture, a feasible-set representation, a realized outcome and an estimated production relation must be distinguished.

Consequently, a workflow diagram leaves many things unspecified that a production model needs: resource quantities, output units, failure rates, constraints, alternatives and the horizon over which inputs can adjust. Conversely, the same input–output frontier can be implemented by different diagrams. A committee and a single delegated decision-maker might achieve the same measured throughput and accuracy while differing materially in accountability. A throughput function alone cannot reconstruct those differences.

It would nevertheless be wrong to claim that formal economics cannot represent sequencing, information or authority. The distinction is between an object and a representation of what it can accomplish, not between economics and everything organizational. A richer model may make design choices explicit, include information-processing constraints or treat institutional rules as restrictions on feasible actions.

### 2.2 A mapping for this book, not a claimed quotation from a source

**Review's analytical construction.** Fix an outcome specification, including a quality standard and delivery horizon. Let x denote quantities of resources; a denote a workflow architecture; T denote technical knowledge and available methods; and g denote the specified institutional environment. Write Y(a; T, g) for feasible input–output plans under that architecture. For a single comparable output, define:

f_a(x; T, g) = sup{q : producing q with resource bundle x is feasible under a, T and g}.

An envelope over admissible architectures is:

F(x; T, g) = sup over a in A(T, g) of f_a(x; T, g).

This is a deliberately schematic construction, not an estimated function. A supremum need not be attained. Multiple outputs, stochastic reliability and indivisibilities may require retaining the set rather than reducing it to a smooth scalar function. Architecture-changing resources must be included in x or explicitly charged elsewhere; otherwise the comparison grants redesign a free input.

The construction exposes three distinctions useful to C-004:

1. **A particular architecture is not the envelope.** Editing a process can switch between existing members of A without creating a new technological possibility.
2. **A firm's practical option set is not necessarily the world's.** Learning to implement an existing technique can expand what this firm can do even if someone else already knew how. Whether that is called adoption, organizational innovation or technical change depends on the stated reference frontier.
3. **An observed outcome is not the frontier.** Failures of execution, downtime, missing context or poor coordination can leave actual output below f_a. Reducing those losses differs from raising the best attainable output conditional on all relevant inputs.

An organization can also choose an architecture for reasons other than maximum current throughput. Resilience, confidentiality, due process, worker development and legitimate decision-making may be constraints or separately valued outcomes. Representing them explicitly does not establish their ethical weights. Omitting them and calling the resulting maximum “efficient” does not make them irrelevant.

### 2.3 Five changes that the metaphor should not collapse

The following classification is this review's application to the admitted argument:

| Change | What changes in the comparison? | What would establish it? |
|---|---|---|
| More or better measured inputs | Resource quantity or quality x | Compare output while accounting for additional service input, human time and capital services |
| Better execution | Distance from the relevant frontier | Hold the method and resource definition sufficiently stable; measure waste, failure and utilization |
| Different existing technique | Chosen architecture a | Compare feasible alternatives with transition and coordination costs included |
| Expanded technical possibilities | T or the admissible architecture set | Establish a capability not previously feasible under the declared reference conditions |
| Different output or objective | The definition or valuation of q | Measure quality, timeliness, risk and beneficiaries rather than counting unlike artifacts as identical units |

Several can happen together. AI-assisted redesign could require new software capital, improve execution and change the attainable output mix. The classification is not an instruction to force every gain into exactly one box. It is a protection against inferring all five from faster completion of one stage.

Solow's original growth-accounting paper is instructive here. It uses technical change broadly for shifts in an aggregate production relation, not solely new inventions. It also states the marginal-product-payment assumption and describes serious capital-service and utilization measurement problems in its U.S. 1909–1949 application. The paper does not identify a single causal mechanism behind the residual. [R03-S02, pp. 312–314] For this book, calling an unexplained improvement “AI technology” or “organizational capital” would likewise name a candidate explanation rather than identify it. A labor-productivity increase, a cost saving and a total-factor-productivity increase are not interchangeable measures.

**Review's numerical illustration.** Suppose every completed case needs one model-produced analysis and one review. The model stage can supply 100 analyses per day; review can complete 20 cases per day. With those fixed one-for-one requirements and no other constraint, completed throughput is at most min(100, 20) = 20. Doubling model capacity does not raise it. Changing the architecture to review only a subset could raise throughput, but it also changes the assurance mechanism. Its risk and quality must be evaluated; deleting a check is not definitionally an efficiency gain. This illustration establishes a logical possibility, not the prevalence or optimal design of such workflows.

## 3. What organizational and general-purpose-technology research adds

### 3.1 Information-processing architecture can have a formal frontier

Radner models an organization as a network of limited-capacity information processors and derives trade-offs between processor numbers and decision delay. He distinguishes information-processing structure from the hierarchy of authority, explicitly limiting the analysis largely to associative operations. Communication cost and incentive problems are not jointly solved by the model. His discussion also shows that conclusions about scale depend on how delay is valued. [R03-S03, pp. 1109–1115, 1136–1139]

This is a particularly close conceptual neighbor of S-04. It demonstrates why the book need not choose between a vague metaphor and a two-input black box. A workflow can be analyzed as a design determining feasible completed work. But an efficient routing network does not establish who is entitled to decide, whether a model has relevant context, or whether the calculated answer is institutionally acceptable. Treating all three as “information processing” would remove the very distinctions that make the authored argument interesting.

There is also a measurement implication. More agents or shorter individual responses need not mean shorter end-to-end delay. The productive service may be a correct decision by a deadline, not a count of generated analyses. The correct comparator for a redesigned system includes queues, handoffs, failures, recovery and unavailable inputs, not only the component whose benchmark improved.

### 3.2 Complementarity supports coordinated design, conditionally

Milgrom and Roberts model modern manufacturing as interacting choices across production, marketing and organization. Complementarity means that adopting more of one activity raises the return to another; non-convexities can make coordinated changes profitable even where isolated changes are not. Their formal results depend on specified objective and demand conditions, and their manufacturing illustrations are not a randomized test of redesign. The paper also leaves some apparently associated choices, such as product-line breadth, outside its general complementarity result. [R03-S04, pp. 513–520, 524–526]

A material correction must travel with this source: their **1995 Reply acknowledges that Theorem 7 of the 1990 paper was incorrect as stated**. Lower costs can favor lower prices, but quality improvements can change demand elasticity and favor a higher price. Recovering the monotonic-price conclusion requires additional conditions. [R03-S05, pp. 997–999] The correction matters directly to any proposed chain from cheaper cognition to mandatory deflation. The broad usefulness of complementarity reasoning does not license citing the uncorrected theorem.

For the book, a sensible empirical question is whether model capability and workflow changes interact in producing useful outcomes. It is not enough to show that successful organizations possess both. A common source of success can produce co-adoption, and managers may select investments after observing favorable demand. Nor does complementarity imply that every component must be replaced simultaneously. Transition costs, uncertainty and reversibility can justify experiments or partial adoption. [R-04](../R-04/README.md) owns the detailed empirical complementarity/electrification treatment; this review does not duplicate its source capsules.

**Review's factorial test.** Compare four conditions where feasible: old process/old capability, old process/new capability, redesigned process/old capability, redesigned process/new capability. With outcomes Q00, Q01, Q10 and Q11 measured on the same resource, quality and time basis, a positive interaction Q11 − Q10 − Q01 + Q00 is evidence of complementarity for those interventions and that metric. A randomized design supports a causal interpretation more strongly than voluntary adoption. A positive interaction still does not establish that the full redesign pays for its development, that effects transfer to other domains, or that either worker or owner captures the gain. A negative interaction could reveal redundant improvements rather than technological failure.

### 3.3 GPT research changes the unit from one workflow to linked innovation

Bresnahan and Trajtenberg's 1992 working paper models a general-purpose technology and application sectors linked through innovation. Its core mechanism is that improvement in the general technology raises returns to downstream innovation, with feedback and coordination/appropriability problems. The authors explicitly describe their analysis as partial equilibrium; aggregate-growth implications are not generated by a fully specified whole-economy model. Their underinvestment conclusion also requires assumptions about private and social returns. The inspected version proposes empirical tests rather than estimating an AI effect. [R03-S06, §§1, 3, 6]

This helps distinguish two claims within “two revolutions at once.” Cheaper cognitive services can change current operating choices. Cheaper production-system invention can change the rate at which new choices become available. The latter is an innovation mechanism, not merely a larger quantity of the former. A model that only augments current labor efficiency may miss it; a model that simply assumes unlimited beneficial redesign has assumed its conclusion.

Calling AI a GPT therefore supplies a research framework, not a prediction of a particular growth rate, diffusion lag or division of income. The relevant tests include breadth of economically useful applications, sustained improvements and induced complementary innovation. The historical-electricity evidence and its analogy limits remain with R-18/R-04.

### 3.4 What the perspectives agree on, and where they differ

These literatures are not rival answers to exactly the same question. The frontier representation asks what could be produced under specified conditions. Information-processing models investigate one mechanism that makes those conditions binding. Complementarity models ask how coordinated choices respond to changed costs. GPT models study linked invention across suppliers and users. Task models endogenize who supplies particular services. Capability and routine perspectives ask how an organization actually discovers, learns and repeatedly implements changes; R-05's dynamic-capability comparison and R-10's knowledge/coordination analysis own those treatments.

There is genuine tension as well as compatibility. An optimizing envelope suppresses ignorance and failed search unless they are modeled. A narrative of learned routines does not by itself identify the efficient alternative or a causal effect. A supply-side design account cannot determine distribution without prices, demand and institutions. An aggregate residual can register something those mechanisms affect without distinguishing them. The book should move between these levels explicitly rather than treating “economists assumed a fixed diagram” as a description of the whole discipline.

## 4. Machine cognition, labor and forms of capital

### 4.1 A service is not necessarily a primitive factor

An input is whatever a specified production process uses. A **primary factor**, a **produced intermediate input**, a **durable asset** and the **flow of services from that asset** occupy different positions in a model. There is no need to decide that machine cognition is a new primitive category before recognizing that a firm can procure it and use it productively.

**Review's model comparison.** A downstream organization may reasonably write q = f(l, k, m; a), with human labor services l, other capital services k and purchased machine-cognition services m. An upstream provider may produce m = g(compute services, energy, software, labor, data access). The downstream equation treats m as an input without claiming it is unproduced. Consolidating the two sectors requires respecting intermediate consumption: adding the full value of m to final output again would double-count it. Conversely, collapsing m into a homogeneous k may hide task-specific substitution and bottlenecks important to the question being asked.

The useful research question is therefore whether distinguishing m improves explanation and measurement. What are its units? Which qualities are held constant? What produces its supply? Which tasks can use it? How do prices, capacity and verification requirements change? Calling m “cognition” does not make different models, contexts, latencies and reliability levels interchangeable. R-01 supplies the effective-completed-task cost analysis; R-11 supplies production-account and capital-service boundaries.

Three readings of the authored “new factor” formulation consequently have different verdicts:

- **New provisionable productive service:** conceptually coherent; the extent of economic novelty and usefulness is empirical.
- **A separately modeled input with a distinctive task-productivity schedule:** also coherent, but a modeling choice whose explanatory value needs examination.
- **An irreducible new primary factor outside existing accounts of produced inputs and capital:** not established by the fact that software performs cognitive tasks. It requires a further argument, not a more emphatic name.

This is not a denial of qualitative novelty. A produced input can radically reorganize production. The point is that novelty of capability and novelty of a foundational economic category are different propositions.

### 4.2 Stock, service, embodied capability and rights

For the book's purposes, the following operational distinctions avoid category errors:

| Term | Object to identify | What should not follow merely from the label |
|---|---|---|
| Human labor | Human time/effort services in the specified activity | That every valuable human contribution is measured by hours or routine output |
| Human capital | Productive capabilities embodied in people, developed or maintained over time | That the person is an ownable asset, or that a capability earns its full social value |
| Software capital | A durable software asset or capability producing services over time, where the stated definition applies | That every prompt, output or subscription payment is acquisition of that asset |
| Machine-cognition service | A flow of task-relevant service, possibly bought from a provider | That the user owns the model, or that all its upstream inputs are a separate final-output contribution |
| Organizational capital | A specified durable productive capability or knowledge associated with the organization or relationships | That every organizational feature is valuable, separable, saleable or legally owned by the firm |
| Authority and control rights | Permitted decisions and rights over specified actions/assets | That technical access grants legitimacy, or productive contribution assigns property rights |

These are a proposed working vocabulary, not new national-accounting rules. [R-09](../R-09/README.md) treats human-capital investment incentives; [R-11](../R-11/README.md) treats durable assets, service flows and actual accounting standards; [R-15](../R-15/README.md) treats ownership and separability. A useful economic capability can lie outside a particular statistical asset boundary. The book should not settle that accounting question by using the word “capital.”

Atkeson and Kehoe's 2005 model associates organizational capital with plant-specific productivity and age, jointly accumulating knowledge with production. They infer payments using a plant-life-cycle model calibrated to U.S. manufacturing data, including 1988 age-group moments. They distinguish plant-embodied capital from worker- or match-embodied alternatives. Payments go to plant owners by model construction; worker-received organizational returns are expressly outside their exercise. This is structural measurement, not an experiment assigning rights or directly observing organizational knowledge's market price. [R03-S08, pp. 1027–1032, 1038–1040]

The implication for “experiential machine capital” is specific. An experience-derived improvement may be a durable productive asset, an improvement in existing software, useful data, a relationship-specific complement or several of these together. That classification depends on what persists and what remains useful. A saved transcript, a learned parameter change and a capability that survives transfer are not interchangeable. R-14 tests persistence and learning; R-17 tests whether pairing history adds productive value; R-15 tests what can be controlled or transferred. Economic definitions cannot perform those tests.

### 4.3 Do not count the same productive resource twice

**Review's accounting illustration.** An employee spends ten hours making an internal tool and teaching colleagues to use it. Those hours are current labor input; the resulting durable software and learned capabilities may supply future services. Calling the ten hours “architectural capital,” “human capital” and “organizational capital” simultaneously does not create three independent resources. One must state which expenditure creates which stock, how stocks overlap, and which subsequent service flow is being measured. A joint production process can create several outputs, but assigning their value requires evidence rather than repeated labels.

Nor does the label decide capture. An employed architect can produce a valuable asset while receiving labor income; an owner can hold an unproductive asset. D-002 already preserves that distinction. A paper whose model allocates a particular rent to owners cannot independently establish an ownership-only prescription for this book.

## 5. Comparative advantage under the conditions that actually matter

### 5.1 Relative opportunity cost is the object

For two comparable outputs A and B, let a_iA and a_iB be resource requirements per unit for producer i. With linear technology and one scarce resource within each producer, the opportunity cost of A in B units is a_iA/a_iB. Absolute productivity comparisons concern a_iA versus a_jA; comparative advantage concerns the ratio across activities. Multiplying both requirements of one producer by the same positive number leaves that ratio unchanged. A widening absolute gap therefore need not change comparative rankings. This is the review's algebraic restatement, not a new historical example.

If the ratios differ, a relative exchange price between them can permit gains from reallocating production, subject to the model's resource, demand and exchange assumptions. Identical ratios eliminate this particular source of gains; other gains such as scale or variety require a different mechanism. Strict gains for both do not follow at every price, and complete specialization is not necessary in every equilibrium. Country size, demand, trade costs and increasing opportunity costs can change specialization patterns. R-18 supplies the original-text correction; no absolute-advantage condition should be reintroduced to make a reassuring human-role argument.

In a firm, however, allocation is not selected by a productivity ratio in isolation. A task's relevant incremental cost can include wages or service prices, scarce capacity, setup, verification, coordination, quality and expected harm. Technical comparative advantage helps describe the trade-off. It is not a universal instruction to assign each person the task at which they are “most better.”

### 5.2 Finite capacity versus provisionable supply

**Review's derivation; invented quantities, not observations.** Suppose the following hourly capacities refer to comparable acceptable outputs:

| Producer | Drafts per hour | Judgments per hour |
|---|---:|---:|
| Human | 10 | 5 |
| Machine service | 100 | 10 |

The machine is absolutely more productive in both activities. Producing one judgment instead of drafts costs the human 2 drafts; it costs the machine 10 drafts. The human has comparative advantage in judgments. If each has exactly one hour of capacity, a target of 100 drafts and 5 judgments is feasible by assigning machine capacity to drafting and human capacity to judgment. If the human instead drafts for a small amount of time, the machine time needed to replace the lost judgments sacrifices more drafts than the human adds. There is a real joint-resource allocation argument for the human's role without any human absolute advantage.

Now change the assumption rather than the arithmetic. Machine hours can be purchased without a binding capacity limit for $100 per hour; the human also costs $100 per hour. Machine unit costs are $1 per draft and $10 per judgment; human unit costs are $10 and $20. The target costs $150 using 1.5 machine hours, against $200 for the capacity-constrained assignment. The firm's cost-minimizing choice is different even though the technical productivity ratios have not changed.

At a hypothetical human wage of $40 per hour, human judgments cost $8 each, so they can again compete with machine judgments while human drafts remain more expensive. This does **not** determine an equilibrium wage. It proves the narrower point that preserving a comparative ranking is consistent with needing a lower wage to remain privately competitive. Quality differences, human-only authority requirements, capacity scarcity or additional human outputs could change the calculation; none may be silently assumed.

Actual AI provision is neither a fixed one-hour machine nor literally unlimited frictionless supply. Prices, latency, inference capacity, energy, integration, budgets and scarce human attention may bind at different horizons. The relevant opportunity costs depend on which resource is scarce. The analogy must state its case rather than use finite national labor endowments in one paragraph and indefinitely replicable machine capacity in the next.

### 5.3 Factor mobility and the choice of economic unit

R-18's factor-mobility qualification is essential here. A two-country model with factors unable to relocate internationally differs from a firm able to buy the same service provider's output for every department. It also differs from an individual choosing whether to perform a task personally, hire someone or consume leisure. The alternatives forgone are different in each case.

An individual can profitably delegate something they perform absolutely better if their time has a more valuable alternative use. But an unemployed worker need not have an alternative customer, and a firm need not buy the worker's service merely because another activity would be an even worse use of that worker. “Society could make productive use of this person” and “this employer will demand their labor at this wage” require different counterfactuals.

Similarly, humans are not a single supplier owning the whole human endowment and bargaining as one party with a machine-owned country. There are workers, consumers, firms and owners, sometimes overlapping. The fact that a task still requires some humans says nothing by itself about the supply of those humans relative to demand, their substitutability with one another, or the rights that determine bargaining. A monopoly of the species over a task would not automatically give each worker monopoly power.

S-01's contrast between “a factor endowment” and “a comparative advantage” also needs care. An endowment is an available stock or supply of a productive resource; comparative advantage describes relative opportunity cost across activities. They are different types of object, not mutually exclusive explanations. An endowment of situated knowledge can affect feasible production and thereby relative costs. Describing possession of that knowledge is not yet a comparison of productivity in producing a specified output. Nor does nonreplicability establish non-substitutability: a different input or process could sometimes achieve the same outcome without reproducing that knowledge. Whether it can do so is an empirical question, not a terminological decision.

### 5.4 A task-allocation model is closer than a literal country analogy

Acemoglu and Autor's published 2011 framework distinguishes tasks from skills and makes task assignment depend on productivity and factor prices. Skill groups and machines supply task services under resource constraints and a specified comparative-advantage ordering. Technical improvement can reduce particular groups' wages through reassignment. This conditional model is motivated by pre-generative-AI evidence; it does not establish an immutable occupational ordering. The illustrative wage regressions are expressly preliminary, not a decisive causal test. [R03-S07, §§3–4, 5.2]

For the book, tasks are neither immutable jobs nor interchangeable tokens. Some output stages can substitute between human and machine services; other stages may require several inputs together. Changing a process can delete a task, create one, bundle tasks differently or alter the information needed to perform them. A theory that endogenizes assignment is useful, but a fixed menu of tasks can still miss those design changes. Endogenous assignment and endogenous task creation are distinct extensions; invoking one does not establish the other.

### 5.5 Why gains do not guarantee wages or welfare for everyone

The logical chain should be disaggregated:

1. A new technique may expand feasible production.
2. A chosen allocation may create higher output or lower costs.
3. Product prices, factor demands, ownership income and adjustment costs may change.
4. Particular people may gain or lose after those changes.
5. A welfare judgment additionally requires a criterion and a treatment of distribution, nonmarket effects and risk.

The first step does not prove the fifth. Even a model in which aggregate gains can fund compensation does not show that compensation occurs. Even if consumers benefit from a lower price, the same people may lose labor income. Conversely, a falling labor share need not imply falling real wages in every model. R-12 evaluates these distributional mechanisms; R-05 evaluates capture and R-15 rights. R-03's role is to prevent a theorem about relative costs from being mistaken for a theorem about adequate pay, human dignity or preferred institutions.

The human-only-input premise does not repair that inference. A necessary input can yield low compensation if demand is limited or many suppliers compete; a bottleneck can generate rents without assigning them to the person whose work created it. Technical necessity, economic scarcity, bargaining leverage and legitimate authority should therefore remain four separate predicates.

## 6. Claim-level evidence ledger

The judgments below concern the exact proposition in the middle column. C-004 and C-046 remain stable historical ledger IDs; this review does not overwrite them. A ledger statement accurately reporting an authored claim can be supported as a report while its embedded economic claim is false.

| Review ID / claim | Proposition tested | Judgment | Basis and required boundary |
|---|---|---|---|
| R03-01 / C-004 | The author uses production function to include people, information, rules and authority arranged into work | Supported within stated scope | Exact S-04/S-10 language, §1; a fact about authored usage |
| R03-02 / C-004 | An implemented arrangement is simply the conventional formal production function | Revised/qualified; the unqualified identity is contradicted | §2; R03-S01/S03/S09; distinguish architecture, feasible set, frontier, realized plan and empirical relation |
| R03-03 / C-004/C-005 | Reorganization can change productive possibilities or realized efficiency | Supported within stated theoretical scope | §§2–3; R03-S03/S04/S06; no universal magnitude or optimal design established |
| R03-04 / C-004/C-006 | Auxiliary inference: “writable” means all constraints can be freely redesigned | Contradicted as an unrestricted inference; not attributed as S-04's unqualified position | §§2, 4; S-04 itself explicitly includes resource and implementation caveats |
| R03-05 / C-001/C-004 | Machine cognition can be represented as a distinct productive input/service | Supported within stated modeling scope | §4.1; representation does not prove current efficacy, fungibility or unlimited supply |
| R03-06 / C-004 | Candidate interpretation of the ambiguous “new factor” phrase: cognitive task performance establishes a new irreducible primary factor | Unresolved as an intended definition; not established by the offered premise | §4; input/service, produced asset and primitive category are distinct |
| R03-07 / C-024/C-034 | Auxiliary equivalence test: durable software, learned capability, current services and rights are interchangeable categories | Contradicted as an equivalence | §4; R03-S08 and analytical cross-references to R-11/R-14/R-15; not an assertion that the author endorsed every equivalence |
| R03-08 / C-046 | The predecessor's opening and closing rules differ | Supported within stated scope | Exact S-01 text, §1; historical ledger diagnosis retained |
| R03-09 / C-046 | Mutual gains require both producers to specialize in absolute advantage | Contradicted in stated scope | §5.1–5.2; R-18's primary-source audit; finite-capacity counterexample |
| R03-10 / C-046 | A widening absolute productivity gap necessarily weakens comparative advantage | Contradicted in stated scope | §5.1; unchanged-ratio derivation |
| R03-11 / C-046 | Auxiliary inference test: comparative advantage guarantees a human role at prevailing wages when machine supply expands | Contradicted as a general inference | §5.2–5.5; explicit supply/cost counterexample and R03-S07 |
| R03-12 / C-046/C-010 | Auxiliary deduction test: a human-only necessary input follows from trade theory | Contradicted as a deduction; empirical capability boundary outside this review | §§1, 5; must establish input/capability premise separately under R-06/R-14 |
| R03-13 / C-004/C-045 | Auxiliary deduction test: complementary technical improvement necessarily reduces output prices | Contradicted without further demand conditions | §3.2; verified R03-S05 correction; downstream constraint for R-12 |
| R03-14 / C-004/C-039 | Auxiliary deduction test: defining a productive capability as capital determines its owner or compensation | Contradicted as a deduction | §4.2–4.3; model-specific allocation in R03-S08; R-05/R-15 |
| R03-15 / C-046 and S-01 factor terminology | S-01 contrasts territory knowledge as a factor endowment rather than a comparative advantage | Revised/qualified as a categorical contrast | §5.3; resource availability and relative output costs are distinct but connected, not mutually exclusive concepts |
| R03-16 / C-046 context | Auxiliary inference test: possession alone establishes absolute advantage | Contradicted as a deduction | §5.3; endowment, feasible output and unit input requirements need separate specification |

## 7. Boundaries, unresolved choices and useful next measurements

### Author terminology choices, not forced normative decisions

1. **Name the operational object.** Retain “production function” with an explicit operational/metaphorical definition, or use “production architecture/system” while reserving production function for the formal relation. Research establishes the distinction; it does not choose the book's title or voice.
2. **Declare the intended strength of “new factor.”** Does the phrase mean a newly provisionable service, a useful separate modeled input, or a claim about irreducible economic categories? The first two require far less than the third. No author response is needed to correct the absolute-advantage error.
3. **Specify the reference frontier.** Is “newly possible” new to the individual, firm, sector or world? Is a useful prototype enough, or must secure, maintained, authorized completed work be attainable? R-02 supplies evidence but cannot select an unspoken comparator.
4. **Specify what counts as an outcome.** A document, a valid decision, a welfare improvement and a legally authoritative action are different output concepts. “Realized value” needs a beneficiary, horizon and counterfactual.
5. **Keep human authority explicit.** If human responsibility is an institutional commitment even when machine capability improves, state it as such. Do not convert that choice into an unsupported productivity monopoly, and do not treat a cost-minimizing model as determining legitimate authority.

### Empirical gaps that definitions cannot close

The review does not estimate how much AI has expanded any production frontier, how persistent a redesigned advantage is, or what fraction of institutional knowledge can transfer to machines. It does not identify the economic value of a saved interaction history, classify a particular asset under law, or forecast wages. Those questions are bounded dependencies, not unfinished searches that could be settled with another generic definition.

For an actual workflow test, record the old and new output specification; task dependencies; human and machine resource use; development and maintenance effort; context and access; quality/error distributions; queues; recovery and escalation; decision rights; and the alternative forgone. Distinguish private cost from social cost, and temporary learning/adoption costs from recurrent operation. Repeat evaluation after novelty and training effects change. A before/after success story without a comparator cannot distinguish better tools, more resources, selected users and redesign.

For the human–machine assignment claim, measure relative effective costs across at least two activities rather than reporting a single benchmark gap. State whether capacity is fixed, purchasable or jointly constrained; which prices adjust; and whether changed task demand or new work is included. A task performed better by a model establishes neither economy-wide substitution nor human comparative advantage somewhere else. Each is a further claim with a further denominator.

### Synthesis constraints

- R-01/R-02 should distinguish input capability and price from completed-work productivity, adoption and full lifecycle cost.
- R-04 should distinguish architecture choice, frontier change and implementation, retaining the 1995 Milgrom–Roberts correction and its own empirical evidence.
- R-05/R-09/R-12/R-15 should not infer compensation from contribution, national gains from firm success, or individual bargaining power from a species-level capability claim.
- R-11 should retain the stock/service/intermediate-input distinctions when evaluating production accounts.
- R-14/R-16/R-17 should identify the durable change and counterfactual productive benefit before treating experience or pairing as capital.

The program's stopping condition is a recovered conceptual mapping, corrected relative-cost reasoning, substantive comparison of relevant mechanisms, claim-level dispositions and explicit residual empirical/author questions. It is not a complete theory of the firm or an empirical resolution of every dependent program.

## 8. Recoverable bibliography, source access and method

### Method and source ownership

This is a focused analytical review, not a preregistered systematic review. Searches covered production sets/frontiers, technical change and measurement, information-processing organization, manufacturing complementarities and corrections, GPT innovation, task allocation and organization capital. Selection targeted the exact definitional claims and counterarguments, rather than maximizing source counts. Primary research texts were read substantively; a clearly labeled graduate teaching source supplies the conventional formal definitions. Abstracts and search snippets were leads, not substitutes for the inspected text.

All access below occurred on 4 October 2026. Public author, university and institutional sources were used. No account, paid access, private origin, contact or paywall bypass was used. Direct public PDF retrieval and local extraction supplemented web extraction. Scanned Milgrom–Roberts texts required OCR; key definition/correction pages were checked against the page images. This review does not reproduce external source tables or extended quotations. Numerical examples and the workflow-envelope/factorial constructions are the review's derivations, not empirical findings or reconstructions of source datasets.

Nine dedicated sources are listed below. Detailed Ricardo/Methuen/history, human-capital incentives, knowledge hierarchies, dynamic capabilities, accounting and property-rights capsules remain with R-18, R-09, R-10, R-05, R-11 and R-15. R-04 owns the fuller Bresnahan–Brynjolfsson–Hitt (2002) empirical treatment; that article was inspected for this review's orientation but is not summarized again. Repeated references to an item do not count as independent evidence. Source-derived exposition is bounded across body, ledger and appendix; the review's own applications are distinguished from source findings.

### R03-S01 — Conventional producer theory

Luke Stein. *Economics 202N: Core Economics 1 and 2*. Stanford University course slides, 11 April 2012. [Author-hosted PDF](https://lukestein.github.io/files/stein-microphd_slides.pdf). Inspected slides 34–45 and 83–87; neighboring assumptions and rationalizability material consulted. Teaching exposition, not an empirical study or a claim that the entire 539-slide file was read. SHA-256: `ab1c660d224ee6b5036ee8f7770fe93fe1673af6e4934d78d6a0687497c5024e`.

### R03-S02 — Technical change and aggregate measurement

Robert M. Solow. 1957. “Technical Change and the Aggregate Production Function.” *Review of Economics and Statistics* 39(3):312–320. DOI [10.2307/1926047](https://doi.org/10.2307/1926047). [Public article scan](https://economicstrategy.org/wp-content/uploads/2013/10/Solow1957.pdf). Inspected pp. 312–314 and concluding measurement/extrapolation discussion, pp. 319–320. Primary formal/accounting study; historical series not replicated. SHA-256: `19da7a61e0b1cf7c52e31d580bfa7812b8e3b75b7467263f0efa52f47c1ff7a0`.

### R03-S03 — Information-processing architecture

Roy Radner. 1993. “The Organization of Decentralized Information Processing.” *Econometrica* 61(5):1109–1146. DOI [10.2307/2951495](https://doi.org/10.2307/2951495). [Author-hosted published article](https://pages.stern.nyu.edu/~rradner/publishedpapers/83OrganizationDecentralizedInfo.pdf). Inspected introduction and selected §§6–8 passages, especially pp. 1136–1139. Appendix proofs not independently replicated. Author's AT&T affiliation/disclaimer is explicit. SHA-256: `246a25f143bb2595fc18097e25711a776f6c68efddf17d81e4b82a44d3dc4d26`.

### R03-S04 — Complementary organizational choices

Paul Milgrom and John Roberts. 1990. “The Economics of Modern Manufacturing: Technology, Strategy, and Organization.” *American Economic Review* 80(3):511–528. [Author-hosted published scan](https://web.stanford.edu/~milgrom/publishedarticles/The%20Economics%20of%20Modern%20Manufacturing.pdf). Inspected pp. 511–520 and 524–527, with theorem setup consulted; not a proof replication. NSF/Stanford support is disclosed. Must be read with S05. SHA-256: `08341f4935dd9841509eb6c2f4c88306e2ce6005b4af94b8e919115d9124cef9`.

### R03-S05 — The necessary correction

Paul Milgrom and John Roberts. 1995. “The Economics of Modern Manufacturing: Reply.” *American Economic Review* 85(4):997–999. [Author-hosted published scan](https://web.stanford.edu/~milgrom/publishedarticles/The%20Economics%20of%20Modern%20Manufacturing,%20Reply.pdf). All three pages inspected. The linked Bushnell–Shepard and Topkis comments are identified in its references but were not independently audited here. SHA-256: `8530152c468eb5c33cd788959808a48c50cb74bbdb5f8584a7f35f049080a32a`.

### R03-S06 — General-purpose technology and linked invention

Timothy F. Bresnahan and Manuel Trajtenberg. 1992. “General Purpose Technologies: ‘Engines of Growth?’” NBER Working Paper 4148, August. DOI [10.3386/w4148](https://doi.org/10.3386/w4148). [Institutional PDF](https://www.nber.org/system/files/working_papers/w4148/w4148.pdf). Inspected introduction, selected §§3.1–3.4 passages and conclusion, manuscript pp. 1–4, 9–19, 32–33. Public download succeeded after web retrieval failed. The [1995 journal version](https://doi.org/10.1016/0304-4076(94)01598-T) was bibliographically identified, not substituted for this text. SHA-256: `25b0439e55d717d1472901785e621266864e89022480c34673a0140fb3e53292`.

### R03-S07 — Skills, tasks and endogenous assignment

Daron Acemoglu and David Autor. 2011. “Skills, Tasks and Technologies: Implications for Employment and Earnings.” *Handbook of Labor Economics*, vol. 4B, pp. 1043–1171. DOI [10.1016/S0169-7218(11)02410-5](https://doi.org/10.1016/S0169-7218(11)02410-5). [Author-institution published PDF](https://economics.mit.edu/sites/default/files/publications/Skills,%20Tasks%20and%20Technologies%20-%20Implications%20for%20.pdf). Selected §§3–4 model passages, §5.2 and conclusion inspected, especially pp. 1119–1122, 1138–1141, 1152–1157. Tables/proofs not comprehensively audited. SHA-256: `5d860e4e0eb2c0dfc2dab588243683384be86f6d9cb8d6bcc26b81e70680772f`.

### R03-S08 — A model-specific organizational asset

Andrew Atkeson and Patrick J. Kehoe. 2005. “Modeling and Measuring Organization Capital.” *Journal of Political Economy* 113(5):1026–1053. DOI [10.1086/431289](https://doi.org/10.1086/431289). [Author-hosted published article](https://pkehoe.people.stanford.edu/sites/g/files/sbiybj30446/files/media/file/modeling_measuring_organization_capital.pdf). Inspected introduction, §I, selected §§III–IV passages and conclusion. NSF support disclosed. Calibration and underlying Census data not independently reproduced. SHA-256: `06e964ad0b7c75a9ab4bc5f685ce68b53c0019b45ec95dbf6a4a4ba8a4570a9d`.

### R03-S09 — Average relations, noise and inefficiency

Dennis Aigner, C. A. Knox Lovell and Peter Schmidt. 1977. “Formulation and Estimation of Stochastic Frontier Production Function Models.” *Journal of Econometrics* 6(1):21–37. DOI [10.1016/0304-4076(77)90052-5](https://doi.org/10.1016/0304-4076(77)90052-5). [Public author-uploaded text](https://www.researchgate.net/publication/4857712_Formation_and_Estimation_of_Stochastic_Frontier_Production_Function_Models). Inspected §§1–3, pp. 21–25. Page metadata abbreviates the title incorrectly; the article heading supplies the title above. Formal econometric source; simulations and estimates not replicated. No login required for the inspected text.

### Access limits and excluded leads

The Rice-hosted production lecture returned 404. Damiani's 2023 production notes were opened, but apparent sign/notation inconsistencies made them unsuitable as the load-bearing definition source; S01 was used instead. The publicly surfaced Mas-Colell 1985 chapter preview and Prescott–Visscher 1980 abstract were not treated as full-text reads. Rubinstein's author download route required registration, and an Open Book Publishers route presented an anti-bot check; neither was pursued through registration or challenge completion. No inaccessible book was counted as substantively reviewed. Milgrom–Roberts' separate 1988 organizational-theory scan was retrieved as a lead, but was not used for a substantive source claim.

These limitations do not undermine the explicit algebraic counterexamples or the inspected 1995 correction. They do prevent describing this review as an exhaustive survey of production theory, all theories of organization, or the capital controversies. The deliverable establishes a usable conceptual boundary for the book and identifies exactly which stronger claims require evidence or an explicit authorial choice.
