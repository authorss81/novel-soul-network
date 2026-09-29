# Arithmetic and calendar — Volume 11

**`workspace/volume-11/ARITHMETIC-AND-CALENDAR.md`, at the volume root, beside `batch-0001/`, and not inside any phase directory. It is a volume-level working file and not a phase: it holds no `PROMPT.md` and no marker, so the controller's selection rule — the first directory under `workspace/` holding a `PROMPT.md` and no `.done` — is unaffected by it. `workspace/volume-06/ARITHMETIC-AND-CALENDAR.md` through `workspace/volume-10/ARITHMETIC-AND-CALENDAR.md` are the precedents and sit in the same place.**

**It was written with `outline/volume-11.md` and before Chapter 501. Sections 1 to 5 are a plan of figures and not a table read back off chapters, and every number below is a day number minus a named anchor day and can be recomputed by anybody in about a minute. Section 6 is owned by the volume close and no writing pass before it may write it.**

**It is a table and a set of series. It is not a prompt, it plans nothing, and it derives nothing.**

**Four rules, and they are the same four as the five files before it.**

1. **No day number may be printed in a chapter.** No month-name, no month-date, no day-date, no year. The only calendar nouns permitted are the season words, the week and the day inside the week. **All interval figures are spelled out in words, and this volume adds no new noun: no chapter prints how far away a town is, and a town is described by how long the bus takes or by nothing at all.**
2. **A day is assigned only by section 1 of this file.** Where this file and a live batch prompt disagree on a day, **the batch prompt is right for its ten days and this file is right for the run**, and a batch prompt that disagrees with the table below on a day is a defect to be corrected in place and recorded.
3. **Weeks run Monday to Sunday. Week 88 = Monday 502 to Sunday 508, so the Monday of week _n_ is 502 + 7 × (_n_ − 88), and a chapter's day is that week's named weekday with Monday at zero.** The detector is `week = (day − 502) // 7 + 88` and the weekday is `wd = (day − 502) mod 7` against Monday-first. **A value that disagrees with the detector is the value that is wrong, and the detector is the one that agrees with the sittings inherited from `outline/series.md` and with the repaired week table in `outline/volume-10.md`.**
4. **The interval map's two-day offset from the Monday of week thirty-one is inherited, is recorded for the eighteenth time, and is not to be re-derived from the anchor.** No chapter in this manuscript has ever printed a day number, so no prose depends on any of it.

---

## 0. What this file inherits

### 0.1 THE CHAIN, CHECKED ONCE AND NOT RE-DERIVED

**The inherited anchors are printed at the head of `outline/volume-11.md` and are not duplicated here, because a table of anchors is an eleventh place in this repository a figure can be copied from and the sixth time that has happened has been a defect. The chain gives 1204 as the Wednesday of week one hundred and eighty-eight, which is the day Volume 10 closed on, and that is the whole of the check.**

### 0.2 THE DAY ZERO, MADE EXPLICITLY AND PRINTED, WITH THE OPENING THAT WAS REFUSED

**Chapter 501 is day 1205, the Thursday of week one hundred and eighty-eight. In one sentence: Volume 11 opens the day after Volume 10 closed, and 1205 is 1204 + 1, and 1204 is the Monday of week 188 at 1202 plus two days, and 1202 is 502 + 7 × 100, and 502 + 700 is 1202.**

**It is a decision and not a consequence, and it is the only volume in this manuscript to open on a day that is not a Monday, and the reason is printed so that a later pass can see the choice rather than the result: the appointment is made on a Thursday, and a volume that waited for Monday would have kept a woman's new office off the page for four days while everyone else in the manuscript described it. Three other openings were available and were not taken: 1207 is a Saturday and this manuscript does not open a volume at a weekend; 1209 is the Monday of week 189, which is the conventional opening and which would have spent the appointment's own day in a gap; and 1232 is the thirty-seventh sitting, which would have handed the first ten days to a Wednesday with its own rules. The arithmetic of all four is 1204 + 3, 1204 + 5 and 1204 + 28.**

