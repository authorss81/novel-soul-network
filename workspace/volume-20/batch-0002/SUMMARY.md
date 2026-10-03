# Volume 20, Movement II — Chapters 1011 to 1020 — SUMMARY

**This file is the measure of record for this movement and the only file a later pass needs to measure these ten chapters against. It was written by the pass that wrote them and every figure below was re-derived from the saved files at the boundary printed at §2, after the repairs at §10, and again after the review-repair pass recorded at §10A, which repaired two anchor cells on two of the ten pages and two claims about a word sweep, one in the plan of record and one in the prompt dispatched to Movement III, and which touched no other line of any of these ten files. The plan of record is `outline/volume-20.md`. The day map's only home is `workspace/volume-20/ARITHMETIC-AND-CALENDAR.md` §1 and the ten rows at §3 were re-derived against that file's detectors and not read out of it.**

---

## 1. WHAT THIS MOVEMENT IS, IN ONE PARAGRAPH, AND WHAT IT IS NOT

**The woman of about forty-three who said the four words comes to a repair shop with a folded piece of paper and asks for it to be printed, and it is never printed, and every reason it is not printed is given by a person.** She wants it to stop being said and she cannot say how she knows it has been said wrongly, and she can answer three of the four questions a printer in a second district asks and cannot answer the fourth, which is the date, because she did not write the day down when she heard it. A man carries those four questions across a city to a floor of about eleven desks and asks them in about nine seconds each. A man with a clipboard puts a printed leaflet up on the lower of two clean rectangles in a fourth district at about half past six in the morning, on his own initiative, and says he has put about nine hundred of them up in that district and never taken one down. A woman of about fifty-four says nine words in a room off a line in Saltmarket and is not wrong. A man opens the drawer he keeps things in and explains that a drawer is not a promise and is not a refusal either, and that he has about nine things in it and cannot tell anybody which are his decisions and which are somebody's silence. A Wednesday evening in a repair shop has about nine people in it saying nothing at all for about an hour and a half, and a man behind a counter finds he cannot put that into a sentence and writes nothing down. **On the Monday of the seventh week, in front of six people, he says in about eleven words that he would have to sign nine words he has never read, and the piece of paper goes back inside a coat, and a woman of about forty-three says she is not going to argue with him and that there is no room in this city that will take her being told she was not mistaken.** On the last day a woman of about thirty-four goes into a queue after about three weeks of not going into one and is told, by the woman who said the four words, that it was not pretended.

**AND WHAT IT IS NOT.** It is not a chapter about a villain and there is none in it. It contains no form, no column, no heading, no list and no name on anything, and **the nine words of the correction are never printed on any of these ten pages**, and the paper is folded in a coat or in a plastic sleeve in every page it appears on. It does not decide whether the four words stop. It sets no heading on the fifth column and proposes none.

## 2. THE BOUNDARY, PRINTED ONCE AND USED THROUGHOUT, AND THE CONTROL THAT WAS RUN BEFORE THE INSTRUMENT WAS POINTED AT A PAGE

