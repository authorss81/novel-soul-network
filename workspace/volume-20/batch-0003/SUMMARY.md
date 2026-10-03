# Volume 20, Movement III — Chapters 1021 to 1030 — SUMMARY

**Ten chapters written on their first pass, ten files, and then eight classes of defect repaired on the pages by the instruments in this file, every one of which is named below at §10 with the row that found it. This file is the measure of record for Movement III and it is a measure of ten files and not a house figure.** **THE HEADLINE OF THIS FILE SAID ELEVEN CLASSES ON ITS FIRST PRINTING AND ITS OWN TABLE CARRIES EIGHT NUMBERED ROWS, and the eleven has been corrected to the eight the table can be counted at rather than the table being padded to eleven. §15 records it, and so do four state files and the Movement IV prompt, which had all inherited the figure.**

## 0. THE BOUNDARY, PRINTED BEFORE ANY CELL BELOW IS FILLED

**The tokeniser is `[A-Za-z0-9]+(?:-[A-Za-z0-9]+)*`. The H1 line is removed, and the characters `*`, `` ` `` and `|` are removed BEFORE segmentation and not after, because a bold dialogue marker hides its own terminator from a splitter that looks for whitespace after a full stop.** A hyphenated compound is one token. The tokeniser does not admit a colon, so a twenty-four-hour clock time is two tokens, and no page of this movement prints one. **Body scope runs to the standalone load-book marker `^\*\d+\.$` and apparatus scope runs from that marker to end of file; the two are disjoint, their sum is the whole file, and the marker line itself is one token belonging to apparatus.**

**THE TWO PARAGRAPH RULES ARE RESTATED HERE EXACTLY, BECAUSE §14.0 OF `batch-0002/SUMMARY.md` ASKED FOR IT AND BECAUSE THIS MOVEMENT FOUND A REAL BREACH THROUGH THEM.** *Breaks KEPT* — a paragraph break is itself a sentence boundary; a terminator followed by whitespace is a boundary; blocks are segmented independently and the segments concatenated. *Breaks DROPPED* — every run of one or more newlines is replaced by a single space, so a paragraph boundary carries no sentence significance and only terminator-plus-whitespace splits; a paragraph that ends without a terminator therefore merges into the next paragraph's first sentence.

**THE TWO COUNTING CONVENTIONS ARE RESTATED HERE EXACTLY, AND THIS MOVEMENT FOUND THAT THE PRECEDING FILE'S PUBLISHED EQUALITY BETWEEN THEM IS NOT PRODUCIBLE.** *Strict* counts every qualifying sentence. *Quote-skipping* discards a sentence that lies wholly inside a double-quoted run. Both keys are run, because the plan's key and the last-twelve-token proxy are both printed beside every cell.

**AND THE INSTRUMENT STOPS RATHER THAN RETURNING A ZERO IT CANNOT JUSTIFY.** It raises and does not answer if a file it was pointed at has no standalone load-book marker, and the control at §1 was run before this instrument was pointed at a Movement III page. That behaviour was inherited from Movement II and it is the one change Movement II made to the instrument after the instrument was right.

## 1. THE CONTROL, RUN AT TEN FILES AND AT SIXTY, AND WHICH OF ITS CELLS REPRODUCE

**Two measures of record already existed before this one and both were run first. One is at ten files and one is at sixty.**

| What the published measure prints | Where | What this instrument returned | Verdict |
| --- | --- | --- | --- |
| Movement I word table, all ten rows and three totals | `batch-0001/SUMMARY.md` §4 | 14,000 / 10,318 / 24,318 and ten rows each summing | **reproduces to the digit** |
| Movement I `about`, three scopes, three conventions | §5 | identical hits, denominators and rates | **reproduces to the digit** |
| Movement I duplication, breaks KEPT, strict | §6 | prose 438, apparatus 168, whole 606 | **reproduces to the digit** |
| Movement I duplication, breaks DROPPED, strict | §6 | prose 407, apparatus 168, whole 575 | **reproduces to the digit** |
| Movement I guardrail three, whole-file distinct keys, DROPPED | §7 | 575 | **reproduces** |
| Movement II word table, all ten rows and three totals | `batch-0002/SUMMARY.md` §14.3 | 19,239 / 10,569 / 29,808 and ten rows each summing | **reproduces to the digit** |
| Movement II `about`, all nine cells and the per-file table | §14.4 | identical hits, denominators and both rates | **reproduces to the digit** |
| Movement II duplication, breaks KEPT, strict | §14.5 | prose 548, apparatus 163, whole 711 | **reproduces to the digit** |
| Movement II duplication, breaks DROPPED, strict | §14.5 | prose 516, apparatus 163, whole 679 | **reproduces to the digit** |
| **Movement II duplication, breaks KEPT, quote-skipping** | **§14.5** | **prose 470, apparatus 163, whole 633** | **DOES NOT REPRODUCE — see §2** |
| **Movement II duplication, breaks DROPPED, quote-skipping** | **§14.5** | **prose 478, apparatus 163, whole 641** | **DOES NOT REPRODUCE — see §2** |
| Movement II anchor renderer against Chapter 1020's own printed docket | §14.7 | 16 of 16 rows reproduce | **reproduces to the digit** |
| Volume 19's sixty files, `screen` stem | §14.8 of this file | 20 on 14 files | **reproduces** |

**THE CONTROL WAS RUN AT SIXTY FILES AS WELL, ON THE ONE MEASURE THAT HAS A PUBLISHED SIXTY-FILE FIGURE IN THIS VOLUME, AND IT IS THE `screen` SWEEP: twenty hits on fourteen files across Volumes 02, 03, 04, 05, 07 and 12, every one of them the bare word `screen`, and not one of them a thing done to a person.** The prompt's figure is reproduced to the digit and it is a figure that was expected to be twenty and was still read rather than certified.

## 2. FINDING ONE, AND IT IS A ROW IN THE PRECEDING FILE'S OWN MEASURE THAT NO INSTRUMENT PRODUCES

**`batch-0002/SUMMARY.md` §14.5 publishes the two counting conventions as returning identical distinct-key counts — prose 548 and 548, apparatus 163 and 163, whole file 711 and 711 — and then discloses a mechanism for the equality: *a job speech is written as three sentences inside a single pair of quotes, so the opening quote falls on the first sentence and the closing quote on the third, and no sentence of twelve tokens or more lies wholly inside a quoted run.* THAT MECHANISM IS FALSE FOR ITS OWN TEN FILES AND THE EQUALITY IS NOT PRODUCIBLE.**

**What the ten files actually contain, measured at the same boundary and with both conventions: on Movement I's ten files the strict count is 438 and the quote-skipping count is 360; on Movement II's ten files the strict count is 548 and the quote-skipping count is 470; on this movement's ten files the strict count is 464 and the quote-skipping count is 384. Seventy-eight qualifying sentences are skipped on Movement I's ten files and seventy-eight on Movement II's, and every one of them is one of the four job speeches on each page. Each is twenty of the forty priced jobs.** The reason is structural and it is now measured rather than asserted: a job speech is written as `**"Twelve pounds,"** he said. **"A socket over a sink with no earth is a socket that is wet and un earthed at the same time. Sockets in that street are like it, and one of them has been a kitchen…**` — the price is one quoted run, the middle sentence stands **outside** every pair of quotes, and the third sentence, which is the longest of the three and the only one of the three that clears twelve tokens, sits **inside** the second quoted run and is skipped. **The equality of the two conventions is an artefact of the previous file having printed the strict row twice, and its disclosed reason is replaced here with the measured mechanism.**

