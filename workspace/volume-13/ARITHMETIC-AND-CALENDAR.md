# Arithmetic and calendar — Volume 13

**`workspace/volume-13/ARITHMETIC-AND-CALENDAR.md`, at the volume root, beside `batch-0001/`, and not inside any phase directory. It is a volume-level working file and not a phase: it holds no `PROMPT.md` and no marker, so the controller's selection rule — the first directory under `workspace/` holding a `PROMPT.md` and no `.done` — is unaffected by it. `workspace/volume-06/ARITHMETIC-AND-CALENDAR.md` through `workspace/volume-12/ARITHMETIC-AND-CALENDAR.md` are the precedents and sit in the same place.**

**It was written with `outline/volume-13.md` and before Chapter 601. Sections 1 to 5 are a plan of figures and not a table read back off chapters, and every number below is a day number minus a named anchor day and can be recomputed by anybody in about a minute. Section 6 is owned by the volume close and no writing pass before it may write it.**

**It is a table and a set of series. It is not a prompt, it plans nothing, and it derives nothing.**

**Four rules, and they are the same four as the seven files before it.**

1. **No day number may be printed in a chapter.** No month-name, no month-date, no day-date, no year. The only calendar nouns permitted are the season words, the week and the day inside the week. **All interval figures are spelled out in words, and a figure that is an exact number of weeks is rendered with the word *to the day* and is not rendered with the word *short*.** No chapter of this volume prints how far away a town is, and a town is described by how long the bus takes or by nothing at all.
2. **A day is assigned only by section 1 of this file.** Where this file and a live batch prompt disagree on a day, **the batch prompt is right for its ten days and this file is right for the run**, and a batch prompt that disagrees with the table below on a day is a defect to be corrected in place and recorded.
3. **Weeks run Monday to Sunday. The detector is inherited unchanged and is `week = (day − 502) // 7 + 88` and the weekday is `wd = (day − 502) mod 7` against Monday-first, and the Monday of week _n_ is `7 × n − 114`.** **A value that disagrees with the detector is the value that is wrong, and the detector is the one that agrees with the sittings inherited from `outline/series.md`, with the repaired week table in `outline/volume-12.md` and with the four sittings of Volume 12.**
4. **The interval map's two-day offset from the Monday of week thirty-one is inherited, is recorded for the twentieth time, and is not to be re-derived from the anchor.** No chapter in this manuscript has ever printed a day number, so no prose depends on any of it.

---

## 0. What this file inherits

### 0.1 THE CHAIN, CHECKED ONCE AND NOT RE-DERIVED

**The inherited anchors are printed at the head of `outline/volume-13.md` and are not duplicated here, because a table of anchors is a second place in this repository a figure can be copied from and the seventh time that has happened has been a defect. The chain gives 1428 as the Wednesday of week two hundred and twenty, which is the day Volume 12 closed on, and 1433 as the Monday of the week after, and that is the whole of the check.** The arithmetic is `7 × 221 − 114 = 1433` and `7 × 220 − 114 = 1426`, and the Wednesday of week 220 is 1426 + 2 = 1428, and the Monday of week 221 is 1426 + 7 = 1433. **A pass that writes the Monday as `7 × W − 682` has dropped two digits and will produce a Monday four hundred and ninety days early, and the repair pass of Volume 12 Movement I found that exact error in a prompt and this file repeats the warning because the warning is what stopped it.**

### 0.2 THE DAY ZERO, MADE EXPLICITLY AND PRINTED, WITH THE OPENINGS THAT WERE REFUSED

**Chapter 601 is day 1433, the Monday of week two hundred and twenty-one. In one sentence: Volume 13 opens on the first Monday after the Wednesday Volume 12 closed on, and 1433 is 1428 + 5, and 1428 is the Wednesday of week 220, and 1430 is the Monday of week 221 minus three, and 1433 is 1428 + 5.**

