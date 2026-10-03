# Volume 20 — Arithmetic and Calendar

**This file is the plan of record for Volume 20's arithmetic. It is written before Chapter 1001 and it is not the measure of record for the chapters; the measure of record for the chapters is `workspace/volume-20/batch-0001/SUMMARY.md` after Movement I, and the volume close writes section 9 beside this one, as in Volumes 15, 16, 17, 18 and 19.** Sections 0 to 8 are the plan and were written before Chapter 1001; section 9 is owed to the volume close and is not written here and nobody may write it who is not that close.

---

# THE FLAG, AND IT IS THE SAME ONE THE VOLUME OUTLINE OPENS WITH

**A twentieth volume exists and did not exist in the plan of record.** `outline/series.md` says fifteen volumes and 760 chapters. `outline/ending.md` says the manuscript ends at Chapter 760. **Volume 16 was created by a directive to continue the novel, Volume 17 by a second, Volume 18 by a third, Volume 19 by a fourth, and Volume 20 by a fifth.** In the words `outline/volume-19.md` line 148 used for the fourth: **this volume makes the plan of record false by a fifth step, and it is written on a fifth continuation directive in the same terms as the first four.** The standing directive is at `workspace/continuation/next/PROMPT.md`, its directory carries a `.done` marker, and a directive is not a decision.

**AND THE SECOND FLAG, WHICH THE VOLUME OUTLINE STATES AT LENGTH AND WHICH IS RESTATED HERE ONCE BECAUSE THIS FILE IS WHAT A WRITER LOADS FOR A DAY.** `outline/ending.md` line 160, the prescribed final image, is carried on the last page of this volume. Chapter 759 already carries a converted tram depot, a scarred workbench and about eleven people asked three things each, and the difference between the two pages is who asks and where, and this file has no view on the image and holds no figure for it. **This file does not decide whether this manuscript ends on this page. Whether Chapter 760, Chapter 1000 or Chapter 1060 is the ending is owner item 6 and is unruled.**

**OWNER ITEM 1 IS NOT SETTLED BY THIS FILE AND IS NOT SETTLED BY CHAPTER 1001.** `outline/series.md`, `outline/ending.md`, `NOVEL_SPEC.md`, `outline/volume-15.md` through `outline/volume-19.md` and `bible/*.md` were read and not written. `NOVEL_SPEC.md`'s eighth Status block is untouched and still records that the volume decision has not been taken and that no agent pass may write it. `state/phase-ledger.json` is controller-owned and was read and not written, and no flag about it is appended anywhere in this file. **The other five owner items are unruled and are not settled, recommended or re-derived here.**

---

## 0. THE INSTRUMENT, ITS BOUNDARY, ITS ASSERTIONS, AND WHAT WAS ASSERTED AGAINST WHAT

### 0.1 THE BOUNDARY, IN A NOTATION A LATER PASS CAN RE-RUN

- **WEEK:** `(day − 502) // 7 + 88`
- **WEEKDAY:** `(day − 502) mod 7`, Monday-first, `0` Monday through `6` Sunday
- **MONDAY OF WEEK _W_:** `7 × W − 114`
- **TOKENISER, for every figure below that is stated in words:** `[A-Za-z0-9]+(?:-[A-Za-z0-9]+)*`. A hyphenated compound is one token. **The tokeniser does not admit a colon, so a twenty-four-hour clock time is two tokens, and every published word count in this manuscript is one word higher for every such time on a page.** This is inherited unchanged from `workspace/continuation/next-0020/GATE.md` §3.0 and it is printed here because the boundary is the boundary and is not optional.
- **CARDINAL:** thousands rendered as `one thousand` up to nineteen hundred and ninety-nine and as `two thousand …` above it; hundreds with `and` before a remainder of under a hundred; tens compounds hyphenated (`twenty-one` is one word and not two).
- **WEEKS RENDERING:** `N weeks to the day` when the remainder is zero, `N weeks and one day` when it is one, `N weeks and M days` otherwise. A semicolon and a colon are not terminators of a figure. A run whose preceding non-conjunction token is `week` or `weeks` is not a figure of its own.
- **THE DAY MAP'S ONLY HOME IS SECTION 1 OF THIS FILE.** The volume outline quotes no day of it, and a figure that appears in two files is a figure a later pass will take from the wrong one.

### 0.2 THE ASSERTIONS, AND THEY RAN BEFORE THIS FILE WAS POINTED AT A CHAPTER

**Sixty-two assertions, sixty-two reproduced, and ten of the sixty-two could not have failed and are disclosed rather than counted as results.**

