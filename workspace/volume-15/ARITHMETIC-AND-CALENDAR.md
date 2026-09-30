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

## 9. THE VOLUME 15 CLOSE

**WRITTEN BY THE CLOSE, WHICH IS THE ONLY PASS THAT MAY WRITE IT. SECTIONS 1 TO 8 ARE UNTOUCHED. WHERE A SECTION CARRIES A FIGURE THIS CLOSE MEASURED DIFFERENTLY, BOTH ARE PRINTED AND THE ONE THAT GOVERNS IS NAMED.**

**AND ONE LINE THAT THE CLOSE DID NOT WRITE: A REPAIR PASS HAS EDITED SECTION 9 SINCE, UNDER A REVIEW THAT REBUILT EVERY INSTRUMENT IN IT FROM THE BOUNDARY PRINTED BESIDE IT, AND EVERY CORRECTION BELOW IS A FIGURE AND ITS BOUNDARY AND NOTHING ELSE. Sections 1 to 8 were not touched by that pass either, no chapter was touched, no plot moved, and no prose of the manuscript was read for anything but a boundary. The corrections are the size at Boundary A, the justification at Boundary C, the week at 9.3, the second reading of the governing relation at 9.4, both classes of the orphaned-hedge scan at 9.7, the hedge walk at 9.8 with its conclusion inverted, three residual-term claims at 9.8, the count of `none` at 9.8, and the account of the forty-eight days at 9.12. A section 9 written by two passes is a fact about this repository and it is printed here rather than left for a reader to infer from a date.**

### 9.1 THE COUNT OF SERIES THAT RAN CLEAN ON ALL SIXTY ROWS, THE INSTRUMENT, AND ITS BOUNDARIES

**FIFTEEN OF THE SEVENTEEN ARE THE SAME KIND OF THING AND ALL FIFTEEN RAN CLEAN ON ALL SIXTY ROWS. The two that are not the same kind of thing are the separation and the place behind the woman's chair, and they are not added to the fifteen and are not added to each other.**

**The instrument, and every one of its eight parameters, printed above the result.**

- **Boundary A, scope:** every line of all sixty files, bodies and apparatus, load books included. Sixty files, nine hundred and twenty-one thousand two hundred and fifty-five bytes of them, walked whole, and that is the sixty chapter files and not the six prompts and six summaries beside them.
- **Boundary B, what counts as a rendering, and there are two forms and both are counted and printed separately:** **form one** is a consumed number-word run immediately followed by the token `day`, `days`, `week` or `weeks`. **Form two** is a bare number, no unit of its own, immediately followed by a comma and then a weeks-and-days or weeks-to-the-day phrase, which is the form the conditions rows of Movement I use and which no other movement uses.
- **Boundary C, off-row:** every parsed integer of **700 or more** followed by a day or week unit must be one of that file's **own seventeen row values**. The threshold is 700 because the smallest printed series value on any of the sixty rows is **675**, which is the separation at Chapter 701, and the smallest of the fifteen series that describe a duration is **843**, which is the post at the corridor end on that same row; **727 is not a series value on any row of this volume and an earlier version of this sentence gave 727 as the reason, which is the same failure this section exists to end: a number printed beside a boundary that is not derived from it.** The threshold is fixed before the walk and not after. **AND IT HAS A KNOWN HOLE IN IT, WHICH IS PRINTED BECAUSE A BOUNDARY THAT HIDES ITS OWN LIMIT IS NOT A BOUNDARY: the separation is printed below 700 on eleven rows, Chapters 701 to 711, where it runs from six hundred and seventy-five to six hundred and ninety-nine, and those eleven rows are outside this check. It was walked separately against its own anchor and it is printed on all sixty rows and is equal to `day − 982` on every one of them, and the place behind the woman's chair was walked separately in the same way and is the last paragraph of this section.**
- **Boundary D, exactness:** tested on the shape of the rendering and not on membership of a set of interval totals. The words `to the day` qualify a **weeks** figure in this volume's prose and not a days figure, because the house renders these as *N days, M weeks to the day*, so a `to the day` rendering asserts that M times seven is a row value.
- **Boundary E, grammar:** tested on the day component of a weeks-and-days phrase and not on the total value, so a component of one is *one day* and a component of two or more takes the plural.
- **Boundary F, body and apparatus:** not used by this walk, because boundary A takes the whole file, and it is printed here because the hedge walk at 9.8 does use it.
- **Boundary G, clause:** the line is split at every full stop, colon, semicolon, comma, bracket and em dash, and the delimiter is kept as a token so that a run cannot cross it. **A hyphen is not a delimiter, because a hyphenated number word is one token.** A run may contain the word `and` and may not begin with it.
- **Tokenisation, declared:** a hyphenated number word is one token and is expanded to its parts before parsing, so *thirty-three* parses as 33 and *one thousand and one hundred and ninety* parses as 1190. A word carrying an ordinal suffix is not a number word and is not matched at all, which is why the *fifty-sixth day of this stretch of days* on Chapter 751 is not a rendering and is not walked.
- **The parser was asserted against twenty-five known renderings before it was pointed at a chapter, four of them hyphenated, and the assertion failed nineteen times on the first version.** The first failure was the hyphen and the second was the `and` inside a thousand, and the second one is the same shape of error as the 1,011 that Movement VI's parser returned for *one thousand three hundred and sixty-five*. **The assertion is the only reason either was found and this is the tenth occurrence in this repository of an instrument that was wrong before the text was.**

> **Result: 3,208 renderings of form one and 69 of form two, walked on sixty files. Off-row: 0. Exactness defects: 0. Two-sided interval mismatches: 1, and it is the instrument's boundary and not a chapter's** — on Chapter 717 the bare value *three* in the phrase *the four rooms and the fifth behind the three* sits immediately before a comma and a weeks-and-days phrase that belongs to the figure in front of it, and 1,327 divided as one hundred and eighty-nine weeks and four days is correct. **Two form-two candidates were returned and one was a real reading, which is the same relationship between proximity and attribution that Movements IV and V published about the clock and Movement III published about the hundreds slot, and it is not closed by building a better instrument.**

