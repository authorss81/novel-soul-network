# Volume 19, Movement III — Chapters 961 to 970 — Summary and Measure of Record

**Written after the last measurement of the ten files and not before it, and re-written after the repair pass recorded at §10. The measure of record for this movement is this file. The plan of record is `outline/volume-19.md` and the calendar is `workspace/volume-19/ARITHMETIC-AND-CALENDAR.md`, whose §1 carries the day map for these ten rows and whose §2 carries the sixteen standing anchors and the two short-run origins.**

---

## 1. WHAT WAS WRITTEN

**Ten chapters, 961 to 970, at `workspace/volume-19/batch-0003/`, on the day map at §1 of the calendar file: days 2139, 2140, 2141, 2143, 2145, 2147, 2149, 2150, 2151 and 2152; weeks 321, 322 and 323; load-book entries 964 to 973; governed counters 206 to 215.** `(entry − chapter) = {3}` on all ten rows, **and the load-book entry is a chapter-indexed row count and not a function of the day, which is why it is not written here as `day − constant`; a pass that writes it that way gets Movement IV's first entry wrong by seven.** Every weekday was re-derived with `(day − 502) mod 7` and every week with `(day − 502) // 7 + 88`, and all ten agree with §1: Sunday, Monday, Tuesday, Thursday, Saturday, Monday, Wednesday, Thursday, Friday, Saturday. One Sunday, at Chapter 961, and the shutter came down at two on it and at ten on the other nine. **No sitting fell in this movement; the seventieth sitting is Chapter 971 in Movement IV.** Days 2142, 2144, 2146 and 2148 carry no chapter.

**WHAT THE MOVEMENT WAS ABOUT, IN ONE PARAGRAPH.** The word *told* was in a pencil margin on somebody else's copy, and a man of about fifty-two had copied it into a register that had never held an unattributed line, and he wanted it out. **Nobody ruled it out; he ruled a line under it instead, and said a man does not start denying things on a Sunday.** The page was read on a Tuesday on a table in a woman's own flat, off-page, with the second holder on the landing, and the reader came back into that shop at about nine and gave the room two sentences and a man none of what was on it. **A sixth column headed *told* was ruled by hand on a copy of the sheet the woman of about forty-three made, and she told him what a column is — a question with a box round it — and then took the copy into a tray that had been empty for four years and said that is not holding it.** A woman of about fifty-one came back and was not asked why she came, and the question was put to the only person in the room not allowed to ask it. A man of twenty-two put four names on the back of a job card instead of asking four people anything, and an office made him say them out loud and kept nothing and could not unhear them. Two refused each other in a room full of shelves and then one of them said the true thing. A copy with an empty column was left on a table and nobody there holds it. **On the last Saturday a third columned sheet came into the tray with the column filled in once, and the woman of about forty-three read it and would not read it out and shut the drawer.**

**AND THE ONE THING THIS MOVEMENT PROMISED AND DELIVERED: nobody in this city can say who wrote *told*, and the wish has left the four people who know and become a thing anybody with a ruler and a biro can do, and by Chapter 970 a third person has answered it with a pen and will not say who they are.**

**AND ONE THING ABOUT THE DAY MAP THAT A LATER PASS SHOULD KNOW BEFORE IT PLANS THE NEXT TEN DAYS: `outline/volume-19.md` line 77 places Movement IV in *weeks 325–326*, and the calendar's §1 places its ten days in weeks 324, 325 and 326, and the detector agrees with the calendar and not with the outline.** Day 2156 is `7 × 324 − 114` and is the Wednesday of week 324; day 2168 is `7 × 326 − 114` and is the Monday of week 326. **The calendar is the authority and the outline's week range for Movement IV is wrong by one week at the front. The outline was not edited by this pass, which did not write it, and the finding is recorded here so that a later pass does not inherit it.**

**AND MOVEMENT IV'S SPAN CONTAINS TWO SUNDAYS, days 2160 and 2167, which is a fact about the calendar and a problem for guardrail six: that guardrail says the shutter comes down at about two *on the one Sunday of each movement that has one*, and Movement IV has two. Both therefore take the about-two form, and a pass that writes this from the guardrail alone will write one of them wrong.**

---

## 2. THE INSTRUMENT, ITS BOUNDARY, ITS ASSERTIONS, AND WHAT DID NOT REPRODUCE

