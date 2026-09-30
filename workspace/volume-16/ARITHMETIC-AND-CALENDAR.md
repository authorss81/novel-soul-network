# Arithmetic and calendar — Volume 16

**`workspace/volume-16/ARITHMETIC-AND-CALENDAR.md`, at the volume root, beside `batch-0001/`, and not inside any phase directory. It is a volume-level working file and not a phase: it holds no `PROMPT.md` and no marker, so the controller's selection rule — the first directory under `workspace/` holding a `PROMPT.md` and no `.done` — is unaffected by it. `workspace/volume-06/ARITHMETIC-AND-CALENDAR.md` through `workspace/volume-15/ARITHMETIC-AND-CALENDAR.md` are the precedents and sit in the same place.**

**It was written with `outline/volume-16.md` and before Chapter 761. Sections 1 to 6 and 8 are a plan of figures and not a table read back off chapters, and every number below is a day number minus a named anchor day and can be recomputed by anybody in about a minute. Section 7 is a list of debts carried forward and it plans nothing. Section 9 is reserved for the Volume 16 close and no writing pass before it may write it.**

**THE FLAG, ONCE, AT THE HEAD, AND NOT AT THE FOOT.** **This volume did not exist in the plan of record.** `outline/series.md`, `outline/ending.md` and `NOVEL_SPEC.md` all held that the manuscript was finished at Chapter 760 of a planned 760 with no Volume 16 and no next phase. A directive to continue the novel arrived after the Volume 15 close had run, with the instruction that a complete volume is followed by a planned next volume and its first batch. **Sections 1 to 8 below were produced for that directive and are the plan of record for this volume only. No figure here contradicts a figure on any of the seven hundred and sixty chapters already on disk, and no anchor has moved since Volume 01.**

## Four rules, and they are the same four as the ten files before this one.

1. **No day number may be printed in a chapter.** No month-name, no month-date, no day-date, no year. The only calendar nouns permitted are the season words, the week and the day inside the week. **All interval figures are spelled out in words, and a figure that is an exact number of weeks is rendered with the words *to the day* and is not rendered with the word *short*.** No chapter of this volume prints how far away a town is, and a town is described by how long the bus takes or by nothing at all.
2. **A day is assigned only by section 1 of this file.** Where this file and a live batch prompt disagree on a day, **the batch prompt is right for its ten days and this file is right for the run**, and a batch prompt that disagrees with the table below on a day is a defect to be corrected in place and recorded.
3. **Weeks run Monday to Sunday. The detector is inherited unchanged and is `week = (day − 502) // 7 + 88` and the weekday is `wd = (day − 502) mod 7` against Monday-first, and the Monday of week _n_ is `7 × n − 114`.** **A value that disagrees with the detector is the value that is wrong.** The relation was asserted against every week from eighty-eight to two hundred and ninety-nine before this file was written and returned Monday for all two hundred and twelve of them. **A pass that writes the Monday as `7 × W − 682` has dropped two digits and will produce a Monday four hundred and ninety-one days early, and that error has been found in this repository once already.**
4. **Every figure in this file is a subtraction and not a count.** Nothing here was read off a chapter.

---

## 0. What this file inherits

### 0.1 THE CHAIN, CHECKED AND NOT RE-DERIVED

**The anchors are not duplicated here, because a table of anchors is a second place in this repository a figure can be copied from and the seventh time that has happened has been a defect; they are in section 2 and they have not moved since Volume 01.** The chain gives 1762 as the Monday of week two hundred and sixty-eight, 1764 as the Wednesday Volume 15 closed on, and 1769 as the Monday of the week after. `7 × 268 − 114 = 1762`, `1762 + 2 = 1764`, `7 × 269 − 114 = 1769`, `1764 + 5 = 1769`.

### 0.2 THE DAY ZERO, MADE EXPLICITLY AND PRINTED, WITH THE OPENING THAT WAS REFUSED

**Chapter 761 is day 1769, the Monday of week two hundred and sixty-nine. In one sentence: Volume 16 opens on the first Monday after the Wednesday Volume 15 closed on, and 1769 is 1764 + 5, and 1764 is the Wednesday of week 268, and 1762 is the Monday of week 268, and 1769 is 1762 + 7.**

**It is a decision and not a consequence. Four other openings were available and were not taken.** 1765 is a Thursday and would have put a volume about a district leaving on a Thursday, which is the conventional day to begin a process and the day on which a process is easiest to ignore. 1766 is a Friday and this manuscript does things on Fridays. 1767 and 1768 are a Saturday and a Sunday. **The Monday is the only opening that lets a sheet go on a board early enough in a week for four people to walk past it before the weekend, and the whole of Movement I is about how many people walk past it.**

**One thing is on this opening day that a writer of this volume has to know and cannot get from a chapter: a woman of about thirty-four pins a printed sheet to a board in a second district at about eleven, and the man of twenty-two is about nine feet away on the floor with a door closer, and neither of them says a word to the other, and he does not find out for two days that it is a notice of anything at all.**

### 0.3 WHAT THIS FILE'S FIGURES DEPEND ON, RESTATED WITH ITS SUBTRACTION BESIDE IT

| Figure | Arithmetic | Value |
| --- | --- | --- |
| Chapter 760 | the Wednesday of week 268, 7 × 268 − 114 + 2 | 1764 |
| Chapter 761 | 1764 + 5, and the Monday of week 269, 7 × 269 − 114 | 1769 |
| The first sitting in this volume | the Wednesday of week 272, 7 × 272 − 114 + 2 | 1792 |
| The last sitting and the close | 7 × 284 − 114 + 2 | 1876 |
| The whole of Volume 16 | 1876 − 1769 | 107 days |
| The whole of Volume 16 inclusive of both ends | 1876 − 1769 + 1 | 108 days |
| The first sitting to the close | 1876 − 1792 | 84 days |
| The place behind the woman's chair at Chapter 761 and at Chapter 820 | 1769 − 1484, and 1876 − 1484 | 285 days, and 392 days |
| The woman's page in the ring binder at Chapter 761 and at Chapter 820 | 1769 − 1578, and 1876 − 1578 | 191 days, and 298 days |

