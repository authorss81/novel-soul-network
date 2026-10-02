# Volume 19 — Arithmetic and Calendar

**This file is the plan of record for Volume 19's arithmetic. It is written before Chapter 941 and it is not the measure of record for the chapters; the measure of record for the chapters is `workspace/volume-19/batch-0001/SUMMARY.md` after Movement I, and the volume close writes section 9 beside this one, as in Volumes 15, 16, 17 and 18.**

---

# THE FLAG, AND IT IS THE SAME ONE THE VOLUME OUTLINE OPENS WITH

**A nineteenth volume exists and did not exist in the plan of record.** `outline/series.md` says fifteen volumes and 760 chapters. `outline/ending.md` says the manuscript ends at Chapter 760. **Volume 16 was created by a directive to continue the novel, Volume 17 by a second, Volume 18 by a third, and Volume 19 by a fourth.** In the words `outline/volume-18.md` line 147 used for the third: **this volume makes the plan of record false by a fourth step, and it is written on a fourth continuation directive in the same terms as the first three.** The standing directive is at `workspace/continuation/next/PROMPT.md`, its directory carries a `.done` marker, and a directive is not a decision.

**OWNER ITEM 1 IS NOT SETTLED BY THIS FILE AND IS NOT SETTLED BY CHAPTER 941.** `outline/series.md`, `outline/ending.md`, `NOVEL_SPEC.md`, `outline/volume-15.md` through `outline/volume-18.md` and `bible/*.md` were read and not written. `NOVEL_SPEC.md`'s eighth Status block is untouched and still records that the volume decision has not been taken and that no agent pass may write it. `state/phase-ledger.json` is controller-owned and was read and not written. **The other five owner items are unruled and are not settled, recommended or re-derived here.**

---

## 0. THE INSTRUMENT, ITS BOUNDARY, ITS ASSERTIONS, AND WHAT WAS ASSERTED AGAINST WHAT

### 0.1 THE BOUNDARY, IN A NOTATION A LATER PASS CAN RE-RUN

- **WEEK:** `(day − 502) // 7 + 88`
- **WEEKDAY:** `(day − 502) mod 7`, Monday-first, `0` Monday through `6` Sunday
- **MONDAY OF WEEK _W_:** `7 × W − 114`
- **TOKENISER, for every figure below that is stated in words:** `[A-Za-z0-9]+(?:-[A-Za-z0-9]+)*`. A hyphenated compound is one token. **The tokeniser does not admit a colon, so a twenty-four-hour clock time is two tokens, and every published word count in this manuscript is one word higher for every such time on a page.** This is inherited unchanged from `workspace/continuation/next-0020/GATE.md` §3.0 and it is printed here because it is the boundary and the boundary is not optional.
- **CARDINAL:** thousands rendered as `one thousand` up to nineteen hundred and ninety-nine and as `two thousand …` above it; hundreds with `and` before a remainder of under a hundred; tens compounds hyphenated (`twenty-one` is one word and not two).
- **WEEKS RENDERING:** `N weeks to the day` when the remainder is zero, `N weeks and one day` when it is one, `N weeks and M days` otherwise. A semicolon and a colon are not terminators of a figure. A run whose preceding non-conjunction token is `week` or `weeks` is not a figure of its own.

### 0.2 THE ASSERTIONS, AND THEY RAN BEFORE THIS FILE WAS POINTED AT A CHAPTER

**Forty-eight assertions, forty-eight reproduced.**

| Block | Assertions | What it protects | Source of the expected values |
| --- | --- | --- | --- |
| cardinal renderings | 6 | the forms used in the anchor table below | printed verbatim in Volume 18 chapter files |
| weeks-and-days renderings | 6 | the zero component takes `to the day`, the singular takes `one day` | printed verbatim in Volume 18 chapter files |
| calendar rows | 20 | `week` and `wd` against eight published Volume 17 and 18 rows | printed verbatim in Volume 17 and 18 chapter files |
| Monday-of-week identity | 16 | `7 × W − 114` lands inside week _W_ and on a Monday, for every week this volume uses | the identity itself, re-derived per week and not tabulated by hand |
| **the total, which is the sum of the column** | **48** | | |

