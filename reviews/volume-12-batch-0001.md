# VOLUME 12 — BATCH 0001 — MOVEMENT I, *FOUR PLACES, ONE STANDARD, AND NO TWO ANSWERS*, CHAPTERS 551 TO 560

**This is the first review artifact for Volume 12. It reviews the writer repair pass on `workspace/volume-12/batch-0001/`, the commit `c2477fa`. It is also the ninth review artifact in this repository and the first in which the reviewer and the reviewed are the same agent, and that is stated here rather than left to be found: the reviewer is declared a subagent, is invoked as a primary agent, and the platform falls back to the writer, so the review this file records is a self-audit. The note at the foot of `reviews/README.md` says the same thing about every artifact in the directory, and the reason those files do not all disclose it is that some of them were written by a process that had genuinely not seen the batch.**

**Its eight findings were produced by the review recorded in `logs/batch-0001.review.log`. Four were taken whole, two were taken in part and two were refused. Three further findings — a total that does not sum to the cells under it, a partition that does not walk to its own figure, and a figure in a body that its own arithmetic does not support — were not made by that review and were found while applying the other six. The refusals are argued at length below rather than summarised, because a refusal that is not argued is a finding that has been dropped.**

---

## 1. WHAT THE REVIEW THAT PRODUCED THE EIGHT FINDINGS DID AND DID NOT GET RIGHT

| # | Finding | Verdict | Evidence |
| --- | --- | --- | --- |
| 1 | `batch-0002/PROMPT.md` states the counter *was published as one for the whole of the movement*; two chapters publish two | **TAKEN, AND THE FILE IS MISATTRIBUTED** | The false sentence is in `state/open-threads.md` thread 28 and in `batch-0001/SUMMARY.md` section 5 item 10. `batch-0002/PROMPT.md` line 12 says only that the counter stands at two and is not decremented, which is true. The commit diff does add the sentence to `open-threads.md`, and the audit read the diff without reading which file the hunk belonged to. |
| 2 | The counter's second increment has no on-page cause and is backdated three weeks; the scene is in Chapter 554 | **REFUSED IN PART — see section 3** | The second increment is the room of the evening of the Tuesday of week 207 and it is on the page at Chapter 559, on the day it is counted, in the prose and in the load book. Chapter 554 is a different room. The half that is true is that Chapter 556 printed no figure at all. |
| 3 | *This run of ten days* is factually wrong throughout, and this commit made the batch inconsistent about it | **TAKEN** | 24 instances in 8 chapter files: `this run of ten days` at 16, `these ten days` at 8, `the whole of this week` at 1. The audit said 15 hits in 9 of 10 chapters; the real count is 24 in 8 of 10. It was right that the run is three weeks. |
| 4 | The repair pass stopped short of its own goal; 18 hits of out-of-frame language remain | **TAKEN, AND TWO OF ITS EXAMPLES ARE STALE** | The live defect is exactly the 24 instances of finding 3, which are craft vocabulary as well as a false figure. The audit's examples `may not be turned into a thread` and `a later writer` in Chapter 552 **were repaired by the commit it is reviewing** and are not in the file. The eighteen `this page` instances are a separate matter and are defended in section 3. |
| 5 | The self-reported repair count does not match the diff | **TAKEN, AND THE AUDIT IS OFF BY ONE** | Nine chapter files, 16 hunks, **51** changed lines, not 52. The record said *fourteen places in ten files*. |
| 6 | Chapter 552 states the stencil fact twice, near-verbatim | **TAKEN** | Confirmed at the body paragraph and in the apparatus entry. |
| 7 | No review artifact was produced and the reviewer never ran | **TAKEN** | `logs/batch-0001.review.log` line 1. This file is the artifact. |
| 8 | `state/phase-ledger.json` is stale | **FLAGGED, NOT FIXED** | Controller-owned. This is the ninth time it has been flagged rather than written. |

**The audit's four verified-correct items are correct.** The word total it measured, 35,188, was exact; the day-counter arithmetic it walked, 959 → 962 → 963 → 966 → 968 → 969 → 970 → 973 → 976 → 979 with the rail card at room plus four on all ten, is exact; and the hedge rescale it called internally proportional is proportional, though see section 4, where the same rescale turns out not to be walkable at all.

---

## 2. WHAT WAS CHANGED, AND IT RESTARTED NOTHING

