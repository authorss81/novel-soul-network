# Arithmetic and calendar — Volume 12

**`workspace/volume-12/ARITHMETIC-AND-CALENDAR.md`, at the volume root, beside `batch-0001/`, and not inside any phase directory. It is a volume-level working file and not a phase: it holds no `PROMPT.md` and no marker, so the controller's selection rule — the first directory under `workspace/` holding a `PROMPT.md` and no `.done` — is unaffected by it. `workspace/volume-06/ARITHMETIC-AND-CALENDAR.md` through `workspace/volume-11/ARITHMETIC-AND-CALENDAR.md` are the precedents and sit in the same place.**

**It was written with `outline/volume-12.md` and before Chapter 551. Sections 1 to 5 are a plan of figures and not a table read back off chapters, and every number below is a day number minus a named anchor day and can be recomputed by anybody in about a minute. Section 6 is owned by the volume close and no writing pass before it may write it.**

**It is a table and a set of series. It is not a prompt, it plans nothing, and it derives nothing.**

**Four rules, and they are the same four as the six files before it.**

1. **No day number may be printed in a chapter.** No month-name, no month-date, no day-date, no year. The only calendar nouns permitted are the season words, the week and the day inside the week. **All interval figures are spelled out in words, and a figure that is an exact number of weeks is rendered with the word *to the day* and is not rendered with the word *short*.** No chapter of this volume prints how far away a town is, and a town is described by how long the bus takes or by nothing at all.
2. **A day is assigned only by section 1 of this file.** Where this file and a live batch prompt disagree on a day, **the batch prompt is right for its ten days and this file is right for the run**, and a batch prompt that disagrees with the table below on a day is a defect to be corrected in place and recorded.
3. **Weeks run Monday to Sunday. Week 88 = Monday 502 to Sunday 508, so the Monday of week _n_ is 502 + 7 × (_n_ − 88) and is also 7 × _n_ − 114, and a chapter's day is that week's named weekday with Monday at zero.** The detector is `week = (day − 502) // 7 + 88` and the weekday is `wd = (day − 502) mod 7` against Monday-first. **A value that disagrees with the detector is the value that is wrong, and the detector is the one that agrees with the sittings inherited from `outline/series.md` and with the repaired week table in `outline/volume-11.md`.**
4. **The interval map's two-day offset from the Monday of week thirty-one is inherited, is recorded for the nineteenth time, and is not to be re-derived from the anchor.** No chapter in this manuscript has ever printed a day number, so no prose depends on any of it.

---

## 0. What this file inherits

### 0.1 THE CHAIN, CHECKED ONCE AND NOT RE-DERIVED

**The inherited anchors are printed at the head of `outline/volume-12.md` and are not duplicated here, because a table of anchors is a second place in this repository a figure can be copied from and the sixth time that has happened has been a defect. The chain gives 1316 as the Wednesday of week two hundred and four, which is the day Volume 11 closed on, and 1321 as the Monday of the week after, and that is the whole of the check.**

### 0.2 THE DAY ZERO, MADE EXPLICITLY AND PRINTED, WITH THE OPENINGS THAT WERE REFUSED

**Chapter 551 is day 1321, the Monday of week two hundred and five. In one sentence: Volume 12 opens on the first Monday after the week Volume 11 closed in, and 1321 is 1316 + 5, and 1316 is the Wednesday of week 204, and 1318 is the Monday of week 205 minus three, and 1321 is 1316 + 5.**

**It is a decision and not a consequence, and the reason is printed so that a later pass can see the choice rather than the result: four days of bus travel is the slowest thing in this manuscript and a volume whose subject is four places four days away cannot spend its first two days on a bus getting to the first place. Four other openings were available and were not taken: 1317 is a Saturday and this manuscript does not open a volume at a weekend; 1319 is a Tuesday and would have opened the volume on the day a printed sheet had already been answered by most of the four places; 1323 is a Wednesday and would have handed the first chapter to a day with a rule of its own, which is the Exchange's day and is not this volume's; and 1328 is the Monday of the second week, which is conventional and would have spent four days of a halt in a gap.**

