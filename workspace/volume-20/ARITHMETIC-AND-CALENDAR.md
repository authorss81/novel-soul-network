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

## 9. WRITTEN BY THE VOLUME CLOSE, AND BY NOBODY BEFORE IT

**This section was empty until Chapter 1060 existed, and it is written now, after it, at sixty-file scope, measured and not inherited.** Chapter 1060 exists on disk, ends `END OF VOLUME 20`, and carries the plan of record's final image. No chapter of this volume or any earlier volume was edited by this pass. Every number below was derived from the sixty chapter files at `batch-0001/` through `batch-0006/` by the instrument at §9.0, and none was carried forward from any movement summary or any earlier close. Where a published ten-file figure disagrees with this instrument, both are printed and the verdict is printed beside them, including the ones that do not reproduce.

### 9.0 THE BOUNDARY, BUILT BEFORE ANY CELL WAS FILLED

**The boundary is `batch-0006/SUMMARY.md` §0, unchanged from `batch-0005/SUMMARY.md` §0: tokeniser `[A-Za-z0-9]+(?:-[A-Za-z0-9]+)*`, H1 line removed, `*`, `` ` `` and `|` deleted before segmentation, hyphenated compound one token, clock time two tokens; body scope to the standalone load-book marker `^\*\d+\.$`, apparatus scope from that marker to end of file, the marker line one token belonging to apparatus, the two scopes disjoint and summing to the whole file minus the H1 line.** Sentence: a maximal token run whose final token is followed by `.`, `!` or `?`, itself followed by whitespace or end of scope after skipping any closing quotation marks, which is the `quote-skipping` reading `workspace/volume-19/close/CLOSE.md` §17 names; a semicolon and a colon are not terminators. Paragraph rules, both run: breaks KEPT, each non-empty line a block; breaks DROPPED, every run of newlines replaced by a single space. Counting conventions, all three run in every cell: strict counts every qualifying sentence; quotation-state discards a segment lying wholly inside a double-quoted run, state tracked block by block; any-quote discards every segment carrying a double quote in its printed span including its bounding marks. Week `(day − 502) // 7 + 88`, weekday `(day − 502) mod 7` Monday-first, Monday of week _W_ `7 × W − 114`. Cardinal in the house form (§2 of `batch-0006/SUMMARY.md`: the `and` dropped between thousand and hundred, kept between hundred and remainder). Weeks rendering `N weeks to the day` / `N weeks and one day` / `N weeks and M days`. **The instrument raises rather than returning a zero it cannot justify: no marker, no sixteen-row docket, or a rendered figure disagreeing with its own page stops it. It raised nothing on these sixty files.**

**Two properties of this instrument are published because they move cells and a later pass must not mistake them for faults.** *One:* at a floor of twelve tokens, no surviving sentence straddles a quotation boundary, so the any-quote rows equal the quotation-state rows in every prose cell; the apparatus carries almost no double-quoted run, so all three conventions are equal there too. *Two:* closing-quotation transparency is what makes priced dialogue countable at all; a literal splitter blind to `."` returns zeroes about nothing, which is the receipt-not-a-result lesson `batch-0001/SUMMARY.md` §17 records.

### 9.0.1 THE CONTROL, RUN BEFORE ANY CELL WAS FILLED, AT TEN FILES AND AT SIXTY

| Control | Where | Expected | This instrument | Verdict |
| --- | --- | --- | --- | --- |
| Movement IV word table | `batch-0004/SUMMARY.md` | 13,406 / 11,197 / 24,603 | 13,406 / 11,197 / 24,603 | **reproduces to the digit** |
| Movement V lead-ins | `batch-0005/SUMMARY.md` §4 | 51, 44, 54, 50, 53, 48, 54, 61, 72, 52 | 51, 44, 54, 50, 53, 48, 54, 61, 72, 52 | **reproduces, ten of ten** |
| Movement V day rows | `batch-0005/SUMMARY.md` §3 | 10 of 10 | 10 of 10, days read back out of first anchor rows | **reproduces** |
| Movement V anchor dockets | `batch-0005/chapter-1041.md`, `-1050.md` | 16 of 16 each | 16 of 16 each | **reproduces** |
| Movement V word table, apparatus column | `batch-0005/SUMMARY.md` §4 | 11,597 published | 11,757, exactly sixteen higher on each of the ten files; body column reproduces to the digit on all ten | **does not reproduce; SETTLED at §9.2: the published column is one hundred and sixty low against the stated boundary, the numerator is not in doubt, and the sixty-file denominator uses the stated boundary throughout** |
| Movement VI word table and lead-ins | `batch-0006/SUMMARY.md` §4–5 | 15,112 / 12,193 / 27,305; 55, 56, 54, 47, 59, 54, 74, 59, 51, 58 | 15,124 / 12,223 / 27,347; 61, 48, 53, 50, 42, 54, 74, 59, 51, 58; exact on Chapters 1056–1060, drifting on 1051–1055 only | **new finding, recorded at §9.2; the sixty-file figure is measured from disk text** |
| `screen` stem, every chapter file on disk | `batch-0003/SUMMARY.md` §14.8 | twenty hits on fourteen files across Volumes 02, 03, 04, 05, 07 and 12 | twenty hits on fourteen files, the same fourteen, across Volumes 02, 03, 04, 05, 07 and 12 | **reproduces to the digit** |
| Sixteen origins and three short-run origins | §2 and §2.1 | Chapter 1001 and Chapter 1060 columns | 960 of 960 rows render, 960 self-consistent, 960 agreeing with their own page; short-run ages read back at §9.6 | **reproduces** |
| Movement II / III word tables | `batch-0002/§14`, `batch-0003/§4` | 19,239 / 10,569 / 29,808 and 15,317 / 11,031 / 26,348 | 19,241 / 10,569 / 29,810 and 15,334 / 11,031 / 26,365 | **body two and seventeen high respectively; the recorded stale tables at `batch-0004/SUMMARY.md` §2.3, confirmed and carried into §9.2** |

### 9.1 THE SIXTY-ROW DAY MAP, RE-DERIVED AND NOT READ FROM §1

**Each day below was read back out of its own page, by inverting the first anchor row (`day = printed figure + 362`), and composed with the two detectors; entry is `chapter + 3`, counter `chapter − 755`. All sixty read-back days agree with §1, all sixty weeks and weekdays agree with the detectors, `(entry − chapter) = {3}` and `(counter − chapter) = {−755}` on all sixty. The plan's table stands beside this one as a comparison and was not its source; the re-derivation exists because §2's round-figure paragraph once assigned a round interval to a chapterless day and was corrected to Chapter 1023 in place.**

