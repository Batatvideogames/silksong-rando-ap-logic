# Chapel of the Beast (Ant_19)

**Game ID:** Ant_19

**Contributors:** herounit

## Subrooms

- chapel entrance
- boss arena
- crest area
- right of boss fight

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | chapel entrance | [Hunter's March Chapel Passage (Ant_20)](hunter-s-march-chapel-passage.md) | D | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | chapel entrance | right of boss fight | drifter's cloak OR activate door switch |  | Verified |  |
| DS | door switch | right of boss fight | chapel entrance | activate door switch |  | Verified |  |
| BR | boss right entrance | right of boss fight | boss arena | none (starts boss fight) |  | Verified |  |
| BR | boss right entrance | boss arena | right of boss fight | defeat savage beastly boss fight |  | Verified |  |
| BL | boss left entrance | crest area | boss arena | defeat savage beastly boss fight |  | Verified |  |
| BL | boss left entrance | boss arena | crest area | defeat savage beastly boss fight |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| door switch | right of boss fight | flip switch down |  | Verified | switch |  |
| savage beastly boss fight | boss arena | none |  | Verified | boss |  |
| crest beast | crest area | none |  | Verified | collectible |  |