### 0.3 WHAT VOLUME 11 HANDED OVER THAT A FIGURE HERE DEPENDS ON, RESTATED WITH ITS SUBTRACTION BESIDE IT

| Figure | Arithmetic | Value |
| --- | --- | --- |
| Chapter 550 | the Wednesday of week 204, 502 + 7 × 116 + 2 | 1316 |
| Chapter 551 | 1316 + 5, and the Monday of week 205, 502 + 7 × 117 | 1321 |
| The first sitting in this volume | 1321 + 23, and the Wednesday of week 208, 502 + 7 × 120 + 2 | 1344 |
| The whole of Volume 12 | 1428 − 1321 | 107 days |
| The whole of Volume 12 inclusive of both ends | 1428 − 1321 + 1 | 108 days |
| The first sitting to the close | 1428 − 1344 | 84 days |
| The room at Chapter 551 and at Chapter 600 | 1321 − 362, and 1428 − 362 | 959, and 1066 |
| The card at Chapter 551 and at Chapter 600 | 1321 − 358, and 1428 − 358 | 963, and 1070 |
| The nineteen lines at Chapter 551 and at Chapter 600 | 1321 − 666, and 1428 − 666 | 655, and 762 |
| The hold at Chapter 551 and at Chapter 600 | 1321 − 729, and 1428 − 729 | 592, and 699 |
| The ask at Chapter 551 and at Chapter 600 | 1321 − 672, and 1428 − 672 | 649, and 756 |
| The man of about fifty-one at Chapter 551 and at Chapter 600 | 1321 − 756, and 1428 − 756 | 565, and 672 |
| The turn of the movement, Chapter 560 to Chapter 561 | 1342 − 1341 | 1 day |

### 0.4 THE FOUR FREE CHECKS, WITH THEIR SIGNS, IN FULL

A check that publishes its clean set and not its limits cannot be told apart from a check that was never run, so all four are printed here with their limits and their signs, and all four are walked on all fifty rows of section 1.

| Check | Expression | Constant | Sign as printed |
| --- | --- | --- | --- |
| The card-minus-room invariant | `(day − 358) − (day − 362)` | 4 | {4} |
| The fourteen-less-fifteen | `(day − 526) − (day − 547)` | 21 | {21} |
| The fifty-first-less-hold | `(day − 756) − (day − 729)` | −27 | {−27} |
| The eighteen-less-sixteen | `(day − 644) − (day − 572)` | −72 | {−72} |

### 0.5 THE SPENT-AGE CLASS GETS AN INSTRUMENT AND NOT ONLY A PROHIBITION

**For each file: extract every occurrence of a spent age, take the noun phrase it sits in, and record whether a person is the subject of it. A spent age on a person established in this manuscript is permitted and is canon. A spent age on a new person is a finding and not a permission. A raw substring count of the spent ages is not an instrument, because a new person can carry a spent age any number of times and a raw count cannot see who is carrying it.** Movement I names two people and neither is given a spent age.

---

## 1. The day map, all fifty chapters, with the load-book entry on each row

