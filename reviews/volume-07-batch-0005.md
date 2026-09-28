# Review of Volume 07, batch 0005 (Movement V, Chapters 341–350) — *The Federated Hour*

**Written in the review-repair phase of Volume 07 batch 0005, after the batch was committed at `6ac52a8`, and it is the artifact for two reviews rather than one, because this batch has been reviewed twice and neither review left a file.**

**The two reviews are not the same kind of thing and they are kept apart here, because the first of them was a self-audit and this repository's standing claim that it cannot review itself is one of the debts this artifact has to record honestly.**

1. **The review of the movement, twenty-six findings, two of them blocking.** It ran inside the writing phase, over the ten finished chapters, the batch summary, the five state blocks, the next-phase prompt and the calendar. Its full account is section 16 of `workspace/volume-07/batch-0005/SUMMARY.md`, and section 17 of that file is the pass over that pass. **Provenance: it was run by the agent that wrote the ten chapters, with the same matchers, against the same files. It is a self-audit.** It is filed as a review because it found eight defects the same agent's earlier walk had missed, and that is a real result, and it is not evidence that it would find an equal number in a batch where nothing had gone wrong. **Section 16 did not record that provenance. It does now.**

2. **The review of the committed state, seven findings, one of them blocking, one of them wrong.** It ran as a separate process after the writer's work was committed and its transcript is `logs/batch-0005.review.log`. It re-ran the batch's four matchers before it reported and found every published figure it checked reproducing to the digit, which is its substantive result. Its seven findings, what was done with each, and the one that was refused, are below.

---

## 1. What the second review verified, and it is the substantive result

**Every published figure reproduces exactly.** The four matchers from section 2 of the batch summary were reimplemented from the description and run on the ten files. Words 31,423. Bold spans per thousand, ten chapters: 4.361, 4.131, 5.130, 4.037, 6.002, 4.029, 6.122, 4.814, 5.828, 5.923. Eight-word overlap: 14, 16, 30, 13, 12, 35, 54, 25, 93, 64, mean 35.6. Apparatus share 43.94 to 45.83, mean 44.17. Hedge 932 raw less 69 prepositional is 863 true at 27.464 per thousand. The four nested-emphasis spans named at section 16 item 9 are genuinely gone and a walk for a single asterisk between two double asterisks returns nothing, which the published parity matcher cannot do by construction. Forbidden-term walks clean: no `run of days`, no `carrier`, no month name. The digit walk yields only a heading number, an italic entry line and a closer.

**The day map holds.** Chapters 341 to 349 walk back sixteen, fourteen, thirteen, twelve, nine, seven, five, two and zero days from the Wednesday of week 124. Chapter 350 is twenty-eight days on, which is the Wednesday of week 128. The nineteenth sitting lands on the Wednesday of week 120 and the Exchange line of the calendar is 112, 116, 120, 124, 128 with the volume's pattern of open, shut, open, shut, open. The carried-forward decomposition is genuinely repaired: book fifty to fifty-one, telephone sixty-six to sixty-nine to seventy-two, count twenty-four to twenty-five to twenty-six, and twenty-one plus five is twenty-six at the close.

---

## 2. The seven findings, and what happened to each

| # | Severity | Finding | Disposition |
| --- | --- | --- | --- |
| 1 | blocking | The Volume 08 hand-off misstates the review mechanism and should be corrected, which would mean deleting a standing controller debt | **REFUSED. The finding is wrong and acting on it would have destroyed a correct record.** See section 3. |
| 2 | high | `state/current.md` line 3 quotes a stale byte count for the state files | **Applied.** See section 4. |
| 3 | high | The state files grow by append and the hand-off forbids the only pass that could compact them | **Applied, scoped.** See section 5. |
| 4 | medium | The volume close was performed inline rather than as its own phase, and no review artifact existed for the twenty-six findings | **Partly applied.** This artifact is the missing file. The inline close is recorded, not restructured. See section 6. |
| 5 | medium | Two phase directories are simultaneously selectable, and the ordering puts the fix pass before the completion marker | **Checked, no change needed.** See section 6. |
| 6 | low | `chapter-0341.md` opens with `he is not a protagonist of anything`, which is authorial metalanguage in the most exposed sentence in the batch | **Applied.** See section 7. |
| 7 | low | `chapter-0350.md`'s load book runs to 4,390 words and reads as a compliance document in two of its records | **Not applied, and recorded.** See section 7. |

