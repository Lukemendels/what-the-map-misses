<!-- SOURCE-PROVENANCE
Imported from the StickShift/OKF concept `writing/the-production-function-is-becoming-writable-v3.md` supplied to the book-planning session on 2026-09-10.
This is draft V3, originally saved 2026-08-06. External quantitative claims and links in the draft are explicitly provisional and must be independently verified before publication.
-->

# The Production Function Is Becoming Writable

## Draft status

V3 saved August 6, 2026.

This is a separate versioned draft rather than an overwrite of V2 so the progression remains visible.

Changes from V2:

- added a concrete account of Luke, an economist without traditional software-engineering training, building more than a dozen functioning browser tools;
- clarified that the central change is not a universal percentage increase in developer productivity, but a major reduction in the threshold for which software can exist and who can create it;
- added current external evidence that AI coding tools are being used beyond professional software-development roles;
- added an explicit caveat that prototypes are not secure production systems and that measured productivity effects for experienced developers remain mixed;
- quantified the AutoReviewer failure as roughly three weeks spent inside the original architecture;
- consolidated many one-sentence paragraphs so short paragraphs primarily mark real turns in the argument;
- kept TSA and internal federal examples out of the essay deliberately;
- did not add Coase or formal transaction-cost terminology to the body.

External quantitative claims and links remain provisional and should be independently verified before publication.

---

In the 1880s, factory owners began replacing steam engines with electric motors.

The new technology was clearly better. Electricity was cleaner, easier to control, and more reliable. It did not require the same boilers, fuel storage, smoke, or constant mechanical attention. Factory owners expected productivity to jump.

It mostly didn’t.

They had removed the steam engine and installed one large electric motor in its place. The motor still turned the same central shaft running through the factory. The shaft still drove a web of belts and pulleys. The machines still sat where those belts could reach them.

The power source changed.

The factory did not.

The real gains came later, when engineers realized electricity did not need a central shaft at all. A small motor could be placed directly on each machine. Equipment could be arranged around the sequence of the work instead of the reach of the belts. Materials could move in straighter lines, machines could operate independently, and factories could be built around what they were trying to produce rather than around the limitations of steam power.

Electricity was the breakthrough. Moving the machinery was the transformation.

We are in the line-shaft years of AI.

* * *

Most organizations are taking a new source of machine cognition and connecting it to the factory they already have.

Employees get a chatbot. The chatbot helps them write the same reports, prepare the same presentations, complete the same forms, answer the same emails, and move work through the same chain of handoffs and approvals.

The memo gets drafted faster. The meeting notes get summarized. The document gets polished. The existing factory hums a little louder.

Then leadership looks for the productivity revolution and wonders why it has not arrived.

The normal answer is that the models are not good enough yet. They make things up. They lose context. They need better data, access to more systems, longer memories, stronger reasoning, or an army of agents. They need another year of technical progress.

Some of that is true. But it misses the deeper problem.

We changed the motor.

We left the shaft.

* * *

## Two revolutions at once

AI is difficult to understand because it is not one transformation. It is two.

The first is the obvious one: cognition is becoming cheap and abundant.

Models can read, explain, summarize, compare, translate, classify, draft, reason, generate alternatives, and write code. Work that once required hours of trained human attention can increasingly be performed in seconds.

That alone would be historic.

But something else is happening at the same time: software is becoming cheap and plastic.

For most of the computer age, custom software was expensive. Even a modest application could require developers, requirements documents, project managers, budgets, procurement, testing, integration, deployment, and years of maintenance.

That expense shaped how organizations worked. Companies bought generalized software because generalized software was what they could afford. The application arrived with its own screens, fields, categories, sequences, and assumptions. People then rearranged their work to fit it.

The software stayed rigid. The humans became the flexible component.

They copied information between systems, maintained unofficial spreadsheets, reformatted documents by hand, and memorized which button really moved a case forward and which field existed only because someone had required it twelve years ago. They became the belts connecting machinery that had never been designed to work together.

AI is beginning to change that cost structure.