**AND SIXTEEN OF THE FORTY-EIGHT COULD NOT HAVE FAILED, AND THAT IS DISCLOSED RATHER THAN COUNTED AS A RESULT.** The sixteen Monday-of-week assertions are `monday_of(W) = 7W − 114` composed with the two detectors, and the composition is the definition of the map, so they confirm the arithmetic and do not test it. **Thirty-two are able to fail and sixteen are not. The total above is a sum of the column and the column carries no column for that distinction, which is the same omission that made Volume 18's close rebuild its table.** They are printed because Volume 18's close published that it had sixty such assertions and could not fail, and a pass that hides them is the defect it is measuring.

**AND ONE EXPECTED VALUE WAS WRONG ON THE FIRST RUN AND THE INSTRUMENT WAS RIGHT.** The first control vector for the cardinal renderer was authored with the trailing word *days* inside the expected string. The renderer does not produce *days* and should not. **This is the second recorded instance in this repository of an assertion whose expected value shared an author with the code under it, and it is the same class as `next-0020/GATE.md` §3.2 fault 2, and it was caught by reading the failure rather than by the assertion passing.**

### 0.3 THE CONTROL: VOLUME 18'S OWN ROWS, RUN BEFORE THIS VOLUME'S FIGURES WERE PUBLISHED

| What Volume 18 prints | What this detector returns | Verdict |
| --- | --- | --- |
| Chapter 881 is the Monday of week 301, day 1993 | week 301, weekday 0 | reproduces |
| Chapter 921 is the Monday of week 312, day 2070 | week 312, weekday 0 | reproduces |
| Chapter 925 is the Sunday of week 312, day 2076 | week 312, weekday 6 | reproduces |
| Chapter 931 is the Wednesday of week 314, day 2086 | week 314, weekday 2 | reproduces |
| Chapter 939 is the Monday of week 316, day 2098 | week 316, weekday 0 | reproduces |
| Chapter 940 is the Wednesday of week 316, day 2100 | week 316, weekday 2 | reproduces |
| day 1538 and day 1764 sit on the detectors | week 227 and week 260 | reproduces |

---

## 1. THE DAY MAP, ALL SIXTY ROWS

