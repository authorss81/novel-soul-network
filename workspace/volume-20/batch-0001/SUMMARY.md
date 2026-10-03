# Volume 20, Movement I — Chapters 1001 to 1010 — SUMMARY

**This file is the measure of record for this movement and the only file a later pass needs to measure these ten chapters against. It was written by the pass that wrote them and every figure below was re-derived from the saved files at the boundary printed at §2, after the repairs at §10. The plan of record is `outline/volume-20.md`. The day map's only home is `workspace/volume-20/ARITHMETIC-AND-CALENDAR.md` §1 and the ten rows at §3 were re-derived against that file's detectors and not read out of it.**

---

## 1. WHAT THIS MOVEMENT IS, IN ONE PARAGRAPH, AND WHAT IT IS NOT

**A woman at a desk in a first district has said four words to about four people, and the four words were true when she said them, and a man who paid for a sheet of paper carrying a door and no list finds out about them on his own counter on the first day of the movement.** He goes up to a first floor off a line in Saltmarket and asks the woman who keeps that room which desk it is and she will not narrow four women to one. On the third day a woman of about thirty-four comes through that door with a folder under her arm and asks for a form and about sixteen people are in that room and not one of them can tell her what there is instead. He asks, in front of about nine people, whether the four words could be printed wrong on purpose, and is told what his own handwriting would mean. He goes and stands at a wall in a passage in a fourth district and about nine people stop at it in an hour and none of them goes. He writes four lines on the back of a docket and cannot finish the fifth. He goes up on a Sunday at half past two, when the room holds about four people who have all been in it on another Sunday and none of whom has ever been in it on a Thursday, and then he goes and stands in an empty passage in the same district at half past four and there is nobody there. **He tells the woman who keeps that room what he is going to do with the paper before he does it, and she says she would have said no, and he goes on with it anyway. He pays a man with a ladder to take the sheet off that wall and does not say the figure out loud. On the ninth day the sheet comes off in a carrier bag in about four minutes in front of about nine people, and he asks her the question he asked a fortnight before, and this time she answers it in about nine words, and it is not a purpose.** On the last day four people who had come on the strength of the four words are given nothing at all and a bag with two hundred and fifty sheets in it is under a bench.

**AND WHAT IT IS NOT.** It is not a chapter about a villain, because there is no villain in it and there is none in this volume. It is not a chapter in which anything is decided about that room, because nothing is decided about it. It contains no form, no list, no column, no heading and no name on anything, and no page of it describes that room.

## 2. THE BOUNDARY, PRINTED ONCE AND USED THROUGHOUT, AND THE INSTRUMENT'S OWN DEFECT ON THE DAY IT WAS RUN