| Chapter | Day | Week | Weekday | Entry | Counter |
| --- | --- | --- | --- | --- | --- |
| 1001 | 2217 | 333 | Monday | 1004 | 246 |
| 1002 | 2218 | 333 | Tuesday | 1005 | 247 |
| 1003 | 2219 | 333 | Wednesday | 1006 | 248 |
| 1004 | 2220 | 333 | Thursday | 1007 | 249 |
| 1005 | 2221 | 333 | Friday | 1008 | 250 |
| 1006 | 2223 | 333 | Sunday | 1009 | 251 |
| 1007 | 2224 | 334 | Monday | 1010 | 252 |
| 1008 | 2225 | 334 | Tuesday | 1011 | 253 |
| 1009 | 2227 | 334 | Thursday | 1012 | 254 |
| 1010 | 2228 | 334 | Friday | 1013 | 255 |
| 1011 | 2232 | 335 | Tuesday | 1014 | 256 |
| 1012 | 2233 | 335 | Wednesday | 1015 | 257 |
| 1013 | 2235 | 335 | Friday | 1016 | 258 |
| 1014 | 2237 | 335 | Sunday | 1017 | 259 |
| 1015 | 2238 | 336 | Monday | 1018 | 260 |
| 1016 | 2240 | 336 | Wednesday | 1019 | 261 |
| 1017 | 2242 | 336 | Friday | 1020 | 262 |
| 1018 | 2243 | 336 | Saturday | 1021 | 263 |
| 1019 | 2245 | 337 | Monday | 1022 | 264 |
| 1020 | 2246 | 337 | Tuesday | 1023 | 265 |
| 1021 | 2251 | 337 | Sunday | 1024 | 266 |
| 1022 | 2253 | 338 | Tuesday | 1025 | 267 |
| 1023 | 2254 | 338 | Wednesday | 1026 | 268 |
| 1024 | 2256 | 338 | Friday | 1027 | 269 |
| 1025 | 2257 | 338 | Saturday | 1028 | 270 |
| 1026 | 2259 | 339 | Monday | 1029 | 271 |
| 1027 | 2261 | 339 | Wednesday | 1030 | 272 |
| 1028 | 2262 | 339 | Thursday | 1031 | 273 |
| 1029 | 2263 | 339 | Friday | 1032 | 274 |
| 1030 | 2264 | 339 | Saturday | 1033 | 275 |
| 1031 | 2268 | 340 | Wednesday | 1034 | 276 |
| 1032 | 2269 | 340 | Thursday | 1035 | 277 |
| 1033 | 2271 | 340 | Saturday | 1036 | 278 |
| 1034 | 2272 | 340 | Sunday | 1037 | 279 |
| 1035 | 2274 | 341 | Tuesday | 1038 | 280 |
| 1036 | 2275 | 341 | Wednesday | 1039 | 281 |
| 1037 | 2277 | 341 | Friday | 1040 | 282 |
| 1038 | 2278 | 341 | Saturday | 1041 | 283 |
| 1039 | 2280 | 342 | Monday | 1042 | 284 |
| 1040 | 2281 | 342 | Tuesday | 1043 | 285 |
| 1041 | 2285 | 342 | Saturday | 1044 | 286 |
| 1042 | 2286 | 342 | Sunday | 1045 | 287 |
| 1043 | 2288 | 343 | Tuesday | 1046 | 288 |
| 1044 | 2289 | 343 | Wednesday | 1047 | 289 |
| 1045 | 2291 | 343 | Friday | 1048 | 290 |
| 1046 | 2292 | 343 | Saturday | 1049 | 291 |
| 1047 | 2294 | 344 | Monday | 1050 | 292 |
| 1048 | 2296 | 344 | Wednesday | 1051 | 293 |
| 1049 | 2297 | 344 | Thursday | 1052 | 294 |
| 1050 | 2298 | 344 | Friday | 1053 | 295 |
| 1051 | 2301 | 345 | Monday | 1054 | 296 |
| 1052 | 2303 | 345 | Wednesday | 1055 | 297 |
| 1053 | 2305 | 345 | Friday | 1056 | 298 |
| 1054 | 2307 | 345 | Sunday | 1057 | 299 |
| 1055 | 2310 | 346 | Wednesday | 1058 | 300 |
| 1056 | 2313 | 346 | Saturday | 1059 | 301 |
| 1057 | 2316 | 347 | Tuesday | 1060 | 302 |
| 1058 | 2319 | 347 | Friday | 1061 | 303 |
| 1059 | 2322 | 348 | Monday | 1062 | 304 |
| 1060 | 2324 | 348 | Wednesday | 1063 | 305 |

**Chapters per week: 333 six, 334 four, 335 four, 336 four, 337 three, 338 four, 339 five, 340 four, 341 four, 342 four, 343 four, 344 four, 345 four, 346 two, 347 two, 348 two; 6 + 4 + 4 + 4 + 3 + 4 + 5 + 4 + 4 + 4 + 4 + 4 + 4 + 2 + 2 + 2 = 60.** Six inclusive spans 12, 15, 15, 14, 14 and 24 sum to 94; thirty-four chapterless days inside them; fourteen clear days between the movements (three, four, two, three, two); 34 + 14 = 48, 48 + 60 = 108, and 2324 − 2217 = 107 as a difference. **The six Sundays are Chapters 1006, 1014, 1021, 1034, 1042 and 1054, one per movement, and the detector returns Sunday on those six and on no other of the sixty.**

### 9.2 THE WORD TABLE FOR ALL SIXTY FILES, WITH A SUM TEST ON EVERY ROW