**The tokeniser is `[A-Za-z0-9]+(?:-[A-Za-z0-9]+)*`. The H1 line is removed, and the characters `*`, `` ` `` and `|` are removed. A hyphenated compound is one token. The tokeniser does not admit a colon, so a twenty-four-hour clock time counts as two tokens, and no page of this movement prints one — the sweep at §11 returns zero colon-clock forms. Body scope runs to the standalone load-book marker and apparatus scope runs from that marker to end of file; the two are disjoint and their sum is the whole file. The marker line itself is one token and it belongs to apparatus, because apparatus is said to begin *at* that marker and not after it.**

**THE INSTRUMENT WAS WRONG THREE TIMES BEFORE IT WAS RIGHT, AND TWO OF THE THREE WERE FOUND BY RUNNING IT ON A DIRECTORY IT HAD NOT OPENED.** First, the sentence splitter tested tokens for `.`, `!` and `?`, and the tokeniser admits no punctuation, so the splitter could never fire and every file's key was its own tail. Second, the marker was matched on `^\*\d{4}\.$`, and the entry numbers of earlier volumes are three digits, so the apparatus scope came back empty on Volume 19 and the whole measure returned zeroes about nothing. Third, the body and apparatus scopes were computed on markdown-stripped text, which deletes the asterisk that is the marker, so the split silently failed a second time. **The instrument now raises and stops if it cannot find a marker on a file, which is the only change made to it after it was right.**

**THE CONTROL, RUN BEFORE THE INSTRUMENT WAS POINTED AT A PAGE.** `workspace/volume-20/batch-0001/`, Chapters 1001 to 1010, same tokeniser, same split, same boundary.

| Scope | published at Movement I's §5 | this instrument | verdict |
| --- | --- | --- | --- |
| body, case-sensitive | 396 hits / 14,000 / 28.15 file / 28.29 pooled | 396 / 14,000 / 28.15 / 28.29 | reproduces to the digit |
| body, case-insensitive | 398 / 14,000 / 28.33 / 28.43 | 398 / 14,000 / 28.33 / 28.43 | reproduces |
| body, capital-form-only | 2 / 14,000 / 0.18 / 0.14 | 2 / 14,000 / 0.18 / 0.14 | reproduces |
| apparatus, case-sensitive | 55 / 9,518 / 5.72 / 5.78 | 55 / 9,518 / 5.72 / 5.78 | reproduces |
| apparatus, case-insensitive | 55 / 9,518 / 5.72 / 5.78 | 55 / 9,518 / 5.72 / 5.78 | reproduces |
| apparatus, capital-form-only | 0 | 0 | reproduces |
| whole file, case-sensitive | 451 / 23,518 / 19.04 / 19.18 | 451 / 23,518 / 19.04 / 19.18 | reproduces |
| whole file, case-insensitive | 453 / 23,518 / 19.13 / 19.26 | 453 / 23,518 / 19.13 / 19.26 | reproduces |
| whole file, capital-form-only | 2 / 23,518 / 0.09 / 0.09 | 2 / 23,518 / 0.09 / 0.09 | reproduces |
| word table, three totals | 14,000 body / 9,518 apparatus / 23,518 whole | 14,000 / 9,518 / 23,518 | reproduces |
| duplication, prose, breaks kept | 407 / 0 — published as the **drops** row; see §6 | — | **see §6, this cell does not reproduce** |
| duplication, prose, breaks kept | 438 / 0 pair-hits | 438 / 0 | reproduces on the pair-hits |
| duplication, apparatus, breaks kept | 168 / 0 | 168 / 0 | reproduces |
| duplication, whole file, breaks kept | 606 / 0 | 606 / 0 | reproduces |

**AND THE SECOND CONTROL, AT SIXTY FILES.** All sixty files of Volume 19, same code, same boundary.

| Scope | paragraph rule | this instrument | against Movement I's §2 |
| --- | --- | --- | --- |
| prose | breaks kept | 2,649 keys, 8 pair-hits | eight, reproduces exactly |
| apparatus | breaks dropped | 1,024 keys, 792 pair-hits | published 1,039 / 795 |
| apparatus | breaks kept | 1,041 keys, 789 pair-hits | published 1,039 / 795 |
| whole file | breaks kept | 3,689 keys, 798 pair-hits | published 3,688 / 803 |
| guardrail three, whole-sentence key | — | 3,772 keys, 309 pair-hits on 31 shared | published 3,550 / 315 on 32 |

**AND THE RESULT OF THE CONTROL IS STATED PLAINLY: the instrument is not a reproduction of the instrument Movement I used, and on five cells it is close and on one it does not reproduce, and the difference is in the distinct-key count, which is a denominator, and not in the sign of any finding.** On the sixty-file control it returns **eight prose pair-hits, which is Movement I's published figure to the digit**, and **309 pair-hits on 31 shared sentences against a published 315 on 32**, and **798 whole-file pair-hits against a published 803**. The `breaks dropped` row is the one that does not reproduce: this instrument removes the paragraph break outright before segmenting, which merges a paragraph's last sentence into the next paragraph's first, and Movement I's does not, and the two definitions are not recoverable from Movement I's file. **The breaks-kept row is therefore the reporting basis for §6 and the breaks-dropped row is published beside it and is labelled.**

**The rule this volume inherited stands and was applied: control an instrument against a measure of record that already exists, then read the thing the instrument found, because the number is the receipt and not the result.**

## 3. THE DAY MAP, TEN ROWS, RE-DERIVED AND NOT READ

| Movement | Chapter | Day | Week | Weekday | Load-book entry | Governed counter |
| --- | --- | --- | --- | --- | --- | --- |
| II | 1011 | 2232 | 335 | Tuesday | 1014 | 256 |
| II | 1012 | 2233 | 335 | Wednesday | 1015 | 257 |
| II | 1013 | 2235 | 335 | Friday | 1016 | 258 |
| II | 1014 | 2237 | 335 | Sunday | 1017 | 259 |
| II | 1015 | 2238 | 336 | Monday | 1018 | 260 |
| II | 1016 | 2240 | 336 | Wednesday | 1019 | 261 |
| II | 1017 | 2242 | 336 | Friday | 1020 | 262 |
| II | 1018 | 2243 | 336 | Saturday | 1021 | 263 |
| II | 1019 | 2245 | 337 | Monday | 1022 | 264 |
| II | 1020 | 2246 | 337 | Tuesday | 1023 | 265 |

**Ten rows, ten re-derivations, ten reproductions.** `week = (day − 502) // 7 + 88` and `wd = (day − 502) mod 7`, Monday-first. `(entry − chapter) = {3}` and `(counter − chapter) = {−755}` on all ten. A second instrument asserts each file's own H1 chapter number, its standalone marker, its load-book header weekday and week, its ordinal day-of-this-stretch, its printed closing `*END OF MOVEMENT II, CHAPTER n. WEEKDAY OF WEEK w. LOAD-BOOK ENTRY e.*` line, and all five agree on all ten rows. **Days 2234, 2236, 2239, 2241 and 2244 carry no chapter and the instrument does not treat any of them as a rehearsal for anything.**

**The one Sunday of this movement is Chapter 1014 at day 2237 and it is the only one of these ten days on which the shutter comes down at about two.** The other nine take the about-ten form and all ten say so in their own words. **The seventy-third sitting fell on Chapter 1016 at day 2240 and the book lay open in that shop from about half past six until about a quarter to ten; no sitting number is printed on any of these ten pages, no figure for the book or the tin is printed on any of them, no difference between them is printed, and no page of this movement remarks on anything about them.**

## 4. THE WORD TABLE, ALL TEN ROWS, WITH A SUM TEST

| Chapter | Body | Apparatus | Whole |
| --- | --- | --- | --- |
| 1011 | 2390 | 944 | 3334 |
| 1012 | 2424 | 955 | 3379 |
| 1013 | 2228 | 989 | 3217 |
| 1014 | 1539 | 981 | 2520 |
| 1015 | 1785 | 980 | 2765 |
| 1016 | 1574 | 1011 | 2585 |
| 1017 | 1969 | 956 | 2925 |
| 1018 | 1234 | 964 | 2198 |
| 1019 | 2232 | 988 | 3220 |
| 1020 | 1864 | 1003 | 2867 |
| **Total** | **19,239** | **9,771** | **29,010** |

**19,239 + 9,771 = 29,010 with nothing in either column twice.** Apparatus share 336.88 per thousand of the whole file. **These are measures of ten files. The measure of record for Volume 20 is not written yet and is owed to the Volume 20 close at `workspace/volume-20/close/CLOSE.md`, and a pass writing Chapter 1021 must not carry any figure in this table into a page.**