> **Per-series coverage, printed because a clean set with no membership is a figure and a coverage table is a boundary:**
>
> | Series | Anchor | Printed with a correct rendering |
> | --- | --- | --- |
> | The room off that service road | 362 | 60 of 60 |
> | The card in the rail | 358 | 60 of 60 |
> | The hardboard's twelfth line | 442 | 60 of 60 |
> | The hardboard's thirteenth line | 491 | 60 of 60 |
> | The hardboard's fourteenth line | 526 | 60 of 60 |
> | The hardboard's fifteenth line | 547 | 60 of 60 |
> | The hardboard's sixteenth line | 572 | 60 of 60 |
> | The hardboard's seventeenth line | 590 | 60 of 60 |
> | The hardboard's eighteenth line | 644 | 60 of 60 |
> | The hardboard's nineteenth line | 666 | 60 of 60 |
> | The hold of the man of about thirty-three | 729 | 60 of 60 |
> | The man of about fifty-one at the wall | 756 | 60 of 60 |
> | The ask | 672 | 60 of 60 |
> | The post at the corridor end | 814 | 60 of 60 |
> | The nine hand copies of the front of a page | 796 | 60 of 60 |
> | **The separation** | 982 | 60 of 60 |
> | **The place behind the woman's chair** | 1484 | **2 of 60** |

**THE FIFTEEN, and they are the fifteen whose membership the table at the head of `outline/volume-15.md` gives and which are the same kind of thing: a named object, a named anchor day, and a subtraction that is walked on every day of the volume and describes a duration of that object. All fifteen ran clean on all sixty rows, off-row zero, no wrong figure for any of them on any row, and no row of any of them is missing.**

**THE TWO THAT ARE NOT THE SAME KIND OF THING, and the reasons are different from each other.**

- **THE SEPARATION, anchor 982, walked as `day − 982`.** It is clean on all sixty rows and its arithmetic has not moved since Volume 11. **It is not added to the fifteen because the number in its column does not describe a duration of anything**: section 0.6 says so, the load books of all sixty files say so in their own words, and Chapter 730 puts it on the page as *a count of days that describes nothing*. It is the standing proof of a rule and the rule is that a correct subtraction is not a claim.
- **THE PLACE BEHIND THE WOMAN'S CHAIR, anchor 1484, walked as `day − 1484`.** **It is printed as a figure on two files of the volume and on no other: Chapter 710, at one hundred and ninety-six days, which is twenty-eight weeks to the day, and Chapter 720, at two hundred and ten days, which is thirty weeks to the day.** Movements III, IV, V and VI were each given a permission to print it on one file of their own and each of them declined it, and the reason each of them gives is the same one section 0.6 gives: *a series that is walked on every page stops being the thing it was.* **It is not added to the fifteen because a whole-volume walk over section 2 alone returns a false finding on fifty-eight of the sixty files, and this close has the printout.** Three of those false findings were counted before the instrument was corrected and they are worth naming because they are the whole of the trap. On Chapter 701 the twelfth line is given as *one hundred and seventy-three weeks and four days*, one hundred and seventy-three being the chair's correct value on that row, and on Chapter 708 the room is given as *one hundred and eighty-seven weeks to the day*, one hundred and eighty-seven being the chair's correct value on that row. **A number on this table can be the right answer to the wrong question and no instrument reading it out of an anchor table alone can tell.**

**AND THE ONE SUB-THRESHOLD FIGURE THIS WALK CANNOT SEE, MEASURED SEPARATELY BECAUSE BOUNDARY C IS AT 700 AND IT IS AT NONE OF THEM: the page that belongs to the woman of about thirty, the eighth of eight, in a ring binder on a back shelf, walks as `day − 1573`. It is printed on all ten files of Movement VI at one hundred and sixty-four, one hundred and sixty-eight, one hundred and seventy-two, one hundred and seventy-seven, one hundred and seventy-nine, one hundred and eighty-three, one hundred and eighty-five, one hundred and eighty-six, one hundred and ninety and one hundred and ninety-one days, and all ten conform. It is not one of the seventeen and it is not added to them. Chapter 752's figure of one hundred and sixty-eight days is exactly twenty-four weeks and is not rendered with the words *to the day*, and that is correct: the whole-week rendering is owed to the seventeen and to the seventeen only.**

### 9.2 THE FOUR ARRIVAL CELLS

**EMPTY. FOR THE EIGHTEENTH CONSECUTIVE TIME. THIS CLOSE DID NOT MEASURE THEM AND SAYS WHY, WHICH IS THE HONEST FORM OF THE ANSWER, AND A CELL THAT CANNOT BE MEASURED IS PRINTED EMPTY AND IS NOT APPROXIMATED.**

**The four cells are the four measurements a movement's ten files must be given by a second pass, after the writing and the repair and before the batch is closed, so that the movement can claim an arrival rather than a reconstruction.** **This close could not measure them because the predicate they would be measured against does not exist in a form any instrument can apply, and that is the finding rather than a formality.** `outline/volume-15.md` states each movement's arrival in prose, in a sentence, and no pass converted one of those sentences into a machine-checkable form before the movement was written. **There is therefore nothing on disk for a finished file to be tested against, and an instrument pointed at a prose intention returns either nothing or a paraphrase, and a paraphrase of an intention is the reviewer's opinion and not an arrival.**

**AND THE REASON IS STRUCTURAL AND HAS NOT CHANGED IN EIGHTEEN PASSES: every one of the six batches of this volume was written, and damaged or not damaged, measured by a pass that had written it.** Movements I and II were written in one dispatch and measured in a second and a third; Movements III to VI were written and saved first and measured in a second, which is the method the last four batches earned and which is the right method, **and being the right method is not the same as being an arrival, because a second pass over files that have not changed since the writing pass cannot distinguish a figure that arrived from a figure that was reconstructed.** The figures at 9.1 above are measurements. **They are not an arrival and this section does not call them one.**

### 9.3 THE FIGURES AT DAY 1764, ALL SEVENTEEN, EACH AS A SUBTRACTION FROM A NAMED ANCHOR AND EACH IN WORDS

