# Arithmetic and calendar — Volume 15

**`workspace/volume-15/ARITHMETIC-AND-CALENDAR.md`, at the volume root, beside `batch-0001/`, and not inside any phase directory. It is a volume-level working file and not a phase: it holds no `PROMPT.md` and no marker, so the controller's selection rule — the first directory under `workspace/` holding a `PROMPT.md` and no `.done` — is unaffected by it. `workspace/volume-06/ARITHMETIC-AND-CALENDAR.md` through `workspace/volume-14/ARITHMETIC-AND-CALENDAR.md` are the precedents and sit in the same place.**

**It was written with `outline/volume-15.md` and before Chapter 701. Sections 1 to 6 and 8 are a plan of figures and not a table read back off chapters, and every number below is a day number minus a named anchor day and can be recomputed by anybody in about a minute. Section 7 is a list of debts carried forward from Volume 14 and it plans nothing. Section 9 is reserved for the Volume 15 close and no writing pass before it may write it.**

**It is a table and a set of series. It is not a prompt, it plans nothing, and it derives nothing.**

**Four rules, and they are the same four as the nine files before it.**

1. **No day number may be printed in a chapter.** No month-name, no month-date, no day-date, no year. The only calendar nouns permitted are the season words, the week and the day inside the week. **All interval figures are spelled out in words, and a figure that is an exact number of weeks is rendered with the words *to the day* and is not rendered with the word *short*.** No chapter of this volume prints how far away a town is, and a town is described by how long the bus takes or by nothing at all.
2. **A day is assigned only by section 1 of this file.** Where this file and a live batch prompt disagree on a day, **the batch prompt is right for its ten days and this file is right for the run**, and a batch prompt that disagrees with the table below on a day is a defect to be corrected in place and recorded.
3. **Weeks run Monday to Sunday. The detector is inherited unchanged and is `week = (day − 502) // 7 + 88` and the weekday is `wd = (day − 502) mod 7` against Monday-first, and the Monday of week _n_ is `7 × n − 114`.** **A value that disagrees with the detector is the value that is wrong.** **A pass that writes the Monday as `7 × W − 682` has dropped two digits and will produce a Monday four hundred and ninety days early, and that exact error was found in a Volume 12 prompt, and this file repeats the warning because the warning is what stopped it.**
4. **The interval map's two-day offset from the Monday of week thirty-one is inherited and is not to be re-derived from the anchor.** No chapter in this manuscript has ever printed a day number, so no prose depends on any of it.

---

## 0. What this file inherits

### 0.1 THE CHAIN, CHECKED ONCE AND NOT RE-DERIVED

**The inherited anchors are printed at the head of `outline/volume-15.md` and are not duplicated here, because a table of anchors is a second place in this repository a figure can be copied from and the seventh time that has happened has been a defect. The chain gives 1652 as the Wednesday of week two hundred and fifty-two, which is the day Volume 14 closed on, and 1657 as the Monday of the week after, and that is the whole of the check.** The arithmetic is `7 × 252 − 114 = 1650` and the Wednesday of week 252 is 1650 + 2 = 1652, and `7 × 253 − 114 = 1657` and the Monday of week 253 is 1650 + 7 = 1657.

### 0.2 THE DAY ZERO, MADE EXPLICITLY AND PRINTED, WITH THE OPENINGS THAT WERE REFUSED

**Chapter 701 is day 1657, the Monday of week two hundred and fifty-three. In one sentence: Volume 15 opens on the first Monday after the Wednesday Volume 14 closed on, and 1657 is 1652 + 5, and 1652 is the Wednesday of week 252, and 1650 is the Monday of week 252, and 1657 is 1650 + 7.**

**It is a decision and not a consequence. `outline/ending.md` gives the Hush to Chapter 701 and the cascade to Chapters 701 to 720, and a volume that opens on a Wednesday would hand its first chapter to a day with a rule of its own, which is what Volume 13 said out loud when it refused one. Four other openings were available and were not taken: 1653 is a Thursday and is a working day, which is the conventional choice and which would have put the biggest event in fifteen volumes on a Thursday; 1654 is a Friday and would have put the nine minutes on a Friday, which is a day this city does things on, and Chapter 707 is a Friday and already has a sheet in it; 1655 and 1656 are a Saturday and a Sunday and this manuscript does not open a volume at a weekend; and 1659 is the Wednesday of the same week, which is Chapter 702 and which would have cost the volume its first page for the sake of a rule.**

**One thing is on this opening day that a writer of this volume has to know and cannot get from a chapter: a doctor of fifty-three has been under this city since a Thursday in the previous week and has armed what was left of the pattern, and the man of twenty-two does not know it, is not told it in Movement I, and no page of Movements I to IV shows what is behind a wall.**

### 0.3 WHAT VOLUME 14 HANDOVER THIS FILE'S FIGURES DEPEND ON, RESTATED WITH ITS SUBTRACTION BESIDE IT

