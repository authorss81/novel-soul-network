# Volume 20, Movement I, Chapters 1001 to 1010 — review-repair pass

**What this pass was given.** A review log for the phase that audited and repaired Volume 20 Movement I, carrying seven findings. The log's first line is the platform's, and it is the same line every artifact in this directory opens on: the reviewer is declared a subagent, is invoked as a primary agent, and the platform falls back to the writer. **The seven findings below therefore came from outside the pass whose work they review, and every one taken here was re-measured from the files before anything was edited. Four were corrected, two are controller-owned and were refused, and one is disclosed rather than corrected on purpose — four plus two plus one is the seven the review carried. Two further defects were found while acting on the fifth finding and were not in the review at all, and a third was committed by this pass and is disclosed at §9.**

**What it changed.** One figure, in eight places. One sentence in the prompt dispatched to Movement III, in two claims rather than the one the review named. Five state-file signposts. Five governing blocks. **It rewrote no sentence of prose in any of the one thousand and twenty chapter files, invented no page, renamed no chapter, reversed nothing in the plan, and did not touch the novel's plot, its cast, its prices, its day map or its threads.**

**Disclosure, stated here rather than left to be found.** This artifact was written in the same phase that acted on the review it records, and it says so on its first page. **That is the case for Volume 12's first two artifacts and it is not the case for any other artifact in this directory.**

**It declines to number itself in either sequence, as `volume-20-batch-0002.md` did before it and for the same reason: the ordinals already recorded in `reviews/README.md` do not agree with one another — that directory's roll-up makes `volume-19-batch-0005.md` the thirteenth while its own entries call it the eleventh to flag the ledger and the thirteenth artifact — so a new ordinal would be a further voice in a sequence that has already stopped counting, and not a continuation of anything. What it does say is what is checkable: this is an artifact for Volume 20 batch 0001, it reviews a repair pass rather than a batch, and it was written in the phase that acted on the review it records.**

---

## 1. THE FINDINGS, ALL SEVEN, AND WHICH OF THEM WERE TAKEN

| # | Finding | Taken? |
| --- | --- | --- |
| 1 | The reviewer never ran; the review phase silently ran the writer with `edit: allow` | **Refused — controller-owned** |
| 2 | `state/phase-ledger.json` has never advanced in the repository's history | **Refused — controller-owned, and flagged again here** |
| 3 | The governing `# LIVE` block under-declared its own pass by three repairs | **Taken, and the gap left visible** |
| 4 | *Exactly eighty apparatus tokens per file* is wrong; Movement II is 798, not 800 | **Taken, and confirmed in a stronger form than the review stated it** |
| 5 | `batch-0003/PROMPT.md` line 70 names a title that was deleted | **Taken, and the same sentence carried a second false claim the review did not name** |
| 6 | `state/current.md` line 1 is garbled and excludes the block it points at | **Taken, and it is in all five state files and not one** |
| 7 | Date ordering in the state file now reads backwards | **Disclosed and left, on purpose; §5** |

**AND TWO THAT THE REVIEW DID NOT MAKE, BOTH FOUND BY ACTING ON FINDING 5.** The prompt's claim that Movement II broke no title rule was false on that prompt's own criteria, at Chapter 1012. And the false *eighty per file* figure was not confined to the two files the review named; it was in five state files and three summary sections, eight places in all. **A review that names two of eight is not a review that found two, and the second pair was found by asking where else the string appeared rather than by looking.**

---

## 2. FINDING 4, AND IT IS THE ONE THAT MATTERS MOST

**The review reported that Movement II's conversion cost 798 apparatus tokens rather than 800, and that Movement I's +800 is correct. Both halves are right, and the confirmation is the part worth publishing: `10,569 − 9,771 = 798` is also what the §4 word table has said since before the sentence beside it was questioned.** The ten per-file apparatus cells in that table have always summed to the printed totals. **The totals were never wrong. The sentence explaining them was, which is the more dangerous of the two failures — a total with nothing beside it can be checked by anyone, and an explanation with nothing beside it is read as fact.**

