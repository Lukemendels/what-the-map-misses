# LOOP 1 — CORPUS INGESTION, THESIS EXTRACTION, AND COHERENCE AUDIT

Repository:

`https://github.com/Lukemendels/what-the-map-misses`

The repository is authoritative.

This is the **FIRST BOOK-PRODUCTION LOOP**.

Read `AGENTS.md` and `STATUS.md` before doing substantive work.

This loop converts Luke Mendelsohn's publication-safe authored corpus into an explicit, traceable candidate book thesis and identifies any conceptual conflicts that require authorial adjudication.

This is an **INGESTION, EXTRACTION, STRUCTURING, AND COHERENCE** mission.

It is not a historical-research mission.

It is not a drafting mission.

It is not a publication mission.

---

# GOAL

Transform the complete publication-safe corpus intentionally admitted under `source/` into a durable intellectual model of the proposed book.

The loop must establish:

1. what the admitted corpus actually argues;
2. which propositions are central versus supporting;
3. how the major propositions depend on one another;
4. where concepts evolved or superseded earlier formulations;
5. where material tension, ambiguity, or contradiction remains;
6. which claims require future empirical or historical research;
7. which conflicts can be reconciled from the corpus itself;
8. which conflicts require Luke's judgment;
9. and a candidate book thesis that remains faithful to the authored corpus rather than silently replacing it with the model's preferred argument.

The desired result is **a coherent candidate thesis with inspectable provenance**, not polished chapter prose.

---

# AUTHORITATIVE INPUTS

Use only:

- `README.md` for the public project framing;
- `AGENTS.md` for standing operating rules;
- `STATUS.md` for current project state;
- substantive publication-safe files intentionally present under `source/`;
- Git history inside this repository where useful for provenance.

The source corpus is authoritative for Luke's existing authored ideas.

Later-dated material does not automatically override earlier material merely because it is newer. Treat a later formulation as superseding an earlier one only when the corpus provides reasonable evidence that the idea evolved, was revised, or was explicitly abandoned.

Preserve meaningful intellectual evolution rather than flattening it into artificial consistency.

---

# PUBLIC-SAFETY BOUNDARY

This repository is public.

Do not search for additional context in:

- parent directories;
- mounted personal drives;
- private repositories;
- browser profiles;
- credentials;
- private StickShift or OKF workspaces;
- unrelated local files;
- email;
- cloud accounts;
- or any other source not explicitly admitted to this repository.

Do not infer missing private context from memory.

If the corpus is insufficient to support a proposition that appears in the public README, record the gap. Do not search privately for the missing material.

---

# EXCLUSIONS

Do not:

- conduct new web research;
- verify historical examples against external sources;
- add historical examples merely because they would strengthen the argument;
- write polished book chapters;
- optimize prose for a market or audience;
- create citations to sources that are not present in the admitted corpus;
- silently resolve a substantive contradiction by choosing the argument you prefer;
- modify source files under `source/`;
- rewrite `README.md` or `AGENTS.md`;
- freeze the book thesis as final;
- begin Loop 2 work.

Historical, empirical, legal, economic, scientific, or technical propositions that need external verification should be classified for future research rather than researched now.

---

# AUTONOMOUS COMPLETION CONTRACT

Carry this mission through to one of its explicit terminal states without additional user prompting.

Do not stop after:

- reading the corpus;
- listing files;
- summarizing the essays;
- identifying several themes;
- discovering a contradiction;
- creating an argument map;
- creating a candidate thesis;
- making an intermediate commit;
- or describing what should happen next.

These are intermediate states.

Continue until every admitted substantive source has been inventoried, the argument has been extracted, material tensions have been classified, required decision packets have been created, acceptance gates have been checked, durable state has been committed and pushed to the authoritative remote, and `STATUS.md` reflects the terminal state.

If the source corpus has not yet been populated with substantive authored material, do not fabricate an analysis from the README alone. Record the blocker in `STATUS.md`, preserve the repository, and terminate as `SOURCE_CORPUS_REQUIRED`.

---

# REMOTE DURABILITY CONTRACT

The authoritative durable state for this mission is the remote GitHub repository, not an unpushed local clone.

Unless repository state explicitly establishes a different authoritative branch, use `origin/main`.

For every required checkpoint in this loop:

1. complete the checkpoint artifacts;
2. inspect the working tree;
3. commit the checkpoint with the specified or equivalent message;
4. push the checkpoint commit to the authoritative remote branch;
5. verify that the remote branch contains the checkpoint commit;
6. only then treat the checkpoint as durable and proceed to the next phase.

A local commit alone is **not** a durable checkpoint.

If push fails because of authentication, divergence, branch protection, connectivity, or another concrete blocker:

- preserve the local commit;
- diagnose the concrete failure;
- make only safe, non-destructive repairs;
- do not force-push or rewrite published history;
- do not proceed as though the checkpoint were durable;
- and do not report successful checkpoint or terminal completion until the required remote state exists.

At terminal closeout, fetch the authoritative remote and verify that the final local `HEAD` is the commit referenced by, or is reachable from, the authoritative remote branch. The final user-facing completion report must report the remotely durable final commit SHA.

---

# CONCEPTUAL CLASSIFICATION

Distinguish at least the following types of intellectual state.

## 1. Reinforcing formulations

Different passages express substantially the same idea and strengthen or clarify one another.

Preserve the strongest formulation and record important variants where they reveal development.

## 2. Evolution / supersession

The corpus shows that Luke's view materially changed.

Preserve both the earlier and later formulation and record the lineage. Do not treat intellectual development as an error.

## 3. Resolvable tension

Two claims initially appear inconsistent, but careful representation of their scope, time horizon, level of analysis, or definitions allows both to survive without changing Luke's substantive position.

Resolve the tension explicitly and record the reconciliation.

## 4. Material ambiguity

The corpus permits more than one interpretation and does not yet determine which is intended.

Preserve the ambiguity. If future evidence could resolve it, mark it for research. If it requires Luke to choose what he means, escalate it as an author decision.

## 5. Authorial conflict

Two central claims cannot both survive in their current form, neither is clearly superseded, and choosing between them would materially alter the thesis, causal mechanism, normative position, or structure of the book.

Do not choose.

Create an author decision packet.

---

# CLAIM DISCIPLINE

Assign stable claim IDs as substantive claims are extracted.

Use a durable format such as:

`C-001`, `C-002`, `C-003`, ...

Once assigned and committed, claim IDs should not be casually renumbered in later work.

For each material claim, record at minimum:

- **Claim ID**
- **Proposition**
- **Role**: core thesis / supporting / causal bridge / normative / forecast / empirical-historical / definition / limitation
- **Corpus basis**: exact source path or paths
- **Status**
- **Depends on**
- **Supports**
- **Tensions or contradictions**
- **Research need**, if any
- **Notes on evolution or scope**

Permitted claim statuses include:

- `AUTHOR_CORPUS_SUPPORTED`
- `SYNTHESIZED_FROM_CORPUS`
- `SUPERSEDED`
- `RESOLVED_TENSION`
- `MATERIAL_AMBIGUITY`
- `EMPIRICAL_RESEARCH_REQUIRED`
- `AUTHOR_DECISION_REQUIRED`

A synthesized proposition may be created when it is a faithful logical connection among authored ideas. It must be labeled `SYNTHESIZED_FROM_CORPUS` and trace back to the propositions from which it was derived.

Do not smuggle a novel model-generated thesis into the ledger as though Luke already authored it.

---

# EXECUTION PHASES

## CHECKPOINT A — CORPUS INGESTION

1. Inspect the repository state and confirm the active branch and current HEAD.
2. Read `AGENTS.md`, `STATUS.md`, and `README.md`.
3. Recursively inventory the substantive files under `source/`.
4. Distinguish actual corpus material from directory instructions, manifests, or placeholders.
5. Create `evidence/corpus-manifest.md`.
6. For each source artifact, record:
   - repository-relative path;
   - title, where available;
   - approximate date/version, where available from the artifact;
   - artifact type;
   - role in the corpus;
   - Git/blob/hash identifier where practical;
   - whether the file contains explicit supersession or revision information;
   - any obvious publication-safety concern discovered inside the admitted file.
7. Confirm whether the corpus is sufficient to perform thesis extraction.

If there is no substantive corpus, update `STATUS.md` to `SOURCE_CORPUS_REQUIRED`, commit the manifest/status state, push that commit to the authoritative remote, verify the remote contains it, and stop. Do not proceed using the README as a substitute corpus.

If the corpus is sufficient, commit Checkpoint A with a message equivalent to:

`Loop 1 checkpoint A: inventory admitted author corpus`

Push the checkpoint commit to the authoritative remote and verify the remote contains it before proceeding to Checkpoint B.

Record the checkpoint commit in the later completion artifact.

## CHECKPOINT B — CLAIM AND ARGUMENT EXTRACTION

Read the complete admitted corpus closely enough to represent its substantive argument rather than merely keyword-clustering it.

Create:

- `evidence/claims/CLAIM-LEDGER.md`
- `evidence/argument-map.md`

The claim ledger is the traceable inventory of substantive propositions.

The argument map should show the logical structure connecting those propositions. It should make visible:

- foundational premises;
- causal mechanisms;
- intermediate conclusions;
- book-level conclusions;
- normative propositions;
- empirical/historical claims requiring verification;
- important nonclaims or boundaries;
- and major dependencies.

Use a human-readable representation. Mermaid may be included when useful, but the argument must remain understandable without relying on rendered graphics.

Do not equate repetition with importance. Infer centrality from how claims function in the argument and how repeatedly later reasoning depends on them.

Commit Checkpoint B with a message equivalent to:

`Loop 1 checkpoint B: extract claims and argument structure`

Push the checkpoint commit to the authoritative remote and verify the remote contains it before proceeding to Checkpoint C.

## CHECKPOINT C — COHERENCE AND CONFLICT AUDIT

Create `evidence/coherence-audit.md`.

Audit the argument for:

- direct contradiction;
- hidden contradiction;
- inconsistent definitions;
- shifts in unit of analysis;
- changes in time horizon;
- confusion between descriptive and normative claims;
- confusion between present-state claims and future predictions;
- causal leaps;
- unsupported bridges;
- assumptions required but not stated;
- historical examples currently carrying more argumentative weight than their unverified status permits;
- duplication that obscures rather than strengthens the thesis;
- and places where the corpus genuinely evolved.

For every apparent conflict, classify it using the conceptual classification above.

Resolve only `RESOLVABLE_TENSION` cases whose reconciliation is supported by the corpus.

Do not resolve `AUTHOR_DECISION_REQUIRED` cases yourself.

For each authorial conflict, create one file under:

`decisions/pending/`

Use a stable filename such as:

`D-001-<short-slug>.md`

Each decision packet must contain:

1. **Decision ID**
2. **The exact crux**
3. **Position A** with supporting claim/source IDs
4. **Position B** with supporting claim/source IDs
5. **Why they cannot both survive unchanged**
6. **What changes in the book if A is chosen**
7. **What changes in the book if B is chosen**
8. **Whether a third synthesis is logically available**
9. **What additional evidence could help, if evidence rather than authorial judgment is the missing input**
10. **A concise question for Luke**

Do not pad the decision packet with generic pros/cons. Isolate the actual intellectual fork.

Commit Checkpoint C with a message equivalent to:

`Loop 1 checkpoint C: complete coherence and conflict audit`

Push the checkpoint commit to the authoritative remote and verify the remote contains it before proceeding to Checkpoint D.

## CHECKPOINT D — CANDIDATE THESIS

Create:

`book/thesis/THESIS-CANDIDATE-1.0.md`

This artifact should synthesize the strongest coherent version of the corpus **without pretending pending author decisions have been resolved**.

Include at minimum:

### Central thesis

A concise statement of the book's current strongest argument.

### Core propositions

The minimum set of propositions required for the thesis to work.

### Causal chain

Show how the propositions connect rather than presenting them as a list of themes.

### Levels of analysis

Distinguish where the book is reasoning about:

- individual cognition and capability;
- firms and institutions;
- software and production technology;
- labor and human-capital formation;
- governance and control rights;
- macroeconomic or welfare effects;
- future adaptive machine cognition.

### Current book arc

Describe a candidate chapter or part sequence derived from the argument. This is architecture, not prose drafting.

### Nonclaims and boundaries

Record important things the book is **not** currently claiming, particularly where overstatement would make the thesis easier to attack than the authored position actually is.

### Empirical and historical research agenda

List claims that require external validation in later loops, prioritized by how much argumentative weight they carry.

### Pending author decisions

Reference any `D-###` packets and explain which parts of the candidate thesis remain conditional on them.

Do not label this artifact final or frozen.

Checkpoint D is incorporated into terminal closeout. Do not treat the candidate thesis as durable until the final Loop 1 commit containing it and the completion artifacts has been pushed and remotely verified.

---

# AUTHORIAL ESCALATION RULE

The existence of a difficult question is not itself reason to stop the loop.

Continue autonomously through research-free reconciliation, classification, mapping, and all work that is not dependent on Luke's choice.

Escalate only when:

- two materially important authored propositions cannot both survive;
- no clear supersession exists;
- corpus evidence cannot resolve the conflict;
- and choosing a resolution would require deciding what Luke actually believes, intends, values, or wants the book to argue.

In that case, create the decision packet and continue all independent work.

Do not wait interactively for Luke during the loop.

The loop's terminal state may legitimately be `AUTHOR_DECISION_REQUIRED`.

---

# ACCEPTANCE GATES

Before terminal closeout, verify all applicable gates.

