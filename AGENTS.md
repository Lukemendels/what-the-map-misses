# AGENTS.md

Standing operating rules for AI systems working in this repository.

## Authority

This repository is the authoritative public state of *What the Map Misses*.

Conversation history, model memory, private workspaces, and prior agent claims are orientation only. Before continuing substantial work, inspect the repository and `STATUS.md`.

## Public boundary

This is a public repository.

Only publication-safe material intentionally placed in this repository may be used as project context. Do not search parent directories, mounted personal drives, private workspaces, credentials, unrelated repositories, or other local data for additional context unless a later explicit human instruction identifies a specific public-safe source and authorizes its use.

Private StickShift/OKF state is not implicitly available to this project and must never be reconstructed, inferred, or copied into the repository from memory.

## Authorship boundary

Luke Mendelsohn is the author and final authority over the book's thesis, normative judgments, substantive interpretation, tone, and what becomes canonical.

AI systems may research, synthesize, challenge, structure, test, and draft when a loop explicitly authorizes that work.

Do not silently resolve a material contradiction in Luke's ideas by choosing the version the model prefers. Preserve the conflict and escalate it through the decision mechanism defined by the active loop.

## State discipline

- Preserve provenance.
- Prefer explicit durable artifacts over conversational memory.
- Do not silently rewrite historical evidence or author decisions.
- Do not treat a generated draft as canonical unless the active loop explicitly makes it so.
- Do not delete contradictory evidence because it complicates the argument.
- Use Git history as part of the project's intellectual provenance.

## Remote durability

The authoritative durable state is the remote repository, not an unpushed local clone.

- A local commit is an intermediate state until it has been successfully pushed to the authoritative remote.
- When an active loop requires a durable checkpoint, commit the checkpoint and push it to the designated authoritative branch before treating that checkpoint as durable.
- Unless the active loop explicitly specifies another branch or remote, use `origin` and the repository's current authoritative branch.
- Do not report a checkpoint or terminal state as durable merely because `git commit` succeeded locally.
- After a required push, verify the remote contains the intended commit. Suitable verification includes fetching the remote and confirming that the local checkpoint or terminal commit is reachable from the corresponding remote branch.
- If push fails because of authentication, divergence, branch protection, connectivity, or another concrete blocker, preserve the local commit, report the blocker truthfully, and do not claim remote durability.
- Never force-push, rewrite published history, or discard remote work unless an explicit human instruction or active loop specifically authorizes it.

## Execution discipline

- Read the active loop specification before beginning mission work.
- Respect frozen or protected state declared by that loop.
- Use deterministic checks where a deterministic property can be tested.
- A commit is a state transition, not proof of completion.
- A checkpoint required to be durable is not complete until its commit has been pushed and verified on the authoritative remote.
- Do not declare success until the active loop's terminal condition is actually satisfied.
- If a local failure occurs, make the smallest causal repair permitted by the loop rather than reopening completed work.

## Research discipline

External research is permitted only when the active loop authorizes it.

When research is authorized:

- distinguish primary sources, strong secondary sources, interpretation, and speculation;
- record sources closely enough that another reader can recover them;
- preserve material counterevidence;
- do not improve an anecdote at the expense of historical accuracy;
- state where an analogy breaks as well as where it fits.

## Failure posture

Failure is data.

Do not hide a failed check, invent completion, or narrow the mission silently to obtain a clean terminal report. Surface the concrete blocker, preserve the last known good state, and follow the active loop's repair or escalation procedure.

The project should not require any individual AI invocation to be infallible. The surrounding process must make ordinary error visible, bounded, and recoverable.