| Ch | Week | Day | Day no. | Entry | Room | Card | 19 | Hold | Ask | 51 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 551 | 205 | **Monday — the volume opens** | 1321 | 554 | 959 | 963 | 655 | 592 | 649 | 565 |
| 552 | 205 | Thursday | 1324 | 555 | 962 | 966 | 658 | 595 | 652 | 568 |
| 553 | 205 | Friday | 1325 | 556 | 963 | 967 | 659 | 596 | 653 | 569 |
| 554 | 206 | Monday | 1328 | 557 | 966 | 970 | 662 | 599 | 656 | 572 |
| 555 | 206 | Wednesday | 1330 | 558 | 968 | 972 | 664 | 601 | 658 | 574 |
| 556 | 206 | Thursday | 1331 | 559 | 969 | 973 | 665 | 602 | 659 | 575 |
| 557 | 206 | Friday | 1332 | 560 | 970 | 974 | 666 | 603 | 660 | 576 |
| 558 | 207 | Monday | 1335 | 561 | 973 | 977 | 669 | 606 | 663 | 579 |
| 559 | 207 | Thursday | 1338 | 562 | 976 | 980 | 672 | 609 | 666 | 582 |
| 560 | 207 | **Sunday** | 1341 | 563 | 979 | 983 | 675 | 612 | 669 | 585 |
| 561 | 208 | Monday | 1342 | 564 | 980 | 984 | 676 | 613 | 670 | 586 |
| 562 | 208 | **Wednesday — the Exchange, the forty-first sitting, the book SHUTS** | 1344 | 565 | 982 | 986 | 678 | 615 | 672 | 588 |
| 563 | 208 | Thursday | 1345 | 566 | 983 | 987 | 679 | 616 | 673 | 589 |
| 564 | 208 | Friday | 1346 | 567 | 984 | 988 | 680 | 617 | 674 | 590 |
| 565 | 209 | Monday | 1349 | 568 | 987 | 991 | 683 | 620 | 677 | 593 |
| 566 | 209 | Wednesday | 1351 | 569 | 989 | 993 | 685 | 622 | 679 | 595 |
| 567 | 209 | Thursday | 1352 | 570 | 990 | 994 | 686 | 623 | 680 | 596 |
| 568 | 209 | Friday | 1353 | 571 | 991 | 995 | 687 | 624 | 681 | 597 |
| 569 | 210 | Monday | 1356 | 572 | 994 | 998 | 690 | 627 | 684 | 600 |
| 570 | 210 | Thursday | 1359 | 573 | 997 | 1001 | 693 | 630 | 687 | 603 |
| 571 | 211 | Monday | 1363 | 574 | 1001 | 1005 | 697 | 634 | 691 | 607 |
| 572 | 211 | Wednesday | 1365 | 575 | 1003 | 1007 | 699 | 636 | 693 | 609 |
| 573 | 211 | Thursday | 1366 | 576 | 1004 | 1008 | 700 | 637 | 694 | 610 |
| 574 | 211 | Friday — **the volume's one panel and its one marker** | 1367 | 577 | 1005 | 1009 | 701 | 638 | 695 | 611 |
| 575 | 212 | Monday | 1370 | 578 | 1008 | 1012 | 704 | 641 | 698 | 614 |
| 576 | 212 | **Wednesday — the Exchange, the forty-second sitting, the book SHUTS** | 1372 | 579 | 1010 | 1014 | 706 | 643 | 700 | 616 |
| 577 | 212 | Thursday | 1373 | 580 | 1011 | 1015 | 707 | 644 | 701 | 617 |
| 578 | 212 | Friday | 1374 | 581 | 1012 | 1016 | 708 | 645 | 702 | 618 |
| 579 | 213 | Monday | 1377 | 582 | 1015 | 1019 | 711 | 648 | 705 | 621 |
| 580 | 213 | Thursday | 1380 | 583 | 1018 | 1022 | 714 | 651 | 708 | 624 |
| 581 | 215 | Monday | 1391 | 584 | 1029 | 1033 | 725 | 662 | 719 | 635 |
| 582 | 215 | Wednesday | 1393 | 585 | 1031 | 1035 | 727 | 664 | 721 | 637 |
| 583 | 215 | Thursday | 1394 | 586 | 1032 | 1036 | 728 | 665 | 722 | 638 |
| 584 | 215 | Friday | 1395 | 587 | 1033 | 1037 | 729 | 666 | 723 | 639 |
| 585 | 216 | Monday | 1398 | 588 | 1036 | 1040 | 732 | 669 | 726 | 642 |
| 586 | 216 | **Wednesday — the Exchange, the forty-third sitting, the book OPENS** | 1400 | 589 | 1038 | 1042 | 734 | 671 | 728 | 644 |
| 587 | 216 | Thursday | 1401 | 590 | 1039 | 1043 | 735 | 672 | 729 | 645 |
| 588 | 216 | Friday | 1402 | 591 | 1040 | 1044 | 736 | 673 | 730 | 646 |
| 589 | 217 | Monday | 1405 | 592 | 1043 | 1047 | 739 | 676 | 733 | 649 |
| 590 | 217 | Thursday | 1408 | 593 | 1046 | 1050 | 742 | 679 | 736 | 652 |
| 591 | 218 | Monday | 1412 | 594 | 1050 | 1054 | 746 | 683 | 740 | 656 |
| 592 | 218 | Wednesday | 1414 | 595 | 1052 | 1056 | 748 | 685 | 742 | 658 |
| 593 | 218 | Thursday | 1415 | 596 | 1053 | 1057 | 749 | 686 | 743 | 659 |
| 594 | 218 | Friday | 1416 | 597 | 1054 | 1058 | 750 | 687 | 744 | 660 |
| 595 | 219 | Monday | 1419 | 598 | 1057 | 1061 | 753 | 690 | 747 | 663 |
| 596 | 219 | Wednesday | 1421 | 599 | 1059 | 1063 | 755 | 692 | 749 | 665 |
| 597 | 219 | Thursday | 1422 | 600 | 1060 | 1064 | 756 | 693 | 750 | 666 |
| 598 | 219 | Friday | 1423 | 601 | 1061 | 1065 | 757 | 694 | 751 | 667 |
| 599 | 220 | Monday | 1426 | 602 | 1064 | 1068 | 760 | 697 | 754 | 670 |
| 600 | 220 | **Wednesday — the Exchange, the forty-fourth sitting, the book SHUTS, and the close** | 1428 | 603 | 1066 | 1070 | 762 | 699 | 756 | 672 |