**The place behind the woman's chair in the room above a line in Saltmarket has been empty since the Wednesday of day 1484 and is two hundred and eighty-five days old at the opening of this volume and three hundred and ninety-two at the close, and three hundred and ninety-two is fifty-six weeks to the day.** The woman's page is the eighth of eight and stood at one hundred and ninety-one days on Chapter 760; it has been on a shelf for every day since and no page of this volume prints a figure for it in a load book, and the row above is here so that a later pass has something to check against and not a sentence to copy.

### 0.4 THE FOUR FREE CHECKS, WITH THEIR SIGNS, IN FULL, AND WHAT THEY ARE

| Check | Expression | Constant | Sign as printed |
| --- | --- | --- | --- |
| The card-minus-room invariant | `(day − 358) − (day − 362)` | 4 | {4} |
| The fourteen-less-fifteen | `(day − 526) − (day − 547)` | 21 | {21} |
| The fifty-one-less-hold | `(day − 756) − (day − 729)` | −27 | {−27} |
| The eighteen-less-sixteen | `(day − 644) − (day − 572)` | −72 | {−72} |

**Walked on all sixty rows of section 1 before Chapter 761 was written, from the anchor table and not from a chapter: zero off-row on all four, sixty rows each, two hundred and forty cells.**

**AND THE STANDING WARNING, EARNED BY THE VOLUME 15 CLOSE AND REPEATED HERE VERBATIM: these four are identities. They are true of any input whatever, including a file of nonsense, so their clean set is a property of the anchor table and is not evidence about a single line of prose.** They are printed as four true sentences about four pairs of anchors and they are not published as a result. This is the fifth withdrawal and the withdrawal is a standing rule in this repository.

### 0.5 THE SPENT-AGE CLASS GETS AN INSTRUMENT AND NOT ONLY A PROHIBITION

**For each file: extract every occurrence of a spent age, take the noun phrase it sits in, and record whether a person is the subject of it. A spent age on a person established in this manuscript is permitted and is canon. A spent age on a new person is a finding and not a permission. A raw substring count of the spent ages is not an instrument, because a new person can carry a spent age any number of times and a raw count cannot see who is carrying it.** **Movement I names two new people and neither is given a spent age.**

### 0.6 THE TWO INHERITED FIGURES WHOSE SUBJECT CHANGES AND WHOSE ARITHMETIC DOES NOT

**The separation walks as `day − 982` and its anchor has not moved since Volume 11 and does not move here. What changes is what it is used for.** In Volume 15 it was the standing proof of a rule about silence. In this volume it is the standing proof of a different one: **a withdrawal is a thing a person does inside a process, and a separation ended in a one-line box in a form is the same shape, and the number in that column has gone on being a correct subtraction since and does not know it.** **The column headed `Sep` in section 1 is therefore a count of days that describes nothing, and a writer who stops printing it has broken the instrument.**

**The place behind the woman's chair walks as `day − 1484` and it is printed on ONE file of each movement and on no other, because a whole-file interval walk built from the anchor table alone returns a false finding on any file that prints it, and a series that is walked on every page stops being the thing it was.** In Movement I it is printed on Chapter 763.

---

## 1. The day map, all sixty chapters, with the load-book entry on each row