| Figure | Arithmetic | Value |
| --- | --- | --- |
| Chapter 700 | the Wednesday of week 252, 7 × 252 − 114 + 2 | 1652 |
| Chapter 701 | 1652 + 5, and the Monday of week 253, 7 × 253 − 114 | 1657 |
| The first sitting in this volume | 1657 + 23, and the Wednesday of week 256, 7 × 256 − 114 + 2 | 1680 |
| The last sitting and the close | 7 × 268 − 114 + 2 | 1764 |
| The whole of Volume 15 | 1764 − 1657 | 107 days |
| The whole of Volume 15 inclusive of both ends | 1764 − 1657 + 1 | 108 days |
| The first sitting to the close | 1764 − 1680 | 84 days |
| The place behind the woman's chair at Chapter 701 and at Chapter 760 | 1657 − 1484, and 1764 − 1484 | 173 days, and 280 days |

**The place behind the woman's chair in the room above a line in Saltmarket was empty on the Wednesday of Chapter 700 and had been empty since the Wednesday of Chapter 628, which is day 1484. The two figures this file needs are 173 days at Chapter 701 and 280 days at Chapter 760, and 280 is forty weeks to the day and 173 is twenty-four weeks and five days, and the difference between them is never printed as a number in a load book.**

### 0.4 THE FOUR FREE CHECKS, WITH THEIR SIGNS, IN FULL

A check that publishes its clean set and not its limits cannot be told apart from a check that was never run, so all four are printed here with their limits and their signs, and all four are walked on all sixty rows of section 1.

| Check | Expression | Constant | Sign as printed |
| --- | --- | --- | --- |
| The card-minus-room invariant | `(day − 358) − (day − 362)` | 4 | {4} |
| The fourteen-less-fifteen | `(day − 526) − (day − 547)` | 21 | {21} |
| The fifty-one-less-hold | `(day − 756) − (day − 729)` | −27 | {−27} |
| The eighteen-less-sixteen | `(day − 644) − (day − 572)` | −72 | {−72} |

**Walked on all sixty rows of section 1 before Chapter 701 was written, from the anchor table and not from a chapter: zero off-row on all four, sixty rows each, two hundred and forty cells.**

### 0.5 THE SPENT-AGE CLASS GETS AN INSTRUMENT AND NOT ONLY A PROHIBITION

**For each file: extract every occurrence of a spent age, take the noun phrase it sits in, and record whether a person is the subject of it. A spent age on a person established in this manuscript is permitted and is canon. A spent age on a new person is a finding and not a permission. A raw substring count of the spent ages is not an instrument, because a new person can carry a spent age any number of times and a raw count cannot see who is carrying it.** **Movement I of this volume names two new people and neither is given a spent age, and the twenty-year-old prohibition in a city-wide volume is that a person who is doing a job during a cascade is described by the job.**

### 0.6 THE TWO INHERITED FIGURES WHOSE SUBJECT CHANGES AND WHOSE ARITHMETIC DOES NOT

**The separation walks as `day − 982` in every volume and the anchor does not move. What changes in this volume is what it is used for.** In Volume 14 it was the standing proof of the house's own rule, because an arrangement that lapsed in a form on a Thursday was a second instance of the same shape with no figure on it. **In this volume it is the standing proof of a different rule, and the sentence that joins the two is again the sentence this volume may not write: about four hundred people in this city signed a form whose box said what the last approved answer was, and a separation that ended in a one-line box in a form in Volume 13 is the same shape, and the number in the separation column has gone on being a correct subtraction since and does not know it.** The column headed `Sep` in section 1 is therefore a count of days that does not describe anything, and a writer who stops printing it has broken the instrument.

**The temporary mapping is not a series and is not one now, and neither is the interface.** The mapping had a number on it — eleven days — and a date and a signature, and **a duration and an age are different figures and the two are never printed in the same column and are not to be.** What lapsed on day 1538 was a sheet with three ruled lines. **What did not lapse is the plate in the cabinet, and there is no row for it in section 1 and there is no anchor for it and there will not be one, and a writer who wants a figure for it is asking for the wrong kind of thing.**

**The Exchange's book is a series of a different kind.** It is at sixty-four lines entering this volume, it SHUTS at the fifty-third sitting and OPENS at the fifty-fourth, SHUTS at the fifty-fifth and OPENS at the fifty-sixth, and it closes the volume at sixty-six. **The pattern is shut, open, shut, open, and it is not derivable from Volume 12's shut, shut, open, shut, Volume 13's shut, open, open, shut or Volume 14's open, shut, open, shut, and the book standing at sixty-four lines on the first day of this volume is a figure and the two lines that go in over a hundred and seven days are two figures, and none of the three is convertible into the tin.**

---

## 1. The day map, all sixty chapters, with the load-book entry on each row