**The tokeniser is `[A-Za-z0-9]+(?:-[A-Za-z0-9]+)*`. The H1 line is removed, and the characters `*`, `` ` `` and `|` are removed. A hyphenated compound is one token. The tokeniser does not admit a colon, so a twenty-four-hour clock time counts as two tokens, and no page of this movement prints one — the sweep at §11 returns zero colon-clock forms and zero numeric dates. Body scope runs to the standalone load-book marker and apparatus scope runs from that marker to end of file; the two are disjoint and their sum is the whole file. The marker line itself is one token and it belongs to apparatus, because apparatus is said to begin *at* that marker and not after it.**

**SENTENCE SEGMENTATION IS DONE BEFORE TOKENISATION AND NOT AFTER, AND THIS PASS GOT THAT WRONG TWICE BEFORE IT GOT IT RIGHT.** The first instrument split on sentence terminators by testing tokens for `.`, `!` and `?`, and the tokeniser admits no punctuation at all, so the splitter could never fire, one file produced exactly one sentence, and every file's key was its own last twelve tokens. **That instrument reported ten distinct keys and zero pair-hits on these ten files, and a controlled instrument reports 407 distinct keys and zero pair-hits on the same files, and the first instrument's guardrail-three figure of zero was also a measurement of nothing.** The second instrument segmented correctly but was pointed at the wrong directory on its first run and returned all zeroes for a third time, which is the same failure in a different costume. **The three failures have one cause between them, which is that a measure which returns zeroes is a receipt and not a result, and the rule this volume inherited is the one Volume 18 offered and Volume 19 published twice: control an instrument against a measure of record that already exists, then read the thing the instrument found, because the number is the receipt and not the result.**

**THE CONTROL, RUN BEFORE THE INSTRUMENT WAS POINTED AT A PAGE.** `workspace/volume-19/batch-0001/`, Chapters 941 to 950, same tokeniser, same split, same forty-five pairs.

| Scope | paragraph rule | distinct keys | pair-hits | against the published figure |
| --- | --- | --- | --- | --- |
| prose | breaks dropped | 413 | 0 | 0 pair-hits, reproduces |
| apparatus | breaks dropped | 234 | 0 | 0 pair-hits, reproduces |
| whole file | breaks dropped | 647 | 0 | 0 pair-hits, reproduces |

**AND THE SECOND CONTROL, WHICH IS THE ONE THAT PROVES THE INSTRUMENT IS THE RIGHT INSTRUMENT.** All sixty files of Volume 19, same code, same boundary.

| Scope | paragraph rule | distinct keys | pair-hits | against `workspace/volume-19/close/CLOSE.md` |
| --- | --- | --- | --- | --- |
| prose | breaks dropped | 2432 | 4 | prose four, reproduces |
| prose | breaks kept | 2650 | 8 | eight, reproduces |
| apparatus | breaks dropped | 1039 | 795 | apparatus 795, reproduces |
| apparatus | breaks kept | 1039 | 795 | reproduces |
| whole | breaks dropped | 3470 | 799 | reproduces |
| whole | breaks kept | 3688 | 803 | reproduces |
| guardrail three, whole-sentence key | — | 3550 | 315 on 32 shared sentences | 315 on 32, reproduces |

**Five of those seven cells and the whole guardrail-three line reproduce a printed figure of record exactly. The instrument is therefore controlled against a measure of record that already exists, and it is that controlled instrument — not the first one — which produced §4 and §5.**

## 3. THE DAY MAP, TEN ROWS, RE-DERIVED AND NOT READ

| Movement | Chapter | Day | Week | Weekday | Load-book entry | Governed counter |
| --- | --- | --- | --- | --- | --- | --- |
| I | 1001 | 2217 | 333 | Monday | 1004 | 246 |
| I | 1002 | 2218 | 333 | Tuesday | 1005 | 247 |
| I | 1003 | 2219 | 333 | Wednesday | 1006 | 248 |
| I | 1004 | 2220 | 333 | Thursday | 1007 | 249 |
| I | 1005 | 2221 | 333 | Friday | 1008 | 250 |
| I | 1006 | 2223 | 333 | Sunday | 1009 | 251 |
| I | 1007 | 2224 | 334 | Monday | 1010 | 252 |
| I | 1008 | 2225 | 334 | Tuesday | 1011 | 253 |
| I | 1009 | 2227 | 334 | Thursday | 1012 | 254 |
| I | 1010 | 2228 | 334 | Friday | 1013 | 255 |

**Ten rows, ten re-derivations, ten reproductions.** `week = (day − 502) // 7 + 88` and `wd = (day − 502) mod 7`, Monday-first. `(entry − chapter) = {3}` and `(counter − chapter) = {−755}` on all ten. The instrument also asserts each file's own H1 chapter number, its standalone marker, its load-book header weekday and week, and its closing `*END OF MOVEMENT I, CHAPTER n. WEEKDAY OF WEEK w. LOAD-BOOK ENTRY e.*` line, and all five agree on all ten rows. **Days 2222 and 2226 carry no chapter and the instrument does not treat either as a rehearsal for anything.**

**The one Sunday of this movement is Chapter 1006 at day 2223 and it is the only one of these ten days on which the shutter comes down at about two.** The other nine take the about-ten form and all ten say so in their own words. No sitting fell in this movement and no number of this matter was said out loud anywhere in that city on any of its ten days.

## 4. THE WORD TABLE, ALL TEN ROWS, WITH A SUM TEST

| Chapter | Body | Apparatus | Whole |
| --- | --- | --- | --- |
| 1001 | 1706 | 971 | 2677 |
| 1002 | 1347 | 942 | 2289 |
| 1003 | 1479 | 960 | 2439 |
| 1004 | 1309 | 928 | 2237 |
| 1005 | 1285 | 944 | 2229 |
| 1006 | 1132 | 1000 | 2132 |
| 1007 | 1361 | 917 | 2278 |
| 1008 | 1301 | 917 | 2218 |
| 1009 | 1749 | 975 | 2724 |
| 1010 | 1331 | 964 | 2295 |