| Ch | Mv | Week | Day | Day no. | Entry | Room | Card | 19 | Hold | Ask | 51 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 761 | I | 269 | **Monday — the volume opens, and the sheet goes on a board** | 1769 | 764 | 1,407 | 1,411 | 1,103 | 1,040 | 1,097 | 1,013 |
| 762 | I | 269 | **Tuesday — the question nobody can answer** | 1770 | 765 | 1,408 | 1,412 | 1,104 | 1,041 | 1,098 | 1,014 |
| 763 | I | 269 | **Wednesday — the room is open and no number is said** | 1771 | 766 | 1,409 | 1,413 | 1,105 | 1,042 | 1,099 | 1,015 |
| 764 | I | 269 | **Thursday — a reason on the back of a sheet** | 1772 | 767 | 1,410 | 1,414 | 1,106 | 1,043 | 1,100 | 1,016 |
| 765 | I | 269 | **Friday — a hand that will not steady, and nothing to repair** | 1773 | 768 | 1,411 | 1,415 | 1,107 | 1,044 | 1,101 | 1,017 |
| 766 | I | 270 | **Monday — the procedure, and the word with no number in it** | 1776 | 769 | 1,414 | 1,418 | 1,110 | 1,047 | 1,104 | 1,020 |
| 767 | I | 270 | **Tuesday — money, refused with a reason about the work** | 1777 | 770 | 1,415 | 1,419 | 1,111 | 1,048 | 1,105 | 1,021 |
| 768 | I | 270 | **Thursday — a caller asks him whether he can stop a district leaving** | 1779 | 771 | 1,417 | 1,421 | 1,113 | 1,050 | 1,107 | 1,023 |
| 769 | I | 270 | **Friday — the register moves from three to four** | 1780 | 772 | 1,418 | 1,422 | 1,114 | 1,051 | 1,108 | 1,024 |
| 770 | I | 271 | **Monday — the second half of the notice, and the one thing** | 1783 | 773 | 1,421 | 1,425 | 1,117 | 1,054 | 1,111 | 1,027 |
| 771 | II | 271 | Tuesday | 1784 | 774 | 1,422 | 1,426 | 1,118 | 1,055 | 1,112 | 1,028 |
| 772 | II | 271 | Wednesday | 1785 | 775 | 1,423 | 1,427 | 1,119 | 1,056 | 1,113 | 1,029 |
| 773 | II | 271 | Thursday | 1786 | 776 | 1,424 | 1,428 | 1,120 | 1,057 | 1,114 | 1,030 |
| 774 | II | 271 | **Friday — a card with two lines of type on it** | 1787 | 777 | 1,425 | 1,429 | 1,121 | 1,058 | 1,115 | 1,031 |
| 775 | II | 272 | **Monday — the volume's one panel and its one marker** | 1790 | 778 | 1,428 | 1,432 | 1,124 | 1,061 | 1,118 | 1,034 |
| 776 | II | 272 | Tuesday | 1791 | 779 | 1,429 | 1,433 | 1,125 | 1,062 | 1,119 | 1,035 |
| 777 | II | 272 | **Wednesday — the Exchange, the fifty-seventh sitting, the book does not open** | 1792 | 780 | 1,430 | 1,434 | 1,126 | 1,063 | 1,120 | 1,036 |
| 778 | II | 272 | Thursday | 1793 | 781 | 1,431 | 1,435 | 1,127 | 1,064 | 1,121 | 1,037 |
| 779 | II | 272 | Friday | 1794 | 782 | 1,432 | 1,436 | 1,128 | 1,065 | 1,122 | 1,038 |
| 780 | II | 273 | Monday | 1797 | 783 | 1,435 | 1,439 | 1,131 | 1,068 | 1,125 | 1,041 |
| 781 | III | 273 | Tuesday | 1798 | 784 | 1,436 | 1,440 | 1,132 | 1,069 | 1,126 | 1,042 |
| 782 | III | 273 | Wednesday | 1799 | 785 | 1,437 | 1,441 | 1,133 | 1,070 | 1,127 | 1,043 |
| 783 | III | 273 | Thursday | 1800 | 786 | 1,438 | 1,442 | 1,134 | 1,071 | 1,128 | 1,044 |
| 784 | III | 273 | Friday | 1801 | 787 | 1,439 | 1,443 | 1,135 | 1,072 | 1,129 | 1,045 |
| 785 | III | 274 | Monday | 1804 | 788 | 1,442 | 1,446 | 1,138 | 1,075 | 1,132 | 1,048 |
| 786 | III | 274 | Tuesday | 1805 | 789 | 1,443 | 1,447 | 1,139 | 1,076 | 1,133 | 1,049 |
| 787 | III | 274 | Wednesday | 1806 | 790 | 1,444 | 1,448 | 1,140 | 1,077 | 1,134 | 1,050 |
| 788 | III | 274 | Thursday | 1807 | 791 | 1,445 | 1,449 | 1,141 | 1,078 | 1,135 | 1,051 |
| 789 | III | 274 | Friday | 1808 | 792 | 1,446 | 1,450 | 1,142 | 1,079 | 1,136 | 1,052 |
| 790 | III | 275 | Monday | 1811 | 793 | 1,449 | 1,453 | 1,145 | 1,082 | 1,139 | 1,055 |
| 791 | IV | 275 | Tuesday | 1812 | 794 | 1,450 | 1,454 | 1,146 | 1,083 | 1,140 | 1,056 |
| 792 | IV | 275 | **Wednesday — a sheet turned round so a room can see a date** | 1813 | 795 | 1,451 | 1,455 | 1,147 | 1,084 | 1,141 | 1,057 |
| 793 | IV | 275 | Thursday | 1814 | 796 | 1,452 | 1,456 | 1,148 | 1,085 | 1,142 | 1,058 |
| 794 | IV | 275 | Friday | 1815 | 797 | 1,453 | 1,457 | 1,149 | 1,086 | 1,143 | 1,059 |
| 795 | IV | 276 | Monday | 1818 | 798 | 1,456 | 1,460 | 1,152 | 1,089 | 1,146 | 1,062 |
| 796 | IV | 276 | Tuesday | 1819 | 799 | 1,457 | 1,461 | 1,153 | 1,090 | 1,147 | 1,063 |
| 797 | IV | 276 | **Wednesday — the Exchange, the fifty-eighth sitting** | 1820 | 800 | 1,458 | 1,462 | 1,154 | 1,091 | 1,148 | 1,064 |
| 798 | IV | 276 | Thursday | 1821 | 801 | 1,459 | 1,463 | 1,155 | 1,092 | 1,149 | 1,065 |
| 799 | IV | 276 | Friday | 1822 | 802 | 1,460 | 1,464 | 1,156 | 1,093 | 1,150 | 1,066 |
| 800 | IV | 277 | Monday | 1825 | 803 | 1,463 | 1,467 | 1,159 | 1,096 | 1,153 | 1,069 |
| 801 | V | 277 | Tuesday | 1826 | 804 | 1,464 | 1,468 | 1,160 | 1,097 | 1,154 | 1,070 |
| 802 | V | 277 | Wednesday | 1827 | 805 | 1,465 | 1,469 | 1,161 | 1,098 | 1,155 | 1,071 |
| 803 | V | 277 | Thursday | 1828 | 806 | 1,466 | 1,470 | 1,162 | 1,099 | 1,156 | 1,072 |
| 804 | V | 277 | Friday | 1829 | 807 | 1,467 | 1,471 | 1,163 | 1,100 | 1,157 | 1,073 |
| 805 | V | 277 | **Sunday — the one Sunday of this volume** | 1831 | 808 | 1,469 | 1,473 | 1,165 | 1,102 | 1,159 | 1,075 |
| 806 | V | 278 | Monday | 1832 | 809 | 1,470 | 1,474 | 1,166 | 1,103 | 1,160 | 1,076 |
| 807 | V | 278 | Tuesday | 1833 | 810 | 1,471 | 1,475 | 1,167 | 1,104 | 1,161 | 1,077 |
| 808 | V | 278 | Wednesday | 1834 | 811 | 1,472 | 1,476 | 1,168 | 1,105 | 1,162 | 1,078 |
| 809 | V | 278 | Thursday | 1835 | 812 | 1,473 | 1,477 | 1,169 | 1,106 | 1,163 | 1,079 |
| 810 | V | 278 | Friday | 1836 | 813 | 1,474 | 1,478 | 1,170 | 1,107 | 1,164 | 1,080 |
| 811 | VI | 279 | Monday | 1839 | 814 | 1,477 | 1,481 | 1,173 | 1,110 | 1,167 | 1,083 |
| 812 | VI | 279 | Wednesday | 1841 | 815 | 1,479 | 1,483 | 1,175 | 1,112 | 1,169 | 1,085 |
| 813 | VI | 280 | **Wednesday — the Exchange, the fifty-ninth sitting, the book OPENS** | 1848 | 816 | 1,486 | 1,490 | 1,182 | 1,119 | 1,176 | 1,092 |
| 814 | VI | 281 | Monday | 1853 | 817 | 1,491 | 1,495 | 1,187 | 1,124 | 1,181 | 1,097 |
| 815 | VI | 281 | Friday | 1857 | 818 | 1,495 | 1,499 | 1,191 | 1,128 | 1,185 | 1,101 |
| 816 | VI | 282 | Monday | 1860 | 819 | 1,498 | 1,502 | 1,194 | 1,131 | 1,188 | 1,104 |
| 817 | VI | 282 | Friday | 1864 | 820 | 1,502 | 1,506 | 1,198 | 1,135 | 1,192 | 1,108 |
| 818 | VI | 283 | **Wednesday — the institution tries to answer the notice with a reason to stay** | 1869 | 821 | 1,507 | 1,511 | 1,203 | 1,140 | 1,197 | 1,113 |
| 819 | VI | 283 | **Friday — a woman of about twenty-four puts one thing in front of him** | 1871 | 822 | 1,509 | 1,513 | 1,205 | 1,142 | 1,199 | 1,115 |
| 820 | VI | 284 | **Wednesday — the Exchange, the sixtieth sitting, the book does not open, and the volume closes** | 1876 | 823 | 1,514 | 1,518 | 1,210 | 1,147 | 1,204 | 1,120 |