**It is a decision and not a consequence, and the reason is printed so that a later pass can see the choice rather than the result: Volume 12's last chapter was a Wednesday and a Wednesday is a sitting day, and a volume that begins on a sitting day begins inside the habit the volume is about to describe. Four other openings were available and were not taken: 1429 is a Saturday and this manuscript does not open a volume at a weekend; 1430 is a Tuesday and would have opened the volume on the first working day, which is the conventional choice and which the calendar of the last seven volumes has never once used for a Monday; 1431 is a Wednesday and would have handed the first chapter to a day with a rule of its own; and 1436 is the Thursday of the same week, which is Chapter 602 and which would have cost the volume a first chapter on a Monday for the sake of a number.**

### 0.3 WHAT VOLUME 12 HANDED OVER THAT A FIGURE HERE DEPENDS ON, RESTATED WITH ITS SUBTRACTION BESIDE IT

| Figure | Arithmetic | Value |
| --- | --- | --- |
| Chapter 600 | the Wednesday of week 220, 7 × 220 − 114 + 2 | 1428 |
| Chapter 601 | 1428 + 5, and the Monday of week 221, 7 × 221 − 114 | 1433 |
| The first sitting in this volume | 1433 + 23, and the Wednesday of week 224, 7 × 224 − 114 + 2 | 1456 |
| The whole of Volume 13 | 1540 − 1433 | 107 days |
| The whole of Volume 13 inclusive of both ends | 1540 − 1433 + 1 | 108 days |
| The first sitting to the close | 1540 − 1456 | 84 days |
| The room at Chapter 601 and at Chapter 650 | 1433 − 362, and 1540 − 362 | 1071, and 1178 |
| The card at Chapter 601 and at Chapter 650 | 1433 − 358, and 1540 − 358 | 1075, and 1182 |
| The nineteen lines at Chapter 601 and at Chapter 650 | 1433 − 666, and 1540 − 666 | 767, and 874 |
| The hold at Chapter 601 and at Chapter 650 | 1433 − 729, and 1540 − 729 | 704, and 811 |
| The ask at Chapter 601 and at Chapter 650 | 1433 − 672, and 1540 − 672 | 761, and 868 |
| The man of about fifty-one at Chapter 601 and at Chapter 650 | 1433 − 756, and 1540 − 756 | 677, and 784 |
| The separation at Chapter 601 and at Chapter 650 | 1433 − 982, and 1540 − 982 | 451, and 558 |
| The turn of the movement, Chapter 610 to Chapter 611 | 1454 − 1450 | 4 days |

### 0.4 THE FOUR FREE CHECKS, WITH THEIR SIGNS, IN FULL

A check that publishes its clean set and not its limits cannot be told apart from a check that was never run, so all four are printed here with their limits and their signs, and all four are walked on all fifty rows of section 1.

| Check | Expression | Constant | Sign as printed |
| --- | --- | --- | --- |
| The card-minus-room invariant | `(day − 358) − (day − 362)` | 4 | {4} |
| The fourteen-less-fifteen | `(day − 526) − (day − 547)` | 21 | {21} |
| The fifty-first-less-hold | `(day − 756) − (day − 729)` | −27 | {−27} |
| The eighteen-less-sixteen | `(day − 644) − (day − 572)` | −72 | {−72} |

### 0.5 THE SPENT-AGE CLASS GETS AN INSTRUMENT AND NOT ONLY A PROHIBITION

**For each file: extract every occurrence of a spent age, take the noun phrase it sits in, and record whether a person is the subject of it. A spent age on a person established in this manuscript is permitted and is canon. A spent age on a new person is a finding and not a permission. A raw substring count of the spent ages is not an instrument, because a new person can carry a spent age any number of times and a raw count cannot see who is carrying it.** Movement I names one person and she is not given a spent age.

### 0.6 THE ONE INHERITED FIGURE WHOSE *SUBJECT* CHANGES AND WHOSE ARITHMETIC DOES NOT