**The totals are 14,000 body, 9,518 apparatus and 23,518 whole, and 14,000 + 9,518 = 23,518 with nothing in either column twice.** Apparatus share 404.711 per thousand of the whole file. **These are measures of ten files. The measure of record for Volume 20 is not written yet and is owed to the Volume 20 close at `workspace/volume-20/close/CLOSE.md`, and a pass writing Chapter 1011 must not carry any figure in this table into a page.**

**THE THREE BIGGEST PAGES AND WHY.** Chapter 1009 is the largest at 2,724 whole-file tokens because it carries the movement's climax and the answer and the cost; Chapter 1001 is next at 2,677 because it carries the whole engine arriving in one afternoon; Chapter 1006 is the smallest at 2,132 because a Sunday in this city is short on every axis, including its four jobs, which came to twenty pounds and the lowest of the ten days. **AND THE SUNDAY IS THE OPPOSITE OF VOLUME 19'S, WHICH IS A FINDING AND NOT A COINCIDENCE.** In Volume 19 the Sundays are the *largest* pages of the sixty — Chapter 946 stands at 14,252 whole-file tokens and is the biggest file in that volume, and the Sunday range across all seven of them runs from 9,941 to 14,252 against a Wednesday range of 10,664 to 14,821. **In this movement the Sunday is the smallest page and the four lowest charges of the ten days, and the reason is on Chapter 1006: about four people are in that room on a Sunday and all of them have been there on another Sunday and none of them has ever been there on a Thursday, so there is nothing on a Sunday for a rumour to attach to.** No page of this movement remarks on the comparison.

## 5. `about`, AT THREE SCOPES AND UNDER ALL THREE CASE CONVENTIONS, WITH THE DENOMINATOR BESIDE EVERY CELL

| Scope | Convention | Hits | Denominator | File-scope | Pooled |
| --- | --- | --- | --- | --- | --- |
| body | case-sensitive | 396 | 14000 | 28.15 | 28.29 |
| body | case-insensitive | 398 | 14000 | 28.33 | 28.43 |
| body | capital-form-only | 2 | 14000 | 0.18 | 0.14 |
| apparatus | case-sensitive | 55 | 9518 | 5.72 | 5.78 |
| apparatus | case-insensitive | 55 | 9518 | 5.72 | 5.78 |
| apparatus | capital-form-only | 0 | 9518 | 0.00 | 0.00 |
| whole file | case-sensitive | 451 | 23518 | 19.04 | 19.18 |
| whole file | case-insensitive | 453 | 23518 | 19.13 | 19.26 |
| whole file | capital-form-only | 2 | 23518 | 0.09 | 0.09 |

**PFILE is the mean of the ten per-file rates and PPOOL is the concatenated files counted once. The two are different quantities and both are printed, because a gate file that printed both under one heading is the defect this repository has already paid for once.**

**Per file, whole-file scope, all three conventions:**

| Chapter | Whole-file tokens | case-insensitive | rate | case-sensitive | rate | capital-only |
| --- | --- | --- | --- | --- | --- | --- |
| 1001 | 2677 | 52 | 19.42 | 52 | 19.42 | 0 |
| 1002 | 2289 | 19 | 8.30 | 19 | 8.30 | 0 |
| 1003 | 2439 | 61 | 25.01 | 61 | 25.01 | 0 |
| 1004 | 2237 | 43 | 19.22 | 43 | 19.22 | 0 |
| 1005 | 2229 | 33 | 14.80 | 33 | 14.80 | 0 |
| 1006 | 2132 | 53 | 24.86 | 51 | 23.92 | 2 |
| 1007 | 2278 | 43 | 18.88 | 43 | 18.88 | 0 |
| 1008 | 2218 | 39 | 17.58 | 39 | 17.58 | 0 |
| 1009 | 2724 | 68 | 24.96 | 68 | 24.96 | 0 |
| 1010 | 2295 | 42 | 18.30 | 42 | 18.30 | 0 |