| Ch | Mv | Week | Day | Day no. | Entry | Room | Card | 19 | Hold | Ask | 51 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 701 | I | 253 | **Monday — the volume opens, and the nine minutes** | 1657 | 704 | 1,295 | 1,299 | 991 | 928 | 985 | 901 |
| 702 | I | 253 | Wednesday | 1659 | 705 | 1,297 | 1,301 | 993 | 930 | 987 | 903 |
| 703 | I | 253 | Thursday | 1660 | 706 | 1,298 | 1,302 | 994 | 931 | 988 | 904 |
| 704 | I | 253 | **Friday — the hands** | 1661 | 707 | 1,299 | 1,303 | 995 | 932 | 989 | 905 |
| 705 | I | 254 | Monday | 1664 | 708 | 1,302 | 1,306 | 998 | 935 | 992 | 908 |
| 706 | I | 254 | Thursday | 1667 | 709 | 1,305 | 1,309 | 1,001 | 938 | 995 | 911 |
| 707 | I | 254 | **Friday — the sheet with four steps on it** | 1668 | 710 | 1,306 | 1,310 | 1,002 | 939 | 996 | 912 |
| 708 | I | 255 | Monday | 1671 | 711 | 1,309 | 1,313 | 1,005 | 942 | 999 | 915 |
| 709 | I | 255 | **Friday — the sixth room's six words** | 1675 | 712 | 1,313 | 1,317 | 1,009 | 946 | 1,003 | 919 |
| 710 | I | 256 | **Wednesday — the Exchange, the fifty-third sitting, the book SHUTS** | 1680 | 713 | 1,318 | 1,322 | 1,014 | 951 | 1,008 | 924 |
| 711 | II | 256 | Thursday | 1681 | 714 | 1,319 | 1,323 | 1,015 | 952 | 1,009 | 925 |
| 712 | II | 256 | Friday | 1682 | 715 | 1,320 | 1,324 | 1,016 | 953 | 1,010 | 926 |
| 713 | II | 257 | Monday | 1685 | 716 | 1,323 | 1,327 | 1,019 | 956 | 1,013 | 929 |
| 714 | II | 257 | Tuesday | 1686 | 717 | 1,324 | 1,328 | 1,020 | 957 | 1,014 | 930 |
| 715 | II | 257 | Wednesday | 1687 | 718 | 1,325 | 1,329 | 1,021 | 958 | 1,015 | 931 |
| 716 | II | 257 | Thursday | 1688 | 719 | 1,326 | 1,330 | 1,022 | 959 | 1,016 | 932 |
| 717 | II | 257 | Friday | 1689 | 720 | 1,327 | 1,331 | 1,023 | 960 | 1,017 | 933 |
| 718 | II | 258 | Monday | 1692 | 721 | 1,330 | 1,334 | 1,026 | 963 | 1,020 | 936 |
| 719 | II | 258 | Tuesday | 1693 | 722 | 1,331 | 1,335 | 1,027 | 964 | 1,021 | 937 |
| 720 | II | 258 | Wednesday | 1694 | 723 | 1,332 | 1,336 | 1,028 | 965 | 1,022 | 938 |
| 721 | III | 258 | Thursday | 1695 | 724 | 1,333 | 1,337 | 1,029 | 966 | 1,023 | 939 |
| 722 | III | 258 | Friday | 1696 | 725 | 1,334 | 1,338 | 1,030 | 967 | 1,024 | 940 |
| 723 | III | 259 | Monday | 1699 | 726 | 1,337 | 1,341 | 1,033 | 970 | 1,027 | 943 |
| 724 | III | 259 | Tuesday | 1700 | 727 | 1,338 | 1,342 | 1,034 | 971 | 1,028 | 944 |
| 725 | III | 259 | Wednesday | 1701 | 728 | 1,339 | 1,343 | 1,035 | 972 | 1,029 | 945 |
| 726 | III | 259 | **Thursday — she is in a room for nine seconds** | 1702 | 729 | 1,340 | 1,344 | 1,036 | 973 | 1,030 | 946 |
| 727 | III | 259 | **Friday — the register moves from two to three** | 1703 | 730 | 1,341 | 1,345 | 1,037 | 974 | 1,031 | 947 |
| 728 | III | 260 | Monday | 1706 | 731 | 1,344 | 1,348 | 1,040 | 977 | 1,034 | 950 |
| 729 | III | 260 | Tuesday | 1707 | 732 | 1,345 | 1,349 | 1,041 | 978 | 1,035 | 951 |
| 730 | III | 260 | **Wednesday — the Exchange, the fifty-fourth sitting, the book OPENS** | 1708 | 733 | 1,346 | 1,350 | 1,042 | 979 | 1,036 | 952 |
| 731 | IV | 260 | Thursday | 1709 | 734 | 1,347 | 1,351 | 1,043 | 980 | 1,037 | 953 |
| 732 | IV | 260 | Friday | 1710 | 735 | 1,348 | 1,352 | 1,044 | 981 | 1,038 | 954 |
| 733 | IV | 261 | Monday | 1713 | 736 | 1,351 | 1,355 | 1,047 | 984 | 1,041 | 957 |
| 734 | IV | 261 | Tuesday | 1714 | 737 | 1,352 | 1,356 | 1,048 | 985 | 1,042 | 958 |
| 735 | IV | 261 | **Wednesday — a person who cannot show a decision is treated as having made none** | 1715 | 738 | 1,353 | 1,357 | 1,049 | 986 | 1,043 | 959 |
| 736 | IV | 261 | Thursday | 1716 | 739 | 1,354 | 1,358 | 1,050 | 987 | 1,044 | 960 |
| 737 | IV | 261 | **Friday — his name is said once** | 1717 | 740 | 1,355 | 1,359 | 1,051 | 988 | 1,045 | 961 |
| 738 | IV | 262 | Monday | 1720 | 741 | 1,358 | 1,362 | 1,054 | 991 | 1,048 | 964 |
| 739 | IV | 262 | Tuesday | 1721 | 742 | 1,359 | 1,363 | 1,055 | 992 | 1,049 | 965 |
| 740 | IV | 262 | Wednesday | 1722 | 743 | 1,360 | 1,364 | 1,056 | 993 | 1,050 | 966 |
| 741 | V | 262 | Thursday | 1723 | 744 | 1,361 | 1,365 | 1,057 | 994 | 1,051 | 967 |
| 742 | V | 262 | Friday | 1724 | 745 | 1,362 | 1,366 | 1,058 | 995 | 1,052 | 968 |
| 743 | V | 263 | Monday | 1727 | 746 | 1,365 | 1,369 | 1,061 | 998 | 1,055 | 971 |
| 744 | V | 263 | **Tuesday — the volume's one panel and its one marker** | 1728 | 747 | 1,366 | 1,370 | 1,062 | 999 | 1,056 | 972 |
| 745 | V | 263 | Thursday | 1730 | 748 | 1,368 | 1,372 | 1,064 | 1,001 | 1,058 | 974 |
| 746 | V | 263 | Friday | 1731 | 749 | 1,369 | 1,373 | 1,065 | 1,002 | 1,059 | 975 |
| 747 | V | 263 | **Sunday — the one Sunday of this volume** | 1733 | 750 | 1,371 | 1,375 | 1,067 | 1,004 | 1,061 | 977 |
| 748 | V | 264 | **Monday — she makes him the bargain** | 1734 | 751 | 1,372 | 1,376 | 1,068 | 1,005 | 1,062 | 978 |
| 749 | V | 264 | **Tuesday — the chisel** | 1735 | 752 | 1,373 | 1,377 | 1,069 | 1,006 | 1,063 | 979 |
| 750 | V | 264 | **Wednesday — the Exchange, the fifty-fifth sitting, the book SHUTS** | 1736 | 753 | 1,374 | 1,378 | 1,070 | 1,007 | 1,064 | 980 |
| 751 | VI | 264 | Thursday | 1737 | 754 | 1,375 | 1,379 | 1,071 | 1,008 | 1,065 | 981 |
| 752 | VI | 265 | Monday | 1741 | 755 | 1,379 | 1,383 | 1,075 | 1,012 | 1,069 | 985 |
| 753 | VI | 265 | Friday | 1745 | 756 | 1,383 | 1,387 | 1,079 | 1,016 | 1,073 | 989 |
| 754 | VI | 266 | Wednesday | 1750 | 757 | 1,388 | 1,392 | 1,084 | 1,021 | 1,078 | 994 |
| 755 | VI | 266 | Friday | 1752 | 758 | 1,390 | 1,394 | 1,086 | 1,023 | 1,080 | 996 |
| 756 | VI | 267 | Tuesday | 1756 | 759 | 1,394 | 1,398 | 1,090 | 1,027 | 1,084 | 1,000 |
| 757 | VI | 267 | Thursday | 1758 | 760 | 1,396 | 1,400 | 1,092 | 1,029 | 1,086 | 1,002 |
| 758 | VI | 267 | **Friday — the answer to Volume 08's question** | 1759 | 761 | 1,397 | 1,401 | 1,093 | 1,030 | 1,087 | 1,003 |
| 759 | VI | 268 | **Tuesday — the tram depot** | 1763 | 762 | 1,401 | 1,405 | 1,097 | 1,034 | 1,091 | 1,007 |
| 760 | VI | 268 | **Wednesday — the Exchange, the fifty-sixth sitting, the book OPENS, and the volume closes** | 1764 | 763 | 1,402 | 1,406 | 1,098 | 1,035 | 1,092 | 1,008 |