**NO FINDING CHANGES. All twelve cells are zero on pair-hits under both conventions, and the conclusion Movement II published stands; what does not stand is one row and the sentence that explains it.** This is recorded rather than repaired in that file, because `batch-0002/` carries a `.deferred` marker and a closed phase's measure of record is not this pass's to rewrite. **`batch-0003/SUMMARY.md` does not inherit that row and a pass controlling an instrument against `batch-0002/SUMMARY.md` §14.5 should expect the quote-skipping row to come back lower than the row beside it and should not read the difference as a fault in its own instrument.**

## 3. THE DAY MAP, TEN ROWS, RE-DERIVED AND NOT READ

**All fifteen days of Movement III's span were derived before a page was written, and the ten chapter days were then re-derived again from the pages themselves with the day read back out of each page's own first anchor row and inverted from its spelled-out cardinal.** `week = (day − 502) // 7 + 88` and `wd = (day − 502) mod 7`, Monday-first.

| Movement | Chapter | Day | Week | Weekday | Load-book entry | Governed counter |
| --- | --- | --- | --- | --- | --- | --- |
| III | 1021 | 2251 | 337 | Sunday | 1024 | 266 |
| III | 1022 | 2253 | 338 | Tuesday | 1025 | 267 |
| III | 1023 | 2254 | 338 | Wednesday | 1026 | 268 |
| III | 1024 | 2256 | 338 | Friday | 1027 | 269 |
| III | 1025 | 2257 | 338 | Saturday | 1028 | 270 |
| III | 1026 | 2259 | 339 | Monday | 1029 | 271 |
| III | 1027 | 2261 | 339 | Wednesday | 1030 | 272 |
| III | 1028 | 2262 | 339 | Thursday | 1031 | 273 |
| III | 1029 | 2263 | 339 | Friday | 1032 | 274 |
| III | 1030 | 2264 | 339 | Saturday | 1033 | 275 |

**THE CONTROL FOR THIS DERIVATION IS MOVEMENT II'S OWN TEN PUBLISHED ROWS AND NOT A PLAN FILE, AND ALL TEN REPRODUCE.** The same two detectors were composed against Movement II's published day, week, weekday, entry and counter for Chapters 1011 to 1020 and returned all five fields on all ten rows. **On top of the derived day this instrument asserts six things printed on each page — the H1 chapter number, the standalone marker, the load-book header's weekday, its week, the spelled-out ordinal of the governed counter, and the whole `END OF MOVEMENT III` line, which carries the chapter, the weekday, the week and the entry — and all six agree on all ten rows.**

`week = 7n − 114` was composed with both detectors for each of weeks three hundred and thirty-seven to three hundred and thirty-nine and lands inside week _n_ on a Monday in all three cases, and those three assertions could not have failed because the composition is the definition of the map.

**Days 2252, 2255, 2258, 2260 and 2265 carry no chapter and the instrument does not treat any of them as a rehearsal for anything.** The one Sunday of this movement is Chapter 1021 at day 2251 and it is the only one of these ten days on which the shutter comes down at about two; the other nine take the about-ten form in their own words. **No sitting falls in this movement and no sitting number is printed on any of these ten pages, no figure for the book or the tin is printed on any of them, no difference between them is printed, and no page remarks on anything about them.** The next sitting falls at Chapter 1031 in Movement IV and this file says nothing about it.

## 4. THE WORD TABLE, ALL TEN ROWS, WITH A SUM TEST

| Chapter | Body | Apparatus | Whole | Body + apparatus = whole |
| --- | --- | --- | --- | --- |
| 1021 | 1788 | 1144 | 2932 | yes |
| 1022 | 1554 | 1109 | 2663 | yes |
| 1023 | 1727 | 1087 | 2814 | yes |
| 1024 | 1504 | 1077 | 2581 | yes |
| 1025 | 1243 | 1107 | 2350 | yes |
| 1026 | 1625 | 1108 | 2733 | yes |
| 1027 | 1542 | 1075 | 2617 | yes |
| 1028 | 1257 | 1098 | 2355 | yes |
| 1029 | 1253 | 1092 | 2345 | yes |
| 1030 | 1824 | 1134 | 2958 | yes |
| **Total** | **15,317** | **11,031** | **26,348** | **15,317 + 11,031 = 26,348** |

**Apparatus share 418.67 per thousand of the whole file. Nothing in either column is counted twice and no row is a copy of another. These figures are a measure of ten files and are not a house figure; the measure of record for Volume 20 is owed to the Volume 20 close, and a pass writing Chapter 1031 must not carry any figure in this table into a page.**

**THE OPENING BOLD PARAGRAPH OF EACH OF THE TEN, IN WORDS, BECAUSE THE MOVEMENT III PROMPT ASKS FOR THEM AND BECAUSE `batch-0002/SUMMARY.md` §14.3 IS WHERE THE PRECEDING MOVEMENT'S TEN ARE PUBLISHED.** They stand at **51, 46, 48, 51, 49, 55, 62, 57, 51 and 54**, all inside the forty-to-seventy-five band, **not one of the ten carries a numeral**, and none of them states an outcome or reports anything a person in another building said. **They are a measure of ten pages and not a target.** **Two OF THE FIGURES IN THIS SENTENCE ARE THE REVIEW-REPAIR PASS'S AND NOT THIS PASS'S, and §15 says which two and why; the first printing of this row read fifty-six for Chapter 1027 and sixty-four for Chapter 1030, and both were the lengths of lead-ins the review-repair pass re-opened.**

**AND THE TEN TITLES, MEASURED AND NOT ASSUMED, AT H1-LINE SCOPE: seven, five, five, seven, six, six, six, six, eight and five words, a median of six, none carrying `And`, none carrying a number-word, none enumerating its contents and none spelling out a date.** Movement I's ten stand at five words and Movement II's at six, so three movements now read five, six and six. **Chapter 1005's title is the one live `And` of the short-title era and this movement did not make it two.** **THE CLAUSE *none carrying a number-word* WAS FALSE ON THE FIRST PRINTING OF THIS ROW AND WAS NOT TRUE OF CHAPTERS 1024 AND 1028, AND IT IS NOW TRUE BECAUSE THAT PASS RENAMED BOTH. §15 carries the two titles as they stood and as they stand, and the word counts are unchanged by the rename, which is why this row's figures did not move.**

