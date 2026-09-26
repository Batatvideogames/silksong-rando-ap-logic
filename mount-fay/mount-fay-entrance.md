# Mount Fay Entrance (Peak_01)

**Game ID:** Peak_01

**Contributors:** Pyxl

## Subrooms

- Slab Spool Room
- Slab Side Room Lower
- Slab Side Room Upper
- lower Entrance
- Lower Left Exit
- Lower Middle Left Exit
- Upper Middle Left Exit
- Upper Left Exit
- Shell Shard Ledge

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LSR | right3 | Slab Spool Room | [Slab Flea Prison (Slab_13)](../the-slab/slab-flea-prison.md) | L | None |  | Verified |  |
| C4 | top4 | Upper Left Exit | [Mount Fay Right Side Middle Room (Peak_07)](mount-fay-right-side-middle-room.md) | F4 | Silk Soar |  | Verified |  |
| C2 | top2 | Upper Left Exit | [Mount Fay Right Side Middle Room (Peak_07)](mount-fay-right-side-middle-room.md) | F2 | Silk Soar |  | Verified |  |
| C3 | top3 | Upper Left Exit | [Mount Fay Right Side Middle Room (Peak_07)](mount-fay-right-side-middle-room.md) | F3 | Silk Soar |  | Verified |  |
| UL | left1 | Upper Left Exit | [Mount Fay Shakra (Peak_02)](mount-fay-shakra.md) | UR | None |  | Verified |  |
| LL | left4 | Lower Left Exit | [Mount Fay Shakra (Peak_02)](mount-fay-shakra.md) | LR | None |  | Verified |  |
| LML | left3 | Lower Middle Left Exit | [Mount Fay Shakra (Peak_02)](mount-fay-shakra.md) | LMR | None |  | Verified |  |
| UML | left2 | Upper Middle Left Exit | [Mount Fay Shakra (Peak_02)](mount-fay-shakra.md) | UMR | None |  | Verified |  |
| USR | right1 | Slab Side Room Upper | [Slab Arena (Slab_16)](../the-slab/slab-arena.md) | L | None |  | Verified |  |
| C1 | top1 | Upper Left Exit | [Mount Fay Right Side Middle Room (Peak_07)](mount-fay-right-side-middle-room.md) | F1 | Cling Grip AND ( Clawline OR ( Faydown Cloak AND DRifters Cloak AND Dash ) OR ( Drifters Cloak AND Sharpdart AND ( Proficient Movement AND Spike Pogo ) AND Hard Heal Stall AND Hard Cocoon Skip ) ) |  | Verified |  |
| MSR | right2 | Slab Side Room Lower | [Slab Chilly Prison (Slab_15)](../the-slab/slab-chilly-prison.md) | L | None |  | Verified |  |
| LR | right4 | lower Entrance | [Slab Bellway (Slab_06)](../the-slab/slab-bellway.md) | L | None |  | Verified |  |
| DU | Dummy | Upper Left Exit | [Mount Fay Right Side Middle Room (Peak_07)](mount-fay-right-side-middle-room.md) | F5 | Invalid |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SL | Slab Connection | Slab Side Room Upper | Slab Side Room Lower | None |  | Verified |  |
| SL | Slab Connection | Slab Side Room Lower | Slab Side Room Upper | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| LC | Lower Crossing | lower Entrance | Lower Left Exit | Silk Soar OR Clawline OR ( Faydown Cloak AND ( Proficient Movement AND Spike Pogo ) AND Hard Heal Stall AND Hard Cocoon Skip AND Ledge Grab ) OR ( Sharpdart AND Drifters Cloak ) |  | Verified |  |
| LC | Lower Crossing | Lower Left Exit | lower Entrance | Cling Grip OR Silk Soar OR Clawline OR Faydown Cloak OR ( Dash AND ( Sprint OR Drifters Cloak OR Sharpdart OR easy Beast Crest pogo OR Medium Heal Stall ) ) |  | Verified |  |
| LL | Lower Ledge | Lower Left Exit | Lower Middle Left Exit | Silk Soar OR ( Faydown Cloak AND ( Cling Grip OR ( Hard Heal Stall AND Scuttlebrace ) ) ) |  | Verified |  |
| LL | Lower Ledge | Lower Middle Left Exit | Lower Left Exit | None |  | Verified |  |
| MC | Middle Crossing | Lower Middle Left Exit | Shell Shard Ledge | ( Cling Grip AND ( ( Clawline OR Drifters Cloak OR ( Faydown Cloak AND ( Dash OR Sharpdart ) ) ) OR ( Medium Reaper Crest pogo AND Faydown Cloak AND Clawline AND ( Proficient Movement AND Spike Pogo ) ) ) ) |  | Verified |  |
| MC | Middle Crossing | Shell Shard Ledge | Lower Middle Left Exit | Clawline OR Silk Soar OR Drifters Cloak OR ( Dash AND Faydown Cloak ) |  | Verified |  |
| SS | Silk Soar Shards | lower Entrance | Shell Shard Ledge | Silk Soar |  | Verified |  |
| SS | Silk Soar Shards | Shell Shard Ledge | lower Entrance | None |  | Verified |  |
| TA | The Ascent | Lower Middle Left Exit | Upper Middle Left Exit | Silk Soar OR ( Cling Grip AND ( Clawline OR ( Faydown Cloak AND Drifters Cloak ) OR ( Sharpdart AND Drifters Cloak AND Hard Cocoon Skip AND ( Sprint OR Have Tool Flintslate ) ) ) ) |  | Verified |  |
| TA | The Ascent | Upper Middle Left Exit | Lower Middle Left Exit | None |  | Verified |  |
| SH | Shortcut | Upper Middle Left Exit | Upper Left Exit | Faydown Cloak OR Silk Soar OR ( complete Breakable Wall - Mount Fay Entrance AND ( Cling Grip OR Scuttlebrace OR ( Easy Beast Crest pogo AND Medium Heal Stall AND Ledge Grab ) ) ) |  | Verified |  |
| SH | Shortcut | Upper Left Exit | Upper Middle Left Exit | None |  | Verified |  |
| DR | Drop | Upper Left Exit | Shell Shard Ledge | None |  | Verified |  |
| DR | Drop | Shell Shard Ledge | Upper Left Exit | Silk Soar |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mount Fay - Shell shard cache #1 | Shell Shard Ledge | None |  | Verified | resource |  |
| Mount Fay - Shell shard cache #2 | Shell Shard Ledge | None |  | Verified | resource |  |
| The Slab - Spool Fragment | Slab Spool Room | cling grip OR Scuttlebrace OR Silk Soar |  | Verified | collectible | Duplicate check name for spool fragment? |
| Breakable Wall - Mount Fay Entrance | Upper Left Exit | None |  | Verified | blockade |  |