### 0.3 WHAT VOLUME 10 HANDED OVER THAT A FIGURE HERE DEPENDS ON, RESTATED WITH ITS SUBTRACTION BESIDE IT

| Figure | Arithmetic | Value |
| --- | --- | --- |
| Chapter 500 | the Wednesday of week 188, 502 + 7 × 100 + 2 | 1204 |
| Chapter 501 | 1204 + 1, and the Thursday of week 188, 502 + 7 × 100 + 3 | 1205 |
| The next sitting after Volume 10's last | 1204 + 28, and the Wednesday of week 192, 502 + 7 × 104 + 2 | 1232 |
| The whole of Volume 11 | 1316 − 1205 | 111 days |
| The first sitting to the close | 1316 − 1232 | 84 days |
| The room at Chapter 501 and at Chapter 550 | 1205 − 362, and 1316 − 362 | 843, and 954 |
| The card at Chapter 501 and at Chapter 550 | 1205 − 358, and 1316 − 358 | 847, and 958 |
| The nineteen lines at Chapter 501 and at Chapter 550 | 1205 − 666, and 1316 − 666 | 539, and 650 |
| The hold at Chapter 501 and at Chapter 550 | 1205 − 729, and 1316 − 729 | 476, and 587 |
| The ask at Chapter 501 and at Chapter 550 | 1205 − 672, and 1316 − 672 | 533, and 644 |
| The man of about fifty-one at Chapter 501 and at Chapter 550 | 1205 − 756, and 1316 − 756 | 449, and 560 |
| The turn of the movement, Chapter 510 to Chapter 511 | 1230 − 1222 | 8 days |

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
| 501 | 188 | Thursday | 1205 | 504 | 843 | 847 | 539 | 476 | 533 | 449 |
| 502 | 188 | Friday | 1206 | 505 | 844 | 848 | 540 | 477 | 534 | 450 |
| 503 | 189 | Monday | 1209 | 506 | 847 | 851 | 543 | 480 | 537 | 453 |
| 504 | 189 | Wednesday | 1211 | 507 | 849 | 853 | 545 | 482 | 539 | 455 |
| 505 | 189 | Thursday | 1212 | 508 | 850 | 854 | 546 | 483 | 540 | 456 |
| 506 | 189 | Friday | 1213 | 509 | 851 | 855 | 547 | 484 | 541 | 457 |
| 507 | 190 | Monday | 1216 | 510 | 854 | 858 | 550 | 487 | 544 | 460 |
| 508 | 190 | Wednesday | 1218 | 511 | 856 | 860 | 552 | 489 | 546 | 462 |
| 509 | 190 | Thursday | 1219 | 512 | 857 | 861 | 553 | 490 | 547 | 463 |
| 510 | 190 | **Sunday** | 1222 | 513 | 860 | 864 | 556 | 493 | 550 | 466 |
| 511 | 192 | Monday | 1230 | 514 | 868 | 872 | 564 | 501 | 558 | 474 |
| 512 | 192 | Wednesday | 1232 | 515 | 870 | 874 | 566 | 503 | 560 | 476 |
| 513 | 192 | Thursday | 1233 | 516 | 871 | 875 | 567 | 504 | 561 | 477 |
| 514 | 192 | Friday | 1234 | 517 | 872 | 876 | 568 | 505 | 562 | 478 |
| 515 | 193 | Monday | 1237 | 518 | 875 | 879 | 571 | 508 | 565 | 481 |
| 516 | 193 | Wednesday | 1239 | 519 | 877 | 881 | 573 | 510 | 567 | 483 |
| 517 | 193 | Thursday | 1240 | 520 | 878 | 882 | 574 | 511 | 568 | 484 |
| 518 | 193 | Friday | 1241 | 521 | 879 | 883 | 575 | 512 | 569 | 485 |
| 519 | 194 | Monday | 1244 | 522 | 882 | 886 | 578 | 515 | 572 | 488 |
| 520 | 194 | Thursday | 1247 | 523 | 885 | 889 | 581 | 518 | 575 | 491 |
| 521 | 195 | Monday | 1251 | 524 | 889 | 893 | 585 | 522 | 579 | 495 |
| 522 | 195 | Wednesday | 1253 | 525 | 891 | 895 | 587 | 524 | 581 | 497 |
| 523 | 195 | Thursday | 1254 | 526 | 892 | 896 | 588 | 525 | 582 | 498 |
| 524 | 195 | Friday | 1255 | 527 | 893 | 897 | 589 | 526 | 583 | 499 |
| 525 | 196 | Monday | 1258 | 528 | 896 | 900 | 592 | 529 | 586 | 502 |
| 526 | 196 | **Wednesday — the Exchange, the thirty-eighth sitting, the book OPENS** | 1260 | 529 | 898 | 902 | 594 | 531 | 588 | 504 |
| 527 | 196 | Thursday — **the volume's one panel and its one marker** | 1261 | 530 | 899 | 903 | 595 | 532 | 589 | 505 |
| 528 | 196 | Friday | 1262 | 531 | 900 | 904 | 596 | 533 | 590 | 506 |
| 529 | 197 | Monday | 1265 | 532 | 903 | 907 | 599 | 536 | 593 | 509 |
| 530 | 197 | Thursday | 1268 | 533 | 906 | 910 | 602 | 539 | 596 | 512 |
| 531 | 198 | Monday | 1272 | 534 | 910 | 914 | 606 | 543 | 600 | 516 |
| 532 | 198 | Wednesday | 1274 | 535 | 912 | 916 | 608 | 545 | 602 | 518 |
| 533 | 198 | Thursday | 1275 | 536 | 913 | 917 | 609 | 546 | 603 | 519 |
| 534 | 198 | Friday | 1276 | 537 | 914 | 918 | 610 | 547 | 604 | 520 |
| 535 | 199 | Monday | 1279 | 538 | 917 | 921 | 613 | 550 | 607 | 523 |
| 536 | 199 | Wednesday | 1281 | 539 | 919 | 923 | 615 | 552 | 609 | 525 |
| 537 | 199 | Thursday | 1282 | 540 | 920 | 924 | 616 | 553 | 610 | 526 |
| 538 | 199 | Friday | 1283 | 541 | 921 | 925 | 617 | 554 | 611 | 527 |
| 539 | 200 | **Wednesday — the Exchange, the thirty-ninth sitting, the book SHUTS** | 1288 | 542 | 926 | 930 | 622 | 559 | 616 | 532 |
| 540 | 200 | Thursday | 1289 | 543 | 927 | 931 | 623 | 560 | 617 | 533 |
| 541 | 201 | Monday | 1293 | 544 | 931 | 935 | 627 | 564 | 621 | 537 |
| 542 | 201 | Wednesday | 1295 | 545 | 933 | 937 | 629 | 566 | 623 | 539 |
| 543 | 201 | Thursday | 1296 | 546 | 934 | 938 | 630 | 567 | 624 | 540 |
| 544 | 201 | Friday | 1297 | 547 | 935 | 939 | 631 | 568 | 625 | 541 |
| 545 | 202 | Monday | 1300 | 548 | 938 | 942 | 634 | 571 | 628 | 544 |
| 546 | 202 | Wednesday | 1302 | 549 | 940 | 944 | 636 | 573 | 630 | 546 |
| 547 | 202 | Thursday — **the first use of the public body's name in this volume** | 1303 | 550 | 941 | 945 | 637 | 574 | 631 | 547 |
| 548 | 203 | Monday | 1307 | 551 | 945 | 949 | 641 | 578 | 635 | 551 |
| 549 | 203 | Thursday | 1310 | 552 | 948 | 952 | 644 | 581 | 638 | 554 |
| 550 | 204 | **Wednesday — the Exchange, the fortieth sitting, the book OPENS, and the close** | 1316 | 553 | 954 | 958 | 650 | 587 | 644 | 560 |