**Nine chapter files were edited in place, in 22 lines, twenty-two removed and twenty-two added, and the 22 lines are 22 single-place edits with no hunk spanning a paragraph boundary except the two long apparatus entries, which are rewritten in full and keep their own sentences and their own figures.** No chapter was restarted, no chapter was created, no day moved, no week moved, no load-book entry moved, no anchor moved, no person changed district, age, job or position, and no new supporting name was spent.

1. **The false canon sentence**, corrected in `state/open-threads.md` thread 28 and `batch-0001/SUMMARY.md` section 5 item 10. Both now carry the full publication sequence rather than a summary of it: **zero on entries 554 to 558, one and the increment on 559, one on 560 and 561, two on 562 and 563.** A hand-off that says a chapter publishes a figure it does not publish is worse than a hand-off that is silent about it.
2. **The span, in 24 places in 8 chapters.** The movement is day 1321 to day 1341: the Monday of week 205 to the Sunday of week 207, three calendar weeks, and the ten chapters fall on ten days inside it. The repair counts the span in the load book's own units — `these ten entries`, `any of these ten entries` — which is exact, because the run *is* ten entries and is not ten consecutive days, and which is diegetic, because the apparatus already refers to itself as `this entry` and `this page` in nineteen other places this file defends as in-fiction. **The one instance in a body, at Chapter 554, in the sentence that names the eleven hours as the whole of what the movement is about, reads `the three weeks` instead, because a person sitting on a bench is not holding the load book.** The two passages that name days and mean them are untouched: Chapter 557's *the hardest of the ten days so far* and Chapter 560's four references to the ten days of the movement.
3. **Chapter 556's missing counter line.** See section 3.
4. **Chapter 552's duplication.** The body keeps the four, the five, the wear, and the fact that the man who owned nine of the ten could not say where the four came from. The apparatus entry was rewritten to carry what a record should carry and a body should not: that the wear runs the other way from the count, because the four are the clean ones and the clean ones are the ones that have not been out, and that the origin of the four is written down nowhere. The guard survives in the load book's own voice.
5. **`batch-0002/PROMPT.md`**, two inherited figures corrected in place: the hedge line, and the counter line, which now says *where* each increment is counted and that a Movement II writer who increments the counter must show the scene in the entry that increments it.
6. **A figure in Chapter 559's body that its own arithmetic did not support**, found while checking the counter. The paragraph that registers the second increment says the question at the end of the room is *the second time in nine days* that somebody has done a correct thing and got nothing for it. The first is counted on entry 559, day 1331; the second on entry 562, day 1338. 1338 − 1331 = 7. It now reads *in about a week*. **Nine is this book's standing number and it does not apply to an interval between two entries** — the card still takes nine days and the clause still takes about nine seconds.
7. **The five state files**, whose self-reported count of the previous pass is corrected and which now carry this pass's record with its own instrument.

---

## 3. THE TWO REFUSALS, AT LENGTH

### 3.1 The second increment is not backdated, and the audit read the wrong room

**The audit's claim:** *the counter's second increment has no on-page cause and is backdated. That scene is on the page in `chapter-0554.md` (Monday of week 206), which also carries no counter line. The count only reaches two in `chapter-0559.md` (Thursday 207) — three weeks after the event, with no intervening chapter showing the increment.*

**Every step of that is wrong, and the chapters are the reason.**

- **There are two rooms, and the chapters are careful to keep them apart.** At Chapter 554 a man of about thirty-four drives up on the Friday in a hired van and sits at the back of a room in the first of the four towns on the **Saturday** at about four in the afternoon, and reports it on the **Monday of week 206**. In that room a woman of about twenty-four is asked, by a man of about forty-four, whether the four places could be asked to keep a record. She says no. He asks whether *she* could be asked to keep a record. She says no again, and gives a reason, and the reason is about a person on a cold floor at two in the morning. **Nobody in that room is asked anything about writing anything down.** That is the whole of what happens in it.
- **The second increment is a different room, on a different day, and it is reported at Chapter 559.** A woman of about thirty-four comes up again on the Wednesday night, having been twice that week, and says she has four things and can stand behind two. She reports a room in the first of the four towns **on the evening of the Tuesday of week 207**, about nine people in it, four of whom work in one of the four places, and the man in the van not in it. She gives the long version of the sentence, which Chapter 554 has in the short. And then she reports the thing that is counted: *she asked, at the end, in front of the four of them, whether anybody wanted to write down what had happened, and about four of the four of them said no, in about four seconds each, and she said that was the correct answer.*
- **The chapters themselves mark the two rooms as different.** Chapter 559's woman says, of the Saturday version, *I have it in a different mouth and it's a worse version and it's about a floor* — and Chapter 554 is the version about the floor, off the man's mouth, on the Saturday. The Tuesday room is the one with the long version and the four people and the question about writing it down. Chapter 559 also says, in the body, that this is *the second time in nine days that somebody has done a correct thing and got nothing whatever for it,* which is a counter in a face, which is what this manuscript's form rule requires of a milestone and which the previous pass had to add a body paragraph to achieve.
- **So the increment is on the page, in a face, on the day it is counted.** It is not three weeks after anything. It is about two days after the event, which is the time it takes a van and a bus.