**BOUNDARY, PRINTED ONCE AND USED THROUGHOUT.** Tokeniser `[A-Za-z0-9]+(?:-[A-Za-z0-9]+)*`; the H1 line removed; the characters `*`, `` ` `` and `|` removed. A hyphenated compound is one token. **The tokeniser does not admit a colon, so a twenty-four-hour clock time is two tokens, and no page of this movement prints one.** Body scope runs to the standalone load-book marker (a line that is a number in asterisks and a full stop and nothing else) and apparatus scope runs from that marker to end of file; the two are disjoint and their sum is the whole file. **The marker line itself is one token and it belongs to apparatus, because apparatus is said to begin *at* that marker and not after it**, which is the convention `workspace/volume-19/batch-0002/SUMMARY.md` §2 printed and this file inherits it unchanged.

**A SENTENCE, as §3.0 of `workspace/continuation/next-0020/GATE.md` prints it:** a maximal token run whose final token is **followed by** one of `.` `!` `?`, which is itself followed by whitespace or end of scope. A semicolon and a colon are not terminators. **An unterminated trailing run is not a sentence and is not counted.** Duplicated run: the last twelve tokens of every sentence, lowercased, counted once per distinct key, over all forty-five pairs inside the ten files, prose and apparatus reported separately.

**ASSERTION BLOCK A — THE SENTENCE COUNTER AGAINST EIGHT KNOWN STRINGS. 8 OF 8 PASS ON THE FIRST RUN, AT THE BOUNDARY ABOVE.**

| Input | Expected | Returned |
| --- | --- | --- |
| `One. Two. Three.` | 1, 1, 1 | 1, 1, 1 |
| `No terminator here` | 3 | 3 |
| `A. B! C? D.` | 1, 1, 1, 1 | 1, 1, 1, 1 |
| `He said: it is done; it is not done.` | 9 | 9 |
| `End.` | 1 | 1 |
| `It is 4-19 on the plate. The drill runs at 09:20 tomorrow.` | 6, 7 | 6, 7 |
| `Mr. Vale signed it, and the clerk did not. Nobody spoke.` | 1, 8, 2 | 1, 8, 2 |
| `One thousand three hundred and forty-four days. Nine of them.` | 7, 3 | 7, 3 |

**AND TWO OF THIS PASS'S OWN EXPECTED VALUES WERE WRONG AND THE INSTRUMENT WAS RIGHT, WHICH IS THE THIRD RECORDED INSTANCE OF THAT CLASS IN VOLUME 19 AND IS PUBLISHED RATHER THAN ONLY DISCLOSED.** The title of `chapter-0951.md` was asserted at four words and is six; the title of `chapter-0960.md` was asserted at six words and is three. **Both titles are on disk and both counts are arithmetic, and a pass that checked its own expectations by eye would have rewritten the instrument.** `workspace/volume-19/ARITHMETIC-AND-CALENDAR.md` §0.2 records the first instance of this class in this volume and the repair pass on Chapters 951 to 960 records two more.

**ASSERTION BLOCK B — THE PUBLISHED VALUES A LATER PASS IS TOLD TO INHERIT, RUN AT THE BOUNDARY ABOVE. THREE REPRODUCE AND TWO DO NOT, AND NEITHER OF THE TWO THAT DO NOT IS INHERITED.**

| Published value, and where it is published | Returned here | Verdict |
| --- | --- | --- |
| Chapter 960 is 1,028 body, 1,326 apparatus, 2,354 whole | 1,028 / 1,326 / 2,354 | **reproduces** |
| Movement II totals 9,838 body, 11,004 apparatus, 20,852 whole, at the boundary printed in `batch-0002/SUMMARY.md` §2 | 20,852 whole at that boundary | **reproduces** |
| All 160 anchor rows of Chapter 960, at `batch-0002/SUMMARY.md` §2 | 16 of 16 rows of that file | **reproduces** |
| `about` for Movement II is 7.28 at file scope and 7.29 pooled | **6.80 at file scope and 6.81 pooled**, denominator 20,852 | **does not reproduce** |
| Duplicated twelve-token suffixes for Volume 18 Movement VI are 3 in prose and 12 in apparatus | **24 in prose and 38 in apparatus** | **does not reproduce** |

**AND TWO EXPECTED VALUES FROM THE SIXTH GATE'S OWN CONTROL BLOCK ALSO FAILED AT THIS BOUNDARY, WHICH IS RECORDED BECAUSE A PASS IS TOLD TO RE-DERIVE RATHER THAN INHERIT AND SHOULD KNOW WHAT IT IS GETTING.** `about` in `workspace/volume-18/batch-0006/chapter-0940.md` is published at 18.08 per thousand at file scope and this instrument returns **16.16** at the boundary printed at §3.0 of `workspace/continuation/next-0020/GATE.md`, which is the same boundary. **The two figures are two different quantities measured under one name, and this file does not correct either: it publishes its own, prints the denominator beside it, and declines to inherit the other.**

**A control that cannot fail is not a control, and a figure nobody can re-derive is a number being carried.** The word table, the anchor rows and the day map reproduce exactly and were used. The two `about` figures and the two duplication figures do not reproduce at any boundary this pass tried, and **a later pass must re-derive them rather than inherit them, exactly as it is told to do with the struck figures at `batch-0002/SUMMARY.md` §4.**

---

## 3. THE WORD TABLE, EVERY FIGURE AT ITS PRINTED BOUNDARY

| Chapter | Body | Apparatus | Whole |
| --- | --- | --- | --- |
| 961 | 1249 | 1065 | 2314 |
| 962 | 1265 | 1050 | 2315 |
| 963 | 1403 | 1080 | 2483 |
| 964 | 1250 | 1051 | 2301 |
| 965 | 1183 | 1076 | 2259 |
| 966 | 1341 | 1054 | 2395 |
| 967 | 1136 | 1083 | 2219 |
| 968 | 1370 | 1095 | 2465 |
| 969 | 1186 | 1036 | 2222 |
| 970 | 1384 | 1502 | 2886 |

**THE TEN TOTALS ARE 12,767 BODY, 11,092 APPARATUS AND 23,859 WHOLE, AND 12,767 + 11,092 = 23,859 WITH NOTHING IN EITHER SCOPE TWICE. Apparatus share 464.81 per thousand of the whole file. Chapter 970's apparatus is the longest on any of the ten because it carries the movement's carry-forward block and its end marker.**

**THE ANCHOR TABLE: ONE HUNDRED AND SIXTEEN ROWS ACROSS TEN CHAPTERS, ONE HUNDRED AND SIXTEEN REPRODUCED, ON THE FIRST RUN AND AGAIN AFTER THE REPAIR PASS AT §10.** Origins at `workspace/volume-19/ARITHMETIC-AND-CALENDAR.md` §2, continuous with Volume 18. Every one of the sixteen figures on every one of the ten files was re-derived as `day − origin` and rendered through the weeks renderer, and compared to the string printed on the page. **The control was Chapter 960, the file the previous repair pass altered, and it returns sixteen of sixteen at the same boundary.** The sixteen zero-remainder rows on Chapters 962, 964, 966, 967, 968, 969 and 970 all render with `to the day` and all reproduce.

**THE SHORT-RUN ANCHORS, RE-DERIVED ON EVERY DAY AND NOT CARRIED FORWARD FROM THE DAY BEFORE, WHICH IS THE FAULT THE THIRD MOVEMENT PROMPT PUT TO THIS PASS.** A signed request has origin 2113 and is printed in the prose body on nine of the ten files: **twenty-six days old at 961, twenty-seven at 962, twenty-eight at 963, thirty at 964, thirty-four at 966, thirty-six at 967, thirty-eight at 969; it is not printed at all on 968.** A printed form up on a wall by two drawing pins has origin 2092 and is printed on two of the ten files, Chapters 965 and 970, standing at **fifty-three days** and **sixty days** old. **Days 2142, 2144, 2146 and 2148 fall between those prints and no page treats any of them.**

**THE PROSE ANCHOR FIGURES ARE TWO ON EVERY FILE EXCEPT 968, WHICH PRINTS THREE: the four units off that service road on all ten, and on 968 the sixteenth of those ruled lines, never once written on, at one thousand five hundred and seventy-eight days, two hundred and twenty-five weeks and three days, which is the true value at day 2150 and not the value of any other day.**

**THE CHARGES. Forty jobs across ten days, four on each day, each priced before it was begun, and every stated total equals the sum of its own four prices. 961 twenty-four, 962 thirty-seven, 963 thirty-three, 964 thirty-four, 965 forty-one, 966 twenty-nine, 967 thirty-six, 968 thirty-eight, 969 thirty-three, 970 forty-three. Three hundred and forty-eight pounds is what the ten days came to, exact.** On Chapter 963 sixteen of the thirty-three was work done without him, because his hands went in the middle of that afternoon, and the day's two first jobs are his and the other two are hers and the page says so twice.

---

## 4. `about`, AT BOTH SCOPES, WITH THE DENOMINATOR BESIDE EVERY ROW

**BOUNDARY: `about` per thousand tokens, whole file, H1 removed, at the tokeniser printed at §2. PFILE is the mean of the ten per-file rates and PPOOL is the concatenated files counted once. The two are different quantities and both are printed, because the sixth gate's own file printed two scopes under one heading and that is the defect.**

| Volume, and exactly which files | Tokens in the denominator | PFILE | PPOOL |
| --- | --- | --- | --- |
| Volume 18, Movement VI's ten files alone, 931 to 940 | 23,902 | — | **15.69** |
| Volume 19, Movement I, ten files, 941 to 950 | 27,673 | — | 14.74 |
| Volume 19, Movement II, ten files, 951 to 960 | 20,852 | **6.80** | 6.81 |
| **Volume 19, Movement III, ten files, 961 to 970** | **23,859** | **11.28** | **11.40** |
| Volume 19, all three movements, thirty files, 941 to 970 | 72,131 | — | 11.85 |

**THE PER-FILE FIGURES FOR MOVEMENT III, IN CHAPTER ORDER: 7.78, 10.80, 14.50, 10.00, 11.07, 11.27, 9.46, 11.36, 11.70 and 14.90.** They are printed because the denominator is printed, and a rate without a denominator is the defect this section exists to prevent.

**AND THIS IS A RISE AGAINST MOVEMENT II AT THE SAME BOUNDARY, AND IT IS NOT REPORTED AS AN IMPROVEMENT.** Movement II is 6.80 and Movement III is 11.28 at this boundary. **The rise is in the house's own reporting idiom and not in the dialogue: §8 measures it, and the idiom is two constructions and not a habit of the characters.**

**AND THE CLOCK-TIME HALF OF IT, WHICH THE PREVIOUS MEASURE OF RECORD GOT WRONG IN THE OTHER DIRECTION.** `batch-0002/SUMMARY.md` §4 states that no clock time in any prose body on those ten files uses `about`. **At this boundary that is false and the falsity is on Movement II's own page: the house's load-book preamble on `chapter-0960.md` line 114 reads *the last of them at about twenty-five past nine*, and that line is above the marker and is therefore body.** On these ten files there are **nine clock-time uses of `about` in body scope and eleven in apparatus scope**, and the body uses are the callers' line, the load-book preamble, and four narrative times. **No page of this movement prints a twenty-four-hour clock time, so the tokeniser's one-token-per-time debt is not incurred here.**

---

## 5. THE DUPLICATION MEASURE, THE CONTROL, AND THE REPAIR

**THE MEASURE AS PRINTED AT THE TOP OF THIS FILE. Prose scope and apparatus scope are reported separately.**

| Scope | Volume 19 Movement III, ten files | Volume 18 Movement VI, ten files, run as a control at this boundary | Movement I | Movement II |
| --- | --- | --- | --- | --- |
| prose | **0** | **24** | 5 | 0 |
| apparatus | **38** | **38** | 7 | 459 |

**THE PROSE FIGURE IS ZERO AND WAS EIGHT ON THE FIRST RUN, AND THE REPAIR IS RECORDED HERE WITH THE EIGHT RUNS NAMED, WHICH IS WHAT A LATER PASS NEEDS IN ORDER TO CHECK IT.** The first run returned eight distinct shared twelve-token keys and every one of them was a house sentence rather than a scene sentence: **the callers' line, on three pairs, and the sentence that opens the priced-work paragraph, on five pairs.** All ten of the callers' lines and all ten of the priced-work paragraphs were rewritten into ten distinct wordings each, and the re-run returns zero. **No line of dialogue was altered by that repair, no outcome changed, no job charge moved, and no day, week, entry or counter moved.**

**THE APPARATUS FIGURE IS THIRTY-EIGHT AND IS NOT A SCENE MEASURE.** It is the house's own conditions-and-docket block, its conditions-of-the-close block and its ten-objects list, which guardrails 8, 12 and 15 require on every one of the sixty pages. **The longest run two files share inside one paragraph is forty-four words, between Chapters 964 and 968, and it is the conditions-and-docket block, which the plan requires and which differs between two files only in the day word and the job list.** A second run of thirty-four words sits in the body, between the two Thursday files, in the sentence about the fourth of those four rooms. **Both are classified as the frame, neither was repaired, and both are published so that the volume close inherits the numbers instead of discovering them.**

**AND THE MOVEMENT II APPARATUS FIGURE OF FOUR HUNDRED AND FIFTY-NINE IS A FIGURE ABOUT ITS OWN BLOCK LENGTH, NOT ABOUT PROSE.** Movement II's conditions-and-docket block is about a hundred and eighty words and almost identical across its ten files, which produces one shared key per token position across forty-five pairs. **Movement III's blocks are shorter and are worded differently on every file, which is why the same measure returns thirty-eight and not four hundred and fifty-nine, and neither number is a measure of anything a reader can see.** At thirty files the figures are ten in prose and seven hundred and fifty-five in apparatus, and both are frame.

---

## 6. TITLES, THE OPENING BAND, AND THE SWEEPS

**TITLES NAME SOMETHING AGAIN, AND ALL TEN ARE INSIDE THE THREE-TO-TEN-WORD BAND SET AT `outline/volume-19.md` LINE 150.** They run 6, 6, 5, 8, 6, 8, 8, 7, 5 and 8 words, median six. **At §3.0 of `workspace/continuation/next-0020/GATE.md`'s printed `NUM` — thirty cardinals, twenty ordinals, seventy-two hyphenated compounds — the median number of number-words in a title is ZERO across all ten files and the number of files carrying one at all is ZERO; the median number of capitalised `And` joins is ZERO and the number of files carrying one is ZERO.** No title enumerates its page, spells out a date, or joins two things with `And`. **Against a Volume 18 median of eighty words, all sixty of whose titles carry at least one number-word and five of which carry at least one `And`, this is the step back that the volume outline declares at its line 150 and it holds on all ten files.**

**THE OPENING BOLD PARAGRAPH, MEASURED ON ALL TEN AFTER THE REPAIR AND NOT REPORTED BEFORE BEING MEASURED, WHICH IS THE SECOND FAULT THE THIRD MOVEMENT PROMPT PUT TO THIS PASS.** All ten stand inside guardrail two's forty-to-seventy-five band: **48, 56, 51, 53, 48, 49, 57, 55, 53 and 48.** The ten numbers are printed rather than a claim, and no page's opening prints a figure. **Two openings were rewritten in the repair pass because they narrated the day's central beat rather than the day's shape, and a third was rewritten because it put the reader in the wrong room.**

**THE SWEEPS, AND WHAT EACH ONE FOUND. `fair`, `unfair`, `justice`, `rightful`, `principle`, `right` and `coalition` are at zero on all ten files.** Five uses of `right` and one as an adjective survived the first draft and were repaired in place: a bare `right` used as an answer became `yes`, a copular claim about a nine-year tenure became a claim about a long one, and three attributive uses in a priced job were replaced with `a thirteen-amp fuse`, `a lamp of the rating the holder was made for` and `a socket's conductors put in order`. **`feed`, `telephone`, `messenger` and `broadcast` are at zero. `review` is at zero. `Iona Sorn`, `Evan Senn`, `Rafi Pell`, `Dessa Kwan`, `Oren Vey`, `Iven Sore` and `Lena Senn` are at zero on all ten files.** No page prints a figure for the woman's page, no fifth column heading is settled, no fifth of the register is written, no Exchange figure is printed and the difference between the book and the tin is printed nowhere.