| Movement | Chapter | Day | Week | Weekday | Load-book entry | Governed counter |
| --- | --- | --- | --- | --- | --- | --- |
| I | 941 | two thousand one hundred and five | 317 | Monday | 944 | 186 |
| I | 942 | two thousand one hundred and six | 317 | Tuesday | 945 | 187 |
| I | 943 | two thousand one hundred and seven | 317 | Wednesday | 946 | 188 |
| I | 944 | two thousand one hundred and eight | 317 | Thursday | 947 | 189 |
| I | 945 | two thousand one hundred and ten | 317 | Saturday | 948 | 190 |
| I | 946 | two thousand one hundred and eleven | 317 | Sunday | 949 | 191 |
| I | 947 | two thousand one hundred and twelve | 318 | Monday | 950 | 192 |
| I | 948 | two thousand one hundred and thirteen | 318 | Tuesday | 951 | 193 |
| I | 949 | two thousand one hundred and fourteen | 318 | Wednesday | 952 | 194 |
| I | 950 | two thousand one hundred and fifteen | 318 | Thursday | 953 | 195 |
| II | 951 | two thousand one hundred and nineteen | 319 | Monday | 954 | 196 |
| II | 952 | two thousand one hundred and twenty | 319 | Tuesday | 955 | 197 |
| II | 953 | two thousand one hundred and twenty-one | 319 | Wednesday | 956 | 198 |
| II | 954 | two thousand one hundred and twenty-two | 319 | Thursday | 957 | 199 |
| II | 955 | two thousand one hundred and twenty-four | 319 | Saturday | 958 | 200 |
| II | 956 | two thousand one hundred and twenty-six | 320 | Monday | 959 | 201 |
| II | 957 | two thousand one hundred and twenty-eight | 320 | Wednesday | 960 | 202 |
| II | 958 | two thousand one hundred and thirty | 320 | Friday | 961 | 203 |
| II | 959 | two thousand one hundred and thirty-two | 320 | Sunday | 962 | 204 |
| II | 960 | two thousand one hundred and thirty-four | 321 | Tuesday | 963 | 205 |
| III | 961 | two thousand one hundred and thirty-nine | 321 | Sunday | 964 | 206 |
| III | 962 | two thousand one hundred and forty | 322 | Monday | 965 | 207 |
| III | 963 | two thousand one hundred and forty-one | 322 | Tuesday | 966 | 208 |
| III | 964 | two thousand one hundred and forty-three | 322 | Thursday | 967 | 209 |
| III | 965 | two thousand one hundred and forty-five | 322 | Saturday | 968 | 210 |
| III | 966 | two thousand one hundred and forty-seven | 323 | Monday | 969 | 211 |
| III | 967 | two thousand one hundred and forty-nine | 323 | Wednesday | 970 | 212 |
| III | 968 | two thousand one hundred and fifty | 323 | Thursday | 971 | 213 |
| III | 969 | two thousand one hundred and fifty-one | 323 | Friday | 972 | 214 |
| III | 970 | two thousand one hundred and fifty-two | 323 | Saturday | 973 | 215 |
| IV | 971 | two thousand one hundred and fifty-six | 324 | Wednesday | 974 | 216 |
| IV | 972 | two thousand one hundred and fifty-seven | 324 | Thursday | 975 | 217 |
| IV | 973 | two thousand one hundred and fifty-eight | 324 | Friday | 976 | 218 |
| IV | 974 | two thousand one hundred and sixty | 324 | Sunday | 977 | 219 |
| IV | 975 | two thousand one hundred and sixty-two | 325 | Tuesday | 978 | 220 |
| IV | 976 | two thousand one hundred and sixty-four | 325 | Thursday | 979 | 221 |
| IV | 977 | two thousand one hundred and sixty-five | 325 | Friday | 980 | 222 |
| IV | 978 | two thousand one hundred and sixty-six | 325 | Saturday | 981 | 223 |
| IV | 979 | two thousand one hundred and sixty-seven | 325 | Sunday | 982 | 224 |
| IV | 980 | two thousand one hundred and sixty-eight | 326 | Monday | 983 | 225 |
| V | 981 | two thousand one hundred and seventy-three | 326 | Saturday | 984 | 226 |
| V | 982 | two thousand one hundred and seventy-four | 326 | Sunday | 985 | 227 |
| V | 983 | two thousand one hundred and seventy-five | 327 | Monday | 986 | 228 |
| V | 984 | two thousand one hundred and seventy-six | 327 | Tuesday | 987 | 229 |
| V | 985 | two thousand one hundred and seventy-eight | 327 | Thursday | 988 | 230 |
| V | 986 | two thousand one hundred and eighty | 327 | Saturday | 989 | 231 |
| V | 987 | two thousand one hundred and eighty-two | 328 | Monday | 990 | 232 |
| V | 988 | two thousand one hundred and eighty-three | 328 | Tuesday | 991 | 233 |
| V | 989 | two thousand one hundred and eighty-four | 328 | Wednesday | 992 | 234 |
| V | 990 | two thousand one hundred and eighty-five | 328 | Thursday | 993 | 235 |
| VI | 991 | two thousand one hundred and eighty-nine | 329 | Monday | 994 | 236 |
| VI | 992 | two thousand one hundred and ninety | 329 | Tuesday | 995 | 237 |
| VI | 993 | two thousand one hundred and ninety-one | 329 | Wednesday | 996 | 238 |
| VI | 994 | two thousand one hundred and ninety-two | 329 | Thursday | 997 | 239 |
| VI | 995 | two thousand one hundred and ninety-four | 329 | Saturday | 998 | 240 |
| VI | 996 | two thousand one hundred and ninety-six | 330 | Monday | 999 | 241 |
| VI | 997 | two thousand one hundred and ninety-nine | 330 | Thursday | 1000 | 242 |
| VI | 998 | two thousand two hundred and three | 331 | Monday | 1001 | 243 |
| VI | 999 | two thousand two hundred and seven | 331 | Friday | 1002 | 244 |
| VI | 1000 | two thousand two hundred and twelve | 332 | Wednesday | 1003 | 245 |