### 1a. THE FORTY-EIGHT DAYS INSIDE THE SPAN THAT CARRY NO CHAPTER, ACCOUNTED FOR AS A RUN AND NOT AS A HOLE

**The span is 108 days and there are 60 chapters, so there are 48 days inside it that carry no chapter, and the arithmetic below is the account of all of them. There are four more days that carry no chapter outside the span, and they are the Thursday, the Friday, the Saturday and the Sunday between the close of Volume 14 and the opening of this one, and one of those four is the Thursday on which a doctor of fifty-three went further under this city.**

**The account is by kind of day, because a weekday gap and a weekend gap are not the same claim. The span holds sixteen Saturdays and sixteen Sundays — thirty-two weekend days — and exactly one of the thirty-two carries a chapter, which is the Sunday of week 263, day 1733, Chapter 747; so 31 weekend days carry no chapter, and 17 weekday days carry no chapter, and 31 + 17 = 48.**

| Account | Days | Which |
| --- | --- | --- |
| Before the first chapter | 4 | 1653 to 1656 — outside the span and not inside it |
| Weekends inside the span | 31 | thirty-two, less the one Sunday that carries Chapter 747 |
| Weekdays inside the span | 17 | six in Movement I and eleven in Movement VI, and none in Movements II to V |
| **Total days with no chapter inside the span** | **48** | and 4 more before the volume opens, so 52 from the last day of Volume 14 to the last day of this one |

**THE SHAPE OF THE VOLUME IS IN THAT TABLE AND IT IS A DECISION: Movements II, III, IV and V have NO WEEKDAY GAP AT ALL. Every one of their ten days is a weekday and every weekday in their span carries a chapter.** The forty days of the four middle movements are forty consecutive weekdays, and the two movements that are spread out are the first one and the last one. **A volume that runs at one rate through a nine-minute failure and then through a city's first ordinary day has not noticed either, and a reader can feel the difference between a chapter that was on a Tuesday and a chapter that was on a Tuesday eleven days after something happened.**

### 1b. Movement I's ten rows with the remaining eleven series, which a writer of Chapters 701 to 710 needs

