# Review artifact — Volume 19, batch 0005, Movement V, Chapters 981 to 990

**Written in the review-repair phase of Volume 19 batch 0005, after the batch was written, measured, reviewed once and repaired once. The object under review is therefore a batch that has already been repaired, and the largest single defect found was in the repair pass's own measure of record rather than in the pages.**

**THIS ARTIFACT WAS WRITTEN BY A PASS THAT WAS NOT THE AGENT WHOSE WORK IT REVIEWS. `.opencode/agent/novel-reviewer.md` declares `mode: subagent`, `scripts/novel_runner.sh` invokes it as a primary agent, and the first line of `logs/batch-0005.review.log` is the platform reporting that it fell back to the default agent, which is the writer. That file and that script are controller-owned and were read and not written. This is the sixth artifact to record the fallback and the second in this volume.**

---

## 1. WHAT THE REVIEW RETURNED AND WHAT WAS DONE WITH IT

A phase review of the ten chapter files, the batch's `SUMMARY.md`, the five state files and `batch-0006/PROMPT.md` returned **three blocking findings, four to fix, and six nits.** All thirteen were confirmed by independent measurement before any of them was acted on. **Eleven reached a page and were repaired. Two were ruled out with the reason. One — the batch-wide single delivery mechanism — was taken as a finding and published without repair, and the reason is given at §4.**

**The two blocking defects in the measure of record are the finding of this artifact, and the prose defect is the largest any review in this volume has found on a page.**

---

## 2. THE THREE BLOCKING FINDINGS

### 2.1 Twenty-eight of the forty priced-work speeches were not English

**The review reported twenty-six; the correct figure is twenty-eight, and this artifact states twenty-eight because it was measured.** Two families:

- **Twenty welds.** A complete clause ends, no punctuation is written, and a second clause carrying its own subject and verb is attached with a space. `Every one of those is the same` + `are like it` + `, and one of them is a corner somebody has swept round a hundred times`. `All four of those are the same job` + `joints in that street have been made good twice`. `That is four times over in that row` + `in that row are`.
- **Eight stranded complements.** A subject and a verb with the predicate left off. `Four of those in that row` + `are` + `, and one of them has been a kitchen`. `Four of those pendants in that row are, and…`. `Four of those boards in that block are, and…`.

**The review's regression comparison is confirmed and it is the strongest form of the finding: Movements I to IV return zero of forty each, and these ten return twenty-eight of forty.** The house construction that carries it — `and one of them is` — is at **zero** occurrences on Movement I and Movement II and at **one** and **three** on Movements III and IV. **The twenty-eight files that carry the defect are these ten chapters and no others in the volume.**

**Why no instrument in this repository's record could see it.** Every duplication measure takes the last twelve tokens of a sentence, which is a proxy for a *repeated* run. A weld is not a repetition; it is a syntax error inside one file, and there is nothing for a cross-file key to collide with. **It is the same shape as the finding `batch-0002/SUMMARY.md` recorded about guardrail three's scope, and the same conclusion applies: a measure finds repetitions and this was not one. It was found by reading a sentence against itself.**

**Repaired in full.** The welds were given the full stop they were missing; the six that had no subject of their own were given one; the eight stranded complements were given the predicate the sentence had lost, taken from the fault named in the line immediately above them — `Four of those bells in that row are on the line itself`, `Four of those flexes in that row are twisted into themselves`, `Four of those boilers in that block are on a light switch`, `Four of those switches in that block are over a pipe`. **No price, no day total, no fault, no place and no four-year duration moved, and all forty prices were re-summed after the repair and still give their ten day totals of 326 pounds exact.**

### 2.2 A certification in the measure of record that its own pages contradict

`SUMMARY.md` §12 item 13 certified that **the speaker alternation had been broken on six of the ten days.** **It was never broken.** All ten files run a strict `she / he / she / he` across the four priced jobs, and no repair in this movement touched an attribution. The certification is struck in place and the fact is printed in its stead.