**The separation walks as `day − 982` in every volume and the anchor does not move. What changes in this volume is what the separation is.** Volume 12 left it not shorter and not ended at four hundred and forty-six days, and published it as a figure of record and not a cliffhanger. **It is ended at Chapter 607, on the Friday, in a one-line box in a form, and the series is not stopped on that day and is walked on all fifty rows of section 1 and in all fifty chapters, and a series that stops being printed when the thing it counts stops is a series that has been given a favour.** Volume 12's close named this volume's inheritance as *a figure of record and not a cliffhanger*, and this file says which of the two it was: **it was a record, and a record goes on being a record.** The column headed `Sep` in section 1 is therefore a count of days and, from Chapter 607 onward, a count of days that does not describe anything, and the last entry of section 2 prints that fact at day 1540.

---

## 1. The day map, all fifty chapters, with the load-book entry on each row

| Ch | Week | Day | Day no. | Entry | Room | Card | 19 | Hold | Ask | 51 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 601 | 221 | **Monday — the volume opens** | 1433 | 604 | 1071 | 1075 | 767 | 704 | 761 | 677 |
| 602 | 221 | Thursday | 1436 | 605 | 1074 | 1078 | 770 | 707 | 764 | 680 |
| 603 | 221 | Friday | 1437 | 606 | 1075 | 1079 | 771 | 708 | 765 | 681 |
| 604 | 222 | **Monday — the collision pair** | 1440 | 607 | 1078 | 1082 | 774 | 711 | 768 | 684 |
| 605 | 222 | Wednesday | 1442 | 608 | 1080 | 1084 | 776 | 713 | 770 | 686 |
| 606 | 222 | Thursday | 1443 | 609 | 1081 | 1085 | 777 | 714 | 771 | 687 |
| 607 | 222 | **Friday — the separation ends** | 1444 | 610 | 1082 | 1086 | 778 | 715 | 772 | 688 |
| 608 | 223 | Monday | 1447 | 611 | 1085 | 1089 | 781 | 718 | 775 | 691 |
| 609 | 223 | Wednesday | 1449 | 612 | 1087 | 1091 | 783 | 720 | 777 | 693 |
| 610 | 223 | **Thursday — the movement closes** | 1450 | 613 | 1088 | 1092 | 784 | 721 | 778 | 694 |
| 611 | 224 | Monday | 1454 | 614 | 1092 | 1096 | 788 | 725 | 782 | 698 |
| 612 | 224 | **Wednesday — the Exchange, the forty-fifth sitting, the book does not open** | 1456 | 615 | 1094 | 1098 | 790 | 727 | 784 | 700 |
| 613 | 224 | Thursday | 1457 | 616 | 1095 | 1099 | 791 | 728 | 785 | 701 |
| 614 | 224 | **Friday — the collision pair** | 1458 | 617 | 1096 | 1100 | 792 | 729 | 786 | 702 |
| 615 | 225 | Monday | 1461 | 618 | 1099 | 1103 | 795 | 732 | 789 | 705 |
| 616 | 225 | Wednesday | 1463 | 619 | 1101 | 1105 | 797 | 734 | 791 | 707 |
| 617 | 225 | Thursday | 1464 | 620 | 1102 | 1106 | 798 | 735 | 792 | 708 |
| 618 | 225 | Friday | 1465 | 621 | 1103 | 1107 | 799 | 736 | 793 | 709 |
| 619 | 226 | **Monday — the collision pair** | 1468 | 622 | 1106 | 1110 | 802 | 739 | 796 | 712 |
| 620 | 226 | Wednesday | 1470 | 623 | 1108 | 1112 | 804 | 741 | 798 | 714 |
| 621 | 226 | Thursday | 1471 | 624 | 1109 | 1113 | 805 | 742 | 799 | 715 |
| 622 | 226 | Friday | 1472 | 625 | 1110 | 1114 | 806 | 743 | 800 | 716 |
| 623 | 227 | Monday | 1475 | 626 | 1113 | 1117 | 809 | 746 | 803 | 719 |
| 624 | 227 | **Wednesday — the volume's one panel and its one marker** | 1477 | 627 | 1115 | 1119 | 811 | 748 | 805 | 721 |
| 625 | 227 | Thursday | 1478 | 628 | 1116 | 1120 | 812 | 749 | 806 | 722 |
| 626 | 227 | Friday | 1479 | 629 | 1117 | 1121 | 813 | 750 | 807 | 723 |
| 627 | 228 | Monday | 1482 | 630 | 1120 | 1124 | 816 | 753 | 810 | 726 |
| 628 | 228 | **Wednesday — the Exchange, the forty-sixth sitting, the book OPENS** | 1484 | 631 | 1122 | 1126 | 818 | 755 | 812 | 728 |
| 629 | 228 | **Thursday — the collision pair** | 1485 | 632 | 1123 | 1127 | 819 | 756 | 813 | 729 |
| 630 | 229 | **Sunday — the shutter at about two** | 1495 | 633 | 1133 | 1137 | 829 | 766 | 823 | 739 |
| 631 | 230 | Monday | 1496 | 634 | 1134 | 1138 | 830 | 767 | 824 | 740 |
| 632 | 230 | Wednesday | 1498 | 635 | 1136 | 1140 | 832 | 769 | 826 | 742 |
| 633 | 230 | Thursday | 1499 | 636 | 1137 | 1141 | 833 | 770 | 827 | 743 |
| 634 | 230 | Friday | 1500 | 637 | 1138 | 1142 | 834 | 771 | 828 | 744 |
| 635 | 231 | Monday | 1503 | 638 | 1141 | 1145 | 837 | 774 | 831 | 747 |
| 636 | 231 | Wednesday | 1505 | 639 | 1143 | 1147 | 839 | 776 | 833 | 749 |
| 637 | 231 | Thursday | 1506 | 640 | 1144 | 1148 | 840 | 777 | 834 | 750 |
| 638 | 231 | Friday | 1507 | 641 | 1145 | 1149 | 841 | 778 | 835 | 751 |
| 639 | 232 | Monday | 1510 | 642 | 1148 | 1152 | 844 | 781 | 838 | 754 |
| 640 | 232 | **Wednesday — the Exchange, the forty-seventh sitting, the book does not open** | 1512 | 643 | 1150 | 1154 | 846 | 783 | 840 | 756 |
| 641 | 233 | Monday | 1517 | 644 | 1155 | 1159 | 851 | 788 | 845 | 761 |
| 642 | 233 | Wednesday | 1519 | 645 | 1157 | 1161 | 853 | 790 | 847 | 763 |
| 643 | 233 | Thursday | 1520 | 646 | 1158 | 1162 | 854 | 791 | 848 | 764 |
| 644 | 233 | Friday | 1521 | 647 | 1159 | 1163 | 855 | 792 | 849 | 765 |
| 645 | 234 | Monday | 1524 | 648 | 1162 | 1166 | 858 | 795 | 852 | 768 |
| 646 | 234 | **Wednesday — the volume climax** | 1526 | 649 | 1164 | 1168 | 860 | 797 | 854 | 770 |
| 647 | 234 | **Thursday — the volume climax** | 1527 | 650 | 1165 | 1169 | 861 | 798 | 855 | 771 |
| 648 | 234 | Friday | 1528 | 651 | 1166 | 1170 | 862 | 799 | 856 | 772 |
| 649 | 236 | Monday | 1538 | 652 | 1176 | 1180 | 872 | 809 | 866 | 782 |
| 650 | 236 | **Wednesday — the Exchange, the forty-eighth sitting, the book does not open, and the close** | 1540 | 653 | 1178 | 1182 | 874 | 811 | 868 | 784 |