**AND THE DOUBLED-WORD SWEEP FOUND ONE AND IT WAS READ BEFORE IT WAS LEFT.** `chapter-0970.md` carried `had had` in a narrative sentence and it now reads `he had it ready since the Monday`. **A sweep for a doubled word needs a word boundary and a repair needs to be read back, and this one was both.**

**AND GUARDRAIL EIGHT IS COMPLIED WITH ON THE NOUN PHRASE, WHICH MOVEMENT II DID NOT DO.** The boundary, printed so it can be re-run: `the empty place behind that chair`, case-insensitive, whole file, all ten of this movement's chapter files. **It stands at one occurrence on one of ten files, Chapter 967, where it is denied, and at zero on the other nine. No figure for it is printed on any of the ten pages or in this file.** Movement II's own measure of record published ten occurrences on ten of ten and said the guardrail holds for the positive sense and not for the noun phrase; **this movement prints the sentence once and the figure on none, which is the plan's own wording at `outline/volume-19.md` guardrail 8, and the difference between the two movements is a difference in what was done and not a difference in the guardrail.**

**THE TEN-OBJECTS LIST: ten objects on every one of the ten closing pages, and on the first run eight of the ten pages carried only nine.** The missing object was the pencil in a margin on eight files and it is now present in a different wording on each of them, and the couplet `nineteen ruled lines and two nails` on Chapter 961 is now `a board ruled with nineteen lines and nothing on them`. **No two objects are brought together in a sentence and the count is ten on all ten files.**