**This is the fifth recorded instance in this volume of a measure of record certifying something its own pages contradict**, and it is the second in this batch alone. The volume's record already holds Movement III's "zero number-words" and "ten objects on ten", and Movement IV's §5 duplication figures.

### 2.3 A denominator published under a claim of consistency its components do not bear

**Movement IV's whole-file token count exists at three values across three files: 25,167 in `batch-0004/SUMMARY.md`, 25,299 in `batch-0005/PROMPT.md` §5, and 25,084 in `batch-0005/SUMMARY.md`.** The fifty-file row was labelled **PASSES ITS OWN SUM TEST**. The arithmetic is true and the claim is false as a control, because it holds only after the disagreeing component has been silently replaced with a re-derivation.

**Measured, and the re-derivation is the correct one.** At the boundary this file prints, Movements I, II and III return their own published denominators to the token — 27,707, 20,852 and 23,850 — Chapter 960 reproduces at 1,028 / 1,326 / 2,354 exactly, and Movement IV returns **25,084**. `SUMMARY.md` §2 had already established *why*: `batch-0004`'s columns correspond to a line cut eight lines lower than the boundary that file describes in words. **So 25,084 was not an error and was not changed. What was wrong was the claim, and the claim is now replaced with a statement that the row is a measurement of this boundary, is not inheritable, and prints all three competing totals.**

---

## 3. THE FOUR TO FIX, AND THE SIX NITS

All four were confirmed and repaired:

4. **Guardrail one binds refusals, offers and costs at about nine words and was landing on the ceremonial beats.** `outline/volume-19.md` line 119 names exactly those three categories. The ceremonial yes at Chapter 984 is nine words and the central acceptance at Chapter 989 is fourteen. **Marek's refusal to be the one who asks on Chapter 981 was forty-five and his naming of the cost of moving the page on Chapter 986 was fifty-eight** — five and six times the guardrail, on the two beats this volume calls its hardest scene. Both repaired to thirteen and fourteen; the second half of the 981 refusal brought into the same register at twenty-one. **The surrounding dialogue, which carries the meaning, was not touched.**
5. **Chapter 990 inverted a house idiom into a contradiction of the sentence in front of it** — *No figure was spoken aloud in that city on that Thursday, and about four people have said since that there was one.* The house form is `have said so since`; the version on the page asserted the opposite of its own clause. Repaired.
6. **Chapter 987 contradicted its own date arithmetic.** She justified the day exactly — *a month is thirty days and today is the thirtieth* — and then called the same act *two days early*, which is her distance from a Wednesday and not from a month, and which her own next speech contradicts. Repaired to *on the thirtieth day*. **This is the sentence §12 item 4 certified as rebuilt and did not rebuild.**
7. **The same woman was four years and four months at the same counter.** Chapter 989 had a bystander say four years; Chapter 990 had her say four months in her own mouth; no page reconciled a factor of twelve. Repaired to four months **on the bystander's line**, because a character speaking about her own duration outranks a summary of it, and because the four-year motif on Chapter 989 belongs to Sera Quill and to the room. Her own page did not move.

Of the six nits, **four were real and repaired** — a corrupted `about four hundred times cheaper` with no referent and no precedent anywhere in the volume; an `already refused once this week` beside a correct `about three days ago`, where the refusal was on the Saturday of the previous week; an `about four months` of elapsed time that is thirty-five days; and single asterisks nested inside a bold run so that `*rows*` rendered as bold-italic.

**Two were false positives, and both are recorded because a pass acting on this review will meet them again.**

12. **`987:55` is not an unbolded speech.** Unbolded short speeches are this house's norm and there are **over a hundred of them across these ten files**; the bolding marks the weighted speeches, not the correct ones. **The instrument that would have caught this — counting bolded lines — is the wrong instrument, and a reviewer applying it to any movement in this volume will produce the same false positive on every short exchange on every page.**
13. **`989:186` does not close the book a chapter early.** *THE BOOK SHUTS* at Chapter 989 is correct: Chapter 989 is the seventy-first sitting and both §1 and §12 item 21 place the book shutting there. The reviewer read the register's book for the volume. The end-marker form is uniform across all ten files and no marker in this movement claims to be a movement's end except its own.