**THE MOVEMENT SITS AT NINETEEN AND SIX HUNDREDTHS OF A POINT POOLED AND NINETEEN AND THIRTEEN HUNDREDTHS AT FILE SCOPE, CASE-INSENSITIVELY, AGAINST THE STANDING TARGET OF NINETEEN, AND THAT IS A RESULT AND NOT AN ACCIDENT.** It is above Volume 19's Movement I at sixteen and sixty pooled and sixteen and fifty-seven at file scope, and it is below Volume 19's sixty files at fifteen and thirty-nine pooled. **The concentration is in the same two places Volume 19 named and in the same proportions: the house's own job formula carries this manuscript's four-year motif and was not touched, and the largest single block is the reporting idiom `about four people in that room have said since`, which is the manuscript's uncertainty register and is not a hedge but a claim about how many witnesses there are.** Chapter 1002 is the outlier at eight and thirty and it is the only one of the ten with no extended scene in the room, and Chapter 1003 and Chapter 1009 are the two highest at about twenty-five because they are the two days on which about sixteen and about eleven people are reported on. **The ten per-file rates run 8.30, 14.80, 17.58, 18.30, 18.88, 19.22, 19.42, 24.86, 24.96 and 25.01, and the uniformity of a docket is not the uniformity of a page, and a later pass must not make these ten uniform.**

**THE TWO CAPITAL-FORM HITS ARE BOTH ON CHAPTER 1006 AND BOTH ARE THE OPENING WORDS OF A SENTENCE** — `About four of those fittings in that hall are outside the flat` and `About four of those faces in that kitchen have been painted` — and both are the same construction the house has used in the job formula since Volume 15. **They are not hedges about a number. They are the manuscript's way of saying how many identical faults were found in one place, and the third case convention is published because the house publishes it and not because it is a fault.**

## 6. THE DUPLICATION MEASURE, BOTH PARAGRAPH RULES AND BOTH COUNTING CONVENTIONS IN THE SAME PLACE AS EVERY CELL

**A run of twelve words or more, taken at the last twelve tokens of every sentence, lowercased, over all forty-five pairs within the ten files.**

| Scope | Paragraph rule | Counting convention | Distinct keys | Pair-hits |
| --- | --- | --- | --- | --- |
| prose | breaks dropped | strict | 407 | 0 |
| prose | breaks dropped | quote-skipping | 407 | 0 |
| prose | breaks kept | strict | 438 | 0 |
| prose | breaks kept | quote-skipping | 438 | 0 |
| apparatus | breaks dropped | strict | 168 | 0 |
| apparatus | breaks dropped | quote-skipping | 168 | 0 |
| apparatus | breaks kept | strict | 168 | 0 |
| apparatus | breaks kept | quote-skipping | 168 | 0 |
| whole file | breaks dropped | strict | 575 | 0 |
| whole file | breaks dropped | quote-skipping | 575 | 0 |
| whole file | breaks kept | strict | 606 | 0 |
| whole file | breaks kept | quote-skipping | 606 | 0 |

**ALL TWELVE CELLS ARE ZERO ON PAIR-HITS, and the two counting conventions are equal on every row of both tables, and that equality is disclosed rather than presented as a finding: this manuscript writes dialogue inside a bold marker whose quotes are stripped by the tokeniser, so a key that is inside a spoken line and a key that is inside a narrated line are the same key to this instrument, and the convention has nothing to skip.** Volume 19's close published a difference of eight and four between the two conventions at sixty files and this movement has no such difference, and the reason is structural and is not a merit.

**THE REPAIRS THIS MEASURE CAUSED ARE AT §10 ITEM 2 AND THEY WERE TWENTY-NINE PROSE PAIR-HITS ON ONE KEY AND THIRTY-EIGHT APPARATUS PAIR-HITS ON TEN, AND ALL THIRTY-NINE ARE REPAIRED.** The prose exposure was a single run shared by eight of the ten files: the sentence that introduces the day's four jobs. **It is the one sentence in this manuscript's house frame that a writer is most tempted to copy verbatim, because it is the one that appears on all sixty pages of the previous volume, and it is exactly the sentence whose repetition would have been published as canon by a measure that measured it and named its cause wrongly.**

## 7. GUARDRAIL THREE, MEASURED AS THE PLAN WRITES IT AND NOT AS THE PROXY

**Guardrail three as `outline/volume-20.md` writes it is the whole normalised sentence as the key with a twelve-token floor, and not the last-twelve-tokens proxy, because the proxy is blind to a shared run at the start of a longer sentence and it has already let one breach through in this manuscript. Both are measured here.**