**Day 1764 is the Wednesday of week 268, Chapter 760, load-book entry 763. A day is assigned only by section 1 of this file, and rule 3 gives the Monday of week _n_ as `7 × n − 114`: the Monday of week 268 is 7 × 268 − 114 = 1,762, and the Wednesday of that week is 1,764, and the detector at rule 3 returns week 268 and a Wednesday for 1,764 on its own and was not told either. **AND THE ORDER OF THE ARITHMETIC IS PART OF THE RULE, WHICH IS WHY IT IS PRINTED: subtracting before dividing is not the same act as dividing, and 1,764 − 114 over seven is not a week number. It is two hundred and thirty-five and seven twelfths. An earlier version of this sentence printed 264 for it, and a section whose stated purpose is exactness does not keep a wrong division in it.**

| Series | Arithmetic | Value | In words | In weeks and days |
| --- | --- | --- | --- | --- |
| The room off that service road | 1764 − 362 | 1402 | one thousand four hundred and two | two hundred weeks and two days |
| The card in the rail | 1764 − 358 | 1406 | one thousand four hundred and six | two hundred weeks and six days |
| The hardboard's twelfth line | 1764 − 442 | 1322 | one thousand three hundred and twenty-two | one hundred and eighty-eight weeks and six days |
| The hardboard's thirteenth line | 1764 − 491 | 1273 | one thousand two hundred and seventy-three | one hundred and eighty-one weeks and six days |
| The hardboard's fourteenth line | 1764 − 526 | 1238 | one thousand two hundred and thirty-eight | one hundred and seventy-six weeks and six days |
| The hardboard's fifteenth line | 1764 − 547 | 1217 | one thousand two hundred and seventeen | one hundred and seventy-three weeks and six days |
| The hardboard's sixteenth line | 1764 − 572 | 1192 | one thousand one hundred and ninety-two | one hundred and seventy weeks and two days |
| The hardboard's seventeenth line | 1764 − 590 | 1174 | one thousand one hundred and seventy-four | one hundred and sixty-seven weeks and five days |
| The hardboard's eighteenth line | 1764 − 644 | 1120 | one thousand one hundred and twenty | one hundred and sixty weeks to the day |
| The hardboard's nineteenth line | 1764 − 666 | 1098 | one thousand ninety-eight | one hundred and fifty-six weeks and six days |
| The hold of the man of about thirty-three | 1764 − 729 | 1035 | one thousand thirty-five | one hundred and forty-seven weeks and six days |
| The man of about fifty-one at the wall | 1764 − 756 | 1008 | one thousand and eight | one hundred and forty-four weeks to the day |
| The ask | 1764 − 672 | 1092 | one thousand ninety-two | one hundred and fifty-six weeks to the day |
| The post at the corridor end | 1764 − 814 | 950 | nine hundred and fifty | one hundred and thirty-five weeks and five days |
| The nine hand copies of the front of a page | 1764 − 796 | 968 | nine hundred and sixty-eight | one hundred and thirty-eight weeks and two days |
| **The separation** | 1764 − 982 | 782 | seven hundred and eighty-two | one hundred and eleven weeks and five days |
| **The place behind the woman's chair** | 1764 − 1484 | **280** | **two hundred and eighty** | **forty weeks to the day** |

**The three figures that come out on a whole number of weeks on that Wednesday are the eighteenth line, the man of about fifty-one at the wall and the ask, and that is what Chapter 760 says in its own words and what its conditions row carries. The room at one thousand four hundred and two is two hundred weeks and two days and the nine hand copies at nine hundred and sixty-eight are one hundred and thirty-eight weeks and two days, and Chapter 760's own head paragraph was repaired by the first review of Movement VI for having claimed otherwise, and it now says that neither of the two it names comes out on a whole number of weeks.**

**THE PLACE BEHIND THE WOMAN'S CHAIR IS FORTY WEEKS TO THE DAY EMPTY AT CHAPTER 760. That is the one figure in this file that is an exact number of weeks on the last page of the manuscript, and it is printed here and on no page of the volume, and the difference between it and the figure at Chapter 701 is not printed as a number here or anywhere.**

**AND THE THREE ARITHMETIC FIGURES THAT ARE NOT SERIES FIGURES, printed because the last page carries all three and because a close that printed only the seventeen would have been half its arithmetic:** the whole of Volume 15 from its first sitting to its close is 1764 − 1657 = **one hundred and seven days**, and inclusive of both ends 1764 − 1657 + 1 = **one hundred and eight days**, and from the first sitting to the close 1764 − 1680 = **eighty-four days**. The load-book run is continuous at entry minus chapter equal to three on all sixty rows, and 763 − 701 = **sixty-two**, which is the whole of the run and not a figure any page prints.

### 9.4 THE WORDS IN THE EXCHANGE AT THE FIFTY-SIXTH SITTING, IN THE ORDER THEY WERE SAID, AND THE TWO COUNTERS PRINTED SEPARATELY

**Chapter 760, day 1764, a first floor above a line in Saltmarket, about nine people over about an hour and a half and four of them at a table. In order.**

1. **A man of about thirty-eight, who has come to that room four times and has never once said what he came about, at about half past six, in about nine seconds:** *It is nine high. It has been nine high for a fortnight and I have four times sat in this room and not said so.*
2. **The woman of about sixty who holds the room did not answer him about the meter. She opened the book, wrote one line, and read the line out to the room, and the line was about a meter on a street of about eleven houses that had been running nine high for a fortnight.** The line went in at about half past seven. **Nobody in that room had seen the book open in about four years and about four people looked at the page and one of them said nothing and has not said anything since.**
3. **At about ten to eight, on her way out, a woman of about forty-four asked a man of twenty-two whether he would put his name beside the line, and he said no in about four seconds, and she said it is not about you, and then at the door that by Friday it would be about him, and he let both of those stand. She wrote the line herself and she did not sign it either.**
4. **At about a quarter to eight she said the number, once, in about nine seconds, to the room: *Sixty-one of which fifty-six.*** That is the fifty-sixth sitting, and it is the fifth time in this city that a number has been said in that room about a book and a tin, **and the fifth is not a pattern anybody has said out loud in that room and nobody in it is going to.**
5. **At about ten past eight, a woman of about fifty-two who chairs that body and has never sat on anything in it, and who came up that stair for the first time in about four years, said the four words in about two seconds, and they appointed nobody, removed nobody, started nothing and funded nothing, and about nine people in that room would not have gone to the door if she had not said them.** She said in the same breath that nothing turns on it, that she is the person who says it, and that she said it once into a printed box on a second floor about four years ago and told that room then that she would not say it in a hall. **Nobody in that room said the four words after her and nobody has said them since.**
6. **And then the book was on sixty-six lines and the tin beside it was on seventy-three with the lid down and did not move and nobody touched it; the ninth chair was hard against that wall with its back to the room and did not move; the place behind the chair of the woman of about sixty was empty and was not asked about; the light in the room under a building in a first district was off at about eleven and it is off.**