| Block | Assertions | What it protects | Source of the expected values |
| --- | --- | --- | --- |
| cardinal renderings | 6 | the forms used in the anchor table below | printed verbatim in Volume 19 chapter files |
| weeks-and-days renderings | 6 | the zero component takes `to the day`, the singular takes `one day` | printed verbatim in Volume 19 chapter files |
| calendar rows | 20 | `week` and `wd` against thirteen published Volume 17, 18 and 19 rows | printed verbatim in those chapter files |
| day-map rows | 30 | `week` and `wd` re-derived against the detectors for thirty of the sixty rows before the table was written out in words | the detectors themselves, composed |
| **the total, which is the sum of the column** | **62** | | |

**THE THIRTY DAY-MAP ASSERTIONS ARE THE ONES THAT COULD NOT HAVE FAILED.** They are `week(d)` and `wd(d)` for the day the plan assigns, composed with the detectors, and the composition is the definition of the map. **They confirm that this file assigned the days it meant to assign and they do not test whether the assignment is any good. The twenty calendar rows are able to fail and the six plus six cardinal rows are able to fail; thirty are not, and the column above carries no column for that distinction, which is the same omission that made Volume 18's close rebuild its table.** They are printed because Volume 18's close published that it had assertions it could not fail and hid them, and a pass that hides them is the defect it is measuring.

### 0.3 THE CONTROL: THIRTEEN PUBLISHED ROWS, RUN BEFORE THIS VOLUME'S FIGURES WERE WRITTEN OUT

| What the manuscript prints | What this detector returns | Verdict |
| --- | --- | --- |
| Chapter 881 is the Monday of week 301, day 1993 | week 301, Monday | reproduces |
| Chapter 921 is the Monday of week 312, day 2070 | week 312, Monday | reproduces |
| Chapter 925 is the Sunday of week 312, day 2076 | week 312, Sunday | reproduces |
| Chapter 931 is the Wednesday of week 314, day 2086 | week 314, Wednesday | reproduces |
| Chapter 939 is the Monday of week 316, day 2098 | week 316, Monday | reproduces |
| Chapter 940 is the Wednesday of week 316, day 2100 | week 316, Wednesday | reproduces |
| Chapter 941 is the Monday of week 317, day 2105 | week 317, Monday | reproduces |
| Chapter 957 is the Wednesday of week 320, day 2128 | week 320, Wednesday | reproduces |
| Chapter 971 is the Wednesday of week 324, day 2156 | week 324, Wednesday | reproduces |
| Chapter 989 is the Wednesday of week 328, day 2184 | week 328, Wednesday | reproduces |
| Chapter 991 is the Monday of week 329, day 2189 | week 329, Monday | reproduces |
| Chapter 998 is the Monday of week 331, day 2203 | week 331, Monday | reproduces |
| Chapter 1000 is the Wednesday of week 332, day 2212 | week 332, Wednesday | reproduces |
| **13 of 13** | | **13 reproduce** |

**AND THE SIXTEEN-WEEK IDENTITY, RUN FOR EVERY WEEK THIS VOLUME USES.** `monday_of(W) = 7W − 114` was composed with both detectors for each of weeks three hundred and thirty-three to three hundred and forty-eight and lands inside week _W_ and on a Monday in all sixteen cases. **Sixteen assertions, and all sixteen could not have failed, because the composition is the definition of the map. They are disclosed here in the same table and are not counted in the sixty-two above.** No expected value in this file shares an author with the code that produced it: the day-map rows come from this file's own movement spans and the controls come from printed pages.

---

## 1. THE DAY MAP, ALL SIXTY ROWS

