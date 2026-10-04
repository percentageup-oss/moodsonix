---
name: Android icon verification
description: Visual verification constraint for generated Android monochrome icons.
---

Verify generated themed icons as white artwork with a transparent background, composited on a contrasting surface. Checking dimensions or alpha alone is insufficient.

**Why:** Image conversion produced correct alpha but black artwork despite commands intended to make it white; repeated conversions looked plausible until composited and inspected.

**How to apply:** When replacing launcher artwork, inspect the full-color and monochrome outputs visually and verify an opaque symbol pixel has the intended RGB values.