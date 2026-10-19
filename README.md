# Cobblemon Daycare v0.14.1 — EXPERIMENTAL / TEST WORLD ONLY

Prototype source of real Pokémon custody for Cobblemon Fabric 1.21.1.

- Pedro's picker now attempts to serialize a Pokémon to `cobblemon_daycare_custody.json` **before** removing it from the party.
- Clicking an occupied pen slot attempts to restore the Pokémon to an available party slot.
- Breeding checks and egg creation can read stored Pokémon snapshots.
- Prevents depositing the last party Pokémon.
- Restores only to party; **PC fallback is not implemented**. Free a party slot before withdrawing.

## IMPORTANT LIMITATIONS

This is **untested experimental source**, NOT safe for the main server. There is no atomic transaction spanning Cobblemon's party save and the Daycare custody file. Server crashes, errors, or administrative pen clearing can leave orphaned custody snapshots or inconsistencies. Make a full backup of the world, Cobblemon storage and `cobblemon_daycare_*.json` first. Test on a disposable world with disposable Pokémon only. If anything fails, stop and restore the complete backup; do not repeat clicks.

The vanilla chest GUI remains. The chicken skin is not active. The workflow compiles via GitHub Actions; no successful compilation is claimed.
