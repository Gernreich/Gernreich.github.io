# LaserMadeMusic

Musical instruments cut from 3mm Baltic birch plywood on a laser, and the cut files to
build them. Everything here is millimetre-true at `1 user unit = 1mm`, so a file prints
and cuts at real size, and every part is a flat plate joined to other flat plates.

The cutting and the playing are on **[LaserMadeMusic](https://www.youtube.com/@LaserMadeMusic)**.

## The instruments

| | |
| --- | --- |
| **[trumpet-coiled](https://gernreich.github.io/trumpet-coiled/)** | A trumpet bore in 25 × 25mm square section that coils flat and drops twice, built with no elbows |
| **[trumpet-octagonal](https://gernreich.github.io/trumpet-octagonal/)** | The trumpet form of the octagonal torus — a curved octagonal bore on the same channel |
| **[trumpet-parts](https://gernreich.github.io/trumpet-parts/)** | The bell and the mouthpiece, shared by every trumpet built on that channel |
| **[torus-octagonal](https://gernreich.github.io/torus-octagonal/)** | An octagonal torus: two nested octagonal tubes joined by annular plates |
| **[kalimba](https://gernreich.github.io/kalimba/)** | A seven-sided kalimba body whose front carries a seven-fold knot rosette |
| **[slapstick](https://gernreich.github.io/slapstick/)** | Two long slats joined at one end; swing it and the free ends clap |
| **[bullroarer](https://gernreich.github.io/bullroarer/)** | Five blade profiles for a bullroarer, whirled on a cord |
| **[buzz-disc](https://gernreich.github.io/buzz-disc/)** | Two designs for a buzz disc, threaded on a cord loop that winds and unwinds |

## The generators

Parts too fiddly to draw by hand, made by a script instead.

| | |
| --- | --- |
| **[bore-generator](https://gernreich.github.io/bore-generator/)** | Turns a bore written as a walk through a lattice of blocks into checked cut files |
| **[bore-designs](https://gernreich.github.io/bore-designs/)** | Every bore worked out so far, built into cut files — the corpus the generator regresses against |
| **[knotwork-soundholes](https://gernreich.github.io/knotwork-soundholes/)** | Knotwork rosettes for an instrument sound hole, by leads and bights |
| **[living-hinge](https://gernreich.github.io/living-hinge/)** | Parametric lattice-hinge patterns, so a flat sheet will bend |

## The tools

| | |
| --- | --- |
| **[lasermade-tools](https://gernreich.github.io/lasermade-tools/)** | Shared checkers: what a writeup claims about itself, and what a cut file claims about its colours |

## Colour is the cut order

Shared by every repository here: **blue engraves, then green → orange → cyan → black**,
with black always the cut that frees the part, and **violet `#8000ff` meaning skip**. A
file uses only the stages it needs.

The one deliberate exception is `test-ladder.py`, where colour carries cut *speed* rather
than order — because splitting an import into layers by colour is the only place a laser
importer will let a separate speed live.

## Why the writeups say where they went wrong

Each build page records the mistakes as well as the method: the bell whose material figure
was right for two sizes and wrong for a third, the bore that was 6mm short per section
because a block was measured at 25mm instead of 31, the checker that passed a page 15/15
while twelve of its thirteen images 404'd. A build sheet that only records what worked is
the one that costs someone a sheet of ply.

Released under [CC0 1.0](LICENSE).