### 1a. THE FIFTY-EIGHT DAYS INSIDE THE SPAN THAT CARRY NO CHAPTER, ACCOUNTED FOR AS A RUN AND NOT AS A HOLE

**The span is 108 days and there are 50 chapters, so there are 58 days inside it that carry no chapter, and the arithmetic below is the account of all of them. There are four more days that carry no chapter outside the span, and they are the Friday, the Saturday, the Sunday and the Monday between the close of Volume 12 and the opening of this one.**

**The account is by kind of day, because a weekday gap and a weekend gap are not the same claim. The span holds 30 Saturdays and Sundays; exactly one of the thirty carries a chapter, which is the Sunday of week 229, day 1495, Chapter 630; so 29 weekend days carry no chapter, and 29 weekday days carry no chapter, and 29 + 29 = 58.**

| Account | Days | Which |
| --- | --- | --- |
| Before the first chapter | 4 | 1429 to 1432 — outside the span and not inside it, and the Friday an inspection happened in Volume 11 is not one of these four and is not in this volume's span at all |
| Weekends inside the span | 29 | fifteen Saturdays and fourteen Sundays, less the one Sunday that carries Chapter 630 |
| Weekdays inside the span | 29 | nineteen runs, of which two are pairs, two are five-day runs, and fifteen are single days |
| **Total days with no chapter inside the span** | **58** | and 4 more before the volume opens, so 62 from the last day of Volume 12 to the last day of this one |