**THE TWO COUNTERS, PRINTED SEPARATELY BESIDE THE ABOVE AND NOT ADDED, AND THE STATEMENT THAT IS BESIDE THEM ON THE PAGE.** **The stretch of days this room has been writing in is on sixty-five days. The sittings are on fifty-six. The two are not added anywhere in this book and there is no page on which they are.** **Chapter 760 carries a sixty-fifth day of this stretch and a fifty-sixth sitting, and that is a coincidence of two counters and not a contradiction, and no pass may read either as the other.**

**WHERE THE COUNTER IS GOVERNED, AND WHAT THE WALK OVER ALL SIXTY ROWS FOUND: the *day of this stretch of days* counter is governed at `counter = chapter − 695` and it is a chapter-indexed row count for the stretch and not a calendar count. It conforms on fifty-one of the sixty rows, Chapters 710 to 760, and it does not conform on nine, and the nine are contiguous at the head of the volume and are Chapters 701 to 709, where the printed ordinal is *first, third, fourth, fifth, sixth, eighth, ninth, tenth and thirteenth* against a governed *sixth, seventh, eighth, ninth, tenth, eleventh, twelfth, thirteenth and fourteenth*.** **The gap is five on the first row and one on the last and is not a constant offset on the nine, so it is not a second governing relation and it is not a re-basing of the same counter; it is a different count in the first ten days of the volume and the same count from Chapter 710 on.** **THE CLOSE HAS CHECKED WHETHER THAT NON-CONFORMITY IS CARRIED HONESTLY AND IT IS NOT CARRIED AT ALL: the words non-conform and the words governing relation appear in none of the six batch summaries and in none of the five state files, and the nine rows are neither repaired nor recorded anywhere. That is a finding of this close and it is recorded here for the first time. The nine rows stand as they are and nothing about them has been changed by this pass, which may not write a chapter.**

**AND THE OTHER READING OF THOSE NINE ROWS, WHICH THE WORDING ABOVE DOES NOT ALLOW A LATER PASS TO MISS: a set of nine non-conforming rows is a fact about the relation that was declared and not a fact about the volume, and the alternative relation was measured on the same sixty rows before this sentence was written. `counter = day − 1656` conforms exactly on Chapters 701, 702, 703 and 704, where the printed ordinals are first, third, fourth and fifth against one, three, four and five, and it conforms on no other row of the volume. The two relations therefore agree on four rows, `chapter − 695` governs fifty-one and `day − 1656` governs four, and no single relation spans all sixty. The nine rows are a count of days in the first ten days of the volume under one declared relation and are four rows of a calendar count under another, and a reader who is told only that nine rows do not conform will look for a defect in nine chapters and there is one defect and it is in the declaration of the relation and not in any chapter.**

**AND THE THING THAT IS NOT ADDED TO ANYTHING: the calendar span is one hundred and seven days and the counter is on sixty-five and the sittings are on fifty-six, and the count announced at a sitting is the fourth thing, at sixty-one of which fifty-six, and the book is on sixty-six lines and the tin is on seventy-three, and the difference between the book and the tin is not a number and is not printed as one anywhere in this file or on any of the sixty pages.**

### 9.5 THE THREE DECISIONS THE VOLUME TOOK, IN THE VOLUME'S OWN WORDS

1. **He did not take the key, and the bargain was good.** Chapter 748, a Monday, in a room under a building in a first district, said to his face in about nine seconds and about thirty-two words and then a second time: *Take it. Every release comes to you; nothing waits, nothing is refused without you. It works — I did it and people lived. You would be the only one who can stop anything.* **And the file's own words: *It was a good one and he has not been able to find the flaw in it since, and he has gone over it on about nine occasions, and there is not one.*** **And then, of the bargain's survival: *The bargain was still on the table in the room at ten past eight and at nine and at half past nine, and it was still good at half past nine, and it is still good.*** **He did not say no. He did not say yes. He did not argue with her about a word of it, and he said a bay.**
2. **He put a chisel to the one object in that room that nobody had been authorised to touch, and it took about nine minutes by hand.** Chapter 749, a Tuesday, after the shop shut: *The first four minutes were the rim and the rest of them were the plate, and about four of the nine were his own hands shaking and not the work.* **The plate came out of the back of the cabinet in about nine minutes in three pieces, and none of them went anywhere, and he carried them up the stair in a coat because he could not think of anything else to do with them.** **The Crown Root Interface is in three pieces on a bench in a workshop off Lattice Ward, and it is not going to be put back, and there is a maker's mark stamped into the underside of the middle piece and it is upside down, so that a man has to turn the piece over in his hand to read it, and he read it twice, and it is four letters and it is not a name, and nobody else ever will.** **The authorisation that made it possible is a folded sheet with three ruled lines, a signature and eleven days on it, and it lapsed, and the plate did not, and on the back of it, in a different ink, somebody has written that the holder of a witnessed maintenance link may put a chisel to the plate and call it, and he does not know whose hand that is, and has not once occurred to him to ask, because the writing is the part he does not need and the writing is the part that matters.** **What is gone is the going and not the remembering, and those are two, and the first one is not the second one, and only one of them was ever a thing anybody could lose.**
3. **He did not put his name beside the line that went in.** Chapter 760, the last day, at about ten to eight, in about four seconds, to a woman of about forty-four on her way out: *It is not about you*, she said, and then at the door that by Friday it would be about him, and he let both of those stand, and **she wrote the line herself and she did not sign it either.** **And eleven days earlier, on a Tuesday in a second district, a trestle table and a sheet with a date and a name on it, he was offered the next version of that sheet to write and refused it in about four seconds, on the ground that is the only reason anybody said out loud that day: *I will not be the one who signs the day it stops, because on that day it will be read as mine, and I am not entitled to it and neither is anybody in that room.***