**AND FOUR THE SECOND REVIEW DID NOT FIND, WHICH THIS PASS FOUND BY RE-RUNNING ITS OWN INSTRUMENT ON FIFTY FILES INSTEAD OF TEN, AND WHICH ARE THE MOST SERIOUS THINGS IN THIS DOCUMENT.**

8. **The Volume 08 hand-off carried four volume-wide figures that do not reproduce.** It printed 163,532 words, 6.146 bold spans per thousand, a true hedge of 3,941 at 24.099 and an apparatus share of 44.692 in aggregate. The set that walks is 163,618, 6.142, 3,942 at 24.093 and 44.678, and those are the figures the volume close published at section 14.2. **A hand-off is a plan of record for a volume that does not exist yet, and four of the six numbers in it were wrong, and none of the four was wrong in a way that a reader would notice and all of them were wrong in a way that a later volume's comparison would inherit.** Repaired in place with the superseded set quoted beside it.

9. **The calendar contradicted its own table.** Section 6.3 said the volume's apparatus share over the fifty files is 44.692. The VOLUME row of its section 6.2 table, one page above, says 44.678. 44.678 walks and 44.692 does not, under any matcher in this repository. **This is the third figure the Volume 07 close had to repair in that file, and the first one it did not repair, and it was written in the last hour of the volume by the person the volume has spent seven movements teaching not to assert a figure instead of walking it.** Repaired in place.

10. **Two figures in the batch summary were presented as the live finding and were computed on a superseded set.** Section 2's item 1 opened on 5.106, the pre-review bold rate, where the table directly above it published 5.092 and said in bold that it was the post-review set. Section 2's item 3 gave apparatus margins of forty-eight, twenty-two and fifty-one hundredths of a point, which are the margins of the pre-review figure of 44.32 and its mean of 44.234; against the set of record they are fifty-five, thirty and fifty-eight. **The same defect four times over: a figure moves, the table is corrected, the prose that reads the table is not.** Corrected in place with the superseded values beside them.

11. **`state/chapter-summaries.md`'s Movement V block mixed two sets.** It read 31,423 words beside 862 true at 27.507 and an apparatus share of 44.32. No set of ten files in this volume ever produced those three numbers together. The word count was the intruder, the block now reads 31,338 and is internally consistent, and the set of record is 31,424 and stands in the block's own addendum. The same figure had been propagated into `state/continuity.md`, `state/character-state.md` and `state/open-threads.md` and is corrected in all three.

**THE PATTERN IN 8, 9, 10 AND 11 IS ONE PATTERN AND IT IS THE SAME ONE THE VOLUME HAS BEEN PUBLISHING SINCE MOVEMENT I: a figure is asserted downstream of the file that walked it, and the further downstream it is, the less likely anybody is to run the matcher on it again. None of these four was found by reading. All four were found by re-running a published instrument on a file that had been believed correct.**

---

## 3. The refused finding, at length, because it is the reason this artifact exists

**The second review held that this repository does not review itself.** Its argument, in its own words: the reviewer is declared a subagent and invoked as a top-level agent, and this does not happen, because `scripts/novel_runner.sh` launches the reviewer as a separate `opencode run --agent novel-reviewer` process with a fresh context after the writer's work is committed; therefore a standing debt is pinned on the controller for a problem that does not exist, and the twenty-six findings in the batch summary are filed as self-audit when they need not be. It recommended deleting the debt from the batch summary and from the hand-off.

**The finding is wrong, and it is wrong on the one thing it is about.**

