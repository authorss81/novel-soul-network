# `workspace/volume-17/batch-0006/` — WHAT THIS PHASE WAS GIVEN, WHAT IT DID, AND WHERE THE WORK WENT

**This file replaces `PROMPT.md` in this directory. The prompt as given is kept whole at `PROMPT-WAS-GIVEN.md` and is not edited. `CLOSE.md` beside it is not edited either and is the best-measured document in this volume.**

**LATE 1 OCTOBER 2026, WRITTEN BY THE REVIEW-FIX PASS AFTER THE CLOSE PASS AND AFTER A REVIEW OF IT. THE MANUSCRIPT HAS NOT MOVED. THIS FILE IS A RECORD AND NOT A PROMPT, AND THERE IS NO `PROMPT.md` IN THIS DIRECTORY ON PURPOSE.**

## 1. The false premise this phase was given, retracted

**The prompt at `PROMPT-WAS-GIVEN.md` opens with the sentence *Volume 17 is complete on the page. Chapters 821 to 880 are written, measured, reviewed and repaired across six movements*. Both halves of that are false against the repository. There are five movements and there are fifty chapters, and Chapters 871 to 880 were never written.** `PROMPT-WAS-GIVEN.md` §1 states it plainly: *Movement VI, Chapters 871 to 880, is at `workspace/volume-17/batch-0006/` only when this phase has run; before this phase runs, Movement VI does not exist on disk and this close is what will say so.*

**That sentence was in the prompt and the phase read it and did not act on it.** The close it produced caught the error itself and said so in its own first line — `CLOSE.md` §0 is headed *THE ONE FACT THAT GOVERNS THIS WHOLE FILE* and reads **MOVEMENT VI DOES NOT EXIST. CHAPTERS 871 TO 880 WERE NEVER WRITTEN** — and it then measured the fifty chapters that exist and marked every Chapter 880 figure as arithmetic with no page under it. **That self-correction is the one thing this phase got right and it is why the error is visible on the record instead of buried, and it is why no part of `CLOSE.md` had to be rewritten.**

**The premise is retracted here and the retraction is the whole of this file's work. Nothing else in this directory is changed.**

## 2. How it happened, in one line of a file

`workspace/volume-17/batch-0005/SUMMARY.md` §11 item 14 records a review finding that the batch had no summary and no next phase, and resolved it like this: *`workspace/volume-17/batch-0006/PROMPT.md` is the next phase, and it is a volume close.*

**The same file's hand-on four paragraphs earlier, at §12, says the manuscript stands at Chapter 870, that Volume 17 is open, and that one movement remains, and it gives Movement VI's ten days, its entries and its woman's-page figures.** One of those two statements is true and the phase acted on the wrong one, and the movement that was to have been written between them was not written. **A pass handed two contradictory statements in one file picked the one that was cheaper to satisfy — creating a directory is a minute of work and writing ten chapters is not — and a close is what a directory gets you.**

**THE LESSON, AND IT IS GENERAL: a review finding that says *this batch has no next phase* asks for a next phase and does not say what kind. The kind is in the file's own hand-on and the finding does not override it. Resolve the finding with the next phase the hand-on names, not with the cheapest thing that satisfies the words.**

## 3. Where the work went, and why the Movement VI prompt is not in this directory

**The live Movement VI chapter prompt is at `workspace/volume-17/batch-0007/PROMPT.md`. Chapters 871 to 880, days 1953 to 1988, weeks 295 to 300, entries 874 to 883, the climax at 877 and 878, the resolution at 879 and 880, the sixty-third sitting at Chapter 875 where the book shuts again, and the sixty-fourth at Chapter 880 where it opens.**

**A Movement VI prompt left in this directory would never be executed, and the reason is the controller's order of operations.** `scripts/novel_runner.sh` marks the phase directory `.done` at `novel_runner.sh:428` immediately after the review-fix pass returns, and its selection rule at `novel_runner.sh:82` and `:85` skips any directory holding a `.done`. **So a prompt written into a directory the controller is about to mark done is a prompt that has already been given up on.** The same is visible in the markers this phase inherited: `workspace/volume-17/batch-0005/` carried `.done` at one commit and `.deferred`, `.attempts` and `.retry-after` at a later one, which is the signature of a path that wrote after completion.

**`batch-0007/` is also the number the plan of record implies once this directory is spent, and the calendar file reserves no further section 9 for this movement.** `has_other_incomplete_phase` at `novel_runner.sh:272` finds `batch-0007/` holding a `PROMPT.md` with no `.done`, so `ensure_next_phase` returns without minting a generic continuation prompt, and the next tick dispatches Movement VI.