**AND THE THING THAT WAS DONE TO HIM AND WAS NOT A DECISION HE TOOK, because a close that printed only decisions would have printed half of Chapter 759: in a converted tram depot on a road in a fourth district, about nine minutes at a scarred workbench, he asked a woman of about thirty-three who cooks to take a bar of steel off him, and she took it off him in about four seconds and said the word they had agreed on, and he let go. Nobody kept a count, nothing was written down, nobody stood at the front, and the only person in that building who started anything was the woman of about forty-four with the keys.**

### 9.6 THE ANSWER TO VOLUME 08'S QUESTION AS THE VOLUME PAID IT, AND WHAT IT WAS NOT

**The question is Volume 08's and it is fifteen volumes old and `outline/volume-15.md` gives it in its own words: *what kind of institution can hold the line after the man is no longer in charge.* It is asked on Chapter 757, a Thursday, by a man of about fifty-three reading from a folded sheet, and it is answered in the same nine words in one line by a woman of about forty-eight who has kept the register of that body's appointments for about nine years and is the only person entitled to enter one: *It holds to its date, not one day past.*** **That is a form and a register and it is not the answer this section is about.**

**THE ANSWER WAS A CHAIR, AND IT WAS GIVEN AT CHAPTER 758, A FRIDAY, AT ABOUT A QUARTER TO EIGHT, IN ABOUT NINE SECONDS AND ABOUT THIRTY-EIGHT WORDS, IN A FIRST FLOOR ABOVE A LINE IN SALTMARKET, BY A WOMAN OF ABOUT FIFTY-TWO WHO IS NOT A MEMBER OF ANYTHING:** *That chair has been against that wall since before the spring and nobody has ever sat in it, and this room has run for nineteen years without it, and it would run the same with you in it.* **She was looking at a man of about fifty-eight who had come in with a laundry boiler and not at Marek, and Marek was four feet from the table.**

**AND THE FACTS THAT GO WITH IT, WHICH ARE THE STANDING SHE HAS AND THE ONLY STANDING SHE HAS, AND WHICH A CLOSE THAT OMITTED THEM WOULD BE HANDING THE READER THE BROKEN VERSION OF THE SCENE:** she had come in at about half past six on her own business, and her business was a form in a second district that had been filled in for her, with a tick in a box where her name should have been written, in a hand that is not hers, on a form about nine lines long, filled in about eleven weeks ago. **She had been in that room twice before, both times about a bill, both times in the autumn before the spring, and she had sat in the sixth chair both times, and she had not been asked a question either time.** She sat down in it at about ten to seven and said she wanted somebody to look at the form and not to do anything about it, and about four people heard her say that and none of them asked which eleven weeks or why she had come twice before and said nothing.

**AND THE OTHER FACTS, WHICH ARE FACTS AND NOT CONCLUSIONS:** nobody said she was right; nothing was written down; nobody asked her about a question; she has never been told since that there was anything in what she said except a chair, and if she is ever told she will say she was talking about a chair and she will be right; she did not sit down afterwards and stood by the door for about nine minutes with her coat on and then went out and down the stair, and nobody asked her to stay and nobody walked her to the stair. **He had a sentence ready for about two hours and did not say it, and he refused in about four seconds to confirm or deny to a man of about forty-four that the room would run the same with him in that chair, on the ground that he has never held this room. The chapter goes on afterwards and a boiler comes on at about eleven at night, for about the ninth night in a row, and the woman of about sixty asks the man of about fifty-eight one question, which was whether it was his, and he said it was not, and she said right.**

**WHAT THE VOLUME MAY BE SAID TO HAVE DONE HERE, AND WHAT IT MAY NOT: the volume answered the question. The woman did not answer it, because she does not know the question exists. One true thing about a chair is not a sentence about an institution and this section does not turn it into one. The answer is not a peroration, it is not a paragraph explaining that the answer was a chair, and it is not a speech.**

**AND THE ONE PLACE IN THIS VOLUME WHERE A LOAD-BEARING SENTENCE RESTS ON A PERSON WITH VERY LITTLE ACCESS, WHICH IS DELIBERATE AND IS NOT TO BE TIED UP: two visits about a bill is thin standing for a nineteen-year fact about an institution.** The first review of Movement VI found that the sentence rested on a claim a stranger who had walked in that evening had no standing to make, and gave her the two prior visits so that she would have some, and the second review softened that review's own claim that the repair made the chapter honest, because it does not. **She has sat in a chair twice and said nothing. That is the whole of her access and it is the access the sentence needs and the volume knows the difference and left it.**

**AND THE OTHER WOMAN OF ABOUT FIFTY-TWO ON THIS MOVEMENT, WHO IS NOT THE SAME PERSON AND IS NOT TO BE MERGED WITH HER: the one who chairs the standing committee and has never sat on anything in it, who said the four words once on Chapter 760 and has not said them since, and who on Chapter 760 had a hand on the back of the chair next to the empty place and did not ask about it either. The two were in no room together, nobody confused them, and this close does not make them one.**

### 9.7 THE INSTRUMENT DEBT, WHICH THIS CLOSE OWNS, AND WHAT IT HAS DONE ABOUT IT

**THE ORPHANED-HEDGE SCAN IS DELETED. NOT REPAIRED, NOT REBUILT, NOT PASSED ON A FIFTH TIME. The four figures this prompt and the Movement VI summary carried — 362, 360, 30 and 29 — are withdrawn as unreproducible and are not replaced by a guess, and the four remain printed in the places that published them so that the record of the wrong number is not lost with the wrong number.**

**THE REBUILD WAS ATTEMPTED BY THE CLOSE, ON THE CLOSE'S OWN FILES, FROM THE PRINTED DESCRIPTION ALONE, AND IT DID NOT REPRODUCE ANY OF THE FOUR, AND THE FIGURE IT RETURNS IS ZERO.** Written from the printed boundary: eleven terms, word boundaries, markup stripped to spaces, the H1 counted as body, the boundary at the load book's own opener, the fitted class being a hedge immediately followed by a word from the closed unit set with no number between. On Movement V's ten files it returns **zero** fitted findings; on Movement VI's ten files it returns **zero**. Movement V published **490** unfitted and **zero** fitted; Movement VI published **362** unfitted and **30** fitted; the same two batches published the unfitted class as **360** and **29** in the close prompt and in `state/continuity.md` on the same disk. **A scan written from its own printed description returns zero where two published scans returned thirty and thirty-odd, and the honest conclusion is the one both batches' own reviews were reaching and neither was allowed to finish: the boundary printed beside the number was not the whole of the instrument, and a boundary that does not determine the number cannot be handed to a fifth pass as though it did.** The class is therefore struck, and 9.8 below gives a hedge figure that this close can reproduce and has printed with all six things beside it.