| Ch | Day | Entry | 12 | 13 | 14 | 15 | 16 | 17 | 18 | Post | Copies | Sep | Chair |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 701 | 1657 | 704 | 1215 | 1166 | 1131 | 1110 | 1085 | 1067 | 1013 | 843 | 861 | 675 | 173 |
| 702 | 1659 | 705 | 1217 | 1168 | 1133 | 1112 | 1087 | 1069 | 1015 | 845 | 863 | 677 | 175 |
| 703 | 1660 | 706 | 1218 | 1169 | 1134 | 1113 | 1088 | 1070 | 1016 | 846 | 864 | 678 | 176 |
| 704 | 1661 | 707 | 1219 | 1170 | 1135 | 1114 | 1089 | 1071 | 1017 | 847 | 865 | 679 | 177 |
| 705 | 1664 | 708 | 1222 | 1173 | 1138 | 1117 | 1092 | 1074 | 1020 | 850 | 868 | 682 | 180 |
| 706 | 1667 | 709 | 1225 | 1176 | 1141 | 1120 | 1095 | 1077 | 1023 | 853 | 871 | 685 | 183 |
| 707 | 1668 | 710 | 1226 | 1177 | 1142 | 1121 | 1096 | 1078 | 1024 | 854 | 872 | 686 | 184 |
| 708 | 1671 | 711 | 1229 | 1180 | 1145 | 1124 | 1099 | 1081 | 1027 | 857 | 875 | 689 | 187 |
| 709 | 1675 | 712 | 1233 | 1184 | 1149 | 1128 | 1103 | 1085 | 1031 | 861 | 879 | 693 | 191 |
| 710 | 1680 | 713 | 1238 | 1189 | 1154 | 1133 | 1108 | 1090 | 1036 | 866 | 884 | 698 | 196 |

**The separation walks as `day − 982` and is 675 at Chapter 701, which is ninety-six weeks and three days, and it is not shorter, and it was ended in a one-line box in a form in the second week of Volume 13, and it is walked on all ten rows of this table and on all sixty rows of the volume and is not stopped on any of them.**

**The place behind the woman's chair walks as `day − 1484` and is printed on ONE file of each movement and on no other, because a whole-file interval walk built from section 2 alone returns false findings on any file that prints it. It is 173 days at Chapter 701 and 196 days at Chapter 710, and 196 is twenty-eight weeks to the day, and neither figure is printed in a load book and the difference between them is never printed as a number.**

---

## 2. The anchors, as a subtraction beside every value

| Series | Anchor day | Form | At 1657 | At 1764 |
| --- | --- | --- | --- | --- |
| The room off that service road | 362 | `day − 362` | 1295 | 1402 |
| The card in the rail | 358 | `day − 358` | 1299 | 1406 |
| The hardboard's twelfth line | 442 | `day − 442` | 1215 | 1322 |
| The hardboard's thirteenth line | 491 | `day − 491` | 1166 | 1273 |
| The hardboard's fourteenth line | 526 | `day − 526` | 1131 | 1238 |
| The hardboard's fifteenth line | 547 | `day − 547` | 1110 | 1217 |
| The hardboard's sixteenth line | 572 | `day − 572` | 1085 | 1192 |
| The hardboard's seventeenth line | 590 | `day − 590` | 1067 | 1174 |
| The hardboard's eighteenth line | 644 | `day − 644` | 1013 | 1120 |
| The hardboard's nineteenth line | 666 | `day − 666` | 991 | 1098 |
| The hold of the man of about thirty-three | 729 | `day − 729` | 928 | 1035 |
| The man of about fifty-one at the wall | 756 | `day − 756` | 901 | 1008 |
| The ask | 672 | `day − 672` | 985 | 1092 |
| The post at the corridor end | 814 | `day − 814` | 843 | 950 |
| The nine hand copies of the front of a page | 796 | `day − 796` | 861 | 968 |
| The separation | 982 | `day − 982` | 675 | 782 |
| **The place behind the woman's chair** | 1484 | `day − 1484` | 173 | **280** |

**The separation's anchor is 982 and has been since Volume 11 and does not move in this volume, and what moves is what it is used for. At day 1764 the column reads 782, and 782 days is a number of days that does not describe a separation, because the separation was not 782 days of anything: it ended in a one-line box in a form in the second week of Volume 13, and the number in that column has gone on being a correct subtraction since and does not know it.**

**THE PLACE BEHIND THE CHAIR IS THE ONE FIGURE IN THIS FILE THAT IS EXACTLY A WHOLE NUMBER OF WEEKS ON THE LAST PAGE OF THE MANUSCRIPT, AND 280 IS FORTY WEEKS TO THE DAY. No chapter of this volume prints it. It is printed here so that a later pass can check the claim that the count ran on, and it is printed here and nowhere else in a number.**

---

## 3. The Exchange, computed from this file and not from any chapter

| Sitting | Chapter | Day | Week | Count announced | Of which correspond | Book before | Book after | Tin |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| the fifty-second | 700 | 1652 | 252 | 57 | 52 | 64 | 64 | 73 |
| the fifty-third | 710 | 1680 | 256 | 58 | 53 | 64 | 64 | 73 |
| the fifty-fourth | 730 | 1708 | 260 | 59 | 54 | 64 | 65 | 73 |
| the fifty-fifth | 750 | 1736 | 264 | 60 | 55 | 65 | 65 | 73 |
| the fifty-sixth | 760 | 1764 | 268 | 61 | 56 | 65 | 66 | 73 |