| Measure | Key | Floor | Distinct keys | Pair-hits | Shared keys |
| --- | --- | --- | --- | --- | --- |
| guardrail three, as the plan writes it | whole normalised sentence | 12 | 575 | **0** | **0** |
| the last-twelve-tokens proxy, for comparison | last twelve tokens | 12 | 407 | 0 | 0 |

**Zero on both, and the two measures did not agree on the way there.** Before the repairs at §10 the last-twelve proxy returned **twenty-nine prose pair-hits and thirty-eight apparatus pair-hits, sixty-seven in all**, and the whole-sentence key returned **fifteen pair-hits on six shared whole sentences**. The two point at the same nine closing frames, and the whole-sentence key is the binding one because it also catches a shared run at the start of a longer sentence, which the proxy cannot see. **All sixty-seven and all fifteen are the same defects found at two resolutions, and all are repaired.** The flat whole-file test, in which one key is compared against all forty-nine other pairs at once, returns zero shared keys on these ten files. Volume 19's close published 315 pair-hits on 32 shared whole sentences at sixty files, so this movement's zero is not a claim about the manuscript.

## 8. THE STANDING ANCHORS TABLE, DECLARED A SCOPE OF ITS OWN, ONE HUNDRED AND SIXTY ASSERTIONS

**This table is invisible to both measures above and it is the longest block on every page in this volume and in every volume from Volume 15 onward. It is declared here as a named scope of its own so that it stops being invisible.** Sixteen origins, unchanged from Volume 19 and continuous with Chapter 1000's own docket at day 2212. **The instrument composes a cardinal renderer and a weeks renderer, including the zero-remainder form `to the day`, and asserts the printed value of all sixteen rows on all ten files: 160 of 160 reproduced.**

**The control is Chapter 1000's own docket at day 2212, re-derived from the sixteen origins, and all sixteen reproduce the printed page exactly** — the first row reads one thousand eight hundred and fifty days, two hundred and sixty-four weeks and two days, which is `2212 − 362`, and the sixteenth reads one thousand two hundred and thirty days, one hundred and seventy-five weeks and five days, which is `2212 − 982`. **The control is run at the same boundary as the measure because a control run at a different boundary is not a control.**

**How the sixteen rows distribute across these ten pages is arithmetic on the origins and not a writer's decision, and the distribution is not uniform, which is the point.** Twenty-nine of the 160 rows come out as exact whole weeks and the other 131 do not, and by file the exact-week count runs **three, zero, three, seven, three, zero, three, zero, seven and three** for Chapters 1001 to 1010. Chapters 1002, 1006 and 1008 carry no exact-week row at all, which is why the strings `weeks to the day` appear on four of those files and on none of the other three. **The quotients on Chapter 1001's three exact-week rows are two hundred and sixty-five, two hundred and thirty-five and two hundred and three; on Chapter 1003's they are two hundred and twenty-five, two hundred and twenty-one and two hundred and nine; on Chapter 1004's seven they run two hundred and sixty-six, two hundred and fifty-four, two hundred and forty-seven, two hundred and forty-two, two hundred and thirty-nine, two hundred and twenty-two and two hundred and thirteen; on Chapter 1009's seven they run two hundred and sixty-seven, two hundred and fifty-five, two hundred and forty-eight, two hundred and forty-three, two hundred and forty, two hundred and twenty-three and two hundred and fourteen. The uniformity of a docket is not the uniformity of a page, and neither is the uniformity of the distribution of whole weeks across ten days.**

**THE THREE SHORT-RUN ANCHORS THAT CARRY THIS VOLUME, AND ALL THREE ARE NON-UNIFORM ACROSS THE TEN DAYS.** The sheet on the passage wall is `2217 − 2189` and stands at twenty-eight days old on the first day and thirty-nine on the last. The second hundred and fifty sheets, printed by a building in a second district, is `2217 − 2203` and stands at fourteen days old on the first day and twenty-five on the last; **it had never been on that wall at all, which is stated out loud on Chapter 1008, and the two figures are never added.** The thing said at a counter in a first district is `2217 − 2212` and stands at five days old on the first day and sixteen on the last; **the origin is the day the Volume 19 close printed it as a fact and not the day it was said, and the day it was said is printed on no page of this movement.** The copy of that sheet with an empty fifth column runs from its sixty-seventh night at Chapter 1001 to its seventy-sixth at Chapter 1010 and it is on that table on ten nights out of ten, **and it is never moved into a drawer and nobody in that shop holds it and no page asks Marek to move it.**

