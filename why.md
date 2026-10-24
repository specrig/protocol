# Why Rule #11 is written as it is

[agents/rule11.md](agents/rule11.md) says what an agent does; this page says why,
for the people who change it. It is not part of `specrig.md`, so none of it costs
an agent's context.

## What lasts and what compensates

Two kinds of rule live in Rule #11, and they age differently.

**What lasts** holds whoever writes the cases: the delta list, a case verified
against the requirements, one axis of folding, the negative written, the meaning
asserted rather than the representation, and the surfaces a reviewer checks
without trusting the author — the red count equal to the known defects, a case
seen to fail, every production file named by a case, what each `Then` a task bound
or changed asserts, and what the merge request must not carry.

**What compensates** answers how agents fail today: the modes, the stop after
each step, an answer that is not approval. They stay as short as they can, in one
place — Modes — so that they can be cut when they stop paying.

Auto mode is what compensates switched off, for a human who would rather not
switch modes but wants the work done specification first, and reviews the whole
cycle at once. It is not the canonical use: approval comes
after the fact. What lasts stays — the order of the steps, and every surface the
stops would have shown, handed over together — and so do the platform's files,
closed, because an agent that changes what a case may stand in for changes what
every case means. Nothing offers it: a refusal never names it, so it is chosen,
not drifted into.

Where a rule can be a mechanism, it is one. The plugin answers for the paths,
refusing an edit outside the mode before it happens; prose is kept for what no tool
can check, and for agents that run without a plugin, for whom the tables in
`specrig.md` are the only check there is. That is chosen: a stack prints its rules,
and the verdict is drawn by the plugin of each agent, not by a command any agent
could run and none is made to.

## The stops

A stop is where a person changes the answer for the price of a conversation
instead of a rewrite. The gate is rarely skipped by deciding to ignore it: it is
skipped by losing count of which step one is on, and most often through an
answer — "add it", "do B" — that reads like a fresh instruction while it only
settles a row that still has to be written and approved.

Approval is the human switching the mode. That guarantees the order of the steps,
not that anybody read the cases: no protocol can check the reading, and a pipeline
can check that a ticket is linked, not that it was argued.

## The specification

A verdict — ✓, ✗, ? — is the state of a review. A tag carrying it in the
repository stops being true the moment a decision is taken elsewhere, and a stale
one reads as current; a specification is not a task tracker. For the same reason
a case carries its reason and not its history: three dated entries and the reader
works through a history instead of a rule, and the prose stops being read. Who
decided, and when, is in the history and the ticket.

Two cases that differ in one cell, written as prose, read as the same case twice,
and a reviewer spends the attention on telling them apart. Merging cases that
differ in their setup leaves a column empty on most rows: a sparse column means
two questions were forced into one table.

## Red-green

A production file no case went red on reads as a decision while the suite would
be exactly as green without it, which is worse than no change: the next person to
open the file takes it for approved behaviour.

A `Then` is bound after approval, in red-green. A step that checks the status and
not the body is red before the code and green after it, while the scenario says
more, so "red for its own reason" cannot see it; the list of what each `Then` the
task bound or changed asserts is what lets the human compare the binding with the
text that was approved. A `Then` nobody touched was compared when it was bound.