**The cause is on the page and was findable by reading one line.** All three hundred and twenty anchor rows print a four-digit interval, and the true range across both movements is one thousand two hundred and thirty-five at Chapter 1001 to one thousand eight hundred and eighty-eight at Chapter 1020. **The first draft of this artifact put the top of that range at one thousand eight hundred and fifty-nine, which is Chapter 1001's own maximum and not the movements', and the error was caught by measuring instead of generalising — which is the whole finding of this artifact, committed one paragraph after it was made.** A cardinal in that range whose remainder below the hundred is non-zero renders in six tokens — `one thousand eight hundred and fifty-five` — against the single digit it replaced, so each row cost five and each file eighty. **One row in three hundred and twenty does not.** `chapter-1017.md`'s twelfth row, *The twelfth of nineteen ruled lines on that board up on two nails*, prints `one thousand eight hundred days`. **One thousand eight hundred is an exact hundred, so it takes no `and` clause and renders in four tokens, and that row cost three.** Fifteen rows at five and one at three is seventy-eight.

**What makes this worth an artifact rather than a corrected number is that the exception is arithmetically perfect.** The day figure is right, the weeks figure beside it is right, the origin is right, and the cell would pass any test in this repository except one that measures the length of the rendering rather than the value of it. **And the only reason the wrong sentence survived two passes is that the rule it asserted — sixteen rows at five tokens each — is true, so it read as a derivation rather than as an assumption.**

**The shape is named, because it has now appeared three times in this volume:** the `screen` sweep published as twenty pages of three volumes and standing on fourteen files across six; the anchor cost published as uniform across twenty files; and the prompt's title claim published as Movement II's compliance. **A figure correct for most of its cases, generalised to all of them in a sentence rather than in a table, and inherited by the next pass as a rule.** None of the three is a defect of a page, and no measure that reads totals would ever have found any of them.

---

## 3. FINDING 5, AND THE SECOND FALSE CLAIM IN THE SAME SENTENCE

`workspace/volume-20/batch-0003/PROMPT.md` line 70 said Movement I broke its title rule once, on *A Ladder And Two Drawing Pins*, and Movement II did not. **The first half was historical, because Chapter 1008 was repaired to *The Wage Envelope Was Thinner* during the pass under review. The second half was false on that prompt's own criteria: Chapter 1012 reads *A Drawer And Four Questions*, which is an `And`-joined pair of two things and carries the number-word `Four`, and it breaks the rule twice on one line.**

**Chapter 1012 was deliberately not renamed.** `workspace/volume-20/batch-0001/SUMMARY.md` §10A named it and left the wording decision open so that it would be taken once and in one place. **Renaming a correct page to make a movement's record read clean is the failure this repository keeps paying for, and a review-repair pass that does it has replaced a record with a tidier one.** The prompt now tells the Movement III pass to count one fewer Movement I break than the version it was dispatched with, and to name Chapter 1012's break rather than repeat it.

**AND THE SHAPE OF FINDING 5 IS THE FINDING.** The previous pass recorded this defect in five separate files, in each case correctly, and then corrected a *different* sentence in the same prompt and left the recorded one. `batch-0001/SUMMARY.md` §10A still says *the Movement III pass should correct it*, and that sentence is now history. **A pass that records a defect in five places has not discharged it, and the sentence that promises a future pass will do the work is the sentence most likely to be read as a reason not to.**

---

## 4. FINDING 3, AND WHY THE UNDER-DECLARATION WAS LEFT VISIBLE

The governing block named two repairs. Its own §2, by way of `batch-0002/SUMMARY.md` §10A, attributed five to the same pass. **The three it omitted were the two arithmetic cell repairs on `chapter-1012.md` and `chapter-1017.md`, the in-place correction to `outline/volume-20.md`, and the correction to the Movement III prompt's `screen` sweep.** The block a later pass actually reads was the narrower of two accounts of the same work.

