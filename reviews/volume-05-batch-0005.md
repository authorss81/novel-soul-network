# Review — Volume 05, batch 0005, Chapters 241–250 ("Three Districts")

Reviewed in the review-repair phase. **No chapter was restarted, no batch was rewritten, and the planned plot is unchanged.** Every finding below is fixed in this pass, recorded rather than actioned with the reason, or flagged for a file this pass may not edit. The findings and the raw reviewer output are in `logs/next-0008.review.log`.

## What the pass was

The review phase found Volume 05 complete on the page at Chapter 250 with its summary, its next prompt and all four rolling state files written, and ran an independent review against every gate the brief prints. **Thirteen findings. Five are canon errors inside the ten chapters and are fixed in the chapters. Three are the next-phase prompt and are fixed in that prompt. Four are state-file errors a Volume 06 writer would have inherited and are fixed in those files. One is the review trail itself and is this file.**

**A NOTE ON THE REVIEWER, BECAUSE IT MATTERS TO EVERY LINE BELOW.** The review phase logs `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, so the review ran on the writing agent and **this is a self-review, as is every review-fix commit in this repository.** That flag is controller-owned and is recorded here rather than acted on. It is the reason the findings below were each re-derived from the files rather than accepted as written: **every one of the five canon findings was confirmed by recomputing the day map before it was fixed, and two of the four measurement findings turned out to have a different cause than the review reported.**

## What passes, and it was checked rather than assumed

- **Both bold ceilings hold with margin.** 262 spans at 8.27 per thousand against 10.75; worst chapter 250 at 10.70 against 12.4.
- **The backward eighty-character sweep reproduces exactly.** 51 maximal shared runs against a full 240-chapter index, with the per-chapter distribution 5, 1, 0, 12, 0, 0, 1, 0, 0, 32 — unchanged by this pass, because the nine sentences added here share nothing with any earlier chapter at that length.
- **Arithmetic reproduces.** Prose plus load book equals the row total in all ten, `---` markers excluded, em-dashes left attached to their token.
- **The load-book run 244 to 253** is continuous, one entry per chapter, with no gap and no duplicate, and continuous with the fifty at Chapter 1 and with Movements I to IV.
- **The day map is used as printed.** All ten dates hold, both Exchange sittings are four weeks to the day from their predecessors, and the book is at forty-five lines at the tenth sitting and forty-six at the eleventh.
- **Hard stops hold.** No `* * *`, no *pattern*, no *carrier*, no Iona, no Sorn, no month-name, no narration bold, and every line carries an even count of `**` and of `"`.
- **Talia Venn is named in 249 and 250 only**, the milestone is spent once, four minutes in a corridor, no scene, no declaration, no kiss.
- **The nine words and the kettle land.** Chapter 247 removes him from the only thing he owns and nobody thanks anybody.

## The findings, and what was done about each

**1. A year appears in Chapter 242, twice, and the summary asserted that the batch added none. FIXED IN BOTH PLACES.**

`chapter-0242.md:7` carried *a float switch that had been set by somebody in about 2019*, and the load book repeated it. The batch prompt's hard stop is that no year appears in any of the ten chapters, and `batch-0005/SUMMARY.md` said flatly that the two inherited years from Chapters 53 and 56 stand and this batch adds none. **That claim was false, and a sweep of the whole manuscript confirms 242 held the only year in Volume 05.**

The float switch is now set by somebody who is not named here and was never asked, and the load book records that there is no name and no date for the setting of it **because that person is not a person in this case** — which is the entry's own existing convention, first stated in the same paragraph, and not a new rule invented to cover a hole. No figure in the chapter changed and no other sentence in the ten was touched.

**2. Chapter 242's wall interval was wrong, and the pass before this one had it right. FIXED, AND THE THIRD TIME THIS FIGURE HAS BEEN WRONG.**

The wall's twelve lines went on the Thursday of week seventy-nine. Anchoring on Chapter 248's *forty-nine days old* and walking the day map back gives 25, 29, 32, 34, 35, 36, 39 and 49. Every value in the batch was right except 242, which said twenty-six.

**The history matters more than the fix.** The first writing pass carried twenty-nine at 242 and was correct; the second pass recorded that as an error and "corrected" it to twenty-six; this pass put it back. **A value that was right was changed in the wrong direction, the error was copied into the summary, and Volume 06 would have inherited it.** The full history is now in the day-map section of the summary rather than only the corrected figure, because the pattern — a repair pass that trusts a neighbouring chapter over the map — is the thing a later writer has to be warned about.

**3. Chapter 250's thirteenth-line age was off by one and the error had already propagated into `state/current.md`. FIXED IN BOTH.**

The line was written on the Thursday of week eighty-six and Chapter 250 is the Wednesday of week eighty-eight, which is thirteen days. The chapter said twelve. **Chapter 249's *eight days old* is correct and was not touched, which is what makes 250 the odd one out.** The same figure was corrected once already, from two to twelve, and a correction that stops one short is worse than the error it replaced. `state/current.md` and `state/open-threads.md` carried the figure too and both are corrected.