**AND THE FINDING THE RENAME UNCOVERED, WHICH IS NOT A DEFECT OF THIS MOVEMENT AND IS A DEFECT OF AN EARLIER AUDIT.** The pass that surveyed all eighty files of the short-title era counted `And` across them and reported three titles and repaired two, **and it did not count number-words across them at all.** Measured at H1 scope over Chapters 941 to 1030, **nine titles carry a number-word and stand unrepaired: Chapter 947 *A Sixth Column Is Offered*, 952 *Four People In Her Head*, 956 *The Second Name*, 961 *Two Copies Of One Pencil Line*, 963 *She Came Back At Nine*, 964 *A Sixth Column On Somebody Else's Form*, 966 *Four Names On The Back Of A Card*, 969 *Two Sheets In One Tray*, and 1011 *The Woman Who Said It First*.** Six of the nine are cardinals and three are ordinals. `outline/volume-20.md` deviation four forbids a number-word in a title without distinguishing the two, and the single precedent for enforcing it, Chapter 1012, was a cardinal. **None of the nine is repaired here, because `batch-0001/` and `batch-0002/` are closed phases and a closed phase is audited and not rewritten, and because a repair that took nine titles across two closed movements is not a review-repair pass's decision to make silently. IT IS RECORDED INSTEAD, at `state/open-threads.md`, and it is owed either to a Volume 20 close that is allowed to touch closed files or to the owner.**

## 5. `about`, AT THREE SCOPES AND UNDER ALL THREE CASE CONVENTIONS, WITH THE DENOMINATOR BESIDE EVERY CELL

| Scope | Convention | Hits | Denominator | Rate per thousand |
| --- | --- | --- | --- | --- |
| body | case-sensitive | 429 | 15317 | 28.01 |
| body | case-insensitive | 430 | 15317 | 28.07 |
| body | capital-form-only | 1 | 15317 | 0.07 |
| apparatus | case-sensitive | 86 | 11031 | 7.80 |
| apparatus | case-insensitive | 86 | 11031 | 7.80 |
| apparatus | capital-form-only | 0 | 11031 | 0.00 |
| whole file | case-sensitive | 515 | 26348 | 19.55 |
| whole file | case-insensitive | 516 | 26348 | 19.58 |
| whole file | capital-form-only | 1 | 26348 | 0.04 |

**THE CASE-SENSITIVE AND CASE-INSENSITIVE COLUMNS WERE TRANSPOSED IN THIS TABLE ON ITS FIRST PRINTING, IN TWO OF ITS THREE SCOPES, AND BOTH COLUMNS AND BOTH RATES ARE CORRECTED HERE.** The first printing gave body case-sensitive 431 against case-insensitive 430, and whole-file case-sensitive 517 against case-insensitive 516. **A case-insensitive count cannot be lower than a case-sensitive count of the same token under the same tokeniser, so the first printing was not a measurement that could stand and the instrument that produced it was not trusted again without a hand-check.** There is exactly one capital-form `About` on these ten pages and it is in Chapter 1024's body, which is why the case-sensitive figure is one lower than the case-insensitive figure in both scopes and why the apparatus row is equal under both. **The per-file table immediately below was correct on its first printing and is not transposed, and that is the check that located the fault: a per-file table and a pooled table built from the same ten files cannot disagree in that direction unless one of them has swapped two labels.** §15 records this.

**Per file, whole-file scope, all three conventions:**

| Chapter | Whole-file tokens | case-insensitive | rate | case-sensitive | rate | capital-only |
| --- | --- | --- | --- | --- | --- | --- |
| 1021 | 2932 | 68 | 23.19 | 68 | 23.19 | 0 |
| 1022 | 2663 | 50 | 18.78 | 50 | 18.78 | 0 |
| 1023 | 2814 | 53 | 18.83 | 53 | 18.83 | 0 |
| 1024 | 2581 | 52 | 20.15 | 51 | 19.76 | 1 |
| 1025 | 2350 | 29 | 12.34 | 29 | 12.34 | 0 |
| 1026 | 2733 | 61 | 22.32 | 61 | 22.32 | 0 |
| 1027 | 2617 | 61 | 23.31 | 61 | 23.31 | 0 |
| 1028 | 2355 | 42 | 17.83 | 42 | 17.83 | 0 |
| 1029 | 2345 | 35 | 14.93 | 35 | 14.93 | 0 |
| 1030 | 2958 | 65 | 21.97 | 65 | 21.97 | 0 |

**PFILE is the mean of the ten per-file rates and PPOOL is the concatenated files counted once. The two are different quantities and both are printed: PPOOL 19.58 and PFILE 19.37 at whole-file scope, case-insensitively.**

### 5.1 THIS MOVEMENT WAS WRITTEN BELOW THE PRECEDING MOVEMENT'S RATE AND THE PROMPT ASKS WHAT WAS DONE, SO IT IS SAID HERE

**The prompt asks this pass to say whether it wrote Movement III at a lower rate or at the same rate. It wrote it at a lower rate, and on the pages as they now stand the figure is five points lower: nineteen and fifty-eight hundredths pooled and nineteen and thirty-seven hundredths at file scope, case-insensitively, against Movement II's published twenty-four and fifty-nine hundredths pooled and twenty-four and seventy-three hundredths at file scope. Movement I's are eighteen and sixty-three hundredths pooled and eighteen and fifty-one hundredths at file scope.** **THE FIRST PRINTING OF THIS SENTENCE READ NINETEEN AND SIXTY-TWO AND NINETEEN AND FORTY, AND BOTH FIGURES WERE CORRECT BEFORE THIS PASS BEGAN: they are this pass's own pool and file-scope rates measured over the pages as first written, and the two paragraphs of §15 moved one file's tokens and one file's hits, which is enough to move a pooled rate by four hundredths and a file-scope rate by three.**

**WHAT WAS DONE WAS NOT A SUBSTITUTION PASS.** No mechanical replacement was run over these files before they were written and none was run over them afterwards, for the reason at `NOVEL_SPEC.md`'s fifth Status block: an instrument that damages prose must not be run first, and a hedge pass that rewrites prose and then reprints the rate is the exact failure this repository has already paid for once. **What was done was a decision about which register the word does in each sentence.** The word is this house's uncertainty register, its designation idiom and its clock-and-duration register, and all three of those jobs are honest uses of it. Movement III took the reading that **a duration is a duration and not a guess, and that the sentence is stronger without the hedge in front of a number the speaker has just watched happen**, so most of the movement's instances are in the idiom and not in front of a figure; and it took the reading that **a quantity of people who have said something since last week is exactly the kind of thing nobody in that city would state flatly**, so the house attribution idiom keeps the word. The three files carrying the lowest rates are the three whose argument is about counting: Chapter 1025 at twelve and thirty-four hundredths, Chapter 1029 at fourteen and ninety-three hundredths and Chapter 1028 at seventeen and eighty-three hundredths.