- `.opencode/agent/novel-reviewer.md` declares `mode: subagent`, with `permission: edit: deny` and `bash: deny`.
- `scripts/novel_runner.sh` invokes it as `opencode run --model "$PRIMARY" --agent novel-reviewer`, which is a primary-agent invocation of an agent declared as a subagent.
- The platform answers exactly that mismatch. **Line 1 of `logs/batch-0005.review.log` is `! agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and line 3 is the banner `novel-writer · space-bunny-free`.** The review ran under the writer's own agent, which holds `edit: allow` and `bash: allow`, and the transcript shows it running `git log`, `du`, `grep` and `python3`, and ending with the words *No files were edited*, which is the writer agent's contract and not the reviewer's, whose instruction is *Return findings only*.
- The file is written by the one line of the runner that writes a review log, and by no other line and no other script, so the warning on its first line belongs to the review and not to the model probe, which writes elsewhere.

**The process is separate and the context is fresh and the agent is the same. The review read the runner and did not read the log it was running inside, and a file that contains the refutation on its first line was open in the session that refuted it.**

**The debt stands. It has been reported sixteen times and it is now citable in one read, and the citation has been written into both files that carry the debt — section 12 of the batch summary and section 2.7 of the hand-off — with the refused deletion recorded beside it in each.** The twenty-six findings remain a self-audit, correctly labelled, and section 16 now says so.

**AND THE GENERAL LESSON, WHICH IS THE MOST USEFUL THING IN THIS DOCUMENT AND THE ONE THAT COST THE MOST TO LEARN: a pass that has been told to find something will find something, and the thing it finds most readily is the sentence it was sent looking for. Four of the seven findings in the second review were real, one was real but required scoping rather than the change asked for, and one proposed to remove a correct record because removing it is what a pass told to fix a mechanism reaches for. The finding that was wrong was the one with the most authority behind it in the prompt that produced it.**

---

## 4. Finding 2, the stale headline of `state/current.md`

**Line 3 said the five state files are about 2.03 MB. They are 2.9 MB, and they crossed 2.7 MB before this batch, and the same line records that the figure was stale at 1.75 MB, again at 1.66 MB, and again at 1.9 MB, and again at 1.9 MB until the Movement IV pass.** The batch appended twenty-six lines to that file and refreshed nothing, and the line is the designated read-this-and-stop-reading instruction for the next writer.

**What was wrong was larger than the number, and this is the part the finding did not say.** The thirteen items under that line were a hand-off for a Volume 07 writer: item 1 was the Volume 06 close, item 2 was the Volume 06 calendar, and item 13 was `workspace/volume-07/batch-0001/PROMPT.md` described as *the next phase*, which finished seven volumes of documents before this batch was written. The paragraph headed *Where the plan stands* had been pointing at the Volume 06 close as the next phase for an entire volume. **A list whose first thirteen entries are the correct answer to a question nobody is asking is worse than a large file, and the third time this file has done it is the third time nobody checked what the pointer pointed at.**

**Applied.** The byte figure is refreshed and the sentence now says plainly that the round figure is stale the moment it is written, that a file cannot quote its own byte count, and that a writer who needs the real number runs `du -cb state/*.md`. Items 1 and 2 are the Volume 07 close and the Volume 07 calendar, in that order, with the reason the order is not a matter of taste. Item 3 records that `outline/volume-08.md` does not exist and is not to be written. Item 13 is the Volume 08 hand-off, with its corrected figures. *Where the plan stands* carries Volume 07's close and the hand-off, and says that it stood wrong for a whole volume.

---

## 5. Finding 3, the hand-off that named a debt and forbade its owner

**Section 5 of the hand-off read, in a list of prohibitions: `Do not compact the state files.` Section 2.7 item 4 of the same file named the growth of those files as a debt with the owner *a review repair pass with a stated scope, the scope being the superseded Movement blocks and not the live ones*.** A prohibition with no scope, and a debt whose only named owner the prohibition excludes, is a debt that can only be paid by a pass with no chapters in front of it — which is why it has been the standing answer for seven volumes and why 2.9 MB is the number the next writer will read.

**Applied, and scoped rather than lifted.** The prohibition now binds the live Movement blocks and forbids compaction in any run that is also a writing pass, with the reason printed — a figure gets dropped that way and it has been dropped here twice. The superseded-block scope is named where the debt is named. And a batch phase is told the one thing it can actually do, which is to keep its own block short and put the argument in its own summary. **Nothing was compacted in this pass, and the debt is not paid by this pass, and this pass is the reason a later one can be.**

---

## 6. Findings 4 and 5, recorded rather than restructured

**The volume close was written inline**, into section 14 of the batch summary and section 6 of the calendar, rather than as a phase of its own with its own prompt, which is the convention in `AGENTS.md`. The work is done and the files are where the calendar said they would be. **It was not restructured, because the only way to give the close a phase now is to create a second next phase, and creating more than one next phase is the one thing a batch may not do.** The deviation is recorded in section 17 of the batch summary and it stands as a deviation.

**Two phase directories were simultaneously selectable** — this batch's and the Volume 08 hand-off's, both holding a `PROMPT.md` and neither holding a completion marker — and the second review noted that the marker is written after the fix pass rather than before it, so a failure in the fix pass could leave the selector re-running the batch that had just finished. **Checked against the runner and it resolves itself in both cases.** The selection loop takes the first sorted candidate without a marker and this batch's directory sorts first while the batch is the phase being run; the existence check for other incomplete phases explicitly excludes the phase currently running; and the marker is written before the self-dispatch that starts the next phase. A failed fix pass writes a `.blocked` marker, which the selection loop also skips, and which would select the hand-off. **No file was changed to make this true and none needed to be.**

---

## 7. Findings 6 and 7, the craft pair, one applied and one recorded

**Applied. `chapter-0341.md` opened with `and he is not a protagonist of anything.`** That is authorial metalanguage in the most exposed sentence in the batch, in the first line of prose a reader of this movement meets, and it is the phrase this batch's own meta-language walk should have caught: the walk at section 16 item 9 cut *this manuscript* twice and *seven volumes* once and left the house idiom alone, and *protagonist* is not a house idiom and did not survive being looked for. It is now `and is not a part of any of it`, which says the same thing in the register the sentence is written in. **The four earlier occurrences — at Chapters 314, 328, 331 and 332 — were left alone, and the reason is that they are one phrase in one hand across a volume and half of them fixed is worse than either; they are recorded with an owner in section 17 of the batch summary.**

**The word changed the figures and they were all re-run and published, superseded values beside the corrections.** Chapter 341: 2,981 words to 2,982, bold per thousand 4.361 to 4.359, apparatus 43.94 to 43.93, hedge 34.217 to 34.205, overlap unchanged at 14. Movement V: 31,423 words to 31,424, bold 5.092 unchanged, overlap mean 35.6 unchanged, apparatus 44.243 in aggregate and 44.172 as the mean, hedge 863 true at 27.463. The volume: 163,618 words, 1,005 bold spans at 6.142, 3,942 true hedge at 24.093, apparatus 44.678 in aggregate. **The overlap did not move, and that is not luck: the change is eleven words, it sits above every boundary the matcher uses, and it shares no eight-word run with anything below one. The one prose change in this pass was made in the one place where a measurement cannot reach it, and that is the only reason it was safe to make at all.**

**Not applied, and recorded. `chapter-0350.md`'s load book runs to 4,390 words against a movement mean of 3,142**, with a Crown Terrace record that is a single semicolon chain and a *What the day did not touch* paragraph of about five hundred words. The second review's own words were that no rule is broken and the content is accurate, and that this is the one place in the batch where the form is doing the work of a report rather than recording something that happened. **It is true and it was not changed, for two reasons, and both are on the page.** The load book is the same instrument the other forty-nine chapters of this volume carry, and the Crown Terrace record is a semicolon chain because that morning was eleven people putting events in an order and nobody took a minute. The *What the day did not touch* paragraph is the closing form of every chapter in this volume, and whether a standing paragraph that recurs in every chapter is a compliance report is already an open question at section 16 item 2 of the batch summary, owned by a later pass. **Trimming either one here would have been a batch deciding an open question in its own favour on the day it closed a volume, and a pass that reaches for the long record at the end of a volume is the same failure as a pass that reaches for the reserved sentence at the end of a volume.**

---

## 8. What this pass did not touch, and the standing owners

Nothing was compacted. No beat, day, character, scene, quoted sentence, guardrail or interval figure moved. No chapter outside this batch was edited. No controller-owned file was touched: not `scripts/`, not `.github/workflows/`, not `.opencode/agent/`, not `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json`, not `state/phase-ledger.json`. No new phase directory was created. The batch was not restarted.

**Still open, with the owner each one already had:** the four weeks in `chapter-0339.md` where the day map gives eight, for a pass over Movement IV. The two standing firstness claims in Volume 06, sixteen weeks apart in the same hand, for a pass over those two chapters. The three-and-two count of true things said by the man of about twenty-nine, for a pass over Movement I's chapter. The two standing firstness claims and the four new firstness claims of this movement, made live and not claimed, for whoever asks. The `protagonist` phrase at Chapters 314, 328, 331 and 332, for a pass over Movements I to IV. The panel and the marker, closed at one in fifty and spent in Chapter 337, with no balance carried. The `protagonist` instance at Chapter 341, fixed. The figures in this document, walked on the files and not copied out of a summary — which is the sentence the fourth finding in section 2 is about.

**And the one that is the controller's, reported for the seventeenth time, now citable:** the review of this repository is performed by the agent that wrote what is under review, and line 1 of the log it happens in says so.