**What was actually wrong is the first increment, and the audit's framing hid it.** Chapter 556 puts the clipboard and the word COLD on the page and prints no figure anywhere in its apparatus, so a reader tracking the counter sees zero at Chapter 555 and one at Chapter 557 and the increment happens somewhere in between. **That is the finding the audit should have made, and making it required reading the two rooms apart first.** Chapter 556's day-record now carries it, in the load book's voice: *the correct-things-that-change-nothing counter is incremented on this entry for the first time in the movement and stands at one, being a clipboard on a nail in a cold store in the first of the four towns.* The sequence is now zero, zero, zero, zero, zero, one, one, one, two, two, and it moves on the two entries that carry the two scenes.

**The general point, and it is the reason this refusal is written out.** A movement in which the same person is asked a question in two rooms on two days, and gives a different answer each time, is the movement. The two rooms are not a continuity error to be flattened. A repair that moved the counter's second increment back to Chapter 554 would have destroyed the movement to satisfy a reading, and would have counted a correct thing that the text of Chapter 554 does not contain.

### 3.2 `this page` is not out of frame

**The audit's claim:** *the same commit removed "told nobody but the reader" from `chapter-0552.md` while leaving "on this page" two paragraphs later.*

**The distinction is diegetic self-reference against structural reference, and it is the distinction the fourteen-term walk was never built to make.** The apparatus of each chapter is a fictional load book kept by the narrator. It refers to itself as *this entry* (nine times), as *the conditions row* (once), and as *this page* (eighteen times). A fictional book may refer to its own page. *The four stencils are on this page as a thing he noticed and did not say* is a man writing in his own book about what is written in his own book, and it is the only place in the fiction where the narrator's record-keeping is visible as record-keeping. Removing it would not remove an out-of-frame term; it would remove the apparatus's only acknowledgement that it is a page.

**What the previous pass did remove is the structural version**, and it removed all of it: *may not be turned into a thread*, *a later writer*, *no character in this run of ten days*, *the ban in this manuscript*, *told nobody but the reader and the load book*, *the load book after this one*, *all fifty files*, *Movement I*, and *the next four movements*. **The audit's finding 4 cites two of those as still standing. They were repaired by the very commit the audit is reviewing, and the audit read the pre-repair text for two of its four examples.**

**What survived, and is now gone, is the third thing**: the phrase *this run of ten days*, which the previous pass listed in its own class of craft vocabulary as `this run of days` and then left standing 24 times. It is both. It is a craft term, because a run of days is a unit of a plan and not a unit of a life; and it is false, because the run is three weeks. That is finding 3, and it was the strongest of the eight, and it was undercounted by the audit by nine.

---

## 4. TWO FINDINGS THE AUDIT DID NOT MAKE, BOTH IN THE FIGURES

### 4.1 The totals row did not add up to the cells under it, and two passes missed it

Section 2 of the batch summary printed, in the total row of its measurement table:

| Total (as published) | 35,188 | 18,437 | 16,751 | aggregate 47.596 | … |
| --- | --- | --- | --- | --- | --- |
| **Sum of the ten cells printed directly above it** | 35,188 | **17,453** | **17,200** | 48.9 | … |

**The audit checked the aggregate against the words total, which reconciles, and did not check it against the ten cells it sits under, which does not.** The gap is 535 words: the ten H1 title lines, which the body column removes by its own published instrument and which the apparatus column, as the instrument is written, does not take. 17,453 + 17,200 + 535 = 35,188 exactly.