**THE ONE CAPITAL-FORM HIT IS ON CHAPTER 1024 AND IS NOT A HEDGE ABOUT A NUMBER**, and it is disclosed rather than explained away. The three files at the top of the table are the three files in which a man who has been standing at the bottom of a stair for about a week is reporting how many people he asked, and a person saying *about* eleven out loud in a room full of people who have been asked is not the same gesture as a narrator hedging.

**THE DECISION ABOUT WHETHER NINETEEN IS THE TARGET FOR THIS VOLUME IS STILL OWED TO THE VOLUME 20 CLOSE AT SIXTY FILES, and this movement's rate is one more data point and not a settlement.** A movement is not allowed to declare the target satisfied by being written carefully.

## 6. THE DUPLICATION MEASURE, BOTH PARAGRAPH RULES AND BOTH COUNTING CONVENTIONS IN THE SAME PLACE AS EVERY CELL

**A run of twelve words or more over all forty-five pairs within the ten files. *Strict* counts every qualifying sentence. *Quote-skipping* discards a sentence that lies wholly inside a double-quoted run. Both keys are run, and the last-twelve-token key is printed beside them for comparison.**

| Scope | Paragraph rule | Counting convention | Distinct keys, whole-sentence key | Pair-hits | Distinct keys, last-twelve proxy | Pair-hits, last-twelve proxy |
| --- | --- | --- | --- | --- | --- | --- |
| prose | breaks KEPT | strict | 464 | **0** | 464 | 0 |
| prose | breaks KEPT | quote-skipping | 384 | **0** | 384 | 0 |
| prose | breaks DROPPED | strict | 425 | **0** | 425 | 0 |
| prose | breaks DROPPED | quote-skipping | 385 | **0** | 385 | 0 |
| apparatus | breaks KEPT | strict | 160 | **0** | 160 | 0 |
| apparatus | breaks KEPT | quote-skipping | 160 | **0** | 160 | 0 |
| apparatus | breaks DROPPED | strict | 160 | **0** | 160 | 0 |
| apparatus | breaks DROPPED | quote-skipping | 160 | **0** | 160 | 0 |
| whole file | breaks KEPT | strict | 624 | **0** | 624 | 0 |
| whole file | breaks KEPT | quote-skipping | 544 | **0** | 544 | 0 |
| whole file | breaks DROPPED | strict | 585 | **0** | 585 | 0 |
| whole file | breaks DROPPED | quote-skipping | 545 | **0** | 545 | 0 |

**ALL TWELVE CELLS ARE ZERO ON PAIR-HITS, under both keys, under both paragraph rules, under both counting conventions, and the flat whole-file test — in which one key is compared against all forty-four other pairs at once — returns zero shared keys. Volume 19's close published 315 pair-hits on thirty-two shared whole sentences at sixty files, so this movement's zero is not a claim about the manuscript.**

**THE TWO CONVENTIONS DIFFER HERE BY EIGHTY AND THE DIFFERENCE IS EXPLAINED AT §2: twenty of the forty priced jobs on these ten pages put their longest sentence inside a pair of quotes.** The apparatus figure is the same under both because apparatus carries no double quotes at all.

**THE DISTINCT-KEY COLUMNS ARE EQUAL ACROSS THE TWO KEYS, AND THAT IS NOT A COINCIDENCE AND NOT A FINDING: a distinct-key count is a property of the set of qualifying sentences and not of the key taken from them, so the two keys can differ only in pair-hits, and on these ten files they do not.** This is inherited correctly from `batch-0002/SUMMARY.md` §14.5 and is restated because two passes in this volume have printed it the other way round.

## 7. GUARDRAIL THREE, MEASURED AS THE PLAN WRITES IT AND NOT AS THE PROXY

**Guardrail three as `outline/volume-20.md` writes it is the whole normalised sentence as the key with a twelve-token floor, and not the last-twelve-tokens proxy, because the proxy is blind to a shared run at the start of a longer sentence and it has already let one breach through in this manuscript.**

| Measure | Key | Floor | Scope | Distinct keys | Pair-hits | Shared keys |
| --- | --- | --- | --- | --- | --- | --- |
| guardrail three, as the plan writes it | whole normalised sentence | 12 | prose | 464 | **0** | **0** |
| guardrail three, as the plan writes it | whole normalised sentence | 12 | apparatus | 160 | **0** | **0** |
| guardrail three, as the plan writes it | whole normalised sentence | 12 | whole file | 624 | **0** | **0** |
| the last-twelve-tokens proxy, for comparison | last twelve tokens | 12 | whole file | 624 | 0 | 0 |

**Zero on both keys, at a floor of twelve, in all three scopes, and zero on the flat test. AND THE ROW THAT MATTERS MOST IN THIS MOVEMENT IS THE OPPOSITE ONE: this movement WROTE at one hundred and ninety-three pair-hits and had them taken out by hand, and §10 says what they were.** The instrument was right and the prose was wrong, and the sequence in which that was established is printed at §10 because a measure that publishes only its final zero teaches the next pass that the zero was free.

## 8. THE STANDING ANCHORS TABLE, DECLARED A SCOPE OF ITS OWN, ONE HUNDRED AND SIXTY ASSERTIONS AND ONE HUNDRED AND SIXTY CONSISTENCY TESTS

**This table is invisible to both measures above and it is the longest block on every page in this volume and in every volume from Volume 15 onward. It is declared here as a named scope of its own so that it stops being invisible.** Sixteen origins, unchanged from Volume 19 and continuous with Chapter 1000's own docket at day 2212. The instrument composes a cardinal renderer and a weeks renderer, including the zero-remainder form `to the day`, and asserts the printed value of all sixteen rows on all ten files: **160 of 160 rendered against the origins reproduce.**

**AND THE TEST NO FIGURE IN THIS FILE HAD BEEN SUBJECTED TO IS RUN AGAIN AND IT IS NOT THE SAME TEST: each printed row is read back out of the page and checked for arithmetic self-consistency with itself, that the day figure equals seven times the weeks figure plus the remainder, and that the row agrees with the day on its own page. 160 of 160 are self-consistent and agree with their own page.** Both tests are needed and neither substitutes for the other: a row can render correctly from a wrong day, and a row can be self-consistent and wrong about the day. **This test found the one arithmetic cell defect on these ten pages and it is at §10 item 11.**

**HOW THE SIXTEEN ROWS DISTRIBUTE ACROSS THESE TEN PAGES IS ARITHMETIC ON THE ORIGINS AND NOT A WRITER'S DECISION, AND THE DISTRIBUTION IS NOT UNIFORM, WHICH IS THE POINT.** Twenty-six of the 160 rows come out as exact whole weeks and the other 134 do not, and by file the exact-week count runs **zero, zero, three, three, zero, three, three, seven, three, zero** for Chapters 1021 to 1030. **Chapters 1021, 1022, 1025 and 1030 carry no exact-week row at all.** The uniformity of a docket is not the uniformity of a page, and neither is the uniformity of the distribution of whole weeks across ten days.