| Movement | Chapter | Day | Week | Weekday | Load-book entry | Governed counter |
| --- | --- | --- | --- | --- | --- | --- |
| I | 1001 | two thousand two hundred and seventeen | 333 | Monday | 1004 | 246 |
| I | 1002 | two thousand two hundred and eighteen | 333 | Tuesday | 1005 | 247 |
| I | 1003 | two thousand two hundred and nineteen | 333 | Wednesday | 1006 | 248 |
| I | 1004 | two thousand two hundred and twenty | 333 | Thursday | 1007 | 249 |
| I | 1005 | two thousand two hundred and twenty-one | 333 | Friday | 1008 | 250 |
| I | 1006 | two thousand two hundred and twenty-three | 333 | Sunday | 1009 | 251 |
| I | 1007 | two thousand two hundred and twenty-four | 334 | Monday | 1010 | 252 |
| I | 1008 | two thousand two hundred and twenty-five | 334 | Tuesday | 1011 | 253 |
| I | 1009 | two thousand two hundred and twenty-seven | 334 | Thursday | 1012 | 254 |
| I | 1010 | two thousand two hundred and twenty-eight | 334 | Friday | 1013 | 255 |
| II | 1011 | two thousand two hundred and thirty-two | 335 | Tuesday | 1014 | 256 |
| II | 1012 | two thousand two hundred and thirty-three | 335 | Wednesday | 1015 | 257 |
| II | 1013 | two thousand two hundred and thirty-five | 335 | Friday | 1016 | 258 |
| II | 1014 | two thousand two hundred and thirty-seven | 335 | Sunday | 1017 | 259 |
| II | 1015 | two thousand two hundred and thirty-eight | 336 | Monday | 1018 | 260 |
| II | 1016 | two thousand two hundred and forty | 336 | Wednesday | 1019 | 261 |
| II | 1017 | two thousand two hundred and forty-two | 336 | Friday | 1020 | 262 |
| II | 1018 | two thousand two hundred and forty-three | 336 | Saturday | 1021 | 263 |
| II | 1019 | two thousand two hundred and forty-five | 337 | Monday | 1022 | 264 |
| II | 1020 | two thousand two hundred and forty-six | 337 | Tuesday | 1023 | 265 |
| III | 1021 | two thousand two hundred and fifty-one | 337 | Sunday | 1024 | 266 |
| III | 1022 | two thousand two hundred and fifty-three | 338 | Tuesday | 1025 | 267 |
| III | 1023 | two thousand two hundred and fifty-four | 338 | Wednesday | 1026 | 268 |
| III | 1024 | two thousand two hundred and fifty-six | 338 | Friday | 1027 | 269 |
| III | 1025 | two thousand two hundred and fifty-seven | 338 | Saturday | 1028 | 270 |
| III | 1026 | two thousand two hundred and fifty-nine | 339 | Monday | 1029 | 271 |
| III | 1027 | two thousand two hundred and sixty-one | 339 | Wednesday | 1030 | 272 |
| III | 1028 | two thousand two hundred and sixty-two | 339 | Thursday | 1031 | 273 |
| III | 1029 | two thousand two hundred and sixty-three | 339 | Friday | 1032 | 274 |
| III | 1030 | two thousand two hundred and sixty-four | 339 | Saturday | 1033 | 275 |
| IV | 1031 | two thousand two hundred and sixty-eight | 340 | Wednesday | 1034 | 276 |
| IV | 1032 | two thousand two hundred and sixty-nine | 340 | Thursday | 1035 | 277 |
| IV | 1033 | two thousand two hundred and seventy-one | 340 | Saturday | 1036 | 278 |
| IV | 1034 | two thousand two hundred and seventy-two | 340 | Sunday | 1037 | 279 |
| IV | 1035 | two thousand two hundred and seventy-four | 341 | Tuesday | 1038 | 280 |
| IV | 1036 | two thousand two hundred and seventy-five | 341 | Wednesday | 1039 | 281 |
| IV | 1037 | two thousand two hundred and seventy-seven | 341 | Friday | 1040 | 282 |
| IV | 1038 | two thousand two hundred and seventy-eight | 341 | Saturday | 1041 | 283 |
| IV | 1039 | two thousand two hundred and eighty | 342 | Monday | 1042 | 284 |
| IV | 1040 | two thousand two hundred and eighty-one | 342 | Tuesday | 1043 | 285 |
| V | 1041 | two thousand two hundred and eighty-five | 342 | Saturday | 1044 | 286 |
| V | 1042 | two thousand two hundred and eighty-six | 342 | Sunday | 1045 | 287 |
| V | 1043 | two thousand two hundred and eighty-eight | 343 | Tuesday | 1046 | 288 |
| V | 1044 | two thousand two hundred and eighty-nine | 343 | Wednesday | 1047 | 289 |
| V | 1045 | two thousand two hundred and ninety-one | 343 | Friday | 1048 | 290 |
| V | 1046 | two thousand two hundred and ninety-two | 343 | Saturday | 1049 | 291 |
| V | 1047 | two thousand two hundred and ninety-four | 344 | Monday | 1050 | 292 |
| V | 1048 | two thousand two hundred and ninety-six | 344 | Wednesday | 1051 | 293 |
| V | 1049 | two thousand two hundred and ninety-seven | 344 | Thursday | 1052 | 294 |
| V | 1050 | two thousand two hundred and ninety-eight | 344 | Friday | 1053 | 295 |
| VI | 1051 | two thousand three hundred and one | 345 | Monday | 1054 | 296 |
| VI | 1052 | two thousand three hundred and three | 345 | Wednesday | 1055 | 297 |
| VI | 1053 | two thousand three hundred and five | 345 | Friday | 1056 | 298 |
| VI | 1054 | two thousand three hundred and seven | 345 | Sunday | 1057 | 299 |
| VI | 1055 | two thousand three hundred and ten | 346 | Wednesday | 1058 | 300 |
| VI | 1056 | two thousand three hundred and thirteen | 346 | Saturday | 1059 | 301 |
| VI | 1057 | two thousand three hundred and sixteen | 347 | Tuesday | 1060 | 302 |
| VI | 1058 | two thousand three hundred and nineteen | 347 | Friday | 1061 | 303 |
| VI | 1059 | two thousand three hundred and twenty-two | 348 | Monday | 1062 | 304 |
| VI | 1060 | two thousand three hundred and twenty-four | 348 | Wednesday | 1063 | 305 |