**AND THE PLACE BEHIND THE WOMAN'S CHAIR.** It is named on **Chapter 1003 alone** of these ten files and on no other, and it carries its printed figure on Chapter 1003 alone: **seven hundred and thirty-five days, which is one hundred and five weeks to the day.** It is printed in the narrator's sentence and not in anybody's mouth, and Marek does the sum standing up with his hands behind his back and does not say it out loud and nobody asks him for it. **The sweep at §11 returns the phrase on one file of these ten and on no other. The interval comes to a round whole number of weeks on Chapter 1023, which is a Wednesday inside Movement III's span and which therefore carries a chapter, and no page of this movement remarks on that and no figure for it is printed here.**

## 9. WHAT THE MOVEMENT SPENT, AND WHAT IT DID NOT SPEND

**SPENT, ON THE PAGE, IN THIS ORDER.** A man learns of the four words at his own counter on the first day. A woman he loves offers him a week of her office twice and is not asked, and says four words out loud the day before to a stranger who is not in her care. A woman of about thirty-four asks a room of about sixteen people for a form and goes out with the folder she came in with. A wall is read by about nine people in an hour by none of whom goes. A man writes four lines on the back of a docket and cannot finish the fifth. A Sunday holds about four people who have never been there on a Thursday and an empty passage where about nine people stood the day before. A man tells a woman what he is going to do before he pays and is told she would have said no. A man with a ladder is paid in fives and told to say nothing if he is asked. A sheet comes off a wall into a carrier bag in about four minutes. **A woman who has kept that room open for six years answers, in about nine words and in front of about eleven people, and the answer is not a purpose.** Four people who came on the four words are given nothing.

**NOT SPENT, ON ANY PAGE.** **The woman's page.** It is printed on no page of this movement, and no value and no range for it appears in this file or in any of the ten chapter files, and the ring binder did not come off its shelf on any of the ten days and nobody apologises to her. **The four arrival cells**, which are not in these files and are not approximated. **The fifth of the register of correct acts that changed nothing**, which is printed as the figure four at both ends of all ten days and is added to by nothing. **Any Exchange figure**, and the difference between the book and the tin, which is printed nowhere. **A comparison of two of the nine hand copies**, of which there is none. **The heading of the fifth column**, which is owner item 4, is unruled, and this movement shows the wall wanting something at the top of a sheet of paper on Chapter 1004 and shows nothing being set, **and that is a refusal on a page and not a setting and not a recommendation.** **Any sentence about what the institution is for**, and the nearest thing to one in these ten files is a woman describing what happens in a room and refusing, in the same breath, to say what it is for.

**AND THE SIX OWNER ITEMS ARE ALL UNRULED AND NONE IS SETTLED, RECOMMENDED OR RE-DERIVED HERE.** Plan against disk — the plan says seven hundred and sixty chapters in fifteen volumes and the disk holds one thousand and ten. The support-spend overage at three readings. The placed cast of five names, at zero on these ten pages, **and no page was invented for any of them in order to make a census come out.** The plan's phrase on Chapter 933. The fifth column's heading, two items and not one. **The ombud's office used on him zero times in this movement, and this file makes no statement about how many times it has been used in this manuscript.** And whether Chapter 760, Chapter 1000 or Chapter 1060 is this manuscript's ending. **Writing Chapter 1001 did not decide the last one and this summary does not decide it and a directive is not a decision.**

**`NOVEL_SPEC.md`, `outline/series.md`, `outline/ending.md`, `outline/volume-15.md` through `outline/volume-19.md`, `bible/*.md`, `workspace/volume-19/ARITHMETIC-AND-CALENDAR.md` and `state/phase-ledger.json` were read and not written, and the last of those is controller-owned.** No page of Volume 15, 16, 17, 18 or 19 was read for editing and none was edited. `state/complete.md` was not written and the declaration that the manuscript is finished remains the owner's decision. No flag about `state/phase-ledger.json` is appended anywhere in this file or in any of the ten chapters.

## 10. WHAT THIS PASS CHANGED, AND WHAT IT FOUND

