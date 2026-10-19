# Cobblemon Daycare 0.15.1 BETA

- `/daycare eggs` now shows persisted egg records (up to 32 eggs) as egg icons in the GUI.
- The egg GUI is read-only: egg icons are representations of stored data, not vanilla item stacks.
- `/daycare admin egginstant <enclosure>` creates one egg immediately in the owner’s bag, checking compatibility, unlocked pen and capacity; it does not hatch the egg or reset the 10-minute timer.
- `/daycare eggbag list` displays egg records.

This is an uncompiled, untested source patch. Build with GitHub Actions, test only on a backed-up copy of the world. The underlying experimental custody system remains unchanged.
