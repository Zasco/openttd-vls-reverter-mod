# OpenTTD "Very Large Ships" Reverter Mod

A NewGRF mod for *OpenTTD* that restores the original specifications of the [default ships](https://wiki.openttd.org/en/Manual/Ships) modified by the [*Very Large Ships* (**VLS**)](https://bananas.openttd.org/package/newgrf/425f0101) NewGRF.

## Purpose

**VLS** replaces the specifications of the default ships instead of overloading them. The changes are thus permanently applied to savegames in which it is added.

Consequently, removing **VLS** from a savegame causes the modified ships to disappear from availability rather than restoring the original default ships.

This mod addresses that problem by restoring the default specifications through overloading rather than replacing them, avoiding the same issue when the mod is removed.

## Limitations

Removing this mod does not restore the ships' availability and their default specifications. The [`resetenginepool`](https://docs.openttd.org/source/d3/d09/console__cmds_8cpp#a5eb16ba5788072d2df14d303913b0d88) command is required to reset them.