**AND THERE IS NO `PROMPT.md` IN THIS DIRECTORY, WHICH IS THE POINT.** A directory without one is not selectable, so this phase cannot be re-dispatched and cannot consume another attempt on work it has already done. `PROMPT-WAS-GIVEN.md` is kept because the record of what a pass was told is worth more than the convenience of the file being re-runnable.

## 4. What `CLOSE.md` in this directory is, and is not

**It is a mid-volume record of Chapters 821 to 870: what fifty chapters did, what they cost, what they left standing, what they did not do, and the measured cells for the fifty pages that exist.** It is the only document in this repository that has re-derived the calendar file's anchor table and every figure class on it, and it did so with an instrument it proved on three control movements before it pointed it at a page.

**It is NOT the volume close, and a pass must not read it as one.** Volume 17 is not closed. Its last page is Chapter 870, day 1951, and the plan of record's last page is Chapter 880, day 1988, which does not exist yet. **Its §0 says this, its §3 marks every Chapter 880 figure as arithmetic with no page under it, its §8's line 1 says the volume is NOT closed, and its §10 says no next phase is dispatched by it.** The review confirmed this as correct rather than as a defect.

**What this pass changed in it: the H1 title and §9's last paragraph, and nothing else.** Both said *close* where they meant *mid-volume record*. The nine findings at `CLOSE.md` §6, the debts at §7, the hand-on at §8, the measured cells at §4 and the guardrail walk at §5 are untouched, and the reviewer reproduced three of them independently — the eighteen occurrences of `right` as an adjective across seven files of Movement I, and `batch-0005/SUMMARY.md` §6's misstatement of Movement IV's whole-number-of-weeks vector.

## 5. What this directory's close pass was and was not permitted to do, and what it therefore left behind

**A close is not permitted to edit a chapter or a batch summary, so it published nine findings instead of repairing them. `CLOSE.md` §6 lists them and the Movement VI prompt at `batch-0007/` §8 says which of them that movement owns. None of them is a plot change and none is repaired here.**

| Finding | Site | Owner |
| --- | --- | --- |
| Three duplicated twelve-word sentences across three file-pairs | 838/843, 824/830, 827/830 | Movements I and III |
| One duplicated twelve-word sentence inside one file | Chapter 850 | Movement III |
| A printed figure for the place behind the chair, and it is correct | Chapter 824 | Movement I, and it stands |
| Support-spend count nine against a ceiling of eight | the pages' own lists | Movement VI records it; it spends none |
| Shutter hour named on forty-four of fifty files, `at ten` on nineteen, on none at all on six | the fifty files | Movement VI measures its own ten |
| Fifth duplication scope's published counts not derivable from its published definition | `batch-0005/SUMMARY.md` §3, §4C | not needed; the four exact-tuple scopes are the guardrail's |
| Movement I's arrival cells on an instrument this volume's tokenizer does not reproduce | `batch-0001/SUMMARY.md` §3 | Movement I |
| `batch-0005/SUMMARY.md` §6 misstates Movement IV's vector | `batch-0005/SUMMARY.md` §6 | Movement V's summary; the correct vector is `batch-0004/SUMMARY.md` §7 |
| `right` as an adjective at eighteen across seven files, all in Movement I | Chapter files of Movement I | Movement I |

## 6. What did not move

**No chapter was written, edited, restarted or cut by this pass.** No resolution of Volume 15 or Volume 16 is reversed, softened or retconned. **Nothing is said about whether the practice the four hundred people kept after their district left in Volume 16 worked.** Iona Sorn stays where the Volume 16 close left him, in public custody, unanswered, not absolved, and at zero on all fifty files. `Evan Senn` is at zero on all fifty. The answer to Volume 08's question stays a chair he does not sit in. The room under the building in a first district is dark on all fifty days and is opened on none. The ninth chair does not move on any of them and its mover is named on none. The ring binder was shut on all fifty days, the page behind it unread, the four words printed on no page, the name this city has for that stretch of country printed on no page, and the woman of about thirty is not named on any of them. Chapter 849's refusal was not reopened, softened or converted into a disagreement. The register of correct acts that changed nothing stands at four and did not move in this volume.

**`outline/series.md`, `outline/ending.md`, `outline/volume-17.md` and `NOVEL_SPEC.md` were read and not written. `NOVEL_SPEC.md`'s eighth Status block is untouched and still records the Volume 17 decision as undecided, and no agent pass may write that paragraph.** `state/phase-ledger.json` is controller-owned, was read and not written, and **no flag about it is appended here**; the fact is recorded once, at `state/open-threads.md` item 29 and in `NOVEL_SPEC.md`.

**`workspace/volume-18/` does not exist and this pass does not create it.** Whether there is a Volume 18 is the repository owner's decision and it has not been taken.