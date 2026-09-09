# CLAUDE.md

Personal fitness and nutrition documents for one person. No code, no build, no tests — the deliverable is the prose and the numbers in it.

## Files

| File | What it is |
|---|---|
| `body-recomp-meal-plan.md` | The main plan. 5'9", 160 lbs, 145g protein/day, ~2,269 cal 7-day average. |
| `upper_body_dumbbell_workout.md` | 3x/week dumbbell routine, Mon/Wed/Fri. |
| `monthly-grocery-estimate.txt` | Monthly peso cost, split by store. |

## Writing rules

**Write for a first-time reader.** No changelogs, no "updated", no "this replaces", no notes about what changed or why it changed. The reader should never be able to tell the document was edited.

**Keep it short.** These files are already dense and the user finds walls of text tiring. Prefer deleting a paragraph to adding one — every edit should aim to leave the file no longer than it was. Don't add a note to explain a change; just make the change read as if it was always that way.

**Don't add sections.** Fit new information into the structure that exists.

## Numbers

Changing one number usually means changing several. When editing a meal, trace it through:

1. The protein rotation table
2. That day's row in Daily Totals
3. The six-day and 7-day averages, and the against-target table
4. Cooking Each Day and the breakfast chicken blocks
5. Grocery quantities and the chicken portion packs
6. Any prose that quotes the figure

Grep the old number across the file before finishing.

**Fixed conventions:** all meat, fish and rice are weighed **cooked**. Vegetables, tomato and onion are logged at zero protein. Chicken breast is 31g protein per 100g cooked. Prices are pesos.

The 145g protein target is the anchor — flag it if an edit pushes a day off target, but the user decides whether that's acceptable.