---

## 4. THE FINDING TAKEN AND NOT REPAIRED

**The retrospective-certification family is one narrative channel for nearly all the scene information in this movement: fifty-six instances, five verb variants, each clause carrying different content, and the chorus never in the room.**

The review was right that this is *not* §9's interchangeable-sentence case — a count of distinct observations, and a real structural fact about the movement rather than a matter of variety. **It was not repaired, and the reason is stated rather than defended: the construction is this house's own frame for what a room knows after a day, it is inherited at 38 on Movement IV and 67 on Movement III, and rebuilding fifty-six clauses across ten pages inside a repair pass would cost more of the movement's voice than the defect costs a reader.** §9 measures it, its two repair passes have taken it from seventy-eight to sixty, and Chapter 990 now carries none of it. **The volume close should read the family's shape and not only its count.**

---

## 5. WHAT THE REVIEW DID NOT FIND, AND IT IS THE SAME SHAPE SIX TIMES

**Six certifications in this batch's own measure of record were false before this pass began. Two were named by the review. Four were found while acting on it, and they are the substance of this artifact.**

| Where | What it certified | What was true |
| --- | --- | --- |
| §12 item 13 | the speaker alternation was broken on six of ten days | strict `she / he / she / he` on all ten, never varied |
| §12 item 2 | Chapter 984's `already refused once this week` was removed | the phrase was still on the page beside a correct three-day figure |
| §12 item 4 | Chapter 987's tray-date scene was rebuilt | one sentence of it still called the opening *two days early* |
| §5 | the fifty-file prose cell is zero at both paragraph rules | it is 2 and 1, both keys inherited from Movements I and II |
| §14 item 12 | this movement's own prose duplication is zero | two shared keys stood on Chapters 981/986 and 985/990 |
| §4 | the fifty-file row passes its own sum test | true of the arithmetic, false of the method |

**Two of the six were not merely wrong in a cell; they certified that prose was duplicated when it was not, and they were wrong about pages.** **The pre-repair tree was measured at commit `1e2f7e8` to establish which of the six were already false, rather than asserted, and all six were.**

**The two prose keys are the finding that generalises.** Both were the priced-work banner, on 981 against 986 on the Saturday and 985 against 990 on the Thursday — the same construction, differing only by weekday word, which is the mechanism §11 of that summary already names for the charge line. **Repaired on all four files. A third, Chapter 983 against Chapter 980, was inherited and did touch this movement's own page; repaired on Chapter 983, the later file, and Chapter 980 was left untouched, which is the convention §11 sets.**

**And the generalisation this artifact exists to record: five of the six were found by reading a sentence against its own page, and none was found by running a measure over the pages.** The one that was found by instrument — the fifty-file sum test — was found by asking what the components were, not by computing anything.

---

## 6. TWO INSTRUMENTS OF THIS PASS THAT WERE WRONG BEFORE THEY WERE CONTROLLED

**This is the sixth time this volume has recorded an instrument failing before it was controlled, and the first time one of the two failures would have produced a false *rejection* rather than a false acceptance.**

1. **A regular expression with a non-capturing group, used as if it captured.** `(?:she|he)` returns the whole match, not the alternation, so the alternation script reported `HHHH` on all ten files — the exact opposite of the truth, and it would have made the review's finding 2 look like a fabrication. **It was caught by printing the raw attribution lines instead of the derived ones.** The corrected instrument is the one in §5's first row.
2. **A number-word parser that did not split on hyphens**, so `fifty-eight` was one token and all 160 anchor rows of Chapter 981 reported unparsed. **It would have made the anchor table look unverifiable rather than verified.** Caught by running it on a known row.