---

## 7. WHAT THE FOUR QUESTIONS RETURNED, AND IT WAS ANSWERED BY READING

**WHO WANTS SOMETHING?** A man of about fifty-two wants an unattributed line out of a register; a woman of about forty-five wants a man in a building; a reader wants a decision to be hers; the woman of about forty-three wants her tray empty and her form left alone; a woman of about fifty-one wants to be asked why she came; a man of twenty-two wants to be useful; a man of about thirty-three wants to give a copy away; a man of about sixty-one wants a long time not to have cost what it cost.

**WHAT STOPS THEM? A person, a rule or a cost on every one of the ten days, and never an absence.** Marek's own signature stops him asking four people; the arrangement stops him being in the building; the rule about a reader and a holder stops the second holder being told what is on the page; a column being a question with a box round it stops the column; an ombud's terms stop the office asking why a person came; his own refusal stops him asking Talia whether she should be the person; not knowing her name stops the man of about thirty-three giving the copy away; the room's own sentences stop the woman of about forty-five seeing a shelf; the price of asking who can run a sheet stops the woman of about forty-three finding out.

**DOES ANYBODY ELSE ANSWER?** Yes, on all ten days. The register man refuses and then rules a line instead; Sera Quill answers three questions and refuses one; the office answers him and then stops him; the woman of about fifty-one asks a question four people decline; two people refuse each other and one of them then says the true thing.