**The narrow block was relabelled `# ARCHIVE` with the gap named in the block's own heading, and it was not left byte-for-byte: its §2 also carried the false per-file figure and that one sentence was corrected in place, which the block's amended heading says so itself. What was left alone is its structure, its wording and its account of the work.** Tidying it would have removed the evidence that a hand-off can under-declare the work behind it, which is the finding. **A record corrected into consistency teaches nothing; a record left inconsistent with a note teaches the shape of the failure once.**

---

## 5. FINDING 7, AND WHY IT WAS NOT FIXED

**The archive blocks at lines 93 and 136 of `state/current.md` carry the date 4 October 2026, which is in the future.** This pass is dated 3 October 2026 and sits below them, so the file's dates read backwards.

**It was disclosed and not repaired.** The convention that an archive block is not reworded is why: a block whose date is corrected is a block whose contents have been touched, and this file has never touched one. **The alternative — silently fixing two dates to make the file look orderly — would have destroyed the only evidence that two passes dated their blocks into the future, which is itself the kind of small unforced inaccuracy that the archive exists to keep.** §5 of the new governing block gives the true order and tells a later pass to read bottom-up.

---

## 6. FINDINGS 1 AND 2, REFUSED, AND THE REASON IS THE SAME

**The reviewer reported that the reviewer never ran, and it is right.** `.opencode/agent/novel-reviewer.md` declares `mode: subagent`, the workflow invokes it as a primary agent, `opencode.json` sets `default_agent: novel-writer`, and `logs/batch-0001.review.log` opens with the platform's own fallback line. **The consequence is that the `AGENTS.md` gate *a reviewer has checked the result* has not been satisfied by an independent reviewer on any batch in this repository, and twenty files of edits made during a review phase were committed under a writer-work message.**

**The reviewer also reported that `state/phase-ledger.json` has never advanced, and it is right.** It stands at `phase-000-bootstrap`, `planned`, `attempts: 0`, `actualModel: null`, after one thousand and twenty chapters and twenty-two continuation phases. **A ledger that has never advanced cannot detect a stall or a retry, so the stall detection the controller relies on is not currently functioning. That is the most consequential open item in the repository and it is not this pass's to touch.**

Both files are controller-owned and `AGENTS.md` forbids editing them. **Both were read and not written, and both are flagged again here. Neither was worked around, and no fiction file was used to smuggle a controller decision into a hand-off.**

---

## 7. WHAT WAS VERIFIED AND DELIBERATELY NOT TOUCHED

**The review's own list of things that should not be re-litigated was checked rather than trusted, and all of it stands.** Guardrail four of `outline/volume-20.md` does require spelled-out interval figures, and the five-volume control is real: Volumes 15 to 19 return zero digit-form day rows and Volume 20 returns zero, with no mixed file in either set. **The 320-row conversion was correct and is preserved.** The day map is intact at chapters 1001 to 1010 against days 2217 to 2228. Chapter 1008's new title breaks neither of the two rules the old one broke, and leaving Chapter 1005 standing is defensible. Both cell fixes are arithmetically right. **And `batch-0002/SUMMARY.md` §10A's disclosure that a previously published *160 of 160 reproduced* certification was false on disk remains the best thing in the phase under review, and this pass disturbed none of it.**

**The cell repairs, the outline correction and the prompt sweep correction were left exactly as the previous pass made them.** They were confirmed on disk and not redone, because redoing a correct repair is how a second wrong figure gets published beside the first.

---

## 8. WHAT A PASS ACTING ON THIS ARTIFACT SHOULD TAKE FROM IT

**Do not carry a per-file cost asserted as a rule; measure it per file.** **Do not accept a repair as discharged because five files say a later pass will do it.** **Do not treat a summary's explanatory sentence as derived from the table beside it, because on this volume's evidence it may not be.** **Do not edit an archive block to make a file read cleanly, including its dates.** **Do not rename a page to make a movement's record consistent.** **And do not read a zero or a clean figure from an instrument that has never been asked a question it could fail.**

---

## 9. WHAT THIS PASS GOT WRONG WHILE FIXING THE ABOVE, AND IT IS THE SAME DEFECT