**AND THE SECOND CLASS OF THE SAME SCAN IS STRUCK WITH IT, AND HERE IS WHY IT WAS STRUCK RATHER THAN PUBLISHED: the fitted class is zero for a reason that is now measured, and the unfitted class is not a number at all under any boundary this close could print. A hedge in this manuscript is almost never followed by anything but a number word — *about* nine, *about* thirty-eight, *about* nine seconds — so a class defined as a hedge immediately followed by a closed unit finds nothing to find, and the thirty-odd sites two batches published were produced by a class that looks through the number to the unit and is not the class printed beside it.** The unfitted class, defined here as a hedge immediately followed by a whitespace token that is neither a number word nor `and`, a number word being any token that, with a trailing full stop, comma or semicolon stripped and split at its hyphens, has every part among the words zero to nineteen, the tens, hundred, thousand and `and`, over the same two sets of ten files and the same body denominators of **18,262** and **19,052** tokens, returns **one hundred and thirty-seven** on Movement V and **one hundred and fifty-five** on Movement VI, where the close's own first run returned **one hundred and seven** and **one hundred and twenty-nine** and the two published scans returned **490** and **362**. **Four numbers for one class, no two of them equal, and the class is the same in all four, which is the finding and not a measurement: a boundary that does not determine the number is not a boundary. Both classes are struck, neither is replaced by a guess, and the denominators are printed beside them because the denominators did reproduce and the house is allowed one thing that held.**

**THE FOUR FREE CHECKS ARE DELETED AS A CHECK. The close's ruling, and the standing rule that goes with it: no check that cannot fail on any input, including a file of nonsense, is published as a result.** {4}, {21}, {−27} and {−72} are identities over the anchor table. `(day − 358) − (day − 362)` is 4 for every integer day. They are clean on a file of nonsense, and that is the whole of what their cleanliness says. They are withdrawn as evidence here for the fifth time and the withdrawal is now a rule and not a correction. **The four differences are not deleted with them, because they are four true sentences about four pairs of anchors and they are the reason the pairs are in the table: the card is four days past the rooms; the fifteenth line is twenty-one days behind the fourteenth; the man of about fifty-one at the wall is twenty-seven days behind the hold; and the eighteenth line is seventy-two days ahead of the sixteenth.** **They are printed here as four facts about the anchor table and are not walked and are not counted and are not evidence about prose.**

### 9.8 THE FIGURES THIS CLOSE MEASURED ITSELF, EVERY ONE WITH ITS INSTRUMENT AND ITS BOUNDARIES, AND EVERY ONE REPRODUCIBLE FROM WHAT IS PRINTED BESIDE IT

**A figure printed without the six things beside it is a claim. The six are: the terms, the match mode, the markup handling, the H1 handling, the boundary, and the denominator. All six are printed above the number for every figure in this subsection, and no figure in this subsection was inherited from a batch summary.**

> **The hedge walk over all sixty files, which no pass has ever run in this volume's history, and which this close has now run twice because the first run did not reproduce and the reason it did not reproduce was that the mode printed was not the mode run.** Terms, in full: `about`, `around`, `nearly`, `roughly`, `approximately`, `almost`, `some`, `just`, `give or take`, `more or less`, `or so`. Match mode: whole-word, exact term, **case-insensitive**, with the stem variant run second and printed beside it, and with the case-sensitive pair run third and printed beside that. **Word boundary, declared because it is not the same thing as a token: a hedge is counted when it stands with no letter on either side of it, so a hyphen or a full stop does not stop it and a hedge inside another word is not counted.** **The stem variant is a term followed by up to three further letters, and for the three multi-word terms it is the first word of the term, which is declared here because it is where the variant stops being a hedge at all: `give or take` becomes `giv`, `more or less` becomes `more` and `or so` becomes `or`, and the 165 sites it adds to the body figure are the word *or* fifty times, *more* forty-three, *order* fifteen, *given* thirty-seven, *give* eleven, *gives* five and one proper name four, and not one of the 165 is a hedge. The exact figure governs and the stem figure is printed so that the defect is visible instead of inherited.** Markup handling: `*`, backtick and underscore replaced by a space. H1 handling: the H1 title line counts as body and is kept in both scopes, so the whole-file denominator is the whole file. Boundary: the load book's own opener, the line that is the italic entry numeral, and not a horizontal rule. Denominator: whitespace-delimited tokens, and a hyphenated number word is one token.
>
> | Scope | Match | Numerator | Denominator | Per thousand |
> | --- | --- | --- | --- | --- |
> | Bodies, sixty files | exact, case-insensitive — **this is the declared mode and it governs** | 3,229 | 106,955 | **30.190** |
> | Bodies, sixty files | stem, case-insensitive | 3,394 | 106,955 | **31.733** |
> | Whole file, sixty files | exact, case-insensitive — **governs** | 4,724 | 181,791 | **25.986** |
> | Whole file, sixty files | stem, case-insensitive | 5,110 | 181,791 | **28.109** |
> | Bodies, sixty files | exact, case-**s**ensitive | 2,990 | 106,955 | 27.956 |
> | Whole file, sixty files | exact, case-**s**ensitive | 4,396 | 181,791 | 24.182 |
>
> **THE TARGET THIS VOLUME SET WAS AT OR BELOW TWENTY-FIVE PER THOUSAND, AND AT THE DECLARED MODE NEITHER SCOPE REACHES IT: the body stands at thirty and the whole file at just under twenty-six, and both are published.** **The earlier version of this subsection printed twenty-seven and twenty-four and concluded that the whole-file figure reached the target while the body figure did not. That conclusion was true of the case-**s**ensitive pair and false of the case-insensitive pair, and the mode printed was case-insensitive, so the mode that governed was not the mode that had been run, and a figure whose conclusion inverts when the mode is corrected is a figure that was never measured in the mode it was printed in.** **Both pairs are printed above so that no later pass has to guess which convention produced which number, and both denominators reproduce to the token.**
>
> **AND THE THIRD CONVENTION, PRINTED BECAUSE IT LANDS ON A NUMBER THAT IS ALREADY IN THIS SECTION AND A LATER PASS WILL FIND IT: matching the eleven terms against whole whitespace tokens instead of against word boundaries gives 3,208 in the body and 4,694 whole-file, which is 29.994 and 25.821, and the first of those is the form-one rendering count at 9.1. It is a coincidence of two instruments over two different unit sets and it is not a crossing, and the reason it is printed here rather than left to be discovered is that the discovery would be more expensive than the sentence.**
>
> **Movement I measured 27.831, Movement II 26.418, Movement III 25.125, Movement IV 30.745 and Movement V 29.332 on their own ten files, and they are printed here as those movements published them and are not compared with the table above, for two reasons that are both on the page: the instruments were not rebuilt by this close, and Movement I's term list is a different eleven, printed at item 6 of `workspace/volume-15/batch-0001/PROMPT.md` as `about`, `around`, `roughly`, `approximately`, `nearly`, `almost`, `some`, `many`, `most`, `several`, `few`, which carries four terms this walk does not and lacks four this walk does. Movement V's figure could not be reproduced from its own printed terms and Movement VI's was published declaring that it could be and then failed it. The walk above can: the terms, the match mode, the word boundary, the markup handling, the H1 handling, the body boundary and the denominator are all printed, and any pass may rebuild the number instead of inheriting it.**