### 1b. Movement I's ten rows with the remaining nine series, which a writer of Chapters 501 to 510 needs and which no other movement's writer has yet

| Ch | Day | Entry | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | Post | Copies |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 501 | 1205 | 504 | 763 | 714 | 679 | 658 | 633 | 615 | 561 | 539 | 391 | 409 |
| 502 | 1206 | 505 | 764 | 715 | 680 | 659 | 634 | 616 | 562 | 540 | 392 | 410 |
| 503 | 1209 | 506 | 767 | 718 | 683 | 662 | 637 | 619 | 565 | 543 | 395 | 413 |
| 504 | 1211 | 507 | 769 | 720 | 685 | 664 | 639 | 621 | 567 | 545 | 397 | 415 |
| 505 | 1212 | 508 | 770 | 721 | 686 | 665 | 640 | 622 | 568 | 546 | 398 | 416 |
| 506 | 1213 | 509 | 771 | 722 | 687 | 666 | 641 | 623 | 569 | 547 | 399 | 417 |
| 507 | 1216 | 510 | 774 | 725 | 690 | 669 | 644 | 626 | 572 | 550 | 402 | 420 |
| 508 | 1218 | 511 | 776 | 727 | 692 | 671 | 646 | 628 | 574 | 552 | 404 | 422 |
| 509 | 1219 | 512 | 777 | 728 | 693 | 672 | 647 | 629 | 575 | 553 | 405 | 423 |
| 510 | 1222 | 513 | 780 | 731 | 696 | 675 | 650 | 632 | 578 | 556 | 408 | 426 |

