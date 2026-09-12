# Hunter's March Chapel Passage (Ant_20)

**Game ID:** Ant_20

**Contributors:** herounit

## Subrooms

- left entrance
- crossing platform
- chapel entrance

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left entrance | [Hunter's March Shaft (Ant_14)](hunter-s-march-shaft.md) | LR | none |  | Verified |  |
| D | door1 | chapel entrance | [Chapel of the Beast (Ant_19)](chapel-of-the-beast.md) | L | none (door forced open) |  | Verified | The randomizer will need to ensure this door stays open when this room is relevant |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EP | evil pogo | left entrance | crossing platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace OR easy shaman pogo OR easy wanderer pogo OR easy beast pogo OR easy reaper pogo OR ( ledge grab AND ( easy witch pogo OR easy hunter pogo OR easy architect pogo ) ) |  | Verified |  |
| EP | evil pogo | crossing platform | left entrance | none |  | Verified | can pogo the gap for free from this direction |
| WT | wind tunnel | crossing platform | chapel entrance | drifter's cloak OR silk soar |  | Verified |  |
| WT | wind tunnel | chapel entrance | crossing platform | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| memory locket | crossing platform | none |  | Verified | collectible | need to break a cage |