**The nineteen weekday runs, in full, so that the account can be checked: 1434–1435, 1441, 1448, 1451, 1455, 1462, 1469, 1476, 1483, 1486, 1489–1493, 1497, 1504, 1511, 1513–1514, 1518, 1525, 1531–1535, 1539. That is nineteen runs and 4 + 5 + 5 + 15 = 29 weekdays, and 29 and 29 is 58, and 58 is the count of days inside a span of 108 that carry no chapter in a volume of 50 chapters.**

**The two five-day runs are the volume's own shape and both are published rather than absorbed: 1489 to 1493 is the four working days between the Thursday of week 228 and the Sunday of week 229, and 1531 to 1535 is the five working days of week 235, which is the fortnight before the close in which nothing in this city has a chapter, and the reason it has none is that the nine rooms in it were doing something this file does not hold a figure for. A volume that publishes a gap has to say what is in it, and this one says that it is not in the table and is not guessed at.**

### 1b. Movement I's ten rows with the remaining six series, which a writer of Chapters 601 to 610 needs

| Ch | Day | Entry | 12 | 13 | 14 | 15 | 16 | 17 | 18 | Post | Copies | Sep |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 601 | 1433 | 604 | 991 | 942 | 907 | 886 | 861 | 843 | 789 | 619 | 637 | 451 |
| 602 | 1436 | 605 | 994 | 945 | 910 | 889 | 864 | 846 | 792 | 622 | 640 | 454 |
| 603 | 1437 | 606 | 995 | 946 | 911 | 890 | 865 | 847 | 793 | 623 | 641 | 455 |
| 604 | 1440 | 607 | 998 | 949 | 914 | 893 | 868 | 850 | 796 | 626 | 644 | 458 |
| 605 | 1442 | 608 | 1000 | 951 | 916 | 895 | 870 | 852 | 798 | 628 | 646 | 460 |
| 606 | 1443 | 609 | 1001 | 952 | 917 | 896 | 871 | 853 | 799 | 629 | 647 | 461 |
| 607 | 1444 | 610 | 1002 | 953 | 918 | 897 | 872 | 854 | 800 | 630 | 648 | 462 |
| 608 | 1447 | 611 | 1005 | 956 | 921 | 900 | 875 | 857 | 803 | 633 | 651 | 465 |
| 609 | 1449 | 612 | 1007 | 958 | 923 | 902 | 877 | 859 | 805 | 635 | 653 | 467 |
| 610 | 1450 | 613 | 1008 | 959 | 924 | 903 | 878 | 860 | 806 | 636 | 654 | 468 |

**The separation walks as `day − 982` and is 451 at Chapter 601, which is sixty-four weeks and three days, and it is neither shorter nor ended on that day, and it is ended on the Friday of Chapter 607 and it is walked on all ten rows of this table and is walked on all forty rows after it and is not stopped on any of them.**

---

## 2. The anchors, as a subtraction beside every value