- [ ] Every substantive admitted source file is represented in `evidence/corpus-manifest.md`.
- [ ] Source files under `source/` were not modified.
- [ ] No external research was conducted or smuggled into the thesis as new evidence.
- [ ] All major book-level propositions have stable claim IDs.
- [ ] Every major proposition traces to authored corpus material or is explicitly labeled `SYNTHESIZED_FROM_CORPUS`.
- [ ] The argument map shows dependency and causal structure, not merely topical similarity.
- [ ] Material historical/empirical assertions needing verification are marked `EMPIRICAL_RESEARCH_REQUIRED`.
- [ ] Every substantive apparent contradiction is classified.
- [ ] Resolved tensions include an explicit reconciliation grounded in the corpus.
- [ ] Authorial conflicts have decision packets.
- [ ] Contradictory or inconvenient source material has not been silently discarded.
- [ ] The candidate thesis accurately distinguishes present claims, forecasts, normative propositions, and analogies.
- [ ] Important nonclaims and limitations are preserved.
- [ ] No polished chapter drafting occurred.
- [ ] No private or non-admitted context was pulled into the public repository.
- [ ] `book/thesis/THESIS-CANDIDATE-1.0.md` exists if the corpus was sufficient.
- [ ] `evidence/coherence-audit.md` exists if the corpus was sufficient.
- [ ] `STATUS.md` reflects the actual terminal state.
- [ ] All mission outputs are committed to Git.
- [ ] Every required checkpoint commit was pushed to the authoritative remote before the next checkpoint began.
- [ ] The final Loop 1 commit was pushed to the authoritative remote.
- [ ] After fetching the remote, the authoritative remote branch contains the final Loop 1 commit.
- [ ] Final local and remote repository state is inspected after the last push.

Do not substitute model confidence for these checks.

---

# REPAIR POLICY

If an acceptance gate fails:

1. identify the concrete failure;
2. determine the smallest causal defect;
3. repair only the affected Loop 1 artifact or extraction step;
4. rerun any acceptance checks whose validity may have changed;
5. preserve the corpus and previously valid work;
6. continue toward terminal closeout.

Do not use a local extraction or formatting problem as permission to rewrite the source corpus or expand into external research.

If a required push fails, treat remote durability itself as the failed gate. Preserve the local commit, repair only the concrete Git/authentication/divergence issue where safe, and do not weaken the durability requirement to obtain a clean terminal state.

---

# TERMINAL STATES

Exactly one of the following states should be recorded in `STATUS.md`.

## `SOURCE_CORPUS_REQUIRED`

Use only if substantive authored source material has not yet been admitted under `source/` in sufficient quantity to perform the mission.

This is a legitimate blocked terminal state, not permission to invent missing context.

## `LOOP_1_COMPLETE_AUTHOR_REVIEW_READY`

Use when:

- the corpus has been fully inventoried;
- claim extraction and argument mapping are complete;
- the coherence audit is complete;
- the candidate thesis exists;
- acceptance gates pass;
- all required commits are remotely durable;
- and no material conflict requires Luke to choose between incompatible authored positions.

The thesis is still a **candidate**, not frozen.

## `LOOP_1_COMPLETE_AUTHOR_DECISION_REQUIRED`

Use when all non-dependent Loop 1 work is complete, all required commits are remotely durable, but one or more material authorial conflicts remain.

All such conflicts must have complete `decisions/pending/D-###-*.md` packets.

The thesis remains conditional where those decisions matter.

---

# TERMINAL CLOSEOUT

Create:

`method/LOOP-1-COMPLETION.md`

Record:

- start commit;
- Checkpoint A commit;
- Checkpoint B commit;
- Checkpoint C commit;
- final commit;
- authoritative remote and branch;
- remote-verification result for each required checkpoint;
- remote-verification result for the final commit;
- number of substantive source artifacts;
- number of extracted claims;
- number of empirical/historical research needs;
- number of resolved tensions;
- number of material ambiguities;
- number of pending author decisions;
- acceptance-gate results;
- final terminal state;
- exact next recommended transition.

Then update `STATUS.md` consistently.

Commit the final state with a message equivalent to:

`Loop 1 complete: thesis extraction and coherence audit`

Push the final commit to the authoritative remote branch.

Then fetch the remote and verify that the authoritative remote branch contains the final commit. Inspect both local and remote repository state after the push.

A successful local commit is not terminal completion.

A successful push without remote verification is not terminal completion.

Only after the final commit is pushed, remotely verified, and the repository reflects the recorded terminal state may the user-facing completion report be produced.

The report should state concisely:

- terminal state;
- remotely durable final commit SHA;
- source/claim counts;
- major thesis result;
- whether author decisions are required;
- paths to the principal artifacts;
- and the exact next step.

Do not call the thesis frozen.

A later author-adjudication/freeze loop will establish `THESIS-1.0` after Luke has reviewed the candidate and resolved any required decisions.