---

## 2. The anchors, as a subtraction beside every value

| Series | Anchor day | Form | At 1205 | At 1222 | At 1316 |
| --- | --- | --- | --- | --- | --- |
| The room off that service road | 362 | `day − 362` | 843 | 860 | 954 |
| The card in the rail | 358 | `day − 358` | 847 | 864 | 958 |
| The hardboard's twelfth line | 442 | `day − 442` | 763 | 780 | 874 |
| The hardboard's thirteenth line | 491 | `day − 491` | 714 | 731 | 825 |
| The hardboard's fourteenth line | 526 | `day − 526` | 679 | 696 | 790 |
| The hardboard's fifteenth line | 547 | `day − 547` | 658 | 675 | 769 |
| The hardboard's sixteenth line | 572 | `day − 572` | 633 | 650 | 744 |
| The hardboard's seventeenth line | 590 | `day − 590` | 615 | 632 | 726 |
| The hardboard's eighteenth line | 644 | `day − 644` | 561 | 578 | 672 |
| The hardboard's nineteenth line | 666 | `day − 666` | 539 | 556 | 650 |
| The hold of the man of about thirty-three | 729 | `day − 729` | 476 | 493 | 587 |
| The man of about fifty-one at the wall | 756 | `day − 756` | 449 | 466 | 560 |
| The ask | 672 | `day − 672` | 533 | 550 | 644 |
| The post at the corridor end | 814 | `day − 814` | 391 | 408 | 502 |
| The nine hand copies of the front of a page | 796 | `day − 796` | 409 | 426 | 520 |

## 3. The Exchange, computed from this file and not from any chapter

| Sitting | Chapter | Day | Week | Count announced | Of which correspond | Book before | Book after | Tin |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| the thirty-sixth | 500 | 1204 | 188 | 41 | 36 | 57 | 58 | 73 |
| the thirty-seventh | 512 | 1232 | 192 | 42 | 37 | 58 | 58 | 73 |
| the thirty-eighth | 526 | 1260 | 196 | 43 | 38 | 58 | 59 | 73 |
| the thirty-ninth | 539 | 1288 | 200 | 44 | 39 | 59 | 59 | 73 |
| the fortieth | 550 | 1316 | 204 | 45 | 40 | 59 | 60 | 73 |

**A count is announced at a sitting and on no other day, and the count goes up by one at every sitting whether the book opens or not. The correspond figure is the count less the five that predate the book on a sheet she has never shown anybody. The book opens only when a caller says a thing to her face. The difference between the book and the tin is not a number and is never printed as one, and none of the four is convertible into another, and the ninth chair is against the wall with its back to the room and does not move in this volume and its mover is not named.**

