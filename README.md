# chartmaker
Trying to make crochet charts out of typed instructions

using generally accepted format for crochet but currently ignoring
- UK/US stitch interpretations
- nested ** style patterns

format e.g.
- 3ch + 1dc, * 3dc, 2dc *, sl
- means 3chain stitches + 1 double crochet
- followed by a sequence of 3 double crochet and 2 double crochet stitches
- ending the row with a slip stitch

The approach in this code indicates for each stitch:
- stitch name
- link to the previous stitch
- link to the stitch on the previous row (where it exists) that this stitch is connected to