**THE SIX MOVEMENT SPANS AND THE DAYS INSIDE THEM THAT CARRY NO CHAPTER.**

| Movement | Span | Days in the span | Chapters | Days with no chapter |
| --- | --- | --- | --- | --- |
| I | 2105–2116 | 12 | 10 | two thousand one hundred and nine, two thousand one hundred and sixteen |
| II | 2119–2134 | 16 | 10 | twenty-three, twenty-five, twenty-seven, twenty-nine, thirty-one, thirty-three, as hundreds with the two thousand prefix |
| III | 2139–2152 | 14 | 10 | forty-two, forty-four, forty-six, forty-eight |
| IV | 2156–2169 | 14 | 10 | fifty-nine, sixty-one, sixty-three, sixty-nine |
| V | 2173–2185 | 13 | 10 | seventy-seven, seventy-nine, eighty-one |
| VI | 2189–2212 | 24 | 10 | fourteen in the span |

**AND THE CLEAR DAYS BETWEEN THE MOVEMENTS: two after Movement I, four after II, three after III, three after IV, three after V.** `2105 + 107 − 1 = 2211` is not the last day of the volume; the last day is 2212 and it is the last chapter.

**THE SPANS SUM TO 107 DAYS INCLUSIVE AND THE SIX MOVEMENTS TO 91, AND THE TWO NUMBERS ARE NEVER ADDED.** The governed counter runs 186 to 245 and is a chapter-indexed row count and not the calendar span.

### 1.1 THE FOUR COLLISION DAYS THAT FALL BETWEEN MOVEMENTS

**Days 2117 and 2118 fall between Movements I and II, days 2135 to 2138 between II and III, 2153 to 2155 between III and IV, 2170 to 2172 between IV and V, and 2186 to 2188 between V and VI.** No chapter of this volume carries any of them and **no chapter may treat one as a rehearsal for anything.** A collision is a coincidence between two integers.


### 1.1 FOUR WEEKDAYS IN THE TABLE ABOVE WERE WRONG ON THE FIRST WRITE AND WERE REPAIRED IN THIS FILE BEFORE IT WAS USED

**The table above was checked by re-deriving all sixty rows against the detector at §0.1 and against the chapter-to-day assignment at §1, and four of them printed the wrong weekday: Chapters 961, 981, 982 and 997.** The days and the week numbers were right on all sixty rows and the weekday was wrong on four, and `wd = (day − 502) mod 7` returns Sunday for Chapter 961, Saturday for 981, Sunday for 982 and Thursday for 997. **All four have been corrected in place in the table above and no day, week, entry or counter was touched. THE FINDING IS RECORDED HERE BECAUSE IT IS THE THIRD RECORDED INSTANCE IN THIS REPOSITORY OF A DAY-MAP ROW DISAGREEING WITH THE DETECTOR, AND THE FIRST ONE THAT WAS FOUND AND REPAIRED IN THE SAME PASS THAT WROTE IT. The other two are Volume 18's Chapter 930, which is the repository owner's and is named at `workspace/volume-18/ARITHMETIC-AND-CALENDAR.md` §9.3, and this one. A pass that does not re-derive a day map against the detector before pointing a chapter at it will find the class again.**

---

## 2. THE SIXTEEN STANDING ANCHORS AND THEIR ORIGINS

**Every origin below is derived from a figure printed in `workspace/volume-18/batch-0006/chapter-0940.md`, at day 2100, so that each anchor is continuous with the last volume rather than restarted.** The origin is the day on which the count was zero, and it is never printed on a page.

