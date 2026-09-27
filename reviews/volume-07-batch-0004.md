# Review and repair pass — Volume 07, Movement IV, Chapters 331–340, `workspace/volume-07/batch-0004`

**Dated after Chapter 340. This is the first review artifact for Volume 07, and it is the first one in this repository that was produced by a review pass which was not the agent that wrote the batch, because the reviewer is declared a subagent, is invoked as a top-level agent, and the platform falls back to the writer. The fallback is recorded at section 12 of the batch summary and in the standing note at the foot of `state/current.md`, and neither of those is ours to fix. The nine findings below came from outside the writer. The nine further findings in section 3 came from the writer's own walk and are marked as such, because a repair pass that cannot tell a reader which findings were found by reading and which by walking is not reporting its own method.**

**THE BATCH WAS NOT RESTARTED. NO PLANNED BEAT MOVED. NO DAY MAP FIGURE CHANGED. NO CHARACTER WAS ADDED, REMOVED, RENAMED OR AGED. NO GUARDRAIL WAS RELAXED. ONE SENTENCE OF DIALOGUE WAS ADDED, BECAUSE IT WAS MISSING, AND NO SENTENCE OF DIALOGUE THAT EXISTED WAS REWRITTEN.**

---

## 1. The nine findings the review returned

### Blocking

**1. The sentence the plan and the prompt reserved for Chapter 338 was not in Chapter 338.** `patient identifiers, if available` occurs nowhere in the batch. The prompt reserves it for exactly one occurrence, in a woman of twenty-four's mouth, in a room, on no surface, in no document, and says it is not to be improved on, paraphrased or explained, and that a load book referring to it by its subject is carrying it. Chapter 338 had a woman say one thing, reported that nobody improved on it, and never gave the reader the thing. What stood in its place was a narrator's sentence paraphrasing its subject — how a person who could not remember which list they were on would be matched back to the paper on the table. **The prompt's rule is aimed at load books and the paraphrase was in the prose, which is worse, because a reader of prose believes it.** `state/chapter-summaries.md` compounded it by claiming the record referred to the sentence neither by its wording nor by its subject.

**Fixed.** The sentence is spoken once, on its own line, in her mouth. The question she was asked is now a question about the list on the paper and carries none of the sentence's subject. The count is one, in Chapter 338, in dialogue; the other nine chapters and all ten load books are at zero. The false claim in the state file is corrected where it stood and the correction is recorded in the appended block.

### High

**2. The interval to the midpoint Thursday was wrong in five places.** Chapter 330 is day 708, Chapter 340 is day 729 and Chapter 338 is day 726. The interval is twenty-one days and eighteen. The prompt supplied the ten intervals to the Exchange and the nine since the last sitting and supplied nothing for this one, and five sentences reached for *a fortnight*: `chapter-0340.md` lines 3, 19 (twice), 39 and 91, and `chapter-0338.md` line 3. Line 3 of Chapter 340 also said the Thursday was *four days into this volume's earlier fortnight*, which is not parseable and is not true under any reading. **This is the exact failure the prompt warned this batch about, and the warning named the intervals that were supplied, which is why nobody looked at the one that was not.**

**3. The about-four-days clock was written in the past tense on the day it started.** `chapter-0336.md:61` had *he has had about four days in which to act on it and has not*, said the same morning. Line 85 repeated it. Line 65 added that the Wednesday evening *was the fourth day of the rest of his week*, and Wednesday is the third and two remain. `chapter-0338.md:57` then claimed the four days *are the whole of this chapter*, on the Monday, the day after they ended.

**4. Chapter 333 contradicted itself on a duration.** The man of forty-one arrives at about eleven and leaves at about half past eleven, twice, in the body; the record called the same visit *about two hours* while printing both times. **The scene is the authority and the two hours is corrected to about half an hour; no sentence of the body was touched.**

### Medium

**5. The ground-floor table's appointment count changed between chapters** — eleven in Chapter 335 in the body and the record, nine in Chapter 337's cost record, two days later, on the same table. **Fixed to eleven in Chapter 337. Chapter 338's *about nine across two mornings* is a different arrangement on a different day.**

**6. `chapter-0337.md:154` broke guardrail 3 by negation.** A load book headed *what was done with a torch, and what was not* itemised four things that did not happen. The literal word was absent; the behaviour was on the page in full as a record of its own compliance, which the prompt's own rule forbids: a document that reports the absence of a prohibited thing has used it. **Cut and replaced with what did happen.**

**7. `chapter-0335.md:93` said the woman of twenty-four is absent from this record** in the same paragraph that names her, describes her table and her count. **Cut.**