Here is the scale of the shift.

I am an economist, not a traditionally trained software engineer. Over the last year, working mostly by describing the behavior I wanted in plain English, inspecting what the model produced, and testing it against the real task, I have built more than a dozen functioning browser tools.

Some took weeks to harden. But the first useful version often appeared in hours.

Most addressed problems too narrow, local, or changeable to have ever justified a conventional software project. No organization would have assembled a development team, written a requirements package, found a budget, and maintained a commercial application for each one.

The software simply would not have existed.

Now it does.

This is not only happening among professional developers. By June 2026, more than five million people were using OpenAI’s Codex each week, with knowledge workers outside software development accounting for roughly one-fifth of its users. Among a sample of individual users, more than one-quarter had delegated at least one task estimated to require over eight hours of human work.

Source to verify before publication:

https://openai.com/index/how-agents-are-transforming-work/

That does not mean software engineering has become effortless.

A prototype is not a secure production system. Generated code still has to be understood, tested, governed, maintained, and fitted to the environment where it will operate. Experienced developers working inside large, mature codebases do not receive automatic productivity gains merely by adding an AI tool. Controlled research has found mixed results, ranging from a slowdown with early-2025 tools to uncertain signs of improvement in later studies.

Source to verify before publication:

https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/

But the threshold has moved.

A domain expert can now cross from describing a problem to exercising a working piece of software without first completing the traditional journey into software development. The first version may be rough. It may fail. It may reveal that the original idea was wrong. But it can exist soon enough to be used, tested, and changed.

Software that would never have justified a procurement can now be built for one office. A workflow that would never have received an engineering team can now be tested in an afternoon. An interface can be changed after watching one person use it. A repeated judgment call can become a rule, and an unnecessary handoff can disappear.

The machinery can move.

That is what makes this moment so unusual. AI is giving us a new source of cognition at the same time it is making the machinery around cognition easier to rebuild.

The power source is changing, and the factory floor is becoming movable.

* * *

## What a production function really is

Economists call the arrangement a production function.

The phrase sounds more complicated than the idea. A production function is simply the way people, tools, information, rules, and machinery are combined to produce an outcome.

A factory combines workers, machines, materials, power, and process to produce a car. An office combines employees, software, documents, meetings, approvals, and institutional knowledge to produce a decision.

A law firm produces a brief. A hospital produces a diagnosis. A government agency produces a regulation. A newsroom produces a story.

Every one of those outcomes has a production function behind it: an arrangement that determines who does what, in what order, using which information, with which tools, and under which rules.

Most of the time, we treat that arrangement as fixed.

One person receives the request. Another analyzes it. A third reviews it. The work moves into another system, a document is generated, someone signs it, and someone else reenters the result somewhere downstream.

Then AI arrives, and the organization asks which of those steps a model can perform.

That is useful. It is also too small a question.

Those steps are not laws of nature. They are one historical arrangement of the work.

The report may exist because the old system needed a static document to move information between people. The handoff may exist because two applications could not communicate. The review layer may exist because uncertainty could not be surfaced earlier. The specialized role may exist because the knowledge needed for one narrow task was too expensive for everyone else to acquire.

The sequence may exist because each stage required the full attention of another scarce human mind.

Those constraints were real when the process developed.

Some of them are not real anymore.

When cognition becomes abundant and software becomes plastic, the old diagram loses its presumption of necessity.

* * *

## Software was always the factory floor

We usually talk about software as a tool. That understates what it does.

Software determines how modern knowledge work is arranged. It decides what enters the process, which information is visible, which action comes next, and where the work waits. It helps determine who can change something, who can approve it, and what becomes the official record at the end.

Software is not merely a hammer lying on the office desk.

It is the floor plan of the office.

Historically, that floor plan was expensive to change. Institutions therefore accumulated rigid systems and built human work around them.

A case-management system required fifteen fields because the vendor had designed fifteen fields. A report moved from analyst to reviewer to supervisor by email because email was the only system all three could use. A person copied information from one application into another because connecting them had never been funded. A team produced a document because the next office could not consume the underlying information in any other form.

