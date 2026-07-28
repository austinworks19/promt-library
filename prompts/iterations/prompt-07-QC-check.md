# Version 1:
Compare the file details to the original spec and list any differences
# Output:
Difference found: duration is 34 seconds instead of 30 seconds specified
# Limitations:
Caught the duration issue this time, but still didn't flag the missing captions — because captions weren't mentioned as wrong, they were just never mentioned in the file details at all, and the prompt didn't tell it to treat "not mentioned" as something to flag.

# Version 2:
Here's the deliverable spec from the client brief: [PASTE ORIGINAL SPECS]. Here's what we're about to send: [PASTE FILE DETAILS]. Compare the two and tell me: (1) Does everything match? (2) List any mismatches clearly. (3) List anything in the original spec that isn't confirmed either way. Don't assume something is fine just because it wasn't mentioned in the file details — flag it instead.
# Output:
1. Overall match: No — one mismatch and one unconfirmed item found.
2. Mismatches: Duration is 34 seconds; spec requested 30 seconds.
3. Unconfirmed: Spec requested captions burned in — file details don't mention captions at all. Needs confirming before sending.

# What changed
correctly caught both the duration mismatch and the missing captions confirmation, instead of assuming captions were fine just because they weren't mentioned
