# Hunter's March Deep Docks Passage (Ant_05b)

**Game ID:** Ant_05b

**Contributors:** herounit

## Subrooms

- before gate
- right of gauntlet
- gauntlet
- left of gauntlet

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | before gate | [Hunter's March Shaft (Ant_14)](hunter-s-march-shaft.md) | L4 | none |  | Verified |  |
| LF | bot1 | left of gauntlet | [Is this still Deep Docks? (West) (Bone_East_04b)](../deep-docks/is-this-still-deep-docks-west.md) | C | none |  | Verified |  |
| RF | bot2 | right of gauntlet | [Is this still Deep Docks? (East) (Bone_East_04)](../deep-docks/is-this-still-deep-docks-east.md) | C | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BG | bone gate | before gate | right of gauntlet | none (switch is on this side) |  | Verified |  |
| BG | bone gate | right of gauntlet | before gate | switched flipped |  | Verified |  |
| RG | right gauntlet | right of gauntlet | gauntlet | none (starts gauntlet) |  | Verified |  |
| RG | right gauntlet | gauntlet | right of gauntlet | defeat gauntlet |  | Verified |  |
| LG | left gauntlet | left of gauntlet | gauntlet | none (starts gauntlet) |  | Verified |  |
| LG | left gauntlet | gauntlet | left of gauntlet | defeat gauntlet |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bone switch | before gate | none |  | Verified | Not included |  |
| gauntlet fight | gauntlet | none |  | Verified | Not included |  |