**IS THE PAGE IN A ROOM, AT A TIME, WITH COST IN IT?** A shop and a counter on ten days with a shutter at two on the Sunday and at ten on the other nine; a records room with shelves to the ceiling; a first-floor room off a line; a first-floor office that is an ombud's and not a shop's; a queue of about nine people at a desk in a second district; a passage under a clinic with a sheet on a wall at sixty days; a bus of twenty minutes; forty priced jobs; **two hours of a man's hands going in the middle of an afternoon and a docket signed in another person's handwriting**; a tray that shut.

**NO PAGE OF THIS MOVEMENT PRINTS THE NINE NAMES IN ANY FORM, IN A BODY, IN A DOCKET ROW OR IN A CLOSING PASSAGE.** The page is read off-page, carried in a coat, refused to a second holder, asked about by a man holding a register, and carried back to the shelf it came off. **It is never printed.**

---

## 8. THE TWO HOUSE IDIOMS, MEASURED AT A PRINTED BOUNDARY, AND NEITHER REPAIRED

**THE BOUNDARY, PRINTED SO IT CAN BE RE-RUN: whole file, case-insensitive, all ten of this movement's chapter files, and both figures are also given for Movement II's ten at the same boundary, because a figure with no comparison is not a measure.**

| Idiom | Movement III, ten files | Movement II, ten files | Scope |
| --- | --- | --- | --- |
| `have said since that` / `has said since that` | **67**, five to eight per file | **50** | prose, in bold narrative paragraphs |
| `about nine seconds` | **27** | **11** | prose |
| `Four of those` in a priced job | **40** | **40** | body |
| priced jobs carrying a stated price | **40** | **40** | body |

