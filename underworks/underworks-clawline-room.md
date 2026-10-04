# Underworks Clawline Room (Under_18)

**Game ID:** Under_18

**Contributors:** Rebel

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Clawline Statue | ✓ |
| S2 | Blocked Off Corridor Left | ✓ |
| S3 | Shard Bundle Check | ✓ |
| S4 | Main Side Door | ✓ |
| S5 | Arena | ✓ |
| S6 | Blocked Off Corridor Top | ✓ |

- **Arena:** Arena activated by Clawline Ring

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TR | Top Right | Arena | [Underworks Twelfth Architect (Under_17)](underworks-twelfth-architect.md) | BR | (Clear Underworks Clawline Gauntlet AND (Cling Grip OR Scuttlebrace OR Silk Soar OR (Faydown Cloak AND (Easy Shaman Pogo OR Easy Beast Charge)))) |  | Verified | ✓ |  |
| L | Left | Blocked Off Corridor Left | [Underworks East Shaft (Under_13)](underworks-east-shaft.md) | MR | Nothing. |  | Verified | ✓ |  |
| R | Right | Main Side Door | [Underworks Clawline Entrance (Under_19c)](underworks-clawline-entrance.md) | TL | Invalid |  | Verified | ✓ |  |
| TL | Top Left | Blocked Off Corridor Top | [Underworks Twelfth Architect (Under_17)](underworks-twelfth-architect.md) | BL | Nothing. |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| AP | Arena Path | Main Side Door | Arena | Clawline OR (Faydown Cloak AND (Sharp Dart OR Swift Step 2) AND Ledge Grab AND Enemy Pogo) |  | Verified | ✓ | getting up here without clawline is worthless unless cause the exit needs clawline anyway lmao |
| CP | Clawline Path | Main Side Door | Clawline Statue | Clawline OR (Faydown Cloak AND Sprint AND (Drifter's Cloak OR (Dash AND Enemy Pogo)) AND Ledge Grab) |  | Verified | ✓ |  |
| SP | Shard Path | Main Side Door | Shard Bundle Check | Clawline OR (Faydown Cloak AND (Sharp Dart OR Swift Step 2) AND Ledge Grab AND Easy Enemy Pogo) |  | Verified | ✓ | same thing as the arena path but you go left at the end instead of right |
| LST | Left Side Travel | Blocked Off Corridor Left | Blocked Off Corridor Top | Silk Soar OR Cling Grip OR Scuttlebrace OR (Faydown Cloak AND (Ledge Grab OR Clawline)) |  | Verified | ✓ |  |
| AP | Arena Path | Arena | Main Side Door | Clawline OR Sharp Dart OR Dash OR Sprint OR Scuttlebrace OR Drifter's Cloak OR (Faydown Cloak AND Ledge Grab) |  | Verified | ✓ |  |
| CP | Clawline Path | Clawline Statue | Main Side Door | Clawline OR (Sharp Dart AND Faydown Cloak AND (Swift Step 2 OR Drifter's Cloak)) |  | Verified | ✓ |  |
| SP | Shard Path | Shard Bundle Check | Main Side Door | Clawline OR ((Drifter's Cloak OR Progressive Swift Step 2) AND (Easy Enemy Pogo OR (Faydown Cloak AND Sharp Dart))) |  | Verified | ✓ |  |
| LST | Left Side Travel | Blocked Off Corridor Top | Blocked Off Corridor Left | Nothing. (Fall) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Clawline Pickup | Clawline Statue | Nothing. |  | Verified | collectible | ✓ |  |
| 2 | Underworks: Shard Bundle #2 | Shard Bundle Check | Nothing. |  | Verified | collectible | ✓ |  |
| 3 | Clawline Ring | Arena | Clawline |  | Verified | switch | ✓ |  |
| 4 | Underworks Clawline Gauntlet | Arena | Activate Clawline Ring |  | Verified | gauntlet | ✓ |  |

## Notes

Left and right sides of this room are not connected.

## Room Images

### Connections

[![Connections for Underworks Clawline Room (Under_18)](../00-annotations/underworks/underworks-clawline-room-connections.png)](../00-annotations/underworks/underworks-clawline-room-connections.png)

### Checks

[![Checks for Underworks Clawline Room (Under_18)](../00-annotations/underworks/underworks-clawline-room-checks.png)](../00-annotations/underworks/underworks-clawline-room-checks.png)

### Scene

[![Scene for Underworks Clawline Room (Under_18)](../00-annotations/underworks/underworks-clawline-room-scene.png)](../00-annotations/underworks/underworks-clawline-room-scene.png)