**A count is announced at a sitting and on no other day, and the count goes up by one at every sitting whether the book opens or not. The correspond figure is the count less the five that predate the book on a sheet she has never shown anybody. The book opens only when a caller says a thing to her face, and this volume's pattern is shut, open, shut, open, and the pattern is not a rule and is not written anywhere and is not evidence of anything and may not be described in a chapter as a change in her. The difference between the book and the tin is not a number and is never printed as one, and none of the four is convertible into another, and the ninth chair is against the wall with its back to the room and does not move in this volume and its mover is not named. The place behind her chair is empty on all sixty days and is twenty-four weeks and five days old at Chapter 701 and forty weeks to the day old at Chapter 760, and neither figure is printed in a load book and the difference between them is never printed as a number.**

**AND THE THING NOBODY HAS ASKED: whether a count that goes up by one at a sitting where the book shuts is a count of anything. It is not this file's business and it is not a chapter's business and nobody in that room has ever been asked.**

---

## 4. The two-sided interval series, and how a writer renders one

**Every series printed in weeks and days is printed twice: once in the load book's row and once in the sentence of the narration above it, and both are converted by `weeks × 7 + days` and required equal. The weeks-and-days phrase is regenerated from the figure and compared character for character.**

**Test the attachment from the end of the `days` token and not from the end of the numeral, and test in both directions, because a compliant rendering in this house may put the weeks form first: "one day short of a hundred and ten weeks" and "a hundred and ten weeks and one day" are both house renderings and a walk that reads only the second will return a clean result on a page that has the first. A figure that is an exact number of weeks is rendered with the words *to the day* and the word *short* is not used.**

**AND THE SINGULAR: a day component of one is *one day* and not *one days*, and a component of zero is *to the day* and not *zero days*, and a component of two or more takes the plural. A generator that prints the plural on every non-zero component produces a walk that is correct on its arithmetic and wrong on its English, and the arithmetic check will not see it.**

Movement I's interval renderings, for the walk and not for reuse as sentences:

| Ch | Room | W and d | Card | W and d | Nineteen | W and d | Hold | W and d | Fifty-one | W and d | Ask | W and d | Copies | W and d | Sep | W and d |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 701 | 1295 | 185 w 0 d | 1299 | 185 w 4 d | 991 | 141 w 4 d | 928 | 132 w 4 d | 901 | 128 w 5 d | 985 | 140 w 5 d | 861 | 123 w 0 d | 675 | 96 w 3 d |
| 702 | 1297 | 185 w 2 d | 1301 | 185 w 6 d | 993 | 141 w 6 d | 930 | 132 w 6 d | 903 | 129 w 0 d | 987 | 141 w 0 d | 863 | 123 w 2 d | 677 | 96 w 5 d |
| 703 | 1298 | 185 w 3 d | 1302 | 186 w 0 d | 994 | 142 w 0 d | 931 | 133 w 0 d | 904 | 129 w 1 d | 988 | 141 w 1 d | 864 | 123 w 3 d | 678 | 96 w 6 d |
| 704 | 1299 | 185 w 4 d | 1303 | 186 w 1 d | 995 | 142 w 1 d | 932 | 133 w 1 d | 905 | 129 w 2 d | 989 | 141 w 2 d | 865 | 123 w 4 d | 679 | 97 w 0 d |
| 705 | 1302 | 186 w 0 d | 1306 | 186 w 4 d | 998 | 142 w 4 d | 935 | 133 w 4 d | 908 | 129 w 5 d | 992 | 141 w 5 d | 868 | 124 w 0 d | 682 | 97 w 3 d |
| 706 | 1305 | 186 w 3 d | 1309 | 187 w 0 d | 1001 | 143 w 0 d | 938 | 134 w 0 d | 911 | 130 w 1 d | 995 | 142 w 1 d | 871 | 124 w 3 d | 685 | 97 w 6 d |
| 707 | 1306 | 186 w 4 d | 1310 | 187 w 1 d | 1002 | 143 w 1 d | 939 | 134 w 1 d | 912 | 130 w 2 d | 996 | 142 w 2 d | 872 | 124 w 4 d | 686 | 98 w 0 d |
| 708 | 1309 | 187 w 0 d | 1313 | 187 w 4 d | 1005 | 143 w 4 d | 942 | 134 w 4 d | 915 | 130 w 5 d | 999 | 142 w 5 d | 875 | 125 w 0 d | 689 | 98 w 3 d |
| 709 | 1313 | 187 w 4 d | 1317 | 188 w 1 d | 1009 | 144 w 1 d | 946 | 135 w 1 d | 919 | 131 w 2 d | 1003 | 143 w 2 d | 879 | 125 w 4 d | 693 | 99 w 0 d |
| 710 | 1318 | 188 w 2 d | 1322 | 188 w 6 d | 1014 | 144 w 6 d | 951 | 135 w 6 d | 924 | 132 w 0 d | 1008 | 144 w 0 d | 884 | 126 w 2 d | 698 | 99 w 5 d |

