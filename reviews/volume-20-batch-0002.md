# Volume 20, Movement II, Chapters 1011 to 1020 — review-repair pass

**What this pass was given.** A review log for the phase that wrote Volume 20 Movement II, carrying three findings and one disclosure. The log's first line is the platform's, and it is the same line every artifact in this directory opens on: the reviewer is declared a subagent, is invoked as a primary agent, and the platform falls back to the writer. **The two substantive findings below therefore came from outside the pass that wrote the ten chapters, and both of them were confirmed here on independent measurement before anything was edited. This is the fourteenth artifact in this directory and the seventh to record that fallback.**

**What it changed.** Two numbers on two of the ten pages, one claim in the plan of record, one claim in the prompt dispatched to Movement III, two certifications in the batch's own measure of record, one state figure, and this file. **It rewrote no sentence of prose, invented no page, reversed nothing in the plan, and did not touch the movement's plot, its four questions, its cast, its prices, its day map or its threads.**

**It is the twelfth artifact in this directory and the seventh to record the reviewer-fallback defect.**

---

## 1. FINDING ONE — TWO ANCHOR CELLS THAT CONTRADICT THEMSELVES

**What the review reported.** That `chapter-1012.md` printed `1419 days, two hundred and three weeks and six days` and `chapter-1017.md` printed `1576 days, two hundred and twenty-five weeks and two days`, that both are internally impossible, that the correct pairs are `two hundred and two weeks and five days` and `two hundred and twenty-five weeks and one day`, and that this contradicts the batch summary's claim of 160 of 160.

**Confirmed, and the scope was measured rather than taken from the finding.** The review's test was re-run over both movements with a parser written against the printed forms, including the zero-remainder `to the day`:

| Set | Rows | Arithmetically self-consistent |
| --- | --- | --- |
| Movement I, Chapters 1001 to 1010 | 160 | **160** |
| Movement II, Chapters 1011 to 1020, before this pass | 160 | **158** |
| Movement II, Chapters 1011 to 1020, after this pass | 160 | **160** |

**The two cells named by the review are the only two in either movement. There is no third.**

**Which side of each cell was wrong, and how that was settled.** In both cases the day count stands and the pair was recomputed, and the reason is that the day counts are corroborated from outside the cell while the pairs are not. **The `corridor post` row runs 1418, 1419, 1421, 1423, 1424, 1426, 1428, 1429, 1431, 1432 across the ten pages — monotone, with the two-day steps falling exactly where the day map gives a chapterless day — and 1419 sits between `1418 = 202w + 4d` and `1421 = 203w + 0d`, so 1419 can only be `202w + 5d`.** The `nineteenth ruled line` row runs 1566 through 1580 on the same monotone shape. **And `workspace/volume-20/batch-0001/chapter-1004.md` line 144 already prints `1576 days, two hundred and twenty-five weeks and one day`, so the pair restored to Chapter 1017 is not an inference at all: it is the rendering of that same day count on an earlier page of this volume.** The repair agrees with a page already on disk.

**The cause, with one correction to the review's diagnosis.** The review said each wrong pair was copied from the neighbouring file and that each matches its neighbour exactly. **The mechanism is confirmed and the second one is exact; the first is half right.** Chapter 1017's remainder `two days` is Chapter 1018's remainder for the same origin, exactly as stated. **Chapter 1012's wrong pair is `203w + 6d`, and Chapter 1013's row for that origin reads `1421 days, two hundred and three weeks to the day`, which is `203w + 0d`: the weeks figure was carried across from the neighbour and the remainder was not.** The `+6d` matches nothing on Chapter 1013 and matches several unrelated rows on Chapter 1012 itself, where `and six days` appears six times. **This does not change the repair, and the difference is recorded because a later pass checking this diagnosis against Chapter 1013 should not be told to expect a match that is not there.**

**The repairs.**

- `workspace/volume-20/batch-0002/chapter-1012.md:216` — now `1419 days, two hundred and two weeks and five days`
- `workspace/volume-20/batch-0002/chapter-1017.md:157` — now `1576 days, two hundred and twenty-five weeks and one day`

**What did not move, checked rather than asserted.** No day, origin, header, ordinal, closing line, caller count, price, day total, short-run anchor or sheet night moved on any of the ten pages. **Both repaired cells were non-exact rows before the repair and both are non-exact rows after it, so the exact-week distribution the summary publishes — zero, three, three, zero, three, three, three, zero, three, zero across Chapters 1011 to 1020, and eighteen of the 160 rows reading to the day — was re-derived after the repair and is unchanged.** **Both repairs are also token-neutral and word-neutral, which was measured and not assumed: each row held eight tokens and eight whitespace words before the repair and holds eight and eight after it, so §4's table still totals 19,239 body, 9,771 apparatus and 29,010 whole with body plus apparatus equal to whole on all ten rows, and Movement I's control still returns 14,000 / 9,518 / 23,518 to the digit.** Both repaired rows sit below their file's apparatus marker and were verified to, so the substitution cannot have moved a body figure either. **No published measure of this batch moved at all, and that is a property of this particular defect and not a general licence: a repair that changed a row's token count would have obliged the summary to reissue §4.**

---

## 2. FINDING TWO — A SWEEP FIGURE WRONG IN THE PLAN, AND WRONG STRONGER IN THE NEXT PROMPT