### 8.1 THE THREE SHORT-RUN ANCHORS, ALL NON-UNIFORM ACROSS THE TEN DAYS, ALL RE-DERIVED AND ALL READ BACK OFF THE PAGES

The sheet that was on the passage wall is `day − 2189`: **sixty-two days old on the first day of this movement and seventy-five on the last**, in a carrier bag under the long bench, off the wall since the Thursday of week 334, and no page of these ten says a sheet is on that wall. The second hundred and fifty, printed in a second district, is `day − 2203`: **forty-eight days old on the first day and sixty-one on the last**, never on that wall, **its whereabouts are named on Chapter 1030 and on no other page of this movement and it was not looked for on any of the ten days**, and **the two figures are never added.** The thing said at a counter in a first district is `day − 2212`: **thirty-nine days old on the first day and fifty-two on the last**, **and the origin is the day the Volume 19 close printed it as a fact and not the day it was said, and the day it was said is printed on no page of this movement.** All thirty figures were read out of the pages and checked against their own days, and all thirty agree.

### 8.2 THE NIGHTS OF THE SHEET WITH THE EMPTY FIFTH COLUMN, AND THE CONVENTION THIS MOVEMENT USED AND WHY

**None of the three figures in the record was inherited. The run was derived from the day against its own origin and printed on each page, and the convention is stated here because the manuscript counts these nights two ways and a pass must not inherit either of them.**

**The convention used is the one derived from the day: `day − 2150`, which is a count of nights and not a chapter index, and the pages carry one hundred and first, third, fourth, sixth, seventh, ninth, eleventh, twelfth, thirteenth and fourteenth.** All ten were read back out of the pages and agree with their own days. **The convention is used because a chapterless day still has a night in it, so a run stepped by chapter is short by one on five of Movement I's ten rows and disagrees with the derived run at the join; and the derived run is the one that means what the sentence says.** Movement I's chapter-stepped run and Movement II's derived run still disagree with each other at their join and that disagreement is still on those pages and is still not smoothed over.

**AND THE COPY OF THAT SHEET WAS ON THAT TABLE FOR ALL TEN NIGHTS, WAS NEVER MOVED INTO A DRAWER, NOBODY IN THAT SHOP HOLDS IT, AND NO PAGE OF THIS MOVEMENT ASKED MAREK TO MOVE IT.**

### 8.3 THE PLACE BEHIND THE WOMAN'S CHAIR, AND WHY THIS FILE PRINTS NO DAY-COUNT FOR IT EITHER

**It is named on Chapter 1023 alone, in Movement III's ten files, and it carries no printed figure there, and no day-count for it appears on any of these ten pages or anywhere in this file.** Chapter 1023 is the file the plan of record assigns the naming to, and it is also the file on which the interval lands on a round whole number of weeks, and it is therefore the file where a writer will most want to print one. **It was not printed, and no page remarks on the roundness, and this measure prints no interval and no day either, for the reason the calendar file gives: the origin plus the day is the figure and a measure that prints the figure has published it to a later pass's complete.** The page's own sentence is that he stood in front of the space where something had stood for years and worked the sum out with his hands behind him where nine people could see him doing it and did not say one word of it aloud.

## 9. THE SWEEPS, AT THE SAME BOUNDARY, WITH WHAT EVERY HIT ACTUALLY IS

| Sweep | Hits | What they are |
| --- | --- | --- |
| **month stems, twelve, case-insensitive, pattern `\w*STEM\w*`** | **10** | **one containing word, the modal verb `may`, ten times, one on each page, every one of them inside the inherited sentence *whatever is filed behind it may be read by any person who asks to see it*. Zero month-names. `Marek` cannot be produced by a `may` stem — *m-a-r* against *m-a-y* — and that is the finding and not a gap** |
| **month-names, twelve, whole word, word-bounded, case-insensitive** | **10** | **and all ten are the same modal verb `may`, and none of them is a month-name.** This row is published at ten and not at zero on purpose. **A case-insensitive whole-word sweep cannot return zero on a manuscript that contains the word `may`, and a file that prints twelve zeroes for this sweep has not run it. Movement II's measure prints zero for this row on files that carry the same modal verb, and that row should be read as a defect of that sweep and not as a property of those pages** |
| `fair`, `unfair`, `justice`, `rightful`, `principle`, `coalition` | 0 | — |
| `right`, every use | 0 | **holds, and it took nine repairs on the first write and one of them cost the whole argument of a page; they are at §10** |
| the bare word `purpose` | 0 | **and it took two repairs, both of them in a scene, on the first write** |
| `Crown`, any form | 0 | Movements I, II and III place no use of the word at all |
| `Evan`, `Senn` | 0 | word-bounded |
| `Rafi`, `Pell`, `Dessa`, `Kwan`, `Oren`, `Vey`, `Iven`, `Lena` | 0 | word-bounded; the placed cast is at zero on these ten pages and §12 says why |
| `screen`, any form | 0 | **and across all one thousand and thirty chapter files the stem returns twenty on fourteen files in Volumes 02, 03, 04, 05, 07 and 12, all twenty of them the bare word, and `screening` is at zero. The twenty were read rather than certified and not one of them is a thing done to a person** |
| four-digit figures | 20 | **every one is a chapter number or a load-book entry: 1021 to 1033, at two apiece. Zero interval figures are printed in Arabic digits on any of these ten pages** |
| three-digit figures | 10 | **every one is a week: 337, 338 or 339** |
| month-dates, numeric dates, years, mileage, colon clock times | 0 | — |
| telephone, messenger, broadcast, feed, letter, any register and any negation | 0 | **the stem sweep returns eleven hits on `post` and every one is a piece of masonry — ten of them the standing anchor row *the post at the far end of that corridor, its face worn halfway up*, and one a post in a yard in a job line. A word-bounded sweep on the five communication verbs themselves returns zero on all ten pages** |
| `call`, any form | 40 | **every one of them inside the word *callers*, being the load-book's own noun for the people who come into a shop. Read and certified** |
| `sitting`, any form | 3 | **all three are the ordinary verb — *she said it sitting down*, *the chair she was sitting in*, *the place where she is sitting*. No sitting number is printed on any of these ten pages and no page remarks on anything about them** |
| `about eleven words` | 0 | **the phrase the volume reserves for its one answer at Chapter 1058 is free, and this movement did not spend it** |
| the register of correct acts that changed nothing | 10 files | printed as the figure four at both ends of all ten days, in each file's own words, and added to by nothing |
| the place behind the woman's chair | 1 file | **Chapter 1023 alone, and with no printed figure and no day-count** |
| the shutter at about two | 1 file | **Chapter 1021 alone; the other nine take the about-ten form** |
| "nobody thanked anybody" / "nobody forgave anybody" | 10 / 10 | all ten, in each file's own words |
| the three questions written out on the card | 0 | the card is named on all ten closing pages with a different description on each and the three questions are written out on none |
| a sitting number, or any figure for the book or the tin, or any difference between them | 0 | — |
| the nine words of the correction | 0 | named as nine words on six pages and written out on none |
| the four words | 0 | named on all ten and printed on none |
| the ten objects at the foot of each page | 10 files | **all ten present on all ten pages, and the rule as the pages write it holds on all ten: the footer's own claim is that not two of them are brought together in *any one of these sentences*, and each footer's ten sentences carry one object each. The wider claim this row first printed — that no sentence on any of the ten pages holds two of them — is FALSE, and §15 says where the eleven counterexamples are** |