### 1a. THE FORTY-EIGHT DAYS INSIDE THE SPAN THAT CARRY NO CHAPTER, ACCOUNTED FOR AS A RUN AND NOT AS A HOLE

**The span is 108 days and there are 60 chapters, so there are 48 days inside it that carry no chapter. The span runs from the Monday of week 269 to the Wednesday of week 284 and therefore holds fifteen whole weeks plus three days, which is thirty weekend days and seventy-eight weekdays. Exactly one weekend day carries a chapter — the Sunday of week 277, day 1831, Chapter 805 — so 29 weekend days carry no chapter, and 59 chapters fall on weekdays, so 78 − 59 = 19 weekday days carry no chapter, and 29 + 19 = 48.**

| Account | Days | Which |
| --- | --- | --- |
| Weekends inside the span | 29 | thirty, less the one Sunday that carries Chapter 805 |
| Weekdays inside the span | 19 | sixteen of them ordinary, and **three of them are collision days: 1778, 1842 and 1846** |
| **Total days with no chapter inside the span** | **48** | and 4 more before the volume opens, so 52 from the last day of Volume 15 to the last day of this one |

**THE SHAPE OF THE VOLUME IS IN THAT TABLE AND IT IS A DECISION, AND IT IS THE INVERSE OF VOLUME 15'S.** Volume 15 spread its first movement and its last and ran its four middle movements at ten consecutive weekdays with no gap at all. **This volume runs fifty chapters across sixty-eight days with one weekday hole, and then ten chapters across thirty-seven days with eighteen weekday holes, and nineteen of the nineteen holes are accounted for: one in Movement I and eighteen in Movement VI, and three of the nineteen are days the collision sweep took away and would otherwise have carried a chapter.** **The one in the first movement is not a rhythm at all; it is a Wednesday, and it is gone because two anchors added together equal it.** **The reason for the inversion is in the world and not in the pacing: Volume 15 opened on the confusion of nine minutes, and this one opens on a Tuesday in which nothing at all is wrong, and a book that ran a catastrophe and then an ordinary institution at one speed would not have noticed which was which.**

### 1b. Movement I's ten rows with the remaining eleven series, which a writer of Chapters 761 to 770 needs