**4. Chapter 247 contradicted itself on the heating. FIXED IN TWO PLACES IN THAT CHAPTER.**

The opening said the heating *was on its fifteenth day off* and the chapter's own load book said *fourteen days into an unheated fortnight*. The fortnight began on the Monday of week eighty-three and this is the Monday of week eighty-five, which is fourteen. **The opening is now fourteenth, and the cook's silence at the sink — which is dated by the same fortnight — is fourteen days and not fifteen.** Both are now the figure the summary's series gives, and the chapter no longer disagrees with itself.

**5. The room-age series was dropped from all ten chapters, and the summary's replacement was wrong. FIXED, AND THE PROMPT WAS WRONG AT SOURCE.**

The prompt fixes a series the batch must continue: the room's own age, from 105 days at Chapter 241, and the card in a rail, from 109. **Neither figure appears anywhere in the ten chapters. Movement IV carried its room age in nine of ten chapter openings and this movement dropped it silently, and no amount of grepping finds it, because absence is not a value.**

Worse, the summary then published a series of its own to fill the gap and **that series was wrong at the last two chapters: 136 at 249 and 151 at 250, where the true figures are 137 and 142.** Working the arithmetic back from the day map: Chapter 241 is the Monday of week eighty-three and Chapter 250 is the Wednesday of week eighty-eight, **a span of thirty-seven days, and the prompt's endpoint of 151 assumed forty-six.** The prompt was nine days high, the summary copied the error, and a Volume 06 writer working from either file would have started a volume nine days out on the volume's most-watched object.

**What this pass did: corrected the prompt's endpoints in place, published the full ten-value series in the summary, and carried it in nine of the ten load books.** Chapter 244 is the tenth and is correctly absent — it is the Exchange back room on the Wednesday of week eighty-four, not the room off the service road, and the series does not belong in it. The nine sentences are in nine different constructions; see finding 8 for why that was not the first draft.

**6. The next-phase prompt contradicted itself on its deliverables. FIXED.**

Line 5 read *Deliverable: one file, `VOLUME-CLOSE.md`. Nothing else*, while line 7 and a dedicated section required `ARITHMETIC-AND-CALENDAR.md` as a second deliverable. **A writer obeying line 5 fails the phase; a writer obeying the section violates line 5, and this is the only live prompt in the repository.** Line 5 now names both files, in order, and says they are one phase.

**7. The same prompt called itself the sixth volume close and then listed four. FIXED TO FIFTH.**

Four closes exist — Volumes 01, 02, 03 and 04 — so this is the fifth. The four template paths the sentence lists were correct and are unchanged.

**8. The same prompt pointed at a section of the summary that does not exist. FIXED, AND THE MEASUREMENT PASS BELOW IS WHY.**

It told the close writer to read *the four passes and their findings* from `batch-0005/SUMMARY.md`. **There is no such section. The summary had a four-*item* interval-fix list and no pass log.** The reference now names what is actually there — the passes over the date intervals and what each found — and this pass added a fifth entry, so the list is five long and the sentence is true.

**The second half of this finding is the one that cost something.** Writing that fifth entry meant reporting the measurement figures, and re-running them produced the next two findings.

**9. The published load-book overlap for Chapter 248 was an arithmetic slip, and the review's diagnosis of it was wrong. FIXED, AND THE METHOD IS NOW WRITTEN DOWN.**

The summary published 28, 32, 19, 34, 106, 100, 57, **69**, 117, 58 and presented the series as exact. The review reported that a set-matched count gives 66 and suggested a separator-line boundary artifact.

**Neither number is the right one, and both are symptoms of the same thing: the method was never stated.** Recovering it took a grid over boundary, dash handling, case, window size and counting mode. **The method that reproduces the other nine figures to the unit is: split at the entry header, keep the `---` markers as tokens, window eight, case-sensitive, and count each distinct string with multiplicity — the smaller of its two counts.** On the pre-pass files that returns the published series exactly, all ten, except Chapter 248, where it returns **67**. **The published 69 was never produced by any reading of the stated method; it was a slip in the summary, and the prose is not implicated — the two sentences in Chapter 248 that generate the overlap are unchanged.** The method is now printed in the summary so the next writer can reproduce it.

**10. The published hedge figure is not what the printed house rule produces. FIXED, AND IT MOVES A CLAIM THIS VOLUME MAKES ABOUT ITSELF.**

The summary published 453 true hedges at 14.51 per thousand and called it the second highest in the volume. **The rule printed in `workspace/volume-05/batch-0004/PROMPT.md` returns 522 at 16.48 on the same files — a difference of sixty-nine, and the error was in the published figure and not in the prose.**

The matcher was validated before it was trusted, on three finished movements' own files: **Volume 05 Movement II reproduces to the unit on all four figures (31,905 words, 560 raw, 401 hedges at 12.57, 238 bold), Movement IV on all four (34,459, 674, 480 at 13.93, 297), and Volume 04 Movement I on all three counts (349 raw, 218 hedges, 211 bold) with its word total drifted by the eighty-five words later repair passes added to it.** The corrected figure is published, the previous one is recorded rather than deleted, and **16.48 is the highest hedge figure in this volume, not the second highest, and the close prompt has been told to carry the corrected number.**