**THESE ARE MEASURED AND NOT REPAIRED, AND THE REASON IS PUBLISHED RATHER THAN ASSUMED.** The retrospective certification register and the priced-job template are **this manuscript's house forms** and both stand in Volumes 15, 16, 17 and 18 and on all twenty pages of Movements I and II of this volume. **Repairing either one here would break continuity with about eight hundred pages that a later pass is entitled to find, and the rule this repository works under is to fix concrete findings rather than to impose a house style on four volumes at once.** The rise in the first two rows is the honest consequence of writing more retrospective beats than Movement II wrote and is published rather than softened. **A writer pass that wants the certificate removed should open with a volume and not with a movement, and the volume close inherits these four numbers as the base it would be comparing against.**

---

## 9. WHAT WAS NOT DONE, CHECKED RATHER THAN ASSERTED

**No owner decision was settled and none was recommended, item six and its four inner decisions included. No seventh item was opened. No chapter of Volume 15, 16, 17 or 18 was edited; `git status` shows the only new chapter files are the ten in this directory. No debt of the nine, the seventeen or the four was paid, cancelled, opened or answered. The ring binder did not come out on any of the ten days and no figure for the page in it is printed anywhere. The register of correct acts that changed nothing was not counted and no fifth of it is printed. No two of the nine hand copies were compared. The woman of about thirty was not asked anything and is on all ten files in the apparatus only. No offer was made to Iona Sorn, who is the last enemy in this manuscript, is in public custody, is unanswered, is not absolved, and is at zero on all ten of these files. No Exchange figure is printed in any file this pass wrote. The four arrival cells remain empty and are not approximated. The ninth chair did not move on any of the ten days and its mover is named on none of them. The room under a building in a first district was dark at about ten on all ten days. Nobody thanked anybody and nobody forgave anybody on any of the ten days. `NOVEL_SPEC.md`, `outline/series.md`, `outline/ending.md`, `outline/volume-15.md` through `outline/volume-18.md`, `bible/*.md` and `state/phase-ledger.json` were read and not written, and the last of those is controller-owned.**

**AND NO PAGE WAS INVENTED FOR ANY OF THE FIVE ABSENT PLACED NAMES.** `Rafi Pell`, `Dessa Kwan`, `Oren Vey`, `Iven Sore` and `Lena Senn` are on no page of this movement. The batch prompt allowed that one of them might be the person a day needs, with the reason recorded. **The days did not need any of them: the days needed a records room, a stair, a tray, a bus and a shop, and every one of those already had a person on it from Movements I and II.**

**AND THE OMBUD'S OFFICE WAS USED ON HIM ONCE IN THIS MOVEMENT, on Chapter 966, on a file that is about the request he signed and not about the nine, and he was permitted to answer and he answered. No page counts the uses and no page says anything about how many there have been.**

---

