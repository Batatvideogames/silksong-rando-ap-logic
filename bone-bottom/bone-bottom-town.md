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
| LL | lower left | ground level | [Bonegrave (Bonegrave)](bonegrave.md) | LR | clear vines holding door closed IN bonegrave |  | Verified |  |
| DR | descend rope | ground level | [Ruined Chapel (Tut_03)](../moss-grotto/ruined-chapel.md) | AR | none |  | Verified |  |
| RF | right floor | ground level | [Moss Grotto Center (Tut_01)](../moss-grotto/moss-grotto-center.md) | C | none |  | Verified |  |
| BD | bellway door | ground level | [Bone Bottom Bellway (Bellway_01)](bone-bottom-bellway.md) | BD | none |  | Verified |  |
| LR | lower right | ground level | [The Marrow Entrance (Bone_01)](../the-marrow/the-marrow-entrance.md) | LL | none |  | Verified |  |
| UR | upper right | upper right platforms | [Mosshome Basement Passage (Bone_01b)](mosshome-basement-passage.md) | LL | none |  | Verified |  |
| T1 | top1 | sky | [The Big Fall (Aspid_01)](the-big-fall.md) | B1 | silk soar |  | Verified |  |
| T2 | right ceiling | upper right platforms | [The Big Fall (Aspid_01)](the-big-fall.md) | B2 | ledge grab  OR scuttlebrace  OR cling grip  OR silk soar OR dash  OR easy shaman pogo |  | Verified | didn't want to make a tiny subroom to account for the ledge grab to get up here |
| T3 | top3 | sky | [The Big Fall (Aspid_01)](the-big-fall.md) | B3 | silk soar |  | Verified |  |
| T4 | top4 | sky | [The Big Fall (Aspid_01)](the-big-fall.md) | B4 | silk soar |  | Verified |  |
| T5 | top5 | sky | [The Big Fall (Aspid_01)](the-big-fall.md) | B5 | silk soar |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CC | climb chapel | ground level | chapel roof | silk soar  OR cling grip  OR ( scuttlebrace AND faydown cloak ) |  | Verified | cling grip only works by itself when the door has not been opened - this makes logic non-monotonic and needs a mod fix |
| SM | soar to middle platforms | ground level | upper middle platforms | silk soar |  | Verified |  |
| SS | soar to sky exit | ground level | sky | silk soar |  | Verified |  |
| SR | soar to right platforms | ground level | upper right platforms | silk soar |  | Verified |  |
| EV | elevator | ground level | upper right platforms | activate elevator switch |  | Verified |  |
| EV | elevator | upper right platforms | ground level | activate elevator switch |  | Verified |  |
| CC | climb chapel | chapel roof | ground level | none (falling) |  | Verified |  |
| CR | climb roof | chapel roof | upper left platforms | silk soar  OR cling grip  OR ( easy scuttlebrace AND faydown cloak ) OR ( hard scuttlebrace AND ( hard heal stall AND ( have crest hunter OR have crest reaper OR have crest wanderer OR have crest beast OR have crest architect ) ) ) OR ( hard scuttlebrace AND ( thread storm OR rune rage ) ) |  | Verified | You need a very precise heal or spell boost to scuttlebrace the wall without wings, which can be done by anything but witch crest |
| CR | climb roof | upper left platforms | chapel roof | none (falling) |  | Verified |  |
| MD | middle platform drift | upper middle platforms | chapel roof | drifters  OR clawline  OR sharpdart  OR easy beast pogo OR easy architect pogo OR ( hard shaman pogo )  OR ( ledge grab AND easy shaman pogo ) OR ( dash AND ( easy hunter pogo OR easy naked pogo ) )  OR ( dash AND ( scuttlebrace OR flea brew OR silkspeed anklets OR faydown cloak ) )  OR ( run AND flea brew ) |  | Verified | Beast and architect can just spam pogo |
| SM | soar to middle platforms | upper middle platforms | ground level | none (falling) |  | Verified |  |
| CL | clawline across the sky | upper middle platforms | upper right platforms | clawline  OR ( dash AND ( sharpdart OR drifters ) )  OR ( run AND sharpdart )  OR ( drifters AND ( faydown cloak OR easy proficient movement ) ) | TODO | Verified | This is how it is currently implemented in the apworld; need to verify with SEG as it was malformed prior to correction. - hero |
| CL | clawline across the sky | upper right platforms | upper middle platforms | clawline  OR ( dash AND ( sharpdart OR drifters ) )  OR ( run AND sharpdart )  OR ( drifters AND ( faydown cloak OR easy proficient movement ) ) |  | Verified | This is how it is currently implemented in the apworld; need to verify with SEG as it was malformed prior to correction. - hero |
| SR | soar to right platforms | upper right platforms | ground level | none (falling) |  | Verified |  |
| DL | sky drift to right platforms | sky | upper middle platforms | drifters  OR clawline OR faydown OR sharpdart OR dash OR easy beast pogo OR easy hunter pogo OR easy architect pogo |  | Verified |  |
| DR | sky drift to middle platforms | sky | upper right platforms | drifters  OR clawline OR faydown OR sharpdart OR dash OR easy beast pogo OR easy hunter pogo OR easy architect pogo |  | Verified |  |
| SS | soar to sky exit | sky | ground level | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bone bottom mossberry | upper right platforms | none |  | Verified | collectible |  |
| elevator switch | upper right platforms | flip switch up |  | Verified | switch |  |
| bone bottom rosary cache 8 | upper right platforms | none |  | Verified | collectible |  |
| bone bottom rosary cache 9 | upper right platforms | none |  | Verified | collectible |  |
| weaver effigy camora moss grotto | upper middle platforms | none |  | Verified | collectible |  |
| bone bottom rosary dish | upper middle platforms | none |  | Verified | collectible |  |
| mask shard pebbs shop grindle act 3 | ground level |  |  |  | collectible | pebb's shop |
| simple key | ground level |  |  |  | collectible | pebb's shop |
| bone bottom shop craft metal | ground level |  |  |  | collectible | pebb's shop |
| magnetite broach | ground level |  |  |  | collectible | pebb's shop |
| shell shard cache bone bottom | ground level |  |  |  | collectible | is this breaking the statue? STILL MARKED AS ??? ON TRACKER |
| bone bottom repairs wish promised | ground level |  |  |  | event |  |
| a life saving bridge wish promised | ground level |  |  |  | event |  |
| an icon of hope wish promised | ground level |  |  |  | event |  |
| garb of the pilgrims wish promised | ground level |  |  |  | event |  |
| volatile flintbeetles wish promised | ground level |  |  |  | event |  |
| the terrible tyrant wish promised | ground level |  |  |  | event |  |
| bone bottom supplies wish promised | ground level |  |  |  | event |  |
| bone bottom skull tyrant boss fight | ground level |  |  |  | boss | can miss |
| reach bone bottom | ground level | none |  | Verified | logic-point | addresses the loading zone blocker in moss grotto center ceiling that only goes away once you've been up here - remove this/requirement in moss grotto center once this is removed in the randomizer |