| Ch | Day | Entry | 12 | 13 | 14 | 15 | 16 | 17 | 18 | Post | Copies | Sep | Chair |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 761 | 1769 | 764 | 1327 | 1278 | 1243 | 1222 | 1197 | 1179 | 1125 | 955 | 973 | 787 | 285 |
| 762 | 1770 | 765 | 1328 | 1279 | 1244 | 1223 | 1198 | 1180 | 1126 | 956 | 974 | 788 | 286 |
| 763 | 1771 | 766 | 1329 | 1280 | 1245 | 1224 | 1199 | 1181 | 1127 | 957 | 975 | 789 | 287 |
| 764 | 1772 | 767 | 1330 | 1281 | 1246 | 1225 | 1200 | 1182 | 1128 | 958 | 976 | 790 | 288 |
| 765 | 1773 | 768 | 1331 | 1282 | 1247 | 1226 | 1201 | 1183 | 1129 | 959 | 977 | 791 | 289 |
| 766 | 1776 | 769 | 1334 | 1285 | 1250 | 1229 | 1204 | 1186 | 1132 | 962 | 980 | 794 | 292 |
| 767 | 1777 | 770 | 1335 | 1286 | 1251 | 1230 | 1205 | 1187 | 1133 | 963 | 981 | 795 | 293 |
| 768 | 1779 | 771 | 1337 | 1288 | 1253 | 1232 | 1207 | 1189 | 1135 | 965 | 983 | 797 | 295 |
| 769 | 1780 | 772 | 1338 | 1289 | 1254 | 1233 | 1208 | 1190 | 1136 | 966 | 984 | 798 | 296 |
| 770 | 1783 | 773 | 1341 | 1292 | 1257 | 1236 | 1211 | 1193 | 1139 | 969 | 987 | 801 | 299 |

**The separation walks as `day − 982` and is 787 at Chapter 761, which is one hundred and twelve weeks and three days, and it is not shorter, and it was ended in a one-line box in a form in the second week of Volume 13, and it is walked on all ten rows of this table and on all sixty rows of the volume and is not stopped on any of them.**

**The place behind the woman's chair walks as `day − 1484` and is printed on ONE file of this movement and on no other. It is 285 days at Chapter 761 and 299 days at Chapter 770, and it is printed at Chapter 763, where it is 287 days, which is forty-one weeks to the day.**

---

## 2. The anchors, as a subtraction beside every value

| Series | Anchor day | Form | At 1769 | At 1876 |
| --- | --- | --- | --- | --- |
| The room off that service road | 362 | `day − 362` | 1407 | 1514 |
| The card in the rail | 358 | `day − 358` | 1411 | 1518 |
| The hardboard's twelfth line | 442 | `day − 442` | 1327 | 1434 |
| The hardboard's thirteenth line | 491 | `day − 491` | 1278 | 1385 |
| The hardboard's fourteenth line | 526 | `day − 526` | 1243 | 1350 |
| The hardboard's fifteenth line | 547 | `day − 547` | 1222 | 1329 |
| The hardboard's sixteenth line | 572 | `day − 572` | 1197 | 1304 |
| The hardboard's seventeenth line | 590 | `day − 590` | 1179 | 1286 |
| The hardboard's eighteenth line | 644 | `day − 644` | 1125 | 1232 |
| The hardboard's nineteenth line | 666 | `day − 666` | 1103 | 1210 |
| The hold of the man of about thirty-three | 729 | `day − 729` | 1040 | 1147 |
| The man of about fifty-one at the wall | 756 | `day − 756` | 1013 | 1120 |
| The ask | 672 | `day − 672` | 1097 | 1204 |
| The post at the corridor end | 814 | `day − 814` | 955 | 1062 |
| The nine hand copies of the front of a page | 796 | `day − 796` | 973 | 1080 |
| The separation | 982 | `day − 982` | 787 | 894 |
| **The place behind the woman's chair** | 1484 | `day − 1484` | 285 | **392** |

**The separation's anchor is 982 and has been since Volume 11. At day 1876 the column reads 894, and 894 days is a number of days that does not describe a separation, because the separation was not 894 days of anything: it ended in a one-line box in a form in the second week of Volume 13, and the number in that column has gone on being a correct subtraction since and does not know it.**

**THE PLACE BEHIND THE CHAIR IS THE ONE FIGURE IN THIS FILE THAT IS EXACTLY A WHOLE NUMBER OF WEEKS ON THE LAST PAGE OF THIS VOLUME, AND 392 IS FIFTY-SIX WEEKS TO THE DAY. No chapter of this volume prints it. It is printed here so that a later pass can check the claim that the count ran on, and it is printed here and nowhere else in a number.**

---

## 3. The Exchange, computed from this file and not from any chapter

| Sitting | Chapter | Day | Week | Count announced | Of which correspond | Book before | Book after | Tin |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| the fifty-sixth | 760 | 1764 | 268 | 61 | 56 | 65 | 66 | 73 |
| the fifty-seventh | 777 | 1792 | 272 | 62 | 57 | 66 | 66 | 73 |
| the fifty-eighth | 797 | 1820 | 276 | 63 | 58 | 66 | 66 | 73 |
| the fifty-ninth | 813 | 1848 | 280 | 64 | 59 | 66 | 67 | 73 |
| the sixtieth | 820 | 1876 | 284 | 65 | 60 | 67 | 67 | 73 |

**A count is announced at a sitting and on no other day, and the count goes up by one at every sitting whether the book opens or not. The correspond figure is the count less the five that predate the book on a sheet she has never shown anybody. The book opens only when a caller says a thing to her face, and this volume's pattern is shut, shut, open, shut, and the pattern is not a rule, is not written anywhere, is not evidence of anything, and may not be described in a chapter as a change in her. The difference between the book and the tin is not a number and is never printed as one, and none of the four is convertible into another, and the ninth chair is against the wall with its back to the room and does not move in this volume and its mover is not named. The place behind her chair is empty on all sixty days, is twenty-nine weeks and six days old at Chapter 761 and fifty-six weeks to the day old at Chapter 820, and neither figure is printed in a load book and the difference between them is never printed as a number.**

**MOVEMENT I HAS NO SITTING AND THEREFORE NO COUNT, AND THIS IS THE FIRST MOVEMENT IN THIS MANUSCRIPT TO SAY SO OUT LOUD.** Chapter 763 is a Wednesday and the room is open and about nine people are in it and **no number is said, because a number is said at a sitting and a sitting is a Wednesday of every fourth week and this was not one.** Volume 15 had two Wednesdays inside a movement that were not sittings and neither of them said anything about the fact; this volume prints the fact once and does not return to it.