**ALL SIXTY ROWS OF THE TABLE ABOVE WERE RE-DERIVED AGAINST §0.1 BEFORE IT WAS WRITTEN OUT IN WORDS, AND NOT READ OFF A HEADING.** `(entry − chapter) = {3}` and `(counter − chapter) = {−755}` on all sixty. Chapters per week: 333 six, 334 four, 335 four, 336 four, 337 three, 338 four, 339 five, 340 four, 341 four, 342 four, 343 four, 344 four, 345 four, 346 two, 347 two, 348 two, **and 6 + 4 + 4 + 4 + 3 + 4 + 5 + 4 + 4 + 4 + 4 + 4 + 4 + 2 + 2 + 2 = 60.**

### 1.1 THE SIX MOVEMENT SPANS AND THE DAYS INSIDE THEM THAT CARRY NO CHAPTER

| Movement | Span | Days in the span | Chapters | Days with no chapter |
| --- | --- | --- | --- | --- |
| I | 2217–2228 | 12 | 10 | twenty-two, twenty-six |
| II | 2232–2246 | 15 | 10 | thirty-four, thirty-six, thirty-nine, forty-one, forty-four |
| III | 2251–2265 | 15 | 10 | fifty-two, fifty-five, fifty-eight, sixty, sixty-five |
| IV | 2268–2281 | 14 | 10 | seventy, seventy-three, seventy-six, seventy-nine |
| V | 2285–2298 | 14 | 10 | eighty-seven, ninety, ninety-three, ninety-five |
| VI | 2301–2324 | 24 | 10 | fourteen in the span |
| **All six** | — | **94** | **60** | **34** |

**AND THE FOURTEEN CLEAR DAYS BETWEEN THE MOVEMENTS.** Three after Movement I — 2229, 2230, 2231. Four after II — 2247, 2248, 2249, 2250. Two after III — 2266, 2267. Three after IV — 2282, 2283, 2284. Two after V — 2299, 2300. **Five runs, three, four, two, three and two, summing to fourteen. No chapter of this volume carries any of them and A COLLISION IS A COINCIDENCE BETWEEN TWO INTEGERS AND NO CHAPTER MAY TREAT ONE AS A REHEARSAL FOR ANYTHING.**

**THE CHECK, PRINTED BECAUSE VOLUME 19'S CLOSE FOUND TWO WRONG FIGURES IN THE SAME PLACE BY RUNNING IT:** `12 + 15 + 15 + 14 + 14 + 24 = 94`, `34 + 14 = 48`, `48 + 60 = 108`, and `2324 − 2217 = 107` as a difference and `2324 − 2217 + 1 = 108` as a count. **All four stand at once. The governed counter runs 246 to 305 and is a chapter-indexed row count and not the calendar span, and the two are never added.**

**AND THESE ARE NOT VOLUME 19'S FIGURES.** Volume 19's six inclusive spans were eleven, sixteen, fourteen, thirteen, thirteen and twenty-four and summed to ninety-one, its chapterless days inside them were thirty-one and its clear days between the movements were seventeen. **None of the six numbers was copied and none of them is inherited, and the different shape is a decision and is set out at `outline/volume-20.md` deviation 5.**

### 1.2 THE SIX SUNDAYS, AND THEY ARE ONE IN EACH MOVEMENT

**`wd = (day − 502) mod 7` returns Sunday on Chapter 1006 at day 2223, Chapter 1014 at day 2237, Chapter 1021 at day 2251, Chapter 1034 at day 2272, Chapter 1042 at day 2286 and Chapter 1054 at day 2307, and on no other of the sixty.** All six are in the table above with the weekday printed beside them. **The shutter takes the about-two form on those six days and the about-ten form on the other fifty-four, and guardrail six of the volume outline is written to that and not to Volume 19's seven.** Volume 19's seventh day on the about-two form was a Saturday and is recorded at `workspace/volume-19/close/CLOSE.md` §1.4 as a defect of guardrail six and not repaired; **this volume's map has no such day and a pass that finds one has found a seventh and should record it rather than absorb it.**

---

## 2. THE SIXTEEN STANDING ANCHORS AND THEIR ORIGINS

**Every origin below is derived from a figure printed in `workspace/volume-19/batch-0006/chapter-1000.md`, at day 2212, so that each anchor is continuous with the last volume rather than restarted.** The origin is the day on which the count was zero, and it is never printed on a page. **The derivation was checked against that chapter's own docket: at day 2212 the first of these reads one thousand eight hundred and fifty days, and `2212 − 362 = 1850`.**

