# Bone Bottom Town (Bonetown)

**Game ID:** Bonetown

**Contributors:** herounit, Super EpicGuy

## Subrooms

- sky
- ground level
- upper right platforms
- upper middle platforms
- upper left platforms
- chapel roof

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper left platforms | [Bonegrave (Bonegrave)](bonegrave.md) | UR | none |  | Verified |  |
| LL | lower left | ground level | [Bonegrave (Bonegrave)](bonegrave.md) | LR | door opened from other side |  | Verified |  |
| DR | descend rope | ground level | [Ruined Chapel (Tut_03)](../moss-grotto/ruined-chapel.md) | AR | none |  | Verified |  |
| RF | right floor | ground level | [Moss Grotto Center (Tut_01)](../moss-grotto/moss-grotto-center.md) | C | none |  | Verified |  |
| BD | bellway door | ground level | [Bone Bottom Bellway (Bellway_01)](bone-bottom-bellway.md) | BD | none |  | Verified |  |
| LR | lower right | ground level | [The Marrow Entrance (Bone_01)](../the-marrow/the-marrow-entrance.md) | LL | none |  | Verified |  |
| UR | upper right | upper right platforms | [Mosshome Basement (Bone_01b)](mosshome-basement.md) | LL | none |  | Verified |  |
| T1 | top1 | sky | [The Big Fall (Aspid_01)](the-big-fall.md) | B1 | silk soar |  | Verified |  |
| T2 | right ceiling | upper right platforms | [The Big Fall (Aspid_01)](the-big-fall.md) | B2 | none |  | Verified |  |
| T3 | top3 | sky | [The Big Fall (Aspid_01)](the-big-fall.md) | B3 | silk soar |  | Verified |  |
| T4 | top4 | sky | [The Big Fall (Aspid_01)](the-big-fall.md) | B4 | silk soar |  | Verified |  |
| T5 | top5 | sky | [The Big Fall (Aspid_01)](the-big-fall.md) | B5 | silk soar |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CC | climb chapel | ground level | chapel roof | silk soar OR ( cling grip AND ( LL door NOT opened OR faydown cloak ) ) OR (scuttlebrace AND dash AND faydown cloak ) |  |  |  |
| SM | soar to middle platforms | ground level | upper middle platforms | silk soar |  |  |  |
| SS | soar to sky exit | ground level | sky | silk soar |  |  |  |
| SR | soar to right platforms | ground level | upper right platforms | silk soar |  |  |  |
| EV | elevator | ground level | upper right platforms | activate elevator switch |  | Verified |  |
| EV | elevator | upper right platforms | ground level | activate elevator switch |  | Verified |  |
| CC | climb chapel | chapel roof | ground level | none |  |  |  |
| CR | climb roof | chapel roof | upper left platforms | silk soar OR cling grip OR (scuttlebrace AND dash AND (((faydown cloak OR shaman OR flea brew)) AND easy skips) OR (hard skips AND (hunter OR reaper OR wanderer OR beast OR architect) OR (silk storm OR rune rage)) |  |  | You need a very precise heal or spell boost to scuttlebrace the wall without wings, which can be done by anything but witch crest |
| CR | climb roof | upper left platforms | chapel roof | none |  |  |  |
| MD | middle platform drift | upper middle platforms | chapel roof | drifter's cloak OR clawline OR sharpdart OR beast OR architect OR (shaman AND (ledge grab AND easy skips) OR hard skips) OR ((hunter OR nude) AND dash) OR (dash AND (scuttlebrace OR flea brew OR silkspeed anklets OR faydown cloak)) OR (run AND flea brew AND easy skips) |  |  | Beast and architect can just spam pogo |
| SM | soar to middle platforms | upper middle platforms | ground level | none |  |  |  |
| CL | clawline across the sky | upper middle platforms | upper right platforms | clawline OR (dash AND (sharpdart OR drifter's cloak)) OR (run AND sharpdart OR (easy skips OR faydown cloak) AND drifters cloak) |  |  |  |
| CL | clawline across the sky | upper right platforms | upper middle platforms | clawline OR (dash AND (sharpdart OR drifter's cloak)) OR (run AND sharpdart OR (easy skips OR faydown cloak) AND drifters cloak) |  |  |  |
| SR | soar to right platforms | upper right platforms | ground level | none |  |  |  |
| DL | sky drift to right platforms | sky | upper right platforms | drifter's cloak OR horizontal movement tech |  |  |  |
| DR | sky drift to middle platforms | sky | upper middle platforms | drifter's cloak OR horizontal movement tech |  |  |  |
| SS | soar to sky exit | sky | ground level | none |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bone bottom mossberry | upper right platforms | none |  |  | collectible |  |
| elevator switch | upper right platforms | none |  |  | switch |  |
| rosary cache bone bottom 8 | upper right platforms | none |  |  | collectible |  |
| rosary cache bone bottom 9 | upper right platforms | none |  |  | collectible |  |
| weaver effigy camora moss grotto | upper middle platforms | none |  |  | collectible |  |
| rosary dish bone bottom | upper middle platforms | none |  |  | collectible | NOT CURRENTLY RANDOMIZED |
| mask shard pebbs shop grindle act 3 | ground level |  |  |  | collectible | pebb's shop |
| simple key | ground level |  |  |  | collectible | pebb's shop |
| bone bottom shop craft metal | ground level |  |  |  | collectible | pebb's shop |
| magnetite broach | ground level |  |  |  | collectible | pebb's shop |
| shell shard cache bone bottom | ground level |  |  |  | collectible | is this breaking the statue? STILL MARKED AS ??? ON TRACKER |
| wish bone bottom repairs | ground level |  |  |  | event |  |
| wish a life saving bridge | ground level |  |  |  | event |  |
| wish an icon of hope | ground level |  |  |  | event |  |
| wish garb of the pilgrims | ground level |  |  |  | event |  |
| wish volatile flintbeetles | ground level |  |  |  | event |  |
| wish the terrible tyrant | ground level |  |  |  | event |  |
| wish bone bottom supplies | ground level |  |  |  | event |  |
| bone bottom skull tyrant boss fight | ground level |  |  |  | boss | can miss |
| reach bone bottom | ground level | none |  |  | logic-point | addresses the loading zone blocker in moss grotto center ceiling that only goes away once you've been up here - remove this/requirement in moss grotto center once this is removed in the randomizer |
