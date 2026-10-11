# High Halls Big Shaft (Hang_08)

**Game ID:** Hang_08

**Contributors:** samupo, rebel

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Top | ✓ |
| S2 | Middle | ✓ |
| S3 | Left Spike Exit | ✓ |
| S4 | Bottom | ✓ |
| S5 | Behind Sentinel Gate | ✓ |
| S6 | Resting Site Ledge | ✓ |
| S7 | Penthouse | ✓ |
| S8 | Clawline Gate 2 | ✓ |
| S9 | Clawline Gate 3 | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SL | left3 | Left Spike Exit | [High Halls Flooded Room (Hang_10)](high-halls-flooded-room.md) | R | none |  | Verified | ✓ |  |
| B | bot1 | Bottom | [High Halls Vault (Hang_06)](high-halls-vault.md) | T | none |  | Verified | ✓ | One way only (opened from this side) |
| L | left4 | Bottom | [High Halls Baby Room (Hang_16)](high-halls-baby-room.md) | R | none |  | Verified | ✓ |  |
| NI | right2 | Middle | [High Halls Not Implemented Room (Cog_11)](high-halls-not-implemented-room.md) | L | invalid |  | Verified | ✓ | NOT IMPLEMENTED BY DEVS |
| R | right1 | Behind Sentinel Gate | [High Halls Sentinel Graveyard (Hang_17b)](high-halls-sentinel-graveyard.md) | L | Activate Clawline Gate 3 AND complete THE Final Audience Wish Promised |  | Verified | ✓ |  |
| ML | left2 | Middle | [High Halls Cogfly Room (Hang_09)](high-halls-cogfly-room.md) | R | none |  | Verified | ✓ |  |
| TL | left1 | Top | [High Halls Big Slide (Hang_13)](high-halls-big-slide.md) | R | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TF | Falling from Top | Top | Clawline Gate 2 | clawline AND drifter's cloak AND Activate Clawline Gate 1 |  | Verified | ✓ |  |
| TF | Falling from Top | Clawline Gate 2 | Top | Invalid | TODO | Needs verification | ✓ | Previously a one-way connection. probably intentional, need to check for possible routes. |
| C | Clawline | Clawline Gate 2 | Middle | clawline AND drifter's cloak AND Activate Clawline Gate 2 |  | Verified | ✓ |  |
| C | Clawline | Middle | Clawline Gate 2 | Invalid | TODO | Needs verification | ✓ | Previously a one-way connection. probably intentional, need to check for possible routes. |
| S | Spiked Secret | Middle | Left Spike Exit | drifter's cloak AND (cling grip OR clawline) AND break wall left |  | Verified | ✓ |  |
| S | Spiked Secret | Left Spike Exit | Middle | Invalid | TODO | Needs verification | ✓ | Previously a one-way connection. probably intentional, need to check for possible routes. |
| SF | Falling from Secret | Left Spike Exit | Clawline Gate 3 | drifter's cloak AND clawline |  | Verified | ✓ |  |
| SF | Falling from Secret | Clawline Gate 3 | Left Spike Exit | Invalid | TODO | Needs verification | ✓ | Previously a one-way connection. probably intentional, need to check for possible routes. |
| MF | Falling from Middle | Middle | Clawline Gate 3 | drifter's cloak AND clawline |  | Verified | ✓ |  |
| MF | Falling from Middle | Clawline Gate 3 | Middle | Invalid | TODO | Needs verification | ✓ | Previously a one-way connection. probably intentional, need to check for possible routes. |
| WG | wish gate | Bottom | Behind Sentinel Gate | complete THE final audience wish promised |  | Verified | ✓ |  |
| WG | wish gate | Behind Sentinel Gate | Bottom | complete THE final audience wish promised |  | Verified | ✓ |  |
| TR | top to resting site | Top | Resting Site Ledge | clawline |  | Verified | ✓ |  |
| TR | top to resting site | Resting Site Ledge | Top | none (falling) |  | Verified | ✓ |  |
| RP | resting site to penthouse | Resting Site Ledge | Penthouse | silk soar OR cling grip |  | Verified | ✓ |  |
| RP | resting site to penthouse | Penthouse | Resting Site Ledge | none (falling) |  | Verified | ✓ |  |
| FC3 | Floor <> Clawline 3 | Clawline Gate 3 | Bottom | Activate Clawline Gate 3 |  | Verified | ✓ |  |
| FC3 | Floor <> Clawline 3 | Bottom | Clawline Gate 3 | Invalid | TODO | Needs verification | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | High Halls - Rosary Cache | Penthouse | none |  | Verified | collectible | ✓ |  |
| 2 | Resting Site: High Halls | Resting Site Ledge | complete THE A Vassal Lost Wish Promised |  | Verified | event | ✓ |  |
| 3 | Clawline Gate 1 | Top | Clawline |  | Verified | switch | ✓ |  |
| 4 | Clawline Gate 2 | Clawline Gate 2 | Clawline |  | Verified | switch | ✓ |  |
| 5 | Clawline Gate 3 | Clawline Gate 3 | Clawline |  | Verified | switch | ✓ |  |
| 6 | Minister 1 | Middle | free |  | Verified | enemy | ✓ |  |

## Notes

the subroom connections in this room need a lot of work. it may be worthwhile to just start from scratch instead of frankensteining something usable out of them.

## Room Images

### Connections

[![Connections for High Halls Big Shaft (Hang_08)](../00-annotations/high-halls/high-halls-big-shaft-connections.png)](../00-annotations/high-halls/high-halls-big-shaft-connections.png)

### Checks

[![Checks for High Halls Big Shaft (Hang_08)](../00-annotations/high-halls/high-halls-big-shaft-checks.png)](../00-annotations/high-halls/high-halls-big-shaft-checks.png)

### Scene

[![Scene for High Halls Big Shaft (Hang_08)](../00-annotations/high-halls/high-halls-big-shaft-scene.png)](../00-annotations/high-halls/high-halls-big-shaft-scene.png)
