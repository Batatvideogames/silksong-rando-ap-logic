# Far Fields Fort Upper Passage (Bone_East_17)

**Game ID:** Bone_East_17

**Contributors:** herounit

## Subrooms

- left exit area
- right exit area
- main area
- check niche

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Far Fields Deep Docks Loopback (Bone_East_15)](far-fields-deep-docks-loopback.md) | R | none |  | Verified |  |
| B | bot1 | main area | [Far Fields Fort Flea Rescue (Bone_East_17b)](far-fields-fort-flea-rescue.md) | C | none |  | Verified |  |
| R | right1 | right exit area | [Far Fields Wind Shaft (Bone_East_07)](far-fields-wind-shaft.md) | L4 | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LP | lower platforms | left exit area | main area | activate lower platform switch |  | Verified |  |
| LP | lower platforms | main area | left exit area | activate lower platform switch |  | Verified |  |
| RJ | running jump | main area | right exit area | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  | Verified | silk soar doesn't get enough horizontal distance without one of the skills that just gets you there |
| RJ | running jump | right exit area | main area | none (falling) |  | Verified |  |
| AC | access niche | main area | check niche | ledge grab OR run OR dash OR silk soar OR drifter's cloak OR faydown cloak OR cling grip OR clawline OR sharpdart OR scuttlebrace OR easy beast pogo OR easy shaman pogo |  | Verified |  |
| AC | access niche | check niche | main area | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 14 | check niche | none |  | Verified | collectible |  |
| rosary cache far fields 15 | main area | none |  | Verified | collectible |  |
| lower platform switch | left exit area | flip switch up |  | Verified | switch |  |
| rosary chest | left exit area | none |  | Verified | collectible | NOT YET RANDOMIZED |