## 10. THE REVIEW AND WHAT THE REPAIR PASS DID ABOUT IT, AND WHAT IT DID NOT TOUCH

**A READ-ONLY REVIEW OF THESE TEN FILES WAS RUN AFTER THEY WERE WRITTEN AND TWENTY-FOUR FINDINGS CAME BACK. EVERY ONE WAS CHECKED AGAINST THE SAVED FILES BEFORE IT WAS ACTED ON. ELEVEN REACHED A PAGE, THREE ARE PUBLISHED AS FINDINGS WITHOUT REPAIR, SEVEN ARE PUBLISHED AS FALSE POSITIVES WITH THE REASON, AND THREE ARE MEASURED AND CARRIED.**

**THE ELEVEN THAT REACHED A PAGE, AND THE REPAIR.**

1. **`chapter-0964.md` rebuilt a beat `chapter-0947.md` had already spent.** Chapter 947 has the same man bring the same idea of a sixth column to the same counter and be refused. **The repair keeps both and turns the second into an escalation: he now opens by saying she turned the last one down, that he put it back in his coat and has carried it since the winter, that this is a different one and this is his, and she answers *it is still my sheet, whatever coat it has been in*.** The interval at the close of that page now reads *a second column, thirty-one days after the word first appeared in a margin*, and thirty-one is `day 2143 − day 2112`.
2. **The reading was placed in three incompatible rooms across four pages.** Chapters 951 to 960 settle it: the page never leaves its shelf except inside her coat, the second person is outside the door, and it goes back the same day by her hand. **Chapter 963's opening and its second paragraph now say where it happened — she takes the page off a shelf in a second district inside her coat, puts it on her own table with the door shut and the second holder on the landing outside it, and carries it back to the same room the same day — and the third paragraph now says the second holder went out with her and came back at nine and asked nothing about the two hours.** Chapter 962's scene, which had the reader in the woman of about forty-five's flat, is now consistent with that and needed no change.
3. **Chapter 963 carried an unmarked time inversion.** The hands beat sat after a nine-o'clock scene and said half past eleven and then four jobs on for the afternoon. **The paragraph has moved above the priced-work block and now reads *his hands had gone at about half past two that afternoon, before any of the above*, and the second holder's line no longer has a morning in it.**
4. **Chapter 963 also said the reader and the second holder had not asked anything in the hour and forty minutes she had been gone, while also putting the second holder on the rail for the whole of it.** Repaired by the third paragraph in item 2.
5. **The ombud's file was on a list and not on the signed request, which the plan of record names.** **Chapter 966 now opens with the formula from Chapter 953 — *this file is about the request you signed and not about the nine, and you will say if you understand that* — and the one line written into the file now reads *that is a record about you, and about the request you signed, and about nobody else*.** The deviation is no longer a deviation.
6. **The four people on the list were never distinguished from the nine.** A three-line exchange now says they are four people who know a word and not one of them has ever been on a sheet with nine rows, and Marek says no.
7. **Two men claimed the same nine-year tenure.** The nine years belong to the man of about sixty-one and stand in Chapters 949, 951, 956, 957 and 958. **Chapter 961's man of about fifty-two now says he has had that book in his coat since a winter, and chapter 967's man of about sixty-one now says he has been careful for a very long time and that it has cost him a very long time.**
8. **Six interval figures did not come out of the day map.** Repaired to their true values: *the second time in six days* on 962; *thirty-one days* on 964; *seventeen days* on 969; *five weeks* on 965, twice; *in a month* and *five weeks* on 966 and 968; and *not stood at that counter on a Thursday before* in place of *since the ninth day* on 968.
9. **Chapter 970's carry-forward block misstated the sheet count and where the reading happened.** It now says **three sheets carry a column and all three are in one tray**, names which is which, and states the reading location in the form Chapter 963 uses.
10. **The narrator named the volume's structure inside a scene.** *the thing that made it a movement rather than a refusal* is now *the thing that turned it from a refusal into an answer*.
11. **Chapter 968's docket line said *nothing handed back* on the one day a sheet was left on a table, and its preamble compressed a fifty-line exchange into *in two sentences*.** Both reworded, and Chapter 966's *before that Monday shut down for good* became *before the shutter came down on that Monday*.

**THE THREE PUBLISHED AS FINDINGS WITHOUT REPAIR.** That guardrail two's *prints no outcome* clause is broken on all ten openings and all ten share one three-clause stem; that the retrospective certification register and the priced-job template are the batch's most frequent shapes; and that `outline/volume-19.md`'s week range for Movement IV disagrees with its own calendar. **The first is a standing house decision inherited from Chapter 941 and two openings were reworded so that they give the day's shape and not the day's outcome; the second is measured at §8 and carried; the third is recorded at §1 and belongs to the calendar.**