### 1a. THE SIXTY-TWO DAYS INSIDE THE SPAN THAT CARRY NO CHAPTER, ACCOUNTED FOR AS A RUN AND NOT AS A HOLE

**The span is 108 days and there are 50 chapters, so there are 58 days inside it that carry no chapter, and the arithmetic below is the account of all of them. There is one more day that carries no chapter outside the span, and it is the Friday of the week Volume 11 closed on.**

| Account | Days | Which |
| --- | --- | --- |
| Before the first chapter | 4 | 1317, 1318, 1319, 1320 — outside the span and not inside it, and the Friday an inspection happened is one of the four and a printed sheet went out on the Thursday and is one of the four |
| Weekends inside the span | 29 | fifteen Saturdays and fifteen Sundays in 108 days, of which exactly one carries a chapter, which is the Sunday of week 207, day 1341, Chapter 560 |
| The tail of week 213 and the whole of week 214 | 6 | 1381, and 1384 to 1388 — the five weekdays of week 214, and its Saturday and Sunday are already counted as weekends |
| The tail of week 217 | 1 | 1409, a Tuesday, and the Saturday and the Sunday either side of it are already counted as weekends |
| Seventeen other weekday gaps | 22 | twenty runs in all, of which three are the two runs above and seventeen are single days or pairs, and the longest is the pair 1322 to 1323 and the pair 1336 to 1337 |
| **Total days with no chapter inside the span** | **58** | and 4 more before the volume opens, so 62 from the Friday of Volume 11's close to the last day of this one |

**The twenty weekday runs, in full, so that the account can be checked: 1322–1323, 1329, 1336–1337, 1339, 1343, 1350, 1357–1358, 1360, 1364, 1371, 1378–1379, 1381, 1384–1388, 1392, 1399, 1406–1407, 1409, 1413, 1420, 1427. That is twenty runs and twenty-nine weekdays, and twenty-nine and twenty-nine is 58, and 58 is the count of days inside a span of 108 that carry no chapter in a volume of 50 chapters.**