**REPAIRED AT THE VOLUME CLOSE, AND THE SUPERSEDED FIGURE IS QUOTED IN PLACE. The row above this paragraph was printed as `59 | 61` and it contradicted this file's own section 0.3, `outline/volume-11.md` lines 54 and 111, the prompt of record for Movement V, and all fifty chapter files, every one of which puts ONE line in at the fortieth sitting and the book at sixty lines. The book went 58, 58, 59, 59, 60 across the four sittings and two lines went in over one hundred and eleven days. The row is now `59 | 60`. One figure in this file was wrong and the error was in this file and the error was found by the pass that closed the volume and not by a writing pass, which is the fifth time in this repository that the figure a writing pass relied on has been the figure that was wrong. Owner of the class: every file in this repository that holds more than one copy of a number.**

## 4. The two-sided interval series, and how a writer renders one

**Every series printed in weeks and days is printed twice: once in the load book's row and once in the sentence of the narration above it, and both are converted by `weeks × 7 + days` and required equal. The weeks-and-days phrase is regenerated from the figure and compared character for character.**

**Test the attachment from the end of the `days` token and not from the end of the numeral, and test in both directions, because a compliant rendering in this house may put the weeks form first: "one day short of seventy-six weeks" and "seventy-six weeks and one day" are both house renderings and a walk that reads only the second will return a clean result on a page that has the first.** A figure that is an exact number of weeks is rendered with the word *to the day* and the word *short* is not used, because "seven weeks short of X" is a different figure from "X less seven weeks" and the two are not interchangeable in a movement where an ask has been counted from a named day for ten volumes.

Movement I's nine interval renderings, for the walk and not for reuse as sentences:

| Ch | Ask | W and d | Man of fifty-one | W and d | Hold | W and d | Room | W and d | Nineteen | W and d |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 501 | 533 | 76 w 1 d | 449 | 64 w 1 d | 476 | 68 w 0 d | 843 | 120 w 3 d | 539 | 77 w 0 d |
| 502 | 534 | 76 w 2 d | 450 | 64 w 2 d | 477 | 68 w 1 d | 844 | 120 w 4 d | 540 | 77 w 1 d |
| 503 | 537 | 76 w 5 d | 453 | 64 w 5 d | 480 | 68 w 4 d | 847 | 121 w 0 d | 543 | 77 w 4 d |
| 504 | 539 | 77 w 0 d | 455 | 65 w 0 d | 482 | 68 w 6 d | 849 | 121 w 2 d | 545 | 77 w 6 d |
| 505 | 540 | 77 w 1 d | 456 | 65 w 1 d | 483 | 69 w 0 d | 850 | 121 w 3 d | 546 | 78 w 0 d |
| 506 | 541 | 77 w 2 d | 457 | 65 w 2 d | 484 | 69 w 1 d | 851 | 121 w 4 d | 547 | 78 w 1 d |
| 507 | 544 | 77 w 5 d | 460 | 65 w 5 d | 487 | 69 w 4 d | 854 | 122 w 0 d | 550 | 78 w 4 d |
| 508 | 546 | 78 w 0 d | 462 | 66 w 0 d | 489 | 69 w 6 d | 856 | 122 w 2 d | 552 | 78 w 6 d |
| 509 | 547 | 78 w 1 d | 463 | 66 w 1 d | 490 | 70 w 0 d | 857 | 122 w 3 d | 553 | 79 w 0 d |
| 510 | 550 | 78 w 4 d | 466 | 66 w 4 d | 493 | 70 w 3 d | 860 | 122 w 6 d | 556 | 79 w 4 d |

**The copy at the corridor end walks as `day − 814` and is 391, which is fifty-five weeks and six days, at Chapter 501. The nine hand copies walk as `day − 796` and are 409, which is fifty-eight weeks and three days, at Chapter 501, and about eight of the nine are still unfinished and the first disagreement in the fourth line is still not found.**

## 5. Collision sweep, and the reading that is required before it is trusted

**Sweep: for each of the fifteen series on each of the fifty rows, test the value against the fifteen anchors, and report every hit where the value is not its own anchor. Volume 11's sweep returns twenty-six rows at thirteen chapters, and every chapter's rows come in pairs. Movement I's rows are six, at Chapters 506, 507 and 509, and every member of every pair is on the page, and the chapter says in the same breath which figure is an age and which is a day something happened.**