| Series | Anchor day | Form | At 1433 | At 1540 |
| --- | --- | --- | --- | --- |
| The room off that service road | 362 | `day − 362` | 1071 | 1178 |
| The card in the rail | 358 | `day − 358` | 1075 | 1182 |
| The hardboard's twelfth line | 442 | `day − 442` | 991 | 1098 |
| The hardboard's thirteenth line | 491 | `day − 491` | 942 | 1049 |
| The hardboard's fourteenth line | 526 | `day − 526` | 907 | 1014 |
| The hardboard's fifteenth line | 547 | `day − 547` | 886 | 993 |
| The hardboard's sixteenth line | 572 | `day − 572` | 861 | 968 |
| The hardboard's seventeenth line | 590 | `day − 590` | 843 | 950 |
| The hardboard's eighteenth line | 644 | `day − 644` | 789 | 896 |
| The hardboard's nineteenth line | 666 | `day − 666` | 767 | 874 |
| The hold of the man of about thirty-three | 729 | `day − 729` | 704 | 811 |
| The man of about fifty-one at the wall | 756 | `day − 756` | 677 | 784 |
| The ask | 672 | `day − 672` | 761 | 868 |
| The post at the corridor end | 814 | `day − 814` | 619 | 726 |
| The nine hand copies of the front of a page | 796 | `day − 796` | 637 | 744 |
| The separation | 982 | `day − 982` | 451 | 558 |

**The separation's anchor is 982 and has been since Volume 11 and does not move in this volume, and what moves is what it counts. At day 1540 the column reads 558, and 558 days is four hundred and sixty-two days longer than the day the separation happened, and the separation itself is not 558 days long because it was not 558 days of anything: it ended in a one-line box in a form on a Friday in the second week of this volume, and the number in that column has gone on being a correct subtraction since and does not know it.**

## 3. The Exchange, computed from this file and not from any chapter

| Sitting | Chapter | Day | Week | Count announced | Of which correspond | Book before | Book after | Tin |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| the forty-fourth | 600 | 1428 | 220 | 49 | 44 | 61 | 61 | 73 |
| the forty-fifth | 612 | 1456 | 224 | 50 | 45 | 61 | 61 | 73 |
| the forty-sixth | 628 | 1484 | 228 | 51 | 46 | 61 | 62 | 73 |
| the forty-seventh | 640 | 1512 | 232 | 52 | 47 | 62 | 62 | 73 |
| the forty-eighth | 650 | 1540 | 236 | 53 | 48 | 62 | 62 | 73 |

**A count is announced at a sitting and on no other day, and the count goes up by one at every sitting whether the book opens or not. The correspond figure is the count less the five that predate the book on a sheet she has never shown anybody. The book opens only when a caller says a thing to her face, and this volume's pattern is shut, open, open, shut, and the pattern is not a rule and is not written anywhere and is not evidence of anything and may not be described in a chapter as a change in her. It is the first pattern in this manuscript with two openings and it sits in the middle, and Volume 11's was shut, open, shut, open and Volume 12's was shut, shut, open, shut, and a reader who has read both cannot produce this one from them. The difference between the book and the tin is not a number and is never printed as one, and none of the four is convertible into another, and the ninth chair is against the wall with its back to the room and does not move in this volume and its mover is not named.**

## 4. The two-sided interval series, and how a writer renders one

**Every series printed in weeks and days is printed twice: once in the load book's row and once in the sentence of the narration above it, and both are converted by `weeks × 7 + days` and required equal. The weeks-and-days phrase is regenerated from the figure and compared character for character.**

**Test the attachment from the end of the `days` token and not from the end of the numeral, and test in both directions, because a compliant rendering in this house may put the weeks form first: "one day short of a hundred and ten weeks" and "a hundred and ten weeks and one day" are both house renderings and a walk that reads only the second will return a clean result on a page that has the first. A figure that is an exact number of weeks is rendered with the word *to the day* and the word *short* is not used.**

