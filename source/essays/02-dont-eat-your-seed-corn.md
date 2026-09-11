<!-- SOURCE-PROVENANCE
Imported from Google Drive Markdown file "dont-eat-your-seed-corn-v8-1.md" on 2026-09-11.
Drive file id: 1zg2yX8eedwukMYkgAe6mhi_Z4jFXlWg7
-->

# Don't Eat Your Seed Corn

Every farmer who lasted more than two seasons learned the same lesson. When winter ran long, you could grind the seed corn into flour. It would feed everyone better right now. The trade was: a fuller belly today, no harvest next year.

We're about to make the opposite trade, at scale, across the entire knowledge economy. And almost nobody making the decision can see what they're trading away.

Here's the trade. To see it clearly, you have to be specific about what the work actually looks like.

---

Most AI conversations assume one of two shapes for human-AI work.

The first is tool-use. Humans drive, AI amplifies — like a faster typewriter, a smarter spreadsheet. The human is in the cockpit the whole time; AI just makes the work go faster.

The second is agentic. AI does the work autonomously. Humans review outputs at checkpoints, approve or reject, hand AI the next task. The human is a supervisor; AI is the worker.

Neither shape uses humans for what humans actually bring. Tool-use underuses what AI can now do — most of the entry-level work AI can handle outright, not just speed up. Agentic pretends humans can supervise work they don't actually understand the texture of — review outputs all day, sure, but how would you know which ones are subtly wrong if you've never sat in the rooms where they get acted on?

I argued for a different shape in *We Were Portugal All Along* a few weeks ago — that humans hold something AI can't get from training data alone, namely the judgment built by years of being in the building. This piece is about the workflow shape that follows from that argument, and the training problem hidden inside it.

The shape is a sandwich.

---

AI sits at the front end. It pulls the relevant documents. It summarizes the precedents. It drafts the first-pass analysis. It surfaces the data. What used to take a junior analyst three weeks now takes a model thirty minutes.

A human sits in the middle. The human reads what AI produced and checks it against what they actually know — about the institution, the people in the room, the political third rails, the unwritten rules. They catch the technically-right-but-situationally-wrong draft. They notice the precedent AI didn't cite because it didn't know which committee chair cares about it. They see the missing context that would change the whole frame. They decide what to revise, what to dig deeper on, what to throw out.

AI sits at the back end. It turns the human's judgment into polished output — final memos, clean analyses, formatted presentations. The human's call gets executed at machine speed.

AI in. Human in the middle. AI out.

The reason for this shape and not the other ones: the human in the middle is doing the only thing in the pipeline AI structurally can't do. Front-end sourcing is parallelizable — a model does it well. Back-end formatting is parallelizable — a model does it well. The middle is where the work is *not* parallelizable, because the judgment depends on context the model doesn't have access to. The context lives in the human's head, accumulated over years of being where AI couldn't be. The human is the only available holder of that input.

I've been calling the person in the middle a *middle-seat operator*. The work itself is harder to name in one word — sense-making, judgment, calibration, knowing what good looks like in your specific institution. Whatever you call it, it's the part of the work that doesn't transfer to a model.

What this actually looks like in practice — the interfaces that support the middle seat, where the seams between AI and human really live, what infrastructure has to exist for the workflow to work at all — is its own piece. I'll come back to it. For now, what matters is the shape, and the training problem hidden inside it.

---

Here's the part of this story I'm worried about.

The middle-seat operator doesn't appear fully formed in a 24-year-old. The judgment that makes them valuable in the middle seat gets built slowly — by spending years doing the front-end work themselves, before AI existed to do it. You learn how your office actually works by pulling the docs, drafting the memos, processing the data, over and over, until the patterns settle underneath the explicit work.

The front-end work was the vehicle. The middle-seat judgment was what you were actually accumulating.

That front-end work is what AI now does.

Automate all of it, and you've severed the mechanism that produces middle-seat operators. You've eaten the seed corn. And there is no next year.

I called this the apprenticeship paradox in Portugal and said I'd come back to it. This is the coming back.

---

I don't think this is hopeless. Some kind of training architecture has to emerge in the new environment, and figuring out what actually works is going to take real effort.

The general shape is clearer than the specifics. Whatever the architecture looks like, it has to do three things. Get juniors enough reps doing the actual cognitive work — not AI-assisted work, but the moves underneath. Put juniors in proximity to seniors doing live work, so the implicit patterns can transfer the way they always have, through exposure. And eventually attach real stakes to junior output, because judgment doesn't fully form until you've felt the consequences of being wrong.

How exactly that gets implemented — simulation environments, shadowing structures, graduated autonomy, something nobody's thought of yet — is going to vary by industry and institution. Some smart people are going to spend the next decade figuring it out.

Here's what's true regardless of the specifics. Every version of this runs on senior knowledge. You can't grade reps without senior examples. You can't structure exposure without seniors doing the live work to be exposed to. You can't attach stakes safely without seniors reviewing before output ships.