### 1b. Movement I's ten rows with the remaining six series, which a writer of Chapters 551 to 560 needs

| Ch | Day | Entry | 12 | 13 | 14 | 15 | 16 | 17 | 18 | Post | Copies | Sep |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 551 | 1321 | 554 | 879 | 830 | 795 | 774 | 749 | 731 | 677 | 507 | 525 | 339 |
| 552 | 1324 | 555 | 882 | 833 | 798 | 777 | 752 | 734 | 680 | 510 | 528 | 342 |
| 553 | 1325 | 556 | 883 | 834 | 799 | 778 | 753 | 735 | 681 | 511 | 529 | 343 |
| 554 | 1328 | 557 | 886 | 837 | 802 | 781 | 756 | 738 | 684 | 514 | 532 | 346 |
| 555 | 1330 | 558 | 888 | 839 | 804 | 783 | 758 | 740 | 686 | 516 | 534 | 348 |
| 556 | 1331 | 559 | 889 | 840 | 805 | 784 | 759 | 741 | 687 | 517 | 535 | 349 |
| 557 | 1332 | 560 | 890 | 841 | 806 | 785 | 760 | 742 | 688 | 518 | 536 | 350 |
| 558 | 1335 | 561 | 893 | 844 | 809 | 788 | 763 | 745 | 691 | 521 | 539 | 353 |
| 559 | 1338 | 562 | 896 | 847 | 812 | 791 | 766 | 748 | 694 | 524 | 542 | 356 |
| 560 | 1341 | 563 | 899 | 850 | 815 | 794 | 769 | 751 | 697 | 527 | 545 | 359 |

**The separation walks as `day − 982` and is 339 at Chapter 551, which is forty-eight weeks and three days, and it is not shorter and not ended, and about four days of bus travel each way this week did not shorten it by a minute.**

---

## 2. The anchors, as a subtraction beside every value

| Series | Anchor day | Form | At 1321 | At 1341 | At 1428 |
| --- | --- | --- | --- | --- | --- |
| The room off that service road | 362 | `day − 362` | 959 | 979 | 1066 |
| The card in the rail | 358 | `day − 358` | 963 | 983 | 1070 |
| The hardboard's twelfth line | 442 | `day − 442` | 879 | 899 | 986 |
| The hardboard's thirteenth line | 491 | `day − 491` | 830 | 850 | 937 |
| The hardboard's fourteenth line | 526 | `day − 526` | 795 | 815 | 902 |
| The hardboard's fifteenth line | 547 | `day − 547` | 774 | 794 | 881 |
| The hardboard's sixteenth line | 572 | `day − 572` | 749 | 769 | 856 |
| The hardboard's seventeenth line | 590 | `day − 590` | 731 | 751 | 838 |
| The hardboard's eighteenth line | 644 | `day − 644` | 677 | 697 | 784 |
| The hardboard's nineteenth line | 666 | `day − 666` | 655 | 675 | 762 |
| The hold of the man of about thirty-three | 729 | `day − 729` | 592 | 612 | 699 |
| The man of about fifty-one at the wall | 756 | `day − 756` | 565 | 585 | 672 |
| The ask | 672 | `day − 672` | 649 | 669 | 756 |
| The post at the corridor end | 814 | `day − 814` | 507 | 527 | 614 |
| The nine hand copies of the front of a page | 796 | `day − 796` | 525 | 545 | 632 |
| The separation | 982 | `day − 982` | 339 | 359 | 446 |

**The separation's anchor is 982 and not 222, and the reason is that 222 was its value at day 1204 and 1204 − 222 is 982. A figure that is printed once as a value and once as an anchor is two figures wearing one coat, and this repository has lost a repair to exactly that.**

## 3. The Exchange, computed from this file and not from any chapter