| Chapter | Body | Apparatus | Whole | Sums |
| --- | --- | --- | --- | --- |
| 1001 | 1706 | 1051 | 2757 | yes |
| 1002 | 1347 | 1022 | 2369 | yes |
| 1003 | 1479 | 1040 | 2519 | yes |
| 1004 | 1309 | 1008 | 2317 | yes |
| 1005 | 1285 | 1024 | 2309 | yes |
| 1006 | 1132 | 1080 | 2212 | yes |
| 1007 | 1361 | 997 | 2358 | yes |
| 1008 | 1301 | 997 | 2298 | yes |
| 1009 | 1749 | 1055 | 2804 | yes |
| 1010 | 1331 | 1044 | 2375 | yes |
| 1011 | 2390 | 1024 | 3414 | yes |
| 1012 | 2424 | 1035 | 3459 | yes |
| 1013 | 2228 | 1069 | 3297 | yes |
| 1014 | 1541 | 1061 | 2602 | yes |
| 1015 | 1785 | 1060 | 2845 | yes |
| 1016 | 1574 | 1091 | 2665 | yes |
| 1017 | 1969 | 1034 | 3003 | yes |
| 1018 | 1234 | 1044 | 2278 | yes |
| 1019 | 2232 | 1068 | 3300 | yes |
| 1020 | 1864 | 1083 | 2947 | yes |
| 1021 | 1789 | 1144 | 2933 | yes |
| 1022 | 1554 | 1109 | 2663 | yes |
| 1023 | 1729 | 1087 | 2816 | yes |
| 1024 | 1505 | 1077 | 2582 | yes |
| 1025 | 1243 | 1107 | 2350 | yes |
| 1026 | 1628 | 1108 | 2736 | yes |
| 1027 | 1545 | 1075 | 2620 | yes |
| 1028 | 1259 | 1098 | 2357 | yes |
| 1029 | 1255 | 1092 | 2347 | yes |
| 1030 | 1827 | 1134 | 2961 | yes |
| 1031 | 1319 | 1104 | 2423 | yes |
| 1032 | 1326 | 1138 | 2464 | yes |
| 1033 | 1165 | 1109 | 2274 | yes |
| 1034 | 1291 | 1113 | 2404 | yes |
| 1035 | 1314 | 1108 | 2422 | yes |
| 1036 | 1295 | 1111 | 2406 | yes |
| 1037 | 1277 | 1121 | 2398 | yes |
| 1038 | 1535 | 1119 | 2654 | yes |
| 1039 | 1289 | 1132 | 2421 | yes |
| 1040 | 1595 | 1142 | 2737 | yes |
| 1041 | 1274 | 1152 | 2426 | yes |
| 1042 | 1175 | 1154 | 2329 | yes |
| 1043 | 1294 | 1135 | 2429 | yes |
| 1044 | 1236 | 1167 | 2403 | yes |
| 1045 | 1269 | 1161 | 2430 | yes |
| 1046 | 1419 | 1199 | 2618 | yes |
| 1047 | 1397 | 1180 | 2577 | yes |
| 1048 | 1239 | 1222 | 2461 | yes |
| 1049 | 1564 | 1177 | 2741 | yes |
| 1050 | 1403 | 1210 | 2613 | yes |
| 1051 | 1325 | 1178 | 2503 | yes |
| 1052 | 1358 | 1210 | 2568 | yes |
| 1053 | 1570 | 1178 | 2748 | yes |
| 1054 | 1313 | 1180 | 2493 | yes |
| 1055 | 1556 | 1196 | 2752 | yes |
| 1056 | 1433 | 1193 | 2626 | yes |
| 1057 | 1498 | 1264 | 2762 | yes |
| 1058 | 1523 | 1222 | 2745 | yes |
| 1059 | 1409 | 1242 | 2651 | yes |
| 1060 | 2139 | 1360 | 3499 | yes |
| **Total** | **90,375** | **67,095** | **157,470** | **90,375 + 67,095 = 157,470, and the sixty rows sum to the total** |

**Apparatus share 426.08 per thousand of the whole file. Nothing in either column is counted twice and no row is a copy of another. Chapter 1060 is the longest page in the volume by six hundred and fifty-one tokens; it is the only page that carries the accounting and the final image together.**

**THE SIX MOVEMENTS' PUBLISHED FIGURES BESIDE THE SIXTY-FILE FIGURE, SIDE BY SIDE, WHICH IS THE TABLE FOUR WRONG COLUMNS WERE MISSING.** Published body / apparatus / whole against this instrument's re-measurement of the same ten files, then the sixty-file totals of each:

| Movement | Published | Re-measured | Delta body / app / whole |
| --- | --- | --- | --- |
| I | 14,000 / 10,318 / 24,318 | 14,000 / 10,318 / 24,318 | 0 / 0 / 0 |
| II | 19,239 / 10,569 / 29,808 | 19,241 / 10,569 / 29,810 | +2 / 0 / +2, the recorded stale body table |
| III | 15,317 / 11,031 / 26,348 | 15,334 / 11,031 / 26,365 | +17 / 0 / +17, the recorded stale body table |
| IV | 13,406 / 11,197 / 24,603 | 13,406 / 11,197 / 24,603 | 0 / 0 / 0 |
| V | 13,270 / 11,597 / 24,867 | 13,270 / 11,757 / 25,027 | 0 / +160 / +160, sixteen per file on all ten, §9.0.1 settled |
| VI | 15,112 / 12,193 / 27,305 | 15,124 / 12,223 / 27,347 | +12 / +30 / +42, on Chapters 1051–1055 only; 1056–1060 reproduce to the digit |
| **Sixty, published sums** | **90,344 / 66,905 / 157,249** | — | — |
| **Sixty, measured** | — | **90,375 / 67,095 / 157,470** | **+31 / +190 / +221, every unit of it in the three rows above** |

**Fifty of the sixty files reproduce their movement's published row to the digit. The other ten are all accounted for: two stale body columns published before their own repairs, one apparatus column one hundred and sixty low, and five Movement VI files whose bodies were re-shaped after their table was written. No repair moves any of them; findings go here and the repair is a separate decision.**

### 9.3 THE `about` RATES, ALL THREE CASE CONVENTIONS, DENOMINATOR BESIDE EVERY ROW

**Case-sensitive counts lowercase `about` only; case-insensitive counts both forms; capital-form-only counts sentence-initial `About` only. PPOOL is the concatenated sixty counted once; PFILE is the mean of the sixty per-file rates.**

| Scope | Convention | Hits | Denominator | Pooled per thousand | File-scope per thousand |
| --- | --- | --- | --- | --- | --- |
| body | case-sensitive | 2,637 | 90,375 | 29.18 | 28.89 |
| body | case-insensitive | 2,650 | 90,375 | 29.32 | 29.05 |
| body | capital-form-only | 13 | 90,375 | 0.14 | 0.16 |
| apparatus | case-sensitive | 543 | 67,095 | 8.09 | 8.00 |
| apparatus | case-insensitive | 550 | 67,095 | 8.20 | 8.09 |
| apparatus | capital-form-only | 7 | 67,095 | 0.10 | 0.10 |
| whole file | case-sensitive | 3,180 | 157,470 | 20.19 | 19.99 |
| whole file | case-insensitive | 3,200 | 157,470 | 20.32 | 20.12 |
| whole file | capital-form-only | 20 | 157,470 | 0.13 | 0.13 |

**Per file, whole-file scope, case-sensitive / case-insensitive / capital-form / denominator / case-insensitive rate:**