## 10. WHAT THIS PASS CHANGED ON THE PAGES, AND WHY IT IS PUBLISHED AT THIS LENGTH

**The ten chapters were written complete, and then eight classes of defect were found by the instruments in this file and repaired by hand, in the same order in which they were found. Nothing below was found by reading the prose. Every item names the row that found it.** **THE FIRST PRINTING OF THIS SENTENCE SAID ELEVEN CLASSES AND THE TABLE BELOW HAS ALWAYS CARRIED EIGHT NUMBERED ROWS; the count is corrected to eight and no row has been added, because a pass cannot invent three defects to make a headline agree with a table. §15 records this and names the other five places the figure had spread to.**

| # | What was found | Found by | What it was | Done |
| --- | --- | --- | --- | --- |
| 1 | 135 occurrences of `one thousand and … hundred` in the anchor rows and the anchor paragraphs | §8's renderer, controlled against Movement II Chapter 1020's printed docket | **a rendering the house does not use. No chapter file in Volume 19's sixty or in Movements I and II prints an `and` after *thousand*; the house form is *one thousand eight hundred and eighty-four*. I wrote the other form on all ten pages and the control caught it on the first file it was pointed at** | **repaired on all ten pages** |
| 2 | The same test returned one wrong remainder | §8's self-consistency read-back | **Chapter 1030's fifteenth anchor row printed *two hundred and forty-five weeks and one day* for an interval of one thousand seven hundred and seventeen days, which is two days** | **repaired** |
| 3 | 193 pair-hits and seventeen shared keys at §6 and §7 | the duplication measure and the flat test | **a real guardrail-three breach, and the cause was mine: I copied the house's closing conditions block and its standing record verbatim from Movement II's closing pages onto all ten of mine, and guardrail three says the conditions row and the standing record are written in each file's own words. Four of those runs stood on all ten pages** | **all ten conditions blocks and all ten standing records rewritten in ten different shapes** |
| 4 | Nine uses of the word `right` | the forbidden-word sweep | **in five files and in scenes, not in frames, which is where Movement II's twenty-eight stood. One of them was in Chapter 1027's central sentence — a man admitting out loud why he refused a woman — and one was an *all right* that had to become something else** | **all nine repaired** |
| 5 | Two uses of the bare word `purpose` | the forbidden-word sweep | **one in a scene and one in a standing record, both in Chapter 1022** | **both repaired** |
| 6 | One duplicated job line in prose scope | the flat test | **the same fourteen tokens in Chapter 1025 and Chapter 1027** | **repaired in Chapter 1025** |
| 7 | Three duplicated book-and-tin rows in apparatus scope | the flat test | **the same-weekday pairs, Tuesday, Wednesday, Friday and Saturday** | **all ten of those rows rewritten in ten different wordings** |
| 8 | Chapter 1030's reflection paragraph had no sheet-night clause | the §8.2 read-back | **the other nine pages carry it and the tenth did not, so the run was nine values and not ten** | **clause restored with its derived value** |

**WHAT WAS REFUSED, WITH THE REASON, BECAUSE AN ARTIFACT THAT RECORDS ONLY WHAT IT DID IS HALF AN ARTIFACT.** This pass refused to run a mechanical substitution over the word `about`, for the reason at `NOVEL_SPEC.md`'s fifth Status block, and it says at §5.1 exactly which decision about the register was taken instead. It refused to touch the four `may` hits, because they are the modal verb inside one inherited sentence and there is nothing wrong with them. It refused to rewrite the eleven `post` hits, because they are a piece of masonry in a corridor. **It refused to edit `batch-0001/SUMMARY.md` or `batch-0002/SUMMARY.md`, because both carry closed-phase markers and a closed phase's measure of record is not this pass's to rewrite, and the two defects this pass found in the second of them are disclosed at §1 and §2 instead.** **It refused to touch `outline/volume-20.md`, `NOVEL_SPEC.md`, `state/phase-ledger.json`, `scripts/`, `.github/workflows/`, `.opencode/agent/` and `AGENTS.md`.** And it created no chapter and no prompt other than the one next-phase prompt named at §14.

## 11. WHAT THE MOVEMENT SPENT, AND WHAT IT DID NOT SPEND, VERIFIED AGAINST THE PAGES

**SPENT, ON THE PAGE, IN THIS ORDER.** A man of about thirty-seven who drives a van six nights a week asks for the three questions to be asked at a door over about nine days, and offers to lose about eleven hundred pounds standing at the bottom of a stair, and says in about nine words that asking people three things in advance worked where he did it, and that eleven people have not walked in off a street since. A woman who has kept a room for about nine years asks for the three questions to be asked out loud at that bench in front of everybody, and is refused in nine words, and says she will come back when he stops saying yes and then no in the same breath. Four people come up that stair on the Tuesday evening having already been asked on a landing. A man says four sentences in a room on the Wednesday and three people refuse all four, and he starts a fifth and abandons it about a second in. A woman of about twenty-nine says she cannot change her mind because she has already said yes on a landing, and goes up anyway. A woman of about thirty-four says she wants to be asked again where nine people can hear her not answering. **On the Monday he does not refuse the woman again, gives the reason in nine words — because a stranger is asking them first and he cannot be the second — and asks her three things at that bench in front of about nine people, and she answers two and will not answer the third in that room, and says she has had about nine of them for about four weeks and has said every one in a doorway to people who wrote nothing down.** On the Thursday the unsaid third thing acquires a face, because nine people glance at the chair she is sitting in, and a woman gets three words into a sentence about what the room is and is stopped by the woman who keeps it. **On the Wednesday of the following week a man says out loud in about nine seconds that he refused the woman because he did not want to ask everybody three things in front of everybody, and the woman it was about stands in the room and hears it.** On the Saturday a man of about thirty-seven says he stopped at the bottom of a stair and is going to start again somewhere with no room at the top of it, and tells somebody first so that it will not arrive from a road. A printer is asked for a card and says there is nothing to print, because there is no heading over it. **The cost, said out loud and printed nowhere: the asking at that bench was refused once on the Tuesday and was not refused again for about six days, and about four people who came up that stair that week had not come up the week before, and about four who had come up the week before did not come up that week, and Marek said to a till that he can name the four and cannot say why they did not come.**