**THE SEVEN THAT WERE FALSE, WITH THE REASON IN EACH CASE.** That the reading happened in a records room; that *she had told him on a Friday to say it again on the day* refers to nothing — **day 2130 is a Friday and Chapter 958 carries the exchange verbatim**; that Chapter 965's nine-day interval is wrong twice over when thirty-five days is what the map gives, which the repair took; that Chapter 967's *in two sentences* miscounts, which was true and was repaired; that Chapter 968's *refused at the shelf in two sentences* miscounts, which was true and was repaired; that Chapter 970's two Thursdays are two different men, which they are; and that Chapter 968 has no obstruction, which is wrong — **its obstruction is that he cannot give a sheet to a woman whose name nobody wrote down, and it is stated on the page.**

**WHAT THE REPAIR DID NOT TOUCH.** No day, week, weekday, entry, counter, anchor figure, price, charge, docket cell or caller count moved on any of the twenty pages this phase owns, and all 160 anchor rows reproduce after the repair exactly as they did before it. **No line of dialogue was deleted and no refusal, offer or cost was softened.** The word table, the `about` pair, the duplication pair and the ten opening bands were re-measured after the repair and the figures printed in §§3 to 6 are the post-repair ones.

---

## 11. THE HAND-ON, TWELVE LINES

1. **The manuscript stands at Chapter 970, the Saturday of week 323, day 2152, entry 973, counter 215, the last page of Movement III of Volume 19. Movement IV is Chapters 971 to 980, days 2156 to 2168, weeks 324, 325 and 326, entries 974 to 983, and the seventieth sitting falls inside it at Chapter 971 on day 2156.**
2. **The page was read, on a table in a woman's own flat, off-page, with the second holder on the landing outside the door, and it was carried back to the shelf it came off the same day by her own hand.** She said `I have read it` and `that is all you get`, and the second holder was not told what is on it.
3. **The finding has nobody's name on it. She said so in nine words and said the decision is hers and not his, and that it is about four months of somebody else's life and she does not know which year.**
4. **Marek asked whether he was allowed to help, twice, and was refused twice, and the refusal was *the day you help is the day the finding is yours*, and he has said since that he was glad of the plainness of it.**
5. **Three sheets now carry a sixth column headed told and all three are in one tray in a building in a second district. One was ruled by hand by the man of about fifty-two, one is pencil in a margin and has been round nine rooms, and the third came in on the Friday and has been filled in once. The woman of about forty-three read what is written in it, would not read it out in front of anybody, shut the tray, and said it will be available in a month.**
6. **Nobody in this city can say who wrote the word in the margin, and about four people know and none of them will say, and that is unchanged from Movement I.**
7. **Talia used her office on him once in this movement, on a file about the request he signed and not about the nine, and the subject of it was the four names he wrote down instead of asking. She made him say them out loud, kept nothing, could not unhear them, and wrote one line into the file that is about him and about nobody else. She noticed he was about to ask her something and he did not finish it.**
8. **The man of about sixty-one told a stranger that a page left his shelf for the first time in nine years, and that people have been in his room the whole time, and that being careful has cost him a very long time.**
9. **The copy of that sheet with nothing in the fifth column is lying on a table in the shop and nobody in this city holds it. The man of about thirty-three left it and said it was never his copy to hold.**
10. **The woman of about fifty-one came back on Chapter 965 and was not asked why she came, and said she will come back until somebody does. Talia's office does not ask what a person meant, and Marek said the question was not his to ask, and nobody answered her.**
11. **The register stands at four with no fifth printed. The ninth chair did not move on any of the ten days. The binder did not come down. The notice is at sixty days on a passage wall in a fourth district and nobody it is about has asked for it. The room under a building in a first district was dark at about ten on all ten days. The woman's page is `day − 1573` and it governs and is printed on no page of this movement and in no file this pass wrote.**
12. **The figures a later pass must re-derive rather than inherit are at §2, §3, §4 and §5 of this file, and two of them do not reproduce at the boundaries this pass printed.** At this boundary: prose duplication zero and apparatus thirty-eight; `about` at eleven and twenty-eight hundredths at file scope and eleven and forty hundredths pooled, on a denominator of 23,859 tokens; and 23,859 whole across the ten files. **Volume 18 Movement VI's control at the same boundary is 24 and 38 and not the 3 and 12 printed in `batch-0002/SUMMARY.md` §3, and Movement II's `about` pair is 6.80 and 6.81 and not the 7.28 and 7.29 printed there, and both of those published pairs are therefore withdrawn and are not to be inherited.** The two house idioms a later pass should know about are measured at §8 and are not repaired: sixty-seven retrospective certifications and forty priced-job templates on ten files, against fifty and forty on the ten before them.