| Anchor, as the pages name it | Origin | At Chapter 1001 | At Chapter 1060 |
| --- | --- | --- | --- |
| Four units standing off that service road, one of them carrying heat | 362 | one thousand eight hundred and fifty-five days, two hundred and sixty-five weeks to the day | one thousand nine hundred and sixty-two days, two hundred and eighty weeks and two days |
| The one card in that rail, once creased across its middle | 358 | one thousand eight hundred and fifty-nine days, two hundred and sixty-five weeks and four days | one thousand nine hundred and sixty-six days, two hundred and eighty weeks and six days |
| The twelfth of nineteen ruled lines on that board up on two nails | 442 | one thousand seven hundred and seventy-five days, two hundred and fifty-three weeks and four days | one thousand eight hundred and eighty-two days, two hundred and sixty-eight weeks and six days |
| The thirteenth of those lines, ruled under the twelfth and blank | 491 | one thousand seven hundred and twenty-six days, two hundred and forty-six weeks and four days | one thousand eight hundred and thirty-three days, two hundred and sixty-one weeks and six days |
| The fourteenth of that board, ruled below the thirteenth, blank | 526 | one thousand six hundred and ninety-one days, two hundred and forty-one weeks and four days | one thousand seven hundred and ninety-eight days, two hundred and fifty-six weeks and six days |
| The fifteenth of that board, low among the nineteen | 547 | one thousand six hundred and seventy days, two hundred and thirty-eight weeks and four days | one thousand seven hundred and seventy-seven days, two hundred and fifty-three weeks and six days |
| The sixteenth of those lines, never once written on | 572 | one thousand six hundred and forty-five days, two hundred and thirty-five weeks to the day | one thousand seven hundred and fifty-two days, two hundred and fifty weeks and two days |
| The seventeenth of the nineteen, standing under the sixteenth | 590 | one thousand six hundred and twenty-seven days, two hundred and thirty-two weeks and three days | one thousand seven hundred and thirty-four days, two hundred and forty-seven weeks and five days |
| The eighteenth of that board, second up from its foot | 644 | one thousand five hundred and seventy-three days, two hundred and twenty-four weeks and five days | one thousand six hundred and eighty days, two hundred and forty weeks to the day |
| The nineteenth and last ruled line on that board | 666 | one thousand five hundred and fifty-one days, two hundred and twenty-one weeks and four days | one thousand six hundred and fifty-eight days, two hundred and thirty-six weeks and six days |
| That space on the sheet marked for a date, which stood empty for all of the above | 672 | one thousand five hundred and forty-five days, two hundred and twenty weeks and five days | one thousand six hundred and fifty-two days, two hundred and thirty-six weeks to the day |
| The hold across nine crates and the floor beneath every one of them | 729 | one thousand four hundred and eighty-eight days, two hundred and twelve weeks and four days | one thousand five hundred and ninety-five days, two hundred and twenty-seven weeks and six days |
| The man of about fifty-one, unmoved from that north wall | 756 | one thousand four hundred and sixty-one days, two hundred and eight weeks and five days | one thousand five hundred and sixty-eight days, two hundred and twenty-four weeks to the day |
| Nine copies of the front of one page, each of them torn at a corner | 796 | one thousand four hundred and twenty-one days, two hundred and three weeks to the day | one thousand five hundred and twenty-eight days, two hundred and eighteen weeks and two days |
| The post at the far end of that corridor, its face worn halfway up | 814 | one thousand four hundred and three days, two hundred weeks and three days | one thousand five hundred and ten days, two hundred and fifteen weeks and five days |
| One written line written inside that box off that road | 982 | one thousand two hundred and thirty-five days, one hundred and seventy-six weeks and three days | one thousand three hundred and forty-two days, one hundred and ninety-one weeks and five days |

**AND FOUR CELLS OF THAT TABLE WERE WRONG ON THE FIRST WRITE AND ALL FOUR HAVE BEEN CORRECTED IN PLACE, AND NO ORIGIN WAS TOUCHED.** The first printing gave the one card in that rail at Chapter 1060 as *two hundred and eighty weeks and one day*, the hold across nine crates as *two hundred and twenty-seven weeks and one day*, the nine copies torn at a corner as *two hundred and eighteen weeks and four days*, and **the post at the corridor end at Chapter 1001 as *two hundred and weeks and three days*, which is not a rendering of anything.** The three week-remainders are each out by five days, four days and two days and the fourth is missing its quotient. **The cause was four hand-typed cells and not the renderer, because every cell was re-derived against `divmod` after the table was written and the renderer was run on the same sixteen origins twice and agreed with itself and with the corrected table.** **This is recorded here because it is the fourth recorded instance in this repository of a day-map or anchor cell disagreeing with the instrument and repaired in the same pass that wrote it, and because the first three are at `workspace/volume-18/ARITHMETIC-AND-CALENDAR.md` §9.3, at `workspace/volume-19/ARITHMETIC-AND-CALENDAR.md` §1.1 and at `workspace/volume-19/close/CLOSE.md` §10, and a pass that does not re-derive a table after writing it will find the class again.** No day, week, entry, counter or origin moved, and the day-count column was right on all sixteen rows on the first write.