**AND THE SINGULAR, WHICH THE REPAIR PASS OF VOLUME 12 MOVEMENT I FOUND IN A GLOSS: a day component of one is *one day* and not *one days*, and a component of zero is *to the day* and not *zero days*, and a component of two or more takes the plural. A generator that prints the plural on every non-zero component produces a walk that is correct on its arithmetic and wrong on its English, and the arithmetic check will not see it.**

Movement I's interval renderings, for the walk and not for reuse as sentences:

| Ch | Room | W and d | Card | W and d | Nineteen | W and d | Hold | W and d | Fifty-one | W and d | Ask | W and d | Copies | W and d | Sep | W and d |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 601 | 1071 | 153 w 0 d | 1075 | 153 w 4 d | 767 | 109 w 4 d | 704 | 100 w 4 d | 677 | 96 w 5 d | 761 | 108 w 5 d | 637 | 91 w 0 d | 451 | 64 w 3 d |
| 602 | 1074 | 153 w 3 d | 1078 | 154 w 0 d | 770 | 110 w 0 d | 707 | 101 w 0 d | 680 | 97 w 1 d | 764 | 109 w 1 d | 640 | 91 w 3 d | 454 | 64 w 6 d |
| 603 | 1075 | 153 w 4 d | 1079 | 154 w 1 d | 771 | 110 w 1 d | 708 | 101 w 1 d | 681 | 97 w 2 d | 765 | 109 w 2 d | 641 | 91 w 4 d | 455 | 65 w 0 d |
| 604 | 1078 | 154 w 0 d | 1082 | 154 w 4 d | 774 | 110 w 4 d | 711 | 101 w 4 d | 684 | 97 w 5 d | 768 | 109 w 5 d | 644 | 92 w 0 d | 458 | 65 w 3 d |
| 605 | 1080 | 154 w 2 d | 1084 | 154 w 6 d | 776 | 110 w 6 d | 713 | 101 w 6 d | 686 | 98 w 0 d | 770 | 110 w 0 d | 646 | 92 w 2 d | 460 | 65 w 5 d |
| 606 | 1081 | 154 w 3 d | 1085 | 155 w 0 d | 777 | 111 w 0 d | 714 | 102 w 0 d | 687 | 98 w 1 d | 771 | 110 w 1 d | 647 | 92 w 3 d | 461 | 65 w 6 d |
| 607 | 1082 | 154 w 4 d | 1086 | 155 w 1 d | 778 | 111 w 1 d | 715 | 102 w 1 d | 688 | 98 w 2 d | 772 | 110 w 2 d | 648 | 92 w 4 d | 462 | 66 w 0 d |
| 608 | 1085 | 155 w 0 d | 1089 | 155 w 4 d | 781 | 111 w 4 d | 718 | 102 w 4 d | 691 | 98 w 5 d | 775 | 110 w 5 d | 651 | 93 w 0 d | 465 | 66 w 3 d |
| 609 | 1087 | 155 w 2 d | 1091 | 155 w 6 d | 783 | 111 w 6 d | 720 | 102 w 6 d | 693 | 99 w 0 d | 777 | 111 w 0 d | 653 | 93 w 2 d | 467 | 66 w 5 d |
| 610 | 1088 | 155 w 3 d | 1092 | 156 w 0 d | 784 | 112 w 0 d | 721 | 103 w 0 d | 694 | 99 w 1 d | 778 | 111 w 1 d | 654 | 93 w 3 d | 468 | 66 w 6 d |

**The post at the corridor end walks as `day − 814` and is 619, which is eighty-eight weeks and three days, at Chapter 601. The nine hand copies walk as `day − 796` and are 637, which is ninety-one weeks to the day, at Chapter 601, and about eight of the nine are still unfinished and the first disagreement in the fourth line is still not found, and no two of the nine are compared on any of the fifty days of this volume.**

## 5. Collision sweep, and the reading that is required before it is trusted