**NOT SPENT, ON ANY PAGE.** The woman's page, printed on no page of this movement, with no value and no range for it in this file or in any of the ten chapter files, and the ring binder never off its shelf and nobody apologising to the woman of about thirty behind the fourth of those four doors. The four arrival cells, absent and not approximated. The fifth of the register of correct acts that changed nothing. Any Exchange figure, and the difference between the book and the tin, and any sitting number, and this movement contains no sitting. The nine words of the correction and the date on them. The four words. The three questions, written out on none of ten pages. A comparison of two of the nine hand copies. The heading of the fifth column, which is owner item 4, is unruled, is not proposed on any of these ten pages, and **is named as the reason a printer has nothing to print on Chapter 1030 without being proposed as an answer.** Any figure for the place behind the woman's chair on any page, and any day-count for it anywhere in the movement or in this file. **The woman of about sixty-two, whose one word is assigned to Movement IV, is on no page of this movement.** **And any sentence about what the institution is for** — the nearest thing on these ten pages is a woman who got three words into one on Chapter 1028 and was stopped by another woman, and who is told that four of them had waited about four seconds for her to finish.

## 12. THE SIX OWNER ITEMS ARE ALL UNRULED AND NONE IS SETTLED, RECOMMENDED OR RE-DERIVED HERE

**One: plan against disk.** `outline/series.md` and `outline/ending.md` say seven hundred and sixty chapters in fifteen volumes; **the disk holds one thousand and thirty chapter files in twenty volume directories**, which is Movement III's ten files added to the one thousand and twenty that were on disk when this prompt was written. Both figures are correct about their own file. **Writing Chapter 1021 did not decide whether this manuscript ends at 760, and neither did writing Chapter 1030.** **Two:** the support-spend overage at three readings, unsettled since Movement II of Volume 18, untouched. **Three:** the placed cast of five names at zero on these ten pages, **and no page was invented for any of them in order to make a cast figure come out; the reason is that none of the five is a van driver who has run advance-asking before, a woman who has kept a room for about nine years, a man with a press in a second district, or a man who has been standing at the bottom of a stair for nine days.** **Four:** the plan's phrase on Chapter 933, untouched. **Five:** the fifth column's heading, two items and not one, unruled, and **Chapter 1030 puts the absence of a heading to work as the reason a printer has nothing to print, which is a use of the absence and is not a proposal and not a settlement.** **Six:** the ombud's office used on him **zero times in this movement and zero times in each of the two before it**, and this file makes no statement about how many times it has been used in this manuscript; **and whether Chapter 760, Chapter 1000 or Chapter 1060 is the ending is the owner's and is unruled.**

## 13. WHAT A LATER PASS MUST NOT INHERIT FROM THIS FILE

**Do not quote any figure in §§4 to 9 as a house figure; every one is a measure of ten files.** **Do not take `about` from §5 as a movement rate and do not treat nineteen as settled — §5.1 is the record of a decision about a register and not a settlement of a target.** **Do not carry `batch-0002/SUMMARY.md` §14.5's quote-skipping row forward; it prints an equality this instrument does not produce, and §2 gives the measured mechanism.** **Do not control an instrument against `batch-0002/SUMMARY.md` §14.0 without reading §2 first, and do not read a lower quote-skipping row as a fault in your own instrument.** **Do not re-derive guardrail three from the proxy and do not expect the two keys' distinct counts to differ, because they cannot.** **Do not carry any of the three sheet-night figures forward; derive from the origin and the chapter's own day and say in your own summary which convention you used.** **Do not print an interval for the place behind the woman's chair, on any day, in any file, for any reason.** **Do not treat the five chapterless days inside this span as a rehearsal for anything.** And **do not take the zero at §7 to mean the prose was free: on this movement's first write there were one hundred and ninety-three pair-hits and they were all mine, and the reason is at §10 item 3, and the reason is that a house template is inherited by copying it and guardrail three requires it not to be.**

## 14. THE ONE NEXT PHASE, AND IT EXISTS

**`workspace/volume-20/batch-0004/PROMPT.md` — Movement IV, Chapters 1031 to 1040, days 2268 to 2281, weeks 340 to 342, load-book entries 1034 to 1043, governed counters 276 to 285, its Sunday at Chapter 1034, the seventy-fourth sitting at Chapter 1031 where the book shuts, and the movement in which three proposals for the heading of the fifth column are made and all three are refused and the fourth proposal is a blank with a rule under it.** It is the only prompt this phase created and it was written after every figure above was measured, so that its arithmetic is derived rather than inherited. **It carries into that movement the woman of about sixty-two and her one word, which Movement III did not use; the fact that a printer has nothing to print and has said so; the fact that a man of about thirty-seven is going to start again somewhere with no room at the top of it; and the fact that a sentence about what that room is for has been started three times on these ten pages and finished none of the times.**

---

## 15. THE REVIEW-REPAIR PASS OVER THESE TEN FILES, DATED 5 OCTOBER 2026, AND WHAT IT FOUND

**This section is appended by the pass that read `logs/batch-0003.review.log` and it is written in the same form as §8 of `batch-0003/PROMPT.md`: what a later pass found to be wrong is corrected in place above and recorded here, and not deleted.** The review log for this phase is a transcript and not a findings list — **the reviewer subagent fell back to the primary agent and the run was cut off before it wrote a verdict**, its last line being *Anchors all verify. Now the trap guardrails: the empty chair and bold-paragraph lengths.* **Everything below was therefore found by finishing that run's own checks and by auditing this file against its own pages, and no finding below is attributed to a reviewer that did not deliver one.** `logs/` is gitignored and is cited here only as the record of what was and was not delivered, which is the one thing a review log is good for.

### 15.1 THE TWO TRAPS THE CUT-OFF RUN WAS ABOUT TO CHECK, AND BOTH WERE CLEAR

**The place behind the woman's chair.** The calendar file at §2 and §5.7, and §3 of this movement's prompt, all place its printed figure on Chapter 1003 alone; **§5 of that prompt says its printed figure falls on Chapter 1023 alone, which contradicts all three, and the prompt's sentence is the error and not the pages'.** Chapter 1023 names the place once, at the ninth beat, in a sentence where Marek works the sum out with his hands behind him where nine people can see him doing it **and says no word of it aloud**, and no figure, no interval and no day-count for that place is printed on any of these ten pages or anywhere in this file. **The trap was not walked into, and the page's own construction is the reason: the sum is done in front of nine people and the figure is withheld from the reader as it is withheld from the room.** The prompt's sentence is corrected at `workspace/volume-20/batch-0003/PROMPT.md` §5 and recorded in that file's own §9, and it is corrected rather than deleted for the reason §6 of that prompt gives.

