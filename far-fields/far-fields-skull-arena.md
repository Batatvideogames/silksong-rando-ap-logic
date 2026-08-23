# Far Fields Skull Arena (Bone_East_LavaChallenge)

**Game ID:** Bone_East_LavaChallenge

**Contributors:** herounit

## Subrooms

- entrance
- arena
- crossing
- check alcove
- mask alcove

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | entrance | [Far Fields Skull Room East (Bone_East_14b)](far-fields-skull-room-east.md) | D | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ET | entrance tunnel | entrance | crossing | break blast rock down AND ( spike pogo OR drifter's cloak OR faydown cloak OR clawline OR dash OR scuttle brace ) |  | Verified |  |
| ET | entrance tunnel | crossing | entrance | ( cling grip OR scuttlebrace ) AND ( spike pogo OR dash OR clawline OR drifter's cloak OR faydown cloak  ) |  | Verified |  |
| CT | check tunnel | crossing | check alcove | break blast rock up AND ( scuttlebrace OR cling grip ) |  | Verified |  |
| CT | check tunnel | check alcove | crossing | none (falling) |  | Verified |  |
| AT | arena tunnel | crossing | arena | break blast rock down |  | Verified |  |
| LA | lava ascend | arena | mask alcove | cling grip AND AND drifter's cloak AND faydown cloak AND dash |  | Verified |  |
| MD | mask descend | mask alcove | entrance | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache far fields 8 | check alcove | none |  | Verified | Included | this becomes inaccessible after defeating the gauntlet - perhaps auto collect? |
| mask shard far fields skull cave | mask alcove | none |  | Verified | Included |  |

## Notes

modeled this area as:
entrance <-> crossing <-> check alcove <-> crossing -> arena -> mask alcove -> entrance 
the arena to mask shard connections are one-way so the full requirement chain is enforced