**THE THREE BIGGEST PAGES AND WHY, AND ONE FIGURE THAT IS A FINDING.** Chapter 1012 is the largest at 3,379 because it carries the whole of the printer's four questions and the argument about a date; Chapter 1011 is next at 3,334 because the woman arrives with the paper and the three ways forward are set out in one evening; Chapter 1013 is third at 3,217 because it carries a floor of about eleven desks, a bus of about twenty minutes each way and a leaflet going up in a passage. **Chapter 1018 is the smallest at 2,198 and it is the only page in this movement with almost nobody in it from the matter, and it is the busiest day the shop has ever had, at sixteen callers and fifty-eight pounds, and the two facts are on the same page and neither is remarked on.**

**AND THE MOVEMENT'S PAGES ARE LONGER THAN MOVEMENT I'S, WHICH IS A FINDING AND NOT A STYLE.** Movement I's ten files total 23,518 whole-file tokens and this movement's total 29,010, which is twenty-three per cent more on ten pages of the same book, and the excess is almost entirely in the body, which runs 19,239 against Movement I's 14,000, thirty-seven per cent more. **The cause is on the page and is a fact about the two movements: Movement I's engine is a discovery, and a discovery is short because nobody knows anything and everybody says a little; Movement II's engine is an argument between people who have each already found something out, and an argument runs long because each of them has to be answered.** The apparatus share fell from 404.7 per thousand to 336.9 for the same reason. **No page was padded to produce this and no page was cut to remove it.**

## 5. `about`, AT THREE SCOPES AND UNDER ALL THREE CASE CONVENTIONS, WITH THE DENOMINATOR BESIDE EVERY CELL

| Scope | Convention | Hits | Denominator | File-scope | Pooled |
| --- | --- | --- | --- | --- | --- |
| body | case-sensitive | 638 | 19239 | 33.51 | 33.16 |
| body | case-insensitive | 641 | 19239 | 33.72 | 33.32 |
| body | capital-form-only | 3 | 19239 | 0.21 | 0.16 |
| apparatus | case-sensitive | 92 | 9771 | 9.40 | 9.42 |
| apparatus | case-insensitive | 92 | 9771 | 9.40 | 9.42 |
| apparatus | capital-form-only | 0 | 9771 | 0.00 | 0.00 |
| whole file | case-sensitive | 730 | 29010 | 25.30 | 25.16 |
| whole file | case-insensitive | 733 | 29010 | 25.43 | 25.27 |
| whole file | capital-form-only | 3 | 29010 | 0.13 | 0.10 |

**PFILE is the mean of the ten per-file rates and PPOOL is the concatenated files counted once. The two are different quantities and both are printed.**

**Per file, whole-file scope, all three conventions:**

| Chapter | Whole-file tokens | case-insensitive | rate | case-sensitive | rate | capital-only |
| --- | --- | --- | --- | --- | --- | --- |
| 1011 | 3334 | 80 | 24.00 | 80 | 24.00 | 0 |
| 1012 | 3379 | 79 | 23.38 | 79 | 23.38 | 0 |
| 1013 | 3217 | 80 | 24.87 | 80 | 24.87 | 0 |
| 1014 | 2520 | 71 | 28.17 | 71 | 28.17 | 0 |
| 1015 | 2765 | 75 | 27.12 | 75 | 27.12 | 0 |
| 1016 | 2585 | 65 | 25.15 | 65 | 25.15 | 0 |
| 1017 | 2925 | 70 | 23.93 | 69 | 23.59 | 1 |
| 1018 | 2198 | 61 | 27.75 | 59 | 26.84 | 2 |
| 1019 | 3220 | 81 | 25.16 | 81 | 25.16 | 0 |
| 1020 | 2867 | 71 | 24.76 | 71 | 24.76 | 0 |

### 5.1 THIS MOVEMENT IS ABOVE THE STANDING TARGET AND THIS FILE SAYS SO INSTEAD OF FIXING IT

**Twenty-five and twenty-seven hundredths pooled, twenty-five and forty-three hundredths at file scope, case-insensitively, against the standing target of nineteen. That is a deviation of about a third and it is the largest single finding in this movement and it is not repaired.** Movement I sits at nineteen and twenty-six hundredths pooled; Volume 19's sixty files sit at fifteen and thirty-nine. **The cause is located and it is not diffuse.** The word does three jobs in this book and only one of them is a hedge: it is the uncertainty register for a claim about how many witnesses there are, it is the designation idiom in *the woman of about forty-three* and *the man of about sixty-one*, and it is the clock and duration register in *at about half past seven* and *for about four years*. The designation idiom and the job formula account for most of the count and both scale with the length of the pages, and this movement's pages are twenty-three per cent longer. The excess over Movement I after that adjustment is in the dialogue, and **the reason is that this movement is about how well people know something and the house's way of hedging a claim in a person's mouth is this one word.**

**AND WHAT THIS PASS DID NOT DO, WHICH IS THE DECISION.** It did not run a mechanical substitution over ten files it had just written, and the reason is the one at `NOVEL_SPEC.md`'s fifth Status block: an instrument that damages prose must not be run first, and a hedge pass that rewrites prose and then reprints the rate is the exact failure this repository has already paid for once. **The figure is published here, the per-file table is published so that a later pass can see which pages carry it, and the decision about whether nineteen is the target for this volume is left where it belongs, which is to the Volume 20 close at sixty files.**

**The three capital-form hits are sentence-initial and none of them is a hedge.** Two are on Chapter 1018 — `About four people who come to that shop have said since` and `About nine hours of it was ordinary work` — and both are the reporting register rather than a claim about a number, and one is on Chapter 1017 in the middle of a sentence, `About the one with the holder`, where the capital is a full stop's worth of emphasis and not a figure. They are published because the house publishes the third case convention and not because any of them is a fault.

## 6. THE DUPLICATION MEASURE, BOTH PARAGRAPH RULES AND BOTH COUNTING CONVENTIONS IN THE SAME PLACE AS EVERY CELL

**A run of twelve words or more, taken at the last twelve tokens of every sentence, lowercased, over all forty-five pairs within the ten files.**