**An independent review of this repair pass, run after the corrections were applied, returned twelve defects. Nine were real and are corrected here and in the files they name. Three were its own errors and are recorded rather than hidden. This section is the part of this artifact that matters most, because a review artifact that lists only what it fixed is an advertisement.**

**DEFECT ONE, AND IT IS THE FINDING OF THIS ARTIFACT COMMITTED ONE PARAGRAPH AFTER IT WAS MADE.** The new §0B in `workspace/volume-20/batch-0002/SUMMARY.md` published the range of the three hundred and twenty anchor intervals as **1,235 to 1,859**. **The true range is 1,235 to 1,888 — 1,888 is Chapter 1020's largest row, and 1,859 is Chapter 1001's.** The figure was read off the first file's sixteen rows and generalised to all twenty, which is the exact failure §2 of this artifact is about, sitting inside the derivation of 798. It was caught by measuring all three hundred and twenty rows instead of generalising from sixteen, and it is corrected in place at `batch-0002/SUMMARY.md` §0B, at `state/continuity.md` and in this file. **It is left named here rather than quietly amended, because a repair pass that commits an instance of the defect it is repairing and does not say so has taught its reader the defect is rarer than it is.**

**DEFECT TWO, AND IT IS A FACTURE OF THE RATHER WORSE THAN A MISCOUNT.** The derivation stated that a cardinal *with a remainder below the hundred* renders in six tokens. The operative condition is a **non-zero** remainder: `chapter-1001.md` prints `one thousand six hundred and seventy`, whose remainder is zero and whose token count is six, because it is the tens that survive, not the hundreds. Only an **exact hundred** drops to four. Corrected in both places.

**DEFECT THREE, AND IT IS A WHOLE PARAGRAPH WRITTEN FROM A BOOKKEEPING ERROR.** This artifact's own first page said five findings were corrected out of seven. **Four were.** It then made the arithmetic reach five by promoting a restatement of the prompt defect to a finding of its own, and asserted the count in six files at once, including twice in `state/current.md` with two different numbers in the same file. **The tally is now four corrected, two refused, one disclosed, seven — and the two defects found while acting are labelled as not being review findings, because inflating a count is how a repair pass starts reporting its own diligence instead of its own work.**

**AND THE REVIEW'S OWN THREE ERRORS, because a review artifact that records only the review's mistakes is half an artifact.** It reported that the narrow block was left exactly as written, which is false: that block's §2 carried the false figure and one sentence of it was corrected in place, which its own amended heading says. It reported a markdown mis-nesting at `batch-0001/SUMMARY.md:75`; **the delimiters on that line were and are balanced and it renders correctly**, though the clause it objected to did sit outside the surrounding bold, and that has been tidied. And it reported that this artifact's ordinal claims were false — **they were, and they are gone**, and this file now declines to number itself for the reason `volume-20-batch-0002.md` gave: the sequence in `reviews/README.md` has already stopped agreeing with itself, and a new ordinal would be a further voice rather than a continuation.

**AND ONE THING THE REVIEW COULD NOT DO, WHICH IS THE SAME LIMITATION IT FOUND IN §5.** It had no shell, so it could not run `git diff`, and it says so rather than implying otherwise. **Its independent route to the same 800 / 798 / 1,598 — tokenising each row itself rather than reading the pre-repair table, and finding exactly one four-token row on exactly one file — is stronger evidence than the diff it could not run, and it is recorded here as the better of the two derivations.**

**AND THE LAST THING THIS PASS GOT WRONG BY ACCIDENT, WHICH IS THE ONE THAT WOULD HAVE COST SOMETHING.** Rewriting the signpost at line 1 of `state/open-threads.md` to carry the governing-block instruction once — which was the whole of finding six — displaced the standing exemption statement that three earlier blocks cite by name, so that *the standing exemption at line 1* became false while the blocks asserting it stayed. It is restored, and the new block says why. **An edit made in the right place can quietly un-break something standing next to it, and the only defence is to go and read what else that line was holding.**