Pull the seniors, and the pipeline collapses.

---

Which is the part most leadership conversations are missing right now.

The seniors who can run this kind of training are a finite resource. They learned the work the old way, before AI was in every workflow. They built their judgment by spending years doing the front-end work themselves. Every year, some of them retire. Every year, the pool gets smaller. There is no second-generation source for what they know — you can't buy it on the market, because the knowledge only exists inside the institution that produced it.

These people are the seed corn. And the clock is running.

Which brings me to the actual failure mode I'm watching for, in real rooms, right now.

---

Here's the scene. A leadership team is looking at their senior analyst payroll. The salaries are not small. AI agents can do a version of the work for ninety percent cheaper. The deck looks beautiful. The board sees savings. And everyone in the room agrees this is what the AI moment requires.

The trade gets made. The seniors are gone by the next quarter.

What actually happens is a double cost. One you can see. One you can't, until it's too late.

The visible cost is drift. The seniors in the middle seat were the active correction mechanism — the people who looked at AI output and said *wait, that's wrong, here's why*. Pull them out, and the AI keeps producing output. The output still looks plausible. The errors are still there. They just accumulate now, until they compound into a failure someone has to explain to the board.

The invisible cost is what we've been talking about. The seniors you just laid off were the entire training pipeline for the next generation. You haven't just cut current capacity. You've foreclosed the mechanism that produces future capacity. Two years out, when you realize you need middle-seat operators, there's nobody inside the building who can train them.

The conversation in the C-suite at that point goes something like: *we need to hire some of these people.* The conversation with the recruiter goes: *they're all working for the competitors who didn't lay theirs off, and they're not coming cheap.*

This isn't cost-cutting. It's eating the seed corn.

And the metaphor isn't decorative. Think about why it's specifically called *seed* corn. It's not generic corn. It's the corn this farm produced from this soil, the seeds that survived this climate and this storm. Plant it next spring and you get a crop adapted to your specific conditions. Buy generic corn from a stranger and you get a crop adapted to someone else's.

Senior knowledge works the same way. It's not generic expertise. It's specifically the knowledge of how *your* institution actually works — who returns calls, which forms matter, where the political third rails are, what the unwritten rules are. You can't buy that on the open market because it doesn't exist on the open market. It only grew in your soil.

And if you eat all of yours, you can't re-grow it.

---

There's a reason this trade keeps getting made. It's not that leaders are stupid. It's that the systems they operate inside reward it.

Quarterly reports favor visible savings. Boards want costs cut. And the seed corn loss — slow, illegible, invisible until next harvest — never hits the spreadsheet at all. So the trade gets made, again and again, with everyone in the room agreeing it's the right call. The savings hit the report. The liquidation of the future doesn't.

---

So. Three calls to action. Three audiences. Same clock running, from different ends.

**If you're leading an organization,** the first thing is the title. Don't eat your seed corn. Don't lay off your seniors to bring in agents. The drift will show up. The pipeline will be gone. And in two or three years, you'll be the company calling recruiters at a multiple of what you thought you saved. The companies that kept their seniors will be the ones taking those calls — and setting the price.

The second thing is to actually build the architecture while your seniors are still in the building. Find the people who hold the territory. Find the people who can work the AI. Get the territory holders fluent enough to operate the middle seat themselves. Treat mentorship like the load-bearing infrastructure it actually is, not like an HR initiative. The window is open. The clock is running. Your seniors aren't coming back if you push them out first.

**If you're a knowledge worker,** the highest-leverage role to develop into is the one that can both operate the middle seat and train other people to operate it. Pick a niche. Embrace AI fully. Stay close to the actual work. Learn to teach what you do — because teachable is what makes you valuable in the next decade, and knowledge that isn't taught dies with the person who held it.

That's the role the companies that ate their seed corn will be desperate to buy back — when they realize they can't manufacture middle-seat operators internally, because they laid off the only people who could have trained them. The cost they booked as quarterly savings comes due as your salary.

**If you're early in your career,** here's the part nobody's telling you. Don't choose the job that pays a little more if it's at a company treating you as front-end work waiting to be automated. Choose the job at the company that's actually going to train you. Attach yourself to someone who has the territory. Pick the apprenticeship over the salary bump. You don't have leverage over whether your function gets agentified — that decision gets made in a room you're not in. What you have leverage over is which building you're in when the decision gets made.

---

Some organization is going to build this. They'll get the workflow right. They'll figure out the training architecture. They'll keep their seniors in the building long enough to capture what those seniors know. They'll treat training like real institutional infrastructure. And they'll win the next era of knowledge work.

Most won't.

Most will look at the senior payroll, do the AI math, and ride the savings until the harvest comes up short. By the time they understand what they traded away, the people who knew how to grow it have been gone for years.

But the prize is real. The window is open. The seed corn is still in the granary.

For now.