| Scope | Paragraph rule | Counting convention | Distinct keys | Pair-hits |
| --- | --- | --- | --- | --- |
| prose | breaks dropped | strict | 277 | 0 |
| prose | breaks dropped | quote-skipping | 277 | 0 |
| prose | breaks kept | strict | 548 | 0 |
| prose | breaks kept | quote-skipping | 548 | 0 |
| apparatus | breaks dropped | strict | 152 | 0 |
| apparatus | breaks dropped | quote-skipping | 152 | 0 |
| apparatus | breaks kept | strict | 163 | 0 |
| apparatus | breaks kept | quote-skipping | 163 | 0 |
| whole file | breaks dropped | strict | 429 | 0 |
| whole file | breaks dropped | quote-skipping | 429 | 0 |
| whole file | breaks kept | strict | 711 | 0 |
| whole file | breaks kept | quote-skipping | 711 | 0 |

**ALL TWELVE CELLS ARE ZERO ON PAIR-HITS and the two counting conventions are equal on every row of both tables, and that equality is disclosed rather than presented as a finding: this manuscript writes dialogue inside a bold marker whose quotes are stripped by the tokeniser, so a key inside a spoken line and a key inside a narrated line are the same key to this instrument, and the convention has nothing to skip.** Volume 19's close published a difference of eight and four between the two conventions at sixty files and this movement has no such difference, and the reason is structural and is not a merit.

**AND WHAT THIS MEASURE CAUSED, WHICH IS FORTY PAIR-HITS ON THE FIRST RUN AND NONE AFTER THE REPAIRS, ALL OF THEM IN THE CLOSING APPARATUS AND ONE IN A SCENE.** The first run returned **thirty-four apparatus pair-hits and six prose pair-hits**. The apparatus exposure was the same nine closing frames that Movement I repaired, and on ten files with no prior repair they came back: the ninth-chair sentence on nine of the ten files in two wordings, the ten-objects lead-in on five in two wordings, the dated-rule sentence on seven, the card's entry among the ten objects on six in three wordings, the out-of-ten list on seven, the dark-room sentence on two, the book-and-tin sentence on two, the binder sentence on two, and the "to the day" run on the two files whose four-units row is a whole-week row. **The prose exposure was one long verbatim quotation on Chapter 1013, in which Marek repeats a printer's sentence word for word, and one shutter sentence on three files, and one binder sentence on two, and one jobs lead-in on two.** Every one is repaired and the ten closing frames are now written in ten different shapes each.

## 7. GUARDRAIL THREE, MEASURED AS THE PLAN WRITES IT AND NOT AS THE PROXY

**Guardrail three as `outline/volume-20.md` writes it is the whole normalised sentence as the key with a twelve-token floor, and not the last-twelve-tokens proxy.**

| Measure | Key | Floor | Scope | Distinct keys | Pair-hits | Shared keys |
| --- | --- | --- | --- | --- | --- | --- |
| guardrail three, as the plan writes it | whole normalised sentence | 12 | prose | 548 | **0** | **0** |
| guardrail three, as the plan writes it | whole normalised sentence | 12 | apparatus | 163 | **0** | **0** |
| guardrail three, as the plan writes it | whole normalised sentence | 12 | whole file | 711 | **0** | **0** |
| the last-twelve-tokens proxy, for comparison | last twelve tokens | 12 | whole file | 711 | 0 | 0 |

**Zero on both, and the two measures did not agree on the way there.** Before the repairs the last-twelve proxy returned forty pair-hits and the whole-sentence key returned seven, all five of the extra seven sitting in the same nine closing frames. The two point at the same defects at two resolutions and all are repaired. The flat whole-file test, in which one key is compared against all forty-nine other pairs at once, returns zero shared keys on these ten files. **Volume 19's close published 315 pair-hits on 32 shared whole sentences at sixty files, so this movement's zero is not a claim about the manuscript.**

## 8. THE STANDING ANCHORS TABLE, DECLARED A SCOPE OF ITS OWN, ONE HUNDRED AND SIXTY ASSERTIONS

**This table is invisible to both measures above and it is the longest block on every page in this volume and in every volume from Volume 15 onward. It is declared here as a named scope of its own so that it stops being invisible.** Sixteen origins, unchanged from Volume 19 and continuous with Chapter 1000's own docket at day 2212. **The instrument composes a cardinal renderer and a weeks renderer, including the zero-remainder form `to the day`, and asserts the printed value of all sixteen rows on all ten files: 160 of 160 reproduced. That certification was FALSE when this file was written and is true only after the repair at §10A, which corrected two of the 160 cells; a pass that inherits the figure and not the correction will find 158 of 160 against the pages as this pass first wrote them. [Corrected at §10A: the version before it read *160 of 160 reproduced* with no mention of the two cells, and the figure it published for the day map, the price table, the caller counts, the short-run anchors, the sheet nights and the distribution below was right on every one of them, so nothing else in this section moved.]** It also reads the day back out of the first row of each file, derives the week and weekday from it, and asserts the file's own header, ordinal and closing line against that derived day.

**The control is Chapter 1000's own docket at day 2212, re-derived from the same sixteen origins, and four of the sixteen were picked out and all four reproduce the printed page exactly** — the first row reads one thousand eight hundred and fifty days, two hundred and sixty-four weeks and two days, which is `2212 − 362`; the second reads one thousand eight hundred and fifty-four days, two hundred and sixty-four weeks and six days, which is `2212 − 358`; the fourteenth reads one thousand four hundred and sixteen days, two hundred and two weeks and two days, which is `2212 − 796`; and the sixteenth reads one thousand two hundred and thirty days, one hundred and seventy-five weeks and five days, which is `2212 − 982`. **The control is run at the same boundary as the measure because a control run at a different boundary is not a control.**