1001 52/52/0/2757/18.86; 1002 19/19/0/2369/8.02; 1003 61/61/0/2519/24.22; 1004 43/43/0/2317/18.56; 1005 33/33/0/2309/14.29; 1006 51/53/2/2212/23.96; 1007 43/43/0/2358/18.24; 1008 39/39/0/2298/16.97; 1009 68/68/0/2804/24.25; 1010 42/42/0/2375/17.68; 1011 80/80/0/3414/23.43; 1012 79/79/0/3459/22.84; 1013 80/80/0/3297/24.26; 1014 71/71/0/2602/27.29; 1015 75/75/0/2845/26.36; 1016 65/65/0/2665/24.39; 1017 69/70/1/3003/23.31; 1018 59/61/2/2278/26.78; 1019 81/81/0/3300/24.55; 1020 71/71/0/2947/24.09; 1021 68/68/0/2933/23.18; 1022 50/50/0/2663/18.78; 1023 53/53/0/2816/18.82; 1024 51/52/1/2582/20.14; 1025 29/29/0/2350/12.34; 1026 61/61/0/2736/22.30; 1027 61/61/0/2620/23.28; 1028 42/42/0/2357/17.82; 1029 35/35/0/2347/14.91; 1030 65/65/0/2961/21.95; 1031 36/36/0/2423/14.86; 1032 44/45/1/2464/18.26; 1033 20/20/0/2274/8.80; 1034 62/63/1/2404/26.21; 1035 32/33/1/2422/13.63; 1036 47/47/0/2406/19.53; 1037 55/55/0/2398/22.94; 1038 45/45/0/2654/16.96; 1039 51/52/1/2421/21.48; 1040 53/53/0/2737/19.36; 1041 37/37/0/2426/15.25; 1042 48/49/1/2329/21.04; 1043 39/39/0/2429/16.06; 1044 52/52/0/2403/21.64; 1045 48/48/0/2430/19.75; 1046 55/55/0/2618/21.01; 1047 48/48/0/2577/18.63; 1048 52/55/3/2461/22.35; 1049 68/68/0/2741/24.81; 1050 47/47/0/2613/17.99; 1051 44/44/0/2503/17.58; 1052 51/51/0/2568/19.86; 1053 49/49/0/2748/17.83; 1054 54/55/1/2493/22.06; 1055 45/45/0/2752/16.35; 1056 59/60/1/2626/22.85; 1057 54/54/0/2762/19.55; 1058 50/50/0/2745/18.21; 1059 60/61/1/2651/23.01; 1060 79/82/3/3499/23.44.

**WHETHER NINETEEN IS THE TARGET IS SETTLED AS FAR AS A CLOSE CAN SETTLE IT.** Nineteen stands named as the standing target in all six movement prompts, and the sixty-file figure is twenty and thirty-two hundredths pooled and twenty and twelve hundredths at file scope, case-insensitively, above it on either denominator (over the published-denominator sum the same numerator comes to twenty and thirty hundredths). The close does not revise the target, does not rank the movements against it, and does not run any substitution: the word does three jobs in this manuscript — the uncertainty register, the designation idiom, and the clock register — and the sixty-file figure is published with the per-file table so that a later pass can see which pages carry it.

### 9.4 GUARDRAIL THREE AS `outline/volume-20.md` WRITES IT, EIGHTEEN CELLS AND THE FLAT TEST

**Whole normalised sentence as key, lowercased, floor twelve tokens. Pair-hits count file pairs sharing a key; shared keys count distinct keys held by two or more files.**

| Scope | Paragraph rule | Convention | Segments | Distinct | Pair-hits | Shared keys |
| --- | --- | --- | --- | --- | --- | --- |
| prose | breaks KEPT | strict | 2,781 | 2,773 | 6 | 4 |
| prose | breaks KEPT | quotation-state | 2,311 | 2,303 | 6 | 4 |
| prose | breaks KEPT | any-quote | 2,311 | 2,303 | 6 | 4 |
| prose | breaks DROPPED | strict | 2,790 | 2,782 | 6 | 4 |
| prose | breaks DROPPED | quotation-state | 2,320 | 2,312 | 6 | 4 |
| prose | breaks DROPPED | any-quote | 2,320 | 2,312 | 6 | 4 |
| apparatus | breaks KEPT | strict | 978 | 964 | 12 | 14 |
| apparatus | breaks KEPT | quotation-state | 978 | 964 | 12 | 14 |
| apparatus | breaks KEPT | any-quote | 978 | 964 | 12 | 14 |
| apparatus | breaks DROPPED | strict | 978 | 964 | 12 | 14 |
| apparatus | breaks DROPPED | quotation-state | 978 | 964 | 12 | 14 |
| apparatus | breaks DROPPED | any-quote | 978 | 964 | 12 | 14 |
| whole file | breaks KEPT | strict | 3,759 | 3,736 | 17 | 18 |
| whole file | breaks KEPT | quotation-state | 3,289 | 3,266 | 17 | 18 |
| whole file | breaks KEPT | any-quote | 3,289 | 3,266 | 17 | 18 |
| whole file | breaks DROPPED | strict | 3,768 | 3,745 | 17 | 18 |
| whole file | breaks DROPPED | quotation-state | 3,298 | 3,275 | 17 | 18 |
| whole file | breaks DROPPED | any-quote | 3,298 | 3,275 | 17 | 18 |

**The flat whole-file test, one key compared across all sixty files at once, returns eighteen shared keys.** Every one of the eighteen stands on files of two different movements; no movement shares a key within its own ten. The six published ten-file zeroes are therefore true of ten files and blind at sixty, which is the fourth thing this repository has paid for measuring at movement scope. The eighteen, in full: prose — one work sentence on Chapters 1010, 1014 and 1025; one Tuesday caller line on 1011 and 1022; one printer's fragment on 1030 and 1031; one man's sentence on 1038 and 1047. Apparatus, fourteen — seven card wordings (1003 with 1016; 1001 with 1017; 1020 with 1021; 1015 with 1023; 1030 with 1033; 1019 with 1034; 1044 with 1058); two dated-rule sentences (1011 with 1022; 1020 with 1021); three ten-objects framings (1009 with 1015; 1012 with 1037; 1020 with 1021); one dark-room condition (1006 with 1014); one book line (1010 with 1024). **All eighteen are identical sentences, all are cross-movement, and none is repaired here: the prose four are repairable-class and the apparatus fourteen are structural, the same standing facts reworded per movement with seven card wordings recurring exactly.**

### 9.5 THE DUPLICATION MEASURE, BOTH KEYS BESIDE EVERY CELL, PROXY PAIR-HITS TRACED AND CLASSIFIED

**The plan's key is §9.4. The last-twelve-token proxy takes the last twelve tokens of every qualifying sentence, lowercased. Proxy pair-hits and shared keys beside every cell:**