| Sitting | Chapter | Day | Week | Count announced | Of which correspond | Book before | Book after | Tin |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| the fortieth | 550 | 1316 | 204 | 45 | 40 | 59 | 60 | 73 |
| the forty-first | 562 | 1344 | 208 | 46 | 41 | 60 | 60 | 73 |
| the forty-second | 576 | 1372 | 212 | 47 | 42 | 60 | 60 | 73 |
| the forty-third | 586 | 1400 | 216 | 48 | 43 | 60 | 61 | 73 |
| the forty-fourth | 600 | 1428 | 220 | 49 | 44 | 61 | 61 | 73 |

**A count is announced at a sitting and on no other day, and the count goes up by one at every sitting whether the book opens or not. The correspond figure is the count less the five that predate the book on a sheet she has never shown anybody. The book opens only when a caller says a thing to her face, and this volume's pattern is shut, shut, open, shut, and the pattern is not a rule and is not written anywhere and is not evidence of anything and may not be described in a chapter as a change in her. The difference between the book and the tin is not a number and is never printed as one, and none of the four is convertible into another, and the ninth chair is against the wall with its back to the room and does not move in this volume and its mover is not named.**

**Volume 11's pattern was shut, open, shut, open. This volume's is shut, shut, open, shut. A volume that repeats its predecessor's terms is a volume a reader can predict, and the third term is the one term in five that could not have been guessed from Volume 11's shape without reading the calendar.**

## 4. The two-sided interval series, and how a writer renders one

**Every series printed in weeks and days is printed twice: once in the load book's row and once in the sentence of the narration above it, and both are converted by `weeks × 7 + days` and required equal. The weeks-and-days phrase is regenerated from the figure and compared character for character.**

**Test the attachment from the end of the `days` token and not from the end of the numeral, and test in both directions, because a compliant rendering in this house may put the weeks form first: "one day short of seventy-six weeks" and "seventy-six weeks and one day" are both house renderings and a walk that reads only the second will return a clean result on a page that has the first. A figure that is an exact number of weeks is rendered with the word *to the day* and the word *short* is not used.**

Movement I's interval renderings, for the walk and not for reuse as sentences:

| Ch | Ask | W and d | Man of fifty-one | W and d | Hold | W and d | Room | W and d | Nineteen | W and d |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 551 | 649 | 92 w 5 d | 565 | 80 w 5 d | 592 | 84 w 4 d | 959 | 137 w 0 d | 655 | 93 w 4 d |
| 552 | 652 | 93 w 1 d | 568 | 81 w 1 d | 595 | 85 w 0 d | 962 | 137 w 3 d | 658 | 94 w 0 d |
| 553 | 653 | 93 w 2 d | 569 | 81 w 2 d | 596 | 85 w 1 d | 963 | 137 w 4 d | 659 | 94 w 1 d |
| 554 | 656 | 93 w 5 d | 572 | 81 w 5 d | 599 | 85 w 4 d | 966 | 138 w 0 d | 662 | 94 w 4 d |
| 555 | 658 | 94 w 0 d | 574 | 82 w 0 d | 601 | 85 w 6 d | 968 | 138 w 2 d | 664 | 94 w 6 d |
| 556 | 659 | 94 w 1 d | 575 | 82 w 1 d | 602 | 86 w 0 d | 969 | 138 w 3 d | 665 | 95 w 0 d |
| 557 | 660 | 94 w 2 d | 576 | 82 w 2 d | 603 | 86 w 1 d | 970 | 138 w 4 d | 666 | 95 w 1 d |
| 558 | 663 | 94 w 5 d | 579 | 82 w 5 d | 606 | 86 w 4 d | 973 | 139 w 0 d | 669 | 95 w 4 d |
| 559 | 666 | 95 w 1 d | 582 | 83 w 1 d | 609 | 87 w 0 d | 976 | 139 w 3 d | 672 | 96 w 0 d |
| 560 | 669 | 95 w 4 d | 585 | 83 w 4 d | 612 | 87 w 3 d | 979 | 139 w 6 d | 675 | 96 w 3 d |