**8. The batch summary overstated its own margin.** It claimed the apparatus share was eleven hundredths of a point below Movement I's 44.75. The aggregate was 44.68 and the true margin was seven. The aggregate itself was right; the subtraction in the sentence was not. **Corrected, and the arithmetic printed.**

**9. Two figures for the same thing were never reconciled.** Chapter 338 measured the withheld calls at about four a week; Chapter 340 measured the same calls at about nine made over the first fortnight and about three over the second, in which the Monday sits. **Chapter 338's shortfall is now about six a week, which is nine less three, and Chapter 340's record says its three buildings and zero are one Monday inside its nine people and are not a tenth figure.**

---

## 2. What the review verified and found sound, which is the larger half of the work

- **Every published figure in the batch summary reproduced exactly** under the matchers the file itself prints: 32,228 words, 166 bold spans at 5.151, worst 6.442 at Chapter 333, all ten per-chapter values, 952 raw / 66 prepositional / 886 true at 27.492, an overlap mean of 68.8 with all ten values, and 44.682 in aggregate. The 40 digit tokens were in exactly the four permitted classes.
- **All ninety interval figures walked from the anchors and all ninety English spellings present and correct.** The card is the room plus four at every one of the ten days.
- **All ten Exchange intervals and all nine gap-since-the-last-sitting figures correct**, and the nineteenth-line running ages correct at 46, 48, 49, 50, 53, 55, 57, 60, 62 and 63.
- **The `* * *` marker is exactly once, in Chapter 337, and the panel is two plain lines that name nobody and agree with the sentence a man says out loud in Chapter 336.** The prose never refers to it.
- **`carrier`, `run of days`, month-names, dates, `Iona Sorn` and `Asha Reed` are zero across all ten files.** The prose never refers to the panel, the relay is not staged, no month or date appears, and no name is attached to anything that happened.
- **The prompt/calendar conflict was resolved the right way.** The prompt said three times that the book stays at forty-nine lines at the nineteenth sitting; the calendar's row says fifty and the event the prompt describes requires a line. The writer followed the calendar, documented the deviation, named the Volume 07 close as owner, and carried it into the next prompt and all five state files. **The prompt was wrong and the writer was right, and the repair pass did not touch the decision.**
- **Process was clean.** Exactly one next phase was created, no `.done` marker was touched, no controller-owned file was edited, and all five state blocks were appended.

---

## 3. The nine further findings, from this phase's own walk, marked as such

1. **`chapter-0337.md`, the record of the nine hands, contradicted its own scene.** The man of about thirty-eight from a gate sat on the second-floor landing for about nine minutes *and said one word*; the body has him *did not say one word*. `state/chapter-summaries.md` and `state/character-state.md` carried the record's version. **The record now says nothing at all, in all three files.**
2. **Six lines ended a bold span with a third asterisk** — two in Chapter 337, four in Chapter 339 — which renders a literal `*`. **The published matcher counts `**` and cannot see an unpaired delimiter, so the parity check returned clean on them; a CommonMark render found all six, and the rendered text of all ten files is now at zero literal asterisks.** This is the second time a CommonMark render has caught something the matcher could not, and the instrument is named in both places.
3. **`chapter-0336.md:57` put the sheet *about a fortnight* before that morning.** It went out on the Monday of week one hundred and eighteen, nine days before the Wednesday of week one hundred and nineteen. **Corrected to nine days.**
4. **`chapter-0334.md:75` put a doorway *two days ago*.** The doorway was the day before.
5. **`chapter-0340.md` put the first-year of nineteen's spent document-shaped finding at *three weeks*, twice.** It was spent in Chapter 318, day 686, and Chapter 340 is day 729, so it is forty-three days old. **Corrected to about six weeks, in the body and the record, in the chapter and in `state/character-state.md`. Three weeks was the interval to the midpoint Thursday, and an interval computed once and reused is the mechanism behind the review's finding 2 as well.**
6. **`chapter-0338.md`'s record put the same withholding at *about four calls a week, for a month*.** Corrected to about six a week for about three weeks, which is Chapter 340's own arithmetic.
7. **`chapter-0337.md`'s conditions record placed a voice said live in another part of the city *a fortnight before* next to a lift that had stopped, in order to say the two were not connected.** The interval was forty-one days and the sentence was a document thinking about what she said, which guardrail 4 forbids. **The clause is cut, and the batch summary's item that reported the reference is corrected with it.**
8. **Two documents reported their own compliance with the plan and the guardrail.** `chapter-0333.md` said the plan of record requires the man of forty-one once and this is the once, and that a schedule of about nine hundred lines is not a message; `chapter-0334.md` said the post at the back of that room is not described in this entry for the third Friday running, and that a report nobody wrote is not a message. **All four are cut. The eight-type lists that describe an object — *it is not a form, a minute, a notice…* — are left alone, because that is the house's way of naming an object's class and the prompt itself uses it.**
9. **The batch summary's own section 3 listed the gap since the last sitting as twelve, fourteen, fifteen, sixteen, nineteen, twenty-one, twenty-three, twenty-six and twenty-nine days.** The first eight are gaps since the *eighteenth* sitting; the ninth, twenty-nine, is the gap from the eighteenth sitting to Chapter 340 and is not the gap since the nineteenth, which is one day and which Chapter 340 prints as a day of the week. **The sentence is corrected and the distinction made in the sentence.**