| Scope | Paragraph rule | Convention | Proxy distinct | Proxy pair-hits | Proxy shared keys |
| --- | --- | --- | --- | --- | --- |
| prose | breaks KEPT | strict | 2,736 | 72 | 27 |
| prose | breaks KEPT | quotation-state | 2,269 | 69 | 24 |
| prose | breaks KEPT | any-quote | 2,269 | 69 | 24 |
| prose | breaks DROPPED | strict | 2,745 | 72 | 27 |
| prose | breaks DROPPED | quotation-state | 2,278 | 69 | 24 |
| prose | breaks DROPPED | any-quote | 2,278 | 69 | 24 |
| apparatus | breaks KEPT | strict | 884 | 178 | 56 |
| apparatus | breaks KEPT | quotation-state | 884 | 178 | 56 |
| apparatus | breaks KEPT | any-quote | 884 | 178 | 56 |
| apparatus | breaks DROPPED | strict | 884 | 178 | 56 |
| apparatus | breaks DROPPED | quotation-state | 884 | 178 | 56 |
| apparatus | breaks DROPPED | any-quote | 884 | 178 | 56 |
| whole file | breaks KEPT | strict | 3,619 | 223 | 82 |
| whole file | breaks KEPT | quotation-state | 3,152 | 220 | 79 |
| whole file | breaks KEPT | any-quote | 3,152 | 220 | 79 |
| whole file | breaks DROPPED | strict | 3,628 | 223 | 82 |
| whole file | breaks DROPPED | quotation-state | 3,161 | 220 | 79 |
| whole file | breaks DROPPED | any-quote | 3,161 | 220 | 79 |