---

## 4. The two-sided interval series, and how a writer renders one

**Every series printed in weeks and days is printed twice: once in the load book's row and once in the sentence of the narration above it, and both are converted by `weeks × 7 + days` and required equal. The weeks-and-days phrase is regenerated from the figure and compared character for character.**

**Test the attachment from the end of the `days` token and not from the end of the numeral, and test in both directions, because a compliant rendering in this house may put the weeks form first: "one day short of a hundred and ten weeks" and "a hundred and ten weeks and one day" are both house renderings and a walk that reads only the second will return a clean result on a page that has the first. A figure that is an exact number of weeks is rendered with the words *to the day* and the word *short* is not used.**

**AND THE SINGULAR: a day component of one is *one day* and not *one days*, and a component of zero is *to the day* and not *zero days*, and a component of two or more takes the plural. A generator that prints the plural on every non-zero component produces a walk that is correct on its arithmetic and wrong on its English, and the arithmetic check will not see it.**

**AND THE PARSER THAT HAS FAILED NINE TIMES IN THIS REPOSITORY MUST BE ASSERTED BEFORE IT WALKS ANYTHING.** The recorded failures are a parser with no tens slot; a shape test applied to the weeks run instead of the days run; a tail rule that let a walk re-enter inside every figure; a walk that bridged a colon; a grammar test that read the total value instead of the day component; an orphan scan whose class two was *any word that is not a number*; a tens table built by enumerating words against an offset; a clause boundary not enforced across punctuation; and an ordinal generator wrong in six consecutive ways. **The assertion that catches all nine is the same and it is twenty-five known renderings checked before the parser is pointed at a chapter, and Movement I's numbers in the tables above were produced by a generator asserted on those renderings first, which is the tenth occurrence of this instrument being wrong before the text was and the first one caught before it was pointed at anything.**

Movement I's interval renderings, for the walk and not for reuse as sentences:

| Ch | Room | W and d | Card | W and d | Nineteen | W and d | Hold | W and d | Fifty-one | W and d | Ask | W and d | Copies | W and d | Sep | W and d |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 761 | 1407 | 201 w 0 d | 1411 | 201 w 4 d | 1103 | 157 w 4 d | 1040 | 148 w 4 d | 1013 | 144 w 5 d | 1097 | 156 w 5 d | 973 | 139 w 0 d | 787 | 112 w 3 d |
| 762 | 1408 | 201 w 1 d | 1412 | 201 w 5 d | 1104 | 157 w 5 d | 1041 | 148 w 5 d | 1014 | 144 w 6 d | 1098 | 156 w 6 d | 974 | 139 w 1 d | 788 | 112 w 4 d |
| 763 | 1409 | 201 w 2 d | 1413 | 201 w 6 d | 1105 | 157 w 6 d | 1042 | 148 w 6 d | 1015 | 145 w 0 d | 1099 | 157 w 0 d | 975 | 139 w 2 d | 789 | 112 w 5 d |
| 764 | 1410 | 201 w 3 d | 1414 | 202 w 0 d | 1106 | 158 w 0 d | 1043 | 149 w 0 d | 1016 | 145 w 1 d | 1100 | 157 w 1 d | 976 | 139 w 3 d | 790 | 112 w 6 d |
| 765 | 1411 | 201 w 4 d | 1415 | 202 w 1 d | 1107 | 158 w 1 d | 1044 | 149 w 1 d | 1017 | 145 w 2 d | 1101 | 157 w 2 d | 977 | 139 w 4 d | 791 | 113 w 0 d |
| 766 | 1414 | 202 w 0 d | 1418 | 202 w 4 d | 1110 | 158 w 4 d | 1047 | 149 w 4 d | 1020 | 145 w 5 d | 1104 | 157 w 5 d | 980 | 140 w 0 d | 794 | 113 w 3 d |
| 767 | 1415 | 202 w 1 d | 1419 | 202 w 5 d | 1111 | 158 w 5 d | 1048 | 149 w 5 d | 1021 | 145 w 6 d | 1105 | 157 w 6 d | 981 | 140 w 1 d | 795 | 113 w 4 d |
| 768 | 1417 | 202 w 3 d | 1421 | 203 w 0 d | 1113 | 159 w 0 d | 1050 | 150 w 0 d | 1023 | 146 w 1 d | 1107 | 158 w 1 d | 983 | 140 w 3 d | 797 | 113 w 6 d |
| 769 | 1418 | 202 w 4 d | 1422 | 203 w 1 d | 1114 | 159 w 1 d | 1051 | 150 w 1 d | 1024 | 146 w 2 d | 1108 | 158 w 2 d | 984 | 140 w 4 d | 798 | 114 w 0 d |
| 770 | 1421 | 203 w 0 d | 1425 | 203 w 4 d | 1117 | 159 w 4 d | 1054 | 150 w 4 d | 1027 | 146 w 5 d | 1111 | 158 w 5 d | 987 | 141 w 0 d | 801 | 114 w 3 d |

