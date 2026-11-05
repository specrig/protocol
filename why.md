# Why Rule #11 is written as it is

[agents/rule11.md](agents/rule11.md) says what an agent does; this page says why,
for the people who change it. It is not part of `specrig.md`, so none of it costs
an agent's context.

## What lasts and what compensates

Two kinds of rule live in Rule #11, and they age differently.

**What lasts** holds whoever writes the cases: the delta list, a case verified
against the requirements, a case that reads with the comments closed, one axis of
folding, the negative written, the meaning asserted rather than the representation,
and the surfaces a reviewer checks
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

What the diff must not carry costs a glance at the file list and depends on nobody
having followed any other rule, which is the point of having it: every other rule is
checkable only by someone who read the work.

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

A table earns its place only if its rows can be read. Folding by the letter produced
`| under a locked contract | 2 | locked | -1y | +1m | revoke | suspended |`: a column
for one row, three columns repeating the row's name, two result columns moving as a
pair. Hence one sentence per outline, read aloud. Tables stay, and a matrix of
transitions is what they are for; what goes is the table that needs a legend because
one cell of it matters.

## A specification that reads

The test of a specification is that its owner reads it. Measured on about a thousand
cases written under an earlier text of this rule: 86% carried a comment, 3.6 lines
against 5.2 steps on average, one in five was longer than its case, and no `Feature`
had a description. The owner had stopped reading: an agent read the cases and retold
them, the owner confirmed the retelling, and what was approved was not what runs. That
text asked for it, sending the reason, the meaning of the rows and the excluded
implementation to the comment.

Deleting the comments is not the cure. Moved to a `Rule`, their text repeats the same
facts above the cases, and the situations in them — a second unit rented in advance, a
debt paid off — are the use case the reader is looking for. So the situation stays
with its case, under its title, and the list of implementations goes to the delta list,
where a reviewer judges it. An exclusion can still ask for variation in the data, and
it stops where the reader has to solve the example: that a case discriminates is
shown by a run, not by the shape of its table.

A reader with no context lists every doubt it has, so their number measures nothing:
the form this page argues for drew 49 of them where the old one drew 43. A cold read
is for the wrong retelling and the contradiction, and answering each doubt with prose
is how a file grows a legend. Doubts still go to the human at hand-over: the author who
left a gap is not the one to rule it out.

How an event is written lives in a stack's `describes`, not in Rule #11: a web app's
`When` is a user's action, and its harness delivers nothing.

## Red-green

A production file no case went red on reads as a decision while the suite would
be exactly as green without it, which is worse than no change: the next person to
open the file takes it for approved behaviour.

A `Then` is bound after approval, in red-green. A step that checks the status and
not the body is red before the code and green after it, while the scenario says
more, so "red for its own reason" cannot see it; the list of what each `Then` the
task bound or changed asserts is what lets the human compare the binding with the
text that was approved. A `Then` nobody touched was compared when it was bound.