**THE PLACE BEHIND THE WOMAN'S CHAIR carries origin 1484** and is named on one file of each movement and prints a figure on Chapter 1003 alone. **THE ORIGIN IS PRINTED HERE AND THE FIGURE IS NOT, AND NEITHER IS ANY DAY-COUNT FOR IT AT ANY POINT IN THIS FILE, because the origin plus the day is the figure and a plan that prints the figure is a plan a later pass can lift.** A pass that needs the interval derives it from the origin and the chapter's own day at §1. **One location is given because the plan's guardrail depends on it and not because the number is wanted: the interval reads to the day on Chapter 1003, and it comes to a round whole number of weeks on Chapter 1023, which is a Wednesday inside Movement III's span and which therefore carries a chapter. Neither the day nor the interval is printed here and both are derivable in one subtraction.** **THE FIRST PRINTING OF THIS PARAGRAPH PLACED THAT ROUND FIGURE INSIDE MOVEMENT II ON A DAY THAT CARRIES NO CHAPTER, AND THAT WAS WRONG: the round figure falls on day 2254, which is Chapter 1023 and not a chapterless day. It was found by re-deriving both days against §1 after this file was written, and it is corrected here and in the two files that repeat it. THE CONSEQUENCE IS A BETTER TRAP THAN THE ONE IT REPLACES, BECAUSE CHAPTER 1023 IS A PAGE THAT CARRIES A CHAPTER AND IS EXACTLY WHERE A WRITER WOULD PRINT A FIGURE.**

### 2.1 THE THREE SHORT-RUN ANCHORS THAT CARRY VOLUME 20, AND NONE OF THEM IS VOLUME 19'S

**A sheet carrying a door and no list, low on a passage wall in a fourth district, by two drawing pins: origin 2189.** It went up on the Monday of week 329 and it is **twenty-eight days old at Chapter 1001** and **one hundred and thirty-five days old at Chapter 1060.** It is the fastest of the three and it is stopped during Movement I and does not go back up.

**A second hundred and fifty of those sheets, printed by a building in a second district: origin 2203.** It was printed on the Monday of week 331 and it is **fourteen days old at Chapter 1001** and **one hundred and twenty-one days old at Chapter 1060.** **The second hundred and fifty is not the same object as the first and the two figures are never added.**

**A thing said at a counter in a first district and carried by about four people afterwards: origin 2212.** **The origin is the day the Volume 19 close printed it as a fact and not the day it was said, and the day it was said is printed nowhere.** It is **five days old at Chapter 1001** and **one hundred and twelve days old at Chapter 1060.** It is the fastest thing in this volume and **it is the only one of the three that gets worse while it gets older, and no page may remark on that.**

---

## 3. THE FOUR SITTINGS, AND WHAT IS FORBIDDEN ABOUT THEM

| Sitting | Week | Day | Chapter | Movement | The book |
| --- | --- | --- | --- | --- | --- |
| seventy-third | 336 | two thousand two hundred and forty | 1016 | II | opens |
| seventy-fourth | 340 | two thousand two hundred and sixty-eight | 1031 | IV | shuts |
| seventy-fifth | 344 | two thousand two hundred and ninety-six | 1048 | V | opens |
| seventy-sixth | 348 | two thousand three hundred and twenty-four | 1060 | VI | shuts |

**ALL FOUR ARE THE WEDNESDAYS OF WEEKS 336, 340, 344 AND 348 ON FOUR-WEEK SPACING, AT TWENTY-EIGHT DAYS' INTERVAL, AND `week` AND `wd` RETURN WEDNESDAY ON ALL FOUR INDEPENDENTLY OF ANY FILE.** Chapter 1001 is not a sitting, no chapter of Movement I is a sitting, and no number is said out loud in any room on any of Movement I's ten days.

**AND THE PATTERN IS OPEN, SHUT, OPEN, SHUT, which is not Volume 19's shut, open, shut, open and is not Volume 15's and is not Volume 16's and is not Volume 17's and is not Volume 18's. It is not a rule and it is not evidence and no page may describe it as a change in the woman who holds that room.**

**NO EXCHANGE FIGURE IS PRINTED IN THIS FILE.** The book and the tin are at their Volume 19 closing figures on the first day of this volume. **The difference between the book and the tin is not printed here in one sentence or in any sentence, and neither is the difference between any two of these four sittings' figures, and a later pass that needs either must go to the volume close and not to this file.**

---