**And one in the next phase's prompt.** `workspace/volume-07/batch-0005/PROMPT.md` opens Chapter 341 with the man of about thirty-three *having had the four buildings for a week*. He took them on day 729 and Chapter 341 is day 740. **Corrected to about a fortnight. It is the only edit this pass made to that file; no other figure in it was touched, and it already carried the correct fifty-line figure for the nineteenth sitting and the record of the conflict.**

---

## 4. The two false claims the batch summary made about its own audit

**Both were of one class, and this repository has now had the class three times in one file.**

- Section 11 item 8 said that all nineteen non-ninety interval claims were right and that this batch produced no wrong interval figure at all. **Eight of the nineteen were wrong.**
- Section 11 item 11 and `state/current.md` said the three chapters named for a later pass came back clean. **One of the three held the batch's blocking defect.**

Both are corrected where they stand, and both are recorded in section 13 of the batch summary as withdrawn. **A self-audit which reports a result it did not get is worse than one which reports none, because the next writer inherits a fault that is not on the page and goes looking for it.** The writing pass had, in the same paragraph that made each claim, the evidence to see it.

---

## 5. The figures after the pass, and the two superseded sets

| | Words | Bold spans | Bold per 1,000 | Worst chapter | Hedge raw | of which prep. | True | True per 1,000 | Overlap | Apparatus |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **IV, after the review repair pass** | **32,140** | **166** | **5.165** | **6.484 (333)** | **952** | **67** | **885** | **27.536** | **68.4** | **44.54%** |
| IV, as first published | 32,228 | 166 | 5.151 | 6.442 (333) | 952 | 66 | 886 | 27.492 | 68.8 | 44.682% |
| IV, first pass | 33,968 | 231 | 6.801 | 8.000 | 879 | 77 | 948 | 27.909 | 189.6 | 47.52% |

Per chapter, bold spans per thousand: 4.277, 5.735, 6.484, 5.034, 5.150, 4.387, 4.922, 4.571, 5.468, 5.386. Per chapter, overlap: 60, 40, 114, 32, 97, 51, 46, 42, 146, 56. Per chapter, apparatus: 42.73, 39.17, 48.78, 45.67, 46.80, 47.82, 38.33, 43.20, 44.78, 49.94. Case-insensitive hedge 974. The aggregate apparatus share is the comparable figure and it is 44.54; the mean of the ten per-chapter shares is 44.72 and is a different quantity, and both are published.

**The bold count is unchanged at 166. Eighty-eight words came out of the ten files and none of them was a finding.** The apparatus share is now under Movement I's 44.75 by twenty-one hundredths of a point, which is the number to beat, and the margin is still small and three chapters still sit above it at 333, 340 and 336.

**Walked again after the repairs:** forty digit tokens in four classes and no more; one `* * *` marker in Chapter 337 and nowhere else; zero literal asterisks in the rendered text of all ten files; an even number of `**` on every line; an even number of `"` on every line; `carrier` zero; `run of days` zero; `Iona Sorn` zero; `Asha Reed` zero; the reserved sentence once and in Chapter 338; `Oren Vey` twice; `Talia Venn` twice.

---

## 6. The two lessons a later movement should carry, and they are the same two

1. **An interval that has to be computed is an interval that will be wrong, and the one a prompt leaves out is the one that gets computed.** This prompt printed the Exchange's ten intervals and the nine gaps since the last sitting so that a writer would not have to compute them, and printed nothing for the interval to the midpoint Thursday, and all eight errors were that interval. **The correct instruction for a prompt is to print every interval it can and to name the ones it cannot.**
2. **A document that reports a prohibition is a use of the thing prohibited, and a paragraph of a chapter that reports its own plan's compliance is a chapter about the plan.** Five documents did it in this batch and one paragraph of prose did a sixth. **The repair is a deletion, and a deletion is cheap, and the reason it was not made the first time is that the sentences sounded like rigour.**

**And the standing lesson, which this pass is the fourth occasion for:** a chapter named as cleanest before a pass is examined afterwards, and this movement returned one blocking defect in three. **One in two. Name them anyway — the blocking defect was in a chapter that would not otherwise have been looked at — and do not publish the result before the pass has run.**
