# Review — Volume 02, Batch 0001 (Chapters 51–60, "The Blank Field")

**Reviewed:** after two writer repair passes, by an independent review of the delivered prose and the state files it describes.
**Manuscript:** `workspace/volume-02/batch-0001/chapter-0051.md` … `chapter-0060.md`, ~35,200 words.
**Outcome:** fourteen items fixed. No plot moved, no scene cut, no ending altered, no canon reversed, no batch restarted.
**Full item list and reasoning:** `workspace/volume-02/batch-0001/SUMMARY.md`, section *A third pass, fourteen items*.

## What the review checked

Prose for internal contradiction, seam and voice; every dated figure in Chapters 51–60 against Chapters 30, 48, 49, 50 and against each other; quotation-mark parity; the state files against the prose they describe; and the next phase prompt against both.

## Blocking — contradictions inside the delivered prose

1. **Chapter 51 contradicted its own arithmetic.** The page is four load-book blocks and two sentences said three. Now four, and the joke survives.
2. **Chapter 58 had an orphaned reply.** *Then we are both doing the same job* answered a line the repair had replaced. Rewritten so Vey answers the refusal he was actually given, and the nine seconds are paid off inside the answer.
3. **Chapter 55's headcount was half-reconciled.** The room is forty; one line still said thirty. Now forty everywhere, with the door's list of forty-one and the thirty-eight certificates distinguished.
4. **Chapter 58's load-book entry had two stale details** — an unnamed *box on a post* where the yard's box is on a wall and on a sheet, and a *man of forty-one* that a reader would attach to Yvette Kohl. Kohl is a woman of forty-six; the man of forty-one is Oren Vey, and the entry now says so and asks Vey's own question.

## State files were not carried along with the prose

5. **The fourteen-weeks canon rule was broken by seven state lines** in four files. All are fourteen now. The Volume 01 thirteens are untouched and the note that forbade the word fourteen is qualified rather than deleted.
6. **The fifty-to-forty minute fix in Chapter 59 did not reach** `character-state.md` or the Chapter 59 summary, which also still dated Bea Nunn's unstated rule to a Monday.
7. **The Exchange book count had three answers in four files**, and one file asserted two of them in a single paragraph.
8. **The Saturday headcount was recorded as forty-one** in three state files where the prose says forty.

## The next phase prompt

9. **A 09:30 intake was scheduled in the evening twice** — in the day map and on the Chapter 62 card, in the chapter that also has a 07:00 depot start. It is 09:30, an hour and a half, in the practical hall.
10. **Three figures had drifted:** *about six or seven* flood rounds, *thirty-one repairs*, and a description of the Chapter 51 load-book page that no longer exists.

## Pre-existing error the passes walked past

11. **Chapter 59's clock did not close.** Ten past nine at the door, forty minutes on the bench, and the room emptying at two minutes to ten; and *you are forty minutes late* said at ten past ten for a ten o'clock meeting, against Bea Nunn's *forty-five minutes late* at a quarter to eleven, which was right. **Both now exact.**

## Confirmed correct, and left alone

- **The Chapter 58 reassignment of the price away from Marek and back onto Tam Arrick**, checked against `chapter-0049.md:165` and `:181` — the minuted price, *not in this room*, the middle finger, Deb, the registrar. This is the strongest fix in the batch.
- **Chapter 53's fourth condition** reading *not limited to Institute equipment*, per Chapter 49.
- **The cut of Kohl's eleven months, fourteen months and the river** as premature spends of the Chapter 75 midpoint, and the removal of the year from Chapter 58.
- **The four-and-two condition split and the re-dating of the review to the week of week 30**, which are forced by the arithmetic and were propagated into the outline instead of being left to contradict it.
- **No System panel in any of the ten chapters**, and the interface has spoken three times in sixty.

## Flagged, controller-owned, not touched

- `state/phase-ledger.json` still reads `phase-000-bootstrap`, `planned`, `attempts: 0` after nine phases. Off limits to this phase.
- Two next-phase prompts exist: the specific `workspace/volume-02/batch-0002/PROMPT.md` and the generic `workspace/continuation/next/PROMPT.md` seeded in `dbbec94`. **The generic one is left in place**, because deleting a phase directory the dispatcher may already be pointing at would strand the pipeline. The specific prompt is the correct one and is the one referenced from `state/current.md`.