**Every one of the eighty-two proxy shared keys is traced in `workspace/volume-20/close/CLOSE.md` §4 to its files and classified: arithmetic (docket-figure tails recurring by the origin set), structural (the house's standing conditions, lists and time language, the same on every page by guardrail), or repairable-class prose standing on closed pages. The proxy manufactures hits out of arithmetic on docket-bearing pages by construction — the last twelve tokens of a docket row are the figure and nothing else — and a pass that wants zero on it is asking for anchor figures that never collide, which is arithmetic and not prose.**

### 9.6 THE STANDING ANCHORS AS A SCOPE OF ITS OWN

**Sixteen origins, unchanged from Volume 19 and continuous with Chapter 1000's docket at day 2212: 362, 358, 442, 491, 526, 547, 572, 590, 644, 666, 672, 729, 756, 796, 814 and 982. Nine hundred and sixty origins-against-pages assertions, nine hundred and sixty self-consistency tests (day figure equals seven times weeks plus remainder), nine hundred and sixty own-day agreements: 960 of 960, 960 of 960, 960 of 960.** Exact-week rows per file (anchors whose interval is a whole number of weeks), Chapters 1001 to 1060 in order: 3, 0, 3, 7, 3, 0, 3, 0, 7, 3, 0, 3, 3, 0, 3, 3, 3, 0, 3, 0, 0, 0, 3, 3, 0, 3, 3, 7, 3, 0, 3, 7, 0, 0, 0, 3, 3, 0, 3, 0, 0, 0, 0, 3, 3, 0, 3, 3, 7, 3, 3, 3, 3, 0, 3, 0, 0, 3, 3, 3.

**The three short-run anchors, derived from the day and read back off all sixty pages: the sheet `day − 2189`, the second printing `day − 2203`, the thing said at a counter `day − 2212`.** One hundred and seventy-nine of one hundred and eighty stated figures agree with derivation. The five wording variants are: Chapter 1001 carries the second printing as a fortnight old; 1002 carries the third as in mouths for six days; 1003 as seven days into mouths; 1054 carries the sheet as days of sheets rather than days old; and Chapter 1004 states no age for the third anchor at all, which is the one genuinely absent cell and is a fact about that page and not a defect in it. **The sheet-night run is `day − 2150`, a count of nights and not a chapter index, and the sixty-row run is 67, 68, 69, 70, 71, 73, 74, 75, 77, 78, 82, 83, 85, 87, 88, 90, 92, 93, 95, 96, 101, 103, 104, 106, 107, 109, 111, 112, 113, 114, 118, 119, 121, 122, 124, 125, 127, 128, 130, 131, 135, 136, 138, 139, 141, 142, 144, 146, 147, 148, 151, 153, 155, 157, 160, 163, 166, 169, 172, 174.** Fifty-nine pages state their night and all fifty-nine stated nights were read back; Chapters 1006 to 1010 carry the chapter-stepped run 72, 73, 74, 75, 76 against derived 73, 74, 75, 77, 78, which is Movement I's known disagreement at the joins, named and not smoothed; Chapter 1060 carries no night line, the copy being a shop object and the last page standing in the depot. **The place behind the woman's chair is named on Chapters 1003, 1015, 1023, 1040, 1046 and 1054, one file per movement, and carries its printed figure on Chapter 1003 alone.** Its interval reads to the day on twelve chapter-carrying days (1003, 1012, 1016, 1023, 1027, 1031, 1036, 1044, 1048, 1052, 1055, 1060) and on four chapterless days (2226, 2247, 2282, 2317); of the six naming files only 1023 is itself such a day, and it carries no figure, which is the trap the plan warns of, working as built.

### 9.7 THE SUBSTRING COINCIDENCES, RE-RUN AT SIXTY FILES AND REPORTED AS ONE COUNT

**The rendered string of a forbidden figure appearing as the tail of a longer anchor numeral on another page, both pages in the sixty, ordered pairs of distinct pages: two hundred and eighteen in all, one hundred and twenty-nine of the woman's-page kind and eighty-nine of the place-interval kind.** With both pages inside one movement: I eleven, II seven, III eight, IV eight, V eight, VI three, forty-six in all. **Verdicts on the published movement counts: Movement V's eight reproduces exactly (five and three); Movement VI's three reproduces exactly (two and one); Movement IV's seventeen does not — its fourteen of the first kind reproduce only under a looser anywhere-substring rule (fourteen), while under the tail rule the file's own mechanism describes, those ten pages carry eight (five and three).** No page prints the figure of the thing it belongs to, and repairing any coincidence would mean printing a wrong anchor figure, which is the refusal this repository has recorded twice and records a third time here.

### 9.8 THE NEAR-CLONE INSTRUMENT, TOKEN-BIGRAM JACCARD, AT TEN FILES AND AT SIXTY

**Order-sensitive token-bigram Jaccard over the conditions section, the standing-record section, the ten-objects block, the six-objects sentence and the dated-rule sentence, extraction rules printed in `close/CLOSE.md` §5. Maximum pair, which pair, and mean over all pairs:**

| Block | Sixty-file max | Which pair | Sixty-file mean | Movement VI max | Movement VI pair | Movement VI mean |
| --- | --- | --- | --- | --- | --- | --- |
| conditions section | 0.651 | 1009 / 1010 | 0.344 | 0.520 | 1057 / 1059 | 0.356 |
| standing-record section | 0.652 | 1020 / 1021 | 0.351 | 0.510 | 1054 / 1058 | 0.377 |
| ten-objects block | 0.787 | 1049 / 1050 | 0.315 | 0.639 | 1054 / 1058 | 0.374 |
| six-objects sentence | 1.000 | 1004 / 1007 | 0.388 | 0.863 | 1054 / 1060 | 0.608 |
| dated-rule sentence | 1.000 | 1011 / 1022 | 0.226 | 0.774 | 1057 / 1058 | 0.376 |

**The ten objects and the four standing conditions are the same on every page by guardrail, so the set-based figure on them is uninformative and the order-sensitive figure above is the one that means anything; it measures what fixed vocabulary costs, and the two 1.000 pairs are identical single sentences (the six-objects framing inside Movement I, one dated-rule sentence across Movements II and III) standing on closed pages. The Movement VI means corroborate `batch-0006/SUMMARY.md` §6.2 within extraction tolerance (0.356/0.377/0.374/0.608/0.376 against 0.349/0.383/0.421/0.343/0.177 on differently cut blocks), and the sixty-file maxima are new.**

### 9.9 THE NINE UNREPAIRED NUMBER-WORD TITLES, AND THE ONE MORE IN THIS VOLUME

**Across Chapters 941 to 1030 the nine stand exactly as `batch-0006/SUMMARY.md` §14's closing record lists them: 947 *A Sixth Column Is Offered*, 952 *Four People In Her Head*, 956 *The Second Name*, 961 *Two Copies Of One Pencil Line*, 963 *She Came Back At Nine*, 964 *A Sixth Column On Somebody Else's Form*, 966 *Four Names On The Back Of A Card*, 969 *Two Sheets In One Tray*, and 1011 *The Woman Who Said It First*.** Five carry cardinals (Two twice, Nine, Four twice) and four carry ordinals (Sixth twice, Second, First), and a title carrying an ordinal breaks the rule in fact and not only on paper, because the rule forbids number-words and an ordinal is one. **This close does not repair them.** Of this volume's sixty titles, 1011 is the only one carrying a number-word and 1005 (*He Wrote It And Could Not Finish*) the only one carrying `And`, the latter recorded as unsettled between two wordings of the rule at `batch-0001/SUMMARY.md` §10A and still unsettled here; 1008's and 1012's were repaired in their own movements and stay repaired.

### 9.10 THE THREE THINGS THE VOLUME 19 CLOSE COULD NOT REPAIR, MEASURED AND NOT INHERITED

*One:* `workspace/volume-19/batch-0005/chapter-0989.md:186`, the END line carrying `THE BOOK SHUTS`, still remarks on the pattern its guardrail ten forbids any page to remark on; verified present, the only such tag on those sixty pages, and repairing it moves that page's word count and every denominator built on it. *Two:* the eight prose keys at `workspace/volume-19/close/CLOSE.md` §4 — seven verified letter-perfect on both named files, the eighth (944 with 953) verified modulo the page's comma, all eight still standing across Movements I, II, V and VI of that volume. *Three:* whole-word `right` returns thirteen hits on four files of Volume 19 (942, 943, 946, 947), nine of them predicative (`is right`, `was right`, `have been right`) against the two attributive `right-hand` uses; all four files still carry them. **None of the three is inherited as fact, none is repaired here, and repairing any of them moves a denominator.**

### 9.11 THE GUARDRAIL-BY-GUARDRAIL SWEEP AT SIXTY FILES

**Fifteen guardrails of `outline/volume-20.md`, one table, measured at the H1-removed boundary:**

| Guardrail | Result at sixty files |
| --- | --- |
| 1. refusals in about nine words; the one answer in about eleven | `about nine words` on 22 files, 45 occurrences, the house form; `about eleven words` on Chapters 1016, 1019 and 1058, three spends of the reserve, §9.13 |
| 2. opening bold paragraph forty to seventy-five words, no figure, no outcome, nothing said elsewhere | all sixty inside the band (lowest 42, highest 74); spelled-out figures stand in several openings and no digit stands in any |
| 3. no sentence of twelve words or more on two files | §9.4: eighteen shared keys, all cross-movement; zero within any movement |
| 4. no month-name, month-date, day-date, year, day number, mileage; intervals in words; exact weeks take `to the day` | month-names zero; month-dates zero; years zero; mileage zero; colon clock times zero; four-digit figures 63 distinct, 240 occurrences, exactly chapters 1001–1063 with four per file and no interval in digits; week figures 333–348 only |
| 5. no telephone, messenger, broadcast, feed, carried letter, in any register or negation | telephone, phone, messenger, broadcast, feed, letter, mail, postage all zero; `letterbox` thrice on Chapter 1013, a flex through a plate and not a letter arriving |
| 6. shutter at about ten on fifty-four, at about two on the six Sundays | §9.11.1: six Sundays about-two, fifty-four ten-form, no cross either way |
| 7. the woman of about thirty unnamed, uncounted, unasked | no name, no count, no question; never in a room with the woman of about thirty-nine |
| 8. ninth chair unmoved; place named on one file per movement, figure on 1003 alone | chair unmoved on all sixty, mover named nowhere; named on 1003, 1015, 1023, 1040, 1046, 1054; figure on 1003 alone |
| 9. room under the building dark on all sixty, never opened | dark on all sixty, opened on none |
| 10. no Exchange figure; book opens 73rd/75th, shuts 74th/76th; no remark on the pattern | no sitting number, no book or tin figure, no difference, no remark; the END tag of Chapter 989's volume is not this volume's |
| 11. `Crown` only in four named forms; Crown Terrace a place | `Crown` zero on all sixty, in any form; the final image takes the house form; **and both proper nouns of the plan's last line are absent, `Nacre` zero on all sixty and last seen anywhere at Chapter 166 — §9.13 and §9.15, cost not settlement** |
| 12. ten objects one to a sentence; the card the new one | ten present on all sixty, one to a sentence, in sixty wordings; six outside the ten on all sixty |
| 13. `Evan Senn` zero | `Evan` zero, `Senn` zero |
| 14. register at four, printed, never a fifth | four on all sixty, in each file's own words, added to by nothing |
| 15. load book reports no prohibited absence; standard heading sixty times | kept sixty times, subject the day's work |

**§9.11.1 THE SHUTTER.** About-two shutter language on Chapters 1006, 1014, 1021, 1034, 1042 and 1054 and on no other file; ten-form shutter or book-shut language on the other fifty-four and the six Sundays' surrounding days; no file carries the other's form. **Forbidden words, exact patterns printed beside every result:** `fair`, `unfair`, `justice`, `rightful`, `principle`, `coalition` and relatives zero on all sixty; `right` in any use zero on all sixty; bare `purpose` thrice (twice adverbial *on purpose* on Chapter 1003, once the denial *it was not a purpose* on Chapter 1009, which also prints the volume's coined subject inside a denial and is named at §9.13 rather than repaired); `Evan`, `Senn` zero; placed cast `Rafi`, `Pell`, `Dessa`, `Kwan`, `Oren`, `Vey`, `Iven`, `Sore`, `Lena` zero on all sixty, and no page was invented for any of them. **Month sweep, twelve whole-word stems:** eleven return zero; `may` returns forty-seven hits on forty-two files, every one the modal verb (two shown: the dated-rule *may read* and the permission *may write*), and no file carries a month-name. **Communication words** in every register and negation zero throughout, `letterbox` excepted as above. **`screen` zero on all sixty files of this volume; `screening` zero on all sixty and on all one thousand and sixty files on disk.** `Iona Sorn` on no page of this volume. **Sitting numbers, book figures, tin figures, differences: zero. Arrival cells: absent and not approximated. `not a purpose`: once, Chapter 1009, inside a denial.**

### 9.12 THE SIX OWNER ITEMS, ALL UNRULED, AT VOLUME SCOPE

| Item | At Chapter 1001 | At Chapter 1060 | This phase proposes |
| --- | --- | --- | --- |
| 1. plan against disk | plan 760 in 15; disk 1,000 in 20 | plan 760 in 15; disk 1,060 in 20 | nothing |
| 2. support-spend overage at three readings | untouched | untouched | nothing |
| 3. placed cast of five names | zero on every page so far | zero on all sixty | nothing |
| 4. plan's phrase on Chapter 933 | untouched | untouched | nothing |
| 5. fifth column's heading, two items and not one | blank with three refusals behind it | blank with a rule under it, refused as an answer on the page | nothing |
| 6. ombud's office used on him; whether 760, 1000 or 1060 is the ending | zero uses in every movement of this volume | zero uses in all six movements; the ending undecided | nothing |

### 9.13 TWO DECISIONS SETTLED OUT LOUD, RECORDED AND NOT REVERSED, AND ONE LEFT UNSETTLED

**The word `right`:** `outline/volume-20.md` lines 96 and 100 prescribe Marek's climax sentence with *right*; line 124 forbids the word as an adjective on all sixty pages. The volume prints no use of the word on any of its sixty pages, and Chapter 1057 carries the sentence as *he may stay and he does not have to answer it, and I do not know whether that is the answer.* Recorded; reversing it changes one word on one closed page and is not this phase's to do.

**`The Crown Vault`: this paragraph was corrected by the review-fix pass of this phase and the correction matters.** `outline/ending.md` line 160 ends *Across **Nacre**, windows light in separate rooms. The old **Crown Vault** remains dark.* Guardrail eleven permits the form; Movements I to V place `Crown` at zero and Movement VI at zero; Chapter 1060 takes the house form, *the room under the building in that first district stayed dark*. **This section previously recorded that as a decision recorded and not reversed, and it is not: it is a cost taken on the manuscript's last page, and it should not be filed beside a settled disagreement, because nothing disagreed.** The word is absent; so is the other proper noun in that line. **`Nacre` is zero on all sixty files of this volume, zero across Volumes 15 to 19, and its last occurrence anywhere in this manuscript is Chapter 166 — eight hundred and ninety-four chapters before the last page. `Crown`'s last occurrence anywhere is Chapter 756, in three other permitted forms, never as the Vault.** So the plan's final image arrives with both of the words that make it legible to a reader of Volume 01 removed, and a reader who has not had the city named in eight hundred and ninety-four chapters is told that windows lit somewhere and that a room stayed dark. **The house form is what the guardrails require and it is defensible as prose, and the cost is real, and both of those are now written down instead of one of them.** Not reversed; not repairable without a closed page; the owner's.

**`about eleven words`:** spent on Chapters 1016, 1019 and 1058 against a reserve the volume meant for its one answer. The movement that spent it last printed both readings — a count describing the sentence is describing and not stating; a count is a frame and this volume refused frames — and recorded the disagreement. **This close records the disagreement as unsettled at volume scope: three spends, no page stating what the room is for, no page agreeing with the answer and none repeating one word of it, and either reading writable only by touching a closed page.**

### 9.14 WHAT WAS FOUND AND NOT REPAIRED, AND WHAT WAS NOT SPENT

**Found and not repaired:** the Movement V apparatus column (160 low, §9.2); Movement II and III stale body columns (+2, +17); Movement VI Tables on 1051–1055 (+12/+30 and lead-ins); eighteen cross-movement shared sentences; eighty-two proxy pair-hits; two hundred and eighteen substring coincidences; the chapter-stepped nights on 1006–1010; the absent night on 1060 and the absent third age on 1004; the nine titles and the `And` of 1005; Chapter 1009's denial; the three Volume 19 items; the sentence-scope instrument divergence; **and the sheet-count contradiction on thirty-six of the sixty files, §9.15, which this list omitted in its first version because the instrument returned it as fixed vocabulary and it is not fixed vocabulary, it is a contradiction between two parts of the same page about what is in a bag.** Every repair moves a denominator already published in six movement summaries, so every finding stands as a finding and the repair is a separate decision. Not spent, on any of the sixty pages: the woman's page (no figure, no range, at any day); the four arrival cells; the fifth of the register; any Exchange figure or difference; any comparison of two hand copies; the fifth column's heading; the plan's phrase on Chapter 933; the ombud's office as used on him in Volume 18; the question of the ending; and Iona Sorn, who is on no page of this volume. **The fifteen guardrails hold on all sixty files with the two recorded readings left reading.**

**Two things the sweep found are not on this list and are not defects, and §9.15 and `close/CLOSE.md` §12 say where they went instead.** The final image's two missing proper nouns (§9.13) are a cost against the plan rather than a breach of a guardrail, and the drained power-system vocabulary is a question about a book rather than a question about a file.

**Sixty files, one hundred and fifty-seven thousand four hundred and seventy words, three thousand two hundred hedges, nine hundred and sixty anchor rows all rendering, eighteen shared sentences all across movements, and no new enemy. The volume is measured.**

### 9.15 WHAT THE REVIEW OF THIS CLOSE FOUND, ADDED BY THE REVIEW-FIX PASS, AND NOTHING IN §9.0 TO §9.14 WAS RECOMPUTED

**This subsection was appended after the close was reviewed. Every finding below was checked against the sixty files before it was written here. No figure in §9.1 to §9.14 moved, and the review re-derived the sixty-file arithmetic from the §9.0 instrument and reproduced body 90,375, apparatus 67,095, whole 157,470, the 426.08 per thousand, the 3,200 hedges, every per-file row and the Movement VI lead-in drift to the digit. The instrument was not at fault in any of the nine findings and it is worth saying so once: six of them are things no instrument of this kind is built to see.**

**9.15.1 THE SHEET-COUNT CONTRADICTION, ON THIRTY-SIX OF SIXTY FILES, AND §4's CLASSIFICATION OF IT WAS WRONG.** `close/CLOSE.md` §4 classed the eight six-objects tails as structural — that is, as fixed vocabulary whose repair means unwriting the close — and the review of this close refused that. `chapter-1060.md:15` and `:25` have Marek say that the bag under the long bench holds *the hundred and fifty* sheets and that the *second* hundred and fifty was printed elsewhere, never on that wall, cost five more days of takings and has never been found. `chapter-1060.md:207` and thirty-five other files, the earliest at `chapter-1010.md`, carry *a carrier bag under a long bench with two hundred and fifty sheets in it*. **Thirty-six pages therefore contradict their own dialogue about a physical object, and the object is the one the volume spends its money on. `state/continuity.md`'s governing block §2 has the figure right and is the correction of record.** The repair is one clause on thirty-six files and it is not made here, because thirty-six word-count changes move the body column, the apparatus column, the `about` rates, the bigram figures and the sixty-row totals at once, and those are published in six movement summaries. Carried as a thread; this subsection is the defect of record.

**9.15.2 CHAPTER 1060 IS THE SECOND STAGING OF THE PLAN'S FINAL IMAGE AND `close/CLOSE.md` §8 AND §9 SAID IT WAS THE FIRST.** `chapter-0759.md:3` opens the same converted tram depot, the same scarred bench, the same about eleven people and the same man being the one who got stopped; `chapter-0760.md:186` and `chapter-0763.md:129` name it again in the standing record. Four files on disk carry the depot and three are three hundred chapters back. **The difference the volume built — asked in advance in a doorway at 759, asked at the bench in front of everybody at 1060 — is real and stands, and a reader who has read both pages meets an ending that has already happened, which no page of this volume says out loud and which the close did not disclose.**

**9.15.3 BOTH PROPER NOUNS OF THE PLAN'S LAST LINE ARE ABSENT, AND §9.13 NOW RECORDS THAT AS A COST.** See §9.13 as corrected. `Nacre` zero on all sixty and zero across Volumes 15 to 19, last seen at Chapter 166; `Crown` zero on all sixty, last seen at Chapter 756 in three other permitted forms and never as the Vault.

**9.15.4 THE RECORDED OWNER DEFAULT IS CHAPTER 820 AND THE CLOSE DID NOT MENTION IT.** `NOVEL_SPEC.md:55`, in the Status block no agent pass may write: **the default if no decision is ever taken is that the manuscript ends at Chapter 820.** The disk stands at 1060, two hundred and forty chapters past the only ending number the record contains. `close/CLOSE.md` §8 names Chapter 760, Chapter 1000 and Chapter 1060 as the three candidates and omits the fourth and the default, and owner items one and six are one item. Corrected in `close/CLOSE.md` §8 and carried at `state/open-threads.md` §10.

**9.15.5 NO NEXT PHASE IS NOT THE SAME AS NO FURTHER DISPATCH, AND THE CLOSE DESCRIBED THE CONTROLLER WRONG.** `close/PROMPT.md` §1–§6 forbids this phase from creating anything and this pass obeyed it. `.github/workflows/novels.yml` does not wait: `workspace/volume-20/close/` has no `.done`, so the detection step finds an eligible phase and re-dispatches this close; and once a marker exists, the seed step's heredoc writes `workspace/continuation/next-0023/PROMPT.md` telling the writer to plan the next volume and write its first ten to twenty chapters, with no `outline/volume-21.md` on disk and no `state/complete.md`. **That is the operational flag and it belongs in the close's own headline rather than in a sentence about who owns a decision. The workflow was read and not edited and this pass created and removed no marker.**

**9.15.6 `state/continuity.md`'S INDEX LINE OVERSTATED WHAT WAS CARRIED FORWARD, AND THE MISSING ITEMS ARE NOW IN THE GOVERNING BLOCK.** The index claimed nine named items from the Movement IV block were "restated in full in the governing block", and at least four were not: the pad word the woman of about forty-three refused to print, the door-asking, the seventy-fourth sitting shutting the book, and the place named on Chapter 1040 alone. The governing block also dropped the must-not-inherit anchors section both predecessor blocks carried. **All four are now in the governing block and the section is restored, and the index line has been corrected to say what is true, which is that the block is recoverable whole from the history and that its remaining items are end-state already stated above.**

**9.15.7 TWO COMPACTION SENTENCES IN ONE PASS CONTRADICTED EACH OTHER.** `close/CLOSE.md` §10 said one file went over its mark and was compacted, which is `state/continuity.md` and is correct; `state/character-state.md` line 1 said no file went over its mark in the same pass. Line 1 is corrected. **This subsection's own honest position is that a review-fix pass is not a close and is not a movement, and it appended nothing to any state file's governing block for that reason: it corrected text inside the close's existing block instead, so that one dated block per file per phase is still true and the block in each file still belongs to the phase that wrote it.**

**9.15.8 AND 9.15.9, WHICH ARE NOT DEFECTS AND ARE NOT INSTRUMENT FINDINGS.** The repetition — one hundred and twenty-one identical thank/forgive sentences across sixty pages, standing on every one of them, twice in fifty-nine and three times in Chapter 1060, which is eight or nine chapters to every weekday; the phrase `about four people` three hundred and ninety-three times, `have said since` two hundred and ninety-two times, `about` once per thirty-four body words, forty-two and six-tenths per cent of every chapter in fixed apparatus — and the drained power-system vocabulary, `Counterpoint` in one file of one thousand and sixty, `Solo Seal` in four and all in Volumes 01 and 05, `Open Weave` in none, nothing of it in Volume 20. **§5's statement that the bigram figure prices fixed vocabulary and not fault is true of the instrument and silent about a reader, and the genre promise in `outline/series.md` is not legible anywhere in the last three hundred chapters.** Both are the owner's; both are at `close/CLOSE.md` §12 and `state/open-threads.md` §12; neither is repaired here, and neither is added to §9.14 because §9.14 lists defects against files and these are questions about a book.