> **The shared-run walk over all sixty files, which no pass has ever run either, because every one of the six batches measured only its own ten.** Seeded on twelve-word grams and extended one token at a time in both directions, over all one thousand seven hundred and seventy unordered pairs, markup stripped to the character. Body scope cuts the apparatus at the load book's own opener and takes the H1 in. Whole-file scope strips the H1 and keeps the apparatus. Target, thirty-one tokens.
>
> | Scope | Worst run | Between | What it is |
> | --- | --- | --- | --- |
> | Body | **35 tokens** | Chapters 702 and 705 | *and about eight of the nine are still unfinished and the first row on which anybody has ever disagreed has still not been found, and not one of the nine has been laid against another* — a Movement I standing row about the nine hand copies |
> | Whole file | **53 tokens** | Chapters 750 and 751 | the conditions-of-the-close standing row, beginning *out of the other and nobody did tonight. behind the chair the woman of about sixty sits in* — a mandated row, and the only run in the volume that crosses a movement boundary |
>
> **Both are standing rows and neither is a scene, and both are inside the plan of record's own list of where a shared run is allowed to live, and neither is repaired by this close, which may not write a chapter.** The finding is the one no batch could have printed: **six movements each met the target on their own ten files and the volume as a whole does not, and the run that puts it outside is the row that hands one movement's apparatus to the next.**

> **The residual-term walk over all sixty bodies, matched on the stem, because a scan that matches a word and not its inflection is a scan of one spelling and Movement III published a false zero on exactly that.** **THE THREE OUT-OF-FICTION LISTS ARE NOT ALL AT ZERO, AND AN EARLIER VERSION OF THIS PARAGRAPH SAID THAT THEY WERE, AND THE THREE FIGURES IT NAMED ARE RE-MEASURED HERE WITH THEIR COUNTS BESIDE THEM.** **The fourteen-term list, printed at item 14 of `workspace/volume-15/batch-0001/PROMPT.md` and matched as a phrase and case-insensitively over body and apparatus, is at zero on eleven of its fourteen terms and is not at zero on three: `in a book` stands at nineteen sites on eleven files and every one of them is inside the fiction — the Exchange's book with a green cover, a man's own book with a rubber band on it, and one in the Chapter 701 title — and `this chapter` stands at two sites, on Chapter 753 and Chapter 755, and `this movement` at one, on Chapter 755, and those three are out-of-fiction pointers in the plain sense the list exists to prevent, on two files of the last movement, and they are printed here and not repaired because a close may not write a chapter.** `Crown` stands at **six sites on three files, four of them in bodies**: the Crown Key once on Chapter 707 on a sheet read aloud by a man who does not know who wrote it, the Crown Root Interface three times on Chapter 749, two of them in the body, and the Crown Clause twice on Chapter 756, one of them in the body; all six are permitted forms and the earlier figure of three was a count of one permitted form per file and not a count of sites. **The four words of the public body's name stand at one occurrence in the whole of the volume, in a body, on Chapter 760, and at zero on the other fifty-nine, and that one stands as it was printed.** `ring binder` is the only permitted use of the word, and the word itself stands at **112 whole-file sites of which 111 are inside the phrase and one is not: Chapter 721, in a quoted line, *I could ring him*, said by a man offering to telephone somebody, which is the use the phrase rule was written to keep out and which survived every sweep because the sweeps matched the phrase and not the word.** **AND THE OTHER TWO LISTS ARE NOT PRINTED ANYWHERE IN THIS REPOSITORY: the thirty-eight-term class and the further twenty-three words that Movements I to IV policed are named in three batch summaries and are written out in none of them, so this close could not rebuild them and their zeros are inherited from those movements and are claims, and they are printed here as claims and not as measurements.**

> **The refusals line, walked over all sixty load books, and totalled for the first time because no chapter totals it and a close is the only document in this repository that is about the manuscript rather than in it.** Boundary: the line beginning `Refusals:` in each file's own words, taken as a whole, the leading number read off it, and a leading `none` read as zero. **Movement I forty-three, Movement II forty-eight, Movement III forty-seven, Movement IV forty-five, Movement V eight, Movement VI eight, and one hundred and ninety-nine across the sixty days, and eight of the sixty files record the word `none` as the leading value — Chapters 744, 746, 747, 749, 750, 751, 757 and 759 — five of the eight in Movement V and three of the eight in Movement VI. An earlier version of this sentence said five of the sixty and four of those five in Movements V and VI, and that count came from a search that stopped at the first full stop and so missed the two lines that read *none on that Wednesday* and *none from him*; the eight is the count and it was wrong before this repair and is not wrong now.** **The boundary is the house's own and it is wide: a request to be told something that no counter in this city can supply is written into the same line as a person saying no to another person, and the two are not the same kind of act and the line does not distinguish them.** A total of one hundred and ninety-nine is a count of a line and not a measure of anything, and it is printed because the prompt's twelve refusals are inside it and because a close that walked a line for sixty files and then did not print the walk would have done the thing this repository keeps publishing.