**How the sixteen rows distribute across these ten pages is arithmetic on the origins and not a writer's decision, and the distribution is not uniform, which is the point.** Eighteen of the 160 rows come out as exact whole weeks and the other 142 do not, and by file the exact-week count runs **zero, three, three, zero, three, three, three, zero, three, zero** for Chapters 1011 to 1020. **Chapters 1011, 1014, 1018 and 1020 carry no exact-week row at all**, and **Chapters 1015 and 1019 carry four occurrences of the string `weeks to the day` against three exact-week rows each, because their four-units row reads to the day and the prose paragraph repeats that one figure in words, which is the house's arrangement and which the instrument asserts.** The uniformity of a docket is not the uniformity of a page, and neither is the uniformity of the distribution of whole weeks across ten days.

**THE THREE SHORT-RUN ANCHORS THAT CARRY THIS VOLUME, AND ALL THREE ARE NON-UNIFORM ACROSS THE TEN DAYS.** The sheet that was on the passage wall is `day − 2189` and stands at forty-three days old on the first day of this movement and fifty-seven on the last, **and it has been off that wall since the Thursday of week 334 at about nine in the morning and does not go back up, and every page states it as an age and states that it is in a bag, and no page says that a sheet is still on that wall.** The second hundred and fifty sheets, printed by a building in a second district, is `day − 2203` and stands at twenty-nine days old on the first day and forty-three on the last; **they were never on that wall and their whereabouts are still not known and were not looked for on any of these ten days, and the two figures are never added.** The thing said at a counter in a first district is `day − 2212` and stands at twenty days old on the first day of this movement and thirty-four on the last; **the origin is the day the Volume 19 close printed it as a fact and not the day it was said, and the day it was said is printed on no page of this movement.**

### 8.1 THE NIGHTS OF THE SHEET WITH THE EMPTY FIFTH COLUMN, AND A DISCONTINUITY THIS PASS CHOSE NOT TO PROPAGATE

**The copy of that sheet with an empty fifth column runs on Marek's table. It was on that table on ten nights out of ten of this movement, it was never moved into a drawer, nobody in that shop holds it, and no page of this movement asked Marek to move it.** Movement I printed it as its sixty-seventh night at Chapter 1001 through to its seventy-sixth at Chapter 1010, and **that printed run steps by exactly one per chapter across the two chapterless days inside Movement I's span, which means it is a chapter-indexed count and not a count of nights.** `day − 2150` gives seventy-eight on Movement I's last day, not seventy-six.

**This movement's ten pages print the figure derived from the day: eighty-two, eighty-three, eighty-five, eighty-seven, eighty-eight, ninety, ninety-two, ninety-three, ninety-five and ninety-six. The two runs therefore disagree at the join by four and the disagreement is on the page and is not smoothed over.** The reason for choosing the derived figure is that a night elapses on a day that carries no chapter, and printing a run that skips two nights inside four days asserts something that cannot happen. **The alternative was available and was rejected: the house has an explicit chapter-indexed convention for one of these two figures and not for the other, being *the second hundred and forty-sixth day of this stretch of days*, which is `chapter − 755` and which the instrument asserts on all ten files; it has no such convention for nights. Movement I's five later pages were not edited, because a batch on disk is audited and not rewritten, and the defect is therefore left standing on five pages and recorded here.**

### 8.2 THE PLACE BEHIND THE WOMAN'S CHAIR

**It is named on Chapter 1015 alone of these ten files and on no other, and it carries no printed figure on any page of this movement.** Marek looks at it while the woman of about fifty-four is not talking, does the sum with his hands behind his back, and does not say it out loud, and about four people in that room have said since that they did not know what he had worked out and that one of them has since asked him about it and he said he had not. **The sweep at §11 returns the phrase on one file and on no other, and returns a figure for it on none.**

**AND THE TRAP THIS FILE WALKED INTO AND DECLINED IS ON THE RECORD.** `day − 1484` comes to a round whole number of weeks on day 2254, which is Chapter 1023 and a Wednesday inside Movement III's span, as `workspace/volume-20/ARITHMETIC-AND-CALENDAR.md` §2 states. **It also comes to a round whole number of weeks on day 2233, which is Chapter 1012 and one of these ten files.** That is not in the calendar file and was not looked for; it fell out of deriving all one hundred and sixty rows and noticing that four files of this movement carry an exact-week row on the fourteenth origin. **Chapter 1012 is the file in which a writer would most have wanted to print it, and it prints no figure, and the row reads as any other row reads.**

## 9. WHAT THE MOVEMENT SPENT, AND WHAT IT DID NOT SPEND

**SPENT, ON THE PAGE, IN THIS ORDER.** A woman of about forty-three puts nine words on a counter in a coat and does not let anybody read them. Three ways forward are set out and one of them is hers. A floor of about eleven desks is given three answers out of four. A man with a clipboard puts up about nine hundred leaflets in a district and has never taken one down. A woman of about forty-three sits on a chair against a wall for forty minutes and is asked one question at the door. A woman of about fifty-four says nine words in a room and is not wrong. Nine people say one sentence between them on a Wednesday. A printer opens a drawer with about nine things in it and cannot tell anybody which are his decisions. A man with a ladder has a stair light that has been wrong for about sixteen years. **Marek says, in about eleven words and in front of six people, that he would have to sign nine words he has never read.** Nobody argues with him. A woman of about thirty-four goes into a queue and is told it was not pretended.

**NOT SPENT, ON ANY PAGE.** **The woman's page.** It is printed on no page of this movement, no value and no range for it appears in this file or in any of the ten chapter files, and the ring binder did not come off its shelf on any of the ten days and nobody apologises to her. **The four arrival cells**, which are not in these files and are not approximated. **The fifth of the register of correct acts that changed nothing**, which is printed as the figure four at both ends of all ten days and is added to by nothing. **Any Exchange figure**, and the difference between the book and the tin, which is printed nowhere. **The nine words of the correction**, which are described on four pages and written out on none, and the date on them, which is described and not printed. **A comparison of two of the nine hand copies**, of which there is none. **The heading of the fifth column**, which is owner item 4, is unruled, and this movement shows a woman of about forty-three want to stop a thing being said and is shown nothing being set in its place. **Any sentence about what the institution is for**, and the nearest thing to one in these ten files is a man behind a counter who cannot put an evening into a sentence and does not try.