| Anchor, as the pages name it | Origin |
| --- | --- |
| Four units standing off that service road, one of them carrying heat | 362 |
| The one card in that rail, once creased across its middle | 358 |
| The twelfth of nineteen ruled lines on that board up on two nails | 442 |
| The thirteenth of those lines, ruled under the twelfth and blank | 491 |
| The fourteenth of that board, ruled below the thirteenth, blank | 526 |
| The fifteenth of that board, low among the nineteen | 547 |
| The sixteenth of those lines, never once written on | 572 |
| The seventeenth of the nineteen, standing under the sixteenth | 590 |
| The eighteenth of that board, second up from its foot | 644 |
| The nineteenth and last ruled line on that board | 666 |
| That space on the sheet marked for a date, which stood empty for all of the above | 672 |
| The hold across nine crates and the floor beneath every one of them | 729 |
| The man of about fifty-one, unmoved from that north wall | 756 |
| Nine copies of the front of one page, each of them torn at a corner | 796 |
| The post at the far end of that corridor, its face worn halfway up | 814 |
| One written line written inside that box off that road | 982 |

**THE PLACE BEHIND THE WOMAN'S CHAIR carries origin 1484** and is named on three files of Movement I and prints a figure on one of them, which is Chapter 941. **THE FIGURE IS NEVER PRINTED IN THIS FILE**, because a figure printed in a plan is a figure a later pass can copy out of it, and the binder's figure is not printed in this volume anywhere at all.

### 2.1 THE TWO SHORT-RUN ANCHORS THAT BEGIN IN MOVEMENT I

**A printed form up on a wall in a passage in a fourth district by two drawing pins: origin 2092.** It went up on the Tuesday of week 315 and it is thirteen days old at Chapter 941 and twenty-three days old at Chapter 950. **It is the only anchor in this volume with an origin inside Volume 18 and it is the fastest-moving thing on any page in Movement I, and no page may remark on that either.**

**A request in writing, signed by one person, asking one room to look at one book: origin 2113.** It is one day old at Chapter 949 and two days old at Chapter 950. **It is the first document in this matter that carries a name and the name on it is not one of the nine.**

---

## 3. THE FOUR SITTINGS, AND WHAT IS FORBIDDEN ABOUT THEM

| Sitting | Week | Day | Chapter | Movement | The book |
| --- | --- | --- | --- | --- | --- |
| sixty-ninth | 320 | two thousand one hundred and twenty-eight | 957 | II | shuts |
| seventieth | 324 | two thousand one hundred and fifty-six | 971 | IV | opens |
| seventy-first | 328 | two thousand one hundred and eighty-four | 989 | V | shuts |
| seventy-second | 332 | two thousand two hundred and twelve | 1000 | VI | opens |

**AND THE PATTERN IS SHUT, OPEN, SHUT, OPEN, which is not Volume 15's, not Volume 16's, not Volume 17's and not Volume 18's. It is not a rule and it is not evidence and no page may describe it as a change in the woman who holds that room.**

**NO EXCHANGE FIGURE IS PRINTED IN THIS FILE.** The book and the tin are at their Volume 18 closing figures on the first day of this volume. **The difference between the book and the tin is not printed here in one sentence or in any sentence, and neither is the difference between any two of these four sittings' figures, and a later pass that needs either must go to the volume close and not to this file.**

---

## 4. THE FIGURES THIS FILE DELIBERATELY DOES NOT CARRY

1. **The woman's page is `day − 1573`. IT IS NOT PRINTED HERE AND NO CHAPTER OF THIS VOLUME PRINTS IT.**
2. **The four arrival cells are printed empty, and they are printed empty because a cell that cannot be measured is printed empty and is not approximated.**
3. **The register of correct acts that changed nothing stands at four and is not counted here and no fifth is written.**
4. **No two of the nine hand copies are compared in this file.**
5. **The difference between the book and the tin, and between any two of the four Exchange figures, is not printed in this file.**

---

## 5. WHAT A LATER PASS NEEDS FROM THIS FILE, IN SEVEN LINES