| Ch | Day | Value | Collides with | Which one it is |
| --- | --- | --- | --- | --- |
| 506 | 1213 | 547 (the nineteenth line) | 547 (the fifteenth line's anchor) | an age; the anchor is the day the fifteenth line was written |
| 506 | 1213 | 666 (the fifteenth line) | 666 (the nineteenth line's anchor) | an age; the anchor is the day the nineteenth line was written |
| 507 | 1216 | 644 (the sixteenth line) | 644 (the eighteenth line's anchor) | an age; the anchor is the day the eighteenth line was written |
| 507 | 1216 | 572 (the eighteenth line) | 572 (the sixteenth line's anchor) | an age; the anchor is the day the sixteenth line was written |
| 509 | 1219 | 547 (the ask) | 547 (the fifteenth line's anchor) | an age in days; the anchor is a day the fifteenth line was written |
| 509 | 1219 | 672 (the fifteenth line) | 672 (the ask's anchor) | an age; the anchor is the day the ask was asked |
| 514 | 1234 | 644 and 590 | the eighteen and the seventeen | a pair |
| 519 | 1244 | 572 and 672 | the sixteen and the ask | a pair |
| 520 | 1247 | 491 and 756 | the thirteen and the fifty-one | a pair |
| 524 | 1255 | 526 and 729 | the fourteen and the hold | a pair |
| 528 | 1262 | 590 and 672 | the seventeen and the ask | a pair |
| 534 | 1276 | 547 and 729 | the fifteen and the hold | a pair |
| 537 | 1282 | 526 and 756 | the fourteen and the fifty-one | a pair |
| 547 | 1303 | 547 and 756 | the fifteen and the fifty-one | a pair |
| 549 | 1310 | 644 and 666 | the eighteen and the nineteen | a pair |
| 550 | 1316 | 644 and 672 | the eighteen and the ask | a pair |

**The reading that is required before this table is trusted: the sweep must be run against the anchor set as a set of integers, and not against a dictionary compared by value, because the second of those compares an integer with a string and matches nothing and then reports a clean result.** Volume 10's fourth movement published a clean result produced by that defect and attributed the shortfall to the instrument. The run above was walked a second time from the row side and from the page side and both sides return the same thirteen chapters.

**And the row-side walk is not sufficient on its own, which is the finding of the last two volumes: a table can be correct on its day, its week, its weekday and its entry and wrong in five of its six series columns, which is what the Chapter 523 row did, and only the page-side walk sees that.** Both halves are therefore required, on every volume of this manuscript, and a pass that runs one half has run half an instrument.

## 6. Written by the volume close, and by nobody before it

**This section is written by the phase that closed the volume and that planned Volume 12. It was written with `outline/volume-12.md` and before Chapter 551. It adds no chapter, moves no day, no week, no entry, no anchor and no interval, and it resolves no thread.**

### 6.1 THE COUNT OF SERIES THAT RAN CLEAN ON ALL FIFTY ROWS

**Sixteen series, eight hundred values, and every one of them is `day − its own named anchor` on the row it is printed against, at zero defects. The four free checks are {4}, {21}, {−27} and {−72} with their signs and they are clean on all fifty rows and not only on the ten rows of a movement. The load-book run is 504 to 553 with no duplicate and no gap and the set of (entry − chapter) is {3} on all fifty rows. The Exchange's four sittings are at days 1232, 1260, 1288 and 1316, all Wednesdays, all four weeks apart, and no Friday in the volume is an Exchange day.**

### 6.2 THE FOUR ARRIVAL CELLS, PRINTED EMPTY ONE MORE TIME, AND THE REASON

**All four are empty. They are empty in all five movement summaries and they are empty here. The reason is the same reason they have been given six times: all fifty chapters of this volume were written and repaired in one dispatch, and a cell that measures a movement arriving from a previous movement cannot be measured on files that did not exist separately. A cell that cannot be measured is printed empty and is not approximated, and a reconstructed arrival is the finished files measured twice and is not an arrival.**

**The recommendation has now been made six times in this volume and taken six times on the first dispatch. Volume 11 is the last volume in which it can be taken, because the next volume is Volume 12 and the movement after the next is a writing phase in a different book, and by then the habit is not a habit anybody has.**

### 6.3 THE FIGURES AT DAY 1316, RE-DERIVED FROM SECTION 2 AND NOT READ OFF A CHAPTER

| Series | Anchor | 1316 − anchor | In weeks and days |
| --- | --- | --- | --- |
| The room off that service road | 362 | 954 | 136 w 2 d |
| The card in the rail | 358 | 958 | 136 w 6 d |
| The hardboard's twelfth line | 442 | 874 | 124 w 6 d |
| The hardboard's thirteenth line | 491 | 825 | 117 w 6 d |
| The hardboard's fourteenth line | 526 | 790 | 112 w 6 d |
| The hardboard's fifteenth line | 547 | 769 | 109 w 6 d |
| The hardboard's sixteenth line | 572 | 744 | 106 w 2 d |
| The hardboard's seventeenth line | 590 | 726 | 103 w 5 d |
| The hardboard's eighteenth line | 644 | 672 | 96 w 0 d |
| The hardboard's nineteenth line | 666 | 650 | 92 w 6 d |
| The hold of the man of about thirty-three | 729 | 587 | 83 w 6 d |
| The man of about fifty-one at the wall | 756 | 560 | 80 w 0 d |
| The ask | 672 | 644 | 92 w 0 d |
| The post at the corridor end | 814 | 502 | 71 w 5 d |
| The nine hand copies of a page front | 796 | 520 | 74 w 2 d |
| The separation | 982 | 334 | 47 w 5 d |

**The nineteenth is still the only line of the nineteen that has ever closed on a zero. A figure rendered as an exact number of weeks takes the word *to the day* and does not take the word *short*, because a figure of that shape is a different figure and an ask has been counted from a named day for eleven volumes.**

### 6.4 THE WORDS IN THE EXCHANGE AT THE FORTIETH SITTING, IN ONE LINE, AND THE WHOLE OF THE LINE

**He said: put down that I was in that hall on the Monday, because in about a year I am going to be a man who says he was in a room where nothing happened. She wrote it in one line in about nine seconds, asked him not one question about the Monday, and nobody in that room said thank you, and he went down the stair at about eleven and did not speak on the landing and has not asked whether it went in and is not going to.**

**And the four figures at that sitting, which are not one figure and are not convertible into one another: the book at sixty lines, having stood at fifty-nine before the morning; the tin at seventy-three with nothing given into it in nineteen years; the count at forty-five announced of which forty correspond, against forty-four of which thirty-nine on the nine days before it; and nineteen years of four-week Wednesdays.**

### 6.5 THE THREE DECISIONS THE VOLUME TOOK, IN THE VOLUME'S OWN WORDS

1. **A public body voted to keep the Commons and refused a single place where every answer anybody gives is entered once, and it did it on a show of hands ruled by a clerk on a sheet of paper, and the clerk is not thanked.** The thing that survived is an institution with a limit written on it. The thing defeated is two proposals and not a person.
2. **A room above a line in another district opened its book twice in one hundred and eleven days and two ordinary sentences went in, and neither of them was a vote, and one of them is a man saying he was in a room where nothing happened.** A book that opens when a person says a thing to a woman's face is not a rule and is not evidence of anything and is not going to be described by anybody as a change in her.
3. **The Conductor's Choir took the remaining Crown pattern out of a building in a town over two nights, and it is plumbing and not the key, and nobody in this volume is holding the key at any point, and the place where the key could be made to answer is not recoverable by anybody who was in the room.**

### 6.6 THE MEASUREMENT OF THE WHOLE VOLUME, WITH ITS INSTRUMENT PRINTED, AND TWO FIGURES THAT DID NOT REPRODUCE

**The instrument: a chapter's apparatus begins at the first line matching `^\*\d+\.` — the load-book entry — and the body is everything above it. The counts are whitespace tokens, measured on the file as it stands on disk, not on any summary.**

- **221,333 words across the fifty files, body 120,249, apparatus 101,084, an apparatus aggregate of 45.671 and a mean of the fifty per-file shares of 45.488, the lowest share 39.5 and the highest 49.2.** Volume 10's own volume aggregate is 46.219 and Volume 09's is 50.385, and Volume 11's is inside the band and Volume 09's is outside it. **This figure had never been printed for this volume before this section and it is the volume's headline.**
- **The per-movement arc, measured on the files as they stand, is 42.727, 43.241, 46.463, 47.604 and 47.458.** The five movement summaries publish 42.727, 43.583, 46.199, 47.604 and 47.458. **TWO OF THE FIVE DID NOT REPRODUCE AND BOTH READINGS ARE PUBLISHED: Movement II is 43.583 in its own summary and 43.241 on the files, and Movement III is 46.199 in its own summary and 46.463 on the files. Movements I, IV and V reproduce to the digit. The cause is not the chapters and is not established: each of the two movements had a review repair pass after its summary was written, and a repair pass that repairs words and is not re-measured leaves the summary standing as the account of a file that no longer exists. Owner: every summary in this repository that was written before the last pass that touched its files.**
- **Word counts by movement on the files as they stand: 39,811, 41,151, 40,622, 46,194 and 53,555, against 39,811, 41,707, 40,317, 46,194 and 53,555 published.** The word count rose by about a third across the volume and the reason is printed: a movement which votes contains about nine hundred people in a room three times and about two hundred and sixty in a queue, a doorway and a road, and none of that is a row.
- **1,957 bold spans by a per-line parity count of `**` with zero odd lines on all fifty files.** A per-line parity count cannot see a nested span and a whole-file non-greedy regex cannot see a span that crosses a line break, and the two readings on a clean file are the same and on a dirty one they are not; this file publishes the parity count and says which one it is.
- **The duplication count at the body-prose scope, by whole sentences of twelve words or more compared byte for byte across all fifty files: seven, and all seven are the room above a line and its nineteen years — the ninth chair against the wall, the table and the unlidded tin, the nine items at four minutes, and the line about nobody asking her whether she was all right.** At the whole-file scope it is twenty-four, and the extra seventeen are the standing-record sentences in the load books, which are mandated in fifty files. **The claim of ZERO in the live block of `state/current.md` was made per movement, where it is true, and is false at fifty files' scale, and the seven and the twenty-four are here instead of the zero.**
- **The out-of-fiction walk, run on the fifty BODIES AND THE FIFTY APPARATUSES, with the fifty H1 title lines separated: zero on the bodies, zero on the apparatuses, fifty on the title lines, and the fifty on the title lines are fifty occurrences of the word Chapter followed by three digits and nothing else.** The fourteen terms are `this volume`, `this chapter`, `this movement`, `this novel`, `the novel`, `volume`, `chapters?`, `chapter <digits>`, `word count`, `per thousand`, `outline`, `canon`, `protagonist`, `POV`. **The apparatuses are in the scope on purpose, because Movement V's instrument named the whole text of each file, reported the bodies in the column beside it, and left four leaks standing in two apparatuses until a repair pass closed that half.**
- **The hedge: raw `about` 4,440, of which 4,411 are the prepositional class `about` immediately governing a figure, leaving a true hedge of 29, which is 0.131 per thousand.** The prepositional class is written out in full above the figure because an unwritten half of a partition is a partition that cannot be walked.
- **The collision sweep on all fifty rows, fifteen series against fifteen anchors: 2,250 comparisons, returning twenty-six rows at thirteen chapters — 506, 507, 509, 514, 519, 520, 524, 528, 534, 537, 547, 549 and 550 — every member of every pair on the page in the body prose of its own chapter, and none of the twenty-six a day anything happened to the heating in this city.**

### 6.7 WHAT THIS SECTION DELIBERATELY DID NOT DO

**It did not write a chapter, and it did not resolve the rota man's inspection, the ninth chair, the woman's page, the licensor, the field, the master's fifth line, the four hand copies, the four rooms and the three rooms, the nine doors, the four bars, the nine keys, the wash-house, the space on the wall, the bin in a town, the four words, or the notebook. It did not resolve the key's activation site. It did not say what was on the piece of paper that went into a bin. It did not join that paper to anything.**