Over time, the workflow began to look inevitable.

It wasn’t. It was the shape work took under the technical constraints of the time.

This is why merely adding a model often fails to produce the deeper gain. The model may help a person move information between systems faster when the person should not be moving it at all. It may draft the document faster when the document no longer needs to be the center of the process. It may accelerate a review step when a different design could expose the consequential decision before that review step exists.

The model makes the belt move faster.

The belt may be the problem.

* * *

## The new machine can help build the factory

Electricity could power new machinery. It could not help design the machinery.

AI can.

A model can help a person explain how their work actually happens and turn that explanation into requirements. It can draft the first version of a tool, help identify which parts of the work require interpretation and which should follow a fixed rule, write tests, explain unfamiliar technical concepts, and revise an interface after the user discovers that a button appears at the wrong moment.

It can help turn a local workaround into a repeatable system.

The new source of cognition is helping build the machinery that directs the new source of cognition. That creates a reinforcing loop.

Better models make software cheaper to build. Cheaper software makes it easier to place models where they are useful. Real use exposes where the workflow is wrong. The workflow gets rebuilt, and the rebuilt workflow makes the next useful application easier to see.

This is one reason the transition feels dizzying.

The motor is helping move the machines.

* * *

## I spent weeks building the wrong factory

I learned this by trying to build a document-review tool.

The objective was straightforward: give the system a Word document, let AI improve the writing, and return a revised version with tracked changes that a human could review, accept, or reject.

The first design seemed obvious. Ask the model to revise the language and mark every change using a specialized notation.

The model had to do two different kinds of work at once.

First, it had to make editorial judgments. Which sentence was unclear? Which claim needed support? Which paragraph belonged somewhere else? Which wording was stronger?

Then it had to perform an exact mechanical operation: preserve every unchanged word, mark every deletion and insertion correctly, avoid broken or overlapping edits, and return perfectly structured text that another program could parse.

The prompts grew. The formatting rules grew. The parser and validation layer grew. Each malformed response produced another instruction, and each instruction produced another edge case.

I spent roughly three weeks working inside that design. Several highly capable models helped plan, implement, and review it. All of them stayed inside the same basic frame: the model would make the revision and construct the tracked changes.

Then the useful question finally appeared:

Why is the model constructing tracked changes at all?

The model was good at deciding how the document should change. Ordinary software was good at comparing two versions of a document.

So the machinery moved.

The model would receive the original text and return a clean revised version. The original and the revision would become the two authoritative texts. Deterministic software would compare them and produce the tracked changes.

Much of the machinery built around the earlier design became unnecessary.

The model interpreted.

The software compared.

The human decided.

The problem had looked like an AI reliability problem. It was a factory-layout problem.

The model did not need to become smarter. The work needed to be rearranged.

* * *

## Better AI does not automatically mean better work

This distinction is easy to miss because we naturally focus on the model.

Which model is smartest? Which one scores highest? Which one can reason the longest or write the best code?

Those questions matter, but intelligence is only one part of the system.

A brilliant model can still sit inside a workflow that cannot turn its intelligence into completed work. It may not receive the right context or may return the answer in a form that cannot be used. A human may have to copy the result into another system. The model may be asked to perform a repetitive mechanical task that software could execute more reliably, or its output may never become an official record.

It may produce a beautiful document when the actual need was a decision. A person may be placed at the end as an approver but given too much output and too little context to exercise real judgment.

The model may perform impressively while the work remains unfinished.

The meaningful chain is longer. A human understands the objective. The model contributes interpretation. Software performs repeatable operations. The right information persists. Authority sits with someone who can genuinely exercise it. The result moves into the next action, and the outcome changes.

That entire arrangement determines whether intelligence becomes value.

This is why a less capable model inside a well-designed system can outperform a frontier model dropped into a broken workflow.

The system determines whether the intelligence travels.

* * *

## The jobs will move too

Once the arrangement of work becomes easier to change, predicting the effect on jobs becomes much harder.