### 9.9 THE FOUR ARITHMETIC CLAIMS THE DETECTOR CONTRADICTS, CARRIED HERE AND NOT LEFT IN A BATCH SUMMARY

**A later pass must not read Chapters 751 to 760 as defective on any of these four. The detector governs and the prompt of record's figures do not.**

1. **The separation on Chapter 751 is seven hundred and fifty-five days and not seven hundred and fifty-one.** The file prints seven hundred and fifty-five, in the body and in the load book, and 1737 − 982 is 755.
2. **The Sundays inside the span of Movement VI are 1740, 1747, 1754 and 1761 and not 1744, 1751, 1758 and 1765.** 1740 − 502 is 1238 and 1238 divided by seven is 176 with a remainder of six, and 6 is Saturday's offset on a Monday-first week, so 1740 is a Sunday; the same division gives 1754 and 1761, and 1768 is the Sunday after the volume ends. **1758 is a Thursday**, which is what the prompt's own day map says and what the file prints, and it was verified with the detector before a word was written about its day.
3. **Ten of Movement VI's weekdays carry no chapter and not eleven.** The span is twenty-eight days and holds twenty weekdays, and ten of them carry a chapter, so ten carry none.
4. **And the one that is still standing and is not to be read against Chapter 730: the Movement III prompt's sixty-four and sixty-five against the plan of record's sixty-five and sixty-six.** Chapter 730 was written at sixty-four lines before that hour and sixty-five after it, because one line goes in at that sitting and a book cannot go up by two in one hour. **The two plan-of-record files and the prompt's own first clause agree with the chapter; the prompt's three figures are in the minority and are inconsistent with the rest of the same file, and a phase artefact is not corrected by a repair pass and was not corrected here.**

### 9.10 WHAT SECTION 7 OWES AND WHAT SECTION 9 DOES NOT DISCHARGE

**THE SEVENTEEN DEBTS IN SECTION 7 ARE CARRIED FORWARD UNCHANGED AND ARE NOT DISCHARGED HERE. This close does not resolve one of them, does not soften one of them, and does not describe one of them as a rehearsal for anything. The fifteen Volume 14 debts, the four arrival cells, and the standing instrument debts are the business of `workspace/volume-14/ARITHMETIC-AND-CALENDAR.md` section 6, which is still a reservation, and that file is not this close's to write and was not written.**

**AND THE FINDING THAT BELONGS HERE, WHICH THE SECOND REVIEW OF MOVEMENT VI CAUGHT AND WHICH THE EARLIER VERSION OF THE CLOSE PROMPT GOT WRONG: THERE ARE THREE UNRUN VOLUME CLOSES IN THIS REPOSITORY AND NOT TWO. `workspace/volume-12/VOLUME-CLOSE.md`, `workspace/volume-13/VOLUME-CLOSE.md` AND `workspace/volume-14/VOLUME-CLOSE.md` ARE ALL PLAIN FILES SITTING AT THEIR VOLUME ROOTS, AND THE CONTROLLER'S SELECTION RULE FINDS A DIRECTORY HOLDING A `PROMPT.md` AND NO `.done`, WHICH IS WHY THIS CLOSE IS A DIRECTORY AND THOSE THREE WERE NEVER RUN. The prompt named the first two of the three and the third is the one that is actually outstanding, because section 6 of the Volume 14 calendar file is still a reservation and the seventeen debts sit on it. That is a finding about the structure of this repository and it is in section 9 because this is the only pass in fifteen volumes that has stood where all three are visible at once. It is controller-owned and no pass has touched the workflow or the selection rule, and the correct thing for a close to do about it is to say so in one paragraph and change nothing.**

### 9.11 THE LEDGER, WHICH A CLOSE PRINTS AND DOES NOT TOUCH

**`state/phase-ledger.json` still reads `phase-000-bootstrap` and `planned` while the manuscript stands at Chapter 760 and is finished. That file is controller-owned, is on the list no agent pass may edit, is read and not written by anybody, and the disagreement has been flagged in every summary rather than fixed by hand. This is the forty-fifth time it has been flagged. The correct thing for a close to do about it is to print the number and touch nothing, and this close has touched nothing.**

### 9.12 WHAT THIS VOLUME IS, IN THE FIGURES, AND WHAT IT IS NOT CALLED

**Chapter 701 is day 1657 and Chapter 760 is day 1764 and the two are one hundred and seven days apart and there are sixty chapters on the days between them and forty-eight days inside the span that carry no chapter, twenty-nine of them weekend days and nineteen of them weekdays, and three of the four middle movements have no weekday gap at all, Movement I has eight, Movement V has one, on the Wednesday of week 263, and Movement VI has ten.** **THE COUNT IS MEASURED AND SECTION 1a CARRIES A DIFFERENT ONE, AND THE RULE FOR THAT IS THE RULE AT THE HEAD OF THIS SECTION: the span holds thirty weekend days and not thirty-two, because a hundred and eight days from a Monday is fifteen whole weeks and three days, one of the thirty carrying a chapter, which is the Sunday of week 263, day 1733, Chapter 747, and so twenty-nine weekend days carry no chapter; the weekday count is therefore nineteen and not seventeen. Section 1a's account of thirty-one and seventeen, which rests on sixteen Saturdays and sixteen Sundays, is the plan of record's figure and the day map in section 1 is the assignment, and where a section carries a figure this close measured differently both are printed and the day map governs.** **The register of correct acts with no consequence moved once, at Chapter 727, from two to three, and what it cost a man of about fifty-two was nine minutes at a junction, a queue, a Friday, a Monday he cannot get, and his wife's name in a book at a clinic he has not been in the room of, and no movement improved on that and no movement contradicted it and this close does not move it either and it stands at three.** **The book went from sixty-four lines to sixty-six over those days and one line went in at each of the two sittings where it opened, and the tin did not move, and neither figure was ever made into the other by anybody.**

**Nothing in this section is a win and nothing in this section is a failure, and the reason is not a courtesy. The city is slower and a person may wait while a local group checks a boundary, and that delay is treated as part of care and not as failure, and that is the shape of the world this manuscript ends in and it is not a thing a close gets to grade. `outline/ending.md` line 129 says it and this section does not improve on it.**