**AND THE SIX OWNER ITEMS ARE ALL UNRULED AND NONE IS SETTLED, RECOMMENDED OR RE-DERIVED HERE.** Plan against disk — the plan says seven hundred and sixty chapters in fifteen volumes and the disk holds one thousand and twenty. The support-spend overage at three readings. The placed cast of five names, at zero on these ten pages, **and no page was invented for any of them in order to make a cast figure come out; the reason is that none of the five is a care worker at a desk, a man with a clipboard, a printer, or a woman who has sat at the same desk for years.** The plan's phrase on Chapter 933. The fifth column's heading, two items and not one. **The ombud's office used on him zero times in this movement, and this file makes no statement about how many times it has been used in this manuscript.** And whether Chapter 760, Chapter 1000 or Chapter 1060 is this manuscript's ending. **Writing ten chapters did not decide the last one and this summary does not decide it and a directive is not a decision.**

**`NOVEL_SPEC.md`, `outline/series.md`, `outline/ending.md`, `outline/volume-15.md` through `outline/volume-19.md`, `bible/*.md`, `workspace/volume-19/ARITHMETIC-AND-CALENDAR.md` and `state/phase-ledger.json` were read and not written, and the last of those is controller-owned.** No page of Volume 15, 16, 17, 18 or 19 was edited. `state/complete.md` was not written and the declaration that the manuscript is finished remains the owner's decision. No flag about `state/phase-ledger.json` is appended anywhere in this file or in any of the ten chapters.

## 10. WHAT THIS PASS CHANGED, AND WHAT IT FOUND

1. **The instrument was pointed at a directory it had not opened and returned zeroes about nothing, twice, and the second time it did so after the first had been fixed.** §2 item 2 and item 3. Both were found because the word table came back with an apparatus column of zero on a set of files that obviously have one. **The instrument now stops rather than returning a zero it cannot justify, and the only change made to it after that was that.**
2. **One cell of the published control does not reproduce and is labelled rather than absorbed.** §2. The `breaks dropped` duplication row returns 429 distinct keys against a published 575 at the same ten files, because this instrument deletes the paragraph break before segmenting and Movement I's does not. **The breaks-kept row reproduces exactly on all three scopes and the sixty-file control returns eight prose pair-hits against a published eight.**
3. **Forty duplication pair-hits on the first run and none after, and thirty-four of the forty were in the closing apparatus in the same nine frames Movement I had already repaired once.** §6. Nine files now carry nine different ninth-chair sentences, ten different ten-objects lead-ins, ten different card entries and ten different dated-rule sentences. **The one prose defect that was not in an apparatus was a verbatim quotation of a printer's sentence inside Marek's mouth on Chapter 1013, and it is repaired by having Marek paraphrase him, which is also what a man does when he is summarising something he heard four hours ago.**
4. **Twenty-eight uses of the word `right` and one of `fair` on the first write, all repaired, so that both are at zero on all ten files.** Chapter 1019's climax is about a woman being right and had to be built out of *not wrong*, *had it*, *was telling the truth* and *was not mistaken*, and the two fixes that cost most were the printer's beat on Chapter 1017, where a man tells Marek not to say *all right* like that and had to become not to say *yes* like that, and Marek's `he was right about me and I have been wrong about him`, which became `he had me and I had him wrong`. **This is the fifth batch in a row in which a forbidden word has been found in a scene rather than in a frame, and it is the first in four batches in which one was found in the movement's climax.**
5. **Two month-names and one prohibited instrument in a negation, all repaired.** Chapter 1016 printed *in about February* and Chapter 1019 printed *in November*, and Chapter 1012 opened its second scene with *he had not telephoned and had not written*, which is guardrail five's explicit prohibition on naming a prohibited thing in any negation. **A whole-word month sweep returns ten hits and all ten are the modal verb `may`, which is not a month-name, and the stem sweep returns 228 across nine containing words.**
6. **One docket cell wrong on the first write and corrected before the chapters were finished.** Chapter 1020's sixteenth row read `1664 days, two hundred and thirty-seven weeks and five days` against a derived `1674 days, two hundred and thirty-nine weeks and one day`. **The cause was hand-typing and not the renderer, and the repair was to splice all sixteen rows on all ten files from the detectors rather than to correct one cell by eye. That is the fifth recorded instance in this repository of a day-map or anchor cell disagreeing with the instrument and repaired in the same pass that wrote it. [Amended at §10A: the splice did not in fact reach two of the 160 cells, so the claim that all sixteen rows on all ten files were spliced was false on those two, and §10A's two repairs are the sixth and seventh recorded instances of this class and neither was found before the chapters were finished.]**
7. **Six of the ten jobs lead-ins were the same sentence with the weekday changed, and the duplication measure returned zero on all six of them.** The prompt named this frame as the one a writer is most tempted to copy and Movement I's own record says it was Movement I's single largest exposure, twenty-eight pair-hits across eight files. **Five of the six are now written in five different shapes, and the measure could not see any of them, which is the finding: a measure keyed on a twelve-token run cannot see a frame that shares its first eight words and its last six.**
8. **A whole-week day inside this movement that the calendar file does not name.** §8.2. Chapter 1012 is one, and it carries no figure for the thing it would have printed.
9. **The nights of the sheet with the empty fifth column disagree with Movement I's printed run by four at the join, and this pass chose not to propagate the error and did not rewrite the five pages that carry it.** §8.1. The two runs are printed side by side in this file and the discontinuity is on the page.

## 10A. THE REVIEW-REPAIR PASS, WHAT IT FOUND, WHAT IT CORRECTED, AND WHAT IT REFUSED

