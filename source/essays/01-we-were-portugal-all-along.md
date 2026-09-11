<!-- SOURCE-PROVENANCE
Imported from the Google Drive document "We Were Portugal All Along" on 2026-09-11.
Drive file id: 1UiiMleTWFzYUkI-337Z5QOyNTQBMNPQmR5M0UzjyBtw
Markdown heading markers reflect the source document's paragraph styles; substantive text is preserved.
-->

# We Were Portugal All Along

In 1817, an English economist named David Ricardo worked out something counterintuitive about trade between two countries.

Imagine Portugal is better than England at making both wine and cloth. Faster, cheaper, better at both. The obvious conclusion is that Portugal should make everything and England should make nothing.

Ricardo showed the obvious conclusion is wrong.

Even when Portugal is better at both, both countries gain if Portugal focuses on what it's most better at (wine) and England focuses on what it's least worse at (cloth). Portugal has absolute advantage in everything. England still has comparative advantage in something. And comparative advantage — not absolute — is what determines who should do what.

This is one of the most durable ideas in economics. It's also the clearest frame I've found for what's happening with AI and knowledge work right now — as long as we get the assignments right. A note on scope before I begin: this is a claim about knowledge work. Plumbing, construction, and field operations are waiting on robotics, and the inversion will look different there.

## Most readings of this analogy get it wrong.

The intuitive move is to cast humans as England — the less-productive party, scrappy, surviving by doing what we're least bad at while the more-capable party (AI) makes the wine. That framing feels honest because it accepts that the model has gotten better than us at a lot of things. But it leads somewhere false. If humans are England, our niche shrinks every time the model improves, because England's comparative advantage weakens as the productivity gap widens. Follow that logic all the way down and human work disappears.

## The assignments are backwards.

Humans are Portugal. We have absolute advantage in the one factor of production that matters most in knowledge work: territory-grounded sense-making. We had absolute advantage at cloth too — drafting memos, summarizing documents, pattern-matching across datasets — for most of history. That wasn't inefficient. It was the only option. There was no one else to make the cloth.

AI is England. It started with comparative advantage at cloth — faster at narrow tasks, cheaper per unit output. But unlike Ricardo's England, AI scales on a trajectory land and labor couldn't. Every frontier model release, every increase in inference compute, every improvement in retrieval and grounding — that's England turning its cloth advantage into dominance at cloth. A year ago this was contested. It isn't anymore. If you're still putting a human on initial triage of a hundred-page report, you're Portugal making cloth while England masters the loom.

The question isn't whether to trade. The question is whether we've noticed what our actual absolute advantage is — and whether we're willing to specialize into it.

## Polanyi's floor.

To understand why humans have absolute advantage at sense-making, not just comparative advantage, we need a different economist.

In 1966, Michael Polanyi wrote a line that should be taught alongside Ricardo: "We know more than we can tell."

His argument was that a huge share of human knowledge is tacit — lived, embodied, demonstrable but not articulable. You know how to ride a bike. You cannot write a manual that would let someone else ride a bike from reading it alone. You know how your office actually works. You cannot write a manual that would let a new hire operate inside it effectively on day one, no matter how thorough you are, because the knowledge isn't fully in your head as propositions. It's in your pattern recognition, your relationships, your sense of what "we do here" means in a specific situation you haven't yet encountered.

This matters for AI because models learn from what can be told. Their entire training corpus is the explicit layer — the written, the recorded, the formalized. The tacit layer doesn't exist in any form they can ingest. It isn't that they haven't gotten to it yet. It's that the input doesn't exist outside the humans who carry it.

This is what makes territory knowledge a factor endowment, not a comparative advantage. Humans possess a factor of production that no amount of compute can substitute for, because the factor isn't produced by computation in the first place. It's produced by being-in-the-territory, which models structurally cannot do.

Notice what this makes the argument. Ricardo's comparative advantage assumed both parties could produce both goods, just at different costs. Polanyi's floor changes the structure of the claim. AI's production capacity for tacit knowledge isn't low. It's structurally zero — not because models haven't gotten there yet, but because the factor isn't produced by computation at all. Humans don't just have absolute advantage here. We have a strict monopoly on a necessary input. The trade isn't a negotiation between peers with different strengths. It's a hard dependency running in one direction.

New-institutional economics adds the organizational dimension. Douglass North and Oliver Williamson spent their careers on a question that matters here: why do institutions exist at all? Why don't markets just handle everything? The answer is transaction costs — the friction of specifying, measuring, enforcing, and adapting agreements when knowledge is incomplete and circumstances change.

Institutions exist because they reduce those costs. And the way they reduce them is by encoding information too expensive to formalize into norms, relationships, and practices that live in people. The reason your office has its particular informal rhythms is that those rhythms carry information the org chart can't. Trying to write them all down would cost more than preserving them tacitly in the humans who learned them by being there.

This is why territory knowledge isn't a temporary limit waiting for better models. It's a structural feature of how institutions work. You can't digitize it without changing what it is. The moment it's fully written down, it stops being the thing that was valuable.

Portugal's wine couldn't be scaled by anyone else. Our sense-making can't either.

## So the workflow inverts.

The old pattern was smart/fast/smart. Human thinks, model executes, human thinks again. Human as bread, model as filling. This worked when models were the scarce resource — when humans had absolute advantage at cloth too, and the only question was how to allocate our own time across both.

The new pattern is fast / human / fast. Model ingests at speed. Human sits in the middle and does the one thing that doesn't scale — reads the output, adds the territory insight, catches what's institutionally wrong even when it's technically right. Model executes at speed on the other side.