## 4. THE FIGURES THIS FILE DELIBERATELY DOES NOT CARRY

1. **The woman's page is `day − 1573`. IT IS NOT PRINTED HERE AND NO CHAPTER OF THIS VOLUME PRINTS IT, AND NO RANGE OF IT IS PRINTED HERE EITHER — not the value at Chapter 1001, not the value at Chapter 1060 and not the width between them.** A plan that prints the span of a forbidden figure has published the figure to nobody's benefit and to a later pass's complete. A pass that needs a value derives it from the origin and the chapter's own day at §1, and the reason the house forbids printing it is not arithmetic and is stated at §6.
2. **The four arrival cells are printed empty, and they are printed empty because a cell that cannot be measured is printed empty and is not approximated.**
3. **The register of correct acts that changed nothing stands at four and is not counted here and no fifth is written.**
4. **No two of the nine hand copies are compared in this file.**
5. **The difference between the book and the tin, and between any two of the four Exchange figures, is not printed in this file.**
6. **The heading of the fifth column is not printed in this file and is not proposed in it.** It is owner item 4, it is unruled, and the volume outline proposes three headings on pages and refuses all three, which is not the same thing as setting one and is not a settlement.

---

## 5. WHAT A LATER PASS NEEDS FROM THIS FILE, IN EIGHT LINES

1. **Chapter 1001 is the Monday of week 333, day 2217, entry 1004, governed counter 246. Chapter 1060 is the Wednesday of week 348, day 2324, entry 1063, counter 305.**
2. **Movement I's ten days are 2217, 2218, 2219, 2220, 2221, 2223, 2224, 2225, 2227 and 2228, and days 2222 and 2226 carry no chapter.**
3. **The one Sunday of Movement I is Chapter 1006, day 2223, and the shutter comes down at about two on it and at about ten on the other nine.**
4. **The sheets come off that passage wall during Movement I and do not go back up, and the second hundred and fifty is never printed, and the third hundred is never printed.**
5. **The three questions are on a card about the size of a hand and the card is not a form and has no column and no heading.**
6. **The first sitting is Chapter 1016 at day 2240 and the book opens there. No sitting falls in Movement I and no number is said out loud anywhere in this city on any of its ten days.**
7. **The place behind the woman's chair carries its printed figure on Chapter 1003 alone, and no other file of this volume carries one, and it comes to a round whole number of weeks on Chapter 1023.** The interval is not printed in this file and a pass that needs it subtracts the origin from the day.
8. **The last page carries `outline/ending.md` line 160 and Chapter 759 is not reversed by it and the difference between them is who asks and where.**

---

## 6. WHAT A VOLUME 20 CLOSE OWES AND WHAT IT MAY NOT SPEND

**OWED: section 9, headed *Written by the volume close, and by nobody before it*, and a `close/CLOSE.md` beside it, and both of them at volume scope rather than at movement scope, because six movement summaries that each publish a figure true of ten files have cost this repository four wrong columns already.** The close is not a movement and is not a batch and writes no chapter, and a prompt that asks a close for ten chapters has asked it for the wrong thing — that is recorded at `workspace/volume-19/ARITHMETIC-AND-CALENDAR.md` §6 and it happened three times in this repository.

**MAY NOT BE SPENT: the woman's page; the four arrival cells; the fifth of the register; any Exchange figure; any comparison of two of the nine hand copies; the fifth column's heading; the plan's phrase on Chapter 933; the ombud's office as used on him in Volume 18; and the question whether Chapter 760, or Chapter 1000, or Chapter 1060 is this manuscript's ending, which is the owner's.**

**AND WHAT THE VOLUME 19 CLOSE OWED AND DID NOT DO, RESTATED HERE AS AN INHERITED INSTRUCTION AND NOT AS A SETTLEMENT, BECAUSE THIS FILE IS WHAT THE VOLUME 20 CLOSE WILL READ.** Four things. *One:* guardrail three must be measured at sixty files and must not sum five movement summaries, **and the sixty-file figure must be published beside the fifty-file figure from Volume 19 rather than beside nothing.** *Two:* the `about` table must be re-derived at sixty files under all three case conventions and published with its scope. *Three:* the duplication apparatus must print both paragraph rules and both counting conventions beside every cell. *Four:* the standing anchors table must be declared a scope of its own, **because at present it is invisible to both measures and it is the longest block on every page in every volume from Volume 15 onward.** **All four are instructions to the close and none of them is a figure, and none of the four may be treated as settled because Volume 19 asked for it too.**