**THE WHOLE-NUMBER-OF-WEEKS ROWS, WHICH IS THE RENDERING THE WALK CHECKS AND WHICH A GENERATOR GETS WRONG BY PRINTING *zero days*.** The rows of Movement I, walked from the anchors before this prompt was written and to be walked again and not assumed: **761 has three (room, sixteenth line, copies); 762 has none; 763 has four (eighteenth line, fifty-one, ask, and the chair, which is printed on one file in the whole movement and is not in a load book); 764 has seven (card, twelfth, thirteenth, fourteenth, fifteenth, nineteenth, hold); 765 has three (seventeenth line, post, separation); 766 has three (room, sixteenth line, copies); 767 has none; 768 has seven (card, twelfth, thirteenth, fourteenth, fifteenth, nineteenth, hold); 769 has three (seventeenth line, post, separation); 770 has three (room, sixteenth line, copies).** **Every whole-number figure is rendered with the words *to the day*, a day component of one is *one day*, a component of zero takes *to the day*, and a component of two or more takes the plural. The word *short* is not used anywhere in this volume.** **The printed vector on Movement I's ten files is therefore 3, 0, 3, 7, 3, 3, 0, 7, 3, 3, and `to the day` is at zero on Chapters 762 and 767 and on no other file of this movement.**

**A NOTE ON THAT TABLE, WHICH IS THE FINDING OF THE FOUR PRECEDING VOLUMES: the whole-week count above is a figure a generator produced, and the authoritative test is not the count and it is the per-cell modulo, because the prose also prints figures that this table does not carry.** The count was corrected by hand in an earlier volume for exactly this reason and the correction was the only correct procedure available.

---

## 5. Collision sweep, and the reading that is required before it is trusted

**Sweep: for each of the seventeen numerical series on each of the sixty rows, test the value against the seventeen anchors, and report every hit where the value is not its own anchor. A hit is the day equalling the sum of two distinct anchors, so the whole sweep can be computed as a set of anchor-pair sums before any chapter is read, and that is how the four rows below were found.**

**Volume 16's chapter-day sweep returns NOTHING. Zero chapter-days out of sixty, on all seventeen series. The reason is arithmetic and not craft: two of the four sums fall on days that the day map was then bent around, and one of those two bends the shape of the first movement and the other bends the shape of the last.**

| Sum | Day | Weekday | Which | Carries |
| --- | --- | --- | --- | --- |
| 796 + 982 | 1778 | Wednesday of week 270 | the nine hand copies against the separation's | **no chapter, and it may never be given one — and this is why Movement I's ten days are not ten consecutive weekdays** |
| 814 + 982 | 1796 | Sunday of week 272 | the post at the corridor end against the separation's | no chapter, and it is a Sunday besides |
| 358 + 1484 | 1842 | Thursday of week 279 | the card in the rail against the place behind the woman's chair | **no chapter, and it is one of the two days that open the seven-day hole in Movement VI** |
| 362 + 1484 | 1846 | Monday of week 280 | the room off that service road against the place behind the woman's chair | **no chapter — and the consequence is that Chapter 812 at day 1841 and Chapter 813 at day 1848 are a week apart** |

**THE 1778 PAIR IS THE FIFTH TIME THE SEPARATION SERIES HAS COLLIDED IN THIS MANUSCRIPT AND IT IS A WEDNESDAY, WHICH IS A SITTING DAY, AND IT CARRIES NO CHAPTER AND IS NOT A SITTING.** **The 1842 and 1846 pairs are the first time the place behind the woman's chair has collided with anything, and they land seven and eight days apart, and they are why Movement VI has the widest hole in the volume in the middle of it rather than at the end of it.** A collision is a coincidence between two integers and says nothing whatever about either object.

**And the row-side walk is not sufficient on its own, which is the finding of the last five volumes: a table can be correct on its day, its week, its weekday and its entry and wrong in eleven of its seventeen series columns, and only the page-side walk sees that.** Both halves are required on every volume of this manuscript, and a pass that runs one half has run half an instrument.

---

## 6. THE FIGURES THE SIX MOVEMENTS WALK, AND WHAT EACH MOVEMENT MAY NOT PRINT

| Movement | Chapters | Days | Span | Weekday gaps | Sittings | Panel | Sunday |
| --- | --- | --- | --- | --- | --- | --- | --- |
| I | 761–770 | 1769–1783 | 14 | **one, and it is the collision day 1778** | **none, and no number is said on any of the ten days** | none | none |
| II | 771–780 | 1784–1797 | 13 | none | the fifty-seventh, and the book does not open | Chapter 775, and its marker | none |
| III | 781–790 | 1798–1811 | 13 | none | none | none | none |
| IV | 791–800 | 1812–1825 | 13 | none | the fifty-eighth | none | none |
| V | 801–810 | 1826–1836 | 10 | none | none | none | Chapter 805 |
| VI | 811–820 | 1839–1876 | 37 | **eighteen, and three of them across the volume are collision days** | the fifty-ninth, and the book OPENS; the sixtieth, and it does not | none | none |

**The about-two shutter form is on Chapter 805 alone in the whole of this volume, and the detector returns one Sunday and one only. The count of the leaves on a printed sheet is at zero in every movement. The number of doors a sheet is at is at zero in every movement. The nine numbers on nine sheets are not added in any movement. The word on the ninth of the nine sheets is not said in any movement.** Movements I, II and III place no use of the word `Crown` in any form, and Movements IV, V and VI permit only `the Crown Key`, `the Crown Vault`, `the Crown Clause` and `the Crown Root Interface`, with the place name Crown Terrace remaining a place and no sentence joining it to any of the other four.

**The whole-number-of-weeks figures on Movements II to VI are the business of their own prompts, which must walk them before they are written and not after. Movement I's vector is printed at section 4 and is 3, 0, 3, 7, 3, 3, 0, 7, 3, 3.**

---

## 7. THE DEBTS AT THE CLOSE OF VOLUME 15, CARRIED FORWARD UNCHANGED AND CANCELLED BY NOTHING

**This section is a list and not a plan. It exists because the Volume 15 close closed nothing, and everything below was open at Chapter 760, and a Volume 16 writer inherits all of it. `outline/volume-16.md` is the document that decides what this volume spends, and it spends none of the following.**