**THIS PASS WAS RUN BY A REVIEW THAT WAS NOT THE PASS THAT WROTE THESE TEN CHAPTERS, AND IT TOOK BOTH OF ITS SUBSTANTIVE FINDINGS. NEITHER WAS A MATTER OF PROSE, AND NEITHER TOUCHED A SENTENCE OF ANY CHAPTER.**

**FINDING ONE, AND IT WAS FOUND BY RUNNING THE INSTRUMENT OF §8 OVER ALL 160 CELLS AND READING EACH CELL AGAINST ITS OWN DAY COUNT, WHICH IS A TEST NO FIGURE IN THIS FILE HAD BEEN SUBJECTED TO.** The instrument of §8 asserts the printed value of the sixteen rows against the origins. **The instrument did not check that each printed row is arithmetically consistent with itself**, and two cells were not. `chapter-1012.md` printed `1419 days, two hundred and three weeks and six days`, which is 203 × 7 + 6 = 1427, and `chapter-1017.md` printed `1576 days, two hundred and twenty-five weeks and two days`, which is 225 × 7 + 2 = 1577. **The day counts are right in both and only the weeks-and-remainder pair is wrong, because part of the pair was taken from the neighbouring file and the day count was left alone.** The first of the two takes its weeks figure, and only its weeks figure, from Chapter 1013's own row of the same origin, which reads `1421 days, two hundred and three weeks to the day`; the second takes its remainder from Chapter 1018's own row of the same origin, which reads `1577 days, two hundred and twenty-five weeks and two days` and is correct.

**THE REPAIR IS TWO NUMBERS ON TWO PAGES AND NOTHING ELSE.** `chapter-1012.md` now reads `1419 days, two hundred and two weeks and five days`, and `chapter-1017.md` reads `1576 days, two hundred and twenty-five weeks and one day`. **No day moved, no origin moved, no header moved, no ordinal moved, no closing line moved, no price moved, no caller count moved, no short-run anchor moved and no sheet night moved. The two repaired cells were both non-exact rows before the repair and both are non-exact rows after it, so the exact-week distribution printed below §8 — zero, three, three, zero, three, three, three, zero, three, zero, and eighteen of the 160 rows reading to the day — is unaffected and was re-derived after the repair rather than assumed.** The restated certification at §8 and the amended one at §10 item 6 record that both claims were false before this pass.

**AND THE MOVEMENT I CONTROL WAS RUN THROUGH THE SAME TEST, BECAUSE A REPAIR THAT CHECKS ONLY THE MOVEMENT IT WAS POINTED AT HAS NOT CHECKED ANYTHING.** `workspace/volume-20/batch-0001/chapter-1001.md` through `chapter-1010.md` return **160 of 160 arithmetically self-consistent**, and Movement II returns **160 of 160 after this repair against 158 of 160 before it.** The control is what makes the two-cell figure believable: the same test, the same parser and the same ten-file scope returns a clean sweep on the movement that §2 uses as its control.

**FINDING TWO, AND IT IS A CLAIM ABOUT A SWEEP THAT WAS WRONG IN THE PLAN OF RECORD AND WRONG AGAIN, STRONGER, IN THE PROMPT DISPATCHED TO MOVEMENT III.** `outline/volume-20.md` stated that the string `screen` stands at twenty across the manuscript on twenty different pages of Volumes 03, 07 and 12. **It stands at twenty and on fourteen files, in Volumes 02, 03, 04, 05, 07 and 12** — the count of occurrences was right and the count of files and the list of volumes were both wrong. The twenty are three folding screens standing at the back of a room, sixteen devices a person reads off and one screen listed among a room's furnishings, and **not one of the twenty is a thing done to a person, so the guardrail the sentence carries stands and only the arithmetic in front of it was wrong.** The word `screening` is at zero on all one thousand and twenty chapter files and that claim was checked and is right. The claim in `outline/volume-20.md` is corrected in place and **the plot is not touched: the man of about thirty-seven who has run screenings before is exactly what the plan says he is and Movement III is written against him unchanged.**

**AND THE PROMPT WAS THE WORSE OF THE TWO, BECAUSE IT TOLD THE NEXT PASS THAT ITS OWN SWEEP WOULD COME BACK EMPTY.** `workspace/volume-20/batch-0003/PROMPT.md` said that the whole-word sweep returns zero across a thousand and twenty pages today. **It returns twenty, and the same prompt warns at its own §7 that a measure returning a zero it cannot justify is the failure this repository keeps making.** A pass told to expect zero either certifies the zero on trust, or runs the sweep, gets twenty and either breaks the guardrail or spends the movement explaining a discrepancy it was told could not exist. **The prompt now prints the twenty, names the fourteen files and the six volumes, tells that pass to expect them and to read all twenty rather than certify a zero.** `state/current.md` and the four other state files carry no copy of either wrong figure, and `state/open-threads.md` carries the Volume 19 Movement VI anchor-row count and not this movement's.

**WHAT THIS PASS REFUSED, AND THE REASON IS GIVEN BECAUSE A REVIEW ARTIFACT THAT RECORDS ONLY WHAT IT DID IS HALF AN ARTIFACT.** The review proposed nothing about the sixty-file duplication control at §2 item 2, which returns 309 pair-hits on 31 shared whole sentences against a published 315 on 32 and 429 distinct keys against a published 575; **that cell is already labelled in §2 as not reproducing and the cause is already named there, and a repair that re-ran it would have had to choose between publishing a figure that is not Movement I's and leaving a labelled non-reproducing cell standing, and this pass left the label.** It proposed nothing about the ten dockets' prose, and this pass read them and found the apparatus frames as they are published. It proposed nothing about §5's `about` rate and this pass did not touch it: the deviation at §5.1 is located, unrepaired and reserved to the Volume 20 close by §13, and a repair that settled it here would take a decision that is not this movement's to make.

## 11. THE SWEEPS, AT THE SAME BOUNDARY, WITH WHAT EVERY HIT ACTUALLY IS