1. **The instrument's sentence splitter could not fire, and two of the three zeroes it produced before it was fixed were zeros about nothing.** Detailed at §2. Fixed, controlled against two measures of record that already exist, and re-run. **The lesson is published here rather than left implicit: a splitter that tests tokens for a character the tokeniser cannot emit will silently produce one sentence per file, and a whole-file key at that level will be the file's own tail.**
2. **Twenty-nine prose pair-hits on one key and thirty-eight apparatus pair-hits on ten keys, all repaired, and all of them in the closing apparatus and the closing frame.** The prose key was `and that kitchen and it took four jobs and not a fifth`, shared by eight of the ten files. The apparatus keys were the ten-objects lead-in, the card's entry in the closing list, the ninth-chair sentence, the dark-room sentence, the book-and-tin sentence, the dated-rule sentence, the outside-the-ten sentence, the binder sentence and two variants of the caller's-line sentence. **Every one of the ten files was repainted in its own words across all nine of those frames, which is why the apparatus column of the word table moved on seven of the ten rows between the first measurement and this one.**
3. **Four predicative and attributive uses of a word guardrail nine forbids, all repaired, and the repair is why `right` is at zero on all ten files** where it stood at four. `they cannot both be right` became `no. Only one of them is hers`; `found the right circuit` became `found the circuit it belonged to`; `moved the switch across to the right floor` became `moved the switch across to the floor it belonged to`; `is it the right one` became `is it that one`. **Volume 19's close published four files carrying predicative adjective uses of that word at sixty-file scope and did not repair them, and this movement does not add a fifth instance to that class.**
4. **Two handler-typed docket cells were wrong on the first write and were corrected before the chapters were finished.** Chapter 1004 and Chapter 1007 carried a mangled seventeenth row and Chapter 1007 carried a mangled eighteenth row. **The cause was hand-typing and not the renderer, and the repair was to splice all sixteen rows on all ten files from the detectors rather than to correct three cells by eye, which is the fourth recorded instance in this repository of a day-map or anchor cell disagreeing with the instrument and repaired in the same pass that wrote it.**
5. **THE MONTH SWEEP WAS RUN ON STEMS AND IT IS NOT TWELVE ZEROES.** One hundred and ninety-four stem hits on nine distinct containing words: `Marek` one hundred and fifty-two, `may` as the modal verb ten, `marked` eleven, `margin` ten, `Saltmarket` five, `junction` four, `mark` one, `decided` one. **Zero month-names, and a sweep run on whole words would have returned zero on all twelve and would also have returned zero on a page in a past tense inside a negation, which is the failure this repository has already paid for once.**
6. **The strip of a path globs was wrong on one run of this pass's own instrument and returned ten zeroes for a third time before the cause was found**, and the cause was a missing directory segment and not the measure. It is recorded because it is the third time in this batch that an instrument returned a clean zero on a set of files it had not opened, and because a pass that had not controlled it would have published all three zeroes as findings.
7. **No page defect was found in a scene.** Every defect this pass made and every defect it repaired sits in a closing apparatus, a closing frame, a load-book header, a docket cell or a word choice. **That is now the fourth batch in a row in which that is the whole of it, and it is worth a later pass asking what a measure that only looks at scenes would have found on these ten pages, which is probably nothing, and which would then have published nothing.**

## 11. THE SWEEPS, AT THE SAME BOUNDARY, WITH WHAT EVERY HIT ACTUALLY IS

| Sweep | Hits | What they are |
| --- | --- | --- |
| month stems, twelve, word-bounded, case-insensitive | 194 | nine containing words; zero month-names |
| `fair`, `unfair`, `justice`, `rightful`, `principle`, `coalition` | 0 | — |
| `right`, every use | 0 | repaired from four; §10 item 3 |
| `Crown`, any form | 0 | Movements I, II and III place no use of the word at all |
| `Iona`, `Sorn`, `Evan`, `Senn`, `Rafi`, `Pell`, `Dessa`, `Kwan`, `Oren`, `Vey`, `Iven`, `Lena` | 0 | eighteen substring hits, every one of them inside the verb *given* |
| `screen`, any form | 0 | — |
| day numbers, month-dates, numeric dates, years, mileage, colon clock times | 0 | — |
| telephone, messenger, broadcast, feed, letter, any register and any negation | 0 | ten hits on `post`, every one of them the inherited standing anchor *The post at the far end of that corridor, its face worn halfway up*, which is a piece of a corridor and not a communication |
| the place behind the woman's chair | 1 file | Chapter 1003 alone, with its figure |
| the shutter at about two | 1 file | Chapter 1006 alone |
| "nobody thanked anybody" / "nobody forgave anybody" | 10 / 10 | all ten, in each file's own words |
| the three questions written out on the card | 0 | the card is named on all ten closing pages as a card about the size of a hand with three questions on it and no heading on it, and the three questions are printed nowhere in this movement |