**Both failed the same way both times: they measured something the printed boundary did not define.** The first did not capture what it appeared to capture; the second did not tokenise what the pages print.

---

## 7. WHAT WAS NOT DONE

**No batch was restarted. No scene was rewritten. No plot point moved and no outcome changed. No owner item was settled, recommended or opened, and no seventh was opened. No chapter of Movements I to IV or of any other volume was edited — `git status` shows ten chapter files in `batch-0005/`, that directory's `SUMMARY.md`, and four state files.** No debt of the nine, the seventeen or the four was paid, cancelled, opened or answered. The ring binder did not come down on any of the ten days. The register of correct acts that changed nothing stands at four and no fifth is printed. No two of the nine hand copies were compared. The woman of about thirty was not asked anything. **Iona Sorn is at zero on all fifty files of this volume, is in public custody, is unanswered and is not absolved.** No Exchange figure is printed on any page. The woman's page is `day − 1573`, it governs, and its figure is printed on no page.

**No next-phase prompt was created.** `workspace/volume-19/batch-0006/PROMPT.md` is on disk, correctly rejects the outline's *seventy-third sitting*, and places the seventy-second at Chapter 1000 on day 2212. `NOVEL_SPEC.md`, `outline/series.md`, `outline/ending.md`, `outline/volume-15.md` through `outline/volume-19.md`, `bible/*.md`, `.opencode/agent/`, `scripts/`, `.github/workflows/`, `AGENTS.md` and **`state/phase-ledger.json`** were read and not written, and the last of those is controller-owned. **This is the thirteenth artifact to flag `state/phase-ledger.json` rather than write it.**

---

## 8. WHAT THE FIGURES ARE NOW, AND THE ONE THAT DISAGREES WITH ITSELF

All of `batch-0005/SUMMARY.md` §§3 to 7 is re-derived after the repair. **The apparatus column did not move at all, which is the useful fact: all thirty-one prose edits landed in body scope.**

- Word table **15,802 body, 10,614 apparatus, 26,416 whole**, apparatus share 401.802 per thousand, body plus apparatus equal to whole on all ten rows.
- `about` **468** on **26,416**; 17.72 file scope and 17.72 pooled case-sensitively, 17.80 and 17.79 case-insensitively.
- This movement's ten: prose duplication **zero** on pair-hits and shared keys under both paragraph rules; apparatus **nine pair-hits and seven shared keys** under both.
- Guardrail three as the plan writes it, whole sentence as key: **zero** on this movement's ten at body scope, **zero** on its own ten at whole-file scope, and **315 pair-hits on 32 shared whole sentences** across all fifty files, **none on a Movement V page**.
- **One hundred and sixty anchor rows reproduce against their calendar origins; ten short-run intervals are the true value of their own day; forty prices sum to 326 pounds exact; the ten opening bands are unchanged at 57, 68, 73, 67, 52, 69, 53, 63, 68 and 48; `Iona Sorn` and all six other placed names are at zero; and every banned word is at zero.**

**The fifty-file guardrail-three cell has now been published at 309 pair-hits on 31 shared sentences and at 315 on 32, at an identical boundary, by two instruments.** A third figure for a nearby cell already stands in `state/continuity.md`. **All are in the low thirties and none of the three touches a Movement V page. The volume close must derive this figure once and print the instrument beside it**, which is the sixth time this volume has had to say that sentence about a duplication cell.

**And one figure that looked like a defect and is not.** `batch-0005/SUMMARY.md` §4 prints `10.98` in bold in Movement III's *mean of rounded* column. **It is correct and a later pass must not "fix" it.** That movement's unrounded mean of per-file rates is 10.98547 and rounds to 10.99; the mean of the same ten *after* each is rounded to two places is 10.98500 and rounds to 10.98. **Both are true of the quantity in their own column.** The retraction recorded against 10.98 in an earlier pass was a retraction of 10.98 in the PFILE column, where it was never true, and this pass verified the cell and left it alone.