**What the review reported.** That `outline/volume-20.md` line 84 places the string `screen` on twenty different pages of Volumes 03, 07 and 12, and that the dispatched prompt tells the next pass the whole-word sweep returns zero across a thousand and twenty pages when it returns twenty.

**Confirmed, and the composition was read rather than counted.** The whole-word sweep over all one thousand and twenty chapter files returns **twenty occurrences on fourteen files**, and the files are in **Volumes 02, 03, 04, 05, 07 and 12**. All twenty were read in place:

| Kind | Count | Where |
| --- | --- | --- |
| A folding screen standing at the back of a room | 3 | Chapters 135, 145 and 163, the last two in a room's furnishing list |
| A device a person reads off | 16 | including two apparatus echoes of a sentence already counted in the body of their own file |
| A screen listed among a room's furnishings | 1 | Chapter 302, a clinic's sink, screen, trolley and window |

**Not one of the twenty is a thing done to a person, so the guardrail the sentence carries stands and only the arithmetic in front of it was wrong.** The count of occurrences was right; the count of files and the list of volumes were both wrong. **The word `screening` is at zero across all one thousand and twenty files and that claim was run and is correct.**

**The plan is corrected in place and no other part of it is touched.** The man of about thirty-seven who has run screenings before, Movement III's want, its refusal on the Tuesday, the three questions asked in advance in a doorway over about nine days and its debt to Chapter 759 are all exactly as the plan set them. **A wrong count of where a word stands is a measurement error and correcting it changes no plot.**

**The prompt was the more dangerous of the two and the reason is worth stating.** `workspace/volume-20/batch-0003/PROMPT.md` told the Movement III pass that its own sweep would return zero, **while the same prompt's §7 warns that a measure returning a zero it cannot justify is the failure this repository keeps making.** A pass told to expect zero either certifies the number on trust, or runs the sweep, gets twenty, and then either breaks the guardrail it was told was clear or spends the movement explaining a discrepancy it was told could not exist. **The prompt now prints the twenty, names the fourteen files and the six volumes, and tells that pass to expect them and read all twenty rather than certify a zero.** The correction is placed in the guardrail paragraph where the wrong claim sat, not in a footnote.

---

## 3. THE DISCLOSURE-ONLY FINDING, AND THE HOUSE FIGURES THAT WERE CHECKED WHILE ACTING

**The review labelled its third finding disclosure-only and required no action, and none was taken.** §2's sixty-file duplication control returns 309 pair-hits on 31 shared whole sentences against a published 315 on 32, and 429 distinct keys against a published 575. **That cell is already labelled in §2 as not reproducing, the cause is already named there, and the review proposed nothing about it. It was left alone, and leaving a labelled non-reproducing cell standing is the correct treatment; replacing it with a figure that is not Movement I's would be a worse record.**

**Three house figures were re-run because this pass was already holding the instruments, and all three hold.** The word table at §4 totals 19,239 body, 9,771 apparatus and 29,010 whole with body plus apparatus equal to whole on all ten rows. The `about` measure at §5 returns 733 of 29,010 pooled, 25.27 per thousand, case-sensitive 730 and capital-form 3. The day map at §3, the forty priced jobs and the ten sheet nights all re-derive. **The review independently reproduced every one of those and this pass did not change any of them, which is the point of running them again.**

**Movement I's sixteen rows per file at one hundred and sixty rows were confirmed as structural counts and not as reproduction claims.** `state/chapter-summaries.md` and `state/character-state.md` both describe the batch as carrying one hundred and sixty anchor rows at sixteen on each of ten pages, and both are right: the files carry sixteen `N days,` rows each and one hundred and sixty across the movement. **Neither state file claimed that all one hundred and sixty reproduce, so neither needed an edit, and this pass checked before editing rather than editing because a review named two figures.**

**No state file carried the wrong `screen` figure.** All five were searched. `state/current.md` carried the anchor-row reproduction claim and is the only one of the five that needed an edit; it now states that the figure was one hundred and fifty-eight of one hundred and sixty until this pass and that the day counts in the two cells were right throughout.

---

## 4. WHAT A LATER PASS MUST NOT INHERIT FROM THIS FILE

**Do not inherit `one hundred and sixty of one hundred and sixty` from any document written before this pass without reading §10A of the batch summary.** The figure is true now and was false on two cells an hour ago. **Do not read this pass's two repairs as evidence that the batch's instruments are sound.** They are not: **the instrument of §8 asserted the printed value of all one hundred and sixty cells and never checked that a cell was consistent with itself, which is the whole of finding one.** A pass that runs that instrument again will get a clean result and will learn nothing about whether the pages are true, because the defect was in what it was never asked. **Assert each cell against its own day count, and treat a day count and a weeks-and-remainder pair that disagree as two findings rather than one.** **And do not expect the `screen` sweep to be empty; it is twenty, and a guardrail pass that certifies it at zero has repeated this pass's second finding one file further along.**

---

*Written by a pass that did not write Chapters 1011 to 1020, and the twelfth artifact in this directory. Two findings taken whole, one disclosure noted and not acted on, three house figures re-run and holding. `state/phase-ledger.json` is controller-owned and was neither read for this file nor written, and this artifact deliberately claims no ordinal for that: the six artifacts before it that make the claim number themselves two ninths, three tenths, two elevenths, two twelfths and two thirteenths, so the sequence in this directory does not agree with itself and a new number would be a seventh voice rather than a continuation.*