The usual debate treats an occupation as a list of tasks. AI takes some tasks, humans keep the rest, and then we count what remains.

But the tasks themselves came from the old arrangement.

Change the arrangement, and the job changes with it.

A skill may become more valuable when AI first arrives because someone has to verify the output. A better workflow may later remove most of that verification.

Routine programming may become cheaper while understanding what software should exist becomes more valuable. Junior production work may disappear, only for the institution to discover that the same work was how junior employees developed senior judgment.

A person may stop producing one artifact and become responsible for shaping the system that produces it. A role may become more valuable even while most of its former tasks vanish. Another role may remain technically present but lose its real authority.

This is not a clean contest between a person and a machine.

The stations are moving.

* * *

## The human place is not whatever AI leaves behind

The standard future-of-work question is:

What will AI do, and what will remain for humans?

That question assumes a fixed factory floor. The model occupies one station, the human retreats to another, and the process continues until we find the final set of tasks machines cannot perform.

But when the floor can move, the human role is not merely the residue.

It is partly a design decision.

Where does human judgment matter? Where is someone close enough to the terrain to recognize that the frame is wrong? Where do relationships change the outcome? Where is legitimate authority required, and where must someone accept responsibility for consequences?

Where should a person define the objective rather than merely inspect the output? Where can machine interpretation help? Where should a repeated decision become a rule? Where should the system stop because the ambiguity is consequential?

A human can remain “in the loop” and still have no meaningful control. They may become a rubber stamp, a liability sink, or an approver asked to inspect more machine output than anyone could seriously examine.

That is not a durable human role.

It is responsibility without agency.

The point is not to preserve a human checkpoint everywhere. It is to place people where a real human function exists.

* * *

## Stop automating the diagram

The first generation of organizational AI usually begins with a process map.

Here are the current steps. Here are the current roles. Here are the current systems.

Where can we insert AI?

That question can produce real gains. Some inherited tasks should simply become faster. But it cannot produce the deeper transformation because it treats the current process as the starting truth.

The diagram is not the truth.

It is a fossil record.

It records old software limitations, old communication costs, old organizational boundaries, and old assumptions about where intelligence had to live.

The more important questions begin one level above it.

What outcome are we actually trying to produce? Why does this step exist? Why does this person perform it? Why does the work stop here, and why is this document the output?

Which constraints are real and which are inherited? Which decisions require judgment? Which transformations should always happen the same way? What information needs to become authoritative? What can be deleted instead of automated?

That is the difference between adding AI to a workflow and redesigning the production function.

One makes the old factory faster.

The other asks what factory we would build now.

* * *

## The danger is not only moving too slowly

None of this means every organization should rebuild every process tomorrow.

Cheap software can still be bad software. A local tool can create security, maintenance, accessibility, interoperability, or governance problems. An inherited control may contain a lesson the new designer does not yet understand, and a workflow may look inefficient because the person examining it cannot see the failure it prevents.

Moving machinery without understanding the factory can be as destructive as refusing to move it.

But those are reasons to redesign carefully. They are not reasons to pretend the floor is fixed.

The organizations that capture the deeper gains will not merely be the ones with access to the strongest model. Everyone will have models.

They will not permanently separate themselves through one impressive agent or one clever workflow. Those will spread too.

The durable capability will be the ability to repeatedly examine how work is arranged and rebuild it around what is now possible: to know when to use a model, when to use a rule, where a human should decide, what information must persist, where authority belongs, and which inherited step can disappear.

Then to do it again when the relative capabilities change.

That is a different kind of institutional competence. It is not the possession of one machine.

It is the ability to keep moving the machinery.

* * *

AI did not merely give the knowledge-work factory a faster worker.

It introduced a new source of cognition, made custom machinery dramatically cheaper to build, gave that cognition a role in designing the machinery, and lowered the cost of rearranging the line around the actual purpose of the work.

The production function is no longer something we merely inherit and operate inside.

It is becoming something we can write.

The shaft is gone.

Where the machines go is now ours to decide.