1. **Chapter 941 is the Monday of week 317, day 2105, entry 944, governed counter 186. Chapter 950 is the Thursday of week 318, day 2115, entry 953, counter 195.**
2. **Movement I's ten days are 2105, 2106, 2107, 2108, 2110, 2111, 2112, 2113, 2114 and 2115, and days 2109 and 2116 carry no chapter.**
3. **The one Sunday of Movement I is Chapter 946, day 2111, and the shutter comes down at about two on it and at about ten on the other nine.**
4. **The fourth of those four rooms is shut by half past six on all ten days, a woman of about thirty is behind that door, and the binder does not come down.**
5. **The request is signed on Chapter 948, day 2113, and it is the first document in this matter with a name on it.**
6. **The records-room man arrives up that stair on Chapter 949, day 2114, nine days after he was written to. Nine days is stated in words and never as a figure.**
7. **No sitting falls in Movement I and no number is said out loud anywhere in this city on any of its ten days.**

---

## 6. WHAT A VOLUME 19 CLOSE OWES AND WHAT IT MAY NOT SPEND

**OWED: section 9, headed *Written by the volume close, and by nobody before it*, and a `close/CLOSE.md` beside it, and both of them at volume scope rather than at movement scope, because six movement summaries that each publish a figure true of ten files have cost this repository four wrong columns already.**

**MAY NOT BE SPENT: the woman's page; the four arrival cells; the fifth of the register; any Exchange figure; any comparison of two of the nine hand copies; the fifth column's heading; the plan's phrase on Chapter 933; the ombud's office as used on him in Volume 18; and the question whether Chapter 760 is this manuscript's ending, which is the owner's and which is owed a page at `outline/ending.md` line 160 and not at line 77.**

---

## 7. AN EXERCISE A PASS MAY DO AND MAY NOT USE AS A FIGURE

**The counts below are re-derivable from section 1 and section 2 at the boundaries printed in section 0.1, and a later pass may check any of them. A later pass may not quote one of them as a house figure, because this file is a plan and not a measure of record.**

| What | Value |
| --- | --- |
| Days in Movement I's span | 12 |
| Chapters in Movement I | 10 |
| Days in Movement I's span with no chapter | 2 |
| Exact weeks to the day on Movement I's Monday, for the four units off that service road | 249 |
| Exact weeks to the day on Movement I's Monday, for the sixteenth of those lines | 219 |
| Sundays among Movement I's ten days | 1 |
| Sittings among Movement I's ten days | 0 |
| Anchor figures in the docket of every one of these ten files | 16 of the 16, on all ten |
| Anchor figures in the prose of Chapter 941 | 3 — the four units off that service road, the space marked for a date, and the man of about fifty-one |
| Anchor figures in the prose of Chapters 942 to 949 | 2 each |
| Anchor figures in the prose of Chapter 950 | 1 — the four units. The other two on that page are the short-run anchors at §2.1 and are stated in days and not as weeks |
| The one anchor figure in this movement's prose that reads to the day on a file other than 941 | none. 941 carries three and 942 to 950 carry two or one |
| The place behind the woman's chair | printed on Chapter 941 and on no other file of this movement |

**AND ONE FIGURE IS LEFT EMPTY ON PURPOSE. The place behind the woman's chair on Chapter 941 is printed on that page in the page's own words and in this file it is empty, because the origin is printed in section 2 and the origin plus the day is the figure and a plan that prints the figure is a plan a later pass can lift.**

---

## 8. THE STANDING RECORD FOR THIS VOLUME, WHICH IS NOT THE PLAN AND IS NOT A FIGURE

**Volume 18 is closed at Chapter 940 and nothing in this file reverses, softens, retcons or improves on one word of it.** Iona Sorn is the last enemy in this manuscript and is in public custody and is unanswered and is not absolved. The ninth chair does not move and its mover is named nowhere. The room under the building in a first district is dark. The answer to Volume 08's question is a chair he does not sit in.

**The five hundred and twenty-seven days that Volume 18's close set down for the woman's page at Chapter 940 is arithmetic and has no page under it, and this file prints no figure for it either.** The place behind the chair reached six hundred and sixteen days at Chapter 940 and no page of Volume 18 printed that as a number, and **this file prints no number for it either.**