Concretely: a regional analyst gets a 200-page stakeholder comment file dropped on her desk Monday morning. Old pattern, she spends three days reading and categorizing before she can think. Fast/human/fast, the model ingests and clusters the comments by theme in minutes — she spends Monday afternoon reading the model's output against what she knows about which stakeholders matter, which arguments are load-bearing in her region specifically, what's missing because the commenters didn't know to raise it. Then the model drafts the response package she's now briefed to shape. The ingest compresses. The sense-making expands. Her judgment, not her throughput, is what the workflow is now built around.

The middle step isn't slow. It's non-parallelizable. You can't throw more clusters at territory knowledge. It takes the time it takes, because it's grounded in years of watching how your office actually works, and that input can't be copied, compressed, or accelerated.

Ricardo's insight, updated: when one party's scaling turns their comparative advantage into absolute advantage, the other party's absolute advantage in a non-substitutable factor doesn't diminish. It becomes the entire basis for the trade. The fast/human/fast workflow pattern has more operational depth than this piece can cover — I'll develop it as its own framework elsewhere.

## Two lanes of work.

The inversion reshapes cognitive labor into two lanes with different skills, different career paths, and different failure modes.

- Lane one: building the rails. Someone has to make sure ingest is load-bearing — that the data streams are hooked up right, that the output can be validated. This is systems work. It's what most people mean when they say "AI engineer," but it's narrower. It's plumbing for the exoskeleton.
- Lane two: operating the exoskeleton. Reading the dashboard. Adding the territory insight. Being the human in the loop who catches the thing the model couldn't see because it wasn't in the data. This is the work that our absolute advantage points to. It's also the work that public-sector professionals have been doing for their entire careers without a name for it.

The principal-agent problem returns here with new stakes: lane one is legible (latency, accuracy, throughput), lane two is largely illegible (value shows up as absence of failure). Organizations that optimize for what they can measure will under-invest in lane two by default. This is familiar territory in the abstract, but the specific machinery of performance measurement turns the general problem into a structural one worth its own analysis. I'll come back to that.

## The train isn't going the wrong way. It's off by five degrees.

Barely noticed at first. Every individual output looks defensible. Every risk summary is technically correct. Every memo is grounded in retrieved context. But each one is off by a small tacit misfit — something the model couldn't see because it wasn't in the data. The errors don't announce themselves. They compound.

Douglass North called this path dependence: the insight that institutions drift along trajectories set by small, early choices that get locked in by subsequent decisions built on top of them. A 5-degree deviation in year one is a 5-degree deviation. A 5-degree deviation compounded across three years of outputs, incorporated into downstream decisions, baked into informal norms about "how we use these tools here" — that's a different organization.

Every enterprise AI deployment that ships without territory-grounded humans in the middle is generating this drift right now. The technology is fine. The rails are solid. Nobody can point to the moment it went wrong, because there wasn't a moment. There was a small angle, repeated at scale, institutionalized through path dependence. How to diagnose the drift inside your own organization is a separate piece — the operational question of what five-degree misalignment looks like in practice deserves its own frame.

This is what North and Williamson were preparing us to see sixty years before the models arrived. Institutions don't fail by going off the rails. They fail by drifting along them.

## The apprenticeship paradox.

There's a tension inside this argument that I want to name rather than paper over.

Lane two skills — reading outputs against territory, catching tacit misfits, holding institutional context — don't appear fully formed. They're acquired the way all tacit knowledge is acquired: slowly, through exposure, by doing the explicit work long enough that the implicit patterns settle underneath it. You learn how your office actually works by spending years drafting the memos, running the triage, processing the datasets. The cloth was never just cloth. It was the vehicle through which the next generation absorbed the territory.

If we fully automate lane one, we risk severing the mechanism by which lane two workers are made.

This is the apprenticeship paradox. The same logic that tells us humans should stop making cloth also tells us that humans-who-can-do-lane-two only exist because humans used to make cloth. A world in which every junior analyst's first job is operating the exoskeleton — without ever having sat in the seat where the work originated — is a world that runs on territory knowledge nobody is being trained to acquire.

I don't think this tension is fatal to the argument, but I'm going to hold the resolution for a future piece. For now, it's enough to name: the prescription to specialize into sense-making assumes a stock of sense-makers. That stock was produced by the very work we're now saying should be automated. Anyone writing confidently about AI and the future of knowledge work without engaging this question is missing something important.

## The prescription.

We probably should have stopped making cloth two or three years ago. We definitely should now.

Our absolute advantage remains — even as AI's comparative advantage at cloth has scaled into dominance at cloth. That's not a threat to the trade. That's the trade working as designed, once the assignments are right. Portugal doesn't lose when England masters the loom. Portugal loses when Portugal keeps making cloth anyway.

If you haven't made the switch from doing to sense-making, now is the time. The specialization has been available for a while. The scaling trajectory that made it necessary has been visible for a while. What's new is that the cost of not specializing is now legible — in the form of institutions drifting five degrees at a time, powered by excellent infrastructure producing institutionally-wrong outputs at scale.

If you have made the switch, double and triple down. Get better at the thing only you can do. Build the muscles for reading outputs against territory, for catching the tacit misfit, for being the human in the middle whose presence keeps the train aligned.

Ricardo didn't know about large language models. He knew that specialization produces mutual gain — but only when both parties specialize into what they have absolute advantage in, and only when they recognize when scaling has shifted the advantage lines.

Polanyi didn't know either. He knew that the most valuable knowledge in any organization is the knowledge that resists being written down.

North and Williamson didn't know either. They knew that institutions exist to preserve exactly that knowledge at scale — and that the way institutions fail is rarely dramatic.

The part of your job that was hardest to do well, because you never had time, is about to become the part that matters most. Not because you're least bad at it. Because you're the only one who can do it at all.

That's the trade.
