# Portrait alternatives

## A — Festival beads

- Add 120 small, visible circles in three rings around the face, using a loop.
- Alternate coral, teal, and gold beads to suggest a cheerful festival mask.
- Keep the neutral eyes and mouth so the geometric border is the main change.

## B — Night-sky stickers

- Draw two original SVG image files with a text editor: a gold star and a blue
  crescent moon, with Codex assistance credited in source comments.
- Place the star on the left cheek and the moon on the right cheek.
- Import both local assets through Vite and keep the script-built head and eyes.

## C — Sunset smile

- Shade the head with a linear gradient from warm peach to soft violet.
- Replace the straight mouth with a quadratic Bézier smile and add two gently
  curved brows to make a relaxed, friendly character.
- Keep the silhouette and high-contrast eyes simple.

## Selection criterion

Choose the portrait whose expression stays friendly and clear when viewed small,
without decoration competing with the eyes and mouth.

## Exploration status

- A explored on branch A: 120 circles form three colorful rings. The outer ring
  sits just beyond the head, making the intended festival border easy to see.
- B explored on branch B: two distinct, original SVG assets show a star and a
  crescent on the cheeks. Both appear in development and the production build.
- C explored on branch C: the peach-to-violet gradient, curved smile, and curved
  brows match the planned relaxed expression.
- These are explored alternatives, not merged features. No major departures
  from the original plan were needed, and main still shows the neutral face.

## Final decision

Choose C, the sunset smile. Its curved mouth and brows communicate a friendly
expression immediately, and the broad peach-to-violet transition remains clear
at a small size. A's 120 beads create a lively border but compete with the facial
features when reduced. B's cheek stickers are distinct, though they decorate the
neutral expression rather than changing it. C best meets the original criterion.

The status above records the earlier exploration checkpoint, when main was still
neutral. Main now adopts C through a fast-forward after rebasing C onto the
neutral buildFace() refactor; the chosen artwork is constructed inside that
function, while mounting and Spin remain outside. A and B remain untouched on
their original sibling branches for comparison and grading.

## Assistance

Codex assisted with the plan, original artwork, implementation, checks, and Git
operations at the student's explicit request. Assisted commits include a trailer.
