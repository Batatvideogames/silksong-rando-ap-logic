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
| L | left1 | left entrance | [Hunter's March Shaft (Ant_14)](hunter-s-march-shaft.md) | LR | none |  |  |  |
| D | door1 | chapel entrance | [Chapel of the Beast (Ant_19)](chapel-of-the-beast.md) | L | no beast crest OR beast chapel door override |  |  | door override is meant to cover when the randomizer ensures the door stays open |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EP | evil pogo | left entrance | crossing platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace OR shaman crest OR wanderer crest OR OR beast crest OR reaper crest OR ( ledge grab AND ( witch crest OR hunter crest OR architect crest ) ) |  | Verified |  |
| EP | evil pogo | crossing platform | left entrance | none |  | Verified | can pogo the gap for free from this direction |
| WT | wind tunnel | crossing platform | chapel entrance | drifter's cloak OR  silk soar |  | Verified |  |
| WT | wind tunnel | chapel entrance | crossing platform | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| memory locket | crossing platform | none |  | Verified | Included | need to break a cage |