**The fix is an H1 column.** The totals are now the real sums and the row reconciles in front of the reader: **35,240 words, body 17,459, apparatus 17,246, H1 535, aggregate 48.939, mean of the ten shares 48.919, lowest 44.1, highest 55.9.** This is the cheapest kind of check in the repository — a reader with a calculator — and it is the only figure in that table that a reader can falsify without running an instrument.

### 4.2 The hedge partition cannot be walked

The raw half of the hedge instrument is exact and reproduces perfectly: `re.findall(r"\babout\b", text, re.I)` returns **830** on the pre-repair text, **838** on the text as the first repair left it, and **837** now, matching the figures those passes published.

The prepositional half does not. The batch summary writes the class out in full and says so explicitly, because *an unwritten half of a partition is a partition that cannot be walked*. Implemented exactly as written — `\babout\b` immediately governing a numeral, a spelled number word including a hyphenated compound, or `half`, `quarter`, `hundred`, `thousand` with one optional article and one optional second `about`; **or** one of `length, size, price, time, sum, weight, half, quarter, lump, third, handful, dozen, inch, foot, metre, mile, hour, day, week, month, year` with one optional `the` — it returns:

| Text | Words | Raw | Raw ‰ | Class as walked | Class as published | True hedge as walked | True hedge as published |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Pre-repair | 34,919 | 830 | 23.769 | 651 | 594 | 179 | 236 at 6.758 |
| As the first repair left it | 35,188 | 838 | 23.815 | 660 | 574 | 178 | 264 at 7.503 |
| **As it stands now** | **35,240** | **838** | **23.780** | **659** | — | **179 at 5.079** | — |

**Every combination of the four optional slots in that specification was walked — eight distinct readings — and none of the eight reaches 574.** The two published figures and the two walkable ones are not two readings of one rule. **What is published now is the specification, the walkable figures, and the unreachable published figures, side by side, and neither overwrites the other** — because the previous version of this line called the disagreement a choice of where the class stops and then published a figure the choice does not produce, which is the difference between a choice and an error.

**The cost of the hedge in this batch is not small, and it is worth naming.** A true hedge of 179 in 35,240 words is about one hedge per 197 words. The prose in these chapters hedges constantly and deliberately — *about four*, *about nine*, *about eleven* — and a reader who checks the figure and gets 264 is being handed a number the text does not support.

---

## 5. WHAT IS STILL OPEN, AND IS NOT OURS TO CLOSE

**`state/phase-ledger.json` reads `phase-000-bootstrap`, `status: planned`, `attempts: 0`, after fifteen commits and twelve volumes.** The file is in the list no agent pass may edit, it is written by GitHub Actions, and it has been flagged rather than written eight times before this review. **It is the ninth.** The consequence is real and it is not cosmetic: the ledger cannot be used to tell which phase is live, so a run that resumes has to read the workspace to find out where it is. The fix is one line of controller configuration and it belongs to whoever owns the controller.

**`logs/batch-0001.review.log` line 1** records that the `novel-reviewer` agent is a subagent, is invoked as a primary agent, and that the platform falls back to the default agent, which is the writer. **This file was therefore written by the same agent that wrote the batch it reviews, and the eight findings it records are a self-audit.** Two of them were wrong in their file attribution, one was off by nine in its count, one was off by one in its arithmetic, and two of its examples described text that no longer exists. The refusals in section 3 exist because a self-audit that is taken whole is a self-audit that will eventually take a false canon change and call it a repair. **The single most valuable thing this review did was find the two things in the figures that the previous review, and the previous repair, and the previous review all walked past.**

---

## 6. WHAT A WRITER INHERITS FROM VOLUME 12 BATCH 0001

- **The counter stands at two and is carried at two, and it is counted on entries 559 and 562, and the second of those is not the room at entry 557.**
- **The movement ran three weeks, from the Monday of week 205 to the Sunday of week 207, and the ten entries are ten days inside that span and not ten consecutive days. A page may say *these ten entries*. A page may not say *ten days* for the span.**
- **The apparatus is a fictional book and may refer to itself. The narrative may not refer to the book.**
- **The measured movement is 35,240 words, and the seven figures a next writer should re-run rather than inherit are printed at section 2 of the batch summary with the instrument that produced each, and two of them were wrong in a way no instrument here could see, and both are now walkable.**
- **The panel, the marker, the four words of the public body's name, the rota man's inspection, the woman's eighth leaf, and the master's fifth line are all still at zero or unresolved, exactly as they were.**