**The post at the corridor end walks as `day − 814` and is 843, which is a hundred and twenty weeks and three days, at Chapter 701. The nine hand copies walk as `day − 796` and are 861, which is a hundred and twenty-three weeks to the day, at Chapter 701, and about eight of the nine are still unfinished and the first disagreement in the fourth line is still not found, and no two of the nine are compared on any of the sixty days of this volume.**

**AND THE WHOLE-NUMBER-OF-WEEKS ROWS, WHICH IS THE RENDERING THE WALK CHECKS AND WHICH A GENERATOR GETS WRONG BY PRINTING *zero days*.** The rows of Movement I and the whole-week series on each, walked from the anchors before this prompt was written and to be walked again and not assumed: **701 has three (room, sixteenth line, copies); 702 has four (eighteenth line, fifty-one, ask, and the chair, which is not printed); 703 has seven (card, twelfth, thirteenth, fourteenth, fifteenth, nineteenth, hold); 704 has three (seventeenth line, post, separation); 705 has three (room, sixteenth line, copies); 706 has eight (card, twelfth, thirteenth, fourteenth, fifteenth, nineteenth, hold, hold's neighbour the thirty-third — no, six of the seven above plus the copies is not; the count is six); 707 has three (seventeenth line, post, separation); 708 has three (room, sixteenth line, copies); 709 has three (seventeenth line, post, separation); 710 has four (eighteenth line, fifty-one, ask, and the chair, which is not printed).** **Every whole-number figure is rendered with the words *to the day*, a day component of one is *one day*, a component of zero takes *to the day*, and a component of two or more takes the plural. The word *short* is not used anywhere in this volume.**

**A NOTE ON THIS TABLE, WHICH IS THE FINDING OF THE FOUR PRECEDING VOLUMES: the whole-week count above is a figure a generator produced and it is wrong on the row for Chapter 706, and the sentence about it in this table has been corrected by hand rather than by the generator, which is the only correct procedure and is also the reason a pass that publishes a figure from an instrument it does not print publishes a guess.** **The authoritative test is not the count and it is the per-cell modulo.**

---

## 5. Collision sweep, and the reading that is required before it is trusted

**Sweep: for each of the seventeen numerical series on each of the sixty rows, test the value against the seventeen anchors, and report every hit where the value is not its own anchor. A hit is the day equalling the sum of two distinct anchors, so the whole sweep can be computed as a set of anchor-pair sums before any chapter is read, and that is how the two rows below were found.**

**Volume 15's chapter-day sweep returns NOTHING. Zero chapter-days out of sixty, on all seventeen series, and this is the first time in four volumes that the sweep has come back empty, and the reason is arithmetic and not craft: the previous three volumes each returned four chapter-day rows and each of those was a pair, and this volume's anchors are the same seventeen integers and the two sums that land inside a hundred and eight days both land on days that carry no chapter.**

| Sum | Day | Weekday | Which | Carries |
| --- | --- | --- | --- | --- |
| 756 + 814 | 1570 | out of span | the fifty-one at the wall against the post at the corridor end | — |
| 982 + 729 | 1711 | Saturday of week 260 | the separation's anchor against the hold's | **no chapter, and it may never be given one** |
| 982 + 756 | 1738 | Friday of week 264 | the separation's anchor against the fifty-one at the wall's | **no chapter, and it may never be given one** |

**THE DAY 1711 PAIR IS THE FOURTH TIME THE SEPARATION SERIES HAS COLLIDED IN THIS MANUSCRIPT AND IT IS A SATURDAY, AND THE DAY 1738 PAIR IS THE FIFTH AND IT IS A FRIDAY. Neither is a discovery. A collision is a coincidence between two integers and says nothing whatever about either object. And the page-side requirement stands and is the one this table was built to satisfy: the row-side and the page-side walk must agree, and both sums above were computed from the anchor set as a set of integers before any chapter was read, and both rows are re-derivable from section 2 alone.**

**And the row-side walk is not sufficient on its own, which is the finding of the last five volumes: a table can be correct on its day, its week, its weekday and its entry and wrong in eleven of its seventeen series columns, and only the page-side walk sees that.** Both halves are therefore required, on every volume of this manuscript, and a pass that runs one half has run half an instrument.

---

## 6. THE FIGURES THE SIX MOVEMENTS WALK, AND WHAT EACH MOVEMENT MAY NOT PRINT

| Movement | Chapters | Days | Span | Weekday gaps | Sittings | Panel | Sunday |
| --- | --- | --- | --- | --- | --- | --- | --- |
| I | 701–710 | 1657–1680 | 24 | six | the fifty-third, and the book SHUTS | none | none |
| II | 711–720 | 1681–1694 | 14 | none | none | none | none |
| III | 721–730 | 1695–1708 | 14 | none | the fifty-fourth, and the book OPENS | none | none |
| IV | 731–740 | 1709–1722 | 14 | none | none | none | none |
| V | 741–750 | 1723–1736 | 14 | none | the fifty-fifth, and the book SHUTS | Chapter 744, and its marker | none |
| VI | 751–760 | 1737–1764 | 28 | eleven | the fifty-sixth, and the book OPENS | none | Chapter 747 is in V |

**The about-two shutter form is on Chapter 747 alone in the whole of this volume, and the detector returns one Sunday and one only. The count of the leaves on a printed sheet is at zero in every movement except Movement II, where it is a number one man keeps and not a number anybody has taken. The number of doors a sheet is at is at zero in Movements I, III, IV, V and VI. The nine numbers on nine sheets are not added in any movement. The word on the ninth of the nine sheets is not said in any movement.**

**The whole-number-of-weeks figures on each movement's ten rows, for the walk and not for reuse as sentences, and each to be re-walked and not assumed: Movement I has three, four, seven, three, three, seven, three, three, three and four, of which the four on Chapter 702 and the four on Chapter 710 each include the place behind the woman's chair, which is printed on one file in the whole movement and is not in a load book. Movements II to VI are not printed here and are the business of their own prompts, which must walk them before they are written and not after.**

---

## 7. THE DEBTS INHERITED FROM VOLUME 14, CARRIED FORWARD UNCHANGED AND CANCELLED BY NOTHING

**This section is a list and not a plan. It exists because the Volume 14 close has not run, and everything below was owed to a close that did not happen, and a Volume 15 writer inherits all of it and may not resolve any of it and may not describe any of it as a rehearsal for anything.**

**The seventeen things Volume 14 leaves with the manuscript, none cancelled:** the printed paragraph on the back of a page of paper and the fact underneath it; the card, a name and a let house; four rooms in four districts that have each refused a merge; the three rooms in four towns; nine hand copies uncompared; nine keys needed and two existing; four bars across the inside of four doors in four buildings in four towns; the licensor, the field and the master's fifth line, which is blank; the second visitor column on a company form; the pale card in a gate hut; the plate of iron with four slots under a floor in the first of the four towns; the rota man's inspection, now about four years old; the returned sheet in the fourth tray, about four years old, the only copy in the world; the two people who cannot show which answer they gave; the heading on the strip, which is a plant and is not resolved in Volume 14; the fracture in the Conductor's Choir, noticed by four people in four places and said to nobody, one of whom is not on any page of Volume 14; and the nine sentences.

**The fifteen that leave it as debts and not as plots:** the nine numbers on nine sheets in Crown Terrace, unadded, and the single word on the ninth of them; the number of doors and the number of hands, both on nothing; about four people who stopped taking a plate off a night shift; a man of about sixty-eight who stopped walking one stretch of road; a card of about nine words in a young woman's own name on a wall in a fourth district that nobody has to obey; about nine people walking about four streets with nobody having asked who is buying; a list of four headings in a drawer that cannot be exposed because it was never hidden; a man of about thirty-four who pushes beds and cannot show that he did not agree to something; a notebook with nine seconds of a woman's speech in it in a coat; a card with two lines of type inside a door of a hall in a second district; the nine rooms and the one route nobody can travel; the lapsed mapping and the interface that did not lapse; and a doctor of fifty-three who is under this city and has armed what is left of the pattern.

**THE FIVE JUDGEMENTS THE VOLUME 14 CLOSE OWNS AND NO CHAPTER OWNS: the ceiling of six against a printed spend pattern that sums to eight against a total of seven; the four failures of Movement IV as four shapes; the repair of the two pre-existing defects in Movement I and the two inherited figure drifts; the standing instrument debts, which are the hedge pass that damaged the prose twice, the object-pair rule with no instrument behind it, the fourteen-term out-of-fiction list that has been wrong about its own class in four volumes running, and the four arrival cells, empty for the eleventh consecutive time; and the answer to the question nobody has asked, which is what Volume 14 accomplished and whether it was the thing it said it was going to do.**

**AND THE ANSWER THIS FILE GIVES TO IT, BECAUSE A FILE MAY CARRY A FINDING AND A CHAPTER MAY NOT: Volume 14's four hundred people who were not sent anywhere and a doctor under the ground are a set of facts and not a set of postponements, and the sentence on the back of the printed sheet is a reason nobody has answered yet and not a rule, and this volume is where it gets answered, and it gets answered in about nine seconds in a room, in Movement VI, and the answer is a chair.**

---

## 8. THE FOUR ARRIVAL CELLS, AND WHY THEY ARE EMPTY AGAIN

**The four arrival cells are the four measurements a movement's ten files must be given by a second pass before the movement can claim an arrival rather than a reconstruction. They have been empty for eleven consecutive times, in Volumes 12, 13 and 14, and they are the cells for arrival words, arrival hedges, arrival figures and arrival outcomes.**

**They will be empty a twelfth time at the end of Movement I unless a second pass is run on these ten files after they are written and repaired and before the batch is closed. This is the one house habit in this repository that has produced thirty-three passes over a volume instead of five, and it is a habit and not a rule, and this file names it so that the phase that writes the batch can decide to do it differently and say so in the batch's own summary.** **A cell that cannot be measured is printed empty and is not approximated, and a reconstructed arrival is the finished files measured twice and is not an arrival.**

---

## 9. Reserved for the Volume 15 close

**The close writes section 9: the count of series that ran clean on all sixty rows, the four arrival cells, the figures at day 1764, the words in the exchange at the fifty-sixth sitting, the three decisions the volume took, and the answer to Volume 08's question as the volume actually paid it. No writing pass before it may write it, and the seven items of section 7 are discharged in the close and not in a chapter. THE SECTIONS 6 THAT WERE OWED TO VOLUME 12, VOLUME 13 AND VOLUME 14 WERE ALL THREE WRITTEN BY A PHASE THAT WAS NOT THAT VOLUME'S CLOSE, AND THE VOLUME 14 ONE IS STILL A RESERVATION, and this file says so rather than letting a later pass find it.**