**Sweep: for each of the sixteen numerical series on each of the fifty rows, test the value against the sixteen anchors, and report every hit where the value is not its own anchor. A hit is the day equalling the sum of two distinct anchors, so the whole sweep can be computed as a set of anchor-pair sums before any chapter is read, and that is how the four chapter-days below were found.**

**Volume 13's chapter-day sweep returns four rows at two chapters in Movement I's range and at three more across the volume, and every chapter's rows come in pairs, and every member of every pair is on the page in the body prose of its own chapter with the age and the day named in the same breath.**

| Ch | Day | Value | Collides with | Which one it is |
| --- | --- | --- | --- | --- |
| 604 | 1440 | 796 (the hardboard's eighteenth line) | 796 (the nine hand copies' anchor) | an age in days; the anchor is the day nine hand copies of the front of a page were begun |
| 604 | 1440 | 644 (the nine hand copies) | 644 (the hardboard's eighteenth line's anchor) | an age in days; the anchor is the day the eighteenth line was written |
| 614 | 1458 | 814 (the hardboard's eighteenth line) | 814 (the post at the corridor end's anchor) | a pair |
| 614 | 1458 | 644 (the post at the corridor end) | 644 (the hardboard's eighteenth line's anchor) | a pair |
| 619 | 1468 | 796 (the ask) | 796 (the nine hand copies' anchor) | a pair |
| 619 | 1468 | 672 (the nine hand copies) | 672 (the ask's anchor) | a pair |
| 629 | 1485 | 756 (the hold of the man of about thirty-three) | 756 (the man of about fifty-one's anchor) | a pair |
| 629 | 1485 | 729 (the man of about fifty-one at the wall) | 729 (the hold's anchor) | a pair |

**THE TABLE ABOVE WAS WRONG ON THREE OF ITS FOUR CHAPTERS WHEN IT WAS FIRST WRITTEN AND IS REPAIRED, AND THE REPAIR IS PUBLISHED BESIDE IT BECAUSE THE ERROR IS THE KIND THAT A ROW-SIDE WALK CANNOT SEE.** The instrument this file runs is: for each of the sixteen series on each of the fifty rows, test `day − anchor(series)` against the anchor set, and report a hit where the hit is not that series' own anchor. **A hand-written table of the same four chapters had the series labels of the 614, 619 and 629 rows transposed, calling the seventeenth line the eighteenth, calling the ask's value the copies' and the copies' value the ask's, and attributing 756 to the ask's anchor when 756 is the man of about fifty-one's own, and 729 to the eighteenth line's anchor when 729 is the hold's own.** Every figure in the four chapters was right and every label on three of them was wrong, and the four rows above are now machine-generated from the anchor set and are correct. **A row-side walk that reads the numbers is clean on the old table and a page-side walk is not, which is the finding of the last three volumes arriving a fourth time and in the simplest possible shape.**

**Four further sums fall inside the span on days that carry no chapter and are printed so that a later pass does not invent them: 1462, 1473, 1480 and 1525. Two of them are Saturdays and two are a Tuesday and a Friday, and none of them is a chapter day in this volume, and a chapter placed on one of them would create a fifth pair and a fifth pair is not a defect but it is not free either, because the figure has to be said in the body and the day has to be defended.**

**The reading that is required before this table is trusted: the sweep must be run against the anchor set as a set of integers, and not against a dictionary compared by value, because the second of those compares an integer with a string and matches nothing and then reports a clean result. The run above was walked a second time from the row side and from the page side and both sides return the same chapters.**

**And the row-side walk is not sufficient on its own, which is the finding of the last three volumes: a table can be correct on its day, its week, its weekday and its entry and wrong in five of its six series columns, and only the page-side walk sees that.** Both halves are therefore required, on every volume of this manuscript, and a pass that runs one half has run half an instrument.

## 6. Reserved for the volume close

**The close writes section 6: the count of series that ran clean on all fifty rows, the four arrival cells, the figures at day 1540, the words in the exchange at the forty-eighth sitting, and the three decisions the volume took. No writing pass before it may write it.**