**The opening bold paragraphs.** All ten stand inside the forty-to-seventy-five band at **51, 46, 48, 51, 49, 55, 62, 57, 51 and 54** on the pages as they now stand, none carries a numeral, and none states an outcome or reports anything a person in another building said. **The second half of that sentence was false of Chapter 1030 on the first write and is the fourth finding below.**

### 15.2 THE FOUR FINDINGS, ALL TAKEN, AND TWO OF THEM TOOK PAGES

| # | What was found | How it was found | What it was | Done |
| --- | --- | --- | --- | --- |
| 1 | Two titles carried a number-word | H1 sweep against `outline/volume-20.md` deviation four, which forbids one | **Chapter 1024 read *A Yes Given On The Second Landing* and Chapter 1028 read *The Third Thing Nobody Would Say*. `Second` and `Third` are number-words, the rule does not distinguish ordinals from cardinals, and the one precedent for enforcing it in this volume is Chapter 1012, renamed for the same reason.** This file's own §4 also asserted *none carrying a number-word*, so the measure and the pages were wrong together | **Chapter 1024 reads *The Yes She Could Not Take Back* and Chapter 1028 reads *The Place Where She Is Sitting*, which is the woman of about thirty-four's own phrase for what the page turns on. Both word counts are unchanged, so §4's row of figures did not move and only its claim had to become true** |
| 2 | Three pairs of lead-ins shared their opening eight words | the opening-eight-words test the Movement III prompt §1 names and the twelve-token measure cannot perform | **Chapters 1023 and 1027, 1024 and 1029, 1025 and 1030. The prompt warned in advance that this frame was Movement I's single largest exposure at twenty-eight pair-hits across eight of ten files, that it came back on ten files with no prior repair, and that the measure returns zero on all ten and could return nothing else. It came back on six of ten files in three pairs** | **the later file of each pair re-opened: 1027, 1029 and 1030. Each still states its day and the shape of its day and each now leads with that day's own fact. All ten are now distinct at eight words** |
| 3 | Chapter 1030's lead-in reported what a person in another building said | §6's own rule, read against the page | **the lead-in ended *Marek walked about nine minutes into a second district in the afternoon and was told there was nothing to print*, which is a printer in another district speaking, and it also gave away the page's turn eleven hours before the page delivers it at *then I have nothing to print*** | **the clause is gone. The walk to the second district and the printer's refusal are untouched in the body, where they were already on the page, so nothing was lost but the warning** |
| 4 | Five cells of this file were wrong about its own pages | §4, §5 and §9 read back against the files | **§5's pooled `about` table had its case-sensitive and case-insensitive columns transposed in two of three scopes; §4's word table and lead-in row went stale the moment findings 1 to 3 were applied; §9's ten-objects row asserted a page-wide rule the pages do not write; and the headline said eleven classes against §10's eight rows** | **all five corrected in place, each with its own paragraph above saying what the first printing said** |

### 15.3 THE TEN-OBJECTS CLAIM, AND WHERE THE ELEVEN COUNTEREXAMPLES ARE

**§9 first printed that *no sentence on any of the ten pages holds two of them, checked sentence by sentence*. That is false and the false part is specific.** The footers carry the rule in Movement II's and Movement III's wording — *not two of them are brought together in any one of **these** sentences* — and by that wording all ten footers pass, one object per sentence, ten sentences, ten objects. **Movement I's wording at Chapter 1010 is wider: *no two of them are brought together in **any** sentence*, and by that wording all ten of these pages fail.**

**Eleven sentences across the ten pages name two of the ten, and they are three inherited frames and not eleven defects.** *One:* on all ten, the closing-conditions sentence names the book in the green binding and the tin beside it together — *By ten on that Wednesday the book in the green binding had been shut and the tin beside it was down* — and it is the same sentence, in ten different wordings, on all ten of Movement II's files, where it stands as `workspace/volume-20/batch-0002/chapter-1020.md` line 157. *Two:* on nine, the day's callers sentence names the shop's own day-book and the shutter — and the day-book is **not** one of the ten objects, which are the book in the green binding, and a sweep that cannot tell two books apart will manufacture this counterexample on its own. *Three:* on ten, the sixteen-row standing-anchor docket names the card, the board, the nicks and the corners, but in sixteen rows and not in one sentence, and an instrument that drops paragraph breaks before it splits sentences will merge sixteen rows into one apparent sentence and report it. **All three are artefacts of a rule stated more widely than the pages state it, and none of them is repaired here, because the book-and-tin row is a required closing condition of this manuscript and not a clause of the ten-objects list, and because the other two are the instrument's and not the page's.** The rule is now printed at §9 as the pages write it, and the wider form is recorded at `state/open-threads.md` as a question about the wording rather than about these ten chapters.

### 15.4 WHAT THIS PASS DID NOT TOUCH, AND WHY

**It did not rewrite a chapter.** Five paragraph-level and two heading-level repairs, on five files, and not one scene, not one dialogue exchange, not one job line and not one word of Marek's or anybody else's mouth. **It did not change the plot, the day map, the anchors, the night run, the charges, the callers, the duplication result or any guardrail sweep, all of which it re-derived and found correct.** **It did not edit `outline/volume-20.md`, `NOVEL_SPEC.md`, `state/phase-ledger.json`, `scripts/`, `.github/workflows/`, `.opencode/agent/` or `AGENTS.md`.** **It did not edit `batch-0001/` or `batch-0002/`, and the nine unrepaired number-word titles it found while renaming two are recorded and not repaired.** **It did not create a prompt.** The Movement IV prompt already existed and was corrected in two places; no prompt for any chapter after Chapter 1040 exists and none was made.

### 15.5 AND THE ONE FIGURE THIS PASS PUTS ON THE RECORD THAT NO INSTRUMENT IN THIS FILE PRODUCED

**Movement III's ten lead-ins, measured at the opening eight words, now stand at zero shared keys across ten files, and the number of files involved in a collision before the repair was six and not four.** `workspace/volume-20/batch-0004/PROMPT.md` §7 states that *four of them still share their opening eight words*, **which is Movement II's published figure carried forward one movement and is wrong about these ten files**: the correct first-printing figure is six files in three pairs, and after the repair it is zero. **That sentence is corrected in place and not deleted, and it is the second time in two phases that a figure about lead-ins has been inherited instead of counted.**

---

*Ten chapters, 1021 to 1030, at `workspace/volume-20/batch-0003/`. Day map 2251 to 2264, weeks 337 to 339, load-book entries 1024 to 1033, governed counters 266 to 275. No sitting falls in this movement. **Written complete on the first pass, then eight classes of defect found by the instruments and repaired by hand, including one hundred and ninety-three guardrail-three pair-hits that were all caused by a house template being copied rather than rewritten. Movement III is handed on, with two titles and three opening paragraphs repaired after the fact by the pass recorded at §15 and with five cells of this file corrected by that same pass. Movement IV is dispatched at `workspace/volume-20/batch-0004/PROMPT.md`, and no prompt exists for any chapter after Chapter 1040.***