**AND THE STRING `not a purpose` IS AT ZERO ACROSS ALL TEN FILES AND APPEARS ONCE IN THE ONE PLACE IT IS ALLOWED TO, WHICH IS THE LOAD-BOOK HEADER OF CHAPTER 1009**, where it reports what the answer was not. The coined phrase of this volume is not spoken by anybody and is not stated as the volume's subject on any page. **The volume's subject is on the page and it is a woman refusing twice and then describing what happens in a room and refusing a third time.**

## 12. THE FOUR QUESTIONS, ANSWERED BY READING

**WHO WANTS SOMETHING?** Marek, on all ten days, and on the ninth of them he gets what he asked for and it is not what he wanted. He wants the room to stop being a place people walk into expecting a thing. He is the only person on these ten pages who wants anything about that room.

**WHAT STOPS HIM?** **A person, on every one of the ten days, and never an absence.** A woman who keeps the room and will not narrow four women to one. A woman he loves who offers him a week twice and is not asked. A woman of about thirty-four who will not repeat the four words and gives him her reason instead. Three people in a passage asking for something at the top of a sheet of paper. A man of about thirty-three who says for the fourth time that he is one of three people holding a thing. A man with a ladder who asks what to tell people who ask him. A man of about thirty-four at the back of a room asking whether there will be something else and getting no answer.

**DOES ANYBODY ELSE ANSWER?** Yes, on nine of the ten days, and on Chapter 1009 the answer is the movement's. Nobody answers the woman who came for the form, and that is a page and not an oversight: four people in that room have tried and the page does not say so in those words.

**IS THE PAGE IN A ROOM, AT A TIME, WITH WEATHER, DISTANCE, COST OR PAIN IN IT?** Yes. One shop, one counter, one yard, one kitchen, one of two rooms, a first floor off a line in Saltmarket, a passage off a clinic in a fourth district, a bus of about twenty minutes and another of about half an hour, forty priced jobs and three hundred and sixty-eight pounds, two hundred and fifty sheets in a carrier bag, a wage envelope thinner than the one it came down in, and a Sunday that ends at two.

## 13. WHAT A LATER PASS MUST NOT INHERIT FROM THIS FILE

**Do not quote any figure here as a house figure.** Every number in §§4 to 8 is a measure of ten files. **Do not take `about` from §5 as the movement's rate** — the files are the authority and the repairs at §10 moved seven of the ten rows after the first measurement. **Do not re-derive the duplication control at zero.** Zero at ten files is a fact about these ten files and Volume 19's sixty files return 799 whole-file pair-hits. **Do not re-derive guardrail three from the proxy.** The whole-sentence key is the one the plan writes and it is the one that must be used, and the two agree here by luck of these ten files and would not agree in general. **Do not treat the four days between Chapter 1003 and Chapter 1009 as a rehearsal for anything.** Days 2222 and 2226 carry no chapter and so do 2226's neighbours and so does 2213's.

**AND THE ONE THING THIS FILE COULD NOT SETTLE AND DID NOT SETTLE.** `outline/volume-20.md` gives the woman of about thirty-four a want and an obstruction and nothing else, and this pass gave her a folder, a queue she did not join, a third version of the four words from a man on a bus, and a fourth person that week to ask Marek what to do. **None of that was invented out of nothing: every one of those four things is asked for by the plan's own sentence, which is *a woman who was told at a counter that the room is where a person goes to be told about a form walks in on the third day and asks for a form, and there is no form, and nobody in that room can tell her what there is instead*.** What is still hers and is not settled here is whether she ever gets to the desk again, and a later pass may answer that and this file does not.

---

*Ten chapters, 1001 to 1010, at `workspace/volume-20/batch-0001/`. Day map 2217 to 2228, weeks 333 and 334, load-book entries 1004 to 1013, governed counters 246 to 255. Movement I is written, measured and handed on. Movement II is dispatched at `workspace/volume-20/batch-0002/PROMPT.md` and no prompt exists for any chapter after Chapter 1020.*