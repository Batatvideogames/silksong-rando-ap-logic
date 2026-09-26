# Slab Cavern Exit (Slab_23)

**Game ID:** Slab_23

## Subrooms

- Left
- Right
- Cavern

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Slab Cell (Slab_03)](slab-cell.md) | L3R | none |  |  |  |
| R | right1 | Right | [Slab Shaft (Slab_21)](slab-shaft.md) | BL | none |  |  |  |
| D1 | door1 | Left | [Slab Penitent Cell (Slab_Cell_Creature)](slab-penitent-cell.md) | L | none |  |  |  |
| D2 | door2 | Cavern | [Slab Quiet Cell (Slab_Cell_Quiet)](slab-quiet-cell.md) | T | none |  |  | Cavern door, for alternate entry, TBD |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Indolent Door | Left | Right | have Key of Indolent |  |  |  |
| H | Indolent Door | Right | Left | have Key of Indolent |  |  |  |
| V | Cavern | Cavern | Left | ledge grab OR faydown OR clawline OR silk soar |  |  |  |

## Check Locations

No check locations defined.
