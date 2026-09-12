# Deep Docks Forge (Room_Forge)

**Game ID:** Room_Forge

**Contributors:** herounit

## Subrooms

- left area
- right area
- gauntlet
- forge daughter
- right exit platform

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | left area | [Deep Docks Lace Intro (Bone_East_12)](deep-docks-lace-intro.md) | F | none |  | Verified | activate airlock |
| L | left1 | left area | [Deep Docks Lower West Shaft (Dock_04)](deep-docks-lower-west-shaft.md) | UR | none |  | Verified |  |
| R | right1 | right exit platform | [Deep Docks Chains West (Dock_02)](deep-docks-chains-west.md) | UL | unlock deep docks simple key lock |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | left area | right area | activate gate switch |  | Verified |  |
| DS | door switch | right area | left area | activate gate switch |  | Verified |  |
| GL | gauntlet left | left area | gauntlet | none |  | Verified |  |
| GL | gauntlet left | gauntlet | left area | complete gauntlet fight |  | Verified |  |
| GR | gauntlet right | right area | gauntlet | none |  | Verified |  |
| GR | gauntlet right | gauntlet | right area | complete gauntlet fight |  | Verified |  |
| GC | gauntlet upper | forge daughter | gauntlet | open airlock down |  | Verified |  |
| GC | gauntlet upper | gauntlet | forge daughter | complete gauntlet fight AND ( open airlock up AND ( ledge grab OR faydown cloak OR clawline OR scuttlebrace OR easy shaman pogo ) ) |  | Verified |  |
| RJ | running jump | right area | right exit platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR easy beast pogo |  | Verified |  |
| RJ | running jump | right exit platform | right area | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR easy beast pogo |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache deep docks 10 | left area | none |  | Verified |  | break wall |
| shard bundle deep docks 2 | left area | none |  | Verified |  |  |
| silkshot (forge daughter) | forge daughter | have ruined tool |  | Verified |  |  |
| sting shard | forge daughter | none |  | Verified |  | forge daughter shop |
| magma bell | forge daughter | none |  | Verified |  | forge daughter shop |
| crafting kit forge daughter | forge daughter | none |  | Verified |  | forge daughter shop |
| readable lore tablet | left area | open airlock left |  | Verified |  |  |
| gate switch | forge daughter | none |  | Verified |  |  |
| gauntlet fight | gauntlet | none |  | Verified |  |  |
| deep docks simple key lock | right exit platform | have simple key deep docks |  | Verified |  |  |