**The post at the corridor end walks as `day − 814` and is 507, which is seventy-two weeks and three days, at Chapter 551. The nine hand copies walk as `day − 796` and are 525, which is seventy-five weeks to the day, at Chapter 551, and about eight of the nine are still unfinished and the first disagreement in the fourth line is still not found. The separation walks as `day − 982` and is 339, which is forty-eight weeks and three days, at Chapter 551, and about four days of bus travel each way in that week did not shorten it by a minute.**

## 5. Collision sweep, and the reading that is required before it is trusted

**Sweep: for each of the fifteen numerical series on each of the fifty rows, test the value against the fifteen anchors, and report every hit where the value is not its own anchor. Volume 12's sweep returns twenty rows at ten chapters, and every chapter's rows come in pairs. Movement I's rows are four, at Chapters 554 and 559, and every member of every pair is on the page in the body prose, and the chapter says in the same breath which figure is an age and which is a day something happened.**

| Ch | Day | Value | Collides with | Which one it is |
| --- | --- | --- | --- | --- |
| 554 | 1328 | 756 (the sixteenth line) | 756 (the fifty-first's anchor) | an age; the anchor is the day the man of about fifty-one first sat down at that wall |
| 554 | 1328 | 572 (the fifty-first) | 572 (the sixteenth line's anchor) | an age; the anchor is the day the sixteenth line was written |
| 559 | 1338 | 672 (the nineteenth line) | 672 (the ask's anchor) | an age; the anchor is the day the ask was put to somebody |
| 559 | 1338 | 666 (the ask) | 666 (the nineteenth line's anchor) | an age in days; the anchor is the day the nineteenth line was written |
| 562 | 1344 | 982 (the room) | 982 (the separation's anchor) | an age; the anchor is the day the separation happened |
| 562 | 1344 | 362 (the separation) | 362 (the room's anchor) | an age; the anchor is the day that room was first used |
| 564 | 1346 | 756 (the seventeenth line) | 756 (the fifty-first's anchor) | a pair |
| 577 | 1373 | 729 (the eighteenth line) | 729 (the hold's anchor) | a pair |
| 584 | 1395 | 729 (the nineteenth line) | 729 (the hold's anchor) | a pair |
| 586 | 1400 | 756 (the eighteenth line) | 756 (the fifty-first's anchor) | a pair |
| 587 | 1401 | 672 (the hold) | 672 (the ask's anchor) | a pair |
| 597 | 1422 | 756 (the nineteenth line) | 756 (the fifty-first's anchor) | a pair |
| 600 | 1428 | 672 (the fifty-one) | 672 (the ask's anchor) | a pair |
| 600 | 1428 | 756 (the ask) | 756 (the fifty-first's anchor) | a pair |

**The two rows at Chapter 562 are the first time in this repository that the separation series has collided with anything, and they collide with the room, and the two figures are on the same afternoon and are not joined to each other in any chapter, because a separation is a day something happened and a room is an age and the sentence that joins them is the sentence the volume may not write.**

**The reading that is required before this table is trusted: the sweep must be run against the anchor set as a set of integers, and not against a dictionary compared by value, because the second of those compares an integer with a string and matches nothing and then reports a clean result. The run above was walked a second time from the row side and from the page side and both sides return the same ten chapters.**

**And the row-side walk is not sufficient on its own, which is the finding of the last three volumes: a table can be correct on its day, its week, its weekday and its entry and wrong in five of its six series columns, and only the page-side walk sees that.** Both halves are therefore required, on every volume of this manuscript, and a pass that runs one half has run half an instrument.

## 6. Reserved for the volume close

**The close writes section 6: the count of series that ran clean on all fifty rows, the four arrival cells, the figures at day 1428, the words in the exchange at the forty-fourth sitting, and the three decisions the volume took. No writing pass before it may write it.**