**The seventeen things Volume 14 left with the manuscript, none cancelled:** the printed paragraph on the back of a page of paper and the fact underneath it; the card, a name and a let house; four rooms in four districts that have each refused a merge; the three rooms in four towns; nine hand copies uncompared; nine keys needed and two existing; four bars across the inside of four doors in four buildings in four towns; the licensor, the field and the master's fifth line, which is blank; the second visitor column on a company form; the pale card in a gate hut; the plate of iron with four slots under a floor in the first of the four towns; the rota man's inspection, now about four years old; the returned sheet in the fourth tray, about four years old, the only copy in the world; the two people who cannot show which answer they gave; the heading on the strip, which is a plant and is not resolved; the fracture in the Conductor's Choir, noticed by four people in four places and said to nobody, one of whom is not on any page of Volume 15; and the nine sentences.

**The forty-one debts open at the close of Volume 15, none cancelled by that close and none cancelled here:** the answer to Volume 08's question, which was a chair, and whether it holds, which is not a question a chapter can answer; Iona Sorn, fifty-three, in public custody, who has not said whether she will work on repairs under somebody else's hand and under a review she does not choose, and to whom nobody has offered it again; about nine people who were part of the Choir and are not in this city and have not been asked, one of whom had a town's name written on the back of a hand and told nobody; the woman of about thirty-six who works a release in a garage on a road in a second district and who made the first exit in a bay without being asked and does not know; the two people who cannot show which answer they gave, who are not asked and not told; the nine hand copies, eight of them unfinished, the first disagreement in the fourth line still not found, and no two of the nine compared on any of Volume 15's sixty days; the woman of about thirty and the eighth of eight; the man of about fifty-one, his back room and his kettle, not asked and not unhappy about it; the man on a landing and the woman of about thirty-one who takes messages for a pound a week; the man of about thirty-four's hands; the nine sentences, never collected, compared, added, totalled or filed; the three pieces of paper in three rooms, the third of which is eight words and is wrong and was not changed; the nine words on a card about four inches by two in a woman's own name, unsoftened; the four bars across the inside of four doors; the heading on the strip; the rota man's inspection; the returned sheet in the fourth tray; the licensor, the field and the master's fifth line; the pale card in a gate hut; the hard backed book; the folder on a shelf above a kettle; the plate of iron with four slots under a floor in the first of the four towns; the four towns; the nine rooms and the one route nobody can travel; the Crown Root Interface in three pieces on a bench in a workshop off Lattice Ward, with a maker's mark on it that is upside down; the separation, ended, whose figure is still walking and describes nothing; the correct-things-that-change-nothing register at three; the four arrival cells, empty for the eighteenth consecutive time; the four free checks, withdrawn as evidence; the orphaned-hedge scan, struck on both classes; the nine non-conforming counter rows at Chapters 701 to 709.

**THE THREE VOLUME CLOSES THAT HAVE NOT RUN, AND IT IS THREE AND NOT TWO.** `workspace/volume-12/VOLUME-CLOSE.md`, `workspace/volume-13/VOLUME-CLOSE.md` and `workspace/volume-14/VOLUME-CLOSE.md` are plain files at their volume roots and the controller's selection rule finds only a `PROMPT.md`, which is why the Volume 15 close is a directory and those three never ran. **The third is the outstanding one, because the seventeen debts of section 7 of the Volume 15 calendar file sit on it, and section 6 of `workspace/volume-14/ARITHMETIC-AND-CALENDAR.md` is still a reservation.** Controller-owned and untouched by any writing pass. **A Volume 16 chapter may not resolve any of these three closes' work and may not describe any plant as a rehearsal for anything.**

**AND WHAT VOLUME 16 SPENDS, WHICH IS ONE THING, NAMED, AND IT IS NOT ON THE LIST ABOVE.** It spends `outline/ending.md` line 79, written before Volume 15 and unpaid at its close: *The Civic Commons begins its first ordinary day. It is underfunded, crowded, and immediately challenged by a district that wants to leave.* **Nothing else on the list above is spent, opened, resolved, softened or mentioned by a Chapter of Movement I, and no chapter of any movement of this volume may compare two of the nine sentences or open the ring binder.**

---

## 8. THE FOUR ARRIVAL CELLS, AND WHY THEY ARE EMPTY AGAIN

**The four arrival cells are the four measurements a movement's ten files must be given by a second pass before the movement can claim an arrival rather than a reconstruction. They have been empty eighteen consecutive times, in Volumes 12, 13, 14 and 15, and this is the last volume in which they can be empty.**

**They will be empty a nineteenth time at the end of Movement I unless a second pass is run on these ten files after they are written and repaired and before the batch is closed. `outline/volume-15.md` states each of Volume 15's six arrivals in a sentence of prose and there is nothing on disk for a finished page to be tested against, and `outline/volume-16.md` states its movements in the same way and has the same defect, and the defect is the plan of record's and not this file's.** **A cell that cannot be measured is printed empty and is not approximated, and a reconstructed arrival is the finished files measured twice and is not an arrival.** The standing rule, earned by the Volume 15 close at a cost of a whole review cycle, is that a state file is written after the last measurement or not written at all, and this file is a plan written before any measurement existed.

---

## 9. THE VOLUME 16 CLOSE

**RESERVED. WRITTEN BY THE CLOSE, WHICH IS THE ONLY PASS THAT MAY WRITE IT. SECTIONS 1 TO 8 ARE UNTOUCHED BY IT. WHERE A SECTION CARRIES A FIGURE THE CLOSE MEASURED DIFFERENTLY, BOTH ARE PRINTED AND THE ONE THAT GOVERNS IS NAMED.**