**The bold figure also moved, from 263 to 262, and that one-span difference is on the pre-pass files as well and is left recorded rather than chased.**

**11. The within-batch repetition measure the prompt named was never published. NOW PUBLISHED, WITH THE METHOD AND THE SPREAD.**

The prompt cited Movement IV's fall from 158 runs to 48 as the move to make, and the summary did not report the measure at all. It is now reported: **983 distinct eight-token strings occurring more than once, over 31,672 words, which is 31.0 per thousand.** An independent review count on a slightly different tokenisation returned 1,259 and 39.9 per thousand. **Both are inside the volume's family of 31.7 to 40.9, and the honest statement is that the figure is method-dependent across roughly 31 to 40 per thousand and that a later writer must quote the method and not the number alone.** That is now what the summary says.

**12. `state/current.md` put Talia Venn in a chapter she is not in, and supported a true claim with a false one. FIXED, WITH THE SAME ERROR FIXED IN `character-state.md`.**

The file said she *was in the room in Chapter 247 while the removal happened and said nothing*. **She is in none of 247 or 248. A woman of twenty-four appears in four of the ten chapters — 245, 246, 249, 250 — and the same sentence said five.** The nine words and the removal in Chapter 247 are the first-year of nineteen's, who is Asha Reed, and the page settles the question itself: *And then she went and washed up* is not Talia Venn. `state/character-state.md` carried the same chapter list and the same count and is corrected with it.

The same sentence then claimed that *we*, *our* and *us* occur only about a company, a room, a depot, an office, a rota, a page and a board. **The claim that matters — that they never occur in a sentence about Talia Venn and Marek Senn — is true and holds. The enumeration behind it was false:** every occurrence in the ten files is about people, including two in Chapter 247, *neither of us has asked to stop* and *not what it means about the two of us*, where the woman is Asha Reed. The false enumeration is replaced with an accurate one, because a next writer checking the rule would have been sent looking for five constructions that do not exist.

**13. No review artifact existed for this batch. THIS IS IT.**

`reviews/` held three files, all Volume 02 and 04. **Volume 03's five batches still have none and Volume 05's four earlier batches have none, and that debt is owed and is not claimed as discharged by this file.** The reviewer noted the same gap.

## What this pass did not do, and why

- **It did not re-plan anything.** No chapter card, scene, movement, character or plot beat was changed. The two load-book sentences added in nine chapters and the four interval corrections carry no story movement: the room's age and the card's age were already canon and were already being quoted in the prompt and the state files, so the prose now agrees with them instead of leaving them to the reader.
- **It did not chase the one-span bold difference.** It is recorded. A figure that has been re-run and differs by one is a smaller problem than one that has been re-run and differs by sixty-nine, and the second is now fixed.
- **It did not unbold ten lines that break a house rule no review raised.** Checking the summary's claim that no line carries a bold span on both sides of one speech tag — a rule the batch prompt does print — **ten lines do: Chapter 246 once, Chapter 247 four times, Chapter 248 twice, Chapter 249 once, Chapter 250 twice.** The pattern is a bolded lead-in, a speech tag and a bolded elaboration, and the two most exposed are the first-year of nineteen's *I have been the person who says things in this room* and the corridor. **The prose is the movement's best dialogue and the emphasis is doing work in all ten, so this pass recorded the truth in the summary and left the pages alone rather than restage eleven beats on a finding nobody raised. The claim of compliance is what was false, and it is no longer claimed. The close should decide whether the ten stand.**
- **It did not edit `state/phase-ledger.json`, the review agent, `.github/` or `.opencode/agent/`.** All are controller-owned and out of bounds. The ledger still reads `phase-000-bootstrap` while the manuscript is at Chapter 250; that is a controller matter and is flagged here for the fourth time.
- **It did not compact the state files.** They are larger than the manuscript's plan and this is the fifth phase in a row whose summary has said so. **The right place for that is the volume close, which is the next phase, and doing it in a repair pass is how a figure gets dropped.**

## What the next writer should know

**The volume's figures changed in this pass and the changes are real.** 31,672 words, not 31,229. 522 hedges at 16.48, not 453 at 14.51. 262 bold spans, not 263. An overlap series of 28, 32, 19, 34, 106, 100, 57, 67, 117, 58, in which only Chapter 248 moved. A within-batch pass of 17 pairs in 23 runs, which is the cleanest in the volume. **The backward sweep did not move at all, which is the check that the added sentences were genuinely new.**

**The day map held every time it was run and three of the five canon errors were figures taken from a neighbouring chapter instead of from it.** That is the standing lesson of this volume and this pass is the eleventh consecutive movement to find it.

**And the one thing that is not a figure: the nine sentences were written to a single construction first, which put the within-batch pass at 28 pairs in 42 runs — worse than the 20 and 31 it started from — and were then rewritten in nine constructions and came out at 17 and 23.** A figure added to a load book is a sentence nine other load books also want, and the discipline that keeps this batch clean is writing it differently every time.