| Sweep | Hits | What they are |
| --- | --- | --- |
| month stems, twelve, word-bounded, case-insensitive | 228 | nine containing words; zero month-names |
| month-names, twelve, whole word, word-bounded | 10 | every one is the modal verb `may` |
| `fair`, `unfair`, `justice`, `rightful`, `principle`, `coalition` | 0 | — |
| `right`, every use | 0 | repaired from twenty-eight; §10 item 4 |
| `Crown`, any form | 0 | Movements I, II and III place no use of the word at all |
| `Iona`, `Sorn`, `Evan`, `Senn`, `Rafi`, `Pell`, `Dessa`, `Kwan`, `Oren`, `Vey`, `Iven`, `Lena` | 0 | word-bounded; substring sweeps hit only inside the verb *given* |
| `screen`, any form | 0 | — |
| the bare word `purpose`, and `not a purpose`, and `a room is not a purpose` | 0 | — |
| day numbers, month-dates, numeric dates, years, mileage, colon clock times | 0 | the numerals on these pages are the docket's own anchor figures and the load-book numbers |
| telephone, messenger, broadcast, feed, letter, any register and any negation | 0 | repaired from one; §10 item 5 |
| the place behind the woman's chair | 1 file | Chapter 1015 alone, with no figure |
| the woman's page, or any day-count in its range | 0 | — |
| the shutter at about two | 1 file | Chapter 1014 alone |
| "nobody thanked anybody" / "nobody forgave anybody" | 10 / 10 | all ten, in each file's own words |
| the three questions written out on the card | 0 | the card is named on all ten closing pages as a card about the size of a hand with three questions on it and no heading on it, and the three questions are printed nowhere |
| a sitting number, or any figure for the book or the tin | 0 | Chapter 1016 is a sitting and prints none |

**AND THE STRING `not a purpose` IS AT ZERO ACROSS ALL TEN FILES AND IS AT ZERO IN THIS FILE, AND IT IS AT ZERO ACROSS ALL ONE THOUSAND AND TWENTY CHAPTER FILES.** The coined phrase of this volume is not spoken by anybody and is not stated as the volume's subject on any page. **The volume's subject is on the page and it is a woman refusing a piece of paper and a man saying he cannot sign nine words he has not read.**

## 12. THE FOUR QUESTIONS, ANSWERED BY READING

**WHO WANTS SOMETHING?** The woman of about forty-three, on six of the ten days, and she is the only person on these pages who wants anything stopped. Marek wants the four words not to have a second hearing, on four of the ten days, and on the seventh of them he gets the thing he asked for and it is that nothing happens. **Nobody else in this movement wants anything about that room.**

**WHAT STOPS HIM?** **A person, on every one of the ten days, and never an absence.** A woman who cannot date a conversation. A printer who will not invent a date and will not print a thing with an empty bottom line. A woman who has kept a room for six years and will not have it on paper. A man with a clipboard who will not take about nine hundred leaflets down. A man of about thirty-three who has not answered a question put to him on the Tuesday. A man who is one of three people holding a thing. A woman of about thirty-four who has been in a queue twice and not gone in.

**DOES ANYBODY ELSE ANSWER?** Yes, on eight of the ten days. Nobody answers the woman of about thirty-four, and that is a page and not an oversight: she is told there is no point in a queue, she is told he has not got an answer, and she goes in on the Friday anyway and is told the truth by the person who started it.

**IS THE PAGE IN A ROOM, AT A TIME, WITH WEATHER, DISTANCE, COST OR PAIN IN IT?** Yes. One shop, one counter, one yard, one kitchen, one hall, one stair, a first floor off a line in Saltmarket, a floor of about eleven desks in a first district, a room and a filing system in a second district, a passage off a clinic in a fourth district, two clean rectangles on a wall in that passage, buses of about twenty minutes and about half an hour each way, forty priced jobs and three hundred and ninety-six pounds, the best day the shop has ever had at fifty-eight pounds, and a man of about thirty-eight whose mother is seventy-one.

## 13. WHAT A LATER PASS MUST NOT INHERIT FROM THIS FILE

**Do not quote any figure here as a house figure.** Every number in §§4 to 8 is a measure of ten files. **Do not take `about` from §5 as the movement's rate and do not treat nineteen as settled** — the movement sits at twenty-five and twenty-seven hundredths pooled, the deviation is located in §5.1, it is not repaired, and the decision belongs to the Volume 20 close. **Do not re-derive the duplication control at zero and do not use the breaks-dropped row** — that row does not reproduce Movement I's published figure and §2 says so. **Do not re-derive guardrail three from the proxy.** The whole-sentence key is the one the plan writes and it is the one that must be used. **Do not treat the five chapterless days inside this span as a rehearsal for anything.** **And do not carry Chapter 1012's exact-week row forward as a licence: the four files in this movement that carry an exact-week row on the fourteenth origin print no figure for that origin anywhere, and Chapter 1023 is a fifth such day and is the one the plan names.**

**AND THE ONE THING THIS FILE COULD NOT SETTLE AND DID NOT SETTLE.** The four words. **They are thirty-four days old at Chapter 1020, they are in about four mouths, they have been reported in at least four different shapes, they have been the subject of a piece of paper that was not printed, and a woman who said she did not know how she knew has said out loud that she is not going to say it to people any more, and a woman who was told them has said no to a correction because she does not know what the other version is.** Nothing on these ten pages stops them and one page says so out loud. **Whether a second hearing of a rumour can be worse than a first one is not a question this movement answers, because answering it in a sentence is a sentence about a room.**

---

*Ten chapters, 1011 to 1020, at `workspace/volume-20/batch-0002/`. Day map 2232 to 2246, weeks 335 to 337, load-book entries 1014 to 1023, governed counters 256 to 265. The seventy-third sitting fell on Chapter 1016 and the book lay open. Movement II is written, measured and handed on. Movement III is dispatched at `workspace/volume-20/batch-0003/PROMPT.md` and no prompt exists for any chapter after Chapter 1030.*