**AND THREE THINGS THE VOLUME 19 CLOSE COULD NOT REPAIR, WHICH ARE STILL UNREPAIRED AND WHICH THE VOLUME 20 CLOSE MUST MEASURE AND NOT INHERIT.** *One:* `workspace/volume-19/batch-0005/chapter-0989.md:186` carries a tag that remarks on the pattern guardrail ten forbids any page to remark on, and it is the only such tag left on those sixty pages. *Two:* eight prose keys are shared across Volume 19's sixty files at the last-twelve-token measure, six of them standing on a Movement V page, named at `workspace/volume-19/close/CLOSE.md` §4. *Three:* four files carry predicative adjective uses of a word guardrail nine forbids. **None of the three is a fact a later pass may inherit as one, and repairing any of them moves a word count and therefore a denominator, so a repair pass must re-derive Volume 19's published table before it touches a page.**

---

## 7. AN EXERCISE A PASS MAY DO AND MAY NOT USE AS A FIGURE

**The counts below are re-derivable from section 1 and section 2 at the boundaries printed in section 0.1, and a later pass may check any of them. A later pass may not quote one of them as a house figure, because this file is a plan and not a measure of record.**

| What | Value |
| --- | --- |
| Days in Movement I's span | 12 |
| Chapters in Movement I | 10 |
| Days in Movement I's span with no chapter | 2 |
| Exact weeks to the day on Movement I's Monday, for the four units off that service road | 265 |
| Exact weeks to the day on Chapter 1007, for the four units off that service road | 266 |
| Exact weeks to the day on Movement I's Monday, for the sixteenth of those lines | 235 |
| Exact weeks to the day on Movement I's Wednesday, for the ninth copies torn at a corner | 203 |
| Sundays among Movement I's ten days | 1 |
| Sittings among Movement I's ten days | 0 |
| Anchor figures in the docket of every one of these ten files | 16 of the 16, on all ten |
| Anchor figures in the prose of Chapters 1001 to 1010 | a decision for the writer and not for this file. **What this file will say is that the count differs between files and that a pass writing them must not make it uniform, because Volume 19's Movement I ran three, two, two, two, two, two, two, two, two, one and the uniformity of a docket is not the uniformity of a page** |
| The one anchor figure in this movement's prose that reads to the day on a file other than 1003 | none in this file's scope. 1001, 1003 and 1007 carry exact-week rows and only 1003 may carry one of the place behind the chair |
| The place behind the woman's chair | printed on Chapter 1003 and on no other file of this movement |

**AND ONE FIGURE IS LEFT EMPTY ON PURPOSE. The place behind the woman's chair on Chapter 1003 is printed on that page in the page's own words and in this file its figure is given at §2 only as a pair of day counts and never as the rendered string, because the origin is printed in section 2 and the origin plus the day is the figure and a plan that prints the rendered string is a plan a later pass can lift.**

---

## 8. THE STANDING RECORD FOR THIS VOLUME, WHICH IS NOT THE PLAN AND IS NOT A FIGURE

**Volume 19 is closed at Chapter 1000 and nothing in this file reverses, softens, retcons or improves on one word of it. Chapter 759 is closed inside Volume 15 and nothing in this file reverses, softens, retcons or improves on one word of that either, and the woman of about forty-four with the keys is not corrected and is not thanked and is not written down.** Iona Sorn is the last enemy in this manuscript and is in public custody and is unanswered and is not absolved. The ninth chair does not move and its mover is named nowhere. The room under the building in a first district is dark. The answer to Volume 08's question is a chair he does not sit in. **The dated rule stands and the records behind it stay public and stay disputed.**

**AND WHAT THE VOLUME 19 CLOSE DID AND DID NOT SET DOWN, STATED HERE AS A FACT ABOUT THAT FILE AND NOT AS A FIGURE.** That close printed the woman's page as `day − 1573`, printed that it governs, and printed that its figure is on none of its sixty files and in neither file it wrote. **It did not set down a value for it at Chapter 1000 and neither does this file.** That close printed the place behind a chair as named on twenty-four of its sixty files and printed no interval for it at Chapter 1000, **and this file does not print one either.** The two facts — a close that declines to print a value, and a plan that declines to print a value — are not the same fact and are not offered as one. **The place behind the chair reached a round whole-week interval at some point before the Volume 19 close and the close said nothing about it and this file does not either.**

---

## 9. OWED TO THE VOLUME 20 CLOSE AND WRITTEN BY NOBODY BEFORE IT

**This section is empty because it is not this file's to fill.** The Volume 20 close writes section 9 and `workspace/volume-20/close/CLOSE.md`, both at volume scope, and both after Chapter 1060, and both are measured rather than inherited. **A pass that fills this section before Chapter 1060 has written a close that has not happened.** Section 9 will carry, at minimum, the word table for all sixty files, the `about` rates under all three case conventions with the denominator beside every row, guardrail three as the plan writes it under both terminator conventions, the duplication measure with both paragraph rules and both counting conventions in the same place as every cell, the standing anchors table as a named scope of its own, and the sixty-row day map re-derived rather than read from section 1.