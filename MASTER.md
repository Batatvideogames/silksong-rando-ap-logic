# Silksong Randomizer Logic

Compiled from the database-generated room notes.

## Moss Grotto

### Moss Grotto Center (Tut_01)

**Game ID:** Tut_01

**Contributors:** herounit, super epicguy

#### Subrooms

- rock bottom
- upper crossing
- center shaft
- side room
- lower crossing
- up and away
- beast alcove
- dead ledge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | rock bottom | [Moss Grotto West (Tut_02)](#moss-grotto-west-tut02) | LR | break vines left |  | Verified |  |
| ML | middle left | lower crossing | [Moss Grotto West (Tut_02)](#moss-grotto-west-tut02) | UR | none |  | Verified |  |
| UL | upper left | upper crossing | [Ruined Chapel (Tut_03)](#ruined-chapel-tut03) | R | break vines left |  | Verified |  |
| LR | lower right | lower crossing | [Moss Grotto East (Tut_01b)](#moss-grotto-east-tut01b) | LL | none |  | Verified |  |
| UR | upper right | upper crossing | [Moss Grotto East (Tut_01b)](#moss-grotto-east-tut01b) | UL | none |  | Verified |  |
| C | ceiling | up and away | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | RF | complete reach bone bottom IN bone bottom town |  | Verified | there is a loading zone blocker that only goes away once you've reached bone bottom once |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S1 | shaft 1 | upper crossing | up and away | silk soar  OR scuttlebrace  OR ( cling grip AND ( easy shaman crest pogo OR easy heal stall OR faydown cloak OR run OR dash OR sharpdart OR clawline ) ) |  | Verified | Easy skip is a heal boost or a reversed slash boost with Shaman's |
| S1 | shaft 1 | up and away | upper crossing | none (falling) |  | Verified |  |
| S2 | shaft 2 | center shaft | upper crossing | silk soar OR cling grip OR scuttlebrace |  | Verified |  |
| S2 | shaft 2 | upper crossing | center shaft | none (falling) |  | Verified |  |
| SV | side room vines | center shaft | side room | break vines left |  | Verified |  |
| SV | side room vines | side room | center shaft | break vines right |  | Verified |  |
| S3 | shaft 3 | lower crossing | center shaft | silk soar OR cling grip OR ( easy scuttlebrace AND dash AND ( sharpdart OR clawline OR faydown cloak ) ) |  | Verified |  |
| S3 | shaft 3 | center shaft | lower crossing | none (falling) |  | Verified |  |
| S4 | shaft 4 | dead ledge | lower crossing | ledge grab OR faydown cloak OR silk soar OR scuttlebrace OR ( cling grip AND ( dash OR clawline ) ) |  | Verified |  |
| S4 | shaft 4 | lower crossing | dead ledge | none (falling) |  | Verified |  |
| S5 | shaft 5 | rock bottom | dead ledge | silk soar OR ( cling grip AND faydown cloak )  OR ( easy scuttlebrace AND dash AND faydown cloak AND ( ( drifters cloak AND ledge grab ) OR clawline OR sharpdart ) ) |  | Verified |  |
| S5 | shaft 5 | dead ledge | rock bottom | none (falling) |  | Verified |  |
| LG | ledge grab 1 | rock bottom | beast alcove | ledge grab OR faydown cloak OR silk soar OR cling grip OR scuttlebrace |  | Verified |  |
| LG | ledge grab 1 | beast alcove | rock bottom | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| frayed rosary string moss grotto | dead ledge | none |  | Verified | collectible |  |
| shell shard cache moss grotto 1 | rock bottom | none |  | Verified | collectible |  |
| moss grotto beast shard | beast alcove | none |  | Verified | collectible |  |
| moss grotto rosary chest | side room | none |  | Verified | collectible |  |

#### Notes

renamed from "moss grotto west" - was mistakenly marked as same room as west room
not having the west part as part of this area causes the graph to be more complex

### Moss Grotto West (Tut_02)

**Game ID:** Tut_02

**Contributors:** herounit

#### Subrooms

- lower right exit area
- the pond
- the backroom floor
- the backroom cache
- upper level
- mossberry platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | upper right | upper level | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | ML | none |  | Verified | asdf |
| LR | lower right | lower right exit area | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | LL | break vines right |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LG1 | first ledge grab | lower right exit area | the pond | ledge grab OR cling grip OR scuttlebrace OR faydown cloak OR silk soar |  | Verified |  |
| LG1 | first ledge grab | the pond | lower right exit area | none (falling) |  | Verified |  |
| SW1 | first swim | the pond | the backroom floor | swim |  | Verified |  |
| SW1 | first swim | the backroom floor | the pond | swim |  | Verified |  |
| LG2 | ledge grab 2 | the backroom floor | the backroom cache | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| LG2 | ledge grab 2 | the backroom cache | the backroom floor | none (falling) |  | Verified |  |
| BW1 | breakable wall 1 | the backroom cache | the pond | clear one-way breakable wall |  | Verified |  |
| BW1 | breakable wall 1 | the pond | the backroom cache | clear one-way breakable wall |  | Verified |  |
| LG3 | ledge grab 3 | the pond | upper level | ledge grab OR run OR dash OR drifters OR faydown OR easy beast pogo OR cling grip OR silk soar OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| LG3 | ledge grab 3 | upper level | the pond | none (falling) |  | Verified |  |
| LG4 | ledge grab 4 | upper level | mossberry platform | ledge grab OR faydown OR cling grip OR silk soar |  | Verified |  |
| LG4 | ledge grab 4 | mossberry platform | upper level | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache moss grotto 5 | the backroom cache | none |  | Verified | collectible |  |
| shell shard cache moss grotto 6 | the backroom cache | none |  | Verified | collectible |  |
| shell shard cache moss grotto 7 | the backroom cache | none |  | Verified | collectible |  |
| moss grotto west mossberry | mossberry platform | none |  | Verified | collectible |  |
| one-way breakable wall | the backroom cache | break wall right |  | Verified | blockade |  |

#### Notes

somehow missed this being its own room before

### Moss Grotto East (Tut_01b)

**Game ID:** Tut_01b

**Contributors:** herounit

#### Subrooms

- ground floor
- weavenest door platform
- upper platforms
- alcove check spot

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper platforms | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | UR | none |  | Verified |  |
| LL | lower left | ground floor | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | LR | none |  | Verified |  |
| WD | weavenest door | weavenest door platform | [Weavenest Atla Entrance (Weave_04)](#weavenest-atla-entrance-weave04) | WD | needolin |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RG | right ledge grab | ground floor | alcove check spot | ledge grab OR cling grip OR scuttlebrace OR faydown |  | Verified |  |
| RG | right ledge grab | alcove check spot | ground floor | none (falling) |  | Verified |  |
| WD | weavenest door gap | ground floor | weavenest door platform | ledge grab OR run OR dash OR clawline OR drifters OR faydown OR cling grip OR ( spike pogo AND proficient movement ) OR easy shaman pogo OR easy beast pogo OR silk soar |  | Verified |  |
| WD | weavenest door gap | weavenest door platform | ground floor | none (falling) |  | Verified |  |
| UG | upper ledge grab | ground floor | upper platforms | ledge grab OR dash OR faydown OR cling grip OR silk soar OR easy shaman pogo |  | Verified |  |
| UG | upper ledge grab | upper platforms | ground floor | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache moss grotto 2 | ground floor | none |  | Verified | collectible |  |
| shell shard cache moss grotto 3 | alcove check spot | none |  | Verified | collectible |  |
| shell shard cache moss grotto 4 | alcove check spot | none |  | Verified | collectible |  |
| moss grotto east mossberry | upper platforms | easy enemy pogo OR run OR dash OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR easy beast pogo OR ( have crest shaman AND ( attack up OR attack right ) ) |  | Verified | collectible |  |

### Ruined Chapel (Tut_03)

**Game ID:** Tut_03

**Contributors:** herounit

#### Subrooms

- chapel
- boss arena
- bench passage
- bench spot

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | bench spot | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | UL | none |  | Verified |  |
| AR | ascend rope | chapel | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | DR | none |  | Verified |  |
| CD | chapel door | chapel | [Ruined Chapel Interior](#ruined-chapel-interior) | CD |  | TODO |  | how the heck do you open this door again? |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RB | right boss entrance | bench passage | boss arena | break vines left (starts fight) |  | Verified |  |
| RB | right boss entrance | boss arena | bench passage | complete moss mother boss fight |  | Verified |  |
| LB | left boss entrance | chapel | boss arena | none (starts fight) |  | Verified |  |
| LB | left boss entrance | boss arena | chapel | complete moss mother boss fight |  | Verified |  |
| V1 | ledge grab | bench spot | bench passage | ledge grab OR faydown OR silk soar OR cling grip |  | Verified |  |
| V1 | ledge grab | bench passage | bench spot | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| moss mother boss fight | boss arena | none |  | Verified | boss |  |
| bench | bench spot | none |  | Verified | bench |  |

#### Notes

ROOM BUG: fighting moss mother without breaking the vines on the right side of the arena (by approaching from the left), you get locked into the arena with darkness still covering the area.

Ascend rope AND the ceiling are valid exits - but I believe they take you to the same bot1 exit on the other side.

### Ruined Chapel Interior

**Contributors:** herounit

#### Subrooms

- ritual chamber
- crest chamber

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CD | chapel door | ritual chamber | [Ruined Chapel (Tut_03)](#ruined-chapel-tut03) | CD |  | TODO |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SS | silk soar spot | ritual chamber | crest chamber | silk soar |  | Verified |  |
| SS | silk soar spot | crest chamber | ritual chamber | silk soar |  | Verified |  |

#### Check Locations

No check locations defined.

#### Notes

**UNABLE TO ACCESS IN LOGIC AUDIT MODE**

## Bone Bottom

### Bone Bottom Town (Bonetown)

**Game ID:** Bonetown

**Contributors:** herounit, Super EpicGuy

#### Subrooms

- sky
- ground level
- upper right platforms
- upper middle platforms
- upper left platforms
- chapel roof

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper left platforms | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | UR | none |  | Verified |  |
| LL | lower left | ground level | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | LR | clear vines holding door closed IN bonegrave |  | Verified |  |
| DR | descend rope | ground level | [Ruined Chapel (Tut_03)](#ruined-chapel-tut03) | AR | none |  | Verified |  |
| RF | right floor | ground level | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | C | none |  | Verified |  |
| BD | bellway door | ground level | [Bone Bottom Bellway (Bellway_01)](#bone-bottom-bellway-bellway01) | BD | none |  | Verified |  |
| LR | lower right | ground level | [The Marrow Entrance (Bone_01)](#the-marrow-entrance-bone01) | LL | none |  | Verified |  |
| UR | upper right | upper right platforms | [Mosshome Basement Passage (Bone_01b)](#mosshome-basement-passage-bone01b) | LL | none |  | Verified |  |
| T1 | top1 | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | B1 | silk soar |  | Verified |  |
| T2 | right ceiling | upper right platforms | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | B2 | ledge grab  OR scuttlebrace  OR cling grip  OR silk soar OR dash  OR easy shaman pogo |  | Verified | didn't want to make a tiny subroom to account for the ledge grab to get up here |
| T3 | top3 | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | B3 | silk soar |  | Verified |  |
| T4 | top4 | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | B4 | silk soar |  | Verified |  |
| T5 | top5 | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | B5 | silk soar |  | Verified |  |
| WW | wish wall | ground level | [Bone Bottom Wish Wall](#bone-bottom-wish-wall) | BB | defeat THE bell beast boss fight |  | Verified |  |

#### Subroom Connections

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
| CL | clawline across the sky | upper middle platforms | upper right platforms | clawline  OR ( dash AND ( sharpdart OR drifters ) )  OR ( run AND sharpdart )  OR ( drifters AND ( faydown cloak OR proficient movement ) ) |  | Verified | This is how it is currently implemented in the apworld; need to verify with SEG as it was malformed prior to correction. - hero |
| CL | clawline across the sky | upper right platforms | upper middle platforms | clawline  OR ( dash AND ( sharpdart OR drifters ) )  OR ( run AND sharpdart )  OR ( drifters AND ( faydown cloak OR proficient movement ) ) |  | Verified | This is how it is currently implemented in the apworld; need to verify with SEG as it was malformed prior to correction. - hero |
| SR | soar to right platforms | upper right platforms | ground level | none (falling) |  | Verified |  |
| DL | sky drift to right platforms | sky | upper middle platforms | drifters  OR clawline OR faydown OR sharpdart OR dash OR easy beast pogo OR easy hunter pogo OR easy architect pogo |  | Verified |  |
| DR | sky drift to middle platforms | sky | upper right platforms | drifters  OR clawline OR faydown OR sharpdart OR dash OR easy beast pogo OR easy hunter pogo OR easy architect pogo |  | Verified |  |
| SS | soar to sky exit | sky | ground level | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bone bottom mossberry | upper right platforms | none |  | Verified | collectible |  |
| elevator switch | upper right platforms | flip switch up |  | Verified | switch |  |
| bone bottom rosary cache 8 | upper right platforms | none |  | Verified | collectible |  |
| bone bottom rosary cache 9 | upper right platforms | none |  | Verified | collectible |  |
| weaver effigy camora moss grotto | upper middle platforms | none |  | Verified | collectible |  |
| bone bottom rosary dish | upper middle platforms | none |  | Verified | collectible |  |
| magnetite broach | ground level | ( act 1 OR act 2 ) AND rosaries 120 |  | Verified | collectible | pebb's shop |
| mask shard pebbs shop grindle act 3 | ground level | ( act 1 OR act 2 ) AND rosaries 300 |  | Verified | collectible | pebb's shop |
| bone bottom shop craft metal | ground level | ( act 1 OR act 2 ) AND rosaries 60 |  | Verified | collectible | pebb's shop |
| simple key | ground level | ( act 1 OR act 2 ) AND rosaries 500 |  | Verified | collectible | pebb's shop |
| shell shard cache bone bottom | ground level | complete THE an icon of hope wish granted |  | Verified | collectible |  |
| skull tyrant bone bottom boss fight | ground level | complete THE the terrible tyrant wish granted AND ( visit blasted steps  OR visit the citadel  OR visit sinners road ) |  | Verified | boss | may be other hidden requirements. wiki says 30% chance of spawn after reaching key areas and using a bench in the zone. |
| reach bone bottom | ground level | none |  | Verified | logic-point | addresses the loading zone blocker in moss grotto center ceiling that only goes away once you've been up here - remove this/requirement in moss grotto center if/when this is removed in the randomizer |

### Bone Bottom Bellway (Bellway_01)

**Game ID:** Bellway_01

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BD | bellway door |  | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | BD | none |  | Verified |  |
| BB | bell beast |  | [Bellway Menu](#bellway-menu) | BB | unlock bellway bone bottom |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bellway bone bottom |  | defeat THE bell beast boss fight |  | Verified | travel |  |

### Bonegrave (Bonegrave)

**Game ID:** Bonegrave

**Contributors:** herounit, super epicguy

#### Subrooms

- upper left exit
- upper right exit
- graveyard
- door platform
- middle right platform
- mossberry platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | upper right | upper right exit | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | UL | none |  | Verified |  |
| LR | lower right | door platform | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | LL | none |  | Verified |  |
| C | ceiling | upper left exit | [Wormways Lower East (Crawl_07)](#wormways-lower-east-crawl07) | F | silk soar OR cling grip OR faydown cloak OR scuttlebrace |  | Verified |  |
| CD | chapel door | graveyard | [Chapel of the Wanderer (Chapel_Wanderer)](#chapel-of-the-wanderer-chapelwanderer) | CD | none |  | Verified | "wanderer's door override" is meant to cover any situation that would require the door to stay open, such as rosary cache rando |
| LL | lower left | graveyard | [Bonegrave Passage (Bone_Steel_Servant)](#bonegrave-passage-bonesteelservant) | R | complete THE a vassal lost wish promised AND visit resting sites 3 |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RV1 | right vertical 1 | middle right platform | upper right exit | silk soar OR cling grip OR scuttlebrace |  | Verified |  |
| RV1 | right vertical 1 | upper right exit | middle right platform | none (falling) |  | Verified |  |
| RV2 | right vertical 2 | door platform | middle right platform | silk soar |  | Verified |  |
| RV2 | right vertical 2 | middle right platform | door platform | none (falling) |  | Verified |  |
| BW | breakable wall | upper left exit | upper right exit | clear wormways access breakable wall |  | Verified |  |
| BW | breakable wall | upper right exit | upper left exit | clear wormways access breakable wall |  | Verified |  |
| PG | pond gap | door platform | graveyard | swim OR run OR clawline OR drifters OR silk soar OR sharpdart OR ( faydown AND ( ledge grab OR easy beast pogo OR easy hunter pogo OR easy reaper pogo OR easy architect pogo OR easy shaman pogo ) ) |  | Verified | A wide variety of stalls are likely to work with faydown here |
| PG | pond gap | graveyard | door platform | silk soar  OR clawline  OR sharpdart OR ( ( ledge grab OR cling grip ) AND run AND dash ) OR ( faydown cloak AND ( run OR dash ) ) OR ( swim AND ( ledge grab OR cling grip OR faydown cloak ) ) |  | Verified | A wide variety of stalls are likely to work here as well with ledge grab or faydown |
| MF | middle vertical 1 | door platform | mossberry platform | silk soar |  | Verified |  |
| MF | middle vertical 1 | mossberry platform | door platform | none (falling) |  | Verified |  |
| G2M | graveyard to mossberry | graveyard | mossberry platform | silk soar OR ledge grab OR cling grip OR faydown cloak |  | Verified |  |
| G2M | graveyard to mossberry | mossberry platform | graveyard | none (falling) |  | Verified |  |
| M2M | mossberry to middle | mossberry platform | middle right platform | faydown  OR clawline OR ( ( ledge grab OR cling grip ) AND ( dash OR easy scuttlebrace OR easy beast pogo OR easy architect pogo OR easy hunter pogo OR sharpdart OR drifters ) ) |  | Verified |  |
| M2M | mossberry to middle | middle right platform | mossberry platform | clawline OR ( run AND dash AND ( sharpdart OR ( ledge grab AND faydown ) ) ) |  | Verified |  |
| USF | upper stall fall | upper right exit | mossberry platform | sharpdart  OR clawline  OR drifters  OR ( run AND dash ) OR ( faydown AND ( run OR dash ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| boneyard mossberry | mossberry platform | none |  | Verified | collectible |  |
| rosary cache bone bottom 6 | upper right exit | none |  | Verified | collectible |  |
| rosary cache bone bottom 7 | upper right exit | none |  | Verified | collectible |  |
| rosaries on grave | graveyard | none |  | Verified | collectible | NOT RANDOMIZED AS OF v0.4.5 |
| wormways access breakable wall | upper left exit | break wall right |  | Verified | blockade |  |
| vines holding door closed | door platform | break vines right |  | Verified | blockade |  |

### Bonegrave Passage (Bone_Steel_Servant)

**Game ID:** Bone_Steel_Servant

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | LL | steel soul on |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| summoned savior boss fight |  | complete THE a vassal lost wish promised AND visit resting sites 3 |  | Verified | boss |  |

### Chapel of the Wanderer (Chapel_Wanderer)

**Game ID:** Chapel_Wanderer

**Contributors:** herounit

#### Subrooms

- door platform
- upper right
- middle right
- gauntlet arena
- lower left shaft 1
- lower left shaft 2
- crest room
- upper left

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CD | chapel door | door platform | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | CD | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| R1 | right 1 | door platform | upper right | none (falling) |  | Verified |  |
| R1 | right 1 | upper right | door platform | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| R2 | right 2 | upper right | middle right | none (falling) |  | Verified |  |
| R2 | right 2 | middle right | upper right | silk soar OR cling grip |  | Verified |  |
| GR | gauntlet right | middle right | gauntlet arena | none (starts gauntlet) |  | Verified |  |
| GR | gauntlet right | gauntlet arena | middle right | clear gauntlet fight |  | Verified |  |
| GL | gauntlet left | gauntlet arena | lower left shaft 2 | clear gauntlet fight |  | Verified |  |
| GL | gauntlet left | lower left shaft 2 | gauntlet arena | none (starts gauntlet) |  | Verified | need to verify this with noclip, but probably doesn't matter |
| L1 | left 1 | door platform | upper left | none (falling) |  | Verified |  |
| L1 | left 1 | upper left | door platform | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| BW | break wall | lower left shaft 1 | upper left | clear one way wall |  | Verified |  |
| BW | break wall | upper left | lower left shaft 1 | clear one way wall |  | Verified |  |
| L2 | left 2 | lower left shaft 1 | lower left shaft 2 | none (falling) |  | Verified |  |
| L2 | left 2 | lower left shaft 2 | lower left shaft 1 | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| L3 | left 3 | lower left shaft 2 | crest room | none (falling) |  | Verified |  |
| L3 | left 3 | crest room | lower left shaft 2 | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| wanderer's crest | crest room | none |  | Verified | collectible |  |
| One Way Wall | lower left shaft 1 | break wall up OR break wall right |  | Verified | blockade |  |
| gauntlet fight | gauntlet arena | none |  | Verified | gauntlet |  |
| rosary cache bongrave 1 | upper left | none |  | Verified | collectible |  |
| rosary cache bongrave 2 | upper left | none |  | Verified | collectible |  |
| rosary cache bongrave 3 | upper right | none |  | Verified | collectible |  |
| rosary cache bongrave 4 | upper right | none |  | Verified | collectible |  |

#### Notes

need see if there are other checks in here

### The Big Fall (Aspid_01)

**Game ID:** Aspid_01

**Contributors:** herounit, Super EpicGuy

#### Subrooms

- top area
- upper right ledge
- upper left ledge
- wish ledge
- middle right ledge
- lower left area
- lower right area
- bottom gap area
- upper silk soar only zone
- lower silk soar only zone
- bottom left area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T1 | top1 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B1 | silk soar |  | Verified | if lace starts her cutscene on you she cancels your silk soar and you fall back down without clearing the cutscene |
| T2 | top2 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B2 | silk soar |  | Verified |  |
| T3 | top3 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B3 | silk soar |  | Verified |  |
| T4 | top4 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B4 | silk soar |  | Verified |  |
| T5 | top5 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B5 | silk soar |  | Verified |  |
| T6 | top6 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B6 | silk soar |  | Verified |  |
| T7 | top7 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B7 | silk soar |  | Verified |  |
| UR | upper right | upper right ledge | [Shellwood Lower Toll bench (Shellwood_08c)](#shellwood-lower-toll-bench-shellwood08c) | L | none |  | Verified |  |
| MR | middle right | middle right ledge | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | L | clear left exit breakable wall IN mosshome upper |  | Verified |  |
| LR | lower right | lower right area | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | L | none |  | Verified |  |
| UL | upper left | upper left ledge | [Wormways Upper East (Crawl_01)](#wormways-upper-east-crawl01) | R | none |  | Verified |  |
| LL | lower left | lower left area | [Wormways Craggler Hallway (Crawl_04)](#wormways-craggler-hallway-crawl04) | R | none |  | Verified |  |
| B1 | bot1 | bottom gap area | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | T1 | none |  | Verified |  |
| B2 | bot2 | lower right area | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | T2 | none |  | Verified |  |
| B3 | bot3 | bottom gap area | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | T3 | none |  | Verified |  |
| B4 | bot4 | bottom gap area | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | T4 | none |  | Verified |  |
| B5 | bot5 | bottom gap area | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | T5 | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| F1 | top fall | top area | upper right ledge | none (falling) |  | Verified |  |
| F2 | upper right ledge fall | upper right ledge | upper left ledge | none (falling) |  | Verified |  |
| F3 | upper left ledge fall | upper left ledge | wish ledge | none (falling) |  | Verified |  |
| F4 | wish ledge fall | wish ledge | upper silk soar only zone | none (falling) |  | Verified |  |
| F5 | upper silk soar zone fall | upper silk soar only zone | middle right ledge | none (falling) |  | Verified |  |
| F6 | middle right ledge fall | middle right ledge | lower silk soar only zone | none (falling) |  | Verified |  |
| F7 | lower silk soar zone fall | lower silk soar only zone | bottom gap area | none (falling) |  | Verified |  |
| F8 | lower left area fall | bottom left area | bottom gap area | none (falling) |  | Verified |  |
| F9 | lower right area fall | lower right area | bottom gap area | none (falling) |  | Verified |  |
| S1 | bottom silk soar | bottom gap area | lower silk soar only zone | silk soar |  | Verified |  |
| S2 | lower zone silk soar | lower silk soar only zone | upper silk soar only zone | silk soar |  | Verified |  |
| S3 | upper zone silk soar | upper silk soar only zone | top area | silk soar |  | Verified |  |
| UC | upper crossing | upper left ledge | upper right ledge | silk soar  OR cling grip  OR faydown cloak  OR ( ledge grab AND ( dash OR clawline OR medium scuttlebrace ) ) OR ( ( medium enemy pogo OR ledge grab ) AND ( run OR sharpdart OR easy beast pogo ) )  OR ( easy enemy pogo AND ( clawline OR dash OR medium shaman pogo ) ) |  | Verified |  |
| UC | upper crossing | upper right ledge | upper left ledge | none (parkour) |  | Verified |  |
| WC | wish climb | wish ledge | upper left ledge | silk soar  OR cling grip OR ( ledge grab AND scuttlebrace ) |  | Verified |  |
| LW | lower to wish climb | lower right area | wish ledge | silk soar  OR ( hard enemy pogo AND ( spike pogo AND proficient movement ) AND ( ( run AND ledge grab ) OR dash ) AND cling grip AND faydown cloak AND drifters cloak AND clawline ) |  | Verified | Super EpicGuy has a clip of doing this skip from the lower right exit to the wish ledge. Insane. |
| LM | lower to middle climb | lower right area | middle right ledge | silk soar  OR ( proficient movement AND hard enemy pogo AND spike pogo AND ( hard cocoon skip OR hard flintslate  stall OR hard flea brew stall OR hard plasmium stall ) AND cling grip AND drifters )  OR ( proficient movement AND medium enemy pogo AND spike pogo AND cling grip AND faydown cloak ) |  | Verified |  |
| LC | lower crossing | lower left area | lower right area | silk soar OR faydown OR medium scuttlebrace (due to risk of falling) OR ( ( ledge grab OR cling grip ) AND ( easy enemy pogo OR run OR dash OR clawline OR sharpdart x 2 OR drifters ) ) |  | Verified |  |
| LC | lower crossing | lower right area | lower left area | silk soar OR faydown OR medium scuttlebrace (due to risk of falling) OR easy enemy pogo OR run  OR dash  OR clawline  OR sharpdart x 1 OR drifters |  | Verified |  |
| BLL | bottom to lower left | bottom left area | lower left area | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| BLL | bottom to lower left | lower left area | bottom left area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| moss grotto rosary cache | bottom left area | none |  | Verified | collectible |  |
| relic choral commandment moss grotto | middle right ledge | none |  | Verified | collectible |  |
| my missing courier wish granted | wish ledge | complete my missing courier wish promised IN belltown |  | Verified | event |  |

### Mosshome Side Room (Bone_05b)

**Game ID:** Bone_05b

**Contributors:** herounit

#### Subrooms

- ground floor
- upper platforms

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | ground floor | [Mosshome Middle (Mosstown_01)](#mosshome-middle-mosstown01) | UR | none |  | Verified |  |
| C | ceiling | upper platforms | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | RF | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LG | ledge grab 1 | ground floor | upper platforms | ledge grab OR cling grip  OR faydown cloak OR scuttlebrace OR silk soar |  | Verified |  |
| LG | ledge grab 1 | upper platforms | ground floor | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| mosshome mossberry | ground floor | none |  | Verified | collectible |  |

### Mosshome Druid (Mosstown_02c)

**Game ID:** Mosstown_02c

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | R | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| berry picking wish start |  | none |  | Verified | event |  |
| berry picking wish goal |  | mossberries 3 |  | Verified | event |  |
| druid's eye |  | complete berry picking wish goal |  | Verified | collectible | TRACKER POSITION WRONG AS OF v0.4.5 |
| druid's eyes |  | mossberries 7 |  | Verified | collectible | TRACKER POSITION WRONG AS OF v0.4.5 |
| bench |  | none |  | Verified | bench |  |

### Mosshome Upper (Mosstown_02)

**Game ID:** Mosstown_02

**Contributors:** herounit, super epicguy

#### Subrooms

- center platforms
- ground right
- ground left
- spire platforms
- silkspear passage

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LF | left floor | ground left | [Mosshome Middle (Mosstown_01)](#mosshome-middle-mosstown01) | C | none |  | Verified |  |
| L | left | ground left | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | MR | clear left exit breakable wall |  | Verified |  |
| RF | right floor | ground right | [Mosshome Side Room (Bone_05b)](#mosshome-side-room-bone05b) | C | none |  | Verified |  |
| R | right | ground right | [Mosshome Druid (Mosstown_02c)](#mosshome-druid-mosstown02c) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RS | right silk blockade | center platforms | ground right | break silk blockade |  | Verified |  |
| RS | right silk blockade | ground right | center platforms | break silk blockade |  | Verified |  |
| GL | left ground crossing | ground left | center platforms | ledge grab OR spike pogo OR run OR dash OR faydown OR drifters OR clawline OR sharpdart OR easy beast pogo OR easy architect charge |  | Verified | platform above spikes make this way more complicated than it should |
| GL | left ground crossing | center platforms | ground left | ledge grab OR spike pogo OR run OR dash OR faydown OR drifters OR clawline OR sharpdart OR easy beast pogo OR easy architect charge |  | Verified |  |
| LS | left silk blockade | spire platforms | silkspear passage | break silk blockade |  | Verified |  |
| LS | left silk blockade | silkspear passage | spire platforms | break silk blockade |  | Verified |  |
| RB | rope barrier | silkspear passage | ground left | clear rope platform blockade |  | Verified |  |
| RB | rope barrier | ground left | silkspear passage | clear rope platform blockade AND ( ledge grab OR cling grip OR faydown OR silk soar OR easy shaman pogo ) |  | Verified |  |
| V1 | vertical 1 | center platforms | spire platforms | ledge grab OR cling grip OR faydown OR silk soar OR easy shaman pogo |  | Verified |  |
| V1 | vertical 1 | spire platforms | center platforms | none |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| mosshome moss plaque | center platforms | none |  | Verified | lore |  |
| silkspear | spire platforms | none |  | Verified | collectible |  |
| mosshome rosary cache 3 | spire platforms | none |  | Verified | collectible |  |
| mosshome rosary cache 4 | spire platforms | none |  | Verified | collectible |  |
| frayed rosary string bone bottom silkspear passage | silkspear passage | none |  | Verified | collectible |  |
| rope platform blockade | silkspear passage | cut rope down OR cut rope left OR cut rope right OR cut rope up |  | Verified | blockade |  |
| left exit breakable wall | ground left | break wall left |  | Verified | blockade |  |

#### Notes

known silk blockade breakers = silk spear, sharpdart, rune rage, weaver silkshot, pimpillo, and needle strikes from hunter, reaper, beast, and shaman

### Mosshome Middle (Mosstown_01)

**Game ID:** Mosstown_01

**Contributors:** herounit

#### Subrooms

- ground floor
- middle left area
- upper left area
- upper right area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | ground floor | [The Marrow Bellway (Bone_05)](#the-marrow-bellway-bone05) | L | none |  | Verified |  |
| UR | upper right | upper right area | [Mosshome Side Room (Bone_05b)](#mosshome-side-room-bone05b) | L | none |  | Verified |  |
| F | floor | ground floor | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | C | activate floor exit switch |  | Verified |  |
| C | ceiling | upper left area | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | LF | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RJ | running jump | middle left area | upper right area | faydown cloak  OR ( ( ledge grab OR cling grip ) AND ( run OR sharpdart OR clawline ) ) |  | Verified |  |
| RJ | running jump | upper right area | middle left area | run  OR dash OR clawline OR faydown OR drifters OR sharpdart OR easy beast pogo OR scuttlebrace |  | Verified |  |
| V1 | vertical 1 | ground floor | upper right area | silk soar |  | Verified |  |
| V1 | vertical 1 | upper right area | ground floor | none (falling) |  | Verified |  |
| LG1 | ledge grab 1 | ground floor | middle left area | ledge grab  OR cling grip  OR faydown OR silk soar OR easy shaman pogo |  | Verified |  |
| LG1 | ledge grab 1 | middle left area | ground floor | none (falling) |  | Verified |  |
| LG2 | ledge grab 2 | middle left area | upper left area | ledge grab  OR cling grip  OR faydown OR silk soar OR easy shaman pogo |  | Verified |  |
| LG2 | ledge grab 2 | upper left area | middle left area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| floor exit switch | middle left area | flip switch down |  | Verified | blockade |  |
| rosary cache mosshome 1 | upper left area | none |  | Verified | collectible |  |
| rosary cache mosshome 2 | upper left area | none |  | Verified | collectible |  |

### Mosshome Lower (Bone_11)

**Game ID:** Bone_11

**Contributors:** herounit

#### Subrooms

- upper left exit
- upper right level
- rosary alcove
- lower right exit
- ground floor

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | lower right exit | [The Marrow Map Shop (Bone_04)](#the-marrow-map-shop-bone04) | LL | none |  | Verified |  |
| UR | upper right | upper right level | [The Marrow Map Shop (Bone_04)](#the-marrow-map-shop-bone04) | UL | none |  | Verified |  |
| L | left | upper left exit | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | LR | none |  | Verified |  |
| C | ceiling | upper left exit | [Mosshome Middle (Mosstown_01)](#mosshome-middle-mosstown01) | F | activate floor exit switch IN mosshome middle |  | Verified |  |
| F | floor | ground floor | [Mosshome Basement (Bone_11b)](#mosshome-basement-bone11b) | C | activate pressure plate IN mosshome basement |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RJ | running jump | upper right level | upper left exit | run  OR ( dash AND ( ledge grab OR cling grip ) ) OR faydown  OR silk soar  OR clawline  OR sharpdart  OR easy beast pogo  OR easy enemy pogo |  | Verified |  |
| RJ | running jump | upper left exit | upper right level | none (falling) |  | Verified |  |
| LG1 | ledge grab 1 | ground floor | rosary alcove | ledge grab  OR faydown cloak OR silk soar OR cling grip OR scuttlebrace OR easy shaman pogo |  | Verified |  |
| LG1 | ledge grab 1 | rosary alcove | ground floor | none (falling) |  | Verified |  |
| LG2 | ledge grab 2 | ground floor | upper right level | ledge grab  OR faydown cloak OR silk soar OR cling grip |  | Verified |  |
| LG2 | ledge grab 2 | upper right level | ground floor | none (falling) |  | Verified |  |
| LG3 | ledge grab 3 | ground floor | lower right exit | ledge grab  OR faydown cloak OR silk soar OR cling grip |  | Verified |  |
| LG3 | ledge grab 3 | lower right exit | ground floor | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache bone bottom 4 | rosary alcove | none |  | Verified | collectible |  |
| rosary cache bone bottom 5 | rosary alcove | none |  | Verified | collectible |  |

### Mosshome Basement (Bone_11b)

**Game ID:** Bone_11b

**Contributors:** herounit

#### Subrooms

- upper level
- lower level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | upper level | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | F | activate pressure plate |  | Verified |  |
| R | right | lower level | [Mosshome Basement Passage (Bone_01b)](#mosshome-basement-passage-bone01b) | UL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | lower level | upper level | ledge grab OR cling grip OR faydown OR silk soar OR easy shaman pogo |  | Verified |  |
| V1 | vertical 1 | upper level | lower level | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bone bottom spool fragment | lower level | none |  | Verified | collectible |  |
| pressure plate | lower level | none (stand on it) |  | Verified | switch |  |

### Mosshome Basement Passage (Bone_01b)

**Game ID:** Bone_01b

**Contributors:** herounit

#### Subrooms

- upper level
- lower level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper level | [Mosshome Basement (Bone_11b)](#mosshome-basement-bone11b) | R | break wall left |  | Verified |  |
| LL | lower left | lower level | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | UR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LU | lower to upper | lower level | upper level | ledge grab OR cling grip OR faydown OR silk soar OR easy shaman pogo |  | Verified |  |
| LU | lower to upper | upper level | lower level | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| the marrow mosslands passage rosary cache 1 | upper level | none |  | Verified | collectible |  |
| the marrow mosslands passage rosary cache 2 | upper level | none |  | Verified | collectible |  |
| the marrow mosshome basement rosary dish | upper level | none |  | Verified | collectible |  |

## The Marrow

### The Marrow Entrance (Bone_01)

**Game ID:** Bone_01

**Contributors:** herounit

#### Subrooms

- ceiling exit
- gauntlet arena
- passage left
- passage right
- middle left
- above gauntlet
- left of gauntlet

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | passage left | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | LR | none |  | Verified |  |
| LR | lower right | passage right | [The Marrow Bell Bench (Bone_01c)](#the-marrow-bell-bench-bone01c) | LL | none |  | Verified |  |
| UR | upper right | above gauntlet | [The Marrow Bell Bench (Bone_01c)](#the-marrow-bell-bench-bone01c) | UL | break wall right |  | Verified |  |
| C | ceiling | ceiling exit | [The Marrow Map Shop (Bone_04)](#the-marrow-map-shop-bone04) | F | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | passage left | passage right | activate sherma door switch |  | Verified |  |
| DS | door switch | passage right | passage left | activate sherma door switch |  | Verified |  |
| UG | upper gauntlet entrance | above gauntlet | gauntlet arena | none (starts gauntlet) |  | Verified |  |
| UG | upper gauntlet entrance | gauntlet arena | above gauntlet | defeat gauntlet fight AND ( silk soar  OR cling grip OR scuttlebrace ) |  | Verified |  |
| SG | side gauntlet entrance | left of gauntlet | gauntlet arena | defeat gauntlet fight |  | Verified |  |
| SG | side gauntlet entrance | gauntlet arena | left of gauntlet | defeat gauntlet fight |  | Verified |  |
| LG | lower gauntlet entrance | gauntlet arena | passage right | defeat gauntlet fight |  | Verified |  |
| LG | lower gauntlet entrance | passage right | gauntlet arena | defeat gauntlet fight AND ( ledge grab OR faydown OR cling grip OR silk soar ) |  | Verified |  |
| LP | lowered platform | above gauntlet | ceiling exit | silk soar  OR ( faydown cloak AND ( run OR ledge grab OR cling grip ) ) OR ( run AND ( clawline OR sharpdart ) AND ( ledge grab OR cling grip ) ) OR ( activate lower platform switch other room IN the marrow map shop AND ( ledge grab OR cling grip OR faydown ) ) |  | Verified | The platform lowering switch has the possibility of making this non-monotonic because it *seems* to require ledge grab to hop over the lowered platform. Probably not really an issue. |
| LP | lowered platform | ceiling exit | above gauntlet | none (falling) |  | Verified |  |
| LG1 | ledge grab 1 | passage left | middle left | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| LG1 | ledge grab 1 | middle left | passage left | none (falling) |  | Verified |  |
| LG2 | ledge grab 2 | left of gauntlet | middle left | ledge grab OR cling grip OR faydown cloak OR silk soar OR scuttlebrace |  | Verified |  |
| LG2 | ledge grab 2 | middle left | left of gauntlet | none (falling) |  | Verified |  |
| LG3 | ledge grab 3 | middle left | above gauntlet | ledge grab OR cling grip OR faydown cloak OR silk soar OR scuttlebrace |  | Verified |  |
| LG3 | ledge grab 3 | above gauntlet | middle left | none (falling) |  | Verified |  |
| V1 | vertical 1 | passage left | left of gauntlet | silk soar |  | Verified |  |
| V1 | vertical 1 | left of gauntlet | passage left | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| the marrow shell shard cache 1 | above gauntlet | none |  | Verified | collectible |  |
| volatile flintbeetle 1 | above gauntlet | complete THE volatile flintbeetles wish promised |  | Verified | miniboss | stable position |
| gauntlet fight | gauntlet arena | none |  | Verified | gauntlet |  |
| sherma door switch | passage right | flip switch up |  | Verified | switch |  |
| the marrow rosary cache 1 | passage right | none |  | Verified | collectible |  |
| the marrow rosary cache 2 | passage right | none |  | Verified | collectible |  |

### The Marrow Bell Bench (Bone_01c)

**Game ID:** Bone_01c

**Contributors:** herounit

#### Subrooms

- falling rocks
- bell bench

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | falling rocks | [The Marrow Entrance (Bone_01)](#the-marrow-entrance-bone01) | UR | none |  | Verified |  |
| LL | lower left | bell bench | [The Marrow Entrance (Bone_01)](#the-marrow-entrance-bone01) | LR | none |  | Verified |  |
| R | right | bell bench | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | L | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| the marrow rosary cache 5 | falling rocks | none |  | Verified | collectible |  |
| the marrow rosary cache 6 | falling rocks | none |  | Verified | collectible |  |
| the marrow rosary cache 3 | bell bench | none |  | Verified | collectible |  |
| the marrow rosary cache 4 | bell bench | none |  | Verified | collectible |  |
| bench rosary lock | bell bench | rosaries 30 |  | Verified | lock |  |
| bench | bell bench | unlock bench rosary lock |  | Verified | bench |  |
| lore plaque | bell bench | none |  | Verified | lore |  |

#### Notes

While falling rocks and the bell bench are the same in-game room, there is no connection between them. So no subroom connections here is to be expected.

### The Marrow Lava Intro (Bone_02)

**Game ID:** Bone_02

**Contributors:** herounit

#### Subrooms

- ground left
- ground right
- flea sign platform
- chain break spot
- upper left exit
- left platforms

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | ground left | [The Marrow Bell Bench (Bone_01c)](#the-marrow-bell-bench-bone01c) | R | none |  | Verified |  |
| R | right | ground right | [The Marrow Lava Track (Bone_16)](#the-marrow-lava-track-bone16) | L | none |  | Verified |  |
| LC | left ceiling | upper left exit | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | F | none |  | Verified |  |
| RC | right ceiling | flea sign platform | [The Marrow Flea Caravan (Bone_10)](#the-marrow-flea-caravan-bone10) | F | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LG | lava gap | ground left | ground right | none (jump) |  | Verified |  |
| LG | lava gap | ground right | ground left | ledge grab OR run OR dash OR drifters OR faydown OR cling grip OR scuttlebrace OR silk soar OR clawline OR sharpdart OR easy shaman pogo OR easy beast pogo |  | Verified |  |
| V1 | vertical 1 | ground right | flea sign platform | ledge grab OR faydown OR silk soar OR cling grip OR easy shaman pogo |  | Verified |  |
| V1 | vertical 1 | flea sign platform | ground right | none (falling) |  | Verified |  |
| V2 | vertical 2 | ground right | chain break spot | ledge grab OR faydown OR silk soar OR cling grip OR easy shaman pogo |  | Verified |  |
| V2 | vertical 2 | chain break spot | ground right | none (falling) |  | Verified |  |
| V3 | vertical 3 | ground left | left platforms | silk soar OR faydown OR ( after chain drop platform AND ( ledge grab OR cling grip ) ) |  | Verified |  |
| V3 | vertical 3 | left platforms | ground left | none (falling) |  | Verified |  |
| V4 | vertical 4 | left platforms | upper left exit | silk soar OR ledge grab OR cling grip OR faydown OR easy shaman pogo |  | Verified |  |
| V4 | vertical 4 | upper left exit | left platforms | none (falling) |  | Verified |  |
| G1 | gap 1 | left platforms | chain break spot | clawline OR sharpdart OR faydown OR ( run AND ( dash OR easy beast pogo ) ) |  | Verified |  |
| G1 | gap 1 | chain break spot | left platforms | none (falling) |  | Verified |  |
| G2 | gap 2 | chain break spot | flea sign platform | clawline |  | Verified | only needs to cover horizontal movement that V2 doesn't. no inverse. |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| chain drop platform | chain break spot | none (stand on it) |  | Verified | switch |  |

#### Notes

no checks

### The Marrow Lava Track (Bone_16)

**Game ID:** Bone_16

**Contributors:** herounit

#### Subrooms

- ceiling exit area
- upper maze left
- middle maze
- left alcove
- lower maze 1
- lower maze 2
- lower maze 3
- right alcove
- left lava track
- right lava track

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left lava track | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | R | none |  | Verified |  |
| R | right | right lava track | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | L | none |  | Verified |  |
| C | ceiling | ceiling exit area | [The Marrow Skull Tyrant Arena (Bone_15)](#the-marrow-skull-tyrant-arena-bone15) | F | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LT | lava track | right lava track | left lava track | activate track pressure plate  OR ( clawline x 8 AND easy shaman pogo ) |  | Verified | other stalls would work but would be harder |
| LT | lava track | left lava track | right lava track | activate track pressure plate  OR ( clawline x 8 AND easy shaman pogo ) |  | Verified | other stalls would work but would be harder |
| AM | ascend to maze | right lava track | lower maze 2 | cling grip  OR silk soar  OR ( scuttlebrace AND ( ledge grab OR faydown cloak OR clawline  ) ) |  | Verified |  |
| AM | ascend to maze | lower maze 2 | right lava track | none (falling) |  | Verified |  |
| RBW | right break wall | lower maze 2 | lower maze 3 | none (break wall right) |  | Verified |  |
| RBW | right break wall | lower maze 3 | lower maze 2 | none (break wall left) |  | Verified |  |
| AR | ascend right | lower maze 3 | right alcove | cling grip  OR scuttlebrace  OR ( faydown AND ledge grab ) |  | Verified |  |
| AR | ascend right | right alcove | lower maze 3 | spike pogo  OR cling grip  OR faydown  OR dash  OR drifters  OR clawline  OR sharpdart  OR scuttlebrace |  | Verified |  |
| MMA | middle maze ascend | lower maze 1 | middle maze | cling grip  OR scuttlebrace  OR ( faydown cloak AND ( ledge grab OR clawline OR easy shaman pogo ) ) |  | Verified |  |
| MMA | middle maze ascend | middle maze | lower maze 1 | none (falling) |  | Verified |  |
| LA | left alcove access | middle maze | left alcove | none (break wall left) |  | Verified |  |
| LA | left alcove access | left alcove | middle maze | cling grip  OR scuttlebrace  OR ( ledge grab AND faydown cloak ) |  | Verified |  |
| SP | spike pogo | lower maze 1 | lower maze 2 | ledge grab  OR spike pogo  OR run  OR dash  OR drifter's cloak  OR faydown cloak  OR clawline  OR scuttlebrace  OR sharpdart |  | Verified | roof makes it so ledge grab works from left to right  but not the other way |
| SP | spike pogo | lower maze 2 | lower maze 1 | spike pogo  OR run  OR dash  OR drifters  OR faydown  OR clawline  OR scuttlebrace  OR sharpdart |  | Verified | possible other stalls might work - lip on ceiling seems to make it impassable with walking jump? |
| UBW | upper break wall | upper maze left | ceiling exit area | none (break wall right) |  | Verified |  |
| UBW | upper break wall | ceiling exit area | upper maze left | none (break wall left) |  | Verified |  |
| UA | upper ascend | middle maze | upper maze left | silk soar  OR cling grip  OR scuttlebrace  OR ( faydown cloak AND ledge grab ) |  | Verified |  |
| UA | upper ascend | upper maze left | middle maze | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| track pressure plate | right lava track | none (stand on it) |  | Verified | switch |  |
| the marrow rosary cache 11 | left alcove | none |  | Verified | collectible |  |
| the marrow rosary cache 12 | left alcove | none |  | Verified | collectible |  |
| the marrow rosary cache 13 | right alcove | none |  | Verified | collectible |  |

### The Marrow Flea Caravan (Bone_10)

**Game ID:** Bone_10

**Contributors:** herounit

#### Subrooms

- top floor
- before breakable wall
- behind breakable wall
- behind metal gate
- flea floor
- ground floor

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | top floor | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | LR | none |  | Verified |  |
| R | right | behind metal gate | [The Marrow Skull Tyrant Arena (Bone_15)](#the-marrow-skull-tyrant-arena-bone15) | L | none |  | Verified |  |
| F | floor | ground floor | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | RC | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | flea floor | behind metal gate | activate door switch |  | Verified |  |
| DS | door switch | behind metal gate | flea floor | activate door switch |  | Verified |  |
| V1 | vertical 1 | ground floor | flea floor | ledge grab OR easy shaman pogo OR faydown OR cling grip OR scuttlebrace OR silk soar |  | Verified |  |
| V1 | vertical 1 | flea floor | ground floor | none (falling) |  | Verified |  |
| BW | break wall | before breakable wall | behind breakable wall | break wall left |  | Verified |  |
| BW | break wall | behind breakable wall | before breakable wall | break wall right |  | Verified |  |
| V2 | vertical 2 | flea floor | before breakable wall | ledge grab OR faydown OR cling grip OR silk soar |  | Verified |  |
| V2 | vertical 2 | before breakable wall | flea floor | none (falling) |  | Verified |  |
| V3 | vertical 3 | before breakable wall | top floor | ledge grab OR easy shaman pogo OR faydown OR cling grip OR scuttlebrace OR silk soar |  | Verified |  |
| V3 | vertical 3 | top floor | before breakable wall | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| the marrow flea caravan passage frayed rosary string | top floor | none |  | Verified | collectible |  |
| the marrow flea caravan rosary dish | behind breakable wall | none |  | Verified | collectible |  |
| door switch | behind metal gate | flip switch up |  | Verified | switch |  |
| survivors camps supplies wish granted | flea floor | complete THE survivors camp supplies wish promised |  | Verified | event | reward is 180 rosaries |
| the lost fleas wish promised | flea floor | none |  | Verified | event | wish can be started here or at the bone bottom wish wall |
| the lost fleas wish granted | flea floor | ( act 1 OR act 2 )  AND complete the lost fleas wish promised AND fleas 5 |  | Verified | event | grants caravan invite |
| flea caravan move to greymoor | flea floor | complete the lost fleas wish granted |  | Verified | event |  |

### The Marrow Shaft (Bone_03)

**Game ID:** Bone_03

**Contributors:** herounit

#### Subrooms

- bottom shaft
- lower middle shaft
- upper middle shaft
- the bridge
- ceiling exit area
- big boy shelf
- collapsing upper crossing

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor | bottom shaft | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | LC | none |  | Verified |  |
| LL | lower left | bottom shaft | [The Marrow Shaft Side Room (Bone_17)](#the-marrow-shaft-side-room-bone17) | R | none |  | Verified |  |
| ML | middle left | upper middle shaft | [The Marrow Map Shop (Bone_04)](#the-marrow-map-shop-bone04) | R | none |  | Verified |  |
| UL | upper left | the bridge | [The Marrow Bellshrine (Bellshrine)](#the-marrow-bellshrine-bellshrine) | R | ( bellshrinesanity off AND activate bellshrine switch IN the marrow bellshrine )  OR ( bellshrinesanity on AND have bell the marrow ) |  | Verified | requirement for inner and outer gate must be maintained in sync |
| LR | lower right | lower middle shaft | [The Marrow Flea Caravan (Bone_10)](#the-marrow-flea-caravan-bone10) | L | none |  | Verified |  |
| UR | upper right | the bridge | [The Marrow Mr Burns House (Bone_14)](#the-marrow-mr-burns-house-bone14) | L | none |  | Verified |  |
| C | ceiling | ceiling exit area | [The Marrow Skull Wall (Bone_06)](#the-marrow-skull-wall-bone06) | F | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | upper middle shaft | the bridge | activate door switch AND ( ledge grab OR run OR dash OR easy beast pogo OR easy shaman pogo OR drifters OR faydown OR cling grip OR silk soar OR clawline OR sharpdart ) |  | Verified |  |
| DS | door switch | the bridge | upper middle shaft | activate door switch |  | Verified |  |
| V1 | vertical 1 | bottom shaft | lower middle shaft | ledge grab OR easy enemy pogo OR cling grip OR faydown OR silk soar |  | Verified |  |
| V1 | vertical 1 | lower middle shaft | bottom shaft | none (falling) |  | Verified |  |
| V2 | vertical 2 | lower middle shaft | upper middle shaft | ledge grab OR easy enemy pogo OR run OR dash OR drifters OR faydown OR cling grip OR scuttlebrace OR clawline OR sharpdart OR silk soar OR easy shaman pogo OR easy hunter pogo OR easy architect pogo OR easy beast pogo OR easy wanderer charge OR easy reaper charge OR easy heal stall OR easy flea brew stall OR easy flintslate stall OR easy plasmium phial stall OR easy voltvessels stall |  | Verified | a WIDE variety of stalls work here. karma for the bottom section all being one chunk |
| V2 | vertical 2 | upper middle shaft | lower middle shaft | none (falling) |  | Verified |  |
| V3 | vertical 3 | the bridge | collapsing upper crossing | ledge grab OR cling grip OR faydown OR silk soar |  | Verified |  |
| V3 | vertical 3 | collapsing upper crossing | the bridge | none (falling) |  | Verified |  |
| V4 | vertical 4 | collapsing upper crossing | big boy shelf | ledge grab OR cling grip OR faydown OR silk soar OR easy enemy pogo |  | Verified |  |
| V4 | vertical 4 | big boy shelf | collapsing upper crossing | none (falling) |  | Verified |  |
| V5 | vertical 5 | big boy shelf | ceiling exit area | ledge grab OR cling grip OR scuttlebrace OR faydown OR silk soar |  | Verified |  |
| V5 | vertical 5 | ceiling exit area | big boy shelf | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| door switch | the bridge | flip switch down |  | Verified | switch |  |

#### Notes

no checks

### The Marrow Shaft Side Room (Bone_17)

**Game ID:** Bone_17

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | LL | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shard pendant |  | none |  | Verified | collectible |  |

### The Marrow Map Shop (Bone_04)

**Game ID:** Bone_04

**Contributors:** herounit

#### Subrooms

- right lower path
- right upper path
- middle upper platform
- shakra intro
- bench spot

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right upper path | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | ML | none |  | Verified |  |
| F | floor | right lower path | [The Marrow Entrance (Bone_01)](#the-marrow-entrance-bone01) | C | none |  | Verified |  |
| UL | upper left | bench spot | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | UR | none |  | Verified |  |
| LL | lower left | shakra intro | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | LR | none |  | Verified |  |
| C | ceiling | shakra intro | [The Marrow Bellway (Bone_05)](#the-marrow-bellway-bone05) | F | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | shakra intro | bench spot | activate bench gate switch |  | Verified |  |
| DS | door switch | bench spot | shakra intro | activate bench gate switch |  | Verified |  |
| V1 | vertical 1 | right lower path | right upper path | ledge grab  OR cling grip OR silk soar OR faydown |  | Verified |  |
| V1 | vertical 1 | right upper path | right lower path | none (falling) |  | Verified |  |
| G1 | gap 1 | right upper path | middle upper platform | activate lower platform switch same room OR clawline OR sharpdart OR faydown OR ( run AND ( ledge grab OR dash OR easy beast pogo OR easy shaman pogo OR drifters ) ) |  | Verified |  |
| G1 | gap 1 | middle upper platform | right upper path | activate lower platform switch same room |  | Verified |  |
| V2 | vertical 2 | right lower path | middle upper platform | silk soar |  | Verified |  |
| V2 | vertical 2 | middle upper platform | right lower path | none (falling) |  | Verified |  |
| V3 | vertical 3 | right lower path | shakra intro | ledge grab  OR cling grip OR silk soar OR faydown OR scuttlebrace OR easy shaman pogo |  | Verified |  |
| V3 | vertical 3 | shakra intro | right lower path | none (falling) |  | Verified |  |
| G2 | gap 2 | middle upper platform | shakra intro | run  OR dash OR easy beast pogo OR easy architect pogo OR drifters OR faydown OR clawline OR sharpdart |  | Verified |  |
| G2 | gap 2 | shakra intro | middle upper platform | clawline OR sharpdart |  | Verified | anything that would get you from lower to upper is excluded for simplicity (ledge grab) |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| lower platform switch same room | right lower path | flip switch down |  | Verified | switch |  |
| the marrow rosary cache 7 | right lower path | none |  | Verified | collectible |  |
| lower platform switch other room | middle upper platform | flip switch up |  | Verified | switch | lowers platform into the marrow entrance room |
| the marrow shell shard cache 2 | shakra intro | none |  | Verified | collectible |  |
| the marrow shell shard cache 3 | shakra intro | none |  | Verified | collectible |  |
| quill | shakra intro | rosaries 50 |  | Verified | collectible | shakra's shop |
| compass | shakra intro | rosaries 70 |  | Verified | collectible | shakra's shop |
| map mosslands | shakra intro | rosaries 40 |  | Verified | collectible | shakra's shop |
| map the marrow | shakra intro | rosaries 50 |  | Verified | collectible | shakra's shop |
| map bench pins | shakra intro | rosaries 60 |  | Verified | collectible | shakra's shop |
| map bellway pins | shakra intro | rosaries 60 |  | Verified | collectible | shakra's shop \| appears to be bugged in availability logic still. shows available but isn't |
| volatile flintbeetle 2 | right upper path | complete THE volatile flintbeetles wish promised |  | Verified | miniboss | this one swaps position based on when the marrow bellshrine is activated (per the wiki) - best to ensure both locations are accessible for the quest |
| bench gate switch | bench spot | flip switch up |  | Verified | switch |  |
| bench | bench spot | none |  | Verified | bench |  |

### The Marrow Bellway (Bone_05)

**Game ID:** Bone_05

**Contributors:** herounit

#### Subrooms

- left area
- boss room
- right area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left area | [Mosshome Middle (Mosstown_01)](#mosshome-middle-mosstown01) | LR | none |  | Verified |  |
| F | floor | left area | [The Marrow Map Shop (Bone_04)](#the-marrow-map-shop-bone04) | C | none |  | Verified |  |
| R | right | right area | [The Marrow Bellshrine (Bellshrine)](#the-marrow-bellshrine-bellshrine) | L | none |  | Verified |  |
| BB | bellway | right area | [Bellway Menu](#bellway-menu) | TM | unlock bellway the marrow |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LB | left boss fight | left area | boss room | none |  | Verified |  |
| LB | left boss fight | boss room | left area | none |  | Verified | boss fight doesn't start automatically so can leave any time |
| RB | right boss fight | right area | boss room | defeat bell beast boss fight |  | Verified | can't enter the arena from this side |
| RB | right boss fight | boss room | right area | defeat bell beast boss fight |  | Verified | bell beast defeated needs to be here to gate this from seemingly like a straight passthrough |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bell beast boss fight | boss room | silkspear |  | Verified | boss | only silkspear works here |
| bell beast silk heart | boss room | defeat bell beast boss fight |  | Verified | collectible |  |
| bellway the marrow | right area | defeat bell beast boss fight |  | Verified | travel |  |

### The Marrow Bellshrine (Bellshrine)

**Game ID:** Bellshrine

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [The Marrow Bellway (Bone_05)](#the-marrow-bellway-bone05) | R | none |  | Verified |  |
| R | right |  | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | UL | ( bellshrinesanity off AND activate bellshrine switch )  OR ( bellshrinesanity on AND have bell the marrow ) |  | Verified | requirement for inner and outer gate must be maintained in sync |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bellshrine switch |  | flip switch down |  | Verified | switch | this opens the right exit |
| bench |  | activate bellshrine switch |  | Verified | bench |  |
| bell the marrow |  | activate bellshrine switch |  | Verified | collectible |  |

### The Marrow Skull Wall (Bone_06)

**Game ID:** Bone_06

**Contributors:** herounit

#### Subrooms

- ground floor
- upper echelon
- flea platform
- middle platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor | ground floor | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | C | none |  | Verified |  |
| R | right | ground floor | [The Marrow Skull Wall Side Room (Bone_18)](#the-marrow-skull-wall-side-room-bone18) | L | none |  | Verified |  |
| L | left | ground floor | [Greyroots Basement Tall room (Mosstown_03)](#greyroots-basement-tall-room-mosstown03) | LR | clear blast rock exit blockade IN shellwood diddy basement tall room |  | Verified | shellwood |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | ground floor | middle platform | ledge grab OR easy enemy pogo OR easy shaman pogo OR faydown OR cling grip OR silk soar |  | Verified |  |
| V1 | vertical 1 | middle platform | ground floor | none (falling) |  | Verified |  |
| V2 | vertical 2 | middle platform | upper echelon | ledge grab OR easy enemy pogo OR easy shaman pogo OR faydown OR cling grip OR silk soar |  | Verified |  |
| V2 | vertical 2 | upper echelon | middle platform | none (falling) |  | Verified |  |
| FD | flea drop | flea platform | upper echelon | silk soar OR ( ledge grab AND faydown ) |  | Verified |  |
| FD | flea drop | upper echelon | flea platform | none (falling) |  | Verified |  |
| FC | flea crossing | ground floor | flea platform | silk soar OR ( clawline AND easy enemy pogo ) |  | Verified | can clawline across this gap with the help of a very cooperative enemy |
| FC | flea crossing | flea platform | ground floor | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea the marrow | flea platform | break vines right |  | Verified | collectible |  |
| volatile flintbeetle 2 | upper echelon | complete THE volatile flintbeetles wish promised |  | Verified | miniboss | this one swaps position based on when the marrow bellshrine is activated (per the wiki) - best to ensure both locations are accessible for the quest |
| Shell Fossil Mimic | upper echelon | attack up |  | Verified | enemy | scene dumper grabbed it, so why not? |

### The Marrow Skull Wall Side Room (Bone_18)

**Game ID:** Bone_18

**Contributors:** herounit

#### Subrooms

- lower level
- upper level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | lower level | [The Marrow Skull Wall (Bone_06)](#the-marrow-skull-wall-bone06) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CG | climb | lower level | upper level | cling grip  OR silk soar OR scuttlebrace |  | Verified |  |
| CG | climb | upper level | lower level | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| the marrow pilgrim diary | lower level | none |  | Verified | lore |  |
| gauntlet fight | upper level | have cling grip |  | Verified | gauntlet |  |
| the marrow memory locket | upper level | defeat gauntlet fight |  | Verified | collectible |  |

### The Marrow Mr Burns House (Bone_14)

**Game ID:** Bone_14

**Contributors:** herounit

#### Subrooms

- ground floor
- right exit area
- right upper area
- mr burns house

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | ground floor | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | UR | none |  | Verified |  |
| R | right | right exit area | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | ground floor | right upper area | silk soar OR ledge grab OR cling grip OR faydown |  | Verified | silk soar works here because the jump to the platform below the right exit (and above the big goomba) is tight but can be done without ledge grab, so there is no ceiling interference |
| V1 | vertical 1 | right upper area | ground floor | none (falling) |  | Verified |  |
| V2 | vertical 2 | ground floor | right exit area | silk soar OR ledge grab OR cling grip OR faydown |  | Verified | silk soar works here because the jump to the platform below the right exit (and above the big goomba) is tight but can be done without ledge grab, so there is no ceiling interference |
| V2 | vertical 2 | right exit area | ground floor | none (falling) |  | Verified |  |
| G1 | gap 1 | right exit area | right upper area | run OR dash OR drifters OR faydown OR clawline OR sharpdart OR easy beast pogo |  | Verified |  |
| G1 | gap 1 | right upper area | right exit area | run OR dash OR drifters OR faydown OR clawline OR sharpdart OR easy beast pogo |  | Verified |  |
| MB | mr burns entry | ground floor | mr burns house | none (tight jump) |  | Verified | jump is a tad tight but can be done |
| MB | mr burns entry | mr burns house | ground floor | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache the marrow 10 | ground floor | none |  | Verified | collectible |  |
| shell shard cache the marrow 5 | right upper area | none |  | Verified | collectible |  |
| shell shard cache the marrow 6 | right upper area | none |  | Verified | collectible |  |

### The Marrow Lower Pogo (Bone_07)

**Game ID:** Bone_07

**Contributors:** herounit

#### Subrooms

- lower right exit area
- craftmetal alcove
- upper mid right area
- lower mid right area
- cache alcove
- pogo supreme

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | pogo supreme | [The Marrow Upper Pogo (Bone_19)](#the-marrow-upper-pogo-bone19) | F | none |  | Verified |  |
| L | left | pogo supreme | [The Marrow Mr Burns House (Bone_14)](#the-marrow-mr-burns-house-bone14) | R | none |  | Verified |  |
| UR | upper right | lower mid right area | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | UL | none |  | Verified |  |
| LR | lower right | lower right exit area | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | LL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | upper mid right area | pogo supreme | ledge grab OR easy shaman pogo OR cling grip OR scuttlebrace OR faydown OR silk soar |  | Verified |  |
| V1 | vertical 1 | pogo supreme | upper mid right area | none (falling) |  | Verified |  |
| L1 | loop part 1 | lower mid right area | upper mid right area | ledge grab OR easy shaman pogo OR cling grip OR scuttlebrace OR faydown OR silk soar |  | Verified |  |
| L1 | loop part 1 | upper mid right area | lower mid right area | none (falling) |  | Verified |  |
| L2 | loop part 2 | upper mid right area | cache alcove | break blast rock left |  | Verified |  |
| L3 | loop part 3 | cache alcove | lower mid right area | none (falling) |  | Verified |  |
| BT | blast tunnel | pogo supreme | craftmetal alcove | break blast rock left AND break blast rock right |  | Verified |  |
| BT | blast tunnel | craftmetal alcove | pogo supreme | ledge grab OR cling grip OR scuttlebrace OR faydown |  | Verified |  |
| V2 | vertical 2 | lower right exit area | pogo supreme | ledge grab OR cling grip OR scuttlebrace OR faydown OR silk soar |  | Verified |  |
| V2 | vertical 2 | pogo supreme | lower right exit area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| the marrow craft metal | craftmetal alcove | attack right |  | Verified | collectible |  |
| the marrow 4 shell shard cache | cache alcove | none |  | Verified | collectible |  |
| volatile flintbeetle 3 | lower mid right area | complete THE volatile flintbeetles wish promised |  | Verified | miniboss | this one has a stable position |

### The Marrow Upper Pogo (Bone_19)

**Game ID:** Bone_19

**Contributors:** herounit

#### Subrooms

- entrance
- pogo land
- chest area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor | entrance | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | C | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BW | break wall | entrance | pogo land | break wall left |  | Verified |  |
| BW | break wall | pogo land | entrance | break wall right |  | Verified |  |
| V1 | vertical 1 | chest area | pogo land | ledge grab OR silk soar OR cling grip OR faydown |  | Verified |  |
| V1 | vertical 1 | pogo land | chest area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache the marrow 14 | pogo land | none |  | Verified | collectible |  |
| rosary cache the marrow 15 | pogo land | none |  | Verified | collectible |  |
| rosary cache the marrow 16 | entrance | none |  | Verified | collectible |  |
| the marrow upper pogo rosary chest | chest area | none |  | Verified | collectible | NOT RANDOMIZED YET |

### The Marrow Jail Pathway (Bone_08)

**Game ID:** Bone_08

#### Subrooms

- upper area
- middle area
- jail area
- check alcove

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper area | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | UR | none |  | Verified |  |
| LL | lower left | middle area | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | LR | none |  | Verified |  |
| UR | upper right | upper area | [Bellhart Lower (Belltown_basement_03)](#bellhart-lower-belltownbasement03) | L | none |  | Verified |  |
| MR | middle right | middle area | [Hunter's March Entrance (Ant_02)](#hunters-march-entrance-ant02) | L | none |  | Verified |  |
| JD | jail door | jail area | [The Marrow Jail (Bone_12)](#the-marrow-jail-bone12) | L | none |  | Verified |  |
| F | floor | jail area | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | C | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PS | platform switch | middle area | upper area | activate platform switch |  | Verified |  |
| PS | platform switch | upper area | middle area | none (falling) |  | Verified |  |
| L1 | ledges 1 | check alcove | middle area | ledge grab OR cling grip OR faydown OR scuttlebrace OR silk soar |  | Verified |  |
| L1 | ledges 1 | middle area | check alcove | none (falling) |  | Verified |  |
| L2 | ledges 2 | jail area | check alcove | ledge grab OR cling grip OR faydown OR scuttlebrace OR silk soar OR easy shaman pogo |  | Verified |  |
| L2 | ledges 2 | check alcove | jail area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| platform switch | upper area | none |  | Verified | switch |  |
| the marrow rosary cache 8 | check alcove | none |  | Verified | collectible |  |
| the marrow rosary cache 9 | check alcove | none |  | Verified | collectible |  |

### The Marrow Jail (Bone_12)

**Game ID:** Bone_12

**Contributors:** herounit

#### Subrooms

- ground floor
- grindle cell
- other cell
- above grindle cell
- upper platforms

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | ground floor | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | JD | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | ground floor | upper platforms | ledge grab OR cling grip OR scuttlebrace OR faydown OR silk soar |  | Verified |  |
| V1 | vertical 1 | upper platforms | ground floor | none (falling) |  | Verified |  |
| C1 | open cell 1 | upper platforms | grindle cell | break wall right |  | Verified |  |
| C1 | open cell 1 | grindle cell | upper platforms | break wall left |  | Verified |  |
| C2 | open cell 2 | upper platforms | other cell | break wall left |  | Verified |  |
| C2 | open cell 2 | other cell | upper platforms | break wall right |  | Verified |  |
| V2 | vertical 2 | grindle cell | above grindle cell | ledge grab OR cling grip OR faydown OR silk soar |  | Verified |  |
| V2 | vertical 2 | above grindle cell | grindle cell | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bench | ground floor | none |  | Verified | bench |  |
| pin minigame 1 | ground floor | defeat THE boss widow AND rosaries 25 AND ( Act 1 OR Act 2 ) |  | Verified | event | requirements per the wiki - not sure if you need the straight pin to start it or not |
| pin minigame 2 | ground floor | complete pin minigame 1 AND rosaries 25 AND ( Act 1 OR Act 2 ) |  | Verified | event | requirements per the wiki |
| pin minigame 3 | ground floor | complete pin minigame 2 AND rosaries 25 AND ( Act 1 OR Act 2 ) |  | Verified | event | requirements per the wiki |
| progressive tool pouch | ground floor | complete pin minigame 1 OR Act 3 |  | Verified | collectible | tool pouch will be available for free in act 3 if not already collected |
| heavy rosary necklace | ground floor | complete pin minigame 2 |  | Verified | collectible |  |
| straight pin | above grindle cell | none |  | Verified | collectible |  |

### The Marrow Lava Docks (Bone_09)

**Game ID:** Bone_09

**Contributors:** herounit

#### Subrooms

- upper left platforms
- elevated platforms
- upper right exit
- ground floor

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | upper left platforms | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | F | none |  | Verified |  |
| L | left | ground floor | [The Marrow Lava Track (Bone_16)](#the-marrow-lava-track-bone16) | R | none |  | Verified |  |
| UR | upper right | upper right exit | [Deep Docks Entrance (Dock_08)](#deep-docks-entrance-dock08) | UL | none |  | Verified |  |
| LR | lower right | ground floor | [Deep Docks Entrance (Dock_08)](#deep-docks-entrance-dock08) | LL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| G1 | gap 1 | upper left platforms | elevated platforms | faydown OR cling grip  OR scuttlebrace |  | Verified |  |
| G1 | gap 1 | elevated platforms | upper left platforms | ledge grab OR faydown OR cling grip |  | Verified |  |
| G2 | gap 2 | elevated platforms | upper right exit | none (falling) |  | Verified |  |
| G2 | gap 2 | upper right exit | elevated platforms | ledge grab OR faydown OR cling grip |  | Verified |  |
| V1 | vertical 1 | ground floor | upper left platforms | ledge grab OR easy enemy pogo OR faydown OR cling grip OR scuttlebrace OR silk soar |  | Verified |  |
| V1 | vertical 1 | upper left platforms | ground floor | none (falling) |  | Verified |  |
| V2 | vertical 2 | ground floor | elevated platforms | silk soar |  | Verified |  |
| V2 | vertical 2 | elevated platforms | ground floor | none (falling) |  | Verified |  |
| V3 | vertical 3 | ground floor | upper right exit | silk soar |  | Verified |  |
| V3 | vertical 3 | upper right exit | ground floor | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary spike | upper left platforms | none |  | Verified | collectible |  |

### The Marrow Skull Tyrant Arena (Bone_15)

**Game ID:** Bone_15

**Contributors:** herounit

#### Subrooms

- ground floor
- tyrants throne

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor | ground floor | [The Marrow Lava Track (Bone_16)](#the-marrow-lava-track-bone16) | C | none |  | Verified |  |
| L | left | ground floor | [The Marrow Flea Caravan (Bone_10)](#the-marrow-flea-caravan-bone10) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| KK | kneel before the king | ground floor | tyrants throne | ledge grab OR silk soar OR cling grip OR faydown |  | Verified |  |
| KK | kneel before the king | tyrants throne | ground floor | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| free silk spinner | ground floor | attack down |  | Verified | collectible |  |
| skull tyrant boss fight | tyrants throne | none |  | Verified | boss |  |
| crown fragment | tyrants throne | complete THE the terrible tyrant wish promised |  | Verified | collectible |  |

## Weavenest Atla

### Weavenest Atla Entrance (Weave_04)

**Game ID:** Weave_04

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| WD | weavenest door |  | [Moss Grotto East (Tut_01b)](#moss-grotto-east-tut01b) | WD | needolin |  | Verified |  |
| R | right |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | UL | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Weavenest Atla Teleporter (Weave_02)

**Game ID:** Weave_02

**Contributors:** herounit

#### Subrooms

- upper telepad
- upper shaft
- lower shaft
- lower telepad

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper telepad | [Weavenest Atla Entrance (Weave_04)](#weavenest-atla-entrance-weave04) | R | none |  | Verified |  |
| UR | upper right | upper telepad | [Weavenest Atla Power Room (Weave_12)](#weavenest-atla-power-room-weave12) | L | none |  | Verified |  |
| MR | middle right | upper shaft | [Weavenest Atla Hallway (Weave_13)](#weavenest-atla-hallway-weave13) | L | none |  | Verified |  |
| ML | middle left | lower shaft | [Weavenest Atla Spool (Weave_11)](#weavenest-atla-spool-weave11) | R | none |  | Verified |  |
| LL | lower left | lower telepad | [Weavenest Atla Bench (Weave_07)](#weavenest-atla-bench-weave07) | R | none |  | Verified |  |
| LR | lower right | lower telepad | [Weavenest Atla Eva (Weave_10)](#weavenest-atla-eva-weave10) | L | break wall right |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TP | teleporter | upper telepad | lower telepad | complete THE weavenest atla power activation |  | Verified |  |
| TP | teleporter | lower telepad | upper telepad | complete THE weavenest atla power activation |  | Verified |  |
| SM | shaft middle | lower telepad | upper shaft | cling grip OR silk soar OR ( faydown cloak AND scuttlebrace ) |  | Verified |  |
| SM | shaft middle | upper shaft | lower telepad | none (falling) |  | Verified |  |
| SB | shaft base | lower telepad | lower shaft | cling grip OR silk soar OR ( faydown cloak AND scuttlebrace ) |  | Verified |  |
| SB | shaft base | lower shaft | lower telepad | none (falling) |  | Verified |  |

#### Check Locations

No check locations defined.

### Weavenest Atla Power Room (Weave_12)

**Game ID:** Weave_12

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | UR | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| weavenest atla power activation |  | flip switch up |  | Verified | switch | NOT CURRENTLY RANDOMIZED |
| weavenest atla map |  | complete weavenest atla power activation |  | Verified | collectible |  |

### Weavenest Atla Eva (Weave_10)

**Game ID:** Weave_10

**Contributors:** herounit

#### Subrooms

- left exit area
- eva pod

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left exit area | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | LR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | left exit area | eva pod | break wall right AND break wall down |  | Verified |  |
| V1 | vertical 1 | eva pod | left exit area | break wall left AND break wall up AND ( cling grip OR silk soar OR scuttlebrace ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| crest of the hunter | eva pod | none |  | Verified | collectible | per a random reddit thread |
| yellow vesticrest | eva pod | tool slots unlocked 12 |  | Verified | collectible | per a random reddit thread |
| blue vesticrest | eva pod | tool slots unlocked 20 |  | Verified | collectible | per a random reddit thread |
| crest of the hunter 2 | eva pod | tool slots unlocked 27 |  | Verified | collectible | per a random reddit thread |
| sylphsong | eva pod | tool slots unlocked 32 |  | Verified | collectible | per a random reddit thread |

### Weavenest Atla Bench (Weave_07)

**Game ID:** Weave_07

**Contributors:** herounit

#### Subrooms

- bench area
- left exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | bench area | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | LL | none |  | Verified |  |
| L | left | left exit area | [Weavenest Atla Grotto (Weave_03)](#weavenest-atla-grotto-weave03) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SW | swim | bench area | left exit area | swim |  | Verified | there is a slim possibility clawline and cling grip could work here, but can't test until swim is randomized |
| SW | swim | left exit area | bench area | swim |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bench | bench area | none |  | Verified | bench |  |

### Weavenest Atla Grotto (Weave_03)

**Game ID:** Weave_03

**Contributors:** herounit

#### Subrooms

- right exit area
- far east platforms
- upper east platforms
- mossberry platform
- causeway 
- upper west platforms
- lower west platforms
- boss room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right exit area | [Weavenest Atla Bench (Weave_07)](#weavenest-atla-bench-weave07) | L | break vines right |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BV1 | break vines 1 | right exit area | far east platforms | break vines left |  | Verified |  |
| BV1 | break vines 1 | far east platforms | right exit area | break vines right |  | Verified |  |
| P1 | platforming 1 | far east platforms | upper east platforms | none (falling) |  | Verified |  |
| P1 | platforming 1 | upper east platforms | far east platforms | ledge grab OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR scuttlebrace OR sharpdart OR easy shaman pogo |  | Verified |  |
| MU | mossberry upper | upper east platforms | mossberry platform | run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline OR easy beast pogo OR ( ledge grab AND ( easy shaman pogo OR easy architect pogo ) ) |  | Verified | other stall techniques may also make it - untested; was unable to replicate previous reaper pogo |
| ML | mossberry lower | causeway | mossberry platform | silk soar |  | Verified |  |
| ML | mossberry lower | mossberry platform | causeway | none (falling) |  | Verified |  |
| EV1 | east vertical 1 | causeway | upper east platforms | ledge grab OR faydown cloak OR   silk soar |  | Verified |  |
| EV1 | east vertical 1 | upper east platforms | causeway | none (falling) |  | Verified |  |
| WG1 | west gap 1 | causeway | upper west platforms | none (falling) |  | Verified |  |
| WG1 | west gap 1 | upper west platforms | causeway | ledge grab OR run OR dash OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| WG2 | west gap 2 | lower west platforms | causeway | ledge grab OR faydown cloak OR spike pogo OR silk soar |  | Verified |  |
| WG2 | west gap 2 | causeway | lower west platforms | none (falling) |  | Verified |  |
| BR | boss room jump | upper west platforms | boss room | break vines left AND ( run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline OR easy beast pogo ) |  | Verified | beast pogo clears this easily |
| BR | boss room jump | boss room | upper west platforms | break vines right AND ( run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline OR scuttlebrace OR easy beast pogo ) |  | Verified |  |
| F1 | fall 1 | boss room | lower west platforms | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| weavenest atla mossberry | mossberry platform | none |  | Verified | collectible |  |
| double moss mother boss fight | boss room | none |  | Verified | boss | BOSS IS NOT CURRENTLY TIED TO A CHECK - but does unlock weavelight check |
| weavelight | boss room | complete double moss mother boss fight |  | Verified | collectible |  |

### Weavenest Atla Hallway (Weave_13)

**Game ID:** Weave_13

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | MR | none |  | Verified |  |
| R | right |  | [Weavenest Atla Lore (Weave_08)](#weavenest-atla-lore-weave08) | L | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Weavenest Atla Lore (Weave_08)

**Game ID:** Weave_08

**Contributors:** herounit

#### Subrooms

- right exit area
- left exit area
- ground floor
- upper platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left exit area | [Weavenest Atla Hallway (Weave_13)](#weavenest-atla-hallway-weave13) | R | none |  | Verified |  |
| R | right | right exit area | [Weavenest Atla Mask Shard (Weave_05b)](#weavenest-atla-mask-shard-weave05b) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CL | climb pit | ground floor | right exit area | break wall right AND ( spike pogo OR dash OR drifter's cloak OR faydown cloak OR cling grip OR clawline OR sharpdart OR scuttlebrace ) |  | Verified |  |
| CL | climb pit | right exit area | ground floor | break wall left AND ( scuttlebrace OR ( cling grip AND ( spike pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart ) ) ) |  | Verified |  |
| V1 | vertical 1 | ground floor | left exit area | ledge grab OR faydown cloak OR cling grip OR scuttlebrace |  | Verified |  |
| V1 | vertical 1 | left exit area | ground floor | none (falling) |  | Verified |  |
| V2 | vertical 2 | ground floor | upper platform | ledge grab OR faydown cloak OR cling grip OR scuttlebrace |  | Verified |  |
| V2 | vertical 2 | upper platform | ground floor | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rune harp weavenest atla | upper platform | none |  | Verified | collectible |  |
| weavenest atla archive inscription | ground floor | none |  | Verified | lore |  |

### Weavenest Atla Mask Shard (Weave_05b)

**Game ID:** Weave_05b

**Contributors:** herounit

#### Subrooms

- left exit area
- starting line
- mask shard spot

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left exit area | [Weavenest Atla Lore (Weave_08)](#weavenest-atla-lore-weave08) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| G1 | gap 1 | left exit area | starting line | spike pogo OR run OR dash OR drifter's cloak OR faydown cloak OR cling grip OR clawline OR sharpdart |  | Verified |  |
| G1 | gap 1 | starting line | left exit area | spike pogo OR run OR dash OR drifter's cloak OR faydown cloak OR cling grip OR clawline OR sharpdart |  | Verified |  |
| LC | lava challenge | starting line | mask shard spot | silk soar  OR medium scuttlebrace OR ( ( cling grip OR scuttlebrace ) AND ( dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart ) ) |  | Verified | the scuttlebrace-only tech allows this to be done without anything else, but I would personally consider it medium because of the timing and control requirements w/ lava damage for mistakes |
| LC | lava challenge | mask shard spot | starting line | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| weavenest alta mask shard | mask shard spot | none |  | Verified | collectible |  |

### Weavenest Atla Snare (Weave_14)

**Game ID:** Weave_14

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor |  | [Weavenest Atla Spool (Weave_11)](#weavenest-atla-spool-weave11) | C | none (falling) |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| snare setter |  | none |  | Verified | collectible |  |

### Weavenest Atla Spool (Weave_11)

**Game ID:** Weave_11

**Contributors:** herounit

#### Subrooms

- right exit area
- mid passage
- upper left passage
- spool spot

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right exit area | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | ML | none |  | Verified |  |
| C | ceiling | right exit area | [Weavenest Atla Snare (Weave_14)](#weavenest-atla-snare-weave14) | F | silk soar OR ( faydown cloak AND ( cling grip OR scuttlebrace ) ) |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SW1 | swim 1 | right exit area | mid passage | swim  OR clawline  OR sharpdart  OR faydown cloak  OR ( ( ledge grab OR cling grip ) AND ( dash OR drifter's cloak ) )  OR ( easy beast pogo AND ( dash OR run OR drifter's cloak ) ) OR ( dash AND ( run OR drifter's cloak ) ) |  | Verified |  |
| SW1 | swim 1 | mid passage | right exit area | swim OR clawline OR sharpdart OR ( ( ledge grab OR cling grip ) AND ( drifter's cloak OR faydown cloak OR ( dash AND run ) ) ) OR ( easy beast pogo AND dash ) |  | Verified |  |
| V1 | vertical 1 | mid passage | upper left passage | ledge grab OR faydown cloak OR cling grip OR scuttlebrace |  | Verified |  |
| V1 | vertical 1 | upper left passage | mid passage | none (falling) |  | Verified |  |
| F1 | fall 1 | upper left passage | spool spot | none (falling) |  | Verified |  |
| V2 | vertical 2 | mid passage | spool spot | faydown cloak |  | Verified |  |
| V2 | vertical 2 | spool spot | mid passage | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| weavenest atla spool fragment | spool spot | none |  | Verified | collectible |  |

## Wormways

### Wormways Craggler Hallway (Crawl_04)

**Game ID:** Crawl_04

**Contributors:** herounit, cry

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | LR | none |  | Verified |  |
| R | right |  | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | LL | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| craggler mini boss fight |  | none |  | Verified | miniboss |  |
| craggler beast shard |  | defeat craggler mini boss fight |  | Verified | collectible |  |

#### Notes

cry: were we adding craggler into logic?
should at bare minimum have dash or run in combat logic

### Wormways Shaft (Crawl_02)

**Game ID:** Crawl_02

**Contributors:** herounit, cry

#### Subrooms

- entrance tunnel
- middle platform area
- upper platform area
- mask grotto
- rosary duct
- behind door

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | entrance tunnel | [Wormways Craggler Hallway (Crawl_04)](#wormways-craggler-hallway-crawl04) | L | none |  | Verified |  |
| LL | lower left | behind door | [Wormways Middle (Crawl_03b)](#wormways-middle-crawl03b) | R | none |  | Verified | there's a pocket of air behind the door and it is not enforced on the other side |
| UL | upper left | upper platform area | [Wormways Upper West (Crawl_03)](#wormways-upper-west-crawl03) | R | clear shaft wall blockade IN Wormways Upper West |  | Verified |  |
| UR | upper right | middle platform area | [Wormways Upper East (Crawl_01)](#wormways-upper-east-crawl01) | L | none |  | Verified |  |
| MR | middle right | middle platform area | [Wormways Flea Rescue (Crawl_06)](#wormways-flea-rescue-crawl06) | L | break wall {right} |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | middle platform area | entrance tunnel | none (door switch is on this side) |  | Verified |  |
| DS | door switch | entrance tunnel | middle platform area | prereq flip door switch AND (cling grip OR (ledge grab AND faydown cloak) OR scuttlebrace OR silk soar) |  | Verified |  |
| CG | platform gaps | middle platform area | upper platform area | (ledge grab AND (silk soar OR cling grip OR scuttlebrace OR faydown cloak)) OR (silk soar OR cling grip OR scuttlebrace) OR (faydown cloak AND (easy shaman pogo OR easy beast pogo OR easy reaper pogo OR easy architect pogo)) |  | Verified |  |
| CG | platform gaps | upper platform area | middle platform area | none (falling) |  | Verified |  |
| GT | grotto tunnel | entrance tunnel | mask grotto | none (falling) |  | Verified |  |
| GT | grotto tunnel | mask grotto | entrance tunnel | ledge grab OR (cling grip OR faydown cloak OR scuttlebrace OR silk soar) |  | Verified |  |
| DL | duct ledge | upper platform area | rosary duct | cling grip OR scuttlebrace |  | Verified |  |
| DL | duct ledge | rosary duct | upper platform area | none (falling) |  | Verified |  |
| SK | simple key lock | entrance tunnel | behind door | unlock Wormways Simple Lock |  | Verified |  |
| SK | simple key lock | behind door | entrance tunnel | unlock Wormways Simple Lock |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Wormways Simple Lock | entrance tunnel | have Simple Key Wormways |  | Verified | lock | unlocks the LL room exit |
| mask shard wormways | mask grotto | (ledge grab OR cling grip OR silksoar OR faydown cloak) |  | Verified | collectible | current hazard respawn from grotto water makes the theoretical no-swim req arbitrary, (you spawn in the entrance tunnel  or in the shaft if you came from above) |
| frayed rosary string wormways | rosary duct | (ledge grab AND (cling grip OR silk soar OR scuttlebrace)) OR (cling grip OR silk soar OR (scuttlebrace AND (flea brew OR clawline OR sharpdart OR faydown cloak))) |  | Verified | collectible |  |
| flip door switch | middle platform area | flip switch down |  | Verified | switch | unlocks the middle/lower shortcut |

### Wormways Flea Rescue (Crawl_06)

**Game ID:** Crawl_06

**Contributors:** herounit, cry

#### Subrooms

- entrance
- main area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | entrance | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | MR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| D | dash | entrance | main area | spike pogo OR run OR dash OR clawline OR sharpdart OR faydown cloak OR drifter's cloak |  | Verified | spike pogo |
| D | dash | main area | entrance | spike pogo OR run OR dash OR clawline OR sharpdart OR faydown cloak OR drifter's cloak |  | Verified | spike pogo |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea wormways snacc | main area | ledge grab OR (easy enemy pogo) OR silk soar OR faydown cloak OR cling grip |  | Verified | collectible |  |

#### Notes

cry: exit - for room rando - the entrance is functional and open regardless of whether you broke the wall in the shaft, but entering shaft's connected entrance will clip you out of bounds if the wall on the other side is unbroken

### Wormways Middle (Crawl_03b)

**Game ID:** Crawl_03b

**Contributors:** herounit, cry

#### Subrooms

- wormways west scaffold
- main tunnel

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | main tunnel | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | LL | none |  | Verified | simple key lock doesn't block this side at all |
| F | floor | main tunnel | [Wormways Lower East (Crawl_07)](#wormways-lower-east-crawl07) | C | none |  | Verified |  |
| C | ceiling | wormways west scaffold | [Wormways Upper West (Crawl_03)](#wormways-upper-west-crawl03) | F | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RJ | running jump | main tunnel | wormways west scaffold | (ledge grab AND (run OR dash OR faydown cloak OR drifter's cloak OR clawline OR silk soar OR sharpdart OR flea brew)) OR (run OR dash OR faydown cloak OR drifter's cloak OR clawline OR silk soar OR sharpdart OR  (cling grip AND flea brew)) OR (cling grip AND proficient movement AND (architect slash [right] OR easy shaman pogo OR flea brew)) OR easy beast pogo |  | Verified |  |
| RJ | running jump | wormways west scaffold | main tunnel | none (falling) |  | Verified |  |

#### Check Locations

No check locations defined.

### Wormways Upper West (Crawl_03)

**Game ID:** Crawl_03

**Contributors:** herounit, cry

#### Subrooms

- main area upper
- plasmium alcove
- weavenest landing
- main tunnel lower
- right exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor | main tunnel lower | [Wormways Middle (Crawl_03b)](#wormways-middle-crawl03b) | C | none |  | Verified |  |
| R | right | main area upper | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | UL | clear shaft wall blockade |  | Verified |  |
| C | ceiling | main area upper | [Wormways Laboratory (Crawl_08)](#wormways-laboratory-crawl08) | F | silk soar OR cling grip OR scuttlebrace |  | Verified |  |
| WD | weaver door | weavenest landing | [Wormways Weavenest (Crawl_05)](#wormways-weavenest-crawl05) | WD | needolin |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CG | upper climb | main area upper | plasmium alcove | (ledge grab AND (cling grip OR faydown cloak OR scuttlebrace)) OR (cling grip OR scuttlebrace OR (faydown cloak AND easy shaman pogo)) |  | Verified |  |
| CG | upper climb | plasmium alcove | main area upper | (ledge grab AND (cling grip OR silk soar OR faydown cloak)) OR (silk soar OR cling grip OR scuttlebrace) |  | Verified |  |
| BJ | big jump | main tunnel lower | weavenest landing | (ledge grab AND (silk soar OR faydown cloak OR (run AND clawline))) OR silk soar OR faydown cloak OR (run AND clawline AND cling grip) |  | Verified |  |
| BJ | big jump | weavenest landing | main tunnel lower | none (falling) |  | Verified |  |
| CL | lower climb | main tunnel lower | plasmium alcove | silk soar |  | Verified |  |
| CL | lower climb | plasmium alcove | main tunnel lower | none (falling) |  | Verified |  |
| MS | main tunnel shaft | main tunnel lower | main area upper | ledge grab OR cling grip OR scuttlebrace OR faydown cloak OR easy enemy pogo |  | Verified |  |
| MS | main tunnel shaft | main area upper | main tunnel lower | none (falling) |  | Verified |  |
| RA | right ascend | main area upper | right exit area | ledge grab OR faydown cloak OR cling grip OR silk soar OR easy shaman pogo OR scuttlebrace |  | Verified |  |
| RA | right ascend | right exit area | main area upper | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| plasmium bud upper west | plasmium alcove | complete THE alchemist's assistant wish promised  AND needle phial |  | Verified | collectible |  |
| shaft wall blockade | main area upper | break wall right |  | Verified | blockade |  |
| plasmid lower | main tunnel lower | act 3 |  | Verified | enemy | there are two spawn points in this subroom |
| plasmified blood lower | main tunnel lower | needle phial  AND defeat plasmid lower |  | Verified | resource |  |
| plasmid upper | main area upper | act 3 |  | Verified | enemy |  |
| plasmified blood upper | main area upper | needle phial  AND defeat plasmid upper |  | Verified | resource |  |

#### Notes

does anything show up in that tunnel opposite to the plasmium alcove later on? feels like there'd be an item or something relevant there

### Wormways Upper East (Crawl_01)

**Game ID:** Crawl_01

**Contributors:** herounit, cry

#### Subrooms

- spike abyss
- upper exit tunnel
- shakra camp
- pilgrim grave
- central elevator
- abyss crossing

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | spike abyss | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | UR | none |  | Verified |  |
| R | right | upper exit tunnel | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | UL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EG | elevator gap | central elevator | upper exit tunnel | ledge grab OR spike pogo OR run OR dash OR cling grip OR drifter's cloak OR faydown cloak OR sharpdart OR clawline |  | Verified |  |
| EG | elevator gap | upper exit tunnel | central elevator | none (falling) |  | Verified |  |
| SC | camp abyss climb | abyss crossing | spike abyss | none (falling) |  | Verified |  |
| SC | camp abyss climb | spike abyss | abyss crossing | (ledge grab AND (run OR dash OR cling grip OR easy shaman pogo OR easy beast pogo OR clawline OR drifter's cloak OR faydown cloak)) OR (proficient movement AND cling grip) OR faydown cloak OR scuttlebrace OR (cling grip AND (clawline OR sharpdart)) OR silk soar |  | Verified |  |
| EA | elevator abyss cross | abyss crossing | central elevator | ledge grab OR cling grip OR faydown cloak OR scuttlebrace OR easy beast pogo |  | Verified |  |
| EA | elevator abyss cross | central elevator | abyss crossing | none |  | Verified |  |
| GP | grave passage | central elevator | pilgrim grave | ledge grab OR cling grip OR silk soar OR easy enemy pogo OR scuttlebrace OR faydown cloak |  | Verified |  |
| GP | grave passage | pilgrim grave | central elevator | none |  | Verified |  |
| CC | camp crossing | shakra camp | abyss crossing | none |  | Verified |  |
| CC | camp crossing | abyss crossing | shakra camp | none |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| dead bugs purse | pilgrim grave | steel soul off |  | Verified | collectible | STILL MARKED AS ??? ON TRACKER |
| shell satchel | pilgrim grave | steel soul on |  | Verified | collectible |  |
| wormways map | shakra camp | rosaries 70 |  | Verified | collectible | shakra shop |

#### Notes

cry: elevator abyss cross is one and done if entered from above without the requirements to climb back up the abyss

### Wormways Laboratory (Crawl_08)

**Game ID:** Crawl_08

**Contributors:** herounit, cry

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor |  | [Wormways Upper West (Crawl_03)](#wormways-upper-west-crawl03) | C | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| needle phial |  | complete alchemist's assistant wish promised OR complete advanced alchemy wish promised |  | Verified | collectible | This tool is removed from your inventory after completing either wish. |
| plasmium phial |  | complete alchemist's assistant wish granted |  | Verified | collectible |  |
| plasmium gland |  | complete advanced alchemy wish granted |  | Verified | collectible |  |
| alchemist's assistant wish promised |  | none |  | Verified | collectible |  |
| alchemist's assistant wish granted |  | complete alchemist's assistant wish promised AND complete THE plasmium bud upper west AND complete THE plasmium bud lower west AND complete THE plasmium bud lower east |  | Verified | event |  |
| advanced alchemy wish promised |  | act 3  AND complete alchemist's assistant wish granted |  | Verified | event |  |
| advanced alchemy wish granted |  | act 3  AND complete advanced alchemy wish promised AND plasmified blood 10 |  | Verified | event |  |
| laboratory bench |  | none |  | Verified | bench |  |

#### Notes

cry: haven't fully verified act 3 stuff aside from a quick spot check, trying not to spoil myself more than i have to sorry
hero: all good, I gotchu (also insane that you are doing logic contributions before even beating the game LOL)

### Wormways Lower East (Crawl_07)

**Game ID:** Crawl_07

**Contributors:** herounit, cry

#### Subrooms

- ceiling exit area
- left exit area
- floor exit area
- bud alcove
- left offshoot
- lower main tunnel
- upper main tunnel

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | ceiling exit area | [Wormways Middle (Crawl_03b)](#wormways-middle-crawl03b) | F | none |  | Verified |  |
| L | left | left exit area | [Wormways Lower West (Crawl_09)](#wormways-lower-west-crawl09) | R | none |  | Verified |  |
| F | floor | floor exit area | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | C | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CC | ceiling climb | upper main tunnel | ceiling exit area | cling grip  OR (ledge grab AND faydown cloak)  OR (faydown cloak AND easy shaman pogo)  OR scuttlebrace  OR silk soar |  | Verified |  |
| CC | ceiling climb | ceiling exit area | upper main tunnel | none (falling) |  | Verified |  |
| V1 | vertical 1 | left offshoot | upper main tunnel | ledge grab OR cling grip OR scuttlebrace OR faydown cloak OR medium enemy pogo |  | Verified |  |
| V1 | vertical 1 | upper main tunnel | left offshoot | none (falling) |  | Verified |  |
| LC | left climb | left offshoot | left exit area | cling grip OR scuttlebrace OR (faydown cloak AND medium enemy pogo) |  | Verified |  |
| LC | left climb | left exit area | left offshoot | none (falling) |  | Verified |  |
| V2 | vertical 2 | lower main tunnel | left offshoot | cling grip OR scuttlebrace OR faydown cloak OR medium enemy pogo |  | Verified |  |
| V2 | vertical 2 | left offshoot | lower main tunnel | none (falling) |  | Verified |  |
| V3 | vertical 3 | bud alcove | lower main tunnel | ledge grab OR cling grip OR scuttlebrace OR faydown cloak OR medium enemy pogo |  | Verified |  |
| V3 | vertical 3 | lower main tunnel | bud alcove | none (falling) |  | Verified |  |
| FC | floor climb | floor exit area | bud alcove | cling grip OR (ledge grab AND (medium enemy pogo OR faydown cloak)) OR scuttlebrace |  | Verified |  |
| FC | floor climb | bud alcove | floor exit area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| plasmium bud lower east | bud alcove | complete THE alchemist's assistant wish promised  AND needle phial |  | Verified | resource |  |
| plasmid west | left offshoot | act 3 |  | Verified | event | location per the wiki |
| plasmified blood west | left offshoot | needle phial AND defeat plasmid west |  | Verified | resource |  |
| plasmid east | bud alcove | act 3 |  | Verified | enemy | location per the wiki |
| plasmified blood east | bud alcove | needle phial AND defeat plasmid east |  | Verified | resource |  |

#### Notes

this one seems a bit tricky, but also it's just a bit late
i think you need cling grip to from any one point to another in here
TODO: review the mapping in here
cry: Most of this area can be navigated without mobility upgrades simply with pogos, every worm-spawn shaft has a blind spot on the right side hornet can hug to safely avoid the worms and pogo over, most other shafts in wormways also have a blind spot in one direction

### Wormways Lower West (Crawl_09)

**Game ID:** Crawl_09

**Contributors:** herounit, cry

#### Subrooms

- left exit shaft
- right exit tunnel
- upper tunnels
- lower tunnels
- right exit basement
- pilgrim tomb

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right exit tunnel | [Wormways Lower East (Crawl_07)](#wormways-lower-east-crawl07) | L | none |  | Verified |  |
| L | left | left exit shaft | [Wormways Zango Arena (Crawl_10)](#wormways-zango-arena-crawl10) | R | break wall {left] OR break wall {right |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LC | left climb | left exit shaft | upper tunnels | spike pogo AND (silk soar OR cling grip OR scuttlebrace) |  | Verified |  |
| LC | left climb | upper tunnels | left exit shaft | cling grip OR faydown cloak OR easy architect pogo OR easy shaman pogo OR easy reaper pogo OR easy beast pogo OR (scuttlebrace AND spike pogo) |  | Verified |  |
| RC | right climb | right exit tunnel | right exit basement | none (falling) |  | Verified |  |
| RC | right climb | right exit basement | right exit tunnel | cling grip OR scuttlebrace OR easy enemy pogo |  | Verified |  |
| TS | tunnel shaft | lower tunnels | upper tunnels | silk soar OR scuttlebrace OR cling grip |  | Verified |  |
| TS | tunnel shaft | upper tunnels | lower tunnels | none (falling) |  | Verified |  |
| TC | tunnel connector | right exit tunnel | upper tunnels | none |  | Verified |  |
| TC | tunnel connector | upper tunnels | right exit tunnel | none |  | Verified |  |
| PC | pilgrim crevace | lower tunnels | pilgrim tomb | spike pogo OR dash OR faydown cloak |  | Verified |  |
| PC | pilgrim crevace | pilgrim tomb | lower tunnels | cling grip OR scuttlebrace OR faydown cloak |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| wormways memory locket | pilgrim tomb | none |  | Verified | collectible |  |
| plasmium bud lower west | left exit shaft | complete THE alchemist's assistant wish promised  AND needle phial |  | Verified | collectible |  |
| Breakable Mid Wall | upper tunnels | needle {right} OR needle {left} |  | Verified | blockade | the area behind this wall will remain in the dark until broken |
| plasmid upper | upper tunnels | act 3 |  | Verified | enemy | location per the wiki |
| plasmified blood upper | upper tunnels | needle phial AND defeat plasmid upper |  | Verified | resource |  |
| plasmid lower | lower tunnels | act 3 |  | Verified | enemy | location per the wiki; two spawn points in this subroom |
| plasmified blood lower | lower tunnels | needle phial AND defeat plasmid lower |  | Verified | resource |  |
| plasmid east | right exit basement | act 3 |  | Verified | enemy | location per the wiki |
| plasmified blood east | right exit basement | needle phial AND defeat plasmid east |  | Verified | resource |  |

#### Notes

this one seems a bit tricky, but also it's just a bit late
i think you need cling grip to from any one point to another in here
TODO: review the mapping in here
cry: wasn't sure how to mark the second markable wall in this room, there's one at the left exit and one right before the climb connecting to the tunnel network -- the full area behind this second wall is left in the dark until that wall is broken; worth noting since you will have to navigate to it blindly in future room rando if you first enter this room from the left entrance

### Wormways Weavenest (Crawl_05)

**Game ID:** Crawl_05

**Contributors:** herounit, cry

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| WD | weaver door |  | [Wormways Upper West (Crawl_03)](#wormways-upper-west-crawl03) | WD | needolin |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| sharpdart |  | none |  | Verified | collectible |  |
| plasmid |  | act 3 |  | Verified | enemy | location per the wiki; two spawn points in this room |
| plasmified blood |  | needle phial AND defeat plasmid |  | Verified | resource |  |

#### Notes

cry: would any difficulty modifiers be appropriate? ledge grab and horizontal movement abilities are unnecessary but make it considerably easier to deal with the worms, finding a safe gap to cross is pretty strict without them, just trying to be conscious of room rando

### Wormways Zango Arena (Crawl_10)

**Game ID:** Crawl_10

**Contributors:** herounit, cry

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Wormways Lower West (Crawl_09)](#wormways-lower-west-crawl09) | L | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| plasmified zango boss fight |  | act 3 |  | Verified | boss | can extract 4 plasmified blood from this boss, but not listing it as a resource because it can be missed if you just kill the boss without extracting them |

## Deep Docks

### Deep Docks Entrance (Dock_08)

**Game ID:** Dock_08

**Contributors:** herounit

#### Subrooms

- main pathway
- gauntlet left
- gauntlet
- gauntlet right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left2 | gauntlet left | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | UR | none |  | Needs verification |  |
| LL | left1 | main pathway | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | LR | none |  | Needs verification |  |
| R | right1 | main pathway | [Deep Docks Bench Shaft (Dock_01)](#deep-docks-bench-shaft-dock01) | L | none |  | Needs verification |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | main pathway | gauntlet right | activate door switch |  | Needs verification |  |
| DS | door switch | gauntlet right | main pathway | none (switch is on this side) |  | Needs verification |  |
| GL | gauntlet fight left | gauntlet left | gauntlet | none (starts gauntlet) |  | Needs verification |  |
| GL | gauntlet fight left | gauntlet | gauntlet left | defeat gauntlet |  | Needs verification |  |
| GR | gauntlet fight right | gauntlet | gauntlet right | defeat gauntlet |  | Needs verification |  |
| GR | gauntlet fight right | gauntlet right | gauntlet | none (starts gauntlet) |  | Needs verification | probably not possible to reach unless switch is flipped via AP check |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| door switch | gauntlet right | none |  | Needs verification | switch |  |
| gauntlet | gauntlet | none |  | Needs verification | gauntlet |  |
| mask shard the marrow deep docks passage | gauntlet right | none |  | Needs verification | collectible |  |

### Deep Docks Bench Shaft (Dock_01)

**Game ID:** Dock_01

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 |  | [Deep Docks Upper Spire (Bone_East_05)](#deep-docks-upper-spire-boneeast05) | L | gate unlocked from other side |  | Needs verification | must be unlocked from the other side |
| LR | right2 |  | [Deep Docks Map Shop (Bone_East_01)](#deep-docks-map-shop-boneeast01) | UL | none |  | Needs verification |  |
| L | left1 |  | [Deep Docks Entrance (Dock_08)](#deep-docks-entrance-dock08) | R | none |  | Needs verification |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bench rosary lock |  | none |  |  |  |  |
| bench |  | unlock bench |  |  |  |  |
| rosary cache deep docks 7 |  | none |  |  |  | MARKED AS ??? ON TRACKER |
| rosary cache deep docks 8 |  | none |  |  |  | MARKED AS ??? ON TRACKER |
| shell shard cache deep docks 4 |  | none |  |  |  | MARKED AS ??? ON TRACKER |

### Deep Docks Map Shop (Bone_East_01)

**Game ID:** Bone_East_01

**Contributors:** herounit

#### Subrooms

- upper area
- lower area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | lower area | [Deep Docks Bench Shaft (Dock_01)](#deep-docks-bench-shaft-dock01) | LR | none |  | Needs verification |  |
| LL | left2 | lower area | [Deep Docks Bellway (Bellway_02)](#deep-docks-bellway-bellway02) | R | none |  | Needs verification |  |
| UR | right1 | upper area | [Deep Docks Spire Lower (Bone_East_03)](#deep-docks-spire-lower-boneeast03) | L | none |  | Needs verification |  |
| MR | right2 | lower area | [Deep Docks Map Shop Side Room (Dock_05)](#deep-docks-map-shop-side-room-dock05) | L | none |  | Needs verification |  |
| LR | right3 | lower area | [Deep Docks Lace Intro (Bone_East_12)](#deep-docks-lace-intro-boneeast12) | L | none |  | Needs verification |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LP | lower platform | lower area | upper area | flip switch to lower platform |  | Needs verification |  |
| LP | lower platform | upper area | lower area | none (falling) |  | Needs verification |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| map purchase deep docks | lower area | none |  | Needs verification |  | shakra shop |
| pin purchase vendor pins | lower area | none |  | Needs verification |  | shakra shop |
| switch to upper lower platform | lower area | none |  | Needs verification |  | NOT CURRENTLY RANDOMIZED |
| switch to lower lower platform | lower area | none |  | Needs verification |  | NOT CURRENTLY RANDOMIZED (doesn't currently really block anything since you can just jump above and fall down) |

### Deep Docks Map Shop Side Room (Dock_05)

**Game ID:** Dock_05

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Map Shop (Bone_East_01)](#deep-docks-map-shop-boneeast01) | MR | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

nothing to see here - just murder sleeping dudes

### Deep Docks Bellway (Bellway_02)

**Game ID:** Bellway_02

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Bellway Flea Rescue (Dock_16)](#deep-docks-bellway-flea-rescue-dock16) | R | break wall left |  | Needs verification |  |
| BB | door_fastTravelExit |  | [Bellway Menu](#bellway-menu) | DD | unlock bellway deep docks |  | Needs verification |  |
| R | right1 |  | [Deep Docks Map Shop (Bone_East_01)](#deep-docks-map-shop-boneeast01) | LL | none |  | Needs verification |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bellway rosary lock |  | rosaries 40 |  | Verified | lock |  |
| bellway deep docks |  | unlock bellway rosary lock |  |  | travel |  |

### Deep Docks Bellway Flea Rescue (Dock_16)

**Game ID:** Dock_16

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Deep Docks Bellway (Bellway_02)](#deep-docks-bellway-bellway02) | L | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue |  | ledge grab OR faydown cloak OR clawline OR silk soar |  | Verified |  |  |

#### Notes

ledge grab is the only real requirement in this room

### Deep Docks Lace Intro (Bone_East_12)

**Game ID:** Bone_East_12

**Contributors:** herounit

#### Subrooms

- left area
- switch platform
- boss arena
- right area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left area | [Deep Docks Map Shop (Bone_East_01)](#deep-docks-map-shop-boneeast01) | LR | none |  |  |  |
| R | right1 | right area | [Deep Docks Bellshrine (Bellshrine_05)](#deep-docks-bellshrine-bellshrine05) | L | none |  |  |  |
| F | bot1 | left area | [Deep Docks Forge (Room_Forge)](#deep-docks-forge-roomforge) | C | activate airlock up |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SP | lever platform jump | left area | switch platform | run OR dash OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR beast crest |  |  |  |
| SP | lever platform jump | switch platform | left area | none (falling) |  |  |  |
| BL | boss arena left | left area | boss arena | gate switch flipped |  |  |  |
| BL | boss arena left | boss arena | left area | gate switch flipped AND completed lace 1 boss fight |  |  |  |
| BR | boss arena right | boss arena | right area | completed lace 1 boss fight |  |  |  |
| BR | boss arena right | right area | boss arena | none |  | Needs verification |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| gate switch | switch platform | none |  |  |  |  |
| lace 1 boss fight | boss arena | none |  |  |  |  |
| lace 1 encounter spot | boss arena | none |  |  |  | This needs to be converted into a multi-location virtual event |

### Deep Docks Bellshrine (Bellshrine_05)

**Game ID:** Bellshrine_05

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Lace Intro (Bone_East_12)](#deep-docks-lace-intro-boneeast12) | R | none |  | Verified |  |
| R | right1 |  | [Far Fields Entrance East (Bone_East_02)](#far-fields-entrance-east-boneeast02) | L | ( bellshrinesanity off AND activate bellshrine switch )  OR ( bellshrinesanity on AND have bell deep docks ) |  | Verified | must keep in sync with other side |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bellshrine switch |  | none |  | Verified | switch |  |
| bench |  | activate bellshrine switch |  | Verified | bench |  |
| bell deep docks |  | activate bellshrine switch |  | Verified | collectible |  |

### Deep Docks Spire Lower (Bone_East_03)

**Game ID:** Bone_East_03

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 |  | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | F | hit blast rock, opens exit |  |  |  |
| L | left1 |  | [Deep Docks Map Shop (Bone_East_01)](#deep-docks-map-shop-boneeast01) | UR | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Is this still Deep Docks? (East) (Bone_East_04)

**Game ID:** Bone_East_04

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top2 |  | [Hunter's March Deep Docks Passage (Ant_05b)](#hunters-march-deep-docks-passage-ant05b) | RF | none |  |  |  |
| UR | right2 |  | ["Deep Docks" March Side Room (Bone_East_04c)](#deep-docks-march-side-room-boneeast04c) | L | silk soar OR cling grip OR faydown cloak |  |  |  |
| LR | right1 |  | [Far Fields Deep Docks Loopback (Bone_East_15)](#far-fields-deep-docks-loopback-boneeast15) | L | none |  |  |  |
| L | left1 |  | [Is this still Deep Docks? (West) (Bone_East_04b)](#is-this-still-deep-docks-west-boneeast04b) | R | wall must be destroyed from the other side |  |  |  |
| F | bot1 |  | [Deep Docks Spire Lower (Bone_East_03)](#deep-docks-spire-lower-boneeast03) | C | floor must be destroyed from the other side |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Is this still Deep Docks? (West) (Bone_East_04b)

**Game ID:** Bone_East_04b

**Contributors:** herounit

#### Subrooms

- side room
- ground
- upper level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | ground | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | L | attack blast rock, unblocks wall |  |  |  |
| C | top1 | upper level | [Hunter's March Deep Docks Passage (Ant_05b)](#hunters-march-deep-docks-passage-ant05b) | LF |  |  |  |  |
| L | left1 | ground | [Deep Docks Upper Spire (Bone_East_05)](#deep-docks-upper-spire-boneeast05) | R |  |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BW | break wall | side room | ground | break wall (left) |  |  |  |
| BW | break wall | ground | side room | none |  |  |  |
| BJ | big jump | ground | upper level | silk soar OR faydown cloak OR cling grip |  |  |  |
| BJ | big jump | upper level | ground | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| blast rock pathway opener | ground | blast rock |  |  |  |  |
| frayed rosary string deep docks | side room | none |  |  |  | MARKED AS ??? ON TRACKER |

### "Deep Docks" March Side Room (Bone_East_04c)

**Game ID:** Bone_East_04c

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | UR | none |  | Verified |  |
| SC | slab capture |  | [Slab Capture](#slab-capture) | DD | after get kidnapped |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| wardenfly |  | ( act 1 OR act 2 ) AND defeat THE bell beast boss fight |  |  | enemy | per the wiki |
| get kidnapped |  | after wardenfly |  |  | logic-point |  |

#### Notes

just a camp? no enemies? did we find bush girl here at some point?

### Deep Docks Upper Spire (Bone_East_05)

**Game ID:** Bone_East_05

**Contributors:** herounit

#### Subrooms

- flea platform
- spire
- right exit platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | spire | [Deep Docks Bench Shaft (Dock_01)](#deep-docks-bench-shaft-dock01) | UR | none (door switch is on this side) |  |  |  |
| R | right1 | right exit platform | [Is this still Deep Docks? (West) (Bone_East_04b)](#is-this-still-deep-docks-west-boneeast04b) | L | none |  |  | need to verify if silksoar works with magma bell |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SR | spire right | spire | right exit platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR (silk soar AND magma bell AND blue slot) OR beast crest |  |  | i did it exactly ONCE with shaman crest and couldn't do it again :( |
| SR | spire right | right exit platform | spire | none |  |  |  |
| PG | platform gaps | spire | flea platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR silk soar |  |  | Removed sharpdart - too many gaps in a row |
| PG | platform gaps | flea platform | spire | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue | flea platform | none |  |  |  |  |
| swift step | spire | none |  |  |  |  |
| door switch | spire | none |  |  |  |  |
| platform switch | flea platform | none |  |  |  |  |

### Deep Docks Forge (Room_Forge)

**Game ID:** Room_Forge

**Contributors:** herounit

#### Subrooms

- left area
- right area
- gauntlet
- forge daughter
- right exit platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | left area | [Deep Docks Lace Intro (Bone_East_12)](#deep-docks-lace-intro-boneeast12) | F | none |  | Verified | activate airlock |
| L | left1 | left area | [Deep Docks Lower West Shaft (Dock_04)](#deep-docks-lower-west-shaft-dock04) | UR | none |  | Verified |  |
| R | right1 | right exit platform | [Deep Docks Chains West (Dock_02)](#deep-docks-chains-west-dock02) | UL | unlock deep docks simple key lock |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | left area | forge daughter | activate gate switch |  | Verified |  |
| DS | door switch | forge daughter | left area | activate gate switch |  | Verified |  |
| GL | gauntlet left | left area | gauntlet | none |  | Verified |  |
| GL | gauntlet left | gauntlet | left area | complete gauntlet fight |  | Verified |  |
| GR | gauntlet right | right area | gauntlet | none |  | Verified |  |
| GR | gauntlet right | gauntlet | right area | complete gauntlet fight |  | Verified |  |
| GC | gauntlet upper | forge daughter | gauntlet | open airlock down |  | Verified |  |
| GC | gauntlet upper | gauntlet | forge daughter | complete gauntlet fight AND ( open airlock up AND ( ledge grab OR faydown cloak OR clawline OR scuttlebrace OR easy shaman pogo ) ) |  | Verified |  |
| RJ | running jump | right area | right exit platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR easy beast pogo |  | Verified |  |
| RJ | running jump | right exit platform | right area | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR easy beast pogo |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| deep docks shell shard cache 10 | left area | none |  | Verified | collectible | break wall |
| deep docks shard bundle 2 | left area | none |  | Verified | collectible |  |
| silkshot (forge daughter) | forge daughter | have ruined tool |  | Verified | collectible |  |
| sting shard | forge daughter | none |  | Verified | collectible | forge daughter shop |
| magma bell | forge daughter | none |  | Verified | collectible | forge daughter shop |
| crafting kit forge daughter | forge daughter | none |  | Verified | collectible | forge daughter shop |
| readable lore tablet | left area | open airlock left |  | Verified | lore |  |
| gate switch | forge daughter | none |  | Verified | switch |  |
| gauntlet fight | gauntlet | none |  | Verified | gauntlet |  |
| deep docks simple key lock | right exit platform | have simple key deep docks |  | Verified | lock |  |
| bench | forge daughter | none |  | Verified | bench |  |

### Deep Docks Lower West Shaft (Dock_04)

**Game ID:** Dock_04

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Church (Dock_06_Church)](#deep-docks-church-dock06church) | R | none |  |  |  |
| MR | right2 |  | [Deep Docks Spool East (Bone_East_13)](#deep-docks-spool-east-boneeast13) | L | none |  |  |  |
| UR | right1 |  | [Deep Docks Forge (Room_Forge)](#deep-docks-forge-roomforge) | L | none |  |  |  |
| LR | right3 |  | [Deep Docks Sauna (Dock_10)](#deep-docks-sauna-dock10) | L | activate door pressure plate IN deep docks sauna |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Deep Docks Spool East (Bone_East_13)

**Game ID:** Bone_East_13

**Contributors:** herounit

#### Subrooms

- the floor is lava
- spool fragment area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | the floor is lava | [Deep Docks Lower West Shaft (Dock_04)](#deep-docks-lower-west-shaft-dock04) | MR | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LP | lower platforms | the floor is lava | spool fragment area | platforms lowered OR faydown cloak OR (silk soar AND magma bell) | TODO |  | might have more options, hard to check after lever is flipped |
| LP | lower platforms | spool fragment area | the floor is lava | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| spool fragment deep docks | spool fragment area | none |  |  |  |  |
| shell shard cache deep docks 1 | the floor is lava | magma bell AND blue slot |  |  |  |  |
| shell shard cache deep docks 2 | the floor is lava | magma bell AND blue slot |  |  |  |  |
| shell shard cache deep docks 3 | the floor is lava | magma bell AND blue slot |  |  |  |  |
| platform lever | the floor is lava | none |  |  |  |  |

### Deep Docks Church (Dock_06_Church)

**Game ID:** Dock_06_Church

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Deep Docks Lower West Shaft (Dock_04)](#deep-docks-lower-west-shaft-dock04) | L | none |  |  |  |
| F | bot1 |  | [Abyss Escape (Abyss_09)](#abyss-escape-abyss09) | C |  | TODO |  | FROM THE ABYSS ESCAPE |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache deep docks 3 |  | none |  |  |  |  |
| rosary cache deep docks 4 |  | none |  |  |  |  |
| rosary cache deep docks 5 |  | none |  |  |  | MARKED AS ??? ON TRACKER |
| rosary cache deep docks 6 |  | none |  |  |  | MARKED AS ??? ON TRACKER |
| rosary chest |  | none |  |  |  | NOT YET RANDOMIZED |

#### Notes

might need to revise the subrooms later

### Deep Docks Chains West (Dock_02)

**Game ID:** Dock_02

**Contributors:** herounit

#### Subrooms

- main area
- middle crossing
- lower left exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | main area | [Deep Docks Forge (Room_Forge)](#deep-docks-forge-roomforge) | R | unlock deep docks simple key lock IN deep docks forge |  |  |  |
| LL | left2 | lower left exit | [Deep Docks Forebrothers (Dock_09)](#deep-docks-forebrothers-dock09) | R | none |  |  |  |
| UR | right1 | main area | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | UL | none |  |  |  |
| MR | right2 | middle crossing | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | ML | none |  |  |  |
| LR | right3 | middle crossing | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | LL | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BF | break floor | middle crossing | main area | cling grip AND clear breakable floor supports |  |  |  |
| BF | break floor | main area | middle crossing | clear breakable floor supports |  |  |  |
| LE | lower left exit | lower left exit | middle crossing | cling grip OR ( silk soar AND magma bell ) |  |  |  |
| LE | lower left exit | middle crossing | lower left exit |  |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shard bundle deep docks 1 | main area | none |  |  |  | MARKED AS ??? ON TRACKER can fall and grab the ledge to this one |
| shell shard cache deep docks 5 | main area | none |  |  |  | MARKED AS ??? ON TRACKER |
| flintstone journal collection point | main area | none |  |  |  |  |
| rosary cache deep docks 1 | main area | none |  |  |  | MARKED AS ??? ON TRACKER |
| rosary cache deep docks 2 | main area | none |  |  |  | MARKED AS ??? ON TRACKER |
| breakable floor supports | middle crossing | break wall up |  |  |  |  |

#### Notes

need to verify how this room works - thought it had some of the platforms go away, but not sure if that was in act 3

### Deep Docks Chains Flea Rescue (Dock_03d)

**Game ID:** Dock_03d

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 |  | [Deep Docks Chains Lower East (Dock_03c)](#deep-docks-chains-lower-east-dock03c) | LC | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Deep Docks Chains Center (Dock_02b)

**Game ID:** Dock_02b

**Contributors:** herounit

#### Subrooms

- upper left hallway
- upper chain platforms
- middle left exit area
- middle switch platform
- lower right area
- lower left area
- middle side room
- lower chain platforms

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | upper left hallway | [Deep Docks Chains West (Dock_02)](#deep-docks-chains-west-dock02) | UR | none |  |  |  |
| ML | left2 | middle left exit area | [Deep Docks Chains West (Dock_02)](#deep-docks-chains-west-dock02) | MR | none |  |  |  |
| LL | left3 | lower left area | [Deep Docks Chains West (Dock_02)](#deep-docks-chains-west-dock02) | LR | none |  |  |  |
| UR | right1 | upper chain platforms | [Deep Docks Chains Upper East (Dock_03)](#deep-docks-chains-upper-east-dock03) | L | break wall (from this side) |  |  | can't enter from the other side until this is broken |
| LR | right2 | lower right area | [Deep Docks Chains Lower East (Dock_03c)](#deep-docks-chains-lower-east-dock03c) | L | break wall (from other side) |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ME | middle exit to switch platform | middle left exit area | middle switch platform | cling grip OR ( silk soar AND magma bell AND blue slot ) |  |  |  |
| ME | middle exit to switch platform | middle switch platform | middle left exit area | none (falling) |  |  |  |
| LC | lower crossing | lower right area | lower left area | run OR dash OR drifter's cloak OR faydown cloak OR cling grip OR silk soar OR claw line OR sharp dart OR beast crest OR shaman crest |  |  |  |
| LC | lower crossing | lower left area | lower right area | none (jump) |  |  |  |
| P1 | lower to middle switch platform | lower left area | lower chain platforms | silk soar |  |  |  |
| P1 | lower to middle switch platform | lower chain platforms | lower left area | none (falling) |  |  |  |
| P2 | lower platforms to lower right area | lower chain platforms | lower right area | none (falling) |  |  |  |
| P2 | lower platforms to lower right area | lower right area | lower chain platforms | silk soar |  |  |  |
| C1 | middle chains to upper chains | middle switch platform | upper chain platforms | ceiling switch activated AND ( silk soar OR cling grip ) |  |  |  |
| C1 | middle chains to upper chains | upper chain platforms | middle switch platform | ceiling switch activated AND none (falling) |  |  |  |
| MS | middle switch platform to side room | middle switch platform | middle side room | none (falling) |  |  | one-way |
| MS | middle switch platform to side room | middle side room | middle switch platform | ceiling switch activated |  |  |  |
| MP | middle platform to lower chains | middle switch platform | lower chain platforms | none |  |  |  |
| MP | middle platform to lower chains | lower chain platforms | middle switch platform | none |  |  |  |
| DS | open door switch | upper left hallway | upper chain platforms | none (door switch is on this side) |  |  |  |
| DS | open door switch | upper chain platforms | upper left hallway | door switch flipped |  |  |  |
| S1 | side room to chain platforms | middle side room | lower chain platforms | none |  |  |  |
| S1 | side room to chain platforms | lower chain platforms | middle side room | none (falling) |  |  | I have a feeling this line is going to cause problems |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flintslate | upper left hallway | none |  |  |  |  |
| shell shard cache deep docks 6 | middle switch platform | none |  |  |  | MARKED AS ??? ON TRACKER |
| shell shard cache deep docks 7 | middle switch platform | none |  |  |  | MARKED AS ??? ON TRACKER |
| shell shard cache deep docks 8 | middle switch platform | none |  |  |  | MARKED AS ??? ON TRACKER |
| shell shard cache deep docks 9 | middle switch platform | none |  |  |  | MARKED AS ??? ON TRACKER |
| ceiling switch | middle switch platform | none |  |  |  | lowers middle chain platforms |
| door switch | upper left hallway | none |  |  |  |  |

#### Notes

the floor/lower half of this area is closed off initially

the switch to lower the middle chain section makes some of this logic difficult to reason about - but if you can reach the middle switch platform, there is no reason you can't reach all the stuff that unlocking the chains provides - might need to revise this for switch randomization

### Deep Docks Chains Upper East (Dock_03)

**Game ID:** Dock_03

**Contributors:** herounit

#### Subrooms

- upper left hallway
- chain platforms
- lower left chest room
- behind ring gate

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | upper left hallway | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | UR | none |  |  |  |
| F | bot1 | behind ring gate | [Deep Docks Chains Lower East (Dock_03c)](#deep-docks-chains-lower-east-dock03c) | RC | none |  |  |  |
| R | right1 | chain platforms | [Far Fields Deep Docks Backdoor (Dock_03b)](#far-fields-deep-docks-backdoor-dock03b) | L | break wall right |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | open door switch | upper left hallway | chain platforms | activate door switch |  |  |  |
| DS | open door switch | chain platforms | upper left hallway | activate door switch |  |  |  |
| BW | break wall | chain platforms | lower left chest room | break wall (from this side) |  |  |  |
| BW | break wall | lower left chest room | chain platforms | wall broken |  |  |  |
| RG | open ring gate | chain platforms | behind ring gate | unlock ring gate |  |  |  |
| RG | open ring gate | behind ring gate | chain platforms | unlock ring gate |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| craftmetal deep docks | lower left chest room | none |  |  |  | its freeeeee, right? :) |
| ring gate | chain platforms | clawline |  |  |  |  |
| door switch | upper left hallway | none |  |  |  |  |

#### Notes

the floor/lower half of this area is closed off initially

### Deep Docks Chains Lower East (Dock_03c)

**Game ID:** Dock_03c

**Contributors:** herounit

#### Subrooms

- upper chains
- spool fragment area
- lower chains
- middle chains
- upper lava platform
- lower lava platform
- gauntlet
- upper left of gauntlet

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RC | top2 | upper chains | [Deep Docks Chains Upper East (Dock_03)](#deep-docks-chains-upper-east-dock03) | F |  |  |  |  |
| LC | top1 | upper left of gauntlet | [Deep Docks Chains Flea Rescue (Dock_03d)](#deep-docks-chains-flea-rescue-dock03d) | F |  |  |  |  |
| L | left2 | lower lava platform | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | LR | none (hit blast rock on this side to open exit for both sides) |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SP | open spool door | spool fragment area | upper chains | open airlock door |  |  | one-way |
| SP | open spool door | upper chains | spool fragment area | can pogo  AND cling grip  AND ( clawline OR ( dash AND ( run OR sharpdart OR drifter's cloak ) ) ) |  | Needs verification | run or sharpdart or drifter's cloak  or clawline to get to the initial wall to cling grip. clawline or dash to get to pogo area. then free. |
| C1 | upper to middle chains | middle chains | upper chains | run OR dash OR drifter's cloak OR faydown cloak OR cling grip OR silk soar OR clawline OR sharpdart |  |  |  |
| C1 | upper to middle chains | upper chains | middle chains | none (falling) |  |  |  |
| C2 | lower to middle chains | lower chains | middle chains | silk soar OR cling grip OR faydown cloak |  |  |  |
| C2 | lower to middle chains | middle chains | lower chains | none (falling) |  |  |  |
| UC | upper clawline area | lower chains | upper lava platform | clawline |  |  |  |
| UC | upper clawline area | upper lava platform | lower chains | clawline OR drifter's cloak |  |  |  |
| LG | cross lava gap | lower chains | lower lava platform | clawline OR ( drifter's cloak AND faydown cloak ) |  | Needs verification | seems just out of reach of drifter's cloak and dash |
| LG | cross lava gap | lower lava platform | lower chains | clawline OR ( drifter's cloak AND faydown cloak ) |  |  |  |
| UL | upper lava platform to lower lava platform | upper lava platform | lower lava platform | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| silk spool deep docks 1 | spool fragment area | none |  |  |  |  |

### Deep Docks Forebrothers (Dock_09)

**Game ID:** Dock_09

**Contributors:** herounit

#### Subrooms

- right area
- boss area
- left area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right area | [Deep Docks Chains West (Dock_02)](#deep-docks-chains-west-dock02) | LL | none |  |  |  |
| L | left1 | left area | [Deep Docks Lower East Shaft (Dock_15)](#deep-docks-lower-east-shaft-dock15) | UR | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RB | right boss entrance | right area | boss area | none (starts fight) |  |  |  |
| RB | right boss entrance | boss area | right area | defeat forebrothers |  |  |  |
| LB | left boss entrance | left area | boss area | none |  |  | not sure if right side is blocked off by default - needs verification |
| LB | left boss entrance | boss area | left area | defeat forebrothers |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| forebrothers boss fight | boss area | none |  |  |  |  |
| rosary cache 1 | right area | none |  |  |  |  |
| rosary cache 2 | right area | none |  |  |  |  |

### Deep Docks Lower East Shaft (Dock_15)

**Game ID:** Dock_15

**Contributors:** herounit

#### Subrooms

- upper area
- the floor is lava
- lower left exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | upper area | [Deep Docks Sauna (Dock_10)](#deep-docks-sauna-dock10) | R | none |  |  |  |
| LL | left2 | upper area | [Deep Docks Memory Hole (Dock_13)](#deep-docks-memory-hole-dock13) | R | none |  |  |  |
| UR | right1 | upper area | [Deep Docks Forebrothers (Dock_09)](#deep-docks-forebrothers-dock09) | L | none |  |  |  |
| MR | right2 | upper area | [Deep Docks Silkeater Room (Dock_14)](#deep-docks-silkeater-room-dock14) | L | none |  |  |  |
| LR | right3 | the floor is lava | [Deep Docks Magma Slug Tunnels (Dock_11)](#deep-docks-magma-slug-tunnels-dock11) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CG | cling grip | upper area | the floor is lava | cling grip |  |  |  |
| CG | cling grip | the floor is lava | upper area | none (falling) |  |  |  |
| BW | breakable wall | upper area | lower left exit area | break wall |  |  |  |
| BW | breakable wall | lower left exit area | upper area | break wall |  |  |  |

#### Check Locations

No check locations defined.

### Deep Docks Sauna (Dock_10)

**Game ID:** Dock_10

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Lower West Shaft (Dock_04)](#deep-docks-lower-west-shaft-dock04) | LR | activate door pressure plate |  | Verified |  |
| R | right1 |  | [Deep Docks Lower East Shaft (Dock_15)](#deep-docks-lower-east-shaft-dock15) | UL | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bench |  | none |  | Verified | bench |  |
| door pressure plate |  | flip switch down |  | Verified | switch | have to break thing on top of pressure plate before you can step on it |

### Deep Docks Memory Hole (Dock_13)

**Game ID:** Dock_13

**Contributors:** herounit

#### Subrooms

- entrance
- pit of despair

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | entrance | [Deep Docks Lower East Shaft (Dock_15)](#deep-docks-lower-east-shaft-dock15) | LL |  |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TP | the pit | entrance | pit of despair | none (falling) |  |  | this is possible but a massive pain, also a one-way softlock potential |
| TP | the pit | pit of despair | entrance | cling grip |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| memory locket deep docks | pit of despair | none |  |  |  |  |

### Deep Docks Silkeater Room (Dock_14)

**Game ID:** Dock_14

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Lower East Shaft (Dock_15)](#deep-docks-lower-east-shaft-dock15) | MR | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| silkeater deep socks |  | none |  |  |  |  |

### Deep Docks Magma Slug Tunnels (Dock_11)

**Game ID:** Dock_11

**Contributors:** herounit

#### Subrooms

- upper far left
- upper mid left
- upper mid right
- upper far right
- worst spot in the game
- check alcove
- right tunnel 1
- right tunnel 2
- right tunnel 3

- **upper far right:** space between right door and transition

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | upper far left | [Deep Docks Lower East Shaft (Dock_15)](#deep-docks-lower-east-shaft-dock15) | LR | none |  | Verified |  |
| R | right1 | upper far right | [Deep Docks Diving Bell Room (Dock_12)](#deep-docks-diving-bell-room-dock12) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LD1 | left doorway 1 | upper far left | upper mid left | activate left door switch |  | Verified |  |
| LD1 | left doorway 1 | upper mid left | upper far left | activate left door switch |  | Verified |  |
| LD2 | left doorway 2 | upper mid right | upper mid left | activate middle door switch |  | Verified |  |
| LD2 | left doorway 2 | upper mid left | upper mid right | activate middle door switch |  | Verified |  |
| RD | right doorway | upper mid right | upper far right | activate right door switch |  | Verified |  |
| RD | right doorway | upper far right | upper mid right | activate right door switch |  | Verified |  |
| LT | left tunnel | upper far left | worst spot in the game | spike pogo OR run  OR dash OR drifters OR faydown OR cling grip OR clawline OR sharpdart |  | Verified | Can technically be done with no items if you can kill the magma slug on the wall in this tunnel. But unlikely to be able to kill it without any of this kit |
| LT | left tunnel | worst spot in the game | upper far left | cling grip OR medium scuttlebrace OR ( faydown AND magma bell AND silk soar ) |  | Verified | scuttlebrace difficulty for  slugs/timing/damage/etc. |
| AA | access alcove | worst spot in the game | check alcove | clear check alcove blast rock blockade |  | Verified |  |
| AA | access alcove | check alcove | worst spot in the game | clear check alcove blast rock blockade |  | Verified |  |
| RV1 | right vertical 1 | worst spot in the game | right tunnel 1 | cling grip  OR medium  scuttlebrace OR ( magma bell AND silk soar ) |  | Verified | scuttlebrace difficulty for  slugs/timing/damage/etc. |
| RV1 | right vertical 1 | right tunnel 1 | worst spot in the game | none (falling) |  | Verified |  |
| RB1 | right blast 1 | right tunnel 1 | right tunnel 2 | clear right tunnel blast rock blockade 1 |  | Verified |  |
| RB1 | right blast 1 | right tunnel 2 | right tunnel 1 | clear right tunnel blast rock blockade 1 |  | Verified |  |
| RB2 | right blast 2 | right tunnel 2 | right tunnel 3 | clear right tunnel blast rock blockade 2 AND (  cling grip  OR ( faydown AND ledge grab ) OR easy scuttlebrace OR easy hazard respawn ) |  | Verified | blast rock requires dropping down above spikes to hit it - free after blast rock is cleared |
| RB2 | right blast 2 | right tunnel 3 | right tunnel 2 | clear right tunnel blast rock blockade 2 AND ( cling grip OR scuttlebrace OR ( faydown AND ledge grab ) ) |  | Verified |  |
| RV2 | right vertical 2 | right tunnel 3 | upper mid right | cling grip OR medium scuttlebrace OR ( magma bell AND silk soar ) |  | Verified | scuttlebrace difficulty for  slugs/timing/damage/etc. |
| RV2 | right vertical 2 | upper mid right | right tunnel 3 | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| left door switch | upper mid left | flip switch up |  | Verified | switch |  |
| middle door switch | upper mid right | flip switch up |  | Verified | switch |  |
| right door switch | upper mid right | flip switch up |  | Verified | switch | unlocks the right exit |
| right tunnel blast rock blockade 1 | right tunnel 1 | break blast rock right |  | Verified | blockade |  |
| right tunnel blast rock blockade 2 | right tunnel 2 | break blast rock right |  | Verified | blockade |  |
| check alcove blast rock blockade | worst spot in the game | break blast rock right |  | Verified | blockade |  |
| beast shard deep docks | check alcove | none |  | Verified | collectible |  |

### Deep Docks Diving Bell Room (Dock_12)

**Game ID:** Dock_12

**Contributors:** herounit & Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 |  | [Deep Docks Diving Bell Interior (Room_Diving_Bell)](#deep-docks-diving-bell-interior-roomdivingbell) | L | unlock diving bell lock |  | Verified |  |
| L | left1 |  | [Deep Docks Magma Slug Tunnels (Dock_11)](#deep-docks-magma-slug-tunnels-dock11) | R | none |  | Verified | transition is not blocked by door in next room |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| diving bell lock |  | have diving bell key |  | Verified | lock |  |

### Deep Docks Diving Bell Interior (Room_Diving_Bell)

**Game ID:** Room_Diving_Bell

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Diving Bell Room (Dock_12)](#deep-docks-diving-bell-room-dock12) | D | none |  | Verified |  |
| D | door_cinematicEnd |  | [Abyss Diving Bell Fixed (Room_Diving_Bell_Abyss_Fixed)](#abyss-diving-bell-fixed-roomdivingbellabyssfixed) | B | ACT3 AND Mallow is in control room above |  | Needs verification |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

## Far Fields

### Far Fields Entrance East (Bone_East_02)

**Game ID:** Bone_East_02

**Contributors:** herounit

#### Subrooms

- deep docks platform
- main pathway
- ceiling exit platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | main pathway | [Far Fields Deep Docks Loopback (Bone_East_15)](#far-fields-deep-docks-loopback-boneeast15) | F | silk soar OR faydown cloak OR cling grip |  | Verified | car barely make it up with faydown cloak |
| L | left1 | deep docks platform | [Deep Docks Bellshrine (Bellshrine_05)](#deep-docks-bellshrine-bellshrine05) | R | ( bellshrinesanity off AND activate bellshrine switch IN deep docks bellshrine )  OR ( bellshrinesanity on AND have bell deep docks ) |  | Verified | must keep in sync with other side |
| R | right1 | main pathway | [Far Fields Entrance West (Bone_East_02b)](#far-fields-entrance-west-boneeast02b) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RJ | running jump | deep docks platform | main pathway | run OR faydown cloak OR sharpdart OR clawline OR ( ledge grab AND ( dash OR drifter's cloak ) ) |  | Verified | couldn't get beast crest pogo to work, but might be possible |
| RJ | running jump | main pathway | deep docks platform | none |  | Verified |  |
| V1 | vertical 1 | main pathway | ceiling exit platform | silk soar OR faydown cloak OR clawline OR ( ledge grab AND ( run OR dash OR drifter's cloak  OR sharpdart ) ) |  | Verified |  |
| V1 | vertical 1 | ceiling exit platform | main pathway | none (falling) |  | Verified |  |

#### Check Locations

No check locations defined.

### Far Fields Entrance West (Bone_East_02b)

**Game ID:** Bone_East_02b

**Contributors:** herounit

#### Subrooms

- lower walkway
- upper right platforms
- lower right exit platform
- upper left platforms
- check alcove

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | upper right platforms | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | L1 | none |  | Verified |  |
| LR | right2 | lower right exit platform | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | L2 | none |  | Verified |  |
| L | left1 | lower walkway | [Far Fields Entrance East (Bone_East_02)](#far-fields-entrance-east-boneeast02) | R | none |  | Verified |  |
| C | top3 | upper left platforms | [Far Fields Fort Lower Passage (Bone_East_16)](#far-fields-fort-lower-passage-boneeast16) | F | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | lower walkway | upper right platforms | run OR clawline OR ( ledge grab AND ( dash OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak ) ) |  | Verified |  |
| V1 | vertical 1 | upper right platforms | lower walkway | none (falling) |  | Verified |  |
| LC | lava crossing | lower walkway | lower right exit platform | run OR dash OR clawline OR sharpdart OR cling grip OR silk soar OR drifter's cloak  OR faydown cloak |  | Verified |  |
| LC | lava crossing | lower right exit platform | lower walkway | run OR dash OR clawline OR sharpdart OR cling grip OR silk soar OR drifter's cloak  OR faydown cloak |  | Verified |  |
| V2 | vertical 2 | lower walkway | upper left platforms | silk soar |  | Verified |  |
| V2 | vertical 2 | upper left platforms | lower walkway | none (falling) |  | Verified |  |
| UC | upper crossing | upper right platforms | upper left platforms | run OR dash OR clawline OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  | Verified |  |
| UC | upper crossing | upper left platforms | upper right platforms | run OR dash OR clawline OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  | Verified |  |
| V3 | vertical 3 | lower right exit platform | upper right platforms | cling grip OR silk soar |  | Verified |  |
| V3 | vertical 3 | upper right platforms | lower right exit platform | none (falling) |  | Verified |  |
| AC | alcove access | lower walkway | check alcove | ledge grab OR silk soar OR faydown cloak OR clawline OR easy shaman pogo |  | Verified | i love shaman pogo |
| AC | alcove access | check alcove | lower walkway | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache far fields 1 | check alcove | none |  | Verified | collectible |  |

### Far Fields Fort Lower Passage (Bone_East_16)

**Game ID:** Bone_East_16

**Contributors:** herounit

#### Subrooms

- the pit of despair
- the highest highs

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | the pit of despair | [Far Fields Entrance West (Bone_East_02b)](#far-fields-entrance-west-boneeast02b) | C | none |  | Verified |  |
| R | right1 | the highest highs | [Far Fields Fort Flea Rescue (Bone_East_17b)](#far-fields-fort-flea-rescue-boneeast17b) | L | none (break wall) |  | Verified | can be broken from either side |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MJ | massive jump | the pit of despair | the highest highs | ledge grab OR clawline OR faydown cloak OR silk soar OR scuttlebrace OR cling grip OR easy shaman pogo |  | Verified |  |
| MJ | massive jump | the highest highs | the pit of despair | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 11 | the highest highs | none |  | Verified | collectible |  |
| rosary cache far fields 12 | the highest highs | none |  | Verified | collectible |  |
| rosary cache far fields 13 | the highest highs | none |  | Verified | collectible |  |

### Far Fields Fort Flea Rescue (Bone_East_17b)

**Game ID:** Bone_East_17b

**Contributors:** herounit

#### Subrooms

- left exit area
- ceiling exit area
- flea rescue area
- camp

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Far Fields Fort Lower Passage (Bone_East_16)](#far-fields-fort-lower-passage-boneeast16) | R | none |  | Verified | break wall |
| C | top1 | ceiling exit area | [Far Fields Fort Upper Passage (Bone_East_17)](#far-fields-fort-upper-passage-boneeast17) | B | none |  | Verified | break wall (can be broken from either side) |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S1 | shaft 1 | left exit area | flea rescue area | ledge grab OR faydown cloak OR silk soar OR clawline |  | Verified |  |
| S1 | shaft 1 | flea rescue area | left exit area | none (falling) |  | Verified |  |
| S2 | shaft 2 | left exit area | camp | ledge grab OR faydown cloak OR silk soar OR clawline |  | Verified |  |
| S2 | shaft 2 | camp | left exit area | none (falling) |  | Verified |  |
| FA | flea ascend | flea rescue area | ceiling exit area | ledge grab OR faydown cloak OR silk soar OR clawline |  | Verified |  |
| FA | flea ascend | ceiling exit area | flea rescue area | none (falling) |  | Verified |  |
| CA | camp ascend | camp | ceiling exit area | ledge grab OR faydown cloak OR silk soar OR clawline OR cling grip |  | Verified |  |
| CA | camp ascend | ceiling exit area | camp | none (falling) |  | Verified |  |
| MC | middling crossing | camp | flea rescue area | ledge grab OR run OR dash OR sharpdart OR drifter's cloak OR faydown cloak OR cling grip OR silk soar OR scuttlebrace |  | Verified |  |
| MC | middling crossing | flea rescue area | camp | ledge grab OR run OR sharpdart OR clawline OR faydown cloak OR cling grip OR silk soar OR scuttlebrace |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue | flea rescue area | none |  | Verified | collectible | break cage |
| rosary cache far fields 16 | camp | none |  | Verified | collectible |  |
| rosary cache far fields 17 | camp | none |  | Verified | collectible |  |

#### Notes

this had no subrooms before ledge grab...

### Far Fields Fort Upper Passage (Bone_East_17)

**Game ID:** Bone_East_17

**Contributors:** herounit

#### Subrooms

- left exit area
- right exit area
- main area
- check niche

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Far Fields Deep Docks Loopback (Bone_East_15)](#far-fields-deep-docks-loopback-boneeast15) | R | none |  | Verified |  |
| B | bot1 | main area | [Far Fields Fort Flea Rescue (Bone_East_17b)](#far-fields-fort-flea-rescue-boneeast17b) | C | none |  | Verified |  |
| R | right1 | right exit area | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | L4 | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LP | lower platforms | left exit area | main area | activate lower platform switch |  | Verified |  |
| LP | lower platforms | main area | left exit area | activate lower platform switch |  | Verified |  |
| RJ | running jump | main area | right exit area | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  | Verified | silk soar doesn't get enough horizontal distance without one of the skills that just gets you there |
| RJ | running jump | right exit area | main area | none (falling) |  | Verified |  |
| AC | access niche | main area | check niche | ledge grab OR run OR dash OR silk soar OR drifter's cloak OR faydown cloak OR cling grip OR clawline OR sharpdart OR scuttlebrace OR easy beast pogo OR easy shaman pogo |  | Verified |  |
| AC | access niche | check niche | main area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 14 | check niche | none |  | Verified | collectible |  |
| rosary cache far fields 15 | main area | none |  | Verified | collectible |  |
| lower platform switch | left exit area | flip switch up |  | Verified | switch |  |
| rosary chest | left exit area | none |  | Verified | collectible | NOT YET RANDOMIZED |

### Far Fields Wind Shaft (Bone_East_07)

**Game ID:** Bone_East_07

**Contributors:** herounit

#### Subrooms

- upper crossing
- rosary cache spot
- R4 left
- R4 area
- below R4
- mort corpse platform
- middle crossing
- L2 area
- R5 area
- R3 area
- left almost bottom
- the bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | upper crossing | [Far Fields Upper Shaft (Bone_East_11)](#far-fields-upper-shaft-boneeast11) | F | activate lower gate lever IN far fields upper shaft |  | Verified |  |
| R1 | right1 | upper crossing | [Far Fields Pilgrim's Rest (Bone_East_10)](#far-fields-pilgrims-rest-boneeast10) | LL | none |  | Verified |  |
| R4 | right4 | R4 area | [Far Fields Target Practice (Bone_East_22)](#far-fields-target-practice-boneeast22) | L | none |  | Verified |  |
| R2 | right2 | middle crossing | [Far Fields Bellway (Bellway_03)](#far-fields-bellway-bellway03) | L | none |  | Verified |  |
| R5 | right5 | R5 area | [Far Fields Map Shop (Bone_East_21)](#far-fields-map-shop-boneeast21) | L | none |  | Verified |  |
| R3 | right3 | R3 area | [Far Fields Chorus (Bone_East_08)](#far-fields-chorus-boneeast08) | L | none |  | Verified |  |
| L4 | left4 | upper crossing | [Far Fields Fort Upper Passage (Bone_East_17)](#far-fields-fort-upper-passage-boneeast17) | R | none |  | Verified |  |
| L1 | left1 | middle crossing | [Far Fields Entrance West (Bone_East_02b)](#far-fields-entrance-west-boneeast02b) | UR | none |  | Verified |  |
| L2 | left2 | L2 area | [Far Fields Entrance West (Bone_East_02b)](#far-fields-entrance-west-boneeast02b) | LR | none |  | Verified |  |
| L3 | left3 | the bottom | [Far Fields Deep Docks Backdoor (Dock_03b)](#far-fields-deep-docks-backdoor-dock03b) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ABA | almost bottom ascent | the bottom | left almost bottom | ledge grab OR faydown cloak OR scuttlebrace OR silk soar OR drifter's cloak OR easy shaman pogo |  | Verified |  |
| ABA | almost bottom ascent | left almost bottom | the bottom | none (falling) |  | Verified |  |
| G1 | gap 1 | left almost bottom | R3 area | run OR dash OR easy beast pogo OR drifter's cloak OR faydown cloak OR cling grip OR silk soar OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| G1 | gap 1 | R3 area | left almost bottom | ledge grab OR run OR dash OR easy beast pogo OR drifter's cloak OR faydown cloak OR cling grip OR silk soar OR clawline OR sharpdart OR scuttlebrace |  | Verified | slightly lower, so ledge grab works here |
| F1 | fall 1 | R3 area | the bottom | none (falling) |  | Verified |  |
| R5A | R5 ascent | left almost bottom | R5 area | ledge grab OR easy shaman pogo OR drifter's cloak OR faydown cloak OR clawline OR silk soar |  | Verified |  |
| R5A | R5 ascent | R5 area | left almost bottom | none (falling) |  | Verified |  |
| L2C | L2 crossing | R5 area | L2 area | run OR dash OR easy beast pogo OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| L2C | L2 crossing | L2 area | R5 area | ledge grab OR run OR dash OR easy beast pogo OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| F2 | fall 2 | L2 area | left almost bottom | none (falling) |  | Verified |  |
| LMA | left middle ascent | L2 area | middle crossing | drifter's cloak OR silk soar |  | Verified |  |
| LMA | left middle ascent | middle crossing | L2 area | none (falling) |  | Verified |  |
| RMA | right middle ascent | R5 area | middle crossing | silk soar OR ( break blast rock down AND drifter's cloak ) |  | Verified |  |
| RMA | right middle ascent | middle crossing | R5 area | none (falling) |  | Verified |  |
| BR4 | below R4 ascent | middle crossing | below R4 | silk soar OR ( drifter's cloak AND break blast rock down ) OR ( ( cling grip OR scuttlebrace ) AND ( faydown cloak OR clawline ) ) |  | Verified |  |
| BR4 | below R4 ascent | below R4 | middle crossing | none (falling) |  | Verified |  |
| R4A | R4 ascent | below R4 | R4 left | break blast rock up AND ( silk soar OR drifter's cloak  ) |  | Verified |  |
| R4A | R4 ascent | R4 left | below R4 | break blast rock down |  | Verified |  |
| R4C | R4C crossing | R4 left | R4 area | run OR dash OR easy beast pogo OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR scuttlebrace |  | Verified | this only applies if you break the right blast rock, but going with most restrictive solution |
| R4C | R4C crossing | R4 area | R4 left | run OR dash OR easy beast pogo OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR scuttlebrace |  | Verified | this only applies if you break the right blast rock, but going with most restrictive solution |
| BPA | belt platform access | below R4 | mort corpse platform | none (falling) |  | Verified | no point in scaffolding the reverse because this is a logical dead-end |
| RUA | right upper ascent | R4 area | upper crossing | drifter's cloak OR ( faydown cloak AND cling grip ) |  | Verified | take the wind stream or scale the wall |
| RUA | right upper ascent | upper crossing | R4 area | none (falling) |  | Verified |  |
| RCA | rosary cache ascent | R4 left | rosary cache spot | ledge grab OR drifter's cloak OR faydown cloak OR silk soar |  | Verified |  |
| RCA | rosary cache ascent | rosary cache spot | R4 left | none (falling) |  | Verified |  |
| C2U | cache to upper crossing | rosary cache spot | upper crossing | ledge grab OR drifter's cloak OR faydown cloak OR clawline OR scuttlebrace |  | Verified |  |
| C2U | cache to upper crossing | upper crossing | rosary cache spot | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 1 | rosary cache spot | none |  | Verified | collectible |  |
| weighted belt | mort corpse platform | act 3 |  | Verified | collectible | according to the wiki you can either buy it from pilgrim's rest in act 1/2 OR you can grab it from mort's corpse here in act 3 |

### Far Fields Upper Shaft (Bone_East_11)

**Game ID:** Bone_East_11

**Contributors:** herounit

#### Subrooms

- the bottom
- above middle gate
- hunters march bridge
- top wind tunnel
- left march bridge room
- right march bridge room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | top wind tunnel | [Greymoor West Bellshrine Room  (Greymoor_01)](#greymoor-west-bellshrine-room-greymoor01) | D | drifter's cloak |  | Verified | silk soar does not work |
| UR | right1 | right march bridge room | [Far Fields Deep Entrance (Bone_East_24)](#far-fields-deep-entrance-boneeast24) | L | none |  | Verified |  |
| L | left1 | left march bridge room | [Hunter's March Deep Entrance (Ant_09)](#hunters-march-deep-entrance-ant09) | R | none |  | Verified |  |
| LR | right2 | the bottom | [Far Fields Pilgrim's Rest (Bone_East_10)](#far-fields-pilgrims-rest-boneeast10) | UL | none |  | Verified |  |
| F | bot1 | the bottom | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | C | none (activate lower gate lever) |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | the bottom | above middle gate | drifter's cloak OR silk soar |  | Verified |  |
| V1 | vertical 1 | above middle gate | the bottom | none (falling) |  | Verified |  |
| V2 | vertical 2 | above middle gate | hunters march bridge | drifter's cloak OR silk soar |  | Verified |  |
| V2 | vertical 2 | hunters march bridge | above middle gate | none (falling) |  | Verified |  |
| V3 | vertical 3 | hunters march bridge | top wind tunnel | silk soar OR ( drifter's cloak AND NOT activate hunter's march bridge lever ) | TODO | Verified | the bridge blocks the wind stream - not sure exactly how this should be represented |
| V3 | vertical 3 | top wind tunnel | hunters march bridge | none (falling) |  | Verified |  |
| LB | left bridge crossing | left march bridge room | hunters march bridge | activate hunter's march bridge lever |  | Verified |  |
| LB | left bridge crossing | hunters march bridge | left march bridge room | activate hunter's march bridge lever |  | Verified |  |
| RB | right bridge crossing | hunters march bridge | right march bridge room | activate hunter's march bridge lever |  | Verified |  |
| RB | right bridge crossing | right march bridge room | hunters march bridge | activate hunter's march bridge lever |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| lower gate lever | the bottom | flip switch down |  | Verified | switch |  |
| middle gate lever | above middle gate | flip switch down |  | Verified | switch |  |
| hunter's march bridge lever | left march bridge room | flip switch down |  | Verified | switch |  |
| greymoor floor blockade | top wind tunnel | none (opens once traveled through) |  | Verified | blockade |  |

### Far Fields Pilgrim's Rest (Bone_East_10)

**Game ID:** Bone_East_10

**Contributors:** herounit

#### Subrooms

- main floor
- upper left exit
- upper right exit
- lower right exit
- middle upper platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | upper left exit | [Far Fields Upper Shaft (Bone_East_11)](#far-fields-upper-shaft-boneeast11) | LR | none |  | Verified |  |
| LL | left2 | main floor | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | R1 | none |  | Verified |  |
| D | door1 | main floor | [Far Fields Pilgrim's Rest Shop (Bone_East_10_Room)](#far-fields-pilgrims-rest-shop-boneeast10room) | R | none (rosary gated) |  | Verified |  |
| UR | right1 | upper right exit | [Far Fields Pilgrim's Rest Deep Passage (Bone_East_18c)](#far-fields-pilgrims-rest-deep-passage-boneeast18c) | L | clear blast rock exit block IN hunters march pilgrims rest deep passage |  | Verified |  |
| LR | right2 | lower right exit | [Far Fields Pilgrim's Rest Church (Bone_East_10_Church)](#far-fields-pilgrims-rest-church-boneeast10church) | L | activate door switch IN far fields pilgrims rest church |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | main floor | upper left exit | silk soar OR faydown cloak |  | Verified | platform can be dropped to make it only ledge grab after middle platform access is granted |
| V1 | vertical 1 | upper left exit | main floor | none (falling) |  | Verified |  |
| G1 | gap 1 | middle upper platform | upper left exit | run OR ledge grab OR clawline OR faydown cloak OR drifter's cloak OR  clawline OR sharpdart |  | Verified | based on after platform falls |
| V2 | vertical 2 | main floor | lower right exit | ledge grab OR faydown cloak OR silk soar OR scuttlebrace OR clawline OR easy shaman pogo |  | Verified |  |
| V2 | vertical 2 | lower right exit | main floor | none (falling) |  | Verified |  |
| V3 | vertical 3 | main floor | upper right exit | ledge grab OR faydown cloak OR silk soar OR scuttlebrace |  | Verified |  |
| V3 | vertical 3 | upper right exit | main floor | none (falling) |  | Verified |  |
| G2 | gap 2 | upper right exit | middle upper platform | run OR dash OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| G2 | gap 2 | middle upper platform | upper right exit | none (jump) |  | Verified |  |
| V4 | vertical 4 | main floor | middle upper platform | silk soar |  | Verified |  |
| V4 | vertical 4 | middle upper platform | main floor | none (falling) |  | Verified |  |

#### Check Locations

No check locations defined.

### Far Fields Pilgrim's Rest Church (Bone_East_10_Church)

**Game ID:** Bone_East_10_Church

**Contributors:** herounit

#### Subrooms

- main floor
- flea rescue area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | main floor | [Far Fields Pinstress Attic (Bone_East_09b)](#far-fields-pinstress-attic-boneeast09b) | C | none |  | Verified |  |
| L | left1 | main floor | [Far Fields Pilgrim's Rest (Bone_East_10)](#far-fields-pilgrims-rest-boneeast10) | LR | activate door switch |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CG | climb 1 | main floor | flea rescue area | cling grip OR scuttlebrace OR silk soar OR ( faydown cloak AND ledge grab ) |  | Verified |  |
| CG | climb 1 | flea rescue area | main floor | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea pilgrims rest | flea rescue area | none |  | Verified | collectible |  |
| rhinogrund miniboss fight | main floor | none (fite me) |  | Verified | miniboss | can skip by leaving and coming back |
| door switch | main floor | none |  | Verified | switch |  |
| beast shard | main floor | defeat rhinogrund miniboss fight |  | Verified | collectible | this can be missed - if the switch is flipped and you leave the room (or die) without defeating the rhinogrund or collecting the beast shard, they become unavailable |

### Far Fields Pilgrim's Rest Shop (Bone_East_10_Room)

**Game ID:** Bone_East_10_Room

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Far Fields Pilgrim's Rest (Bone_East_10)](#far-fields-pilgrims-rest-boneeast10) | D | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| weighted belt |  | none (shop) |  | Verified | collectible | POSITION OF WEIGHTED BELT DEPENDS ON ACT - CAN BUY IT HERE IN ACT 1 AND 2 BUT HAVE TO GRAB IT FROM ACT 3 IN THE WIND SHAFT |
| memory locket pilgrims rest shop |  | none (shop) |  | Verified | collectible | shop |
| tool pouch pilgrim's rest shop |  | none (shop) |  | Verified | collectible | NOT RANDOMIZED AS OF v0.4.2 |
| pilgrims rest supplies wish granted |  | complete THE pilgrims rest supplies wish promised |  | Verified | collectible |  |

### Far Fields Chorus (Bone_East_08)

**Game ID:** Bone_East_08

**Contributors:** herounit

#### Subrooms

- left exit area
- lower left side
- upper left alcove
- boss arena
- upper right alcove
- lower right side

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | R3 | none |  | Verified |  |
| R | right1 | lower right side | [Far Fields Pinstress Room (Bone_East_09)](#far-fields-pinstress-room-boneeast09) | LL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | lower left side | left exit area | silk soar OR drifter's cloak |  | Verified |  |
| V1 | vertical 1 | left exit area | lower left side | none (falling) |  | Verified |  |
| G1 | gap 1 | left exit area | upper left alcove | drifter's cloak OR clawline |  | Verified | one way only |
| V2 | vertical 2 | lower left side | upper left alcove | silk soar OR drifter's cloak |  | Verified |  |
| V2 | vertical 2 | upper left alcove | lower left side | none (falling) |  | Verified |  |
| BL | boss left entrance | lower left side | boss arena | none |  | Verified | no boss defeat passthrough requirement |
| BL | boss left entrance | boss arena | lower left side | none |  | Verified |  |
| BR | boss right entrance | lower right side | boss arena | none |  | Verified | no boss defeat passthrough requirement |
| BR | boss right entrance | boss arena | lower right side | none |  | Verified |  |
| V3 | vertical 3 | lower right side | upper right alcove | drifter's cloak OR ( silk soar AND ( scuttlebrace OR ( cling grip AND ( faydown cloak OR dash OR clawline OR sharpdart ) ) ) ) |  | Verified |  |
| V3 | vertical 3 | upper right alcove | lower right side | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| fourth chorus boss fight | boss arena | complete THE flexible spines wish granted |  | Verified | boss |  |
| rosary cache far fields 2 | upper left alcove | none |  | Verified | collectible |  |
| silk | upper right alcove | none |  | Verified | resource | silk webs |
| savage beastfly 2 boss fight | boss arena | complete THE savage beastfly wish promised |  | Verified | boss |  |
| Horn Fragment | boss arena | defeat savage beastfly 2 boss fight |  | Verified | collectible |  |

### Far Fields Pinstress Attic (Bone_East_09b)

**Game ID:** Bone_East_09b

**Contributors:** herounit

#### Subrooms

- bottom left area
- upper right area
- ceiling exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | bottom left area | [Far Fields Bellway (Bellway_03)](#far-fields-bellway-bellway03) | R | none |  | Verified |  |
| F | bot1 | bottom left area | [Far Fields Pinstress Room (Bone_East_09)](#far-fields-pinstress-room-boneeast09) | T | clear blast rock exit block |  | Verified |  |
| C | top1 | ceiling exit | [Far Fields Pilgrim's Rest Church (Bone_East_10_Church)](#far-fields-pilgrims-rest-church-boneeast10church) | F | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| D1 | drift passage 1 | bottom left area | upper right area | drifter's cloak OR ( silk soar AND faydown cloak AND clawline ) |  | Verified |  |
| D1 | drift passage 1 | upper right area | bottom left area | drifter's cloak OR clawline |  | Verified |  |
| D2 | drift passage 2 | upper right area | ceiling exit | drifter's cloak AND ( dash OR clawline OR sharpdart ) AND cling grip |  | Verified | one way - might need some further validation |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far field 3 | upper right area | none |  | Verified | collectible |  |
| rosary cache far field 4 | upper right area | none |  | Verified | collectible |  |
| blast rock exit block | bottom left area | break blast rock down |  | Verified | blockade |  |

### Far Fields Pinstress Room (Bone_East_09)

**Game ID:** Bone_East_09

**Contributors:** herounit

#### Subrooms

- ceiling exit area
- ceiling wind tunnel
- upper left exit area
- lower left exit area
- upper right exit area
- lower right exit area
- pinstress hut platform
- lava basin

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | ceiling exit area | [Far Fields Pinstress Attic (Bone_East_09b)](#far-fields-pinstress-attic-boneeast09b) | F | clear blast rock exit block IN far fields pinstress attic |  | Verified |  |
| UL | left3 | upper left exit area | [Far Fields Pinstress Mask Shard (Bone_East_20)](#far-fields-pinstress-mask-shard-boneeast20) | R | none |  | Verified |  |
| LR | right2 | lower right exit area | [Far Fields Skull Room West (Bone_East_14)](#far-fields-skull-room-west-boneeast14) | LL | none |  | Verified |  |
| LL | left2 | lower left exit area | [Far Fields Chorus (Bone_East_08)](#far-fields-chorus-boneeast08) | R | none |  | Verified |  |
| UR | right1 | upper right exit area | [Far Fields Skull Room West (Bone_East_14)](#far-fields-skull-room-west-boneeast14) | UL | none |  | Verified |  |
| D | door1 | pinstress hut platform | [Far Fields Pinstress Hut Interior (Bone_East_Umbrella)](#far-fields-pinstress-hut-interior-boneeastumbrella) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LBA | left basin access | lower left exit area | lava basin | none (falling) |  | Verified |  |
| LBA | left basin access | lava basin | lower left exit area | ledge grab OR drifter's cloak OR faydown cloak OR silk soar OR scuttlebrace OR easy shaman pogo |  | Verified |  |
| RBA | right basin access | upper right exit area | lava basin | none |  | Verified | actually none both ways - not even ledge grab |
| RBA | right basin access | lava basin | upper right exit area | none |  | Verified | actually none both ways - not even ledge grab |
| LRA | lower right access | upper right exit area | lower right exit area | none (falling) |  | Verified |  |
| LRA | lower right access | lower right exit area | upper right exit area | cling grip OR drifter's cloak |  | Verified |  |
| RHA | right hut access | upper right exit area | pinstress hut platform | ledge grab OR drifter's cloak OR faydown cloak OR cling grip OR scuttlebrace OR clawline |  | Verified |  |
| RHA | right hut access | pinstress hut platform | upper right exit area | none (falling) |  | Verified |  |
| HA | hut ascend | lava basin | pinstress hut platform | drifter's cloak OR silk soar |  | Verified |  |
| HA | hut ascend | pinstress hut platform | lava basin | none (falling) |  | Verified |  |
| ULA | upper left ascend | lower left exit area | upper left exit area | silk soar |  | Verified |  |
| ULA | upper left ascend | upper left exit area | lower left exit area | none (falling) |  | Verified |  |
| URC | upper right crossing | upper right exit area | ceiling wind tunnel | ( drifter's cloak AND break blast rock down ) OR ( cling grip AND faydown cloak AND clawline ) |  | Verified | maybe someone else try to find other options? |
| CWA | ceiling wind ascend | ceiling wind tunnel | ceiling exit area | silk soar OR ( break blast rock down AND drifter's cloak ) |  | Verified |  |
| CWA | ceiling wind ascend | ceiling exit area | ceiling wind tunnel | none (falling) |  | Verified |  |
| F1 | fall 1 | ceiling wind tunnel | pinstress hut platform | none (falling) |  | Verified |  |
| ULC | upper left crossing | upper left exit area | ceiling wind tunnel | run OR dash OR easy beast pogo OR drifter's cloak OR faydown cloak OR silk soar OR sharpdart OR scuttlebrace |  | Verified |  |
| ULC | upper left crossing | ceiling wind tunnel | upper left exit area | run OR ( easy beast pogo AND ledge grab ) OR drifter's cloak OR faydown cloak OR silk soar OR sharpdart |  | Verified | left ledge is slightly higher, so fewer options this way |

#### Check Locations

No check locations defined.

### Far Fields Pinstress Hut Interior (Bone_East_Umbrella)

**Game ID:** Bone_East_Umbrella

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Far Fields Pinstress Room (Bone_East_09)](#far-fields-pinstress-room-boneeast09) | D | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bench |  | none |  | Verified | bench |  |
| flexible spines wish promised |  | none |  | Verified | event |  |
| flexible spines wish granted |  | complete flexible spines wish promised AND ( flexible spines 25  OR defeat hoker enemy IN far fields skull room west OR defeat hoker enemy IN far fields skull room east ) |  | Verified | event | wasn't sure which made more sense here - the former is more accurate, but the latter is more logic complete |
| drifters cloak |  | complete flexible spines wish granted |  | Verified | collectible |  |

### Far Fields Pinstress Mask Shard (Bone_East_20)

**Game ID:** Bone_East_20

**Contributors:** herounit

#### Subrooms

- right side
- left side

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right side | [Far Fields Pinstress Room (Bone_East_09)](#far-fields-pinstress-room-boneeast09) | UL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TC | thorn crossing | right side | left side | clawline OR ( drifter's cloak AND ( ledge grab OR silk soar ) ) |  | Verified |  |
| TC | thorn crossing | left side | right side | drifter's cloak OR ( clawline AND ( silk soar OR faydown cloak OR run ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| mask shard far fields above the seamstress | left side | drifter's cloak OR silk soar OR faydown cloak |  | Verified | collectible | must break blast rock on ceiling - this likely has a large number of tool options - haven't really considered this here |
| random silk | left side | none |  | Verified | resource | NOT YET RANDOMIZED |

### Far Fields Target Practice (Bone_East_22)

**Game ID:** Bone_East_22

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | R4 | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| progressive curveclaw 2 |  | act 3 AND curveclaw |  | Verified | collectible | NOT CURRENTLY ON TRACKER - MAY NOT BE RANDOMIZED |

#### Notes

this is the room where you get progressive curveclaw (curvesickle) in act 3

### Far Fields Map Shop (Bone_East_21)

**Game ID:** Bone_East_21

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | R5 | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| map purchase far fields |  | none |  | Verified | collectible | shakra shop |

### Far Fields Bellway (Bellway_03)

**Game ID:** Bellway_03

**Contributors:** herounit

#### Subrooms

- bellway
- hidden area
- right exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right exit area | [Far Fields Pinstress Attic (Bone_East_09b)](#far-fields-pinstress-attic-boneeast09b) | L | none |  | Verified |  |
| L | left1 | bellway | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | R2 | none |  | Verified |  |
| BB | door_fastTravelExit | bellway | [Bellway Menu](#bellway-menu) | FF | unlock bellway far fields |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| HP | hidden pathway | bellway | hidden area | unlock bellway rosary lock |  | Verified |  |
| HP | hidden pathway | hidden area | bellway | unlock bellway rosary lock |  | Verified |  |
| TP | thorn path | hidden area | right exit area | ( silk soar AND ( ledge grab OR cling grip OR scuttlebrace ) )  OR ( faydown cloak AND cling grip )  OR ( break blast rock down AND drifter's cloak AND ( cling grip OR scuttlebrace ) ) |  | Verified |  |
| TP | thorn path | right exit area | hidden area | silk soar OR drifter's cloak |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bench | bellway | unlock bench rosary lock |  | Verified | bench |  |
| bench rosary lock | bellway | none |  | Verified | lock |  |
| bellway rosary lock | bellway | none |  | Verified | lock |  |
| bellway far fields | bellway | unlock bellway rosary lock |  | Verified | travel |  |
| Craw Summons | bellway | craw summons ready |  | Verified | collectible |  |

### Far Fields Deep Docks Loopback (Bone_East_15)

**Game ID:** Bone_East_15

**Contributors:** herounit

#### Subrooms

- spike exit
- ground
- bell bench
- before gate

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | bell bench | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | LR | none |  | Verified |  |
| F | bot1 | ground | [Far Fields Entrance East (Bone_East_02)](#far-fields-entrance-east-boneeast02) | C | none |  | Verified |  |
| R | right1 | spike exit | [Far Fields Fort Upper Passage (Bone_East_17)](#far-fields-fort-upper-passage-boneeast17) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SF | spike float | ground | spike exit | ( cling grip AND drifter's cloak ) OR ( silk soar AND drifter's cloak ) |  | Verified | exit silk soar early and land on platform |
| SF | spike float | spike exit | ground | none (falling) |  | Verified | can barely ledge grab by falling to jump down |
| BG | bell bench gate | before gate | bell bench | none (switch is on this side) |  | Verified |  |
| BG | bell bench gate | bell bench | before gate | activate gate switch |  | Verified |  |
| CG | cling grip | ground | before gate | cling grip OR silk soar OR scuttlebrace |  | Verified |  |
| CG | cling grip | before gate | ground | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 9 | ground | none |  | Verified | collectible | MARKED AS ??? ON TRACKER |
| rosary cache far fields 10 | ground | none |  | Verified | collectible | MARKED AS ??? ON TRACKER |
| gate switch | before gate | flip switch up |  | Verified | switch |  |
| bench rosary lock | bell bench | none |  | Verified | lock |  |
| bench :) | bell bench | unlock bench rosary lock |  | Verified | bench |  |

### Far Fields Deep Docks Backdoor (Dock_03b)

**Game ID:** Dock_03b

**Contributors:** herounit

#### Subrooms

- upper area
- lower area
- platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | upper area | [Deep Docks Chains Upper East (Dock_03)](#deep-docks-chains-upper-east-dock03) | R | break wall left |  | Verified |  |
| R | right1 | lower area | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | L3 | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LG1 | ledge grab 1 | lower area | upper area | ledge grab  OR silk soar  OR faydown  OR cling grip OR easy shaman pogo |  | Verified |  |
| LG1 | ledge grab 1 | upper area | lower area | none (falling) |  | Verified |  |
| LG2 | ledge grab 2 | upper area | platform | ledge grab  OR silk soar  OR faydown  OR cling grip OR scuttlebrace |  | Verified |  |
| LG2 | ledge grab 2 | platform | upper area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| warding bell | platform | none |  | Verified | collectible |  |

### Far Fields Skull Room West (Bone_East_14)

**Game ID:** Bone_East_14

**Contributors:** herounit

#### Subrooms

- lower left exit area
- upper left exit area
- main floor
- relic alcove
- rosary alcove
- bone bridge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | upper left exit area | [Far Fields Pinstress Room (Bone_East_09)](#far-fields-pinstress-room-boneeast09) | UR | none |  | Verified |  |
| LL | left2 | lower left exit area | [Far Fields Pinstress Room (Bone_East_09)](#far-fields-pinstress-room-boneeast09) | LR | none |  | Verified |  |
| UR | right1 | bone bridge | [Far Fields Skull Room East (Bone_East_14b)](#far-fields-skull-room-east-boneeast14b) | UL | none |  | Verified |  |
| LR | right2 | main floor | [Far Fields Skull Room East (Bone_East_14b)](#far-fields-skull-room-east-boneeast14b) | LL | break blast rock right |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LBR | left blast rock | lower left exit area | main floor | clear lower left blast rock blockade |  | Verified |  |
| LBR | left blast rock | main floor | lower left exit area | clear lower left blast rock blockade |  | Verified |  |
| V1 | vertical 1 | main floor | upper left exit area | ledge grab OR silk soar OR easy shaman pogo OR drifter's cloak OR faydown cloak OR cling grip OR clawline OR scuttlebrace |  | Verified |  |
| V1 | vertical 1 | upper left exit area | main floor | clear upper left blast rock blockade |  | Verified |  |
| V2 | vertical 2 | main floor | relic alcove | clear upper left blast rock blockade AND ( drifter's cloak OR silk soar ) |  | Verified |  |
| V2 | vertical 2 | relic alcove | main floor | none (falling) |  | Verified |  |
| V3 | vertical 3 | main floor | rosary alcove | drifter's cloak OR faydown cloak OR silk soar OR ( ledge grab AND ( run OR dash OR easy beast pogo OR cling grip OR clawline OR sharpdart OR scuttlebrace ) ) |  | Verified |  |
| V3 | vertical 3 | rosary alcove | main floor | none (falling) |  | Verified |  |
| V4 | vertical 4 | main floor | bone bridge | clear spine break blast rock AND ( faydown cloak OR silk soar OR ledge grab ) |  | Verified |  |
| V4 | vertical 4 | bone bridge | main floor | clear spine break blast rock |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary string far fields | lower left exit area | none |  | Verified | collectible | MARKED AS ??? ON TRACKER |
| relic bone scroll far fields | relic alcove | none |  | Verified | collectible |  |
| rosary cache far fields 5 | rosary alcove | none |  | Verified | collectible |  |
| rosary cache far fields 6 | rosary alcove | none |  | Verified | collectible |  |
| hoker enemy | main floor | none |  | Verified | enemy | used to farm flexible spines |
| spine break blast rock | bone bridge | break blast rock up |  | Verified | blockade |  |
| lower left blast rock blockade | lower left exit area | break blast rock right |  | Verified | blockade |  |
| upper left blast rock blockade | upper left exit area | break blast rock left |  | Verified | blockade |  |

### Far Fields Skull Room East (Bone_East_14b)

**Game ID:** Bone_East_14b

**Contributors:** herounit

#### Subrooms

- weavenest platform
- main floor
- upper left exit area
- skull platform
- rosary platform
- upper passage

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | upper left exit area | [Far Fields Skull Room West (Bone_East_14)](#far-fields-skull-room-west-boneeast14) | UR | none |  | Verified |  |
| LL | left2 | main floor | [Far Fields Skull Room West (Bone_East_14)](#far-fields-skull-room-west-boneeast14) | LR | none |  | Verified |  |
| D | door1 | skull platform | [Far Fields Skull Arena (Bone_East_LavaChallenge)](#far-fields-skull-arena-boneeastlavachallenge) | L | none |  | Verified |  |
| R | right1 | weavenest platform | [Weavenest Cindril Entrance (Bone_East_Weavehome)](#weavenest-cindril-entrance-boneeastweavehome) | L | needolin |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| G1 | gap 1 | main floor | weavenest platform | run OR dash OR easy beast pogo OR drifters cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| G1 | gap 1 | weavenest platform | main floor | run OR dash OR easy beast pogo OR drifters cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| V1 | vertical 1 | main floor | skull platform | silk soar OR ( clawline AND ( cling grip OR faydown cloak ) ) OR ( ledge grab AND run AND dash AND faydown cloak ) |  | Verified |  |
| V1 | vertical 1 | skull platform | main floor | none (falling) |  | Verified |  |
| V2 | vertical 2 | main floor | rosary platform | silk soar OR faydown cloak OR ( ledge grab AND ( run OR dash OR drifter's cloak OR clawline OR sharpdart ) ) |  | Verified |  |
| V2 | vertical 2 | rosary platform | main floor | none (falling) |  | Verified |  |
| V3 | vertical 3 | main floor | upper passage | ledge grab OR silk soar OR faydown cloak |  | Verified | might be missing options here |
| V3 | vertical 3 | upper passage | main floor | none (falling) |  | Verified |  |
| UC | upper crossing | upper passage | upper left exit area | ledge grab OR spike pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| UC | upper crossing | upper left exit area | upper passage | ledge grab OR spike pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 7 | rosary platform | none |  | Verified | collectible |  |
| rosary cache far fields 8 | rosary platform | none |  | Verified | collectible |  |
| hoker enemy | main floor | none (attack enemy up) |  | Verified | enemy | used to farm flexible spines |

### Far Fields Skull Arena (Bone_East_LavaChallenge)

**Game ID:** Bone_East_LavaChallenge

**Contributors:** herounit

#### Subrooms

- entrance
- arena
- crossing
- check alcove
- mask alcove

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | entrance | [Far Fields Skull Room East (Bone_East_14b)](#far-fields-skull-room-east-boneeast14b) | D | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ET | entrance tunnel | entrance | crossing | break blast rock down AND ( spike pogo OR drifter's cloak OR faydown cloak OR clawline OR dash OR scuttlebrace ) |  | Verified |  |
| ET | entrance tunnel | crossing | entrance | ( cling grip OR scuttlebrace ) AND ( spike pogo OR dash OR clawline OR drifter's cloak OR faydown cloak  ) |  | Verified |  |
| CT | check tunnel | crossing | check alcove | break blast rock up AND ( scuttlebrace OR cling grip ) |  | Verified |  |
| CT | check tunnel | check alcove | crossing | none (falling) |  | Verified |  |
| AT | arena tunnel | crossing | arena | break blast rock down |  | Verified |  |
| LA | lava ascend | arena | mask alcove | cling grip AND drifter's cloak AND faydown cloak AND dash |  | Verified |  |
| MD | mask descend | mask alcove | entrance | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache far fields 8 | check alcove | none |  | Verified | collectible | this becomes inaccessible after defeating the gauntlet - perhaps auto collect? |
| mask shard far fields skull cave | mask alcove | none |  | Verified | collectible |  |

#### Notes

modeled this area as:
entrance <-> crossing <-> check alcove <-> crossing -> arena -> mask alcove -> entrance 
the arena to mask shard connections are one-way so the full requirement chain is enforced

### Weavenest Cindril Entrance (Bone_East_Weavehome)

**Game ID:** Bone_East_Weavehome

**Contributors:** herounit

#### Subrooms

- entrance
- secret room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | entrance | [Far Fields Skull Room East (Bone_East_14b)](#far-fields-skull-room-east-boneeast14b) | R | needolin |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SR | secret room | entrance | secret room | unlock secret room lock |  | Verified |  |
| SR | secret room | secret room | entrance | unlock secret room lock AND ( cling grip OR silk soar OR scuttlebrace ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| silkspeed anklets | entrance | run |  | Verified | collectible |  |
| relic rune harp weavenest cindril | secret room | none |  | Verified | collectible |  |
| map of paths away from pharloom | secret room | none |  | Verified | lore |  |
| secret room lock | entrance | run AND silkspeed anklets AND flea brew |  | Verified | lock |  |

### Far Fields Deep Entrance (Bone_East_24)

**Game ID:** Bone_East_24

**Contributors:** herounit

#### Subrooms

- left exit area
- bottom exit area
- right exit area
- lower left alcove
- middle left platform
- plains
- lower right area
- lower right alcove
- upper right alcove
- left of right exit gate
- plains upper right platform
- plains upper left platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | bottom exit area | [Far Fields Deep Lower West (Bone_East_18)](#far-fields-deep-lower-west-boneeast18) | C | none |  | Verified |  |
| L | left1 | left exit area | [Far Fields Upper Shaft (Bone_East_11)](#far-fields-upper-shaft-boneeast11) | UR | none |  | Verified |  |
| R | right1 | right exit area | [Far Fields Deep Fort Bench (Bone_East_27)](#far-fields-deep-fort-bench-boneeast27) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | left exit area | middle left platform | none (falling) |  | Verified |  |
| V1 | vertical 1 | middle left platform | left exit area | silk soar OR faydown cloak |  | Verified |  |
| V2 | vertical 2 | middle left platform | lower left alcove | run OR dash OR easy beast pogo OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| V2 | vertical 2 | lower left alcove | middle left platform | ( faydown cloak AND ledge grab ) OR ( cling grip AND ( run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart ) ) |  | Verified |  |
| G1 | gap 1 | middle left platform | plains | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| G1 | gap 1 | plains | middle left platform | run OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR ( dash AND ledge grab ) |  | Verified |  |
| V3 | vertical 3 | plains | lower right area | none (falling) |  | Verified |  |
| V3 | vertical 3 | lower right area | plains | silk soar  OR faydown OR ( ledge grab AND ( run OR clawline ) ) |  | Verified |  |
| V4 | vertical 4 | lower right area | lower right alcove | break blast rock left AND ( spike pogo OR cling grip OR faydown cloak OR scuttlebrace OR   easy hazard respawn ) |  | Verified | can just break it, reset from thorns and jump down again - won't work with 1 hp though :) |
| V4 | vertical 4 | lower right alcove | lower right area | cling grip OR faydown cloak OR scuttlebrace |  | Verified |  |
| V5 | vertical 5 | lower right area | bottom exit area | none (falling) |  | Verified |  |
| V5 | vertical 5 | bottom exit area | lower right area | silk soar OR cling grip OR scuttlebrace ( faydown cloak AND ledge grab ) |  | Verified |  |
| DS | door switch | right exit area | left of right exit gate | activate right exit door switch |  | Verified |  |
| DS | door switch | left of right exit gate | right exit area | activate right exit door switch |  | Verified |  |
| V6 | vertical 6 | lower right area | left of right exit gate | silk soar OR faydown cloak OR ( ledge grab AND ( run OR drifter's cloak OR clawline ) ) |  | Verified |  |
| V6 | vertical 6 | left of right exit gate | lower right area | none (falling) |  | Verified |  |
| S1 | silk soar 1 | plains | plains upper left platform | silk soar OR ( faydown cloak AND clawline ) |  | Verified | can hop up from the ground here or cross over from the plains upper right platform - requirements are the same |
| S1 | silk soar 1 | plains upper left platform | plains | none (falling) |  | Verified |  |
| S2 | silk soar 2 | plains | plains upper right platform | silk soar |  | Verified |  |
| S2 | silk soar 2 | plains upper right platform | plains | none (falling) |  | Verified |  |
| S3 | silk soar 3 | lower right area | upper right alcove | silk soar |  | Verified |  |
| S3 | silk soar 3 | upper right alcove | lower right area | none (falling) |  | Verified |  |
| G2 | gap 2 | left of right exit gate | plains upper right platform | faydown cloak AND ( run OR dash OR drifter's cloak OR clawline OR sharpdart OR scuttlebrace ) |  | Verified |  |
| G2 | gap 2 | plains upper right platform | left of right exit gate | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR scuttlebrace OR sharpdart |  | Verified |  |
| V7 | vertical 7 | plains upper right platform | upper right alcove | cling grip AND faydown cloak AND ( ledge grab OR run OR dash OR drifter's cloak OR clawline OR sharpdart OR scuttlebrace ) |  | Verified |  |
| V7 | vertical 7 | upper right alcove | plains upper right platform | none (falling) |  | Verified |  |
| G3 | gap 3 | plains upper left platform | plains upper right platform | faydown cloak AND clawline |  | Verified |  |
| G3 | gap 3 | plains upper right platform | plains upper left platform | faydown cloak AND clawline |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| right exit door switch | right exit area | flip switch down |  | Verified | switch |  |
| AP Minor Cache - Shell Shard Cache: Far Fields #4 | lower left alcove | none |  | Verified | collectible |  |
| AP Minor Cache - Shell Shard Cache: Far Fields #5 | lower left alcove | none |  | Verified | collectible |  |
| AP Minor Cache - Shell Shard Cache: Far Fields #6 | plains upper left platform | none |  | Verified | collectible |  |
| AP Minor Cache - Shell Shard Cache: Far Fields #7 | lower right alcove | none |  | Verified | collectible |  |
| AP Minor Cache - Rosary Cache: Far Fields #20 | upper right alcove | none |  | Verified | collectible |  |
| AP Minor Cache - Rosary Cache: Far Fields #21 | upper right alcove | none |  | Verified | collectible |  |
| AP Minor Cache - Rosary Cache: Far Fields #22 | upper right alcove | none |  | Verified | collectible |  |
| pale rosary necklace far fields | upper right alcove | act 3 |  | Needs verification | collectible | requires act 3 according to the wiki |

### Far Fields Deep Lower East (Bone_East_18b)

**Game ID:** Bone_East_18b

**Contributors:** herounit

#### Subrooms

- left exit area
- right exit area
- ceiling exit area
- crossing
- trapper's arena
- trapper's den
- trapper's ledge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 | right exit area | [Sprintmaster Cave (Sprintmaster_Cave)](#sprintmaster-cave-sprintmastercave) | L | none |  | Verified |  |
| C | top1 | ceiling exit area | [Far Fields Deep Fort Passage (Bone_East_26)](#far-fields-deep-fort-passage-boneeast26) | F | none |  | Verified |  |
| L | left1 | left exit area | [Far Fields Deep Lower West (Bone_East_18)](#far-fields-deep-lower-west-boneeast18) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TB | trapped bench | crossing | trapper's arena | act 3 AND complete THE the hidden hunter wish promised |  | Verified |  |
| TB | trapped bench | trapper's arena | crossing | defeat gurr the outcast boss fight AND silk soar |  | Verified |  |
| RB | right boss fight | trapper's arena | trapper's den | defeat gurr the outcast boss fight |  | Verified |  |
| RB | right boss fight | trapper's den | trapper's arena | defeat gurr the outcast boss fight |  | Verified |  |
| G1 | gap 1 | left exit area | crossing | clawline AND silkhearts 1 |  | Verified |  |
| G1 | gap 1 | crossing | left exit area | clawline  AND silkhearts 1 AND ( run OR dash OR drifters OR faydown ) |  | Verified |  |
| G2 | gap 2 | crossing | right exit area | clawline AND silkhearts 1 |  | Verified | need to pogo to let silk recharge with only 1 heart, but it isn't that bad |
| G2 | gap 2 | right exit area | crossing | ( clawline AND silkhearts 2 ) OR ( clawline  AND silkhearts 1 AND ( dash OR faydown OR drifters ) ) |  | Verified | need enough silk to clawline twice to get the distance by itself |
| V1 | vertical 1 | crossing | ceiling exit area | ( faydown cloak AND ( cling grip OR scuttlebrace ) )  OR ( silk soar AND ( clawline OR drifter's cloak OR faydown cloak OR ( ledge grab AND dash ) ) ) |  | Verified |  |
| V1 | vertical 1 | ceiling exit area | crossing | run OR dash OR drifter's cloak OR  faydown cloak OR easy beast pogo OR sharpdart OR scuttlebrace |  | Verified |  |
| T1 | trapper 1 | trapper's den | trapper's ledge | faydown OR cling grip OR scuttlebrace OR silk soar |  | Verified |  |
| T1 | trapper 1 | trapper's ledge | trapper's den | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| gurr the outcast boss fight | trapper's arena | none |  | Verified | boss |  |
| AP Minor Cache - Rosary Cache: Far Fields #19 | trapper's ledge | none |  | Verified | collectible |  |
| Grass Doll | trapper's ledge | none |  | Verified | collectible |  |

### Far Fields Pilgrim's Rest Deep Passage (Bone_East_18c)

**Game ID:** Bone_East_18c

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Far Fields Deep Lower West (Bone_East_18)](#far-fields-deep-lower-west-boneeast18) | L | none |  | Verified |  |
| L | left1 |  | [Far Fields Pilgrim's Rest (Bone_East_10)](#far-fields-pilgrims-rest-boneeast10) | UR | clear blast rock exit block |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| blast rock exit block |  | break blast rock left |  | Verified | blockade |  |

### Far Fields Deep Lower West (Bone_East_18)

**Game ID:** Bone_East_18

**Contributors:** herounit

#### Subrooms

- ceiling exit area
- ground level
- upper right alcove
- left of alcove gate

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | ceiling exit area | [Far Fields Deep Entrance (Bone_East_24)](#far-fields-deep-entrance-boneeast24) | F | none |  | Verified |  |
| L | left1 | ground level | [Far Fields Pilgrim's Rest Deep Passage (Bone_East_18c)](#far-fields-pilgrims-rest-deep-passage-boneeast18c) | R | none |  | Verified |  |
| R | right1 | ground level | [Far Fields Deep Lower East (Bone_East_18b)](#far-fields-deep-lower-east-boneeast18b) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | ground level | upper right alcove | silk soar OR scuttlebrace OR ( cling grip AND ( run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR easy beast pogo ) ) |  | Verified |  |
| V1 | vertical 1 | upper right alcove | ground level | none (falling) |  | Verified |  |
| DS | door switch | upper right alcove | left of alcove gate | activate door switch |  | Verified |  |
| DS | door switch | left of alcove gate | upper right alcove | activate door switch |  | Verified |  |
| V2 | vertical 2 | ground level | ceiling exit area | silk soar OR faydown cloak OR ( ledge grab AND ( run OR clawline OR ( drifter's cloak AND ( dash OR sharpdart ) ) ) ) |  | Verified |  |
| V2 | vertical 2 | ceiling exit area | ground level | none (falling) |  | Verified |  |
| V3 | vertical 3 | left of alcove gate | ceiling exit area | silk soar OR clawline OR faydown cloak OR scuttlebrace OR ( run AND ledge grab ) OR ( cling grip AND ( run OR dash OR sharpdart OR easy beast pogo OR drifter's cloak ) ) |  | Verified | no inverse because there isn't much point |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| door switch | upper right alcove | flip switch down |  | Verified | switch |  |
| AP Minor Cache - Shell Shard Cache: Far Fields #2 | upper right alcove | none |  | Verified | collectible |  |
| AP Minor Cache - Shell Shard Cache: Far Fields #3 | upper right alcove | none |  | Verified | collectible |  |
| AP Minor Cache - Rosary Cache: Far Fields #18 | upper right alcove | none |  | Verified | collectible |  |

### Far Fields Deep Fort Passage (Bone_East_26)

**Game ID:** Bone_East_26

**Contributors:** herounit

#### Subrooms

- ceiling exit area
- floor exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | ceiling exit area | [Far Fields Deep Fort Bench (Bone_East_27)](#far-fields-deep-fort-bench-boneeast27) | F | none |  | Verified |  |
| F | bot1 | floor exit area | [Far Fields Deep Lower East (Bone_East_18b)](#far-fields-deep-lower-east-boneeast18b) | C | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TC | thorn crossing | floor exit area | ceiling exit area | clawline  AND silkhearts 1 AND ( faydown OR silk soar ) |  | Verified |  |
| TC | thorn crossing | ceiling exit area | floor exit area | ( clawline  AND ( silkhearts 2  OR ( silkhearts 1 AND ( faydown OR dash OR drifters ) ) ) ) OR ( run AND dash AND drifters AND faydown ) |  | Verified |  |

#### Check Locations

No check locations defined.

### Far Fields Deep Fort Bench (Bone_East_27)

**Game ID:** Bone_East_27

**Contributors:** herounit

#### Subrooms

- main floor
- bench area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | main floor | [Far Fields Deep Fort Passage (Bone_East_26)](#far-fields-deep-fort-passage-boneeast26) | C | none |  | Verified |  |
| R | right1 | main floor | [Far Fields Deep Fort (Bone_East_25)](#far-fields-deep-fort-boneeast25) | L | none |  | Verified |  |
| L | left1 | main floor | [Far Fields Deep Entrance (Bone_East_24)](#far-fields-deep-entrance-boneeast24) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SS | silk soar spot | main floor | bench area | silk soar |  | Verified |  |
| SS | silk soar spot | bench area | main floor | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bench | bench area | none |  | Verified | bench |  |
| Craw Summons | bench area | craw summons ready |  | Verified | collectible | one of several possible craw summons locations |

### Far Fields Deep Fort (Bone_East_25)

**Game ID:** Bone_East_25

**Contributors:** herounit

#### Subrooms

- main area
- prison

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | main area | [Far Fields Deep Fort Bench (Bone_East_27)](#far-fields-deep-fort-bench-boneeast27) | R | none |  | Verified |  |
| D | door1 | main area | [Current Karmelita (Ant_Queen)](#current-karmelita-antqueen) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DG | defeat grunt | main area | prison | defeat grunt |  | Verified |  |
| DG | defeat grunt | prison | main area | defeat grunt |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| memory locket far fields | prison | none |  | Verified | collectible | name says act 3 but is not actually gated by act 3 |
| grunt | main area | none |  | Verified | miniboss | does not respawn |

### Current Karmelita (Ant_Queen)

**Game ID:** Ant_Queen

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Far Fields Deep Fort (Bone_East_25)](#far-fields-deep-fort-boneeast25) | D | none |  | Verified |  |
| MG | memory |  | [Memory Karmelita (Memory_Ant_Queen)](#memory-karmelita-memoryantqueen) | MG | elegy of the deep |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| meet karmelita |  | none |  | Verified | logic-point | used for the hidden hunter wish |

### Memory Karmelita (Memory_Ant_Queen)

**Game ID:** Memory_Ant_Queen

**Contributors:** herounit

#### Subrooms

- entrance
- arena

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MG | door_wakeInMemory | entrance | [Current Karmelita (Ant_Queen)](#current-karmelita-antqueen) | MG | none |  | Verified | just walk left to leave |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AP | arena passage | entrance | arena | silk soar OR faydown cloak |  | Verified |  |
| AP | arena passage | arena | entrance | silk soar OR ( faydown cloak AND ledge grab ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| skarrsinger karmelita boss fight | arena | none |  | Verified | boss |  |
| hunter's heart | arena | defeat skarrsinger karmelita boss fight |  | Verified | collectible |  |

### Sprintmaster Cave (Sprintmaster_Cave)

**Game ID:** Sprintmaster_Cave

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Far Fields Deep Lower East (Bone_East_18b)](#far-fields-deep-lower-east-boneeast18b) | D | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| RestBench |  | none |  | Verified | bench |  |
| fastest in pharloom wish promised |  | none |  | Verified | event | can also start at the bellhart wish wall |
| fastest in pharloom wish granted |  | complete fastest in pharloom wish promised AND complete race victory 3 |  | Verified | event |  |
| race victory 1 |  | complete fastest in pharloom wish promised AND run AND dash AND cling grip AND clawline AND faydown cloak | TODO | Needs verification | event | these need to be refined for each race |
| race victory 2 |  | complete race victory 1  AND run AND dash AND cling grip AND clawline AND faydown cloak | TODO | Needs verification | event | these need to be refined for each race |
| race victory 3 |  | complete race victory 2  AND run AND dash AND cling grip AND clawline AND faydown cloak | TODO | Needs verification | event | these need to be refined for each race |
| race victory 4 |  | complete race victory 3  AND run AND dash AND cling grip AND clawline AND faydown cloak | TODO | Needs verification | event | these need to be refined for each race |
| rosary beads |  | complete race victory 1 |  | Verified | collectible |  |
| beast shard |  | complete race victory 2 |  | Verified | collectible |  |
| fastest in pharloom mask shard |  | complete race victory 3 |  | Verified | collectible |  |
| sprintmaster memento |  | complete race victory 4 |  | Verified | collectible |  |

## Hunter's March

### Chapel of the Beast (Ant_19)

**Game ID:** Ant_19

**Contributors:** herounit

#### Subrooms

- chapel entrance
- boss arena
- crest area
- right of boss fight

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | chapel entrance | [Hunter's March Chapel Passage (Ant_20)](#hunters-march-chapel-passage-ant20) | D | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | chapel entrance | right of boss fight | drifter's cloak OR activate door switch |  | Verified |  |
| DS | door switch | right of boss fight | chapel entrance | activate door switch |  | Verified |  |
| BR | boss right entrance | right of boss fight | boss arena | none (starts boss fight) |  | Verified |  |
| BR | boss right entrance | boss arena | right of boss fight | defeat savage beastfly boss fight |  | Verified |  |
| BL | boss left entrance | crest area | boss arena | defeat savage beastfly boss fight |  | Verified |  |
| BL | boss left entrance | boss arena | crest area | defeat savage beastfly boss fight |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| door switch | right of boss fight | flip switch down |  | Verified | switch |  |
| savage beastfly boss fight | boss arena | none |  | Verified | boss |  |
| crest beast | crest area | none |  | Verified | collectible |  |

### Hunter's March Chapel Passage (Ant_20)

**Game ID:** Ant_20

**Contributors:** herounit

#### Subrooms

- left entrance
- crossing platform
- chapel entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left entrance | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | LR | none |  | Verified |  |
| D | door1 | chapel entrance | [Chapel of the Beast (Ant_19)](#chapel-of-the-beast-ant19) | L | none (door forced open) |  | Verified | The randomizer will need to ensure this door stays open when this room is relevant |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EP | evil pogo | left entrance | crossing platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace OR easy shaman pogo OR easy wanderer pogo OR easy beast pogo OR easy reaper pogo OR ( ledge grab AND ( easy witch pogo OR easy hunter pogo OR easy architect pogo ) ) |  | Verified |  |
| EP | evil pogo | crossing platform | left entrance | none |  | Verified | can pogo the gap for free from this direction |
| WT | wind tunnel | crossing platform | chapel entrance | drifter's cloak OR silk soar |  | Verified |  |
| WT | wind tunnel | chapel entrance | crossing platform | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| memory locket | crossing platform | none |  | Verified | collectible | need to break a cage |

### Hunter's March Entrance (Ant_02)

**Game ID:** Ant_02

**Contributors:** herounit

#### Subrooms

- before door
- after door
- checks alcove

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | before door | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | MR | none |  | Verified |  |
| R | right1 | after door | [Hunter's March Pogo Intro (Ant_03)](#hunters-march-pogo-intro-ant03) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FG | fight grunt | before door | after door | defeat grunt fight |  | Verified |  |
| FG | fight grunt | after door | before door | defeat grunt fight |  | Verified |  |
| LG | ledge grab | after door | checks alcove | ledge grab OR faydown cloak OR silk soar |  | Verified |  |
| LG | ledge grab | checks alcove | after door | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache hunter's march 1 | checks alcove | none |  | Verified | collectible | MARKED AS ??? ON TRACKER |
| shell shard cache hunter's march 2 | checks alcove | none |  | Verified | collectible | MARKED AS ??? ON TRACKER |
| grunt fight | before door | none |  | Verified | miniboss |  |

### Hunter's March Pogo Intro (Ant_03)

**Game ID:** Ant_03

**Contributors:** herounit

#### Subrooms

- flea rescue area
- main area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left2 | main area | [Hunter's March Entrance (Ant_02)](#hunters-march-entrance-ant02) | R | none |  | Verified |  |
| R | right3 | main area | [Hunter's March Early Pathway West (Ant_04_left)](#hunters-march-early-pathway-west-ant04left) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| UP | upper pogo | main area | flea rescue area | ledge grab OR scuttlebrace OR easy shaman pogo OR easy reaper pogo OR easy wanderer pogo OR faydown cloak OR silk soar |  | Verified |  |
| UP | upper pogo | flea rescue area | main area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue | flea rescue area | break vines right |  | Verified | collectible |  |

### Hunter's March Early Pathway West (Ant_04_left)

**Game ID:** Ant_04_left

**Contributors:** herounit

#### Subrooms

- upper platforms
- upper left alcove
- left exit area
- lower floor

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Hunter's March Pogo Intro (Ant_03)](#hunters-march-pogo-intro-ant03) | R | none |  | Verified |  |
| R | right1 | lower floor | [Hunter's March Map Shop (Ant_04_mid)](#hunters-march-map-shop-ant04mid) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| P1 | pogo 1 | left exit area | upper platforms | silk soar OR faydown cloak OR easy shaman pogo OR easy wanderer pogo OR easy reaper pogo OR ledge grab |  | Verified |  |
| P1 | pogo 1 | upper platforms | left exit area | none (falling) |  | Verified |  |
| L1 | ledge grab 1 | lower floor | left exit area | ledge grab OR silk soar OR faydown cloak OR clawline OR easy shaman pogo |  | Verified |  |
| L1 | ledge grab 1 | left exit area | lower floor | none (falling) |  | Verified |  |
| L2 | ledge grab 2 | upper platforms | upper left alcove | ledge grab OR faydown cloak OR silk soar OR easy shaman pogo |  | Verified |  |
| L2 | ledge grab 2 | upper left alcove | upper platforms | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache hunters march 1 | upper left alcove | none |  | Verified | collectible | get there fast - the ants will eat them (v0.4.2) |
| rosary cache hunters march 2 | upper left alcove | none |  | Verified | collectible | get there fast - the ants will eat them (v0.4.2) |
| rosary cache hunters march 3 | upper platforms | none |  | Verified | collectible |  |
| rosary necklace hunters march | upper platforms | none |  | Verified | collectible | ants eat them before you can collect (v0.4.2) |

### Hunter's March Map Shop (Ant_04_mid)

**Game ID:** Ant_04_mid

**Contributors:** herounit

#### Subrooms

- left of gauntlet
- gauntlet
- right of gauntlet

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left of gauntlet | [Hunter's March Early Pathway West (Ant_04_left)](#hunters-march-early-pathway-west-ant04left) | R | none |  | Verified |  |
| R | right1 | right of gauntlet | [Hunter's March Early Pathway East (Ant_04)](#hunters-march-early-pathway-east-ant04) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LG | left gauntlet entrance | left of gauntlet | gauntlet | none (starts gauntlet) |  | Verified |  |
| LG | left gauntlet entrance | gauntlet | left of gauntlet | defeat gauntlet fight |  | Verified |  |
| RG | right of gauntlet entrance | right of gauntlet | gauntlet | none (starts gauntlet) |  | Verified |  |
| RG | right of gauntlet entrance | gauntlet | right of gauntlet | defeat gauntlet fight |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| gauntlet fight | gauntlet | none |  | Verified | gauntlet |  |
| map purchase hunter's march | gauntlet | defeat gauntlet fight |  | Verified | collectible |  |

### Hunter's March Early Pathway East (Ant_04)

**Game ID:** Ant_04

**Contributors:** herounit

#### Subrooms

- main area
- ceiling alcove

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | main area | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | L3 | none |  | Verified |  |
| L | left1 | main area | [Hunter's March Map Shop (Ant_04_mid)](#hunters-march-map-shop-ant04mid) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | main area | ceiling alcove | silk soar OR easy shaman pogo OR easy reaper pogo OR easy wanderer pogo OR faydown cloak OR cling grip OR ledge grab OR scuttlebrace |  | Verified |  |
| V1 | vertical 1 | ceiling alcove | main area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache hunters march 3 | ceiling alcove | none |  | Verified | collectible |  |
| shell shard cache hunters march 4 | ceiling alcove | none |  | Verified | collectible |  |
| silk webs x3 | main area | none |  | Verified | resource | not yet randomized |

### Hunter's March Shaft (Ant_14)

**Game ID:** Ant_14

**Contributors:** herounit

#### Subrooms

- the top
- L1 platform
- L2 platform
- UR platform
- L3 platform
- the bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L5 | left5 | the top | [Hunter's March Treasure Vault (Ant_21)](#hunters-march-treasure-vault-ant21) | R | none |  | Verified |  |
| L1 | left1 | L1 platform | [Hunter's March Skarr Shop (Ant_Merchant)](#hunters-march-skarr-shop-antmerchant) | R | none |  | Verified |  |
| L2 | left2 | L2 platform | [Hunter's March Trapped Bench (Ant_17)](#hunters-march-trapped-bench-ant17) | R | none |  | Verified |  |
| L3 | left3 | L3 platform | [Hunter's March Early Pathway East (Ant_04)](#hunters-march-early-pathway-east-ant04) | R | none |  | Verified |  |
| L4 | left4 | the bottom | [Hunter's March Deep Docks Passage (Ant_05b)](#hunters-march-deep-docks-passage-ant05b) | R | none |  | Verified |  |
| UR | right2 | UR platform | [Hunter's March Statue (Ant_05c)](#hunters-march-statue-ant05c) | L | none |  | Verified |  |
| LR | right3 | the bottom | [Hunter's March Chapel Passage (Ant_20)](#hunters-march-chapel-passage-ant20) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | the bottom | L3 platform | ledge grab OR silk soar OR drifter's cloak OR faydown cloak |  | Verified |  |
| V1 | vertical 1 | L3 platform | the bottom | none (falling) |  | Verified |  |
| V2 | vertical 2 | the bottom | UR platform | ledge grab OR silk soar OR drifter's cloak OR faydown cloak |  | Verified |  |
| V2 | vertical 2 | UR platform | the bottom | none (falling) |  | Verified |  |
| F1 | falling 1 | UR platform | L3 platform | none (falling) |  | Verified |  |
| V3 | vertical 3 | UR platform | L2 platform | ledge grab OR silk soar OR drifter's cloak OR faydown cloak |  | Verified | got it with scuttlebrace exactly once LOL |
| V3 | vertical 3 | L2 platform | UR platform | none (falling) |  | Verified |  |
| V4 | vertical 4 | L2 platform | L1 platform | ledge grab OR silk soar OR drifter's cloak OR faydown cloak OR easy enemy pogo |  | Verified | can pogo off a fly to avoid the need for ledge grab bit of a pain |
| V4 | vertical 4 | L1 platform | L2 platform | none (falling) |  | Verified |  |
| V5 | vertical 5 | L1 platform | the top | silk soar OR cling grip OR faydown cloak OR easy scuttlebrace OR ledge grab |  | Verified | saying that ledge grab is needed for convenience |
| V5 | vertical 5 | the top | L1 platform | none (falling) |  | Verified |  |

#### Check Locations

No check locations defined.

### Hunter's March Trapped Bench (Ant_17)

**Game ID:** Ant_17

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | L2 | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| trapped bench |  | activate bench trap switch |  | Verified | bench |  |
| bench trap switch |  | flip switch up |  | Verified | switch |  |

### Hunter's March Skarr Shop (Ant_Merchant)

**Game ID:** Ant_Merchant

**Contributors:** herounit

#### Subrooms

- storage room
- skarr shop

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | storage room | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | L1 | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CG | cross gap | storage room | skarr shop | run OR dash OR faydown cloak OR clawline OR sharpdart x 3 |  | Verified | too many jumps for sharpdart without upgrades or silk heart; could add progressive spool fragments as a requirement for multiple sharpdart jumps |
| CG | cross gap | skarr shop | storage room | run OR dash OR faydown cloak OR clawline OR sharpdart x 3 |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| fractured mask | skarr shop | none |  | Verified | collectible |  |
| curveclaw | skarr shop | none |  | Verified | collectible | I think this item mistakenly displays in the treasure vault instead of the skarr shop |
| shell shard cache hunter's march 5 | storage room | none |  | Verified | collectible |  |
| shell shard cache hunter's march 6 | storage room | none |  | Verified | collectible |  |
| shell shard cache hunter's march 7 | storage room | none |  | Verified | collectible |  |
| shell shard cache hunter's march 8 | storage room | none |  | Verified | collectible |  |

### Hunter's March Treasure Vault (Ant_21)

**Game ID:** Ant_21

**Contributors:** herounit

#### Subrooms

- right of door
- left of door

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right of door | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | L5 | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| GF | grunt fight | left of door | right of door | defeat grunt fight |  | Verified |  |
| GF | grunt fight | right of door | left of door | defeat grunt fight |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache hunters march 4 | left of door | none |  | Verified | collectible |  |
| rosary cache hunters march 5 | left of door | none |  | Verified | collectible |  |
| rosary cache hunters march 6 | left of door | none |  | Verified | collectible |  |
| rosary cache hunters march 7 | left of door | none |  | Verified | collectible |  |
| rosary cache hunters march 8 | left of door | none |  | Verified | collectible |  |
| rosary cache hunters march 9 | left of door | none |  | Verified | collectible |  |
| rosary cache hunters march 10 | left of door | none |  | Verified | collectible |  |
| grunt fight | right of door | none |  | Verified | miniboss | pretty sure these two don't respawn |

### Hunter's March Statue (Ant_05c)

**Game ID:** Ant_05c

**Contributors:** herounit

#### Subrooms

- statue area
- right exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | statue area | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | UR | none |  | Verified |  |
| R | right1 | right exit area | [Hunter's March Deep Entrance (Ant_09)](#hunters-march-deep-entrance-ant09) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SS | silk soar spot | statue area | right exit area | silk soar |  | Verified |  |
| SS | silk soar spot | right exit area | statue area | none (falling) |  | Verified |  |

#### Check Locations

No check locations defined.

### Hunter's March Deep Docks Passage (Ant_05b)

**Game ID:** Ant_05b

**Contributors:** herounit

#### Subrooms

- before gate
- right of gauntlet
- gauntlet
- left of gauntlet

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | before gate | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | L4 | none |  | Verified |  |
| LF | bot1 | left of gauntlet | [Is this still Deep Docks? (West) (Bone_East_04b)](#is-this-still-deep-docks-west-boneeast04b) | C | none |  | Verified |  |
| RF | bot2 | right of gauntlet | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | C | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BG | bone gate | before gate | right of gauntlet | activate bone switch |  | Verified |  |
| BG | bone gate | right of gauntlet | before gate | activate bone switch |  | Verified |  |
| RG | right gauntlet | right of gauntlet | gauntlet | none (starts gauntlet) |  | Verified |  |
| RG | right gauntlet | gauntlet | right of gauntlet | defeat gauntlet fight |  | Verified |  |
| LG | left gauntlet | left of gauntlet | gauntlet | none (starts gauntlet) |  | Verified |  |
| LG | left gauntlet | gauntlet | left of gauntlet | defeat gauntlet fight |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bone switch | before gate | none |  | Verified | switch |  |
| gauntlet fight | gauntlet | none |  | Verified | gauntlet |  |

### Hunter's March Deep Entrance (Ant_09)

**Game ID:** Ant_09

**Contributors:** herounit

#### Subrooms

- left exit area
- below left exit
- right exit area
- free silk

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Hunter's March Statue (Ant_05c)](#hunters-march-statue-ant05c) | R | none |  | Verified |  |
| R | right1 | right exit area | [Far Fields Upper Shaft (Bone_East_11)](#far-fields-upper-shaft-boneeast11) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical access | below left exit | left exit area | silk soar OR cling grip OR ( faydown cloak AND ledge grab ) |  | Verified |  |
| V1 | vertical access | left exit area | below left exit | none (falling) |  | Verified |  |
| TC | thorn crossing | below left exit | right exit area | clawline x 4 AND silkhearts 1 AND faydown cloak |  | Verified |  |
| TC | thorn crossing | right exit area | below left exit | ( clawline x 4 AND faydown cloak AND silkhearts 1 ) OR ( clawline x 5 AND silkhearts 2 ) |  | Verified |  |
| SC | silk collection | right exit area | free silk | clawline x 2 |  | Verified |  |
| SC | silk collection | free silk | right exit area | clawline x 2 |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| free silk | free silk | none |  | Verified | resource | not yet randomized |

## Shellwood

### Cling Grip Room (Shellwood_10)

**Game ID:** Shellwood_10

**Contributors:** Pyxl

#### Subrooms

- Ground Level
- Central Level
- Upper Level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Upper Level | [Shellwood Top Room (Shellwood_26)](#shellwood-top-room-shellwood26) | L | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  | Verified |  |
| LR | right2 | Ground Level | [Shellwood Flower Pogo Upper Hall (Shellwood_20)](#shellwood-flower-pogo-upper-hall-shellwood20) | L | ( Dash AND Scuttlebrace ) OR Cling Grip OR Clawline OR Faydown Cloak OR Ledge Grab |  | Verified |  |
| ML | left2 | Central Level | [Cling Grip Side Room (Shellwood_11)](#cling-grip-side-room-shellwood11) | LR | Dash OR Sprint OR Clawline OR SharpDart OR easy Beast Crest pogo OR Faydown Cloak OR Drifters Cloak |  | Verified |  |
| UL | left1 | Upper Level | [Cling Grip Side Room (Shellwood_11)](#cling-grip-side-room-shellwood11) | UR | None |  | Verified |  |
| MR | right3 | Central Level | [Sister Splinter (Shellwood_18)](#sister-splinter-shellwood18) | L | ( Dash AND Scuttlebrace ) OR Cling Grip OR Clawline OR Faydown Cloak OR Ledge Grab |  | Verified |  |
| LL | left3 | Ground Level | [Shellwood Lower Left Tall Room (Shellwood_03)](#shellwood-lower-left-tall-room-shellwood03) | UR | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EP | taunt pogo | Ground Level | Central Level | ( Dash AND Scuttlebrace ) OR Cling Grip OR (( Faydown Cloak OR Easy enemy pogo ) AND ( Clawline OR  Sharpdart OR  Faydown Cloak ) ) OR Silk Soar |  | Verified |  |
| EP | taunt pogo | Central Level | Ground Level | None |  | Verified |  |
| OA | Open Area | Central Level | Upper Level | Silk Soar OR ( Easy enemy pogo AND Cling Grip AND Faydown Cloak ) |  | Verified |  |
| OA | Open Area | Upper Level | Central Level | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cling Grip | Upper Level | None |  | Verified | collectible |  |
| Pollip Heart #5 | Central Level | None |  | Verified | collectible |  |
| Shellwood - Weaver Harp Inscryption | Ground Level | Needolin |  | Verified | lore |  |

### Cling Grip Side Room (Shellwood_11)

**Game ID:** Shellwood_11

**Contributors:** Pyxl

#### Subrooms

- Upper Level
- Lower Level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | right2 | Lower Level | [Cling Grip Room (Shellwood_10)](#cling-grip-room-shellwood10) | ML | None |  | Verified |  |
| UR | right1 | Upper Level | [Cling Grip Room (Shellwood_10)](#cling-grip-room-shellwood10) | UL | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FP | Flower Pogos | Lower Level | Upper Level | ( Easy enemy pogo AND Swim ) OR Dash OR Sprint OR SharpDart OR easy Beast Crest pogo OR Faydown Cloak OR Drifters Cloak OR Clawline OR ( Dash AND Scuttlebrace ) OR Cling Grip OR Silk Soar |  | Verified |  |
| FP | Flower Pogos | Upper Level | Lower Level | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosaries | Upper Level | None | TODO | Verified | resource | Not included rn |

### Greyroot (Room_Witch)

**Game ID:** Room_Witch

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Greyroot Entrance (Shellwood_Witch)](#shellwood-greyroot-entrance-shellwoodwitch) | D | None |  | Verified |  |
| QR | Quest Rebirth |  | [Witch Chapel (Shellwood_25b)](#witch-chapel-shellwood25b) | QR | complete rite of rebirth wish promised |  | Verified | One way one use Teleport |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rite of the pollip wish promised |  | none |  | Verified | event |  |
| rite of the pollip wish granted |  | complete rite of the pollip wish promised AND Pollip Hearts 6 |  | Verified | event |  |
| Pollip Pouch |  | complete rite of the pollip wish granted |  | Verified | collectible |  |
| rite of rebirth wish promised |  | complete rite of the pollip wish granted  AND have twisted bud |  | Verified | event |  |
| rite of rebirth wish granted |  | complete rite of rebirth wish promised |  | Verified | event |  |
| Crest Cursed |  | complete rite of rebirth wish granted |  | Verified | collectible |  |

### Greyroots Basement Tall room (Mosstown_03)

**Game ID:** Mosstown_03

**Contributors:** Pyxl

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right2 | Top | [Shellwood Diddy Basement Main (Shellwood_25)](#shellwood-diddy-basement-main-shellwood25) | L | None |  | Verified |  |
| LR | right1 | Bottom | [The Marrow Skull Wall (Bone_06)](#the-marrow-skull-wall-bone06) | L | clear blast rock exit blockade |  | Verified |  |
| C | top1 | Top | [Shellwood Lower Left Tall Room (Shellwood_03)](#shellwood-lower-left-tall-room-shellwood03) | F | Cling Grip |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SH | Shaft | Top | Bottom | None |  | Verified |  |
| SH | Shaft | Bottom | Top | Silksoar OR Cling grip |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Shellwood #1 | Top | None |  | Verified | resource |  |
| Bench Diddy Basement | Bottom | Cling Grip OR ( Dash AND Scuttlebrace ) |  | Verified | bench |  |
| Craw Summons | Bottom | Craw Summons Ready |  | Verified | collectible |  |
| Shell Shard Cache: Shellwood #2 | Top | None |  | Verified | resource |  |
| Shell Shard Cache: Shellwood #3 | Top | None |  | Verified | resource |  |
| Breakable Roof Diddy Basement | Top | Cling Grip |  | Verified | blockade |  |
| Blast Rock Exit Blockade | Bottom | break blast rock right |  | Verified | blockade |  |

### Long Pin (Belltown_Room_shellwood)

**Game ID:** Belltown_Room_shellwood

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Right Side Big room (Shellwood_01)](#shellwood-right-side-big-room-shellwood01) | UR | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Long pin |  | None |  | Verified | collectible |  |

### Shellgrave (Shellgrave)

**Game ID:** Shellgrave

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 |  | [Shellwood Left side Long pond room (Shellwood_04b)](#shellwood-left-side-long-pond-room-shellwood04b) | RC | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache |  | None |  | Verified | resource | Not included no id |

### Shellwood Bellshrine (Bellshrine_03)

**Game ID:** Bellshrine_03

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Connection To Blasted steps (Shellwood_08)](#shellwood-connection-to-blasted-steps-shellwood08) | R | None |  | Verified |  |
| R | right1 |  | [Shellwood Bellway  (Shellwood_19)](#shellwood-bellway) | L | ( bellshrinesanity off AND activate bellshrine switch )  OR ( bellshrinesanity on AND have bell shellwood ) |  | Verified | must keep in sync with the other side |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bell: Shellwood |  | activate bellshrine switch |  | Verified | collectible |  |
| bench |  | activate bellshrine switch |  | Verified | bench |  |
| bellshrine switch |  | flip switch down |  | Verified | switch |  |

### Shellwood Bellway
 (Shellwood_19)

**Game ID:** Shellwood_19

**Contributors:** Pyxl

#### Subrooms

- Left Puddle
- Right Puddle

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right Puddle | [Shellwood Lower Left Tall Room (Shellwood_03)](#shellwood-lower-left-tall-room-shellwood03) | UL | None |  | Verified |  |
| L | left1 | Left Puddle | [Shellwood Bellshrine (Bellshrine_03)](#shellwood-bellshrine-bellshrine03) | R | ( bellshrinesanity off AND activate bellshrine switch IN shellwood bellshrine )  OR ( bellshrinesanity on AND have bell shellwood ) |  | Verified | Might also need switch from other side, needs testing |
| BB | door_fastTravelExit | Right Puddle | [Bellway Menu](#bellway-menu) | SW | Unlock Shellwood Bellway |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PU | Puddle | Left Puddle | Right Puddle | Swim OR Dash OR Sprint OR Clawline OR Sharpdart OR Easy Beast Crest pogo OR Drifters Cloak OR Faydown Cloak |  | Verified |  |
| PU | Puddle | Right Puddle | Left Puddle | Swim OR Dash OR Sprint OR Clawline OR Sharpdart OR Easy Beast Crest pogo OR Drifters Cloak OR Faydown Cloak |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shellwood Bellway | Right Puddle | Unlock Bellway Rosary Lock |  | Verified | travel |  |
| Bellway Rosary Lock | Right Puddle | Rosaries 40 |  | Verified | lock |  |

### Shellwood Big Room Left (Shellwood_02)

**Game ID:** Shellwood_02

**Contributors:** Pyxl

#### Subrooms

- Ceiling area
- Ground Left
- Platforms
- Ground Centre
- Ground Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Ceiling area | [Shellwood Sister Splinter Bench (Shellwood_01b)](#shellwood-sister-splinter-bench-shellwood01b) | LL | None |  | Verified |  |
| LL | left2 | Ground Left | [shellwood Shakra (Shellwood_16)](#shellwood-shakra-shellwood16) | R | None |  | Verified |  |
| UL | left3 | Platforms | [Shellwood Greyroot Entrance (Shellwood_Witch)](#shellwood-greyroot-entrance-shellwoodwitch) | R | None |  | Verified |  |
| LR | right2 | Ground Right | [Shellwood Right Side Big room (Shellwood_01)](#shellwood-right-side-big-room-shellwood01) | LL | NOne |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EL | Elevator | Ground Centre | Ceiling area | Prereq Elevator Button |  | Verified |  |
| EL | Elevator | Ceiling area | Ground Centre | Prereq Elevator Button |  | Verified |  |
| RL | Right Lake | Ground Centre | Ground Right | ( Enemy Pogo AND Ledge Grab ) OR Dash OR Sprint OR clawline OR Easy Beast Crest Pogo OR Faydown Cloak OR Drifters Cloak OR ( Swim AND Ledge Grab ) |  | Verified |  |
| RL | Right Lake | Ground Right | Ground Centre | ( Enemy Pogo AND Ledge Grab ) OR Dash OR Sprint OR clawline OR Easy Beast Crest Pogo OR Faydown Cloak OR Drifters Cloak OR ( Swim AND Ledge Grab ) |  | Verified |  |
| LL | Left Lake | Ground Centre | Ground Left | ( Enemy Pogo AND Ledge Grab ) OR Dash OR Sprint OR clawline OR Easy Beast Crest Pogo OR Faydown Cloak OR Drifters Cloak |  | Verified |  |
| LL | Left Lake | Ground Left | Ground Centre | None |  | Verified |  |
| LP | Left Platforms | Platforms | Ground Left | None |  | Verified |  |
| LP | Left Platforms | Ground Left | Platforms | ( Faydown Cloak AND ( Cling Grip OR ( ScuttleBrace AND Dash ) ) ) OR Silk Soar OR ( Hard Enemy Pogo ) |  | Verified |  |
| CP | Central Platforms | Platforms | Ground Centre | None |  | Verified |  |
| CP | Central Platforms | Ground Centre | Platforms | ( Faydown Cloak AND Ledge Grab ) OR Silk Soar |  | Verified |  |
| RP | Right Platforms | Platforms | Ground Right | None |  | Verified |  |
| RP | Right Platforms | Ground Right | Platforms | Silk Soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pollip Heart #6 | Platforms | Ledge Grab OR Silk Soar OR Faydown Cloak |  | Verified | collectible |  |
| Elevator Button | Ceiling area | None |  | Verified | switch |  |
| Big Door Button | Ground Right | None |  | Verified | switch |  |

### Shellwood Connection To Blasted steps (Shellwood_08)

**Game ID:** Shellwood_08

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Shellwood Bellshrine (Bellshrine_03)](#shellwood-bellshrine-bellshrine03) | L | None |  | Verified |  |
| L | left1 |  | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | R | None |  | Verified |  |
| F | bot1 |  | [shellwood Far Left Tall Room (Shellwood_04c)](#shellwood-far-left-tall-room-shellwood04c) | C | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Shellwood Diddy Basement Main (Shellwood_25)

**Game ID:** Shellwood_25

**Contributors:** Pyxl

#### Subrooms

- Left Corridor
- Left Puddles
- Right Puddles
- Right Corridor

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Corridor | [Greyroots Basement Tall room (Mosstown_03)](#greyroots-basement-tall-room-mosstown03) | UR | None |  | Verified |  |
| D | door1 | Right Corridor | [Witch Chapel (Shellwood_25b)](#witch-chapel-shellwood25b) | L | INVALID |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LW | Left Wall | Left Corridor | Left Puddles | Cling Grip OR Silk soar OR Faydown Cloak OR ( Dash AND Scuttlebrace ) |  | Verified |  |
| LW | Left Wall | Left Puddles | Left Corridor | None |  | Verified |  |
| PU | Puddles | Left Puddles | Right Puddles | Swim OR Clawline OR Sharpdart OR Drifters Cloak OR Easy Enemy Pogo |  | Verified |  |
| PU | Puddles | Right Puddles | Left Puddles | Swim OR Clawline OR Sharpdart OR Drifters Cloak OR Easy Enemy Pogo |  | Verified |  |
| RW | Right Wall | Right Puddles | Right Corridor | Cling Grip OR Silk soar OR Faydown Cloak OR ( Dash AND Scuttlebrace ) |  | Verified |  |
| RW | Right Wall | Right Corridor | Right Puddles | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary String: Shellwood #2 | Left Puddles | Cling Grip OR Silk Soar OR ( Faydown Cloak AND Easy Shaman Crest pogo ) OR ( Dash AND Scuttlebrace ) |  | Verified | collectible |  |
| Relic: Weaver effigy (Keelal, Shellwood) | Right Corridor | Cling Grip AND Swim AND ( Clawline OR Faydown Cloak OR Drifters Cloak OR Sharpdart OR Easy Beast Crest pogo OR Sprint OR Dash ) |  | Verified | collectible |  |

### Shellwood Flower Pogo Upper Hall (Shellwood_20)

**Game ID:** Shellwood_20

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Shellwood Sister Splinter Bench (Shellwood_01b)](#shellwood-sister-splinter-bench-shellwood01b) | UL | None |  | Verified |  |
| L | left1 |  | [Cling Grip Room (Shellwood_10)](#cling-grip-room-shellwood10) | LR | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pollip Heart #3 |  | None |  | Verified | collectible |  |

### Shellwood Greyroot Entrance (Shellwood_Witch)

**Game ID:** Shellwood_Witch

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 |  | [Greyroot (Room_Witch)](#greyroot-roomwitch) | L | None |  | Verified |  |
| R | right1 |  | [Shellwood Big Room Left (Shellwood_02)](#shellwood-big-room-left-shellwood02) | UL | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Shellwood Hidden Bellhart Connection (Shellwood_15)

**Game ID:** Shellwood_15

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Sister Splinter Bench (Shellwood_01b)](#shellwood-sister-splinter-bench-shellwood01b) | MR | Faydown Cloak OR ( Drifters Cloak AND Ledge Grab ) OR ( Dash AND Ledge Grab )  OR Clawline OR Sharpdart OR easy Beast Crest pogo |  | Verified |  |
| R | right1 |  | [Upper Bellhart (Belltown_04)](#upper-bellhart-belltown04) | LL | Faydown Cloak OR Drifters Cloak OR Dash OR Clawline OR Sharpdart OR easy Beast Crest pogo |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pollip Heart #2 |  | Faydown Cloak OR Drifters Cloak OR Dash OR Clawline OR Sharpdart OR easy Beast Crest pogo |  | Verified | collectible |  |
| Shellwood 15 Wall |  | None |  | Verified | blockade |  |

### Shellwood Left side Long pond room (Shellwood_04b)

**Game ID:** Shellwood_04b

**Contributors:** Pyxl

#### Subrooms

- Right Lake
- Left Lake

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right Lake | [Shellwood Lower Left Tall Room (Shellwood_03)](#shellwood-lower-left-tall-room-shellwood03) | LL | None |  | Verified |  |
| RC | top2 | Right Lake | [Shellgrave (Shellgrave)](#shellgrave-shellgrave) | F | Ledge grab OR Faydown Cloak OR Silk Soar OR Enemy Pogo |  | Verified |  |
| L | left1 | Left Lake | [Shellwood Lower Toll bench (Shellwood_08c)](#shellwood-lower-toll-bench-shellwood08c) | R | Break Vines Left |  | Verified |  |
| LC | top1 | Left Lake | [shellwood Far Left Tall Room (Shellwood_04c)](#shellwood-far-left-tall-room-shellwood04c) | F | Enemy Pogo OR Cling grip OR Silk soar OR Faydown Cloak OR ( Dash AND Scuttlebrace ) |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PC | Pond Crossing | Left Lake | Right Lake | Swim OR Clawline OR ( Sprint AND Drifters Cloak ) OR ( Faydown Cloak AND Enemy Pogo ) OR ( Drifters Cloak AND Enemy Pogo ) |  | Verified |  |
| PC | Pond Crossing | Right Lake | Left Lake | Swim OR Clawline OR ( Sprint AND Drifters Cloak ) OR ( Faydown Cloak AND Enemy Pogo ) OR ( Drifters Cloak AND Enemy Pogo ) |  | Verified |  |

#### Check Locations

No check locations defined.

### Shellwood Lower Left Tall Room (Shellwood_03)

**Game ID:** Shellwood_03

**Contributors:** Pyxl

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | Top | [Shellwood Bellway  (Shellwood_19)](#shellwood-bellway) | R | Sprint OR Dash OR clawline OR silksoar OR Sharpdart OR Drifters Cloak OR Faydown Cloak OR Easy Beast Crest Pogo |  | Verified |  |
| F | bot1 | Bottom | [Greyroots Basement Tall room (Mosstown_03)](#greyroots-basement-tall-room-mosstown03) | C | Clear Breakable Roof Diddy Basement IN Shellwood Diddy Basement Tall room |  | Verified | Help |
| MR | right2 | Top | [Shellwood Mask Shard Room (Shellwood_14)](#shellwood-mask-shard-room-shellwood14) | L | None |  | Verified |  |
| LL | left3 | Bottom | [Shellwood Left side Long pond room (Shellwood_04b)](#shellwood-left-side-long-pond-room-shellwood04b) | R | None |  | Verified |  |
| UR | right1 | Top | [Cling Grip Room (Shellwood_10)](#cling-grip-room-shellwood10) | LL | Ledge Grab OR Faydown Cloak OR Silk Soar OR Cling Grip |  | Verified |  |
| LR | right3 | Bottom | [shellwood Shakra (Shellwood_16)](#shellwood-shakra-shellwood16) | L | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FP | Flower Pogo | Bottom | Top | Ledge Grab OR Cling Grip OR Silk Soar |  | Verified |  |
| FP | Flower Pogo | Top | Bottom | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Shellwood | Top | None |  | Verified | collectible |  |

### Shellwood Lower Toll bench (Shellwood_08c)

**Game ID:** Shellwood_08c

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | UR | None |  | Verified |  |
| R | right1 |  | [Shellwood Left side Long pond room (Shellwood_04b)](#shellwood-left-side-long-pond-room-shellwood04b) | L | Break Vines Right |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lower Shellwood Toll Bench |  | None |  | Verified | bench |  |
| Craw Summons |  | Craw Summons Ready |  | Verified | collectible |  |

### Shellwood Mask Shard Room (Shellwood_14)

**Game ID:** Shellwood_14

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Lower Left Tall Room (Shellwood_03)](#shellwood-lower-left-tall-room-shellwood03) | MR | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mask Shard: Shellwood #12 |  | Ledge Grab OR Dash OR Clawline OR Faydown Cloak OR Drifters Cloak OR Easy Beast Crest pogo |  | Verified | collectible |  |

### Shellwood Right Side Big room (Shellwood_01)

**Game ID:** Shellwood_01

**Contributors:** Pyxl

#### Subrooms

- Ground Level Left
- Central Platforms
- Right Platforms
- Ground Level Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Right Platforms | [Long Pin (Belltown_Room_shellwood)](#long-pin-belltownroomshellwood) | L | Prereq Longpin Nest |  | Verified |  |
| UL | left1 | Central Platforms | [Shellwood Sister Splinter Bench (Shellwood_01b)](#shellwood-sister-splinter-bench-shellwood01b) | LR | None |  | Verified |  |
| LR | right2 | Ground Level Right | [Bellhart Hallway to Shellwood (Belltown_07)](#bellhart-hallway-to-shellwood-belltown07) | L | None |  | Verified |  |
| LL | left2 | Ground Level Left | [Shellwood Big Room Left (Shellwood_02)](#shellwood-big-room-left-shellwood02) | LR | Prereq Big Door Button IN Shellwood Big Room Left |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LA | Lake | Ground Level Left | Ground Level Right | ( Dash AND ( Sprint OR Drifters Cloak ) ) OR Clawline OR Sharpdart OR Swim OR ( Faydown Cloak AND Drifters Cloak ) |  | Verified |  |
| LA | Lake | Ground Level Right | Ground Level Left | ( Dash AND ( Sprint OR Drifters Cloak ) ) OR Clawline OR Sharpdart OR Swim OR ( Faydown Cloak AND Drifters Cloak ) |  | Verified |  |
| C1 | Chasm 1 | Ground Level Left | Central Platforms | ( Ledge Grab AND ( Dash OR Drifters Cloak OR Easy Beast Crest pogo ) ) OR Clawline OR Cling Grip OR Silk Soar OR Sharpdart OR Faydown Cloak |  | Verified |  |
| C1 | Chasm 1 | Central Platforms | Ground Level Left | None |  | Verified |  |
| C2 | Chasm 2 | Central Platforms | Right Platforms | Ledge Grab OR Faydown Cloak OR Silk Soar OR Cling grip OR Dash OR Scuttlebrace OR Clawline  OR Sprint |  | Verified |  |
| C2 | Chasm 2 | Right Platforms | Central Platforms | None |  | Verified |  |
| C3 | Chasm 3 | Right Platforms | Ground Level Right | None |  | Verified |  |
| C3 | Chasm 3 | Ground Level Right | Right Platforms | Silk Soar OR ( Cling Grip AND Faydown Cloak  AND ( Swim OR ( Easy Enemy Pogo AND ( Sprint OR Dash ) ) OR Drifters Cloak OR Clawline OR Sharpdart ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shellwood - Frayed Rosary String | Central Platforms | None |  | Verified | collectible |  |
| Pollip Heart #1 | Right Platforms | Cling Grip OR Silk Soar OR Scuttlebrace |  | Verified | collectible |  |
| Shell shard Cache: Shellwood #4 | Right Platforms | None |  | Verified | resource |  |
| Shell shard Cache: Shellwood #5 | Right Platforms | None |  | Verified | resource |  |
| Shell shard Cache: Shellwood #6 | Right Platforms | None |  | Verified | resource |  |
| Longpin Nest | Right Platforms | None |  | Verified | blockade |  |

### Shellwood Sister Splinter Bench (Shellwood_01b)

**Game ID:** Shellwood_01b

**Contributors:** Pyxl

#### Subrooms

- Above Arena
- Arena
- Bench Toll
- Elevator Platform
- Upper Main
- Upper Hidden

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Elevator Platform | [Shellwood Upper Bellhart Entrance (Shellwood_13)](#shellwood-upper-bellhart-entrance-shellwood13) | LL | None |  | Verified |  |
| LR | right2 | Bench Toll | [Shellwood Right Side Big room (Shellwood_01)](#shellwood-right-side-big-room-shellwood01) | UL | None |  | Verified |  |
| MR | right3 | Upper Hidden | [Shellwood Hidden Bellhart Connection (Shellwood_15)](#shellwood-hidden-bellhart-connection-shellwood15) | L | activate Shellwood 15 Wall IN Shellwood Hidden Bellhart Connection |  | Verified |  |
| UL | left1 | Upper Main | [Shellwood Flower Pogo Upper Hall (Shellwood_20)](#shellwood-flower-pogo-upper-hall-shellwood20) | R | None |  | Verified |  |
| LL | left2 | Above Arena | [Shellwood Big Room Left (Shellwood_02)](#shellwood-big-room-left-shellwood02) | UR | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AD | Arena Drop | Above Arena | Arena | None |  | Verified |  |
| AD | Arena Drop | Arena | Above Arena | Silk Soar |  | Verified |  |
| AE | Arena Exit | Arena | Bench Toll | Ledge Grab OR ( Dash AND Scuttlebrace ) OR Clawline OR Cling Grip OR Faydown Cloak OR Silk Soar |  | Verified |  |
| AE | Arena Exit | Bench Toll | Arena | None |  | Verified |  |
| CL1 | Climb 1 | Bench Toll | Upper Hidden | ( Cling Grip AND ( Clawline OR Dash OR Sharpdart OR Drifters Cloak OR Faydown Cloak OR easy Beast Crest pogo ) ) OR Silk Soar |  | Verified |  |
| CL1 | Climb 1 | Upper Hidden | Bench Toll | None |  | Verified |  |
| EL | Elevator | Bench Toll | Elevator Platform | Activate Shellwood Elevator Button 2 |  | Verified |  |
| EL | Elevator | Elevator Platform | Bench Toll | Activate Shellwood Elevator Button 2 |  | Verified |  |
| CL2 | Climb 2 | Upper Main | Bench Toll | None |  | Verified |  |
| CL2 | Climb 2 | Bench Toll | Upper Main | Cling Grip OR Silk Soar |  | Verified |  |
| HP | Hidden Path | Upper Main | Upper Hidden | None |  | Verified |  |
| HP | Hidden Path | Upper Hidden | Upper Main | None |  | Verified |  |
| EP | Elevator Platform | Upper Main | Elevator Platform | None |  | Verified |  |
| EP | Elevator Platform | Elevator Platform | Upper Main | Ledge Grab OR ( Dash AND Scuttlebrace ) OR Clawline OR Cling Grip OR Faydown Cloak OR Silk Soar |  | Verified |  |
| CL3 | Climb 3 | Above Arena | Bench Toll | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  | Verified |  |
| CL3 | Climb 3 | Bench Toll | Above Arena | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary String: Shellwood #1 | Upper Hidden | None |  | Verified | collectible |  |
| Sister Splinter Toll Bench | Bench Toll | None |  | Verified | bench |  |
| Craw Summons | Bench Toll | Craw Summons Ready |  | Verified | collectible |  |
| Shellwood Elevator Button 2 | Elevator Platform | None |  | Verified | switch |  |

### Shellwood Top Room (Shellwood_26)

**Game ID:** Shellwood_26

**Contributors:** Pyxl

#### Subrooms

- Left Side
- Central
- Right Side
- Upper Area
- Pollip Room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Side | [Cling Grip Room (Shellwood_10)](#cling-grip-room-shellwood10) | UR | None |  | Verified |  |
| F | bot1 | Right Side | [Sister Splinter (Shellwood_18)](#sister-splinter-shellwood18) | C | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LW | Left Wall | Left Side | Central | Cling Grip OR Faydown Cloak OR Silk Soar OR ( Dash AND Scuttlebrace ) |  | Verified |  |
| LW | Left Wall | Central | Left Side | Cling Grip OR Faydown Cloak OR Silk Soar OR ( Dash AND Scuttlebrace ) |  | Verified |  |
| RW | Right Wall | Central | Right Side | ( Swim OR ( Drifters Cloak  AND Easy enemy pogo ) ) AND ( Cling Grip OR Scuttlebrace ) |  | Verified |  |
| RW | Right Wall | Right Side | Central | Cling Grip OR Faydown Cloak OR Silk Soar OR ( Dash AND Scuttlebrace ) |  | Verified |  |
| HS | Hidden Shaft | Pollip Room | Upper Area | prereq Shellwood 26 Wall AND Silk Soar |  | Verified |  |
| HS | Hidden Shaft | Upper Area | Pollip Room | prereq Shellwood 26 Wall |  | Verified |  |
| CC | Central Shaft | Central | Upper Area | Cling Grip AND ( ( Swim OR Clawline OR Drifters Cloak OR Sharpdart OR ( easy Beast Crest pogo AND Dash ) OR ( Sprint AND Dash ) ) OR ( Dash AND Scuttlebrace AND ( Swim OR Clawline OR Easy enemy pogo OR Faydown Cloak ) ) ) |  | Verified |  |
| CC | Central Shaft | Upper Area | Central | None |  | Verified |  |
| PH | Pollip Hole | Central | Pollip Room | Silk Soar OR ( Faydown Cloak AND ( Ledge Grab OR Cling Grip ) ) |  | Verified |  |
| PH | Pollip Hole | Pollip Room | Central | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pollip Heart #4 | Pollip Room | Cling Grip OR Silk Soar OR Clawline OR ( Faydown Cloak AND ( Ledge Grab OR Clawline ) ) |  | Verified | collectible |  |
| Rosary cache: Shellwood | Right Side | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  | Verified | resource |  |
| Resting Site: Shellwood | Right Side | prereq Wish: A vassal Lost started AND Steel Soul |  | Verified | collectible |  |
| Wish: A Vassal Lost Started | Right Side | None |  | Verified | event |  |
| Shellwood 26 Wall | Upper Area | None |  | Verified | blockade |  |

### Shellwood Upper Bellhart Entrance (Shellwood_13)

**Game ID:** Shellwood_13

**Contributors:** Pyxl

#### Subrooms

- Left Pond
- Right Pond
- Bell Ledge
- Upper Area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | Upper Area | [Sister Splinter (Shellwood_18)](#sister-splinter-shellwood18) | R | ((( Easy Hunter Crest pogo OR Easy Beast Crest pogo OR medium Architect Crest pogo ) AND Ledge Grab) OR ( Medium Heal Stall AND ( medium Reaper Crest pogo OR Hard Shaman Crest pogo OR easy Wanderer Crest pogo OR hard Witch Crest pogo ) ) ) OR Clawline OR Dash OR Drifter's Cloak OR Faydown Cloak OR Sharpdart |  | Verified |  |
| R | right1 | Bell Ledge | [Upper Bellhart (Belltown_04)](#upper-bellhart-belltown04) | UL | None |  | Verified |  |
| LL | left2 | Left Pond | [Shellwood Sister Splinter Bench (Shellwood_01b)](#shellwood-sister-splinter-bench-shellwood01b) | UR | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bell Ledge | Bell Ledge | Upper Area | None |  | Verified |  |
| BL | Bell Ledge | Upper Area | Bell Ledge | Cling Grip OR Faydown Cloak OR Silk soar OR ( Dash AND Scuttlebrace ) |  | Verified |  |
| PO | Pond | Left Pond | Right Pond | Swim OR Clawline OR (Drifter's Cloak AND (Faydown Cloak OR (Sprint AND Dash) OR (Sharpdart AND Ledge Grab))) OR (Faydown Cloak AND Sharpdart AND (Dash OR easy Beast Crest pogo )) |  | Verified |  |
| PO | Pond | Right Pond | Left Pond | Swim OR ( Clawline AND ( Ledge Grab OR Dash OR Sharpdart OR easy beast Crest pogo OR Faydown Cloak ) ) OR ( Sprint AND ( ( Sharpdart AND Dash ) OR ( Sharpdart AND easy Beast Crest pogo ) OR ( Faydown Cloak AND Drifters Cloak ) OR ( Sharpdart AND Drifters Cloak) OR ( Faydown Cloak AND Sharpdart ) ) ) |  | Verified |  |
| PL | Platforms | Upper Area | Right Pond | None |  | Verified |  |
| PL | Platforms | Right Pond | Upper Area | Ledge Grab OR Dash OR Clawline OR Faydown Cloak OR Cling Grip OR Silk soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shard Bundle: Shellwood | Upper Area | (Cling Grip AND Faydown Cloak ) OR Silk Soar OR ( Faydown Cloak AND Dash AND Scuttlebrace ) |  | Verified | collectible |  |

### Sister Splinter (Shellwood_18)

**Game ID:** Shellwood_18

**Contributors:** Pyxl

#### Subrooms

- Arena Side
- Right Side

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Arena Side | [Cling Grip Room (Shellwood_10)](#cling-grip-room-shellwood10) | MR | None |  | Verified |  |
| R | right1 | Right Side | [Shellwood Upper Bellhart Entrance (Shellwood_13)](#shellwood-upper-bellhart-entrance-shellwood13) | UL | None |  | Verified |  |
| C | top1 | Right Side | [Shellwood Top Room (Shellwood_26)](#shellwood-top-room-shellwood26) | F | Cling Grip OR ( Dash AND Scuttlebrace ) |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PU | Puddle | Arena Side | Right Side | Swim OR ( Cling Grip AND Ledge grab ) OR Dash OR Clawline OR SharpDart OR Drifters Cloak OR Faydown Cloak OR easy Beast Crest pogo |  | Verified |  |
| PU | Puddle | Right Side | Arena Side | Swim OR Dash OR Clawline OR SharpDart OR Drifters Cloak OR Faydown Cloak OR easy Beast Crest pogo |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Sister Splinter | Arena Side | None |  | Verified | boss |  |

### Witch Chapel (Shellwood_25b)

**Game ID:** Shellwood_25b

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left1 |  | [Shellwood Diddy Basement Main (Shellwood_25)](#shellwood-diddy-basement-main-shellwood25) | D | None |  | Verified |  |
| QR | Quest Rebirth |  | [Greyroot (Room_Witch)](#greyroot-roomwitch) | QR | invalid |  | Verified | 1 way 1 use teleport from other side this is here just for the link |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### shellwood Far Left Tall Room (Shellwood_04c)

**Game ID:** Shellwood_04c

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 |  | [Shellwood Connection To Blasted steps (Shellwood_08)](#shellwood-connection-to-blasted-steps-shellwood08) | F | ( Faydown Cloak AND Hard enemy pogo ) OR cling grip OR silk soar OR ( Dash AND Medium Scuttlebrace AND Faydown Cloak ) |  | Verified |  |
| F | bot1 |  | [Shellwood Left side Long pond room (Shellwood_04b)](#shellwood-left-side-long-pond-room-shellwood04b) | LC | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### shellwood Shakra (Shellwood_16)

**Game ID:** Shellwood_16

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Lower Left Tall Room (Shellwood_03)](#shellwood-lower-left-tall-room-shellwood03) | LR | None |  | Verified |  |
| R | right1 |  | [Shellwood Big Room Left (Shellwood_02)](#shellwood-big-room-left-shellwood02) | LL | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map: Shellwood |  | None |  | Verified | collectible |  |

## Bellhart

### Bellhart Bellway (Belltown_basement)

**Game ID:** Belltown_basement

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 |  | [Bellhart Lower (Belltown_basement_03)](#bellhart-lower-belltownbasement03) | C | None |  | Verified |  |
| L | left1 |  | [Belltown (Belltown)](#belltown-belltown) | BD | Ledge Grab OR Clawline OR Faydown Cloak OR Cling Grip OR Silk Soar |  | Verified |  |
| BH | door_fastTravelExit |  | [Bellway Menu](#bellway-menu) | BH | unlock Bellway Bellhart |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bellway rosary lock |  | none |  | Verified | lock |  |
| Bellway: Bellhart |  | unlock bellway rosary lock |  | Verified | travel |  |

### Bellhart Hallway to Shellwood (Belltown_07)

**Game ID:** Belltown_07

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Right Side Big room (Shellwood_01)](#shellwood-right-side-big-room-shellwood01) | LR | None |  | Verified |  |
| R | right1 |  | [Belltown (Belltown)](#belltown-belltown) | L | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Bellhart #4 |  | Cling Grip OR Silk soar OR ( Dash AND Scuttlebrace AND Faydown Cloak ) |  | Verified | resource |  |
| Bellhart- Outer Sign |  | None |  | Verified | lore |  |

### Bellhart Lower (Belltown_basement_03)

**Game ID:** Belltown_basement_03

**Contributors:** Pyxl

#### Subrooms

- Top Exit
- Hermit
- Upper Hall
- Under Hermit Hall
- Rosary Room
- Passage below rosary
- Breakable Wall Passage
- Lower Passage 1
- Lower Passage 2
- Bottom Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | Top Exit | [Bellhart Bellway (Belltown_basement)](#bellhart-bellway-belltownbasement) | F | None |  | Verified |  |
| L | left1 | Bottom Exit | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | UR | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PL | Platforms Upper | Top Exit | Hermit | None |  | Verified |  |
| PL | Platforms Upper | Hermit | Top Exit | Clawline OR Ledge Grab OR easy Shaman Crest pogo OR ( Dash AND Scuttlebrace ) OR Faydown Cloak OR Silk Soar OR  Cling Grip |  | Verified |  |
| UP | Upper Hall | Hermit | Upper Hall | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| UP | Upper Hall | Upper Hall | Hermit | None |  | Verified |  |
| TL | Tall Passage Left | Upper Hall | Under Hermit Hall | None |  | Verified |  |
| TL | Tall Passage Left | Under Hermit Hall | Upper Hall | Cling Grip OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| HH | Hermit Hole | Hermit | Under Hermit Hall | prereq Hermit hole breakable wall |  | Verified |  |
| HH | Hermit Hole | Under Hermit Hall | Hermit | prereq Hermit hole breakable wall  AND ( Cling Grip OR Silk Soar OR Scuttlebrace ) |  | Verified |  |
| TR | Tall Passage Right | Under Hermit Hall | Rosary Room | None |  | Verified |  |
| TR | Tall Passage Right | Rosary Room | Under Hermit Hall | Cling Grip OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| WS | Wide Shaft | Rosary Room | Passage below rosary | None |  | Verified |  |
| WS | Wide Shaft | Passage below rosary | Rosary Room | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| RS | Shaft near Rosary Cache | Passage below rosary | Breakable Wall Passage | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| RS | Shaft near Rosary Cache | Breakable Wall Passage | Passage below rosary | None |  | Verified |  |
| BW | Broken Floor Shaft | Breakable Wall Passage | Under Hermit Hall | prereq Breakable Wall Passage Breakable Wall AND ( Cling Grip OR Scuttlebrace ) |  | Verified |  |
| BW | Broken Floor Shaft | Under Hermit Hall | Breakable Wall Passage | prereq Breakable Wall Passage Breakable Wall |  | Verified |  |
| BL | Tall Passage Bottom Left | Breakable Wall Passage | Lower Passage 1 | None |  | Verified |  |
| BL | Tall Passage Bottom Left | Lower Passage 1 | Breakable Wall Passage | Cling Grip OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| LV | Lower Passages Shaft | Lower Passage 1 | Lower Passage 2 | None |  | Verified |  |
| LV | Lower Passages Shaft | Lower Passage 2 | Lower Passage 1 | Cling Grip OR ( Scuttlebrace AND Dash ) |  | Verified |  |
| WP | Wide Platform Shaft | Lower Passage 2 | Passage below rosary | prereq Lower Passage 2 Breakable Wall AND ( Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace AND ( Ledge Grab OR Clawline OR Faydown Cloak OR Sharpdart OR easy Beast Crest pogo ) ) ) |  | Verified |  |
| WP | Wide Platform Shaft | Passage below rosary | Lower Passage 2 | prereq Lower Passage 2 Breakable Wall AND ( Dash OR Sprint OR Ledge grab OR Clawline OR Drifters Cloak OR Faydown Cloak OR Cling grip OR easy Shaman Crest pogo OR easy Architect Crest pogo OR easy Beast Crest pogo ) |  | Verified |  |
| ES | Exit Shaft | Lower Passage 2 | Bottom Exit | prereq Lower Passage 2 Breakable  Wall To Exit |  | Verified |  |
| ES | Exit Shaft | Bottom Exit | Lower Passage 2 | prereq Lower Passage 2 Breakable  Wall To Exit AND ( Cling Grip OR Silk Soar ( Dash AND Scuttlebrace AND Faydown Cloak ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Hermits Soul | Hermit | prereq Wish: Silk And Soul Started |  | Verified | collectible |  |
| Silver Bell Spawn Location #6 | Upper Hall | prereq Wish: Silver Bells Started |  | Verified | collectible |  |
| Rosary Cache: Bellhart #6 | Upper Hall | None |  | Verified | resource |  |
| Silver Bell Spawn Location #7 | Upper Hall | prereq Wish: Silver Bells Started |  | Verified | collectible |  |
| Silver Bell Spawn Location #8 | Under Hermit Hall | prereq Wish: Silver Bells Started |  | Verified | collectible |  |
| Silver Bell Spawn Location #12 | Under Hermit Hall | prereq Wish: Silver Bells Started |  | Verified | collectible |  |
| Rosary Cache: Bellhart #7 | Rosary Room | None |  | Verified | resource |  |
| Silver Bell Spawn Location #9 | Passage below rosary | prereq Wish: Silver Bells Started |  | Verified | collectible |  |
| Silver Bell Spawn Location #10 | Lower Passage 1 | prereq Wish: Silver Bells Started |  | Verified | collectible |  |
| Silver Bell Spawn Location #11 | Lower Passage 2 | prereq Wish: Silver Bells Started |  | Verified | collectible |  |
| Rosary Cache: Bellhart #5 | Bottom Exit | None |  | Verified | resource |  |
| Hermit Hole Breakable Wall | Under Hermit Hall | None |  | Verified | blockade |  |
| Breakable Wall Passage Breakable Wall | Breakable Wall Passage | None |  | Verified | blockade |  |
| Lower Passage 2 Breakable Wall | Lower Passage 2 | None |  | Verified | blockade |  |
| Lower Passage 2 Breakable  Wall To Exit | Lower Passage 2 | None |  | Verified | blockade |  |
| Wish: Silver Bells Started | Top Exit | None |  | Verified | event |  |
| Wish: Silk And Soul Started | Top Exit | None |  | Verified | event |  |

### Bellhart Pinsmith (Belltown_Room_pinsmith)

**Game ID:** Belltown_Room_pinsmith

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Belltown (Belltown)](#belltown-belltown) | ND | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Progressive Needle Upgrade 1 |  | None |  | Verified | collectible |  |
| Progressive Needle Upgrade 2 |  | pale oils 1 |  | Verified | collectible | cumulative requirement |
| Progressive Needle Upgrade 3 |  | pale oils 2 |  | Verified | collectible | cumulative requirement |
| Progressive Needle Upgrade 4 |  | pale oils 3 |  | Verified | collectible | cumulative requirement |
| Pinmaster's Oil Wish Granted |  | complete THE Pinmaster's Oil Wish Promised AND pale oils 1 |  | Verified | event | can be missed, but counts towards silk and soul regardless of completion after second needle upgrade |

### Bellhart Relic Shop (Belltown_Room_Relic)

**Game ID:** Belltown_Room_Relic

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Belltown (Belltown)](#belltown-belltown) | RD | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Hand In Bone Scroll Relic Bone Scroll Far Fields |  | have Relic Bone Scroll Far Fields |  | Verified | event |  |
| Hand In Bone Scroll Greymoor |  | have Relic Bone Scroll Greymoor |  | Verified | event |  |
| Hand In Bone Scroll Underworks |  | have Relic Bone Scroll Underworks |  | Verified | event |  |
| Hand In Bone Scroll Wisp Thicket |  | have Relic Bone Scroll Wisp Thicket |  | Verified | event |  |
| Hand In Weaver Effigy Moss Grotto |  | have Relic Weaver Effigy Camora Moss Grotto |  | Verified | event |  |
| Hand In Weaver Effigy Shellwood |  | have Relic Weaver Effigy Keelal Shellwood |  | Verified | event |  |
| Hand In Weaver Effigy  The Slab |  | have Relic Weaver Effigy Atla The Slab |  | Verified | event |  |
| Hand in Choral Commandment Jubilana |  | have Relic Choral Commandment Jubilana |  | Verified | event |  |
| Hand in Choral Commandment Western Whiteward |  | have Relic Choral Commandment Western Whiteward |  | Verified | event |  |
| Hand in Choral Commandment Moss Grotto |  | have Relic Choral Commandment Moss Grotto |  | Verified | event |  |
| Hand in Choral Commandment Eastern Whiteward |  | have Relic Choral Commandment Eastern Whiteward |  | Verified | event |  |
| Hand in Rune Harp Weavenest Atla |  | have Relic Rune Harp Weavenest Atla |  | Verified | event |  |
| Hand in Rune Harp Weavenest Cindril |  | have Relic Rune Harp Weavenest Cindril |  | Verified | event |  |
| Hand in Rune Harp High Halls |  | have Relic Rune Harp High Halls |  | Verified | event |  |
| Hand in Arcane Egg |  | have Relic Arcane Egg |  | Verified | event |  |

#### Notes

Relic slots are numbered for convenience but not for required reasons.

### Bellhart Right Entrance (Belltown_06)

**Game ID:** Belltown_06

**Contributors:** Pyxl

#### Subrooms

- Lower Level
- Upper Level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left3 | Upper Level | [Widow Boss Fight (Belltown_Shrine)](#widow-boss-fight-belltownshrine) | R | None |  | Verified |  |
| LL | left1 | Lower Level | [Belltown (Belltown)](#belltown-belltown) | R | None |  | Verified |  |
| R | right1 | Lower Level | [Greymoor Entry to Bellhart (Greymoor_08)](#greymoor-entry-to-bellhart-greymoor08) | L | None |  | Verified | Update once skai sends in the left greymoor export only here so moriko doesnt crucify me |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EL | Elevator | Lower Level | Upper Level | prereq Bellhart elevator |  | Verified |  |
| EL | Elevator | Upper Level | Lower Level | prereq Bellhart elevator |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lore: Bellhart #1 | Lower Level | none |  | Verified | lore |  |
| Bellhart elevator | Upper Level | None |  | Verified | switch |  |

### Belltown (Belltown)

**Game ID:** Belltown

**Contributors:** Pyxl

#### Subrooms

- Upper Area
- Lower Area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RD | door4 | Upper Area | [Bellhart Relic Shop (Belltown_Room_Relic)](#bellhart-relic-shop-belltownroomrelic) | L | defeat THE boss widow |  | Verified |  |
| HD | door5 | Upper Area | [Bellhome (Belltown_room_spare)](#bellhome-belltownroomspare) | L | none |  | Verified | the randomizer makes this always accessible |
| ND | door3 | Upper Area | [Bellhart Pinsmith (Belltown_Room_pinsmith)](#bellhart-pinsmith-belltownroompinsmith) | L | defeat THE boss widow |  | Verified |  |
| L | left3 | Lower Area | [Bellhart Hallway to Shellwood (Belltown_07)](#bellhart-hallway-to-shellwood-belltown07) | R | None |  | Verified |  |
| R | right2 | Lower Area | [Bellhart Right Entrance (Belltown_06)](#bellhart-right-entrance-belltown06) | LL | None |  | Verified |  |
| BD | door1 | Lower Area | [Bellhart Bellway (Belltown_basement)](#bellhart-bellway-belltownbasement) | L | None |  | Verified |  |
| WW | wish wall | Lower Area | [Bellhart Wish Wall](#bellhart-wish-wall) | BH | defeat THE boss widow |  | Verified |  |
| DW | delivery wishes | Upper Area | [Bellhart Deliveries](#bellhart-deliveries) | BH | complete THE my missing brother wish granted |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PL | Platforms | Lower Area | Upper Area | Ledge grab OR Dash OR Clawline OR Silksoar OR Faydown Cloak OR Sharpdart OR easy Shaman Crest pogo OR Cling Grip |  | Verified |  |
| PL | Platforms | Upper Area | Lower Area | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket: Bellhart Roof | Upper Area | Silk Soar |  | Verified | collectible |  |
| Couriers Rasher | Upper Area | complete THE Great Taste of Pharloom Wish Promised |  | Verified | logic-point |  |
| Map: Bellhart | Upper Area | None |  | Verified | collectible |  |
| Memory Locket (Frey) | Lower Area | Rosaries 330 |  | Verified | event |  |
| Spool Fragment (Frey) | Lower Area | prereq THE My Missing Courier Wish Granted AND Rosaries 270 |  | Verified | event |  |
| Multibinder | Lower Area | prereq THE My Missing Courier Wish Granted AND Rosaries 800 |  | Verified | collectible |  |
| Desk | Lower Area | Rosaries 380 |  | Verified | collectible |  |
| Gleamlights | Lower Area | Rosaries 320 |  | Verified | collectible |  |
| Bell Lacquer | Lower Area | Rosaries 520 |  | Verified | collectible |  |
| Personal Spa | Lower Area | Bellhome Items 2 AND Rosaries 11000 |  | Verified | collectible |  |
| Gramophone | Lower Area | sold pslam cylinders 6 AND Rosaries 490 |  | Verified | collectible |  |
| Bench | Lower Area | none |  | Verified | bench |  |
| Craw Summons | Lower Area | Craw Summons Ready |  | Verified | collectible |  |

### Upper Bellhart (Belltown_04)

**Game ID:** Belltown_04

**Contributors:** Pyxl

#### Subrooms

- Lower Exits
- Lower Big Room
- Silver Bell Cubby
- Central Passage
- Upper Big room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | left2 | Lower Exits | [Shellwood Hidden Bellhart Connection (Shellwood_15)](#shellwood-hidden-bellhart-connection-shellwood15) | R | None |  | Verified |  |
| F | bot1 | Lower Exits | [Widow Boss Fight (Belltown_Shrine)](#widow-boss-fight-belltownshrine) | C | None |  | Verified |  |
| UL | left1 | Upper Big room | [Shellwood Upper Bellhart Entrance (Shellwood_13)](#shellwood-upper-bellhart-entrance-shellwood13) | R | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TS1 | Tall Shaft1 | Lower Exits | Lower Big Room | ( Ledge Grab OR Clawline OR Faydown Cloak OR ( Dash AND Scuttlebrace ) OR Cling Grip ) |  | Verified |  |
| TS1 | Tall Shaft1 | Lower Big Room | Lower Exits | ( Ledge Grab OR Clawline OR Faydown Cloak OR ( Dash AND Scuttlebrace ) OR Cling grip ) |  | Verified |  |
| TS2 | Tall Shaft2 | Lower Exits | Silver Bell Cubby | ( Cling Grip OR ( Dash AND Scuttlebrace ) ) |  | Verified |  |
| TS2 | Tall Shaft2 | Silver Bell Cubby | Lower Exits | None |  | Verified |  |
| TS3 | Tall Shaft3 | Lower Big Room | Silver Bell Cubby | Cling Grip OR Scuttlebrace |  | Verified |  |
| TS3 | Tall Shaft3 | Silver Bell Cubby | Lower Big Room | None |  | Verified |  |
| TS4 | Tall Shaft4 | Silver Bell Cubby | Central Passage | Cling Grip OR ( Dash AND Scuttlebrace ) |  | Verified |  |
| TS4 | Tall Shaft4 | Central Passage | Silver Bell Cubby | None |  | Verified |  |
| US | Upper Shafts | Central Passage | Upper Big room | ( Cling Grip OR ( Dash AND Scuttlebrace ) ) |  | Verified |  |
| US | Upper Shafts | Upper Big room | Central Passage | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silver Bell Spawn Location #1 | Lower Big Room | None |  | Verified | collectible |  |
| Silver Bell Spawn Location #2 | Lower Big Room | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  | Verified | collectible |  |
| Rosary Cache: Bellhart #1 | Lower Big Room | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  | Verified | resource |  |
| Rosary Cache: Bellhart #2 | Lower Big Room | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  | Verified | resource |  |
| Silver Bell Spawn Location #3 | Silver Bell Cubby | None |  | Verified | collectible |  |
| Silver Bell Spawn Location #4 | Central Passage | None |  | Verified | collectible |  |
| Rosary Cache: Bellhart #3 | Central Passage | None |  | Verified | resource |  |
| Silver Bell Spawn Location #5 | Upper Big room | None |  | Verified | collectible |  |
| Flea: Bellhart | Upper Big room | Silk Soar OR Cling Grip OR ( Dash AND Scuttlebrace ) OR ( Easy enemy pogo AND ( Faydown Cloak OR Drifters Cloak ) ) |  | Verified | collectible |  |

### Widow Boss Fight (Belltown_Shrine)

**Game ID:** Belltown_Shrine

**Contributors:** Pyxl

#### Subrooms

- Arena
- Upper

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Arena | [Bellhart Right Entrance (Belltown_06)](#bellhart-right-entrance-belltown06) | UL | None |  | Verified |  |
| C | top1 | Upper | [Upper Bellhart (Belltown_04)](#upper-bellhart-belltown04) | F | Silk Soar OR Cling Grip OR ( Dash AND Scuttlebrace ) OR ( Easy Heal Stall AND ( Faydown Cloak OR Drifters Cloak ) ) |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TD | Trapdoor | Arena | Upper | prereq Bellshrine Lever AND ( Cling Grip OR Silk soar OR ( Dash AND Scuttlebrace ) ) |  | Verified | Permanently open |
| TD | Trapdoor | Upper | Arena | prereq Bellshrine Lever |  | Verified | Permanently open |
| RH | Roof Hole | Arena | Upper | Silk Soar OR ( Cling Grip AND Faydown Cloak AND ( Clawline OR Sharpdart ) ) |  | Verified |  |
| RH | Roof Hole | Upper | Arena | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Widow | Arena | None |  | Verified | boss |  |
| Bell: Bellhart | Arena | Activate Bellshrine Lever |  | Verified | collectible |  |
| Needolin | Arena | Defeat Boss Widow |  | Verified | collectible |  |
| Bellshrine Lever | Arena | Defeat Boss Widow |  | Verified | switch |  |
| Bench | Arena | Activate Bellshrine Lever |  | Verified | bench |  |

### Bellhome (Belltown_room_spare)

**Game ID:** Belltown_room_spare

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left1 |  | [Belltown (Belltown)](#belltown-belltown) | HD | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bench |  | none |  | Verified | bench |  |
| act toggle |  | act 3 AND needolin | TODO |  | bench | is needolin required for swap? |

## Greymoor

### Greymoor Bellshrine (Bellshrine_02)

**Game ID:** Bellshrine_02

**Contributors:** Isssma

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Greymoor West Bellshrine Room  (Greymoor_01)](#greymoor-west-bellshrine-room-greymoor01) | MR | ( bellshrinesanity off AND activate bellshrine switch )  OR ( bellshrinesanity on AND have bell greymoor ) |  | Verified | need to make sure this stays in sync with the connection on the other side |
| R | right |  | [Greymoor East Bellshrine Room (Greymoor_02)](#greymoor-east-bellshrine-room-greymoor02) | ML | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bellshrine switch |  | hit lever: right OR hit lever: left |  | Verified | switch |  |
| bell greymoor |  | activate bellshrine switch |  | Verified | collectible |  |

### Greymoor Craw Lake (Greymoor_15b)

**Game ID:** Greymoor_15b

**Contributors:** Isssma

#### Subrooms

- craw building
- lower left section
- middle craw nest
- left top craw nest
- spiked room
- flea room
- middle craw nest left
- small ass platform
- upper craw nest
- lower flea room
- right top craw nest
- lil top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top | lil top | [Greymoor Weaver Shrine (Greymoor_22)](#greymoor-weaver-shrine-greymoor22) | B | silk soar OR ledge grab OR faydown cloak OR cling grip |  | Verified |  |
| ML | middle left | middle craw nest left | [Greymoor Craw Lake Entrance (Greymoor_15)](#greymoor-craw-lake-entrance-greymoor15) | UR | none |  | Verified |  |
| LR | lower right | craw building | [Verdania Placeholder](#verdania-placeholder) | P | ACT 3 AND (((cling grip OR silk soar) AND (clawline OR (progressive swift step 1 AND (drifters cloak OR (sharpdart AND faydown cloak))) OR (progressive swift step 2 AND faydown cloak))) OR (prereq balloon lever IN greymoor crow nest AND (clawline OR faydown cloak OR drifters cloak OR sharpdart OR progressive swift step 2 OR ledge grab OR easy hunter pogo OR easy architect pogo OR easy shaman pogo OR easy beast crest pogo))) |  | Verified | verdania not yet mapped |
| CN | craw nest entrance | craw building | [Greymoor Crow Nest (Room_CrowCourt)](#greymoor-crow-nest-roomcrowcourt) | L | swim OR ledge grab OR cling grip OR hard enemy pogo |  | Verified |  |
| LL | lower left | lower left section | [Greymoor Craw Lake Entrance (Greymoor_15)](#greymoor-craw-lake-entrance-greymoor15) | LR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LG | lake gap | lower left section | craw building | swim OR clawline OR ((progressive swift step 2 OR sharpdart) AND faydown cloak AND drifters cloak) OR (progressive swift step 2 AND sharpdart AND faydown cloak) OR (progressive swift step 1 AND sharpdart AND drifters cloak) OR (silk soar AND drifters cloak AND (faydown cloak OR sharpdart OR progressive swift step 2)) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| LG | lake gap | craw building | lower left section | swim OR clawline OR silk soar OR ((progressive swift step 2 OR sharpdart) AND faydown cloak AND drifters cloak) OR (progressive swift step 2 AND sharpdart AND faydown cloak) OR (progressive swift step 1 AND sharpdart AND (drifters cloak OR ((ledge grab OR cling grip) AND faydown cloak))) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| FR | fall right | right top craw nest | flea room | progressive swift step 2 OR clawline OR sharpdart OR drifters cloak OR faydown cloak |  | Verified |  |
| FL | fall left | upper craw nest | middle craw nest left | progressive swift step 2 OR clawline OR sharpdart OR drifters cloak OR (faydown cloak AND ledge grab) |  | Verified |  |
| FL | fall left | middle craw nest left | upper craw nest | silk soar |  | Verified | must drop to middle craw nest |
| G1 | gap 1 | craw building | small ass platform | (drifters cloak AND ((progressive swift step 1 AND clawline) OR (progressive swift step 2 AND sharpdart AND faydown cloak))) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G1 | gap 1 | small ass platform | craw building | (drifters cloak AND ((progressive swift step 1 AND clawline) OR (progressive swift step 2 AND sharpdart AND faydown cloak))) OR  prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G2 | gap 2 | middle craw nest left | middle craw nest | none (normal jump) |  | Verified |  |
| G2 | gap 2 | middle craw nest | middle craw nest left | (progressive swift step 1 AND faydown cloak AND ledge grab) OR  prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G3 | gap 3 | middle craw nest | flea room | drifters cloak OR clawline OR (progressive swift step 2 AND (ledge grab OR cling grip OR sharpdart OR faydown cloak)) OR (progressive swift step 1 AND faydown cloak AND (ledge grab OR cling grip OR sharpdart)) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G3 | gap 3 | flea room | middle craw nest | drifters cloak OR clawline OR (progressive swift step 2 AND (sharpdart OR faydown cloak)) OR (progressive swift step 1 AND faydown cloak AND (ledge grab OR cling grip OR sharpdart)) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G4 | gap 4 | craw building | lower flea room | faydown cloak OR silk soar OR hard enemy pogo |  | Verified |  |
| G4 | gap 4 | lower flea room | craw building | none |  | Verified |  |
| G5 | gap 5 | left top craw nest | right top craw nest | clawline OR drifters cloak OR (progressive swift step 1 AND (sharpdart OR (faydown cloak AND flea brew))) OR (progressive swift step 2 AND faydown cloak) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| G5 | gap 5 | right top craw nest | left top craw nest | (progressive swift step 1 AND faydown cloak AND (drifters cloak OR sharpdart)) OR (clawline AND (faydown cloak OR progressive swift step 2 OR drifters cloak OR sharpdart OR (progressive swift step 1 AND medium beast pogo))) OR (progressive swift step 2 AND faydown cloak AND flea brew) OR (sharpdart AND faydown cloak AND drifters cloak) OR (prereq balloon lever IN greymoor crow nest AND (clawline OR faydown cloak OR sharpdart OR (drifters cloak AND progressive swift step 1) OR progressive swift step 2)) |  | Verified |  |
| D1 | drop 1 | craw building | flea room | silk soar |  | Verified |  |
| D1 | drop 1 | flea room | craw building | none (just fall) |  | Verified |  |
| D2 | drop 2 | upper craw nest | middle craw nest | none (just fall) |  | Verified |  |
| D2 | drop 2 | middle craw nest | upper craw nest | silk soar OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| D3 | drop 3 | middle craw nest | craw building | none (just fall) |  | Verified |  |
| D3 | drop 3 | craw building | middle craw nest | silk soar OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| D4 | drop 4 | small ass platform | middle craw nest | prereq balloon lever IN greymoor crow nest |  | Verified |  |
| D4 | drop 4 | middle craw nest | small ass platform | clawline OR sharpdart OR progressive swift step 2 OR faydown cloak OR drifters cloak OR (progressive swift step 1 AND (ledge grab OR flea brew OR silkspeed anklets)) |  | Verified |  |
| H | hatch | lower flea room | flea room | prereq flea airlock |  | Verified |  |
| H | hatch | flea room | lower flea room | prereq flea airlock |  | Verified |  |
| SL | spike lower | spiked room | upper craw nest | prereq spike room lever AND (clawline AND faydown cloak AND (ledge grab OR progressive swift step 1)) |  | Verified |  |
| SL | spike lower | upper craw nest | spiked room | (clawline OR ((progressive swift step 2 OR sharpdart) AND (drifters cloak OR faydown cloak)) ) AND prereq spike room lever |  | Verified |  |
| SU | spike upper | spiked room | left top craw nest | (proficient movement AND spike pogo) OR prereq balloon lever IN greymoor crow nest |  | Verified |  |
| SU | spike upper | left top craw nest | spiked room | none |  | Verified |  |
| F1 | fall 1 | left top craw nest | upper craw nest | none (just fall) |  | Verified |  |
| F1 | fall 1 | upper craw nest | left top craw nest | silk soar OR (cling grip AND (easy enemy pogo OR faydown cloak)) |  | Verified |  |
| F2 | fall 2 | right top craw nest | middle craw nest | nothing (just fall) |  | Verified |  |
| F2 | fall 2 | middle craw nest | right top craw nest | silk soar OR (prereq balloon lever IN greymoor crow nest AND faydown cloak AND (ledge grab OR cling grip)) |  | Verified |  |
| F3 | fall 3 | right top craw nest | upper craw nest | drifters cloak OR progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR (flea brew AND ledge grab) |  | Verified |  |
| F4 | fall 4 | spiked room | middle craw nest left | prereq spike room lever |  | Verified |  |
| F4 | fall 4 | middle craw nest left | spiked room | (prereq balloon lever IN greymoor crow nest OR silk soar) AND prereq spike room lever |  | Verified |  |
| FF | free fall | lil top | right top craw nest | nothing (just fall) |  | Verified |  |
| FF | free fall | right top craw nest | lil top | silk soar |  | Verified |  |
| BG | balloon gap | left top craw nest | lil top | prereq balloon lever IN greymoor crow nest |  | Verified |  |
| BG | balloon gap | lil top | left top craw nest | prereq balloon lever IN greymoor crow nest OR clawline OR sharpdart OR drifters cloak OR progressive swift step 2 OR (faydown cloak AND (ledge grab OR flea brew OR progressive swift step 1)) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Frayed Rosary String #2 | small ass platform | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #20 | lower flea room | none |  | Verified | resource |  |
| Flea Freymoor - Craw Lake | flea room | silk soar OR ledge grab OR faydown cloak OR cling grip OR medium enemy pogo |  | Verified | collectible |  |
| Greymoor - Rosary Cache #21 | flea room | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #22 | flea room | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #19 | right top craw nest | nothing |  | Verified | resource |  |
| Threefold Pin | right top craw nest | nothing |  | Verified | collectible |  |
| flea airlock | flea room | open airlock left OR open airlock right OR open airlock up |  | Verified | switch |  |
| spike room lever | upper craw nest | flip lever up OR flip lever left OR flip lever right |  | Verified | switch |  |

### Greymoor Crow Court (Room_CrowCourt_02)

**Game ID:** Room_CrowCourt_02

**Contributors:** Isssma

#### Subrooms

- entrance
- left shaft
- the court

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | entrance | [Greymoor Crow Nest (Room_CrowCourt)](#greymoor-crow-nest-roomcrowcourt) | b | cling grip OR scuttlebrace |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| D | drop | entrance | the court | none (just fall) |  | Verified |  |
| D | drop | the court | entrance | defeat Crow Father AND silk soar |  | Verified |  |
| MD | metal door | the court | left shaft | defeat Crow Father |  | Verified |  |
| MD | metal door | left shaft | the court | defeat Crow Father |  | Verified |  |
| W | wall | left shaft | entrance | clear wood wall AND (cling grip OR (easy scuttlebrace AND (ledge grab OR faydown cloak OR clawline))) |  | Verified |  |
| W | wall | entrance | left shaft | clear wood wall |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Crow Father | the court | nothing |  | Verified | boss |  |
| craw memento | the court | defeat Crow Father |  | Verified | collectible |  |
| Greymoor - Rosary Cache #35 | left shaft | cling grip OR (easy scuttlebrace AND (ledge grab OR faydown cloak OR clawline OR easy beast pogo)) |  | Verified | resource |  |
| Greymoor - Rosary Cache #36 | left shaft | cling grip OR (easy scuttlebrace AND (ledge grab OR faydown cloak OR clawline OR easy beast pogo)) |  | Verified | resource |  |
| Greymoor - Rosary Cache #37 | left shaft | cling grip OR (easy scuttlebrace AND (ledge grab OR faydown cloak OR clawline OR easy beast pogo)) |  | Verified | resource |  |
| Crow bell | left shaft | cling grip OR (easy scuttlebrace AND (ledge grab OR faydown cloak OR clawline OR easy beast pogo)) |  | Verified | collectible |  |
| wood wall | left shaft | break wall right OR break wall up |  | Verified | blockade |  |

### Greymoor Crow Nest (Room_CrowCourt)

**Game ID:** Room_CrowCourt

**Contributors:** Isssma

#### Subrooms

- crow lower nest
- crow arena
- crow nest entrance
- balloon control room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| b | bottom | crow lower nest | [Greymoor Crow Court (Room_CrowCourt_02)](#greymoor-crow-court-roomcrowcourt02) | T | craw summons ready |  | Verified |  |
| L | left | crow nest entrance | [Greymoor Craw Lake (Greymoor_15b)](#greymoor-craw-lake-greymoor15b) | CN | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| f1 | fall 1 | crow nest entrance | crow lower nest | none (just fall) |  | Verified |  |
| f1 | fall 1 | crow lower nest | crow nest entrance | silk soar OR prereq balloon lever |  | Verified |  |
| f2 | fall 2 | crow arena | crow lower nest | none (just fall) |  | Verified |  |
| f2 | fall 2 | crow lower nest | crow arena | ledge grab OR silk soar OR faydown cloak OR easy enemy pogo |  | Verified |  |
| PG1 | platform gap 1 | crow arena | balloon control room | clear Craw Lake Gauntlet AND (easy shaman pogo OR easy reaper pogo OR easy wanderer pogo OR easy hunter pogo OR faydown cloak OR ledge grab OR silk soar OR ledge grab) |  | Verified |  |
| PG1 | platform gap 1 | balloon control room | crow arena | clear Craw Lake Gauntlet |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| balloon lever | balloon control room | flip lever up OR flip lever left OR flip lever right |  | Verified | switch |  |
| Greymoor - Rosary Cache #30 | crow nest entrance | nothing |  | Verified | resource |  |
| Greymoor - Rosary Cache #29 | crow nest entrance | nothing |  | Verified | resource |  |
| Greymoor - Rosary Cache #28 | crow lower nest | (faydown cloak AND (progressive swift step 1 OR sharpdart OR clawline)) OR ((ledge grab OR cling grip OR easy enemy pogo) AND drifters cloak AND (progressive swift step 2 OR sharpdart OR clawline)) OR prereq balloon lever |  | Verified | resource |  |
| Greymoor - Rosary Cache #32 | crow lower nest | ((ledge grab OR cling grip OR easy enemy pogo) AND (progressive swift step 1 OR sharpdart OR clawline)) OR faydown cloak OR prereq balloon lever |  | Verified | resource |  |
| Greymoor - Rosary Cache #33 | crow lower nest | ((ledge grab OR cling grip OR easy enemy pogo) AND (progressive swift step 1 OR sharpdart OR clawline)) OR faydown cloak OR prereq balloon lever |  | Verified | resource |  |
| Greymoor - Rosary Cache #31 | crow lower nest | (faydown cloak AND (progressive swift step 1 OR sharpdart OR clawline)) OR ((ledge grab OR cling grip OR easy enemy pogo) AND drifters cloak AND (progressive swift step 2 OR sharpdart OR clawline)) OR prereq balloon lever |  | Verified | resource |  |
| Greymoor - Rosary Cache #34 | crow arena | none |  | Verified | resource |  |
| Craw Lake Gauntlet | crow arena | nothing |  | Verified | gauntlet |  |

### Greymoor East Bellshrine Room (Greymoor_02)

**Game ID:** Greymoor_02

**Contributors:** Isssma

#### Subrooms

- lower section left
- lower section right
- middle section right
- middle section left
- bridge left section
- bridge right section
- upper crow nest
- lone crow platform
- top left
- top right
- hidden exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LSL | lower left | lower section left | [Greymoor West Bellshrine Room  (Greymoor_01)](#greymoor-west-bellshrine-room-greymoor01) | LR | none |  | Verified |  |
| LR | lower right | lower section right | [Greymoor Craw Lake Entrance (Greymoor_15)](#greymoor-craw-lake-entrance-greymoor15) | LL | none |  | Verified |  |
| ML | middle left | middle section left | [Greymoor Bellshrine (Bellshrine_02)](#greymoor-bellshrine-bellshrine02) | R | none |  | Verified |  |
| MR | middle right | middle section right | [Greymoor Craw Lake Entrance (Greymoor_15)](#greymoor-craw-lake-entrance-greymoor15) | UL | none |  | Verified |  |
| BL | bridge left | bridge left section | [Greymoor West Bellshrine Room  (Greymoor_01)](#greymoor-west-bellshrine-room-greymoor01) | TR | none |  | Verified |  |
| HR | hidden right | hidden exit | [Greymoor Silver Shells room (Greymoor_17)](#greymoor-silver-shells-room-greymoor17) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TP | tall platform | lower section right | lower section left | ledge grab OR faydown cloak OR silk soar OR cling grip |  | Verified |  |
| TP | tall platform | lower section left | lower section right | nothing (just fall) |  | Verified |  |
| F1 | fall 1 | middle section left | lower section left | nothing (just fall) |  | Verified |  |
| LS1 | lever switch 1 | lower section right | middle section right | silk soar OR prereq balloon switch |  | Verified |  |
| LS1 | lever switch 1 | middle section right | lower section right | none (just fall) |  | Verified |  |
| G1 | gap 1 | middle section right | middle section left | prereq balloon switch OR progressive swift step 1 OR clawline OR sharpdart OR drifters cloak OR faydown cloak OR silk soar |  | Verified |  |
| G1 | gap 1 | middle section left | middle section right | Progressive swift step 2 OR clawline OR sharpdart OR drifters cloak OR silksoar OR (progressive swift step 1 AND (faydown cloak OR ledge grab)) OR prereq balloon switch |  | Verified |  |
| BG | bridge gap | bridge left section | bridge right section | (prereq bridge lever AND (clawline OR ((progressive swift step 2 OR sharpdart OR (progressive swift step 1 AND (( flea brew AND ledge grab) OR (silkspeed anklets AND cling grip)))) AND (drifters cloak OR faydown cloak)))) OR nothing |  | Verified |  |
| BG | bridge gap | bridge right section | bridge left section | (prereq bridge lever AND (clawline OR ((progressive swift step 2 OR sharpdart OR (progressive swift step 1 AND ((flea brew AND ledge grab) OR (silkspeed anklets AND cling grip)))) AND (drifters cloak OR faydown cloak)))) OR nothing |  | Verified |  |
| CR | climb right | middle section right | bridge right section | prereq bridge lever AND (cling grip OR silk soar) |  | Verified |  |
| CR | climb right | bridge right section | middle section right | prereq bridge lever |  | Verified |  |
| CL | climb left | middle section left | bridge left section | prereq bridge lever AND (silk soar OR (cling grip AND faydown cloak)) |  | Verified |  |
| CL | climb left | bridge left section | middle section left | prereq bridge lever |  | Verified |  |
| UL | upper left | bridge left section | upper crow nest | silk soar |  | Verified |  |
| UL | upper left | upper crow nest | bridge left section | none (fall) |  | Verified |  |
| UR | upper right | bridge right section | lone crow platform | nothing |  | Verified |  |
| UR | upper right | lone crow platform | bridge right section | none (fall) |  | Verified |  |
| G2 | gap 2 | lone crow platform | upper crow nest | silk soar OR faydown cloak OR hard enemy pogo OR clawline OR sharpdart OR progressive swift step 2 OR drifters cloak |  | Verified |  |
| G2 | gap 2 | upper crow nest | lone crow platform | nothing |  | Verified |  |
| S1 | shaft 1 | upper crow nest | top right | silk soar OR (cling grip AND ((proficient movement AND spike pogo) OR progressive swift step 1 OR clawline OR sharpdart OR drifters cloak OR medium enemy pogo )) |  | Verified |  |
| S1 | shaft 1 | top right | upper crow nest | nada |  | Verified |  |
| PG1 | platform gap | upper crow nest | top left | silk soar OR faydown cloak OR hard enemy pogo |  | Verified |  |
| PG1 | platform gap | top left | upper crow nest | nothing |  | Verified |  |
| G3 | gap 3 | top left | top right | faydown cloak OR (ledge grab AND (clawline OR progressive swift step 1 OR sharpdart) ) |  | Verified |  |
| G3 | gap 3 | top right | top left | nothing |  | Verified |  |
| B | blockade | top right | hidden exit | break wall right OR break wall up |  | Verified |  |
| B | blockade | hidden exit | top right | break wall left OR break wall up |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Spool Fragment | top left | nothing |  | Verified | collectible |  |
| Greymoor #2 - Rosary Cache | upper crow nest | nothing |  | Verified | resource |  |
| Greymoor #3 - Rosary Cache | upper crow nest | nothing |  | Verified | resource |  |
| Greeymoor - map purchase | lower section right | nothing |  | Verified | collectible |  |
| balloon switch | middle section right | flip lever up OR flip lever right OR flip lever left |  | Verified | switch |  |
| bridge lever | bridge right section | flip lever up OR flip lever right OR flip lever left |  | Verified | switch |  |

### Greymoor Eastern Tower (Greymoor_04)

**Game ID:** Greymoor_04

**Contributors:** Isssma

#### Subrooms

- arena encounter
- middle section
- lower airstream section
- upper section
- tower top
- upper airstream section

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | arena encounter | [Greymoor Halfway Home Exterior (Greymoor_03)](#greymoor-halfway-home-exterior-greymoor03) | LL | clear Greymoor Tower Gaunlet |  | Verified |  |
| LL | lower left | arena encounter | [Greymoor Towers Patio (Greymoor_05)](#greymoor-towers-patio-greymoor05) | MR | clear Greymoor Tower Gaunlet |  | Verified |  |
| MR | middle right | middle section | [Greymoor Halfway Home Exterior (Greymoor_03)](#greymoor-halfway-home-exterior-greymoor03) | ML | nothing |  | Verified |  |
| ML | middle left | middle section | [Greymoor Middle Passage (Greymoor_10)](#greymoor-middle-passage-greymoor10) | R | nothing |  | Verified |  |
| UL | upper left | tower top | [Greymoor Upper Towers Path (Greymoor_11)](#greymoor-upper-towers-path-greymoor11) | R | nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| F1 | fall 1 | arena encounter | lower airstream section | silk soar |  | Verified |  |
| F1 | fall 1 | lower airstream section | arena encounter | nothing (just fall) |  | Verified |  |
| S1 | shaft 1 | lower airstream section | middle section | silk soar OR (activate lower airstream AND drifters cloak) |  | Verified |  |
| S1 | shaft 1 | middle section | lower airstream section | nothing (just fall) |  | Verified |  |
| S2 | shaft 2 | middle section | upper section | silk soar OR (drifters cloak  AND (activate lower airstream OR (faydown cloak AND (ledge grab OR cling grip OR easy scuttlebrace))) AND activate middle airstream) |  | Verified |  |
| S2 | shaft 2 | upper section | middle section | nothing (just fall) |  | Verified |  |
| PG1 | platform gap 1 | upper section | upper airstream section | nothing (just fall) |  | Verified |  |
| PG1 | platform gap 1 | upper airstream section | upper section | ledge grab OR faydown cloak OR silk soar OR medium enemy pogo |  | Verified |  |
| S3 | shaft 3 | upper section | tower top | (proficient movement AND spike pogo) OR silk soar OR ((drifters cloak AND (spike pogo OR ledge grab OR progressive swift step 2 OR faydown cloak OR cling grip)) AND activate upper airstream) |  | Verified |  |
| S3 | shaft 3 | tower top | upper section | none (just fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Rosary Cache #6 | lower airstream section | nothing |  | Verified | resource |  |
| Greymoor - Silkeater | tower top | silk soar OR (proficient movement AND spike pogo) OR (drifters cloak AND (spike pogo OR faydown cloak OR (clawline AND cling grip)) AND activate top airstream) |  | Verified | collectible |  |
| Greymoor Tower Gaunlet | arena encounter | nothing |  | Verified | gauntlet |  |
| lower airstream | lower airstream section | hit lever right OR hit lever up OR hit lever down |  | Verified | switch |  |
| middle airstream | middle section | ((drifters cloak AND activate lower airstream) OR ledge grab OR cling grip OR silk soar OR faydown cloak) AND (hit lever right OR hit lever up OR hit lever left) |  | Verified | switch |  |
| upper airstream | upper airstream section | hit lever right OR hit lever down |  | Verified | switch |  |
| top airstream | tower top | (hit lever right OR hit lever up OR hit lever left) AND ((activate upper airstream AND drifters cloak) OR (proficient movement AND spike pogo)) |  | Verified | switch |  |

### Greymoor Weaver Shrine (Greymoor_22)

**Game ID:** Greymoor_22

**Contributors:** Isssma

#### Subrooms

- left section
- right section

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bottom | left section | [Greymoor Craw Lake (Greymoor_15b)](#greymoor-craw-lake-greymoor15b) | T | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| UP | upper path | left section | right section | easy hunter pogo OR easy reaper pogo OR easy wanderer pogo OR easy beast pogo OR hard witch pogo OR medium architect pogo OR easy shaman pogo OR ledge grab OR cling grip OR faydown cloak |  | Verified |  |
| UP | upper path | right section | left section | ledge grab OR silk soar OR cling grip OR faydown cloak |  | Verified |  |
| W | wall exit | right section | left section | clear wooden wall |  | Verified |  |
| W | wall exit | left section | right section | clear wooden wall |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Thread storm | left section | easy hunter pogo OR easy reaper pogo OR easy wanderer pogo OR easy beast pogo OR hard witch pogo OR medium architect pogo OR easy shaman pogo OR ledge grab OR cling grip OR faydown cloak |  | Verified | collectible |  |
| Greymoor - Rosary Cache #26 | right section | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #27 | right section | none |  | Verified | resource |  |
| wooden wall | right section | break wall left OR break wall up |  | Verified | blockade |  |

### Greymoor Western Tower (Greymoor_06)

**Game ID:** Greymoor_06

**Contributors:** Isssma

#### Subrooms

- lower section
- guarded platforms
- lower spike wheel
- upper spike wheel
- tower top section
- whisp thicket entrance
- middle section

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | lower section | [Greymoor Towers Patio (Greymoor_05)](#greymoor-towers-patio-greymoor05) | LL | none |  | Verified |  |
| LL | lower left | lower section | [Greymoor Western Room (Greymoor_07)](#greymoor-western-room-greymoor07) | LT | none |  | Verified |  |
| ML | middle left | lower spike wheel | [Greymoor Western Room (Greymoor_07)](#greymoor-western-room-greymoor07) | UT | none |  | Verified |  |
| MR | middle right | upper spike wheel | [Greymoor Middle Passage (Greymoor_10)](#greymoor-middle-passage-greymoor10) | L | none |  | Verified |  |
| YP | Yanarby Path | upper spike wheel | [Yarnaby Place (Wisp_03)](#yarnaby-place-wisp03) | R | none |  | Verified |  |
| GR | garmon room | lower spike wheel | [Greymoor Towers Patio (Greymoor_05)](#greymoor-towers-patio-greymoor05) | ML | none |  | Verified |  |
| UR | upper right | whisp thicket entrance | [Greymoor Upper Towers Path (Greymoor_11)](#greymoor-upper-towers-path-greymoor11) | U | none |  | Verified |  |
| T | Top | whisp thicket entrance | [Wisp Thicket Bench (Wisp_04)](#wisp-thicket-bench-wisp04) | B | faydown cloak |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PG1 | plartform gap 1 | lower section | guarded platforms | ledge grab OR silk soar OR cling grip OR progressive swift step 2 OR medium shaman pogo  OR easy beast needle strike |  | Verified |  |
| PG1 | plartform gap 1 | guarded platforms | lower section | none (just fall) |  | Verified |  |
| PG2 | platform gap 2 | middle section | lower spike wheel | ledge grab OR silk soar OR cling grip OR progressive swift step 1 OR easy beast needle strike |  | Verified |  |
| PG2 | platform gap 2 | lower spike wheel | middle section | none (just fall) |  | Verified |  |
| PG3 | platform gap 3 | lower spike wheel | upper spike wheel | cling grip OR silk soar OR (faydown cloak AND (easy scuttlebrace OR progressive swift step 1)) |  | Verified |  |
| PG3 | platform gap 3 | upper spike wheel | lower spike wheel | none (just fall) |  | Verified |  |
| F1 | fall 1 | upper spike wheel | tower top section | unlock top trapdoor AND spike pogo AND (faydown cloak OR ledge grab OR cling grip) |  | Verified |  |
| F1 | fall 1 | tower top section | upper spike wheel | unlock top trapdoor |  | Verified |  |
| S1 | shaft 1 | tower top section | whisp thicket entrance | silk soar OR cling grip OR medium scuttlebrace OR (easy scuttlebrace AND (faydown cloak OR ledge grab)) |  | Verified |  |
| S1 | shaft 1 | whisp thicket entrance | tower top section | none (just fall) |  | Verified |  |
| PG4 | platform gap 4 | middle section | guarded platforms | nothing |  | Verified |  |
| PG4 | platform gap 4 | guarded platforms | middle section | ledge grab OR silk soar OR cling grip  OR easy shaman pogo  OR easy beast needle strike OR faydown cloak |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Greymoor - Tower | tower top section | none |  | Verified | collectible |  |
| Greymoor - Rosary Cache #10 | middle section | nothing |  | Verified | resource |  |
| top trapdoor | tower top section | break lever right OR break lever left OR break lever up |  | Verified | blockade |  |

### Greymoor Bellway (Bellway_04)

**Game ID:** Bellway_04

**Contributors:** Isssma

#### Subrooms

- upper entrance
- lower passage
- bellway zone

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | upper entrance | [Greymoor Towers Patio (Greymoor_05)](#greymoor-towers-patio-greymoor05) | LR | none |  | Verified |  |
| BW | Bellway | bellway zone | [Bellway Menu](#bellway-menu) | GM | unlock bellway greymoor |  | Verified |  |
| D | down | lower passage | [Greymoor Rat Tunnel (Greymoor_16)](#greymoor-rat-tunnel-greymoor16) | T | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PG1 | platform gap 1 | upper entrance | bellway zone | nothing |  | Verified |  |
| PG1 | platform gap 1 | bellway zone | upper entrance | ledge grab OR cling grip OR silk soar OR faydown cloak OR easy scuttlebrace |  | Verified |  |
| HP | hidden passage | bellway zone | lower passage | break wall left |  | Verified |  |
| HP | hidden passage | lower passage | bellway zone | break wall right AND (ledge grab OR faydown cloak OR easy scuttlebrace OR cling grip) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bellway Greymoor | bellway zone | Unlock Bellway Rosary Lock |  | Verified | travel |  |
| Bellway Rosary Lock | bellway zone | rosaries 60 |  | Verified | lock |  |

### Greymoor Bone Scroll Room (Greymoor_21)

**Game ID:** Greymoor_21

**Contributors:** Isssma

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top |  | [Greymoor Lower Halfway Home Path (Greymoor_13)](#greymoor-lower-halfway-home-path-greymoor13) | D | Ledge grab OR faydown cloak OR silk soar OR cling grip OR medium shaman pogo |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Relic: Bone Scroll (Greymoor) |  | swim |  | Verified | collectible |  |

### Greymoor Chapel of The Reaper (Greymoor_20c)

**Game ID:** Greymoor_20c

**Contributors:** Isssma

#### Subrooms

- entrance section
- gauntlet room
- upper area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | entrance section | [Greymoor Chapel of The Reaper Entrance (Greymoor_20b)](#greymoor-chapel-of-the-reaper-entrance-greymoor20b) | CHE | nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SW | spike wheel | entrance section | gauntlet room | unlock gauntlet airlock AND ( spike pogo OR ledge grab OR faydown cloak OR cling grip OR (silk soar AND (clawline OR sharpdart OR drifters cloak OR progressive swift step 2))) |  | Verified |  |
| SW | spike wheel | gauntlet room | entrance section | unlock gauntlet airlock |  | Verified |  |
| PG1 | platform gap | gauntlet room | upper area | complete Chapel of the Reaper Gauntlet AND (ledge grab OR cling grip OR faydown cloak OR silk soar) |  | Verified |  |
| PG1 | platform gap | upper area | gauntlet room | complete Chapel of the Reaper Gauntlet |  | Verified |  |
| F1 | fall 1 | upper area | entrance section | clear tied platform AND (ledge grab OR cling grip OR faydown cloak OR silk soar) |  | Verified |  |
| F1 | fall 1 | entrance section | upper area | clear tied platform AND ( cling grip OR silk soar OR (faydown cloak AND easy scuttlebrace)) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Crest: Reaper | upper area | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified | collectible |  |
| Chapel of the Reaper Gauntlet | gauntlet room | nothing |  | Verified | gauntlet |  |
| gauntlet airlock | entrance section | hit lever right OR hit lever left OR hit lever up |  | Verified | blockade |  |
| tied platform | upper area | break vines left OR break vines up OR break vines right |  | Verified | blockade |  |

### Greymoor Chapel of The Reaper Entrance (Greymoor_20b)

**Game ID:** Greymoor_20b

**Contributors:** Isssma

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CHE | chapel Entrance |  | [Greymoor Chapel of The Reaper (Greymoor_20c)](#greymoor-chapel-of-the-reaper-greymoor20c) | L | nothing |  | Verified | MUST NOT OWN REAPER CREST, the door will close if crest is owned at all blocking the exit |
| R | right |  | [Greymoor Western Room (Greymoor_07)](#greymoor-western-room-greymoor07) | CH | nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Greymoor Craw Lake Entrance (Greymoor_15)

**Game ID:** Greymoor_15

**Contributors:** Isssma

#### Subrooms

- upper section
- lower left section
- lower right section
- middle section
- craw lake middle entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | lower left section | [Greymoor East Bellshrine Room (Greymoor_02)](#greymoor-east-bellshrine-room-greymoor02) | LR | none |  | Verified |  |
| LR | lower right | lower right section | [Greymoor Craw Lake (Greymoor_15b)](#greymoor-craw-lake-greymoor15b) | LL | swim OR medium enemy pogo OR flea brew OR progressive swift step 1 OR clawline OR sharpdart OR drifters cloak OR faydown cloak |  | Verified |  |
| UR | upper right | craw lake middle entrance | [Greymoor Craw Lake (Greymoor_15b)](#greymoor-craw-lake-greymoor15b) | ML | none |  | Verified |  |
| UL | upper left | upper section | [Greymoor East Bellshrine Room (Greymoor_02)](#greymoor-east-bellshrine-room-greymoor02) | MR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ASP | air shaft platform | lower left section | lower right section | drifters cloak OR silk soar OR (faydown cloak AND (cling grip OR ledge grab)) |  | Verified |  |
| ASP | air shaft platform | lower right section | lower left section | silk soar OR cling grip OR easy enemy pogo OR (faydown cloak AND ledge grab) |  | Verified |  |
| F | fall | lower right section | middle section | silk soar OR hard enemy pogo |  | Verified |  |
| F | fall | middle section | lower right section | nothing (just fall) |  | Verified |  |
| C | climb | middle section | upper section | ledge grab OR faydown cloak OR silk soar OR cling grip OR scuttlebrace |  | Verified |  |
| C | climb | upper section | middle section | nothing (just fall) |  | Verified |  |
| CD | closed door | upper section | craw lake middle entrance | prereq crawlake door AND (silk soar OR ledge grab OR faydown cloaK OR medium enemy pogo OR cling grip) |  | Verified |  |
| CD | closed door | craw lake middle entrance | upper section | prereq crawlake door |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Frayed Rosary String #1 | middle section | nothing |  | Verified | resource |  |
| Greymoor - Rosary Cache #18 | upper section | silk soar OR faydown cloak OR hard enemy pogo OR ((medium enemy pogo OR ledge grab OR cling grip) AND (progressive swift step 1 OR sharpdart OR clawline OR drifters cloak)) |  | Verified | resource |  |
| crawlake door | craw lake middle entrance | flip lever up OR flip lever right OR flip lever left |  | Verified | switch |  |

### Greymoor Entry to Bellhart (Greymoor_08)

**Game ID:** Greymoor_08

**Contributors:** skai AND Isssma

#### Subrooms

- Top Section
- Bottom Left Section
- Top Right Section
- Bottom Right Section
- Bottom Middle Section

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | Bottom Left Section | [Bellhart Right Entrance (Belltown_06)](#bellhart-right-entrance-belltown06) | R | nothing |  | Verified |  |
| T | Top | Top Section | [Greymoor Western Room (Greymoor_07)](#greymoor-western-room-greymoor07) | D | nothing |  | Verified |  |
| R | Right | Top Right Section | [Greymoor Rat Tunnel (Greymoor_16)](#greymoor-rat-tunnel-greymoor16) | L | nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TBM | Top to Bottom Middle | Top Section | Bottom Middle Section | prereq tied airstream |  | Verified |  |
| TBM | Top to Bottom Middle | Bottom Middle Section | Top Section | (Drifters Cloak OR Silk Soar OR (Faydown AND Cling Grip) OR (Faydown AND medium Scuttlebrace)) AND prereq tied airstream |  | Verified |  |
| TRB | Top Right to Bottom Right | Bottom Right Section | Top Right Section | Ledge Grab OR Silk Soar OR Faydown OR Clawline OR Scuttlebrace OR (Flea Brew) |  | Verified |  |
| TRB | Top Right to Bottom Right | Top Right Section | Bottom Right Section | nothing (Fall) |  | Verified |  |
| BLM | Bottom Left to Middle | Bottom Left Section | Bottom Middle Section | Dash OR Sprint OR Ledge Grab OR Silk Soar OR Faydown OR Clawline OR Cling Grip OR (Flea Brew) |  | Verified |  |
| BLM | Bottom Left to Middle | Bottom Middle Section | Bottom Left Section | nothing |  | Verified |  |
| BMR | Bottom Middle to Right | Bottom Middle Section | Bottom Right Section | nothing (Jump) |  | Verified |  |
| BMR | Bottom Middle to Right | Bottom Right Section | Bottom Middle Section | nothing (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Rosary Cache #14 | Top Right Section | nothing |  | Verified | resource |  |
| Flea Brew | Bottom Left Section | complete THE The Lost Fleas Wish Granted |  | Verified | collectible |  |
| Flea Caravan - Spool fragment | Bottom Left Section | after flea caravan move to blasted steps |  | Verified | collectible | reward for the move is the spool fragment |
| Boss: Moorwing | Bottom Left Section | invalid |  | Verified | boss | randomizer should always force moorwing at other spot for consitent logic - hero, 9/26 |
| tied airstream | Top Section | break switch left OR break switch up OR break switch right |  | Verified | blockade |  |
| flea caravan move to blasted steps | Bottom Left Section | after THE flea caravan move to greymoor AND fleas 12 AND defeat THE boss last judge |  | Verified | event | per the wiki |

### Greymoor Halfway Home (Halfway_01)

**Game ID:** Halfway_01

**Contributors:** Isssma

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Greymoor Halfway Home Exterior (Greymoor_03)](#greymoor-halfway-home-exterior-greymoor03) | HHR | nothing |  | Verified |  |
| L | left |  | [Greymoor Halfway Home Exterior (Greymoor_03)](#greymoor-halfway-home-exterior-greymoor03) | HHL | nothing |  | Verified |  |
| B | bottom |  | [Halfway Home Cellar (Ant_08)](#halfway-home-cellar-ant08) | T | prereq  Great Taste of Pharloom Wish Promised IN choral chambers dining room |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Halfwat Home - Memory Locket |  | silk soar OR (faydown cloak AND (ledge grab OR cling grip)) |  | Verified | collectible |  |
| Bugs of Pharloom - Tool Pouch |  | complete Wish: Bugs of Pharloom |  | Verified | event |  |
| Greymoor - Nuu's Scrolls |  | (silk soar OR faydown cloak OR ledge grab OR cling grip) |  | Verified | lore | Nuu must not be present in halfway home, according to the wiki she has a 50% chance to not appear but its garanteed that she leaves after certain bosses are defeated: the Skull Tyrant in the Marrow, one of the Great Conchflies in Blasted Steps, Sister Splinter in Shellwood, and Voltvyrm in Voltnest |
| Wish: Bugs of Pharloom |  | silk soar OR faydown cloak OR ledge grab OR cling grip |  | Verified | event |  |
| pressure plate |  | none (pressure switch) |  | Verified | switch |  |
| Crawbug Clearing Wish Promised |  | defeat THE boss widow |  | Verified | event | can be accepted here or at the wish board |
| Crawbug Clearing Wish Granted |  | complete Crawbug Clearing Wish Promised AND Ragpelts 25 |  | Verified | event |  |
| Greymoor Crafting Kit |  | complete Crawbug Clearing Wish Granted |  | Verified | collectible |  |

### Greymoor Halfway Home Exterior (Greymoor_03)

**Game ID:** Greymoor_03

**Contributors:** Isssma

#### Subrooms

- lower left section
- lower right section
- sinner road entrance
- tower platform
- building left
- upper center room
- middle right section
- building roof
- upper right section

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | lower left section | [Greymoor Eastern Tower (Greymoor_04)](#greymoor-eastern-tower-greymoor04) | LR | nothing |  | Verified |  |
| LR | lower right | lower right section | [Greymoor Lower Halfway Home Path (Greymoor_13)](#greymoor-lower-halfway-home-path-greymoor13) | L | nothing |  | Verified |  |
| HR | hidden right | upper right section | [Greymoor Kraft Room (Greymoor_24)](#greymoor-kraft-room-greymoor24) | L | prereq hidden right wall |  | Verified |  |
| MR | middle right | middle right section | [Greymoor Upper Halfway Home Path (Greymoor_12)](#greymoor-upper-halfway-home-path-greymoor12) | L | nothing |  | Verified |  |
| HHR | halfway home right | lower right section | [Greymoor Halfway Home (Halfway_01)](#greymoor-halfway-home-halfway01) | R | activate pressure plate IN greymoor halfway home |  | Verified |  |
| UR | upper right | sinner road entrance | [Sinner's Road Entrance (Dust_01)](#sinners-road-entrance-dust01) | L | ledge grab OR progressive swift step 1 OR clawline OR sharpdart OR cling grip OR silk soar OR faydown cloak OR medium shaman pogo  OR drifters cloak OR easy beast pogo |  | Verified |  |
| HHL | halfway home left | building left | [Greymoor Halfway Home (Halfway_01)](#greymoor-halfway-home-halfway01) | L | nothing |  | Verified |  |
| ML | middle left | tower platform | [Greymoor Eastern Tower (Greymoor_04)](#greymoor-eastern-tower-greymoor04) | MR | nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S1 | shaft 1 | lower right section | middle right section | silk soar OR cling grip OR (faydown cloak AND easy scuttlebrace) |  | Verified |  |
| S1 | shaft 1 | middle right section | lower right section | none (just fall) |  | Verified |  |
| PG1 | platform gap 1 | lower right section | building roof | silk soar OR flea brew OR drifters cloak OR faydown cloak OR progressive swift step 1 OR clawline OR sharpdart OR easy beast pogo  OR easy architect needle strike OR easy wanderer needle strike OR ((easy reaper needle strike OR medium shaman pogo) AND ledge grab) |  | Verified |  |
| PG1 | platform gap 1 | building roof | lower right section | none (just fall) |  | Verified |  |
| PG2 | platform gap 2 | building roof | middle right section | medium enemy pogo OR silk soar OR (faydown cloak AND (progressive swift step 2 OR sharpdart OR ((ledge grab OR cling grip) AND (progressive swift step 1 OR clawline OR drifters cloak OR medium shaman pogo OR easy beast pogo)))) |  | Verified |  |
| PG2 | platform gap 2 | middle right section | building roof | none (just fall) |  | Verified |  |
| F1 | fall 1 | middle right section | tower platform | silk soar |  | Verified |  |
| F1 | fall 1 | tower platform | middle right section | none (just fall) |  | Verified |  |
| F2 | fall 2 | tower platform | building roof | none |  | Verified |  |
| F2 | fall 2 | building roof | tower platform | silk soar OR activate tower elevator |  | Verified |  |
| LG | lake gap | building left | lower left section | progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR silk soar OR drifters cloak OR activate tower elevator OR swim OR easy hunter pogo OR easy reaper pogo OR easy beast pogo OR easy witch pogo OR easy architect pogo OR easy shaman pogo |  | Verified |  |
| LG | lake gap | lower left section | building left | silk soar OR faydown cloak OR (activate tower elevator  AND (drifters cloak OR progressive swift step 1 OR sharpdart OR clawline OR easy beast pogo OR easy needle strike stall (architect) OR (swim AND (ledge grab OR cling grip)))) OR (activate tower elevator AND cling grip) |  | Verified |  |
| PG3 | platform gap 3 | building roof | building left | none (just fall) |  | Verified |  |
| PG3 | platform gap 3 | building left | building roof | silk soar OR (activate tower elevator AND faydown cloak) |  | Verified |  |
| G1 | gap 1 | tower platform | upper right section | ledge grab OR easy hunter pogo OR easy reaper pogo OR easy beast pogo OR easy shaman pogo OR flea brew OR progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR drifters cloak OR silksoar OR have Crest Architect |  | Verified |  |
| G1 | gap 1 | upper right section | tower platform | none (just fall) |  | Verified |  |
| S2 | shaft 2 | upper right section | sinner road entrance | silk soar OR cling grip OR easy scuttlebrace |  | Verified |  |
| S2 | shaft 2 | sinner road entrance | upper right section | none (just fall) |  | Verified |  |
| BG | baloon gap | upper right section | upper center room | hard enemy pogo OR (medium enemy pogo AND clawline) |  | Verified |  |
| BG | baloon gap | upper center room | upper right section | none (just fall) |  | Verified |  |
| G2 | gap 2 | upper center room | sinner road entrance | easy enemy pogo OR clawline OR progressive swift step 1 OR faydown cloak OR drifters cloak OR sharpdart OR easy hunter pogo OR easy reaper pogo OR easy beast pogo OR easy witch pogo OR easy architect pogo |  | Verified |  |
| G2 | gap 2 | sinner road entrance | upper center room | silk soar |  | Verified |  |
| F3 | fall 3 | tower platform | upper center room | silk soar |  | Verified |  |
| F3 | fall 3 | upper center room | tower platform | none (just fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Rosary Cache #4 | sinner road entrance | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #5 | sinner road entrance | none |  | Verified | resource |  |
| Greymoor - Orders | upper center room | none |  | Verified | lore |  |
| tower elevator | tower platform | none (pressure switch) |  | Verified | switch |  |
| hidden right wall | upper right section | break wall right OR break wall up |  | Verified | blockade |  |

### Greymoor Kraft Room (Greymoor_24)

**Game ID:** Greymoor_24

**Contributors:** Isssma

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Greymoor Halfway Home Exterior (Greymoor_03)](#greymoor-halfway-home-exterior-greymoor03) | HR | nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea Greymoor - Kraft |  | silk soar OR cling grip OR easy scuttlebrace |  | Verified | collectible |  |

### Greymoor Lower Halfway Home Path (Greymoor_13)

**Game ID:** Greymoor_13

**Contributors:** Isssma

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Greymoor Halfway Home Exterior (Greymoor_03)](#greymoor-halfway-home-exterior-greymoor03) | LR | progressive swift step 1 OR clawline OR faydown cloak OR drifters cloak OR sharpdart OR easy beast pogo OR flea brew OR (cling grip AND (easy hunter pogo OR easy reaper pogo OR easy witch pogo OR easy architect pogo OR easy shaman pogo)) OR swim |  | Verified |  |
| R | right |  | [Greymoor West Bellshrine Room  (Greymoor_01)](#greymoor-west-bellshrine-room-greymoor01) | LL | swim OR easy hunter pogo OR easy reaper pogo OR easy wanderer pogo OR easy beast pogo OR easy witch pogo OR easy architect pogo OR easy shaman pogo OR progressive swift step 2 OR clawline OR sharpdart OR (drifters cloak AND (ledge grab OR progressive swift step 1 OR faydown cloak)) OR (faydown cloak AND progressive swift step 1) |  | Verified |  |
| D | down |  | [Greymoor Bone Scroll Room (Greymoor_21)](#greymoor-bone-scroll-room-greymoor21) | T | swim OR (clawline AND ledge grab) |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Greymoor Middle Passage (Greymoor_10)

**Game ID:** Greymoor_10

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Greymoor Western Tower (Greymoor_06)](#greymoor-western-tower-greymoor06) | MR | nothing |  | Verified |  |
| R | right |  | [Greymoor Eastern Tower (Greymoor_04)](#greymoor-eastern-tower-greymoor04) | ML | nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Greymoor Rat Tunnel (Greymoor_16)

**Game ID:** Greymoor_16

**Contributors:** skai AND Isssma

#### Subrooms

- Top Left Shaft (Upper)
- Top Left Shaft (Center)
- Top Left Shaft (bottom)
- Top Right Section (Upper)
- Top Right Section (Center)
- Top Right Section (Bottom)
- bellway secret entrance
- bottom section left
- bottom section right

- **bottom section right:** fat fuck rat inside

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | Top Left Shaft (Center) | [Greymoor Entry to Bellhart (Greymoor_08)](#greymoor-entry-to-bellhart-greymoor08) | R | nothing |  | Verified |  |
| T | Top | bellway secret entrance | [Greymoor Bellway (Bellway_04)](#greymoor-bellway-bellway04) | D | nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PG1 | platform gap 1 | Top Left Shaft (Center) | Top Left Shaft (Upper) | ledge grab OR silk soar OR faydown cloak OR cling grip OR easy scuttlebrace OR (easy enemy pogo AND (clawline OR progressive swift step 1 OR sharpdart OR drifters cloak OR easy beast pogo OR easy shaman pogo OR easy hunter pogo OR easy architect pogo OR easy reaper pogo)) |  | Verified |  |
| PG1 | platform gap 1 | Top Left Shaft (Upper) | Top Left Shaft (Center) | nothing (just fall) |  | Verified |  |
| PG2 | platform gap 2 | Top Left Shaft (Center) | Top Left Shaft (bottom) | nothing (just fall) |  | Verified |  |
| PG2 | platform gap 2 | Top Left Shaft (bottom) | Top Left Shaft (Center) | ledge grab OR silk soar OR faydown cloak OR cling grip OR easy scuttlebrace OR medium enemy pogo OR easy  shaman pogo OR easy beast pogo OR easy reaper pogo |  | Verified |  |
| S1 | shaft 1 | Top Left Shaft (Center) | Top Right Section (Center) | clear tied blockade |  | Verified |  |
| S1 | shaft 1 | Top Right Section (Center) | Top Left Shaft (Center) | clear tied blockade AND (cling grip OR easy scuttlebrace OR silksoar OR (faydown cloak AND (ledge grab OR medium shaman pogo))) |  | Verified |  |
| PG3 | platform gap 3 | Top Right Section (Center) | Top Right Section (Bottom) | nothing (just fall) |  | Verified |  |
| PG3 | platform gap 3 | Top Right Section (Bottom) | Top Right Section (Center) | faydown cloak OR silk soar OR cling grip OR ledge grab OR (easy scuttlebrace AND drifters cloak) OR medium enemy pogo |  | Verified |  |
| PG4 | platform gap 4 | Top Right Section (Center) | Top Right Section (Upper) | cling grip OR faydown cloak OR silk soar OR ledge grab |  | Verified |  |
| PG4 | platform gap 4 | Top Right Section (Upper) | Top Right Section (Center) | nothing (jsut fall) |  | Verified |  |
| F1 | fall 1 | Top Right Section (Bottom) | bottom section right | nothing (just fall) |  | Verified |  |
| F1 | fall 1 | bottom section right | Top Right Section (Bottom) | hard enemy pogo AND faydown cloak |  | Verified |  |
| SG | swimming gap | bottom section right | bottom section left | (swim AND (ledge grab OR faydown cloak OR cling grip)) OR (clawline AND faydown cloak AND drifters cloak) |  | Verified |  |
| SG | swimming gap | bottom section left | bottom section right | swim OR ((clawline OR sharpdart) AND (faydown cloak OR drifters cloak)) OR (faydown cloak AND progressive swift step 2 AND drifters cloak) OR (clawline AND hard beast pogo) |  | Verified |  |
| F2 | fall 2 | Top Left Shaft (bottom) | bottom section left | open airlock left OR open airlock right OR open airlock up |  | Verified |  |
| F2 | fall 2 | bottom section left | Top Left Shaft (bottom) | (open airlock left OR open airlock right OR open airlock up) AND (progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR easy beast pogo OR drifters cloak) |  | Verified |  |
| BW | breakable wall | Top Right Section (Center) | bellway secret entrance | break wall right OR break wall up |  | Verified |  |
| BW | breakable wall | bellway secret entrance | Top Right Section (Center) | break wall left OR break wall up |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Breakable wooden Wall | Top Right Section (Bottom) | break wall right OR break wall up |  | Verified | blockade |  |
| Greymoor - Shell Shard Cache #1 | bottom section right | none |  | Verified | resource |  |
| Greymoor - Shell Shard Cache #2 | bottom section right | none |  | Verified | resource |  |
| Greymoor - Memory Locket | Top Right Section (Upper) | none |  | Verified | collectible |  |
| Greymoor - Cage Record | Top Left Shaft (Upper) | nothing |  | Verified | lore |  |
| Greymoor - Rosary Cache #23 | Top Right Section (Bottom) | clear Breakable wooden Wall |  | Verified | resource |  |
| Greymoor - Rosary Cache #24 | Top Right Section (Bottom) | clear Breakable wooden Wall |  | Verified | resource |  |
| Greymoor - Rosary Cache #25 | Top Right Section (Bottom) | clear Breakable wooden Wall |  | Verified | resource |  |
| tied blockade | Top Left Shaft (Center) | break switch left OR break switch up OR break switch right |  | Verified | blockade |  |

### Greymoor Silver Shells room (Greymoor_17)

**Game ID:** Greymoor_17

**Contributors:** Isssma

#### Subrooms

- main path
- hidden area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | main path | [Greymoor East Bellshrine Room (Greymoor_02)](#greymoor-east-bellshrine-room-greymoor02) | HR | none |  | Verified |  |
| U | upper | main path | [Sinner's Road Styx Room (Dust_11)](#sinners-road-styx-room-dust11) | B | faydown cloak OR cling grip OR easy scuttlebrace OR silk soar |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| C | climb | main path | hidden area | none (just fall) |  | Verified |  |
| C | climb | hidden area | main path | ledge grab OR silk soar OR faydown cloak OR cling grip OR (easy scuttlebrace AND (easy enemy pogo OR progressive swift step 2 OR clawline OR sharpdart)) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Shell Shard Cache #3 | hidden area | prereq wooden wall |  | Verified | resource |  |
| Greymoor - Shell Shard Cache #4 | hidden area | prereq wooden wall |  | Verified | resource |  |
| Greymoor - Shell Shard Cache #5 | hidden area | prereq wooden wall |  | Verified | resource |  |
| Greymoor - Shell Shard Cache #6 | hidden area | prereq wooden wall |  | Verified | resource |  |
| Greymoor - Shell Shard Cache #7 | hidden area | prereq wooden wall |  | Verified | resource |  |
| wooden wall | hidden area | break wall: left |  | Verified | blockade |  |

### Greymoor Towers Patio (Greymoor_05)

**Game ID:** Greymoor_05

**Contributors:** Isssma

#### Subrooms

- upper area
- lower section
- garmond room
- east tower entrance
- lower hanging platforms
- left middle section

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | lower section | [Greymoor Bellway (Bellway_04)](#greymoor-bellway-bellway04) | L | nothing |  | Verified |  |
| LL | lower left | lower section | [Greymoor Western Tower (Greymoor_06)](#greymoor-western-tower-greymoor06) | LR | nothing |  | Verified |  |
| ML | middle left | garmond room | [Greymoor Western Tower (Greymoor_06)](#greymoor-western-tower-greymoor06) | GR | nothing |  | Verified |  |
| MR | middle right | east tower entrance | [Greymoor Eastern Tower (Greymoor_04)](#greymoor-eastern-tower-greymoor04) | LL | ledge grab OR cling grip OR silk soar OR hard scuttlebrace |  | Verified |  |
| SC | slab capture | lower section | [Slab Capture](#slab-capture) | GM | after Get Kidnapped |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| F1 | fall 1 | east tower entrance | lower hanging platforms | clawline OR (progressive swift step 1 AND (faydown cloak OR (sharpdart AND ledge grab))) OR (faydown cloak AND  flea brew) OR (medium enemy pogo AND (progressive swift step 2 OR drifters cloak OR faydown cloak OR sharpdart)) OR (medium scuttlebrace AND (drifters cloak OR sharpdart)) |  | Verified |  |
| F1 | fall 1 | lower hanging platforms | east tower entrance | nothing (just fall) |  | Verified |  |
| C1 | climb 1 | lower section | east tower entrance | silk soar OR ledge grab OR easy enemy pogo OR faydown cloak |  | Verified |  |
| C1 | climb 1 | east tower entrance | lower section | nothing (just fall) |  | Verified |  |
| PG1 | platform gap 1 | lower hanging platforms | upper area | faydown cloak OR (medium enemy pogo AND (progressive swift step 2 OR drifters cloak OR faydown cloak OR sharpdart)) OR silk soar |  | Verified |  |
| PG1 | platform gap 1 | upper area | lower hanging platforms | nothing (just fall) |  | Verified |  |
| F2 | fall 2 | upper area | east tower entrance | nothing (just fall) |  | Verified |  |
| F2 | fall 2 | east tower entrance | upper area | cling grip OR silk soar |  | Verified |  |
| BG1 | big gap 1 | lower hanging platforms | left middle section | drifters cloak |  | Verified |  |
| PG2 | platform gap 2 | lower section | left middle section | ledge grab OR medium enemy pogo OR silk soar OR faydown cloak OR cling grip |  | Verified |  |
| PG2 | platform gap 2 | left middle section | lower section | nothing (just fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Rosary Cache #7 | left middle section | nothing |  | Verified | resource |  |
| Greymoor - Rosary Cache #8 | left middle section | nothing |  | Verified | resource |  |
| Greymoor - Rosary Cache #9 | upper area | nothing |  | Verified | resource |  |
| Greymor - Shard Bundle #1 | upper area | faydown cloak OR progressive swift step 1 OR easy enemy pogo OR silk soar OR sharpdart OR clawline |  | Verified | resource |  |
| Boos: MoorWing | lower section | Act 2 AND complete THE the lost fleas wish granted |  | Verified | boss | maybe just change the wqish to moorwing spkipped ion the other room |
| Wardenfly | lower section | ( act 1 AND act 2 ) AND defeat THE bell beast boss fight |  | Verified | enemy | per the wiki |
| Get Kidnapped | lower section | after wardenfly |  | Verified | event |  |

### Greymoor Upper Halfway Home Path (Greymoor_12)

**Game ID:** Greymoor_12

**Contributors:** Isssma

#### Subrooms

- left section
- right section
- upper platform section
- check platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left section | [Greymoor Halfway Home Exterior (Greymoor_03)](#greymoor-halfway-home-exterior-greymoor03) | MR | swim OR medium enemy pogo OR progressive swift step 1 OR clawline OR sharpdart OR flea brew OR faydown cloak OR drifters cloak OR easy hunter pogo OR easy reaper pogo OR easy beast pogo OR easy witch pogo OR easy architect pogo OR (medium shaman pogo AND ledge grab) |  | Verified |  |
| R | right | right section | [Greymoor West Bellshrine Room  (Greymoor_01)](#greymoor-west-bellshrine-room-greymoor01) | TL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TP | tall platform | left section | right section | swim OR faydown cloak OR medium scuttlebrace OR medium enemy pogo OR ((easy enemy pogo OR flea brew) AND (ledge grab OR cling grip OR clawline OR progressive swift step 1 OR sharpdart OR easy hunter pogo OR easy reaper pogo OR easy beast pogo OR easy witch pogo OR easy architect pogo OR easy shaman pogo)) |  | Verified |  |
| TP | tall platform | right section | left section | swim OR faydown cloak OR medium scuttlebrace OR medium enemy pogo OR (easy enemy pogo AND (cling grip OR ledge grab)) OR (cling grip AND (progressive swift step 1 OR clawline OR sharpdart)) OR (silk soar AND (clawline OR progressive swift step 2 OR sharpdart)) |  | Verified |  |
| UP | upper platform | left section | upper platform section | silk soar OR easy enemy pogo OR progressive swift step 1 OR faydown cloak OR sharpdart OR clawline OR flea brew OR (drifters cloak AND (cling grip OR ledge grab)) |  | Verified |  |
| UP | upper platform | upper platform section | left section | none (just fall) |  | Verified |  |
| G | gap | check platform | upper platform section | faydown cloak OR (cling grip AND (clawline OR progressive swift step 1)) |  | Verified |  |
| G | gap | upper platform section | check platform | faydown cloak OR drifters cloak OR progressive swift step 1 OR sharpdart OR clawline OR easy hunter pogo OR easy reaper pogo OR easy beast pogo OR easy witch pogo OR easy architect pogo OR easy shaman pogo |  | Verified |  |
| PG | pogo skip | left section | check platform | faydown cloak OR silk soar OR (hard enemy pogo AND ledge grab) |  | Verified |  |
| PG | pogo skip | check platform | left section | none (fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor #2 - Shard Bundle: | check platform | none |  | Verified | resource |  |

### Greymoor Upper Towers Path (Greymoor_11)

**Game ID:** Greymoor_11

**Contributors:** Isssma

#### Subrooms

- main section
- airstream lever
- upper corridor

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| U | up | upper corridor | [Greymoor Western Tower (Greymoor_06)](#greymoor-western-tower-greymoor06) | UR | nothing |  | Verified |  |
| R | right | main section | [Greymoor Eastern Tower (Greymoor_04)](#greymoor-eastern-tower-greymoor04) | UL | nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S1 | shaft 1 | main section | upper corridor | silk soar OR cling grip OR medium scuttlebrace |  | Verified |  |
| S1 | shaft 1 | upper corridor | main section | none (just fall) |  | Verified |  |
| D1 | drop 1 | main section | airstream lever | none (just fall) |  | Verified |  |
| D1 | drop 1 | airstream lever | main section | spike pogo OR silk soar OR ledge grab OR easy enemy pogo OR cling grip OR faydown cloak OR progressive swift step 2 |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Rosary Cache #15 | main section | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #16 | main section | none |  | Verified | resource |  |
| Greymoor - Rosary Cache #17 | main section | drifters cloak OR (silk soar AND (progressive swift step 2 OR sharpdart OR clawline OR faydown cloak OR hard enemy pogo)) |  | Verified | resource |  |
| airstream | airstream lever | hit lever right OR hit lever up |  | Verified | switch |  |

### Greymoor West Bellshrine Room  (Greymoor_01)

**Game ID:** Greymoor_01

**Contributors:** Isssma

#### Subrooms

- main path
- middle section left
- middle section right
- upper path right
- upper path left

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | top left | upper path left | [Greymoor Upper Halfway Home Path (Greymoor_12)](#greymoor-upper-halfway-home-path-greymoor12) | R | Ledge grab OR cling grip OR enemy pogo OR faydown cloak OR medium scuttlebrace OR (progressive swift step 1 AND (clawline OR sharpdart)) OR silk soar |  | Verified |  |
| TR | top right | upper path right | [Greymoor East Bellshrine Room (Greymoor_02)](#greymoor-east-bellshrine-room-greymoor02) | BL | cling grip OR progressive swift step 1 OR faydown cloak OR silk soar OR clawline OR sharpdart OR (drifters cloak AND ledge grab) |  | Verified |  |
| LR | lower right | main path | [Greymoor East Bellshrine Room (Greymoor_02)](#greymoor-east-bellshrine-room-greymoor02) | LSL | (prereq shrine entrance lever AND (ledge grab OR medium shaman pogo OR faydown cloak OR silk soar)) OR nothing |  | Verified |  |
| LL | lower left | main path | [Greymoor Lower Halfway Home Path (Greymoor_13)](#greymoor-lower-halfway-home-path-greymoor13) | R | none |  | Verified |  |
| MR | middle right | middle section right | [Greymoor Bellshrine (Bellshrine_02)](#greymoor-bellshrine-bellshrine02) | L | ( bellshrinesanity off AND activate bellshrine switch IN greymoor bellshrine )  OR ( bellshrinesanity on AND have bell greymoor ) |  | Verified | need to make sure this stays in sync with the connection on the other side |
| D | down | main path | [Far Fields Upper Shaft (Bone_East_11)](#far-fields-upper-shaft-boneeast11) | C | clear greymoor floor blockade IN far fields upper shaft |  | Verified | MUST enter from far fields to activate this connection |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LS | lever switch | main path | middle section right | cling grip OR medium scuttlebrace OR (prereq shrine entrance lever AND (ledge grab OR medium shaman pogo)) |  | Verified |  |
| LS | lever switch | middle section right | main path | none (Switch is on this sidel) |  | Verified |  |
| P | Platform | middle section left | upper path left | ledge grab OR faydown cloak OR silk soar OR medium shaman pogo OR cling grip |  | Verified |  |
| P | Platform | upper path left | middle section left | none (just fall) |  | Verified |  |
| F1 | Fall 1 | middle section right | upper path right | Silk soar |  | Verified |  |
| F1 | Fall 1 | upper path right | middle section right | none (just fall) |  | Verified |  |
| BG | Big Gap | middle section right | middle section left | progressive swift step 1 AND clawline AND drifters cloak AND faydown cloak |  | Verified |  |
| BG | Big Gap | middle section left | middle section right | progressive swift step 1 AND clawline AND drifters cloak AND faydown cloak |  | Verified |  |
| G | Gap | upper path right | upper path left | faydown cloak OR drifters cloak OR flea brew OR progressive swift step 1 OR clawline OR sharpdart OR medium scuttlebrace |  | Verified |  |
| G | Gap | upper path left | upper path right | ledge grab OR medium enemy pogo OR progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR easy beast pogo OR medium shaman pogo |  | Verified |  |
| F2 | Fall 2 | middle section left | main path | none (just fall) |  | Verified |  |
| F2 | Fall 2 | main path | middle section left | silk soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor #1 - Rosary Cache | middle section left | none |  | Verified | resource |  |
| shrine entrance lever | middle section right | flip switch right OR flip switch up OR flip switch left |  | Verified | switch |  |

### Greymoor Western Room (Greymoor_07)

**Game ID:** Greymoor_07

**Contributors:** Isssma

#### Subrooms

- upper section
- middle section
- tower entrance
- rosaries room
- lower section
- door cage

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LT | lower tower | door cage | [Greymoor Western Tower (Greymoor_06)](#greymoor-western-tower-greymoor06) | LL | nothing |  | Verified |  |
| UT | upper tower | upper section | [Greymoor Western Tower (Greymoor_06)](#greymoor-western-tower-greymoor06) | ML | ledge grab OR faydown cloak OR silk soar OR medium enemy pogo OR cling grip |  | Verified |  |
| D | down | lower section | [Greymoor Entry to Bellhart (Greymoor_08)](#greymoor-entry-to-bellhart-greymoor08) | T | nothing |  | Verified |  |
| CH | chapel | middle section | [Greymoor Chapel of The Reaper Entrance (Greymoor_20b)](#greymoor-chapel-of-the-reaper-entrance-greymoor20b) | R | nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PG1 | platform gap 1 | upper section | middle section | nothing (just fall) |  | Verified |  |
| PG1 | platform gap 1 | middle section | upper section | ledge grab OR cling grip OR silk soar OR easy scuttlebrace OR progressive swift step 2 |  | Verified |  |
| F1 | fall 1 | middle section | tower entrance | nothing |  | Verified |  |
| F1 | fall 1 | tower entrance | middle section | silk soar OR (cling grip AND (faydown cloak OR clawline OR sharpdart OR (drifters cloak AND (ledge grab OR progressive swift step 2 OR easy beast pogo OR easy shaman pogo)) OR (easy architect needle strike AND progressive swift step 2))) |  | Verified |  |
| B1 | blockade 1 | tower entrance | door cage | unlock tower entrance door |  | Verified |  |
| B1 | blockade 1 | door cage | tower entrance | unlock tower entrance door |  | Verified |  |
| PG2 | platform gap 2 | tower entrance | rosaries room | nothing |  | Verified |  |
| PG2 | platform gap 2 | rosaries room | tower entrance | progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR silk soar OR ledge grab OR easy architect needle strike OR easy beast pogo  OR drifters cloak |  | Verified |  |
| PG3 | platform gap 3 | rosaries room | lower section | nothing |  | Verified |  |
| PG3 | platform gap 3 | lower section | rosaries room | ledge grab OR faydown cloak OR cling grip OR progressive swift step 2 OR silk soar OR (medium shaman pogo AND medium scuttlebrace) |  | Verified |  |
| C1 | climb 1 | rosaries room | middle section | ledge grab OR faydown cloak OR cling grip OR progressive swift step 2 OR silk soar OR easy scuttlebrace |  | Verified |  |
| C1 | climb 1 | middle section | rosaries room | nothing |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Rosary Cache #11 | rosaries room | nothing |  | Verified | resource |  |
| Greymoor - Rosary Cache #12 | rosaries room | nothing |  | Verified | resource |  |
| Greymoor - Rosary Cache #13 | upper section | silk soar OR faydown cloak OR clawline OR progressive swift step 1 OR sharpdart OR ledge grab OR cling grip OR easy beast pogo OR medium shaman pogo |  | Verified | resource |  |
| Greymoor - Rosary Dish | rosaries room | nothing |  | Verified | resource |  |
| tower entrance door | tower entrance | break lever right OR break lever left OR break lever up |  | Verified | blockade |  |

### Pimpillo Room (Wisp_06)

**Game ID:** Wisp_06

**Contributors:** Isssma

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | down |  | [Yarnaby Place (Wisp_03)](#yarnaby-place-wisp03) | T | nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pimpillo |  | have Craftmetal |  | Verified | collectible |  |
| bounce vine wall |  | break wall: down |  | Verified | blockade | if not broken you just get bounced back |

### Yarnaby Place (Wisp_03)

**Game ID:** Wisp_03

**Contributors:** Isssma

#### Subrooms

- lower section
- upper shaft

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| YH | yanarby house | lower section | [Greymoor Yarnaby Room (Belltown_Room_doctor)](#greymoor-yarnaby-room-belltownroomdoctor) | L | have crest cursed |  | Verified |  |
| R | right | lower section | [Greymoor Western Tower (Greymoor_06)](#greymoor-western-tower-greymoor06) | YP | nothing |  | Verified |  |
| T | top | upper shaft | [Pimpillo Room (Wisp_06)](#pimpillo-room-wisp06) | D | prereq vine wall AND (silk soar OR cling grip OR easy scuttlebrace) |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S1 | shaft 1 | lower section | upper shaft | silk soar OR ((cling grip AND easy scuttlebrace) AND (faydown cloak OR progressive swift step 1 OR clawline OR sharpdart OR easy architect needle strike OR easy beast pogo OR ((flea brew OR drifters cloak) AND cling grip))) |  | Verified |  |
| S1 | shaft 1 | upper shaft | lower section | nothing (just fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Frayed Rosary String #3 | upper shaft | silk soar OR cling grip OR easy scuttlebrace |  | Verified | resource |  |
| vine wall | upper shaft | break wall: up |  | Verified | blockade | if not broken the vine wall bounces you back |

### Greymoor Yarnaby Room (Belltown_Room_doctor)

**Game ID:** Belltown_Room_doctor

**Contributors:** Isssma

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Yarnaby Place (Wisp_03)](#yarnaby-place-wisp03) | YH | nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Infestation Operation Wish Promised |  | complete THE rite of rebirth wish granted AND have crest cursed |  | Verified | event |  |
| Infestation Operation Wish Granted |  | complete Infestation Operation Wish Promised AND have Steel Spines |  | Verified | event |  |
| Crest: Witch |  | complete Infestation Operation Wish Granted |  | Verified | collectible |  |

### Halfway Home Cellar (Ant_08)

**Game ID:** Ant_08

**Contributors:** Isssma

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | Top |  | [Greymoor Halfway Home (Halfway_01)](#greymoor-halfway-home-halfway01) | B | (silk soar OR cling grip) AND complete Halfway Home Gauntlet |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Halfway Home Gauntlet |  | silk soar OR cling grip OR (faydown cloak AND ledge grab) |  | Verified | gauntlet | completing the gauntlet requires defeating all enemies stationed across the room |
| vintage nectar |  | complete Halfway Home Gauntlet |  | Verified | event |  |

## Whisp Thicket

### Eastern Wisp Thicket (Wisp_07)

**Game ID:** Wisp_07

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Wisp Thicket Shaft (Wisp_08)](#wisp-thicket-shaft-wisp08) | R | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mask Shard: Wisp Thicket |  | cling grip AND (clawline OR (faydown cloak AND spike pogo)) |  | Verified | collectible |  |

### Wisp Thicket Shaft (Wisp_08)

**Game ID:** Wisp_08

**Contributors:** samupo

#### Subrooms

- Bottom
- Right
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Bottom | [Wisp Thicket Bench (Wisp_04)](#wisp-thicket-bench-wisp04) | R | none |  |  |  |
| R | right1 | Right | [Eastern Wisp Thicket (Wisp_07)](#eastern-wisp-thicket-wisp07) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Right to Top | Right | Top | cling grip AND spike pogo |  |  |  |
| V2 | Bottom to Right | Bottom | Right | cling grip AND spike pogo AND faydown cloak |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Relic: Bone Scroll (Wisp Thicket) | Top | none |  |  | collectible |  |

### Wisp Thicket Bench (Wisp_04)

**Game ID:** Wisp_04

**Contributors:** samupo

#### Subrooms

- Bench
- Bottom
- Left

- **Bench:** somehow got this duplicated or something internally

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Wisp Thicket Grounds (Wisp_02)](#wisp-thicket-grounds-wisp02) | R | none |  |  |  |
| R | right1 | Bench | [Wisp Thicket Shaft (Wisp_08)](#wisp-thicket-shaft-wisp08) | L | none |  |  |  |
| B | bot1 | Bottom | [Greymoor Western Tower (Greymoor_06)](#greymoor-western-tower-greymoor06) | T | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| L1 | Left to Bench | Left | Bench | clawline OR dash OR spike pogo OR drifter's cloak OR faydown cloak |  |  |  |
| L2 | Left to Bottom | Left | Bottom | spike pogo OR drifter's cloak OR clawline OR dash |  |  |  |
| B1 | Bench to Left | Bench | Left | (dash AND ledge grab) OR faydown cloak OR clawline |  |  |  |
| B2 | Bench to Bottom | Bench | Bottom | drifter's cloak OR spike pogo OR clawline OR dash |  |  |  |
| V1 | Bottom to Bench | Bottom | Bench | spike pogo OR (faydown cloak AND clawline) |  |  |  |
| V2 | Bottom to Left | Bottom | Left | spike pogo AND (ledge grab OR faydown cloak OR clawline) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bench | Bench | none |  | Verified | bench |  |
| Craw Summons | Bench | Craw Summons Ready |  | Verified | collectible |  |

### Wisp Thicket Grounds (Wisp_02)

**Game ID:** Wisp_02

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 |  | [Wisp Thicket Secret Path (Wisp_05)](#wisp-thicket-secret-path-wisp05) | B | silk soar OR cling grip |  |  |  |
| R | right1 |  | [Wisp Thicket Bench (Wisp_04)](#wisp-thicket-bench-wisp04) | L | none |  |  |  |
| L | left1 |  | [Father of the Flame (Belltown_08)](#father-of-the-flame-belltown08) | R | ledge grab OR faydown cloak OR silk soar |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Necklace: Wisp Thicket |  | silk soar OR cling grip |  |  | collectible |  |

### Father of the Flame (Belltown_08)

**Game ID:** Belltown_08

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Wisp Thicket Grounds (Wisp_02)](#wisp-thicket-grounds-wisp02) | L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Wispfire Lantern |  | faydown cloak | TODO |  | collectible | You can defeat the boss naked... but maybe something is "recommended" |
| Boss: Father of the Flame |  | faydown cloak | TODO |  | boss | You can defeat the boss naked... but maybe something is "recommended" |

### Wisp Thicket Secret Path (Wisp_05)

**Game ID:** Wisp_05

**Contributors:** samupo

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom | [Wisp Thicket Grounds (Wisp_02)](#wisp-thicket-grounds-wisp02) | T | none |  |  |  |
| L | left1 | Top | [Wisp Thicket Cave (Wisp_09)](#wisp-thicket-cave-wisp09) | R | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Bottom | Top | cling grip AND (spike pogo OR (faydown cloak AND clawline)) |  |  |  |
| V | Vertical | Top | Bottom | spike pogo OR drifter's cloak |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Craftmetal: Wisp Thicket | Top | none |  |  | collectible |  |

### Wisp Thicket Cave (Wisp_09)

**Game ID:** Wisp_09

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Wisp Thicket Secret Path (Wisp_05)](#wisp-thicket-secret-path-wisp05) | L | spike pogo OR clawline OR drifter's cloak OR (faydown cloak AND dash) |  |  |  |
| T | top1 |  | [Underworks Wisp Thicket Passage (Under_23)](#underworks-wisp-thicket-passage-under23) | B | faydown cloak |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Wisp Thicket #6 |  | (dash AND cling grip) OR clawline OR spike pogo OR drifter's cloak | TODO |  | collectible | May have different requirements if entered from the top |
| Shell Shard Cache: Wisp Thicket #7 |  | (dash AND cling grip) OR clawline OR spike pogo OR drifter's cloak | TODO |  | collectible | May have different requirements if entered from the top |
| Shell Shard Cache: Wisp Thicket #1 |  | dash OR faydown cloak OR clawline OR spike pogo OR drifter's cloak |  |  | collectible |  |
| Shell Shard Cache: Wisp Thicket #2 |  | dash OR faydown cloak OR clawline OR spike pogo OR drifter's cloak |  |  | collectible |  |
| Shell Shard Cache: Wisp Thicket #3 |  | dash OR faydown cloak OR clawline OR spike pogo OR drifter's cloak |  |  | collectible |  |
| Shell Shard Cache: Wisp Thicket #4 |  | dash OR faydown cloak OR clawline OR spike pogo OR drifter's cloak |  |  | collectible |  |
| Shell Shard Cache: Wisp Thicket #5 |  | dash OR faydown cloak OR clawline OR spike pogo OR drifter's cloak |  |  | collectible |  |

## Verdania

### Verdania Placeholder

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| P | placeholder |  | [Greymoor Craw Lake (Greymoor_15b)](#greymoor-craw-lake-greymoor15b) | LR | invalid |  | Needs verification |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

## Blasted Steps

### Blasted Steps Bellway (Bellway_08)

**Game ID:** Bellway_08

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right |  | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | TL | Nothing |  | Verified |  |
| BB | Bell Beast |  | [Bellway Menu](#bellway-menu) | BS | Unlock Blasted Steps Bellway |  | Verified |  |
| L | Left |  | [Blasted Steps Thin Long Vertical (Coral_35)](#blasted-steps-thin-long-vertical-coral35) | R | Nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Blasted Steps Bellway |  | Unlock Bellway Rosary Lock |  | Verified | travel |  |
| Bellway Rosary Lock |  | Rosaries 60 |  | Verified | lock |  |
| Bench |  | Unlock Bench Rosary Lock |  | Verified | bench |  |
| Bench Rosary Lock |  | Rosaries 40 |  | Verified | lock |  |

### Blasted Steps Grindle (Coral_42)

**Game ID:** Coral_42

**Contributors:** skai

#### Subrooms

- Lower Half
- Upper Half

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right | Lower Half | [Blasted Steps Thin Long Vertical (Coral_35)](#blasted-steps-thin-long-vertical-coral35) | ML | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MO | Middle Opening | Lower Half | Upper Half | Silk Soar OR (Faydown AND (Cling Grip OR  Scuttlebrace)) |  | Verified |  |
| MO | Middle Opening | Upper Half | Lower Half | Nothing (Falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Thief's Mark | Upper Half | Nothing |  | Verified | collectible |  |
| Snitch Pick | Upper Half | Clawline |  | Verified | collectible |  |
| Relic: Psalm Cylinder (Grindle) | Upper Half | Nothing |  | Verified | collectible |  |
| Crafting Kit: Grindle | Upper Half | Nothing |  | Verified | collectible |  |
| Spool Fragment: Grindle (Blasted Steps) | Upper Half | Nothing |  | Verified | collectible |  |
| Pebb (Bone Bottom) / Grindle (Act 3) - Magnetite Brooch | Upper Half | Act 3 |  | Verified | collectible | IF NOT Acquired from Pebb |
| Pebb (Bone Bottom) / Grindle (Act 3) - Mask Shard | Upper Half | Act 3 |  | Verified | collectible | IF NOT Acquired from Pebb |
| Pebb (Bone Bottom) / Grindle (Act 3) - Craftmetal | Upper Half | Act 3 |  | Verified | collectible | IF NOT Acquired from Pebb |
| Pebb (Bone Bottom) / Grindle (Act 3) - Simple Key | Upper Half | Act 3 |  | Verified | collectible | IF NOT Acquired from Pebb |
| Mort (Pilgrim's Rest) / Grindle (Act 3) - Tool Pouch | Upper Half | Act 3 |  | Verified | collectible | IF NOT Acquired from Mort |
| Mort (Pilgrim's Rest) / Grindle (Act 3) - Memory Locket | Upper Half | Act 3 |  | Verified | collectible | IF NOT Acquired from Mort |
| Lumble (Blasted Steps) / Grindle (Act 3) - Magnetite Dice | Upper Half | Act 3 |  | Verified | collectible | IF NOT Acquired from Lumble |

### Blasted Steps Horizontal Room with Two Sand Pits (Coral_43)

**Game ID:** Coral_43

**Contributors:** skai

#### Subrooms

- Left of Sand Pits
- Right of Sand Pits
- Sand Pits

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right | Right of Sand Pits | [Blasted Steps Thin Long Vertical (Coral_35)](#blasted-steps-thin-long-vertical-coral35) | BL | Nothing |  | Verified |  |
| L | Left | Left of Sand Pits | [Lumble the Lucky (Coral_33)](#lumble-the-lucky-coral33) | R | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SPR | Sand Pit to Right | Sand Pits | Right of Sand Pits | Progressive Swift Step 1 OR Faydown OR Clawline OR Drifter's Cloak OR Sharpdart OR (Flea Brew AND (Easy Flea Brew Stall OR (Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo OR Easy Shaman Crest Pogo))) |  | Verified |  |
| SPR | Sand Pit to Right | Right of Sand Pits | Sand Pits | Progressive Swift Step 1 OR Faydown OR Clawline OR Drifter's Cloak OR Sharpdart OR (Flea Brew AND (Easy Flea Brew Stall OR (Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo OR Easy Shaman Crest Pogo))) |  | Verified |  |
| SPL | Sand Pit to Left | Left of Sand Pits | Sand Pits | Nothing |  | Verified |  |
| SPL | Sand Pit to Left | Sand Pits | Left of Sand Pits | Nothing |  | Verified |  |

#### Check Locations

No check locations defined.

### Blasted Steps Map Edge (Coral_19)

**Game ID:** Coral_19

**Contributors:** skai

#### Subrooms

- Lace Bridge
- Before Map Edge
- Map Edge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B1 | Bottom | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T1 | Nothing (Falling) |  | Verified |  |
| B2 | bot2 | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T2 | Nothing (Falling) |  | Verified |  |
| B3 | bot3 | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T3 | Nothing (Falling) |  | Verified |  |
| B4 | bot4 | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T4 | Nothing (Falling) |  | Verified |  |
| B5 | bot5 | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T5 | Nothing (Falling) |  | Verified |  |
| B6 | bot6 | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T6 | Nothing (Falling) |  | Verified |  |
| B7 | bot7 | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T7 | Nothing (Falling) |  | Verified |  |
| R | Right | Lace Bridge | [Shellwood Connection To Blasted steps (Shellwood_08)](#shellwood-connection-to-blasted-steps-shellwood08) | L | Nothing |  | Verified |  |
| TR3 | Top Right (3) | Lace Bridge | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | B3 | Silk Soar |  | Verified |  |
| TR4 | Top Right (4) | Lace Bridge | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | B4 | Silk Soar |  | Verified |  |
| TR5 | Top Right (5) | Lace Bridge | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | B5 | Silk Soar |  | Verified |  |
| TR6 | Top Right (6) | Lace Bridge | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | B6 | Silk Soar |  | Verified |  |
| TR7 | Top Right (7) | Lace Bridge | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | B7 | Silk Soar |  | Verified |  |
| TR8 | Top Right (8) | Lace Bridge | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | B8 | Silk Soar |  | Verified |  |
| TM | Top Middle | Before Map Edge | [Blasted Steps Toll Bench Bottom (Coral_02)](#blasted-steps-toll-bench-bottom-coral02) | BR | (Cling Grip AND (Spike Pogo OR Progressive Swift Step 1 OR Faydown OR Spike Pogo OR Drifter's Cloak OR Flea Brew OR Proficient Movement OR Sharpdart OR Clawline OR Easy Needle Strike Stall OR Easy Heal Stall)) OR Scuttlebrace |  | Verified |  |
| TL | Top Left | Map Edge | [Blasted Steps Mask Shard (Coral_19b)](#blasted-steps-mask-shard-coral19b) | B | Silk Soar OR (Progressive Swift Step 1 AND Faydown AND Clawline AND Ledge Grab AND (Cling Grip OR Scuttlebrace)) |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MEB | Map Edge to Before | Map Edge | Before Map Edge | Nothing |  | Verified |  |
| MEB | Map Edge to Before | Before Map Edge | Map Edge | Nothing |  | Verified |  |
| BLB | Before to Lace Bridge | Before Map Edge | Lace Bridge | Nothing |  | Verified |  |
| BLB | Before to Lace Bridge | Lace Bridge | Before Map Edge | Nothing |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Blasted Steps - Shellwood Entrance Sign | Before Map Edge | Cling Grip OR Easy Scuttlebrace OR Silk Soar |  | Verified | lore |  |

### Blasted Steps Mask Shard (Coral_19b)

**Game ID:** Coral_19b

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | Bottom |  | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TL | Nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mask Shard: Blasted Steps |  | (Scuttlebrace AND Faydown) OR ( Proficient Movement AND Cling Grip AND Spike Pogo AND (Ledge Grab OR Easy Hazard Respawn)) |  | Verified | collectible |  |

### Blasted Steps Shakra Room (Coral_12)

**Game ID:** Coral_12

**Contributors:** skai

#### Subrooms

- Bottom Third (Left)
- Bottom Third (Right)
- Middle Third (Bottom)
- Middle Third (Top)
- Middle Third (Entrance)
- Top Third
- Top Third (Entrance)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bottom Left | Bottom Third (Left) | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | BR | Nothing |  | Verified |  |
| R | Right | Middle Third (Entrance) | [Blasted Steps Steel Soul (Coral_37)](#blasted-steps-steel-soul-coral37) | L | Nothing |  | Verified |  |
| TL | Top Left | Top Third (Entrance) | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | MR | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLR | Bottom Third Left to Right | Bottom Third (Left) | Bottom Third (Right) | Progressive Swift Step 1 OR Faydown OR Clawline OR Flea Brew OR Sharpdart OR Easy Beast Crest Pogo |  | Verified |  |
| BLR | Bottom Third Left to Right | Bottom Third (Right) | Bottom Third (Left) | Progressive Swift Step 1 OR Faydown OR Clawline OR Flea Brew OR Sharpdart OR Easy Beast Crest Pogo |  | Verified |  |
| BMB | Bottom to Middle Bottom | Bottom Third (Right) | Middle Third (Bottom) | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| BMB | Bottom to Middle Bottom | Middle Third (Bottom) | Bottom Third (Right) | Nothing (Falling) |  | Verified |  |
| MBT | Middle Bottom to Middle Top | Middle Third (Bottom) | Middle Third (Top) | ((Progressive Swift Step 2 OR Faydown OR Clawline  OR Sharpdart) AND Cling Grip) OR ((Hard Scuttlebrace AND Ledge Grab) OR (Medium Scuttlebrace AND (Flea Brew OR Faydown OR Clawline) AND Ledge Grab)) OR Silk Soar |  | Verified |  |
| MBT | Middle Bottom to Middle Top | Middle Third (Top) | Middle Third (Bottom) | Nothing (Falling) |  | Verified |  |
| MTE | Middle Top to Middle Entrance | Middle Third (Top) | Middle Third (Entrance) | Clawline OR Faydown OR Scuttlebrace OR Cling Grip OR Silk Soar OR Sharpdart OR ((Drifter's OR (Progressive Swift Step 2 AND Flea Brew) OR (Flea Brew AND Medium Flea Brew Stall)) AND Ledge Grab) |  | Verified |  |
| MTE | Middle Top to Middle Entrance | Middle Third (Entrance) | Middle Third (Top) | Progressive Swift Step 2 OR Faydown OR Clawline OR  Sharpdart OR (Flea Brew AND Easy Flea Brew Stall) |  | Verified |  |
| MET | Middle Entrance to Top | Middle Third (Entrance) | Top Third | Cling Grip OR Silk Soar OR (Scuttlebrace AND Spike Pogo) OR (Faydown AND Easy Enemy Pogo) |  | Verified |  |
| MET | Middle Entrance to Top | Top Third | Middle Third (Entrance) | Nothing (Falling) |  | Verified |  |
| TTE | Top to Top Entrance | Top Third | Top Third (Entrance) | Nothing |  | Verified |  |
| TTE | Top to Top Entrance | Top Third (Entrance) | Top Third | Progressive Swift Step 2 OR Faydown OR Clawline OR Sharpdart OR Flea Brew |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map Purchase: Blasted Steps | Bottom Third (Right) | (Progressive Swift Step 1 OR Faydown OR Clawline OR Flea Brew OR Sharpdart OR Easy Beast Crest Pogo) AND Act 1 |  | Verified | collectible | This can be purchased at Bellhart if Shakra has moved. |

### Blasted Steps Shell / Beast Shard (Coral_36)

**Game ID:** Coral_36

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Blasted Steps Thin Long Vertical (Coral_35)](#blasted-steps-thin-long-vertical-coral35) | MR | Nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Beast Shard: Blasted Steps |  | (Scuttlebrace AND Faydown) OR Cling Grip OR Silk Soar |  | Verified | collectible |  |
| Shell Shard Cache: Blasted Steps #4 |  | (Scuttlebrace AND Faydown) OR Cling Grip OR Silk Soar |  | Verified | collectible |  |
| Shell Shard Cache: Blasted Steps #5 |  | (Scuttlebrace AND Faydown) OR Cling Grip OR Silk Soar |  | Verified | collectible |  |
| Blasted Steps - Judge Nursery Record |  | Nothing |  | Verified | lore |  |

### Blasted Steps Steel Soul (Coral_37)

**Game ID:** Coral_37

**Contributors:** skai

#### Subrooms

- Silkeater Area
- Steel Soul Area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | Silkeater Area | [Blasted Steps Shakra Room (Coral_12)](#blasted-steps-shakra-room-coral12) | R | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SS | Steel Soul Passage | Silkeater Area | Steel Soul Area | Steel Soul On AND break wall right |  | Verified |  |
| SS | Steel Soul Passage | Steel Soul Area | Silkeater Area | Steel Soul On AND break wall left |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silkeater: Blasted Steps | Silkeater Area | Nothing |  | Verified | collectible |  |
| A Vassal Lost Wish Promised | Steel Soul Area | Steel Soul On AND Maps 1 |  | Verified | event | must have a map requirement per the wiki |
| A Vassal Lost Wish Granted | Steel Soul Area | defeat THE Summoned Savior Boss Fight |  | Verified | event |  |
| Growstone | Steel Soul Area | complete A Vassal Lost Wish Granted |  | Verified | collectible |  |

### Blasted Steps Thin Long Vertical (Coral_35)

**Game ID:** Coral_35

**Contributors:** skai

#### Subrooms

- Bottom Third (Lower Half)
- Bottom Third (Upper Half)
- Middle Third (Lower Half)
- Middle Third (Upper Half)
- Top Third (Lower Half)
- Top Third (Upper Half)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bottom Left | Bottom Third (Lower Half) | [Blasted Steps Horizontal Room with Two Sand Pits (Coral_43)](#blasted-steps-horizontal-room-with-two-sand-pits-coral43) | R | Nothing |  | Verified |  |
| R | Right | Bottom Third (Upper Half) | [Blasted Steps Bellway (Bellway_08)](#blasted-steps-bellway-bellway08) | L | Nothing |  | Verified |  |
| ML | Middle Left | Middle Third (Lower Half) | [Blasted Steps Grindle (Coral_42)](#blasted-steps-grindle-coral42) | R | Nothing |  | Verified |  |
| MR | Middle Right | Middle Third (Upper Half) | [Blasted Steps Shell / Beast Shard (Coral_36)](#blasted-steps-shell-beast-shard-coral36) | L | Break Wall Right OR Break Wall Left |  | Verified |  |
| T | Top | Top Third (Upper Half) | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | F | Prereq Stalactite IN Sands of Karak Tall Centre Room |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLU | Bottom Lower to Upper | Bottom Third (Lower Half) | Bottom Third (Upper Half) | Cling Grip OR Medium Scuttlebrace OR Faydown OR (Silk Soar AND Ledge Grab) |  | Verified |  |
| BLU | Bottom Lower to Upper | Bottom Third (Upper Half) | Bottom Third (Lower Half) | Nothing (Falling) |  | Verified |  |
| BML | Bottom to Middle Lower | Bottom Third (Upper Half) | Middle Third (Lower Half) | Cling Grip OR (Scuttlebrace AND (Clawline OR Faydown OR Easy Flea Brew Stall OR Sharpdart)) OR (Silk Soar AND (Ledge Grab OR Progressive Swift Step 2 OR Faydown OR Clawline OR Flea Brew OR Sharpdart)) |  | Verified |  |
| BML | Bottom to Middle Lower | Middle Third (Lower Half) | Bottom Third (Upper Half) | Nothing (Falling) |  | Verified |  |
| MLU | Middle Lower to Upper | Middle Third (Lower Half) | Middle Third (Upper Half) | Cling Grip OR (Easy Scuttlebrace AND (Faydown OR Easy Flea Brew Stall OR Medium Heal Stall)) OR Silk Soar |  | Verified |  |
| MLU | Middle Lower to Upper | Middle Third (Upper Half) | Middle Third (Lower Half) | Nothing (Falling) |  | Verified |  |
| MTL | Middle to Top Lower | Middle Third (Upper Half) | Top Third (Lower Half) | Spike Pogo AND (Cling Grip OR Easy Scuttlebrace) |  | Verified |  |
| MTL | Middle to Top Lower | Top Third (Lower Half) | Middle Third (Upper Half) | Nothing (Falling) |  | Verified |  |
| TLU | Top Lower to Upper | Top Third (Lower Half) | Top Third (Upper Half) | Nothing (Jump) |  | Verified |  |
| TLU | Top Lower to Upper | Top Third (Upper Half) | Top Third (Lower Half) | Nothing (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Blasted Steps | Top Third (Upper Half) | Nothing |  | Verified | collectible |  |

### Blasted Steps Toll Bench Bottom (Coral_02)

**Game ID:** Coral_02

**Contributors:** skai

#### Subrooms

- Bottom Right
- Middle
- Bottom Left
- Top Left
- Top Right
- Top Right Pit (Right)
- Top Right Pit (Left)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BR | Bottom Right | Bottom Right | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TM | Nothing |  | Verified |  |
| TR | Top Right | Top Right | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | BL | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BRM | Bottom Right to Middle | Bottom Right | Middle | (Cling Grip AND (Progressive Swift Step 1 OR Sharpdart OR Clawline OR Flea Brew)) OR Faydown OR Easy Scuttlebrace OR Silk Soar |  | Verified |  |
| BRM | Bottom Right to Middle | Middle | Bottom Right | Nothing (Falling) |  | Verified |  |
| BLM | Bottom Left to Middle | Bottom Left | Middle | (Cling Grip AND (Progressive Swift Step 1 OR Sharpdart OR Clawline OR Flea Brew)) OR Faydown OR Medium Scuttlebrace OR Silk Soar |  | Verified |  |
| BLM | Bottom Left to Middle | Middle | Bottom Left | Nothing (Falling) |  | Verified |  |
| MTL | Middle to Top Left | Middle | Top Left | (Cling Grip AND (Progressive Swift Step 1 OR Sharpdart OR Clawline OR Flea Brew)) OR Faydown OR Easy Scuttlebrace OR Silk Soar |  | Verified |  |
| MTL | Middle to Top Left | Top Left | Middle | Nothing (Fall) |  | Verified |  |
| TLR | Top Left to Top Right | Top Left | Top Right | (Cling Grip AND (Progressive Swift Step 2 OR Sharpdart OR Clawline OR (Flea Brew AND (Easy Flea Brew Stall OR Easy Heal Stall OR Ledge Grab)))) OR (Faydown AND Ledge Grab) OR Easy Scuttlebrace OR Silk Soar |  | Verified |  |
| TLR | Top Left to Top Right | Top Right | Top Left | Progressive Swift Step 2 OR Sharpdart OR Clawline OR Faydown OR (Flea Brew AND (Easy Flea Brew Stall OR Easy Heal Stall OR Ledge Grab)) |  | Verified |  |
| PLT | Pit Left to Top Right | Top Right Pit (Left) | Top Right | Cling Grip OR Scuttlebrace OR Silk Soar OR (Faydown AND Ledge Grab AND (Easy Heal Stall OR Easy Flea Brew Stall)) |  | Verified |  |
| PLT | Pit Left to Top Right | Top Right | Top Right Pit (Left) | Nothing (Falling) |  | Verified |  |
| PRT | Pit Right to Top RIght | Top Right Pit (Right) | Top Right | Cling Grip OR Scuttlebrace OR (Faydown AND Ledge Grab) |  | Verified |  |
| PRT | Pit Right to Top RIght | Top Right | Top Right Pit (Right) | Nothing (Falling) |  | Verified |  |
| BRP | Bottom Right to Pit | Top Right Pit (Left) | Bottom Right | Nothing (Falling) |  | Verified |  |
| BRP | Bottom Right to Pit | Bottom Right | Top Right Pit (Left) | (Prereq Top Right Pit Lever (Top Right Pit) OR (Faydown AND Ledge Grab)) AND Silk Soar |  | Verified |  |
| LPM | Left Pit to Middle | Top Right Pit (Left) | Middle | Prereq Top Right Pit Lever OR (Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo) OR Clawline OR Flea Brew OR Sharpdart OR Progressive Swift Step 2 OR Faydown |  | Verified | Didn't Split Sprint/Dash |
| LPM | Left Pit to Middle | Middle | Top Right Pit (Left) | (Prereq Top Right Pit Lever AND (Ledge Grab OR Faydown)) OR Silk Soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket: Blasted Steps | Top Right Pit (Right) | Nothing (Fall) |  | Verified | collectible |  |
| Shell Shard Cache: Blasted Steps #1 | Bottom Left | Nothing (Fall) |  | Verified | collectible |  |
| Shell Shard Cache: Blasted Steps #2 | Bottom Left | Nothing (Fall) |  | Verified | collectible |  |
| Shell Shard Cache: Blasted Steps #3 | Bottom Left | Nothing (Fall) |  | Verified | collectible |  |
| Top Right Pit Lever | Top Right Pit (Left) | Nothing |  | Verified | switch |  |

### Blasted Steps Wide Long Vertical (Coral_03)

**Game ID:** Coral_03

**Contributors:** skai

#### Subrooms

- Pit
- Bottom Third (Left)
- Bottom Third (Right)
- Middle Left (Entrance)
- Middle Right (Entrance)
- Middle Section 1
- Middle Section 2
- Top Third Entrances
- Top Third

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bottom Left | Bottom Third (Left) | [Blasted Steps Toll Bench Bottom (Coral_02)](#blasted-steps-toll-bench-bottom-coral02) | TR | Nothing |  | Verified |  |
| B3 | Bottom (3) | Pit | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TR3 | Nothing |  | Verified |  |
| B4 | Bottom (4) | Pit | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TR4 | Nothing |  | Verified |  |
| B5 | Bottom (5) | Pit | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TR5 | Nothing |  | Verified |  |
| B6 | Bottom (6) | Pit | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TR6 | Nothing |  | Verified |  |
| B7 | Bottom (7) | Pit | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TR7 | Nothing |  | Verified |  |
| B8 | Bottom (8) | Pit | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TR8 | Nothing |  | Verified |  |
| BR | Bottom Right | Bottom Third (Right) | [Blasted Steps Shakra Room (Coral_12)](#blasted-steps-shakra-room-coral12) | BL | Nothing |  | Verified |  |
| ML | Middle Left | Middle Left (Entrance) | [Great Conchflies (Coral_11)](#great-conchflies-coral11) | R | Nothing |  | Verified |  |
| MR | Middle Right | Middle Right (Entrance) | [Blasted Steps Shakra Room (Coral_12)](#blasted-steps-shakra-room-coral12) | TL | Nothing |  | Verified |  |
| TR | Top Right | Top Third Entrances | [Pre Last Judge Room (Coral_32)](#pre-last-judge-room-coral32) | L | Nothing |  | Verified |  |
| TL | Top Left | Top Third Entrances | [Blasted Steps Bellway (Bellway_08)](#blasted-steps-bellway-bellway08) | R | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLR | Bottom Left to Right | Bottom Third (Left) | Bottom Third (Right) | Progressive Swift Step 1 OR Faydown OR Easy Enemy Pogo OR Silk Soar OR Clawline OR (Flea Brew AND ((Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo) OR Easy Flea Brew Stall OR Ledge Grab)) |  | Verified |  |
| BLR | Bottom Left to Right | Bottom Third (Right) | Bottom Third (Left) | Progressive Swift Step 1 OR Faydown OR Easy Enemy Pogo OR Silk Soar OR Clawline OR (Flea Brew AND ((Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo) OR Easy Flea Brew Stall OR Ledge Grab)) |  | Verified |  |
| BLM | Bottom Left to Middle 1 | Bottom Third (Left) | Middle Section 1 | (Easy Enemy Pogo AND Faydown AND Ledge Grab) OR ((Progressive Swift Step 2 OR Faydown OR Clawline OR Drifter's Cloak OR Easy Enemy Pogo OR (Flea Brew AND (((Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo)) OR Easy Flea Brew Stall))) AND Cling Grip) OR (Progressive Swift Step 2 AND Scuttlebrace AND Faydown) OR Silk Soar |  | Verified |  |
| BLM | Bottom Left to Middle 1 | Middle Section 1 | Bottom Third (Left) | Nothing (Falling) |  | Verified |  |
| BRM | Bottom Right to Middle | Bottom Third (Right) | Middle Section 1 | (Easy Enemy Pogo AND Faydown AND Ledge Grab) OR ((Progressive Swift Step 2 OR Faydown OR Clawline OR Drifter's Cloak OR Easy Enemy Pogo OR (Flea Brew AND (((Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo)) OR Easy Flea Brew Stall))) AND Cling Grip) OR (Progressive Swift Step 2 AND Scuttlebrace AND Faydown) OR Silk Soar |  | Verified |  |
| BRM | Bottom Right to Middle | Middle Section 1 | Bottom Third (Right) | Nothing (Falling) |  | Verified |  |
| M12 | Middle 1 to Middle 2 | Middle Section 1 | Middle Section 2 | Nothing (Jumping) |  | Verified |  |
| M12 | Middle 1 to Middle 2 | Middle Section 2 | Middle Section 1 | Nothing (Falling) |  | Verified |  |
| MLE | Middle to Middle Left | Middle Section 2 | Middle Left (Entrance) | Easy Enemy Pogo OR Silk Soar OR Progressive Swift Step 2 OR Clawline OR Sharpdart OR (Drifter's Cloak AND Ledge Grab) OR (Flea Brew AND (Cling Grip OR Easy Flea Brew Stall OR Easy Heal Stall)) |  | Verified |  |
| MLE | Middle to Middle Left | Middle Left (Entrance) | Middle Section 2 | Easy Enemy Pogo OR Progressive Swift Step 2 OR Clawline OR Sharpdart OR Drifter's Cloak OR Faydown OR Flea Brew OR Silk Soar OR ((Easy Hunter Pogo OR Easy Reaper Pogo OR Easy Beast Pogo OR Easy Architect Pogo OR Easy Shaman Pogo) AND Cling Grip) |  | Verified |  |
| MRE | Middle to Middle Right | Middle Section 2 | Middle Right (Entrance) | (Proficient Movement AND Drifter's Cloak AND Progressive Swift Step 2) OR (Proficient Movement AND Progressive Swift Step 2 AND Clawline AND Cling Grip AND Ledge Grab) OR (Faydown AND ((Progressive Swift Step 2 AND Ledge Grab) OR (Drifter's Cloak AND Medium Wind Skip AND Ledge Grab) OR Clawline)) OR Silk Soar |  | Verified |  |
| MRE | Middle to Middle Right | Middle Right (Entrance) | Middle Section 2 | Nothing (Falling) |  | Verified |  |
| PTB | Pit to Bottom | Pit | Bottom Third (Left) | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| PTB | Pit to Bottom | Bottom Third (Left) | Pit | Nothing (Falling) |  | Verified |  |
| MRT | Middle Right to Top | Middle Right (Entrance) | Top Third | Ledge Grab OR Cling Grip OR Faydown OR Silk Soar OR Scuttlebrace |  | Verified |  |
| MRT | Middle Right to Top | Top Third | Middle Right (Entrance) | Nothing (Falling) |  | Verified |  |
| TTE | Top Third to Entrances | Top Third | Top Third Entrances | (Ledge Grab AND (Cling Grip OR (Scuttlebrace AND Proficient Movement)) AND ((Prereq Top Third Lever AND Flea Brew) OR Progressive Swift Step 2 OR Clawline)) OR Silk Soar |  | Verified |  |
| TTE | Top Third to Entrances | Top Third Entrances | Top Third | Nothing (Falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Frayed Rosary String: Blasted Steps | Pit | Nothing (Falling) |  | Verified | collectible |  |
| Top Third Lever | Top Third | (Ledge Grab AND (Cling Grip OR Scuttlebrace)) OR Faydown OR Silk Soar |  | Verified | switch |  |

### Great Conchflies (Coral_11)

**Game ID:** Coral_11

**Contributors:** skai

#### Subrooms

- Great Conchflies
- Triple Sand Pit Right
- Triple Sand Pit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right | Triple Sand Pit Right | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | ML | Nothing |  | Verified |  |
| L | Left | Great Conchflies | [Horizontal Room with Sand Pit (Coral_11b)](#horizontal-room-with-sand-pit-coral11b) | R | defeat Boss: Great Conchflies |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TSC | Triple Sand Pit to Conch | Triple Sand Pit | Great Conchflies | Progressive Swift Step 1 OR Faydown OR Clawline OR Sharpdart OR ((Drifter's Cloak OR Medium Beast Crest Pogo OR (Flea Brew AND Easy Flea Brew Stall)) AND Ledge Grab) |  | Verified |  |
| TSC | Triple Sand Pit to Conch | Great Conchflies | Triple Sand Pit | Progressive Swift Step 1 OR Faydown OR Clawline OR Sharpdart OR ((Drifter's Cloak OR Medium Beast Crest Pogo OR (Flea Brew AND Easy Flea Brew Stall)) AND Ledge Grab) |  | Verified |  |
| TSR | Triple Sand Pit to Right | Triple Sand Pit | Triple Sand Pit Right | Progressive Swift Step 1 OR Faydown OR Clawline OR Sharpdart OR ((Drifter's Cloak OR Medium Beast Crest Pogo OR (Flea Brew AND Easy Flea Brew Stall)) AND Ledge Grab) |  | Verified |  |
| TSR | Triple Sand Pit to Right | Triple Sand Pit Right | Triple Sand Pit | Progressive Swift Step 1 OR Faydown OR Clawline OR Sharpdart OR ((Drifter's Cloak OR Medium Beast Crest Pogo OR (Flea Brew AND Easy Flea Brew Stall)) AND Ledge Grab) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Great Conchflies | Great Conchflies | Nothing |  | Verified | boss |  |

### Horizontal Room with Sand Pit (Coral_11b)

**Game ID:** Coral_11b

**Contributors:** skai

#### Subrooms

- Sand Pit Left
- Sand Pit Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right | Sand Pit Right | [Great Conchflies (Coral_11)](#great-conchflies-coral11) | L | Nothing |  | Verified |  |
| L | Left | Sand Pit Left | [Windy Pinstress Entrance (Coral_34)](#windy-pinstress-entrance-coral34) | R | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SP | Sand Pit | Sand Pit Left | Sand Pit Right | Progressive Swift Step 1 OR Faydown OR Clawline OR Drifter's Cloak OR Easy Beast Crest Pogo OR Sharpdart OR (Flea Brew AND (Easy Flea Brew Stall OR Easy Heal Stall OR Ledge Grab)) |  | Verified | Didn't Split Sprint/Dash |
| SP | Sand Pit | Sand Pit Right | Sand Pit Left | Progressive Swift Step 1 OR Faydown OR Clawline OR Drifter's Cloak OR Easy Beast Crest Pogo OR Sharpdart OR (Flea Brew AND (Easy Flea Brew Stall OR Easy Heal Stall OR Ledge Grab)) |  | Verified | Didn't Split Sprint/Dash |

#### Check Locations

No check locations defined.

### Last Judge Arena (Coral_Judge_Arena)

**Game ID:** Coral_Judge_Arena

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Pre Last Judge Room (Coral_32)](#pre-last-judge-room-coral32) | R | Nothing |  | Verified |  |
| R | Right |  | [Grand Bridge (Coral_10)](#grand-bridge-coral10) | L | defeat Boss: Last Judge |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Last Judge |  | prereq Five Bellshrines Rung AND (Progressive Swift Step 2 OR Faydown) |  | Verified | boss | Combat Requirements |
| Five Bellshrines Rung |  | activated bellshrines 5 |  | Verified | event |  |
| flea caravan move to fleatopia |  | after THE flea caravan move to blasted steps AND fleas 22 AND after THE reached pale lake |  | Verified | event |  |

### Lumble the Lucky (Coral_33)

**Game ID:** Coral_33

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right |  | [Blasted Steps Horizontal Room with Two Sand Pits (Coral_43)](#blasted-steps-horizontal-room-with-two-sand-pits-coral43) | L | Nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Magnetite Dice |  | ( Complete Bankrupt Lumble OR Prereq Clawline Pickup IN Underworks Clawline Room OR Prereq THE cogwork dancers boss fight ) AND ( Act 1 OR Act 2 ) |  | Verified | collectible |  |
| Bankrupt Lumble |  | None |  | Verified | event |  |
| Lost Garmond Boss Fight |  | complete THE Hero's Call Wish Promised |  | Verified | boss |  |
| Hero's Call Wish Granted |  | defeat Lost Garmond Boss Fight |  | Verified | event |  |
| Hero's Memento |  | defeat Lost Garmond Boss Fight |  | Verified | collectible |  |

### Windy Pinstress Room (Room_Pinstress)

**Game ID:** Room_Pinstress

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Windy Pinstress Entrance (Coral_34)](#windy-pinstress-entrance-coral34) | C | Nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Needle Strike |  | Nothing |  | Verified | collectible |  |
| Read Pinstress Note |  | act 3 AND have needle strike AND have silk soar |  | Verified | logic-point | technically lore, but not really |
| Fatal Resolve Wish Promised |  | after Read Pinstress Note |  | Verified | event | can be accepted at the wish wall, but hornet has to read the note first anyway, so functionally it doesn't matter |

### Pre Last Judge Room (Coral_32)

**Game ID:** Coral_32

**Contributors:** skai

#### Subrooms

- Ascension
- Intermission
- Descent
- Top (Entrance)
- Right (Entrance)
- Top Vertical Shaft
- Top Right
- Left (Entrance)
- Top (Blocked Side)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | Left (Entrance) | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | TR | Nothing |  | Verified |  |
| T | Top | Top (Entrance) | [Sands of Karak Elevator to Blasted Steps (Coral_38)](#sands-of-karak-elevator-to-blasted-steps-coral38) | F | Nothing |  | Verified | Have to come from Coral_38 side |
| R | Right | Right (Entrance) | [Last Judge Arena (Coral_Judge_Arena)](#last-judge-arena-coraljudgearena) | L | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LTA | Left to Ascension | Left (Entrance) | Ascension | Progressive Swift Step 1 OR Faydown OR Clawline OR Drifter's Cloak OR Silk Soar OR Flea Brew |  | Verified |  |
| LTA | Left to Ascension | Ascension | Left (Entrance) | ((Progressive Swift Step 1 OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  | Verified |  |
| ATI | Ascension to Intermission | Ascension | Intermission | ((Progressive Swift Step 2 OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  | Verified |  |
| ATI | Ascension to Intermission | Intermission | Ascension | Nothing (Fall) |  | Verified |  |
| ITR | Intermission to Top Right | Intermission | Top Right | Nothing (Fall) |  | Verified |  |
| ITR | Intermission to Top Right | Top Right | Intermission | Ledge Grab |  | Verified |  |
| TRD | Top Right to Descent | Top Right | Descent | Nothing (Fall) |  | Verified |  |
| TRD | Top Right to Descent | Descent | Top Right | ((Progressive Swift Step 2 OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND (Ledge Grab OR Easy Hazard Respawn)))) AND Cling Grip |  | Verified |  |
| TRV | Top Right to Top Vertical | Top Right | Top Vertical Shaft | ((Progressive Swift Step 2 OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  | Verified |  |
| TRV | Top Right to Top Vertical | Top Vertical Shaft | Top Right | Nothing (Fall) |  | Verified |  |
| VTE | Top Vertical to Top (Entrance) | Top Vertical Shaft | Top (Blocked Side) | Cling Grip OR Silk Soar |  | Verified |  |
| VTE | Top Vertical to Top (Entrance) | Top (Blocked Side) | Top Vertical Shaft | Nothing (Fall) |  | Verified |  |
| TRE | Top Right to Right (Entrance) | Top Right | Right (Entrance) | ((Progressive Swift Step 2 OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  | Verified |  |
| TRE | Top Right to Right (Entrance) | Right (Entrance) | Top Right | Nothing (Fall) |  | Verified |  |
| TBE | Top Blocked to Entrance | Top (Blocked Side) | Top (Entrance) | Clear Spiky Blockade |  | Verified |  |
| TBE | Top Blocked to Entrance | Top (Entrance) | Top (Blocked Side) | Clear Spiky Blockade |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Craftmetal: Blasted Steps | Descent | Faydown OR Clawline OR Drifter's Cloak OR Sharpdart OR Medium Shaman Pogo OR (Progressive Swift Step 1 AND Ledge Grab) |  | Verified | collectible |  |
| Spiky Blockade | Top (Entrance) | Break Wall Left |  | Verified | blockade |  |

### Windy Pinstress Entrance (Coral_34)

**Game ID:** Coral_34

**Contributors:** skai

#### Subrooms

- Lower Third
- Middle Third
- Upper Third

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right | Lower Third | [Horizontal Room with Sand Pit (Coral_11b)](#horizontal-room-with-sand-pit-coral11b) | L | Nothing |  | Verified |  |
| C | Center | Middle Third | [Windy Pinstress Room (Room_Pinstress)](#windy-pinstress-room-roompinstress) | L | Nothing (Falling) |  | Verified |  |
| T | Top | Upper Third | [Sands of Karak Entrance (Coral_25)](#sands-of-karak-entrance-coral25) | F | Cling Grip OR (Scuttlebrace AND Faydown) OR Silk Soar |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LTC | Lower to Center | Lower Third | Middle Third | Clawline OR (Silk Soar AND Progressive Swift Step 2) OR (Flea Brew AND (Faydown OR (Progressive Swift Step 2 AND Ledge Grab) OR (Easy Beast Crest Pogo AND Ledge Grab))) |  | Verified |  |
| LTC | Lower to Center | Middle Third | Lower Third | Nothing (Falling) |  | Verified |  |
| CTT | Center to Top | Middle Third | Upper Third | (Clawline AND (Cling Grip OR Scuttlebrace)) OR (Clawline AND Cling Grip AND (Faydown OR (Easy Beast Crest Pogo AND Ledge Grab))) |  | Verified |  |
| CTT | Center to Top | Upper Third | Middle Third | Nothing (Falling) |  | Verified |  |

#### Check Locations

No check locations defined.

## Grand Gate

### Grand Bridge (Coral_10)

**Game ID:** Coral_10

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Last Judge Arena (Coral_Judge_Arena)](#last-judge-arena-coraljudgearena) | R | prereq Boss: Last Judge IN Last Judge Arena |  | Verified |  |
| R | Right |  | [Grand Gate Courtroom (Song_19_entrance)](#grand-gate-courtroom-song19entrance) | L | activate Grand Bridge Plate |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Grand Bridge Plate |  | Nothing |  | Verified | switch |  |

### Grand Gate Maintenance Room (Song_01c)

**Game ID:** Song_01c

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Grand Gate Courtroom (Song_19_entrance)](#grand-gate-courtroom-song19entrance) | TR | none |  | Verified | falling is enough |
| T | top1 |  | [Choral Chambers Below Ventrica (Song_01)](#choral-chambers-below-ventrica-song01) | B | cling grip |  | Verified | no silk soar |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Grand Gate Courtroom (Song_19_entrance)

**Game ID:** Song_19_entrance

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Grand Bridge (Coral_10)](#grand-bridge-coral10) | R | Prereq Boss: Last Judge IN Last Judge Arena |  | Verified | blocked |
| TR | right1 |  | [Grand Gate Maintenance Room (Song_01c)](#grand-gate-maintenance-room-song01c) | L | faydown cloak OR silk soar |  | Verified |  |
| R | right2 |  | [Grand Elevator (Under_01)](#grand-elevator-under01) | TL | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Spool Fragment: Grand Gate |  | (faydown cloak AND cling grip) OR silk soar |  | Verified | collectible |  |
| Map Purchase: Grand Gate |  | None |  | Verified | collectible |  |

### Grand Elevator (Under_01)

**Game ID:** Under_01

**Contributors:** samupo

#### Subrooms

- Top
- Crash Site

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | left1 | Top | [Grand Gate Courtroom (Song_19_entrance)](#grand-gate-courtroom-song19entrance) | R | none |  | Verified |  |
| SLB | left3 | Crash Site | [Entrance to Nyleth (Under_27)](#entrance-to-nyleth-under27) | LR | prereq Vined Up door IN Entrance to Nyleth |  | Verified |  |
| SLT | left2 | Crash Site | [Entrance to Nyleth (Under_27)](#entrance-to-nyleth-under27) | UR | silk soar AND cling grip |  | Verified | Either come back from Top for a second time or get access from the crash site. To check if the breakable wall exists both sides |
| R | right1 | Crash Site | [Broken Elevator (Under_01b)](#broken-elevator-under01b) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| F | Falling | Top | Crash Site | none |  | Verified | Just once |

#### Check Locations

No check locations defined.

### Entrance to Nyleth (Under_27)

**Game ID:** Under_27

**Contributors:** Pyxl

#### Subrooms

- Entrance
- Shell Shard Ledge
- Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Exit | [Shrine Guardian Seth (Shellwood_22)](#shrine-guardian-seth-shellwood22) | R | None |  | Verified |  |
| UR | right1 | Entrance | [Grand Elevator (Under_01)](#grand-elevator-under01) | SLT | Silk Soar OR ( Faydown Cloak AND Cling Grip ) |  | Verified |  |
| LR | right2 | Entrance | [Grand Elevator (Under_01)](#grand-elevator-under01) | SLB | Prereq Vined Up door |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Entrance | Exit | prereq Breakable Chain - Entrance AND ( prereq Breakable Vines - Exit Hall OR ( Faydown Cloak AND ( Clawline OR Drifters Cloak ) AND ( Cling Grip OR Ledge grab OR Silk Soar OR Scuttlebrace ) ) ) |  | Verified |  |
| WR | Whole Room | Exit | Entrance | ( prereq Breakable Vines - Exit Hall AND Faydown Cloak AND ( Cling Grip OR Ledge Grab OR Dash ) ) |  | Verified |  |
| DE | Detour | Exit | Shell Shard Ledge | ( Faydown Cloak AND Cling Grip AND ( Clawline OR Dash OR Drifters Cloak ) ) |  | Verified |  |
| DE | Detour | Shell Shard Ledge | Exit | ( Faydown Cloak AND ( Cling Grip OR Ledge Grab OR Silk Soar ) AND ( Clawline OR Dash OR Drifters Cloak ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Grand Gate - Shell Shard Cache | Shell Shard Ledge | None |  | Verified | resource |  |
| Breakable Vines - Exit Hall | Exit | None |  | Verified | blockade |  |
| Breakable Chain - Entrance | Entrance | Silk Soar OR ( Faydown Cloak OR Cling Grip ) |  | Verified | blockade |  |
| Vined Up door | Entrance | None |  | Verified | blockade |  |

### Shrine Guardian Seth (Shellwood_22)

**Game ID:** Shellwood_22

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 |  | [Nyleth Shrine (Shellwood_11b)](#nyleth-shrine-shellwood11b) | R | Prereq Boss: Shrine Guardian Seth |  | Verified |  |
| R | right1 |  | [Entrance to Nyleth (Under_27)](#entrance-to-nyleth-under27) | L | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Shrine Guardian Seth |  | Needle Upgrades 2 |  | Verified | boss |  |

### Nyleth Shrine (Shellwood_11b)

**Game ID:** Shellwood_11b

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Shrine Guardian Seth (Shellwood_22)](#shrine-guardian-seth-shellwood22) | D | None |  | Verified |  |
| D | door_wakeOnGround |  | [Nyleth Fight (Shellwood_11b_Memory)](#nyleth-fight-shellwood11bmemory) | D | Needolin AND Have Elegy of the deep |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lore |  | None |  | Verified | lore | Not included on the map |

### Nyleth Fight (Shellwood_11b_Memory)

**Game ID:** Shellwood_11b_Memory

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door_wakeInMemory |  | [Nyleth Shrine (Shellwood_11b)](#nyleth-shrine-shellwood11b) | D | Prereq Boss: Nyleth |  | Verified | This is just an entrance transition if you wanna go back gotta die |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Nyleth |  | needle upgrades 2 |  | Verified | boss |  |
| Pollen Heart |  | needle upgrades 2 |  | Verified | collectible |  |

## Sinner's Road

### Sinner's Road Bench (Dust_10)

**Game ID:** Dust_10

**Contributors:** herchey

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Sinner's Road Vertical Hall West (Dust_02)](#sinners-road-vertical-hall-west-dust02) | ML | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Sinner’s Road #8 |  | Silk soar OR (Faydown AND cling grip) |  | Verified | collectible |  |
| Map Purchase: Sinner's Road |  | Silk Soar OR (spike pogo AND (swim OR ledge grab)) |  | Verified | collectible |  |
| Sinner's Road Bench |  | rosaries 40 AND (cling grip OR silk soar) AND break wall left AND break vines right AND ((faydown cloak AND clawline) OR (spike pogo AND swim)) |  | Verified | bench |  |
| Craw Summons |  | Craw Summons Ready |  | Verified | collectible |  |

### Sinner's Road Chef's Kitchen (Dust_Chef)

**Game ID:** Dust_Chef

**Contributors:** herchey

#### Subrooms

- lower
- upper
- basement

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | lower | [Sinner's Road Hanging Cages (Dust_04)](#sinners-road-hanging-cages-dust04) | R | prereq Sinner's Road Chef's Kitchen Door Switch |  | Verified |  |
| H | hatch | basement | [Sinner's Road Muckroach Cages (Dust_03)](#sinners-road-muckroach-cages-dust03) | C | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LU | lower to upper | lower | upper | faydown cloak OR silk soar |  | Verified |  |
| LU | lower to upper | upper | lower | none |  | Verified |  |
| BL | basement to lower | basement | lower | scuttlebrace OR cling grip OR silk soar |  | Verified |  |
| BL | basement to lower | lower | basement | invalid (true one-way) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Disgraced Chef Lugoli | upper | none |  | Verified | boss |  |
| Sinner's Road Chef's Kitchen Door Switch | lower | hit switch up OR hit switch left |  | Verified | switch |  |

### Sinner's Road Entrance (Dust_01)

**Game ID:** Dust_01

**Contributors:** herchey

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Greymoor Halfway Home Exterior (Greymoor_03)](#greymoor-halfway-home-exterior-greymoor03) | UR | ledge grab OR cling grip OR silk soar OR faydown cloak OR scuttlebrace |  | Verified |  |
| R | right |  | [Sinner's Road Vertical Hall West (Dust_02)](#sinners-road-vertical-hall-west-dust02) | LL | ledge grab OR cling grip OR silk soar OR faydown cloak OR scuttlebrace |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Frayed Rosary String: Sinner's Road |  | break wall left |  | Verified | collectible |  |

### Sinner's Road Flea Rescue (Dust_12)

**Game ID:** Dust_12

**Contributors:** herchey

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Sinner's Road Vertical Hall East (Dust_06)](#sinners-road-vertical-hall-east-dust06) | MR | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Sinner's Road |  | break wall left |  | Verified | collectible |  |

### Sinner's Road Hanging Cages (Dust_04)

**Game ID:** Dust_04

**Contributors:** herchey

#### Subrooms

- lower entry
- lower platform
- right ledge
- shard ledge
- upper entry
- shack
- plat above upper door
- middle left plat

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | lower entry | [Sinner's Road Vertical Hall West (Dust_02)](#sinners-road-vertical-hall-west-dust02) | MR | none |  | Verified |  |
| R | right | right ledge | [Sinner's Road Chef's Kitchen (Dust_Chef)](#sinners-road-chefs-kitchen-dustchef) | L | none |  | Verified |  |
| UL | upper left | upper entry | [Sinner's Road Vertical Hall West (Dust_02)](#sinners-road-vertical-hall-west-dust02) | UR | none |  | Verified |  |
| S | shack | shack | [Sinner's Road Shack (dust_shack)](#sinners-road-shack-dustshack) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RSL | right ledge to shard ledge | right ledge | shard ledge | Faydown cloak OR silk soar OR (cling grip AND enemy pogo AND (clawline OR sharpdart)) |  | Verified |  |
| RSL | right ledge to shard ledge | shard ledge | right ledge | none |  | Verified |  |
| UES | upper entry to shack | plat above upper door | shack | Clawline OR ((Cling grip OR silk soar) AND enemy pogo AND (drifter’s cloak OR sharpdart)) |  | Verified |  |
| UES | upper entry to shack | shack | plat above upper door | Run AND (faydown cloak OR clawline OR sharpdart) |  | Verified |  |
| RLS | right ledge to shack | right ledge | shack | silk soar |  | Verified |  |
| RLS | right ledge to shack | shack | right ledge | none |  | Verified |  |
| LP | lower entry to lower platform | lower entry | lower platform | ledge grab OR cling grip OR clawline OR sharpdart OR run OR dash OR drifter's cloak OR faydown cloak OR easy beast pogo OR easy wanderer needle strike OR easy architect needle strike |  | Verified |  |
| LP | lower entry to lower platform | lower platform | lower entry | none |  | Verified |  |
| PR | lower platform to right ledge | lower platform | right ledge | clawline OR enemy pogo OR (faydown cloak AND drifter's cloak AND ledge grab AND (sharpdart OR dash OR run)) |  | Verified |  |
| PR | lower platform to right ledge | right ledge | lower platform | clawline OR sharpdart OR swim OR enemy pogo OR drifter's cloak OR dash |  | Verified |  |
| UP | upper entry to upper plat | upper entry | plat above upper door | ledge grab OR cling grip OR silk soar OR faydown cloak |  | Verified |  |
| UP | upper entry to upper plat | plat above upper door | upper entry | none |  | Verified |  |
| LPM | lower plat to mid left plat | lower platform | middle left plat | silk soar |  | Verified |  |
| LPM | lower plat to mid left plat | middle left plat | lower platform | none |  | Verified |  |
| LEM | lower entry to mid left plat | lower entry | middle left plat | cling grip AND faydown cloak |  | Verified |  |
| LEM | lower entry to mid left plat | middle left plat | lower entry | none |  | Verified |  |
| LMU | middle left plat to upper | middle left plat | plat above upper door | silk soar OR (cling grip AND (clawline OR enemy pogo)) OR (faydown cloak AND (enemy pogo OR (clawline AND (ledge grab OR cling grip)))) |  | Verified |  |
| LMU | middle left plat to upper | plat above upper door | middle left plat | none |  | Verified |  |
| MLS | middle left to shard | middle left plat | shard ledge | faydown cloak OR (run AND (ledge grab OR cling grip)) OR (clawline AND (ledge grab OR cling grip)) |  | Verified |  |
| MLS | middle left to shard | shard ledge | middle left plat | ((ledge grab OR cling grip) AND (dash OR clawline x 2 OR sharpdart x 2)) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| My Missing Brother Wish Granted | upper entry | complete THE My Missing Brother Wish Promised |  | Verified | event |  |
| Shell Shard Cache: Sinner’s Road #4 | shard ledge | none |  | Verified | collectible |  |
| Shell Shard Cache: Sinner’s Road #5 | shard ledge | none |  | Verified | collectible |  |
| Upper Entry Switch | upper entry | hit switch left OR hit switch up |  | Verified | switch |  |

### Sinner's Road Mist Maze Completed (Dust_Maze_08_completed)

**Game ID:** Dust_Maze_08_completed

**Contributors:** Herchey and a gallon of milk

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | up right |  | [Exhaust Organ Exterior (Dust_09)](#exhaust-organ-exterior-dust09) | L | cling grip AND (silk soar OR clawline OR sharpdart OR drifter's cloak OR faydown cloak OR (enemy pogo AND run)) |  | Verified |  |
| LR | low right |  | [Sinner's Road North Hall (Dust_05)](#sinners-road-north-hall-dust05) | L | spike pogo OR clawline OR sharpdart OR faydown cloak OR drifter's cloak OR scuttlebrace OR run OR dash OR cling grip |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Sinner's Road Muckroach Cages (Dust_03)

**Game ID:** Dust_03

**Contributors:** herchey

#### Subrooms

- left half
- right half

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | right half | [Sinner's Road Chef's Kitchen (Dust_Chef)](#sinners-road-chefs-kitchen-dustchef) | H | (faydown cloak AND cling grip) OR silk soar |  | Verified |  |
| LR | lower right | right half | [Sinner's Road Spike Basement (Dust_Barb)](#sinners-road-spike-basement-dustbarb) | C | none |  | Verified |  |
| L | left | left half | [Sinner's Road Vertical Hall West (Dust_02)](#sinners-road-vertical-hall-west-dust02) | LR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LR | left to right | left half | right half | none |  | Verified |  |
| LR | left to right | right half | left half | Cling grip OR ledge grab OR silk soar OR dash OR enemy pogo OR faydown cloak |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Sinner’s Road #1 | left half | Silk soar OR ledge grab OR cling grip OR faydown cloak |  | Verified | collectible | Check subroom |
| Shell Shard Cache: Sinner’s Road #2 | left half | Silk soar OR ledge grab OR cling grip OR faydown cloak |  | Verified | collectible |  |
| Shell Shard Cache: Sinner’s Road #3 | left half | Silk soar OR ledge grab OR cling grip OR faydown cloak |  | Verified | collectible |  |
| Rosary Cache: Sinner’s Road #4 | left half | Ledge grab OR silk soar OR faydown cloak OR scuttlebrace |  | Verified | collectible |  |

### Sinner's Road North Hall (Dust_05)

**Game ID:** Dust_05

**Contributors:** herchey

#### Subrooms

- behind left wall
- left area
- middle area
- right door platform
- hatch

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | behind left wall | [Sinner's Road Mist Maze Completed (Dust_Maze_08_completed)](#sinners-road-mist-maze-completed-dustmaze08completed) | LR | none |  | Verified |  |
| C | center | hatch | [Sinner's Road Vertical Hall West (Dust_02)](#sinners-road-vertical-hall-west-dust02) | C | none |  | Verified |  |
| R | right | right door platform | [Sinner's Road Vertical Hall East (Dust_06)](#sinners-road-vertical-hall-east-dust06) | L | faydown cloak OR (enemy pogo AND drifter’s cloak) OR (clawline AND (ledge grab OR cling grip)) |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LWL | Behind left wall to left area | behind left wall | left area | complete North Hall Breakable wall |  | Verified |  |
| LWL | Behind left wall to left area | left area | behind left wall | complete North Hall Breakable wall AND (Silk soar OR faydown cloak OR cling grip OR scuttlebrace) |  | Verified |  |
| LAM | Left area to middle area | left area | middle area | clawline OR enemy pogo OR (sharpdart x 3 AND (drifter’s cloak OR faydown cloak)) OR (drifter’s cloak AND ((cling grip AND ledge grab) OR faydown cloak)) OR (swim AND ledge grab) |  | Verified |  |
| LAM | Left area to middle area | middle area | left area | clawline OR enemy pogo OR (sharpdart AND (drifter’s cloak OR faydown cloak)) OR (drifter’s cloak AND faydown cloak) OR (swim AND (ledge grab OR cling grip)) |  | Verified |  |
| MAH | Middle area to hatch | middle area | hatch | none |  | Verified | Technically "any attack" is the requirement |
| MAH | Middle area to hatch | hatch | middle area | Ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| MAR | Middle area to right door platform | middle area | right door platform | (swim AND faydown cloak) OR (clawline AND (drifter’s cloak OR sharpdart OR enemy pogo)) OR (drifter’s cloak AND (sharpdart OR enemy pogo)) OR (sharpdart AND enemy pogo) |  | Verified |  |
| MAR | Middle area to right door platform | right door platform | middle area | enemy pogo OR swim OR (drifter’s cloak AND (run OR dash OR ledge grab OR sharpdart OR clawline OR faydown cloak)) OR (run AND (faydown cloak OR sharpdart OR clawline)) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Sinner’s Road #6 | left area | swim AND attack up |  | Verified | collectible |  |
| Shell Shard Cache: Sinner’s Road #7 | left area | swim AND attack up |  | Verified | collectible |  |
| North Hall Breakable wall | left area | none |  | Verified | blockade |  |

### Sinner's Road Spike Basement (Dust_Barb)

**Game ID:** Dust_Barb

**Contributors:** herchey

#### Subrooms

- upper
- lower

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | upper | [Sinner's Road Muckroach Cages (Dust_03)](#sinners-road-muckroach-cages-dust03) | LR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| UL | Upper to lower | upper | lower | none |  | Verified |  |
| UL | Upper to lower | lower | upper | Silk soar OR cling grip |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Barbed Bracelet | lower | none |  | Verified | collectible |  |

### Sinner's Road Styx Room (Dust_11)

**Game ID:** Dust_11

**Contributors:** herchey

#### Subrooms

- left
- right
- cage

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left | [Sinner's Road Vertical Hall East (Dust_06)](#sinners-road-vertical-hall-east-dust06) | LR | none |  | Verified |  |
| B | basement | cage | [Greymoor Silver Shells room (Greymoor_17)](#greymoor-silver-shells-room-greymoor17) | U | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LR | left to right | left | right | (Swim OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR dash) AND complete Styx Room Upper Breakable Wall |  | Verified |  |
| LR | left to right | right | left | (Spike pogo OR Faydown cloak OR (silk soar AND drifter’s cloak) OR (cling grip AND (sharpdart OR clawline OR dash))) AND complete Styx Room Upper Breakable Wall |  | Verified |  |
| CR | cage to right | cage | right | complete Styx Room Lower Breakable Wall |  | Verified |  |
| CR | cage to right | right | cage | complete Styx Room Lower Breakable Wall |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Styx Room Upper Breakable Wall | left | break wall right |  | Verified | blockade |  |
| Styx Room Lower Breakable Wall | cage | break wall right |  | Verified | blockade |  |
| Styx Grew First Grub | left | steel soul off |  | Verified | logic-point |  |
| Craw Summons | left | Craw Summons Ready |  | Verified | collectible |  |

### Sinner's Road Vertical Hall East (Dust_06)

**Game ID:** Dust_06

**Contributors:** herchey

#### Subrooms

- lower
- upper

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | upper | [Sinner's Road North Hall (Dust_05)](#sinners-road-north-hall-dust05) | R | none |  | Verified |  |
| LR | lower right | lower | [Sinner's Road Styx Room (Dust_11)](#sinners-road-styx-room-dust11) | L | none |  | Verified |  |
| MR | middle right | upper | [Sinner's Road Flea Rescue (Dust_12)](#sinners-road-flea-rescue-dust12) | L | none |  | Verified |  |
| UR | upper right | upper | [Bilewater Sinner's Entrance (Shadow_05)](#bilewater-sinners-entrance-shadow05) | L | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Sinner’s Road #5 | upper | none |  | Verified | collectible |  |
| Rosary Cache: Sinner’s Road #6 | upper | none |  | Verified | collectible |  |
| Rosary Cache: Sinner’s Road #7 | upper | none |  | Verified | collectible |  |
| Shard Bundle: Sinner’s Road | upper | Ledge grab OR cling grip OR faydown cloak OR silk soar OR scuttlebrace |  | Verified | collectible |  |
| Simple Key: Roachkeeper | upper | Cling grip AND (dash OR drifter’s cloak OR clawline OR sharpdart) |  | Verified | collectible |  |

### Sinner's Road Vertical Hall West (Dust_02)

**Game ID:** Dust_02

**Contributors:** herchey

#### Subrooms

- basement
- lower
- middle right
- middle left
- upper right
- top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | lower | [Sinner's Road Entrance (Dust_01)](#sinners-road-entrance-dust01) | R | none |  | Verified |  |
| ML | middle left | middle left | [Sinner's Road Bench (Dust_10)](#sinners-road-bench-dust10) | R | none |  | Verified |  |
| C | ceiling | top | [Sinner's Road North Hall (Dust_05)](#sinners-road-north-hall-dust05) | C | none |  | Verified |  |
| LR | lower right | lower | [Sinner's Road Muckroach Cages (Dust_03)](#sinners-road-muckroach-cages-dust03) | L | none |  | Verified |  |
| MR | middle right | middle right | [Sinner's Road Hanging Cages (Dust_04)](#sinners-road-hanging-cages-dust04) | LL | none |  | Verified |  |
| UR | upper right | upper right | [Sinner's Road Hanging Cages (Dust_04)](#sinners-road-hanging-cages-dust04) | UL | prereq Upper Entry Switch IN Sinner's Road Hanging Cages |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BL | basement to lower | lower | basement | none |  | Verified | Technically "any attack" is a requirement |
| BL | basement to lower | basement | lower | cling grip |  | Verified |  |
| LMR | low to mid right | lower | middle right | Cling grip OR silk soar OR (scuttlebrace AND faydown cloak) |  | Verified |  |
| LMR | low to mid right | middle right | lower | none |  | Verified |  |
| MRL | mid right to mid left | middle right | middle left | silk soar |  | Verified |  |
| MRL | mid right to mid left | middle left | middle right | none |  | Verified |  |
| LUR | mid left to upper right | middle left | upper right | Cling grip OR faydown cloak |  | Verified |  |
| LUR | mid left to upper right | upper right | middle left | none |  | Verified |  |
| URT | upper right to top | upper right | top | Silk soar OR (cling grip AND (enemy pogo OR faydown cloak OR (proficient movement AND drifter's cloak) OR clawline OR sharpdart OR dash)) OR (faydown cloak AND ledge grab AND enemy pogo) |  | Verified |  |
| URT | upper right to top | top | upper right | none |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Sinner’s Road #1 | lower | swim AND (Ledge grab OR cling grip OR faydown cloak) |  | Verified | collectible |  |
| Rosary Cache: Sinner’s Road #2 | upper right | none |  | Verified | collectible |  |
| Rosary Cache: Sinner’s Road #3 | upper right | none |  | Verified | collectible |  |

### Sinner's Road Shack (dust_shack)

**Game ID:** dust_shack

**Contributors:** herchey

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Sinner's Road Hanging Cages (Dust_04)](#sinners-road-hanging-cages-dust04) | S | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Roach Guts Wish Promised |  | act 2 |  | Verified | event |  |
| Roach Guts Wish Granted |  | roach guts 10 |  | Verified | event |  |
| Tacks |  | complete Roach Guts Wish Granted OR act 3 |  | Verified | collectible |  |
| Steel Spines |  | complete THE Infestation Operation Wish Promised AND ( ( act 2 AND rosaries 160 ) OR act 3 ) |  | Verified | collectible | Free in act 3 cause they ded |

## Underworks

### Vaults & Bellway Cauldron Entrance (Library_11)

**Game ID:** Library_11

#### Subrooms

- Elevator Shaft
- Bottom Exit
- Side Shaft Bottom Exit
- Side Shaft Top Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | Top Left | Elevator Shaft | [Trobbio (Library_13)](#trobbio-library13) | BR | Nothing. |  | Verified |  |
| HL | High Left | Side Shaft Top Exit | [Grand Bellway (Bellway_City)](#grand-bellway-bellwaycity) | R | Nothing. |  | Verified |  |
| LR | Low Right | Bottom Exit | [Underworks Exhaust Organ Transit (Library_12)](#underworks-exhaust-organ-transit-library12) | LL | Nothing. |  | Verified |  |
| LL | Low Left | Elevator Shaft | [Underworks Silk Spool (Library_11b)](#underworks-silk-spool-library11b) | R | Nothing. |  | Verified |  |
| UR | Upper Right | Side Shaft Bottom Exit | [Underworks Exhaust Organ Transit (Library_12)](#underworks-exhaust-organ-transit-library12) | UL | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SST | Side Shaft Traversal | Side Shaft Bottom Exit | Side Shaft Top Exit | Cling Grip OR Scuttlebrace AND Spike Pogo |  | Verified |  |
| SST | Side Shaft Traversal | Side Shaft Top Exit | Side Shaft Bottom Exit | Nothing. (Fall) |  | Verified |  |
| MST | Main Shaft Traversal | Elevator Shaft | Bottom Exit | Spike Pogo OR Cling Grip AND Faydown Cloak OR Drifter's Cloak OR Dash OR Clawline OR Sharp Dart OR Scuttlebrace AND Clawline OR (Faydown Cloak AND Drifter's Cloak) (Difficult) |  | Verified |  |
| MST | Main Shaft Traversal | Bottom Exit | Elevator Shaft | Elevator moved up AND Cling Grip AND (Drifter's Cloak OR Clawline OR Sharp Dart OR Spike Pogo) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Flip Switch #2 (Left) | Elevator Shaft | Nothing. |  | Verified | switch |  |

### Chapel of the Architect (Under_20)

**Game ID:** Under_20

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Underworks Twelfth Architect (Under_17)](#underworks-twelfth-architect-under17) | AC | Nothing. |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Silkeater |  | Nothing. |  |  | collectible |  |
| Underworks: Break Wall (Up) |  | Nothing. |  |  | blockade |  |
| Underworks: Needolin Lore |  | Needolin. |  |  | lore |  |
| Architect's Crest |  | Nothing. |  |  | collectible |  |

### Underworks Below Vaultkeeper (Library_12b)

**Game ID:** Library_12b

#### Subrooms

- Top Exit Corner
- Top Exit Shaft
- Needolin Check
- Shell Shard Check
- Left Side Shafts
- Left Side Shaft Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | Left Side Shaft Exit | [Underworks Exhaust Organ Transit (Library_12)](#underworks-exhaust-organ-transit-library12) | R | Nothing. |  | Verified |  |
| T | Top | Top Exit Corner | [Vaultkeeper Cauldron Entrance (Library_10)](#vaultkeeper-cauldron-entrance-library10) | B | Silk Soar OR Faydown Cloak OR Cling Grip OR Scuttlebrace |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TP | Top Path | Top Exit Corner | Top Exit Shaft | Nothing. (Fall) |  | Verified |  |
| TP | Top Path | Top Exit Shaft | Top Exit Corner | Cling Grip OR Scuttlebrace |  | Verified |  |
| NP | Needolin Path | Top Exit Shaft | Needolin Check | Nothing. (Fall) |  | Verified | pretty precise fall |
| NP | Needolin Path | Needolin Check | Top Exit Shaft | Cling Grip OR Spike Pogo |  | Verified |  |
| LP | Left Path | Top Exit Shaft | Left Side Shafts | Nothing. (Fall) |  | Verified |  |
| LP | Left Path | Left Side Shafts | Top Exit Shaft | Ledge Grab OR Clawline OR Scuttlebrace OR Faydown Cloak OR Easy Shaman Pogo OR Easy Beast Charge |  | Verified |  |
| SP | Shell Path | Left Side Shafts | Shell Shard Check | Nothing. (fall) |  | Verified |  |
| SP | Shell Path | Shell Shard Check | Left Side Shafts | Cling Grip OR Scuttlebrace |  | Verified |  |
| LPC | Left Path, Continued | Left Side Shafts | Left Side Shaft Exit | Nothing. (Fall) |  | Verified |  |
| LPC | Left Path, Continued | Left Side Shaft Exit | Left Side Shafts | Cling Grip OR Scuttlebrace |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Needolin Lore #1 | Needolin Check | Needolin |  | Verified | lore |  |
| Underworks: Shell Shard Cache #1 | Shell Shard Check | Nothing. |  | Verified | collectible |  |

### Underworks Clawline Entrance (Under_19c)

**Game ID:** Under_19c

#### Subrooms

- Top
- Bottom
- Center

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | left1 | Top | [Underworks Clawline Room (Under_18)](#underworks-clawline-room-under18) | R | Nothing. |  | Verified |  |
| BL | left2 | Center | [Underworks Craftmetal Corridor (Under_19b)](#underworks-craftmetal-corridor-under19b) | R | Nothing. |  | Verified |  |
| B | bot1 | Bottom | [Underworks Lava Flow Corridor (Under_19)](#underworks-lava-flow-corridor-under19) | T | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BC | B-C | Bottom | Center | Silk Soar OR Cling Grip OR Scuttlebrace AND Easy Shaman Pogo OR Faydown Cloak AND (Ledge Grab OR Clawline) |  | Verified |  |
| CT | C-T | Center | Top | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| CT | C-T | Top | Center | Nothing. (Fall) |  | Verified |  |
| BC | B-C | Center | Bottom | Nothing. (Fall) |  | Verified |  |

#### Check Locations

No check locations defined.

### Underworks Clawline Room (Under_18)

**Game ID:** Under_18

#### Subrooms

- Clawline Statue
- Blocked Off Corridor Left
- Shard Bundle Check
- Main Side Door
- Arena
- Blocked Off Corridor Top

- **Arena:** Arena activated by Clawline Ring

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TR | Top Right | Arena | [Underworks Twelfth Architect (Under_17)](#underworks-twelfth-architect-under17) | BR | Completed Arena AND (Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown Cloak AND (Crest Pogo (Shaman) OR Crest Needle Strike (Beast))) |  | Verified |  |
| L | Left | Blocked Off Corridor Left | [Underworks East Shaft (Under_13)](#underworks-east-shaft-under13) | MR | Nothing. |  | Verified |  |
| R | Right | Main Side Door | [Underworks Clawline Entrance (Under_19c)](#underworks-clawline-entrance-under19c) | TL | Can't enter from this side. |  | Verified |  |
| TL | Top Left | Blocked Off Corridor Top | [Underworks Twelfth Architect (Under_17)](#underworks-twelfth-architect-under17) | BL | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AP | Arena Path | Main Side Door | Arena | Clawline OR Faydown Cloak AND (Sharp Dart OR Swift Step) AND Ledge Grab AND Enemy Pogo |  | Verified | getting up here without clawline is worthless unless cause the exit needs clawline anyway lmao |
| CP | Clawline Path | Main Side Door | Clawline Statue | Clawline OR Faydown Cloak AND Sprint AND (Drifter's Cloak OR (Dash AND Enemy Pogo)) AND Ledge Grab |  | Verified |  |
| SP | Shard Path | Main Side Door | Shard Bundle Check | Clawline OR Faydown Cloak AND (Sharp Dart OR Swift Step) AND Ledge Grab AND Enemy Pogo |  | Verified | same thing as the arena path but you go left at the end instead of right |
| LST | Left Side Travel | Blocked Off Corridor Left | Blocked Off Corridor Top | Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak AND (Ledge Grab OR Clawline) |  | Verified |  |
| AP | Arena Path | Arena | Main Side Door | Clawline OR Sharp Dart OR Dash OR Sprint OR Scuttlebrace OR Drifter's Cloak OR Faydown Cloak AND Ledge Grab |  | Verified |  |
| CP | Clawline Path | Clawline Statue | Main Side Door | Clawline OR Sharp Dart AND Faydown Cloak AND (Swift Step OR Drifter's Cloak) |  | Verified |  |
| SP | Shard Path | Shard Bundle Check | Main Side Door | Clawline OR (Drifter's Cloak OR Swift Step) AND Enemy Pogo OR Faydown Cloak AND Sharp Dart |  | Verified |  |
| LST | Left Side Travel | Blocked Off Corridor Top | Blocked Off Corridor Left | Nothing. (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Clawline Pickup | Clawline Statue | Nothing. |  | Verified | collectible |  |
| Underworks: Shard Bundle #2 | Shard Bundle Check | Nothing. |  | Verified | collectible |  |
| Clawline Ring | Arena | Clawline |  | Verified |  |  |

### Underworks Craftmetal Corridor (Under_19b)

**Game ID:** Under_19b

#### Subrooms

- Fuckass Jump Left
- Fuckass Jump Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Fuckass Jump Right | [Underworks Clawline Entrance (Under_19c)](#underworks-clawline-entrance-under19c) | BL | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| J | Jump | Fuckass Jump Left | Fuckass Jump Right | Ledge Grab OR Clawline OR Sharp Dart OR Cling Grip OR Scuttlebrace OR Sprint OR Dash OR Faydown Cloak OR Drifter's Cloak  OR Easy Shaman Pogo  OR Easy Beast Pogo OR Easy Architect Pogo OR Easy Hunter Pogo OR Easy Reaper Pogo  OR Easy Witch Needle Strike OR Easy Wanderer Needle Strike |  | Verified | why couldnt you have been TWO pixels shorter? |
| J | Jump | Fuckass Jump Right | Fuckass Jump Left | Nothing. |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Craftmetal #1 | Fuckass Jump Left | Nothing. |  | Verified | collectible |  |

### Underworks East Shaft (Under_13)

**Game ID:** Under_13

#### Subrooms

- Lower Central Shaft
- Bottom Left Entrance
- Bottom Right Entrance
- Bottom
- Lower Left Entrance
- High Left Entrance
- Top Left Entrance
- Mid Right Entrance
- Top Right Entrance
- Upper Central Shaft

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bottom Left | Bottom Left Entrance | [Underworks Flea Room (Under_21)](#underworks-flea-room-under21) | R | Nothing. |  | Verified |  |
| BR | Bottom Right | Bottom Right Entrance | [Underworks Lava Flow Corridor (Under_19)](#underworks-lava-flow-corridor-under19) | L | Nothing. |  | Verified |  |
| TL | Top Left | Top Left Entrance | [Underworks Lever Spike Corridor (Under_11)](#underworks-lever-spike-corridor-under11) | R | Nothing. |  | Verified |  |
| TR | Top Right | Top Right Entrance | [Underworks Twelfth Architect (Under_17)](#underworks-twelfth-architect-under17) | FL | Nothing. |  | Verified |  |
| HL | High Left | High Left Entrance | [Underworks Ventrica (Under_22)](#underworks-ventrica-under22) | R | Nothing. |  | Verified |  |
| MR | Mid Right | Mid Right Entrance | [Underworks Clawline Room (Under_18)](#underworks-clawline-room-under18) | L | Nothing. |  | Verified |  |
| LL | Low Left | Lower Left Entrance | [Underworks Eastern Gauntlet (Under_10)](#underworks-eastern-gauntlet-under10) | R | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLR | Bottom Left-Bottom Right | Bottom Left Entrance | Bottom Right Entrance | Ledge Grab OR Clawline OR Faydown Cloak |  | Verified |  |
| BLR | Bottom Left-Bottom Right | Bottom Right Entrance | Bottom Left Entrance | Ledge Grab AND (Sprint OR Dash OR Drifter's Cloak) OR Clawline OR Cling Grip OR Faydown Cloak |  | Verified |  |
| BC | Bottom-Lower Central | Bottom | Lower Central Shaft | Silk Soar OR (Faydown Cloak OR Clawline) AND Enemy Pogo OR Cling Grip OR Scuttlebrace |  | Verified |  |
| LHL | Lower Left-High Left | Lower Left Entrance | High Left Entrance | Cling Grip OR Scuttlebrace |  | Verified |  |
| LHL | Lower Left-High Left | High Left Entrance | Lower Left Entrance | Nothing. (Fall) |  | Verified |  |
| HLT | High Left-Top Left | High Left Entrance | Top Left Entrance | Silk Soar OR Faydown Cloak OR Cling Grip OR Scuttlebrace |  | Verified |  |
| HLT | High Left-Top Left | Top Left Entrance | High Left Entrance | Nothing. (Fall) |  | Verified |  |
| HLR | High Left-Mid Right | High Left Entrance | Mid Right Entrance | Activate shortcut from other side, flip lever. |  | Verified |  |
| HLR | High Left-Mid Right | Mid Right Entrance | High Left Entrance | Flip bridge lever AND Silk Soar OR Cling Grip OR Faydown Cloak OR Scuttlebrace AND (Drifter's Cloak OR (Dash AND Ledge Grab)) |  | Verified |  |
| LUC | Lower Central-Upper Central | Lower Central Shaft | Upper Central Shaft | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| LUC | Lower Central-Upper Central | Upper Central Shaft | Lower Central Shaft | Nothing. (Fall) |  | Verified |  |
| BC | Bottom-Lower Central | Lower Central Shaft | Bottom | Nothing. (Fall) |  | Verified |  |
| CTP | Upper Central-Top Left | Upper Central Shaft | Top Right Entrance | Clawline OR Ledge Grab OR Scuttlebrace OR Faydown Cloak OR Cling Grip OR Silk Soar |  | Verified |  |
| CTP | Upper Central-Top Left | Top Right Entrance | Upper Central Shaft | Nothing. (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Flip Switch (Left OR Right) #3 | Mid Right Entrance | Nothing. |  | Verified | switch | is this even a check? |

### Underworks Eastern Gauntlet (Under_10)

**Game ID:** Under_10

#### Subrooms

- Right Entrance
- Arena
- Left Entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Entrance | [Underworks Central Shaft (Under_05)](#underworks-central-shaft-under05) | BR | Nothing. |  | Verified |  |
| R | right1 | Right Entrance | [Underworks East Shaft (Under_13)](#underworks-east-shaft-under13) | LL | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RA | Right-Arena | Right Entrance | Arena | Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak |  | Verified |  |
| LA | Left-Arena | Left Entrance | Arena | Flipped Lever |  | Verified |  |
| LA | Left-Arena | Arena | Left Entrance | Flipped Lever |  | Verified |  |
| RA | Right-Arena | Arena | Right Entrance | Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak OR Ledge Grab OR Clawline |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Lever (Up) #1 | Arena | Beat Arena |  | Verified | switch |  |
| Underworks: Silk Spool #2 | Arena | Nothing. |  | Verified | collectible |  |
| Underworks: Arena Fight #1 | Arena |  |  | Verified | collectible |  |

### Underworks Exhaust Organ Transit (Library_12)

**Game ID:** Library_12

#### Subrooms

- Shell Shard Cache #1
- Shell Shard Cache #2
- Shell Bundle Pickup
- Exhaust Organ Elevator
- Far Right
- Lower Left
- Upper Left
- Center
- One-Way Floor

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | Upper Left | Upper Left | [Vaults & Bellway Cauldron Entrance (Library_11)](#vaults-bellway-cauldron-entrance-library11) | UR | Nothing. |  | Verified |  |
| LL | Lower Left | Lower Left | [Vaults & Bellway Cauldron Entrance (Library_11)](#vaults-bellway-cauldron-entrance-library11) | LR | Nothing. |  | Verified |  |
| EV | Elevator | Exhaust Organ Elevator | [Exhaust Organ Interior (Organ_01)](#exhaust-organ-interior-organ01) | UE | Nothing. |  | Verified |  |
| R | Right | Far Right | [Underworks Below Vaultkeeper (Library_12b)](#underworks-below-vaultkeeper-library12b) | L | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SB | Collect Shell Bundle | Far Right | Shell Bundle Pickup | Nothing. (Fall) |  | Verified |  |
| SB | Collect Shell Bundle | Shell Bundle Pickup | Far Right | Silk Soar OR Scuttlebrace AND Spike Pogo OR Cling Grip AND (Spike Pogo OR Faydown Cloak OR Drifter's Cloak OR Clawline OR Sharp Dart) |  | Verified |  |
| CFR | Center-Far Right | Far Right | Center | Spike Pogo OR Sprint OR Dash OR Faydown Cloak OR Drifter's Cloak OR Clawline OR Sharp Dart OR Scuttlebrace |  | Verified |  |
| CT | Center-Top | Center | One-Way Floor | Scuttlebrace AND (Faydown Cloak OR Clawline OR Sharp Dart OR ((Sprint OR Spike Pogo) AND (Ledge Grab OR Dash OR Drifter's Cloak)) OR Cling Grip AND (Spike Pogo OR Drifter's Cloak OR Faydown Cloak OR Clawline OR Sharp Dart OR Dash OR Crest Pogo (Beast) OR Crest Needle Strike (Architect OR Beast) |  | Verified |  |
| CL | Center-Low | Lower Left | Center | Silk Soar AND (Clawline OR Sharp Dart OR Dash OR Faydown Cloak OR Drifter's Cloak OR Crest Pogo (Beast)) Cling Grip OR Scuttlebrace |  | Verified |  |
| CFR | Center-Far Right | Center | Far Right | Silk Soar AND (Clawline OR Dash OR Sharp Dart OR Drifter's Cloak OR Faydown Cloak) OR Scuttlebrace OR Cling Grip |  | Verified |  |
| CL | Center-Low | Center | Lower Left | Silk Soar OR Faydown Cloak OR Drifter's Cloak OR OR Dash OR Cling Grip OR Clawline OR Sharp Dart OR Scuttlebrace OR Spike Pogo |  | Verified |  |
| CT | Center-Top | One-Way Floor | Center | Nothing. (Fall) |  | Verified | IF floor is broken. |
| BF | Breakable Floor | One-Way Floor | Upper Left | Break the ceiling |  | Verified |  |
| SP | Shard Pillars Center | Center | Shell Shard Cache #2 | Nothing. (Fall) |  | Verified |  |
| SSR | Shell Shard Rocks | Upper Left | Shell Shard Cache #1 | Nothing. |  | Verified |  |
| SPL | Shard Pillars Left | Lower Left | Shell Shard Cache #2 | Spike Pogo OR Clawline AND Sharp Dart AND Ledge Grab OR Clawline AND (Faydown Cloak OR Drifter's Cloak) |  | Verified |  |
| ET | Elevator Transit | Upper Left | Exhaust Organ Elevator | Opened Shortcut |  | Verified |  |
| ET | Elevator Transit | Exhaust Organ Elevator | Upper Left | Nothing. |  | Verified |  |
| BF | Breakable Floor | Upper Left | One-Way Floor | Nothing. (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Break Wall #1 (Left OR Right) | Far Right | Nothing. |  | Verified | switch |  |
| Underworks: Shell Shard Pillar #1 | Shell Shard Cache #2 | Nothing. |  | Verified | collectible |  |
| Underworks: Shell Shard Pillar #2 | Shell Shard Cache #2 | Nothing. |  | Verified | collectible |  |
| Underworks: Shell Shard Rock #2 | Shell Shard Cache #1 | Nothing. |  | Verified | collectible |  |
| Underworks: Shard Bundle #1 | Shell Bundle Pickup | Nothing. |  | Verified | collectible |  |
| Underworks: Shell Shard Rock #1 | Shell Shard Cache #1 | Nothing. |  | Verified | collectible |  |
| Wunderworks: Break Wall #2 (Up) | Upper Left | Nothing. |  | Verified | blockade |  |
| Underworks: Flip Switch #1 (Left) | Exhaust Organ Elevator | Nothing. |  | Verified | switch |  |

### Underworks Flea Room (Under_21)

**Game ID:** Under_21

#### Subrooms

- Entrance
- Flea

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Entrance | [Underworks East Shaft (Under_13)](#underworks-east-shaft-under13) | BL | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FG | Flea Get | Entrance | Flea | Ledge Grab OR Clawline OR Cling Grip OR Scuttlebrace OR Faydown Cloak OR Silk Soar |  | Verified |  |
| FG | Flea Get | Flea | Entrance | Nothing. (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Flea #1 | Flea | Nothing. |  | Verified | collectible |  |

### Underworks Lava Flow Corridor (Under_19)

**Game ID:** Under_19

#### Subrooms

- Right Exit
- Main

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Right Exit | [Underworks Clawline Entrance (Under_19c)](#underworks-clawline-entrance-under19c) | B | Nothing. |  | Verified |  |
| L | left1 | Main | [Underworks East Shaft (Under_13)](#underworks-east-shaft-under13) | BR | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| J | Jump | Right Exit | Main | Clawline OR Sharp Dart OR Dash OR Faydown Cloak OR Drifter's Cloak OR Scuttlebrace |  | Verified |  |
| J | Jump | Main | Right Exit | Scuttlebrace OR (Clawline OR Sharp Dart OR Dash) AND (Faydown Cloak OR Cling Grip) |  | Verified |  |

#### Check Locations

No check locations defined.

### Underworks Lever Spike Corridor (Under_11)

**Game ID:** Under_11

#### Subrooms

- Left Side Entrance
- Right Side Entrance
- Central Top Shaft
- Lever Shaft

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Side Entrance | [Underworks Central Shaft (Under_05)](#underworks-central-shaft-under05) | TR | Nothing. |  | Verified |  |
| R | right1 | Right Side Entrance | [Underworks East Shaft (Under_13)](#underworks-east-shaft-under13) | TL | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LC | Left-CentraL | Left Side Entrance | Central Top Shaft | Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak |  | Verified |  |
| LC | Left-CentraL | Central Top Shaft | Left Side Entrance | Nothing. (Fall) |  | Verified |  |
| RC | Right-Central | Right Side Entrance | Central Top Shaft | Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak |  | Verified |  |
| RC | Right-Central | Central Top Shaft | Right Side Entrance | Nothing. (Fall) |  | Verified |  |
| CL | Central-Lever | Central Top Shaft | Lever Shaft | Nothing. (fall) |  | Verified |  |
| CL | Central-Lever | Lever Shaft | Central Top Shaft | Lever Flipped AND (Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak) |  | Verified |  |
| LL | Left-Lever | Left Side Entrance | Lever Shaft | Lever Flipped AND (Spike Pogo OR Dash OR Sprint OR Clawline OR Sharp Dart OR Faydown Cloak OR Drifter's Cloak OR Scuttlebrace |  | Verified |  |
| LL | Left-Lever | Lever Shaft | Left Side Entrance | Lever Flipped AND (Spike Pogo OR Dash OR Sprint OR Clawline OR Sharp Dart OR Faydown Cloak OR Drifter's Cloak OR Scuttlebrace |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Flip Switch (Left) #3 | Lever Shaft | Nothing. |  | Verified | switch |  |

### Underworks Rosary Room (Under_12)

**Game ID:** Under_12

#### Subrooms

- Entrance
- Rosary Necklace

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Entrance | [Underworks Central Shaft (Under_05)](#underworks-central-shaft-under05) | R | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RP | Rosary Pickup | Entrance | Rosary Necklace | Ledge Grab OR Clawline OR  Cling Grip OR Scuttlebrace OR Faydown Cloak OR Silk Soar |  | Verified |  |
| RP | Rosary Pickup | Rosary Necklace | Entrance | Nothing. (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Frayed Rosary Necklace #1 | Rosary Necklace | Nothing. |  | Verified | collectible |  |

### Underworks Silk Spool (Library_11b)

**Game ID:** Library_11b

#### Subrooms

- Upper Right
- Shell Shard Alcove #1
- Shell Shard Alcove #2
- Upper Left
- Bottom
- Silk Spool

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left3 | Upper Left | [Underworks Twelfth Architect (Under_17)](#underworks-twelfth-architect-under17) | FR | Nothing. |  | Verified |  |
| R | right1 | Upper Right | [Vaults & Bellway Cauldron Entrance (Library_11)](#vaults-bellway-cauldron-entrance-library11) | LL | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RL | Right-Left | Upper Left | Upper Right | Spike Pogo AND Ledge Grab OR (Sprint OR Dash OR Clawline OR Sharp Dart) AND (Silk Soar OR Cling Grip OR Scuttlebrace OR (Faydown Cloak AND (Ledge Grab OR Clawline)) |  | Verified |  |
| CS1 | Collect Shards #1 | Upper Right | Shell Shard Alcove #1 | Faydown Cloak AND Drifter's Cloak AND Ledge Grab AND Spike Pogo OR (Cling Grip OR Scuttlebrace) AND (Clawline OR (Dash AND Sharp Dart AND Spike Pogo AND Ledge Grab) |  | Verified |  |
| CS2 | Collect Shards #2 | Upper Left | Shell Shard Alcove #2 | Nothing. (Fall) |  | Verified |  |
| CSS | Collect Silk Spool | Bottom | Silk Spool | Break Wall |  | Verified |  |
| C | Climb | Upper Left | Bottom | Nothing. (Fall) |  | Verified |  |
| C | Climb | Bottom | Upper Left | Cling Grip OR Scuttlebrace AND Faydown Cloak |  | Verified |  |
| CS2 | Collect Shards #2 | Shell Shard Alcove #2 | Upper Left | Ledge Grab OR Clawline OR Cling Grip OR Scuttlebrace OR Faydown Cloak OR Silk Soar |  | Verified |  |
| CSS | Collect Silk Spool | Silk Spool | Bottom | Nothing. |  | Verified |  |
| CS1 | Collect Shards #1 | Shell Shard Alcove #1 | Upper Right | Spike Pogo OR Dash OR Clawline OR Sharp Dart OR Drifter's cloak OR Faydown Cloak OR Scuttlebrace |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Shell Shard Rock #3 | Shell Shard Alcove #1 | Nothing. |  | Verified | collectible |  |
| Underworks: Shell Shard Rock #4 | Shell Shard Alcove #1 | Nothing. |  | Verified | collectible |  |
| Underworks: Shell Shard Rock #5 | Shell Shard Alcove #1 | Nothing. |  | Verified | collectible |  |
| Underworks: Shell Shard Rock #6 | Shell Shard Alcove #1 | Nothing. |  | Verified | collectible |  |
| Underworks: Shell Shard Cache #2 | Shell Shard Alcove #2 | Nothing. |  | Verified | collectible |  |
| Underworks: Shell Shard Cache #3 | Shell Shard Alcove #2 | Nothing. |  | Verified | collectible |  |
| Underworks: Silk Spool Fragment #1 | Silk Spool | Nothing. |  | Verified | collectible |  |
| Underworks: Break Wall #3 (Left) | Silk Spool | Nothing. |  | Verified | blockade |  |

### Underworks Twelfth Architect (Under_17)

**Game ID:** Under_17

#### Subrooms

- One-way Entrance (Top)
- One-way Entrance (Bottom)
- Ground Floor
- Shell Shard Cache
- Left Exit Bottom)
- First Floor
- Needolin Check Guy
- Second Floor
- Left Exit (Top)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| FL | Far Left | Left Exit (Top) | [Underworks East Shaft (Under_13)](#underworks-east-shaft-under13) | TR | Nothing. |  | Verified |  |
| FR | Far Right | Ground Floor | [Underworks Silk Spool (Library_11b)](#underworks-silk-spool-library11b) | L | Nothing. |  | Verified |  |
| BL | Bottom Left | Left Exit Bottom) | [Underworks Clawline Room (Under_18)](#underworks-clawline-room-under18) | TL | Nothing. |  | Verified |  |
| BR | Bottom Right | One-way Entrance (Bottom) | [Underworks Clawline Room (Under_18)](#underworks-clawline-room-under18) | TR | Nothing. |  | Verified |  |
| UP | Upwards | One-way Entrance (Top) | [Whiteward Descent (Ward_06)](#whiteward-descent-ward06) | B | Silk Soar. |  | Verified |  |
| AC | Architect Chapel | Second Floor | [Chapel of the Architect (Under_20)](#chapel-of-the-architect-under20) | L | have Architect's Key |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| GTF | Ground to First | Ground Floor | First Floor | Clawline OR Faydown Cloak AND (Sprint OR Dash OR Sharp Dart OR Scuttlebrace) AND (Cling Grip OR Ledge Grab OR Scuttlebrace) |  | Verified |  |
| FTS | First to Second | First Floor | Second Floor | Silk Soar OR Faydown Cloak AND (Ledge Grab OR Clawline) OR Cling Grip OR Scuttlebrace |  | Verified |  |
| NC | Needolin Check | First Floor | Needolin Check Guy | Silk Soar OR Faydown Cloak AND (Ledge Grab OR Clawline) OR Cling Grip OR Scuttlebrace |  | Verified | same requirements lmao |
| NC | Needolin Check | Needolin Check Guy | First Floor | Nothing. (Fall) |  | Verified |  |
| FTS | First to Second | Second Floor | First Floor | Nothing. (Fall) |  | Verified |  |
| GTF | Ground to First | First Floor | Ground Floor | Nothing. (Fall) |  | Verified |  |
| TE | Top Entrance | One-way Entrance (Top) | Ground Floor | Nothing. (Fall) |  | Verified |  |
| BE | Bottom Entrance | One-way Entrance (Bottom) | Ground Floor | Silk Soar OR Faydown Cloak AND (Ledge Grab OR Clawline) OR Cling Grip OR Scuttlebrace |  | Verified |  |
| TE | Top Entrance | Ground Floor | One-way Entrance (Top) | invalid |  | Verified |  |
| BE | Bottom Entrance | Ground Floor | One-way Entrance (Bottom) | invalid |  | Verified |  |
| CS | Collect Shards | Ground Floor | Shell Shard Cache | Nothing. (Fall) |  | Verified |  |
| CS | Collect Shards | Shell Shard Cache | Ground Floor | Silk Soar OR Faydown Cloak AND (Ledge Grab OR Clawline) OR Cling Grip OR Scuttlebrace |  | Verified | LOTTA this in this room. |
| ESL | Exit Stage Left | Ground Floor | Left Exit Bottom) | Nothing. (Fall) |  | Verified |  |
| ESL | Exit Stage Left | Left Exit Bottom) | Ground Floor | Silk Soar OR Faydown Cloak AND (Ledge Grab OR Clawline) OR Cling Grip OR Scuttlebrace |  | Verified |  |
| OSL | ...Other Stage Left | Left Exit Bottom) | Left Exit (Top) | Silk Soar OR Faydown Cloak AND (Cling Grip OR Scuttlebrace) OR Drifter's Cloak with activated fan |  | Verified |  |
| OSL | ...Other Stage Left | Left Exit (Top) | Left Exit Bottom) | Nothing. (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Shell Shard Cache #4 | Shell Shard Cache | Nothing. |  | Verified | collectible |  |
| Twelfth Architect Pristine Core | First Floor | Nothing. | TODO | Verified | collectible | is this really nothing? - hero, 9/25 |
| Underworks: Needolin Lore #2 | One-way Entrance (Top) | Needolin |  | Verified | lore | futureproofing in case |
| Underworks: Needolin Lore #3 | Needolin Check Guy | Needolin |  | Verified | lore | futureproofing in case |
| Underworks: Flip Switch (Left OR Right) | Left Exit (Top) | Nothing. |  | Verified | switch |  |
| Twelfth Architect: Silkshot | First Floor | have Ruined Tool  AND Craftmetals 1 |  | Verified | collectible |  |
| Twelfth Architect: Cogwork Wheel | First Floor | Craftmetals 1 |  | Verified | collectible |  |
| Twelfth Architect: Sawtooth Circlet | First Floor | Craftmetals 1 |  | Verified | collectible |  |
| Twelfth Architect: Scuttlebrace | First Floor | Craftmetals 1 |  | Verified | collectible |  |
| Twelfth Architect: Crafting Kit | First Floor | Nothing. |  | Verified | collectible |  |
| Twelfth Architect: Architect's Key | First Floor | Tools 25 |  | Verified | collectible |  |

### Underworks Ventrica (Under_22)

**Game ID:** Under_22

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Underworks East Shaft (Under_13)](#underworks-east-shaft-under13) | HL | Nothing. |  | Verified |  |
| V | door_tubeEnter |  | [Ventrica Menu](#ventrica-menu) | UW | unlock Underworks: Ventrica |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Ventrica Rosary Lock |  | Rosaries 80 |  | Verified | lock |  |
| Underworks: Ventrica |  | unlock Underworks: Ventrica Rosary Lock |  | Verified | travel |  |

### Broken Elevator (Under_01b)

**Game ID:** Under_01b

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Grand Elevator (Under_01)](#grand-elevator-under01) | R | none |  |  |  |
| R | right1 |  | [Underworks Shaft (Under_02)](#underworks-shaft-under02) | L1 | none |  |  | one way, opens from this side |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Confession Toll (Under_08)

**Game ID:** Under_08

**Contributors:** samupo

#### Subrooms

- Base
- Top
- Memory
- Secret

- **Secret:** Whiteward entrance?

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Secret | [Whiteward Unravelled Arena Room (Ward_02)](#whiteward-unravelled-arena-room-ward02) | B | none | TODO |  | has to be checked from white ward |
| B | bot1 | Base | [Underworks Below Confession (Under_06)](#underworks-below-confession-under06) | T | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Base to Top | Base | Top | cling grip AND (faydown cloak OR dash OR sharpdart OR drifter's cloak OR ledge grab) OR silk soar |  |  |  |
| V2 | Top To Memory | Top | Memory | faydown cloak OR ledge grab OR silk soar | TODO |  | check cling grip as well when there's no ledge grab |
| F | Top to Base | Top | Base | none |  |  | falling |
| S | Secret to Top | Secret | Top | none | TODO |  | falling |
| S2 | Secret to Memory | Secret | Memory | none | TODO |  | falling |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket: Underworks | Memory | none |  |  | collectible | based on in-game coords, this is named incorrectly - hero, 9/26 |
| Shell Shard Cache: Underworks #15 | Top | none |  |  | collectible |  |
| Relic: Psalm Cylinder (Underworks) | Secret | TBD | TODO |  | collectible |  |

### Underworks Below Confession (Under_06)

**Game ID:** Under_06

**Contributors:** samupo

#### Subrooms

- Center
- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Underworks Western Gauntlet (Under_07)](#underworks-western-gauntlet-under07) | R | none |  |  |  |
| T | top1 | Center | [Confession Toll (Under_08)](#confession-toll-under08) | B | cling grip OR silk soar |  |  |  |
| R | right1 | Right | [Underworks Central Shaft (Under_05)](#underworks-central-shaft-under05) | TL | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LC | Left-Center | Left | Center | spike pogo OR dash OR clawline | TODO |  | Very hard for me to verify |
| LC | Left-Center | Center | Left | spike pogo OR dash OR clawline | TODO |  | Very hard for me to verify |
| RC | Right-Center | Right | Center | spike pogo OR dash OR clawline | TODO |  | Very hard for me to verify |
| RC | Right-Center | Center | Right | spike pogo OR dash OR clawline | TODO |  | Very hard for me to verify |

#### Check Locations

No check locations defined.

### Underworks Map Room (Under_16)

**Game ID:** Under_16

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Underworks Shaft (Under_02)](#underworks-shaft-under02) | L2 | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map Pickup: Underworks |  | none |  | Verified | collectible |  |
| Relic: Bone Scroll (Underworks) |  | none |  | Verified | collectible |  |

### Underworks Outside Choral Chambers (Under_07c)

**Game ID:** Under_07c

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| NF | bot1 |  | [Underworks Western Gauntlet (Under_07)](#underworks-western-gauntlet-under07) | NF | NOT IMPLEMENTED | TODO |  | Haven't found any connection to bottom in Act 2. Maybe Act 3? Maybe a miss from the devs? |
| L | left2 |  | [Underworks Shaft (Under_02)](#underworks-shaft-under02) | R4 | none |  |  |  |
| T | top1 |  | [Choral Chambers Outisde Underworks (Under_07b)](#choral-chambers-outisde-underworks-under07b) | B | cling grip OR silk soar |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Underworks #2 |  | cling grip |  | Verified | collectible |  |
| Rosary Cache: Underworks #3 |  | cling grip |  | Verified | collectible |  |
| Shell Shard Cache: Underworks #14 |  | cling grip AND (dash OR clawline OR sharpdart) |  | Verified | collectible |  |
| Frayed Rosary String: Underworks #1 |  | cling grip |  | Verified | collectible |  |

### Underworks Shaft (Under_02)

**Game ID:** Under_02

**Contributors:** samupo

#### Subrooms

- Underground
- Bottom
- Lever
- Mid
- Top
- Overtop

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R4 | right1 | Overtop | [Underworks Outside Choral Chambers (Under_07c)](#underworks-outside-choral-chambers-under07c) | L | none |  |  |  |
| R3 | right2 | Top | [Underworks Western Gauntlet (Under_07)](#underworks-western-gauntlet-under07) | L | none |  |  |  |
| R2 | right3 | Mid | [Underworks Saw Intro (Under_03b)](#underworks-saw-intro-under03b) | L | none |  |  |  |
| L2 | left3 | Mid | [Underworks Map Room (Under_16)](#underworks-map-room-under16) | R | none |  |  |  |
| L1 | left1 | Bottom | [Broken Elevator (Under_01b)](#broken-elevator-under01b) | R | must be opened from the other side |  |  |  |
| R1 | right4 | Underground | [Underworks Delver's Drill (Under_14)](#underworks-delvers-drill-under14) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Reaching Bottom Lever | Bottom | Lever | silk soar OR (cling grip AND (ledge grab OR faydown cloak OR clawline)) |  |  |  |
| LM | Lever to Mid | Lever | Mid | cling grip OR silk soar |  |  |  |
| TOT | Top to Overtop | Top | Overtop | cling grip OR faydown cloak OR silk soar |  |  |  |
| UG | Coming form Underground | Underground | Bottom | been able to reach top and  (faydown cloak and cling grip) or (silk soar and ((dash and ledge grab) or cling grip or clawline) | TODO |  | Hard to verify because of the difficult geometry |
| UGL | Underground Level | Top | Underground | none |  |  | Hitting the lever will let you go all the way down to the underground |
| FOT | Falling from Overtop | Overtop | Top | none |  |  | falling |
| FT | Falling from Top | Top | Mid | none |  |  | falling |
| FT2 | Falling from Top 2 | Top | Lever | none |  |  | falling. It's not done from Mid, since there would be a wall if you haven't cleared it. |
| FL | Falling from Lever | Lever | Bottom | none |  |  | falling |

#### Check Locations

No check locations defined.

### Underworks Western Gauntlet (Under_07)

**Game ID:** Under_07

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right2 |  | [Underworks Below Confession (Under_06)](#underworks-below-confession-under06) | L | gauntlet |  |  |  |
| NF | top1 |  | [Underworks Outside Choral Chambers (Under_07c)](#underworks-outside-choral-chambers-under07c) | NF | NOT IMPLEMENTED | TODO |  | Not found? Act 3 only? Mistake by the devs? |
| L | left3 |  | [Underworks Shaft (Under_02)](#underworks-shaft-under02) | R3 | gauntlet |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Underworks #1 |  | cling grip OR silk soar OR (faydown cloak AND ledge grab) |  |  | collectible |  |

### Underworks Central Shaft (Under_05)

**Game ID:** Under_05

#### Subrooms

- Wisp Thicket
- Bottom
- Mid
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | left1 | Top | [Underworks Below Confession (Under_06)](#underworks-below-confession-under06) | R | none |  |  |  |
| R | right2 | Mid | [Underworks Rosary Room (Under_12)](#underworks-rosary-room-under12) | L | none |  |  |  |
| BL | left2 | Bottom | [Underworks Crushing Path (Under_04)](#underworks-crushing-path-under04) | R | none |  |  |  |
| BR | right3 | Bottom | [Underworks Eastern Gauntlet (Under_10)](#underworks-eastern-gauntlet-under10) | L | none |  |  |  |
| WT | left3 | Wisp Thicket | [Underworks Wisp Thicket Passage (Under_23)](#underworks-wisp-thicket-passage-under23) | R | none |  |  |  |
| TR | right1 | Top | [Underworks Lever Spike Corridor (Under_11)](#underworks-lever-spike-corridor-under11) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BF | Break Floor | Wisp Thicket | Bottom | cling grip AND (spike pogo OR clawline OR faydown cloak) |  |  |  |
| BM | Bototm to Mid | Bottom | Mid | silk soar OR (cling grip AND (dash OR ledge grab OR faydown cloak OR sharpdart OR clawline OR drifter's cloak) |  |  |  |
| MT | Mid to Top | Mid | Top | silk soar OR cling grip |  |  |  |
| FT | Falling from Top | Top | Mid | none |  |  | falling |
| FM | Falling from Mid | Mid | Bottom | none |  |  | falling |

#### Check Locations

No check locations defined.

### Underworks Crushing Path (Under_04)

**Game ID:** Under_04

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Underworks Saw Shaft (Under_03c)](#underworks-saw-shaft-under03c) | R | dash or clawline | TODO |  | may be other options |
| T | top1 |  | [Underworks Gym (Under_03d)](#underworks-gym-under03d) | B | cling grip | TODO |  | may be other options |
| R | right1 |  | [Underworks Central Shaft (Under_05)](#underworks-central-shaft-under05) | BL | dash or clawline | TODO |  | may be other options |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Underworks |  | cling grip AND (dash OR faydown cloak OR clawline) | TODO |  | collectible | may be other options |

### Underworks Delver's Drill (Under_14)

**Game ID:** Under_14

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Underworks Shaft (Under_02)](#underworks-shaft-under02) | R1 | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Delver's Drill |  | none |  |  | collectible |  |

### Underworks Gym (Under_03d)

**Game ID:** Under_03d

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 |  | [Underworks Crushing Path (Under_04)](#underworks-crushing-path-under04) | T | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Underworks Saw Intro (Under_03b)

**Game ID:** Under_03b

**Contributors:** samupo

#### Subrooms

- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Underworks Shaft (Under_02)](#underworks-shaft-under02) | R2 | none |  |  |  |
| R | right1 | Right | [Underworks Saw Shaft (Under_03c)](#underworks-saw-shaft-under03c) | L2 | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Left | Right | ledge grab OR dash OR clawline OR cling grip |  |  |  |
| H | Horizontal | Right | Left | ledge grab OR dash OR clawline |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Underworks #12 | Left | none |  |  | collectible |  |

### Underworks Saw Shaft (Under_03c)

**Game ID:** Under_03c

**Contributors:** samupo

#### Subrooms

- Top
- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L2 | left1 | Top | [Underworks Saw Intro (Under_03b)](#underworks-saw-intro-under03b) | R | none |  |  |  |
| L1 | left2 | Left | [Underworks Shard Room (Under_03)](#underworks-shard-room-under03) | R | none |  |  |  |
| R | right1 | Right | [Underworks Crushing Path (Under_04)](#underworks-crushing-path-under04) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Left | Right | dash OR clawline OR faydown cloak OR (spike pogo AND ledge grab) OR (drifter's cloak AND ledge grab) |  |  |  |
| H | Horizontal | Right | Left | dash OR clawline OR faydown cloak OR spike pogo OR drifter's cloak |  |  |  |
| V | Vertical | Top | Left | cling grip |  |  |  |
| V | Vertical | Left | Top | cling grip |  |  |  |

#### Check Locations

No check locations defined.

### Underworks Shard Room (Under_03)

**Game ID:** Under_03

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Underworks Saw Shaft (Under_03c)](#underworks-saw-shaft-under03c) | L1 | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shard Bundle: Underworks #1 |  | proficient movement OR dash OR faydown cloak OR drifter's cloak OR spike pogo OR clawline OR sharpdart |  |  | collectible |  |

### Underworks Wisp Thicket Passage (Under_23)

**Game ID:** Under_23

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Underworks Central Shaft (Under_05)](#underworks-central-shaft-under05) | WT | cling grip AND dash |  |  |  |
| B | bot1 |  | [Wisp Thicket Cave (Wisp_09)](#wisp-thicket-cave-wisp09) | T | cling grip AND dash |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Underworks #13 |  | cling grip AND dash |  |  | collectible |  |
| Flea: Underworks - Wisp Thicket Passage |  | cling grip AND dash |  |  | collectible |  |

## Choral Chambers

### High Halls Entrance (Hang_01)

**Game ID:** Hang_01

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BR | right2 |  | [Corridor to High Halls (Song_17)](#corridor-to-high-halls-song17) | L | none |  | Verified |  |
| TP | right1 |  | [High Halls Small Slide (Hang_02)](#high-halls-small-slide-hang02) | L | clawline AND (spike pogo OR faydown cloak) OR silk soar |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Songclave Bellshrine (Bellshrine_Enclave)

**Game ID:** Bellshrine_Enclave

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Songclave (Song_Enclave)](#songclave-songenclave) | D | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bellshrine switch |  |  | TODO |  | switch |  |
| bench |  | activate bellshrine switch |  | Verified | bench |  |

### Songclave (Song_Enclave)

**Game ID:** Song_Enclave

#### Subrooms

- Base
- Top Platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | left2 | Base | [Songclave Steam Tunnel (Library_02)](#songclave-steam-tunnel-library02) | TR | none |  | Verified |  |
| TL | left1 | Top Platform | [Memorium Entrance Tunnel (Song_25)](#memorium-entrance-tunnel-song25) | R | none |  | Verified |  |
| B | bot1 | Base | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | T | none |  | Verified |  |
| T | top1 | Top Platform | [Songclave Tube (Song_Enclave_Tube)](#songclave-tube-songenclavetube) | B | none |  | Verified |  |
| D | door1 | Base | [Songclave Bellshrine (Bellshrine_Enclave)](#songclave-bellshrine-bellshrineenclave) | L | none | TODO | Verified |  |
| WW | wish wall | Base | [Songclave Wish Wall](#songclave-wish-wall) | SC | complete Meet the Caretaker |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Base | Top Platform | silk soar OR cling grip |  | Verified |  |
| V | Vertical | Top Platform | Base | none |  | Verified | falling |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| White Key | Base | none |  |  | collectible |  |
| Wish: Pain, Anguish and Misery | Base | Act 3 AND Defeat Trobbio IN Trobbio |  |  | event |  |
| Meet the Caretaker | Base | activate bellshrine switch IN bellshrine-enclave |  | Verified | logic-point |  |
| Reach Songclave | Base | none |  | Verified | logic-point | Used for Savage Beastfly wish. |

### Choral Chambers Spa (Song_10)

**Game ID:** Song_10

**Contributors:** samupo

#### Subrooms

- Showers
- Spa

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Showers | [Choral Chambers Outside Spa (Song_04)](#choral-chambers-outside-spa-song04) | R2 | none |  | Verified |  |
| R | right1 | Spa | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | BLB | cling grip OR silk soar OR (faydown cloak AND ledge grab) |  | Verified | one way door, opens from this side |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Showers | Spa | cling grip | TODO |  |  |
| H | Horizontal | Spa | Showers | none |  | Verified | lever shortcut |

#### Check Locations

No check locations defined.

### Choral Chambers Outside Spa (Song_04)

**Game ID:** Song_04

**Contributors:** samupo

#### Subrooms

- Base
- Gauntlet
- Left
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Left | [Choral Chambers Above Ventrica (Song_03)](#choral-chambers-above-ventrica-song03) | T | none |  | Verified |  |
| L | left1 | Top | [Slab Bridge (Slab_01)](#slab-bridge-slab01) | R | none |  | Verified |  |
| R1 | right1 | Top | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | BL | none |  | Verified |  |
| R2 | right2 | Base | [Choral Chambers Spa (Song_10)](#choral-chambers-spa-song10) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top | Base | none |  | Verified | falling |
| V | Vertical | Base | Top | cling grip OR silk soar |  | Verified |  |
| GL | Gauntlet Left | Left | Gauntlet | none |  | Verified |  |
| GL | Gauntlet Left | Gauntlet | Left | defeat Gauntlet Fight |  | Verified |  |
| GR | Gauntlet Right | Base | Gauntlet | none |  | Verified |  |
| GR | Gauntlet Right | Gauntlet | Base | defeat Gauntlet Fight |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Gauntlet Fight | Gauntlet | none |  |  | gauntlet |  |
| Heavy Rosary Necklace: Choral Chambers | Base | cling grip OR silk soar |  |  | collectible | Secret hidden by breaking the ceiling |
| Second Sentinel Encounter | Gauntlet | defeat Gauntlet Fight AND Act 2 AND complete THE Second Sentinel Activation |  |  | resource | only act 2 per the wiki |

### Choral Chambers Western Shaft (Song_12)

**Game ID:** Song_12

**Contributors:** samupo

#### Subrooms

- Bottom
- Section 1
- Section 2
- Section 3
- Section 4 Left
- Section 4 Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | left1 | Bottom | [Choral Chambers Outside Spa (Song_04)](#choral-chambers-outside-spa-song04) | R1 | none |  |  |  |
| BR | right3 | Bottom | [Choral Chambers Above Spa (Song_13)](#choral-chambers-above-spa-song13) | L | none |  |  |  |
| S1L | left4 | Section 1 | [Choral Chambers Shop (Song_28)](#choral-chambers-shop-song28) | R | none |  |  |  |
| S2R | right2 | Section 2 | [Choral Chambers Flea Room (Song_14)](#choral-chambers-flea-room-song14) | L | none |  |  |  |
| S3L | left2 | Section 3 | [Choral Chambers Cogheart Room (Song_26)](#choral-chambers-cogheart-room-song26) | R | none |  |  |  |
| S4R | right1 | Section 4 Right | [Choral Chambers Maintenance Tunnel (Song_15)](#choral-chambers-maintenance-tunnel-song15) | L | none |  |  |  |
| S4L | left3 | Section 4 Left | [Choral Chambers Grindle (Song_08)](#choral-chambers-grindle-song08) | R | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Bottom to Section 1 | Bottom | Section 1 | silk soar OR (faydown cloak AND ledge grab) OR (cling grip AND (dash OR faydown cloak OR clawline OR sharpdart)) |  | Verified |  |
| V2 | Section 1 to Section 2 | Section 1 | Section 2 | ledge grab OR silk soar OR faydown cloak OR clawline |  | Verified |  |
| V3 | Section 2 to Section 3 | Section 2 | Section 3 | silk soar OR cling grip OR (faydown cloak AND ledge grab) |  | Verified |  |
| V4L | Section 3 to Section 4 Left | Section 3 | Section 4 Left | cling grip OR (faydown cloak AND ledge grab) |  | Verified |  |
| V4R | Section 3 to Section 4 Right | Section 3 | Section 4 Right | spike pogo OR silk soar OR (faydown cloak AND ledge grab) |  | Verified |  |
| S4 | Section 4 traversal | Section 4 Left | Section 4 Right | clawline OR drifter's cloak OR dash OR faydown cloak OR sharpdart |  | Verified |  |
| S4 | Section 4 traversal | Section 4 Right | Section 4 Left | clawline OR drifter's cloak OR dash OR faydown cloak OR sharpdart |  | Verified |  |
| F4L | Section 4 Left falling | Section 4 Left | Section 3 | none |  | Verified | falling |
| F4R | Section 4 Right falling | Section 4 Right | Section 3 | none |  | Verified | falling |
| F3 | Section 3 Falling | Section 3 | Section 2 | none |  | Verified | falling |
| F2 | Section 2 Falling | Section 2 | Section 1 | none |  | Verified | falling |
| F1 | Section 1 Falling | Section 1 | Bottom | none |  | Verified | falling |

#### Check Locations

No check locations defined.

### Choral Chambers Shop (Song_28)

**Game ID:** Song_28

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | S1L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Choral Chambers Cogheart Room (Song_26)

**Game ID:** Song_26

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | S3L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Choral Chambers Cogheart Piece |  | flip switch up OR flip switch down |  | Verified | collectible | memory puzzle |

### Choral Chambers Grindle (Song_08)

**Game ID:** Song_08

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | S4L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Choral Chambers Flea Room (Song_14)

**Game ID:** Song_14

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | S2R | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Choral Chambers - Spa |  | none |  | Verified | collectible |  |

### Choral Chambers Above Spa (Song_13)

**Game ID:** Song_13

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | BLT | none |  | Verified |  |
| L | left1 |  | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | BR | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Choral Chambers Maintenance Tunnel (Song_15)

**Game ID:** Song_15

**Contributors:** samupo

#### Subrooms

- Base
- Maintenance Tunnel

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Base | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | S2L | none |  | Verified |  |
| L | left1 | Maintenance Tunnel | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | S4R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Base | Maintenance Tunnel | silk soar |  |  |  |
| V | Vertical | Maintenance Tunnel | Base | silk soar OR cling grip |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Choral Chambers #17 | Base | none |  |  | collectible |  |
| Rosary Cache: Choral Chambers #18 | Base | none |  |  | collectible |  |
| Rosary Cache: Choral Chambers #19 | Base | none |  |  | collectible |  |

### Choral Chambers Flea Shaft (Song_11)

**Game ID:** Song_11

**Contributors:** samupo

#### Subrooms

- Base Bottom
- Base Upper
- Top Section 1
- Top Section 2
- Top Section 3 Left
- Top Section 3 Right

- **Base Bottom:** Base Isolated from Top by one-way door available on Top
- **Base Upper:** Base Isolated from Top by one-way door available on Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S3L | left1 | Top Section 3 Left | [Corridor to High Halls (Song_17)](#corridor-to-high-halls-song17) | R | none |  |  |  |
| S2L | left2 | Top Section 2 | [Choral Chambers Maintenance Tunnel (Song_15)](#choral-chambers-maintenance-tunnel-song15) | R | none |  |  |  |
| S3R | right2 | Top Section 3 Right | [High Halls Corridor (Hang_07)](#high-halls-corridor-hang07) | L | ledge grab OR faydown cloak OR cling grip OR silk soar |  |  |  |
| BLB | left4 | Base Upper | [Choral Chambers Spa (Song_10)](#choral-chambers-spa-song10) | R | breakable wall -must be opened from the other side |  |  |  |
| BR | right3 | Base Bottom | [Choral Chambers Eastern Shaft (Song_05)](#choral-chambers-eastern-shaft-song05) | L3 | none |  |  |  |
| BLT | left3 | Base Upper | [Choral Chambers Above Spa (Song_13)](#choral-chambers-above-spa-song13) | R | none |  |  |  |
| S1R | right1 | Top Section 1 | [Choral Chambers Dining Room (Song_09b)](#choral-chambers-dining-room-song09b) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VB | Vertical Base | Base Bottom | Base Upper | silk soar faydown cloak OR (cling grip AND ((dash AND ledge grab) OR (drifter's cloak AND ledge grab) OR clawline)) |  |  |  |
| VB | Vertical Base | Base Upper | Base Bottom | none |  |  | falling |
| VL | Vertical Lever | Top Section 1 | Base Upper | none |  |  | one way, falling |
| V1 | Section 1 to Section 2 | Top Section 1 | Top Section 2 | silk soar OR cling grip OR (faydown cloak AND ledge grab) |  |  |  |
| V2L | Section 2 to Section 3 Left | Top Section 2 | Top Section 3 Left | silk soar AND (ledge grab OR clawline OR dash OR sharpdart OR faydown cloak) |  |  |  |
| V3R | Section 2 to Section 3 Right | Top Section 2 | Top Section 3 Right | silk soar OR (cling grip AND (clawline OR dash)) |  |  |  |
| F3L | Section 3 Right falling | Top Section 3 Right | Top Section 2 | none |  |  | falling |
| F3R | Section 3 Left falling | Top Section 3 Left | Top Section 2 | none |  |  | falling |
| F2 | Section 2 falling | Top Section 2 | Top Section 1 | none |  |  | falling |
| H | Top Horizontal Traversal | Top Section 3 Right | Top Section 3 Left | ledge grab OR clawline OR drifter's cloak | TODO |  | check sharpdart |
| H | Top Horizontal Traversal | Top Section 3 Left | Top Section 3 Right | ledge grab OR clawline OR cling grip |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Choral Chambers - Walled Room | Top Section 2 | (cling grip AND drifter's cloak) OR silk soar |  |  | collectible |  |
| Rosary Cache: Choral Chambers #14 | Base Upper | clawline OR faydown cloak OR (dash AND ledge grab) | TODO |  | collectible | check, probably better to split Base Upper into two zones since they can be gotten from BLT easier than from BLB |
| Rosary Cache: Choral Chambers #15 | Base Upper | clawline OR faydown cloak OR (dash AND ledge grab) | TODO |  | collectible | check, probably better to split Base Upper into two zones since they can be gotten from BLT easier than from BLB |
| Rosary Cache: Choral Chambers #16 | Base Upper | clawline OR faydown cloak OR (dash AND ledge grab) | TODO |  | collectible | check, probably better to split Base Upper into two zones since they can be gotten from BLT easier than from BLB |

### High Halls Corridor (Hang_07)

**Game ID:** Hang_07

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | S3R | one way entrance, opens from the other side |  | Verified | one way entrance, opens from the other side |
| R | right1 |  | [Cog Dancers (Cog_Dancers)](#cog-dancers-cogdancers) | L | none |  | Verified |  |
| B | bot1 |  | [Choral Chambers Over Dininig (Song_09)](#choral-chambers-over-dininig-song09) | T | none |  | Verified |  |
| T | top1 |  | [High Halls Vault (Hang_06)](#high-halls-vault-hang06) | B | one way entrance, opens from the other side |  | Verified | one way entrance, opens from the other side |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Corridor to High Halls (Song_17)

**Game ID:** Song_17

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | S3L |  |  |  |  |
| L | left1 |  | [High Halls Entrance (Hang_01)](#high-halls-entrance-hang01) | BR |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Choral Chambers Over Dininig (Song_09)

**Game ID:** Song_09

**Contributors:** samupo

#### Subrooms

- Top
- Base
- Right Secret

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right Secret | [Cogwork Core West Gauntlet (Cog_05)](#cogwork-core-west-gauntlet-cog05) | L | none |  |  |  |
| T | top1 | Top | [High Halls Corridor (Hang_07)](#high-halls-corridor-hang07) | B | none |  |  |  |
| B | bot1 | Base | [Choral Chambers Dining Room (Song_09b)](#choral-chambers-dining-room-song09b) | T | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top | Base | none |  |  | falling |
| V | Vertical | Base | Top | cling grip OR faydown cloak OR silk soar | TODO |  | Needs checking |
| S | Secret | Right Secret | Base | none |  |  | one way door |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Choral Chambers #11 | Top | none |  |  | collectible | falling |
| Rosary Cache: Choral Chambers #12 | Top | none |  |  | collectible | falling |
| Rosary Cache: Choral Chambers #13 | Top | none |  |  | collectible | falling |
| Mask Shard: Cogwork Core | Right Secret | none |  |  | collectible |  |

### Choral Chambers Dining Room (Song_09b)

**Game ID:** Song_09b

**Contributors:** samupo

#### Subrooms

- Diner
- Below Diner

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Diner | [Choral Chambers Over Dininig (Song_09)](#choral-chambers-over-dininig-song09) | B | ledge grab OR clawline OR faydown cloak OR silk soar |  |  |  |
| L | left1 | Below Diner | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | S1R | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Diner | Below Diner | none |  |  | one way levers |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silkeater: Choral Chambers East | Below Diner | ledge grab OR silk soar OR cling grip OR faydown cloak | TODO |  | collectible | Check |
| Great Taste of Pharloom Wish Promised | Diner | Act 2 |  | Verified | event | wiki says "act 2" is the only prereq |

### Choral Chambers Eastern Shaft (Song_05)

**Game ID:** Song_05

#### Subrooms

- Section 1
- Section 2
- Section 3
- Section 4

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L1 | left5 | Section 1 | [Choral Chambers Below Spa (Song_02)](#choral-chambers-below-spa-song02) | R | none |  | Verified |  |
| R1 | right3 | Section 1 | [Whiteward Entrance (Ward_01)](#whiteward-entrance-ward01) | TL | none |  | Verified |  |
| L2 | left4 | Section 3 | [Choral Chambers Merchant Room (Song_07)](#choral-chambers-merchant-room-song07) | R | none |  | Verified |  |
| R2 | right4 | Section 2 | [Choral Chambers East to West (Song_27)](#choral-chambers-east-to-west-song27) | L | activate door switch IN choral chambers east to west |  | Verified |  |
| L3 | left3 | Section 3 | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | BR | none |  | Verified |  |
| R4 | right2 | Section 4 | [Choral Chambers Below Dining (Song_18)](#choral-chambers-below-dining-song18) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Section 1 to Section 2 | Section 1 | Section 2 | (ledge grab AND pogo) OR silk soar OR (cling grip AND (dash OR clawline)) |  |  |  |
| V2 | Section 2 to Section 3 | Section 2 | Section 3 | silk soar OR (cling grip AND (ledge grab OR clawline)) OR faydown cloak |  |  |  |
| V3 | Section 3 to Section 4 | Section 3 | Section 4 | ((ledge grab OR clawline) AND pogo) OR silk soar |  |  |  |
| F4 | Falling from Section 4 | Section 4 | Section 3 | none |  |  | falling |
| F3 | Falling from Section 3 | Section 3 | Section 2 | none |  |  | falling |
| F2 | Falling from Section 2 | Section 2 | Section 1 | none |  |  | falling |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lace Second Encounter | Section 1 | none |  | Verified | event |  |

### Choral Chambers Merchant Room (Song_07)

**Game ID:** Song_07

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Choral Chambers Eastern Shaft (Song_05)](#choral-chambers-eastern-shaft-song05) | L2 | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Choral Chambers #10 |  | cling grip |  | Verified | collectible |  |
| The Wandering Merchant Wish Granted |  | complete THE The Wandering Merchant Wish Promised |  |  | event |  |
| Second Sentinel Encounter |  | Act 3  AND complete THE Second Sentinel Activation AND complete The Wandering Merchant Wish Granted |  |  | event | per the wiki |

### Choral Chambers Below Dining (Song_18)

**Game ID:** Song_18

**Contributors:** samupo

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Top | [Choral Chambers Eastern Shaft (Song_05)](#choral-chambers-eastern-shaft-song05) | R4 | none |  |  |  |
| B | bot1 | Bottom | [Choral Chambers East to West (Song_27)](#choral-chambers-east-to-west-song27) | T | none |  |  | one way only, cannot be traversed from the other side |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top | Bottom | none |  |  | falling |
| V | Vertical | Bottom | Top | silk soar OR cling grip |  |  |  |

#### Check Locations

No check locations defined.

### Choral Chambers Below Spa (Song_02)

**Game ID:** Song_02

**Contributors:** samupo

#### Subrooms

- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right | [Choral Chambers Eastern Shaft (Song_05)](#choral-chambers-eastern-shaft-song05) | L1 | none |  |  |  |
| L | left2 | Left | [Choral Chambers Ventrica Room (Song_01b)](#choral-chambers-ventrica-room-song01b) | R | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Right | Left | cling grip OR silk soar |  |  |  |
| H | Horizontal | Left | Right | ledge grab OR faydown cloak OR silk soar |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Second Sentinel Encounter | Right | Act 3 AND  complete THE Second Sentinel Activation | TODO | Needs verification | event | Random. Need to verify it is on this side |

### Choral Chambers Above Ventrica (Song_03)

**Game ID:** Song_03

**Contributors:** samupo

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom | [Choral Chambers Ventrica Room (Song_01b)](#choral-chambers-ventrica-room-song01b) | T | none |  |  |  |
| T | top1 | Top | [Choral Chambers Outside Spa (Song_04)](#choral-chambers-outside-spa-song04) | B | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top | Bottom | none |  |  | falling |
| V | Vertical | Bottom | Top | silk soar OR (cling grip AND (faydown cloak OR clawline OR dash)) OR (faydown cloak AND ledge grab) |  |  |  |

#### Check Locations

No check locations defined.

### Choral Chambers Ventrica Room (Song_01b)

**Game ID:** Song_01b

**Contributors:** samupo

#### Subrooms

- Ventrica
- Lateral

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Lateral | [Choral Chambers Below Spa (Song_02)](#choral-chambers-below-spa-song02) | L | none |  |  |  |
| T | top1 | Ventrica | [Choral Chambers Above Ventrica (Song_03)](#choral-chambers-above-ventrica-song03) | B | cling grip OR silk soar OR faydown cloak |  |  |  |
| B | bot1 | Lateral | [Choral Chambers Below Ventrica (Song_01)](#choral-chambers-below-ventrica-song01) | T | none |  |  |  |
| V | door_tubeEnter | Ventrica | [Ventrica Menu](#ventrica-menu) | CC | unlock Ventrica: Choral Chambers |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Ventrica | Lateral | none |  |  | one way door |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map Purchase: Choral Chambers | Lateral | rosaries 70 |  |  | collectible | one of two possible locations - hero, 9/26 |
| Rosary Cache: Choral Chambers #5 | Ventrica | none |  |  | collectible |  |
| Rosary Cache: Choral Chambers #6 | Ventrica | none |  |  | collectible |  |
| Rosary Cache: Choral Chambers #7 | Ventrica | none |  |  | collectible |  |
| Ventrica: Choral Chambers | Ventrica | Unlock Ventrica: Choral Chambers Rosary Lock |  |  | travel |  |
| Ventrica: Choral Chambers Rosary Lock | Ventrica | rosaries 80 |  |  | lore |  |

### Choral Chambers Below Ventrica (Song_01)

**Game ID:** Song_01

**Contributors:** samupo

#### Subrooms

- Bottom
- Window
- Right Exit
- Side Chamber
- Pre Top
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom | [Grand Gate Maintenance Room (Song_01c)](#grand-gate-maintenance-room-song01c) | T | none |  |  |  |
| T | top1 | Top | [Choral Chambers Ventrica Room (Song_01b)](#choral-chambers-ventrica-room-song01b) | B | cling grip or silk soar |  |  |  |
| R | right2 | Right Exit | [Choral Chambers Outisde Underworks (Under_07b)](#choral-chambers-outisde-underworks-under07b) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Pre Top to Top | Pre Top | Top | cling grip or faydown cloak |  |  |  |
| V2 | Side Chamber to Top | Side Chamber | Top | silk soar or cling grip |  |  |  |
| V3 | Window to Side Chamber | Window | Side Chamber | silk soar or cling grip |  |  |  |
| V4 | Bottom to Window | Bottom | Window | (cling grip and (ledge grab or clawline or faydown cloak)) or silk soar |  |  |  |
| V5 | Bottom to Right Exit | Bottom | Right Exit | faydown cloak or (cling grip and (ledge grab or clawline)) or silk soar |  |  |  |
| FT | Falling from Top | Top | Pre Top | none |  |  | falling |
| FPT | Falling from Pre Top | Pre Top | Side Chamber | none |  |  | falling |
| LV | Lever | Window | Right Exit | none |  |  | one side lever |
| SW | Side Chamber to Window | Side Chamber | Window | none |  |  |  |
| FW | Falling from Window | Window | Bottom | none |  |  | falling |
| FR | Falling from Right Exit | Right Exit | Bottom | none |  |  | falling |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Choral Chambers #3 | Pre Top | none |  |  |  |  |
| Rosary Cache: Choral Chambers #4 | Pre Top | none |  |  |  |  |
| Shell Shard Cache: Choral Chambers | Side Chamber | none |  |  |  |  |
| Rosary Cache: Choral Chambers #1 | Window | none |  |  |  |  |
| Rosary Cache: Choral Chambers #2 | Window | none |  |  |  |  |

### Choral Chambers Outisde Underworks (Under_07b)

**Game ID:** Under_07b

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 |  | [Underworks Outside Choral Chambers (Under_07c)](#underworks-outside-choral-chambers-under07c) | T | Only opened from the other side |  |  |  |
| L | left1 |  | [Choral Chambers Below Ventrica (Song_01)](#choral-chambers-below-ventrica-song01) | R | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Songclave Tube (Song_Enclave_Tube)

**Game ID:** Song_Enclave_Tube

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 |  | [Songclave (Song_Enclave)](#songclave-songenclave) | T | none |  | Verified |  |
| V | door_tubeEnter |  | [Ventrica Menu](#ventrica-menu) | FS | unlock Ventrica: First Shrine |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Ventrica: First Shrine Rosary Lock |  | rosaries 80 |  | Verified | lock |  |
| Ventrica: First Shrine |  | unlock Ventrica: First Shrine Rosary Lock |  | Verified | travel |  |

### Memorium Entrance Tunnel (Song_25)

**Game ID:** Song_25

**Contributors:** samupo, heric

#### Subrooms

- Base
- Secret Platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | top2 | Secret Platform | [Cogwork Core Breakable Walls (Cog_10_Destroyed)](#cogwork-core-breakable-walls-cog10destroyed) | B | none | TODO |  |  |
| L | left1 | Base | [Cog Dancers (Cog_Dancers)](#cog-dancers-cogdancers) | R | none |  | Verified |  |
| T | top1 | Base | [Memorium Start Shaft (Arborium_01)](#memorium-start-shaft-arborium01) | B | (silk soar OR faydown cloak) |  | Verified |  |
| R | right1 | Base | [Songclave (Song_Enclave)](#songclave-songenclave) | TL | none |  | Verified |  |
| B | bot1 | Base | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | T | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical Secret | Base | Secret Platform | act 3 AND silk soar | TODO |  | NEEDS LOGIC, PROBABLY ACT 3 ONLY |
| V | Vertical Secret | Secret Platform | Base | none | TODO |  | Not verified, most likely falling |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memorium entrance vines | Base | (silk soar OR faydown cloak) AND break wall up |  | Verified | blockade | one way wall and also logic can be improved for more skips |
| Second Sentinel Encounter | Base | complete THE Second Sentinel Activation |  | Verified | event |  |

### Rotating Tunnel (Song_20b)

**Game ID:** Song_20b

**Contributors:** samupo

#### Subrooms

- Top Platform
- Central Area
- Bottom Area
- Horizontal Tunnel

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Top Platform | [Memorium Entrance Tunnel (Song_25)](#memorium-entrance-tunnel-song25) | B | none |  | Verified |  |
| L1 | left2 | Central Area | [Songclave Silk Shop (Song_29)](#songclave-silk-shop-song29) | R | ledge grab OR dash OR faydown cloak OR clawline OR sharpdart OR drifter's cloak OR silk soar OR easy enemy pogo |  | Verified |  |
| R1 | right2 | Central Area | [Songclave Steam Tunnel (Library_02)](#songclave-steam-tunnel-library02) | TL | none |  | Verified |  |
| B | bot1 | Bottom Area | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | T | none |  | Verified |  |
| RH | right3 | Horizontal Tunnel | [Songclave Steam Tunnel (Library_02)](#songclave-steam-tunnel-library02) | BL | none |  | Verified | both sides have levers making the tunnel horizontal |
| LH | left4 | Horizontal Tunnel | [Cogwork Core East Choral Entrance (Cog_06)](#cogwork-core-east-choral-entrance-cog06) | R | none |  | Verified | both sides have levers making the tunnel horizontal |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top Platform | Central Area | none |  | Verified | falling, door on top platform's side (no inverse) |
| T | Tunnel | Central Area | Bottom Area | none |  | Verified | falling, both sides have levers making the tunnel vertical |
| T | Tunnel | Bottom Area | Central Area | silk soar OR cling grip |  | Verified | both sides have levers making the tunnel vertical |

#### Check Locations

No check locations defined.

### Songclave Silk Shop (Song_29)

**Game ID:** Song_29

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | L1 | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Grand Bellway Shaft (Song_20)

**Game ID:** Song_20

**Contributors:** samupo

#### Subrooms

- Top
- Upper Right
- Upper Left
- Right Stage
- Bottom Left
- Bottom Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | Upper Left | [Choral Chambers East to West (Song_27)](#choral-chambers-east-to-west-song27) | R | none |  |  |  |
| T | top1 | Top | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | B | none |  |  |  |
| UR | right4 | Upper Right | [Grand Bellway Library (Library_03)](#grand-bellway-library-library03) | L | none |  |  |  |
| RS | right5 | Right Stage | [Trobbio (Library_13)](#trobbio-library13) | L | none |  |  |  |
| BR | right6 | Bottom Right | [Grand Bellway (Bellway_City)](#grand-bellway-bellwaycity) | L | none |  |  |  |
| BL | left2 | Bottom Left | [Grand Bellway Side Room (Song_24)](#grand-bellway-side-room-song24) | R | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| F1 | Top to Upper Right | Top | Upper Right | none |  | Verified | falling |
| F2 | Upper Right to Upper Left | Upper Right | Upper Left | none |  | Verified | falling |
| F3 | Upper Left to Right Stage | Upper Left | Right Stage | none |  | Verified | falling |
| F4 | Right Stage to Bottom Left | Right Stage | Bottom Left | none |  | Verified | falling |
| F5 | Bottom Left to Bottom Right | Bottom Left | Bottom Right | none |  | Verified | falling |
| J5 | Bottom Right to Bottom Left | Bottom Right | Bottom Left | silk soar OR cling grip |  | Verified | Might be able to use enemy pogo and faydown cloak |
| J4 | Bottom Left to Right Stage | Bottom Left | Right Stage | cling grip OR silk soar |  | Verified |  |
| J3 | Right Stage to Upper Left | Right Stage | Upper Left | cling grip OR silk soar |  | Verified |  |
| J3E | Bottom Right to Upper Left | Bottom Right | Upper Left | silk soar |  | Verified |  |
| J2 | Upper Left to Upper Right | Upper Left | Upper Right | (cling grip AND (faydown cloak OR swift step OR clawline)) OR silk soar |  | Verified |  |
| J1 | Upper Right to Top | Upper Right | Top | ledge grab OR silk soar OR clawline OR faydown cloak |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lace Second Encounter | Bottom Right | none |  | Verified | event |  |

### Grand Bellway Side Room (Song_24)

**Game ID:** Song_24

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | BL | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silkeater: Choral Chambers West |  | spike pogo OR dash OR clawline OR faydown cloak OR sharpdart OR drifter's cloak OR cling grip |  | Verified | collectible |  |
| Second Sentinel Encounter |  | Act 3  AND complete THE Second Sentinel Activation | TODO | Needs verification | event | need to verify this is the room the wiki is referring to |

### Grand Bellway (Bellway_City)

**Game ID:** Bellway_City

**Contributors:** samupo

#### Subrooms

- Base
- Secret Tunnel

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Secret Tunnel | [Vaults & Bellway Cauldron Entrance (Library_11)](#vaults-bellway-cauldron-entrance-library11) | HL |  | TODO |  |  |
| L | left1 | Base | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | BR | none |  | Verified |  |
| BW | door_fastTravelExit | Base | [Bellway Menu](#bellway-menu) | GB | unlock Bellway: Grand Bellway |  | Verified |  |
| VT | door_tubeEnter | Base | [Ventrica Menu](#ventrica-menu) | GB | unlock Ventrica: Grand Bellway |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Secret Tunnel | Base | none |  |  | falling, one sided door |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket: Choral Chambers | Secret Tunnel | none |  | Verified | collectible | breakable wall |
| Map Purchase: Choral Chambers | Base | rosaries 70 |  | Verified | collectible | one of two possible locations - hero, 9/26 |
| Ventrica: Grand Bellway Rosary Lock | Base | rosaries 80 |  | Verified | lock |  |
| Ventrica: Grand Bellway | Base | Unlock Ventrica: Grand Bellway Rosary Lock |  | Verified | travel |  |
| Bellway: Grand Bellway Rosary Lock | Base | rosaries 80 |  | Verified | lock |  |
| Bellway: Grand Bellway | Base | Unlock Bellway Grand Bellway Rosary Lock |  | Verified | travel |  |

### Choral Chambers East to West (Song_27)

**Game ID:** Song_27

**Contributors:** samupo

#### Subrooms

- Left Side
- Right Side

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Left Side | [Choral Chambers Below Dining (Song_18)](#choral-chambers-below-dining-song18) | B | One way, can't be used at all from this side even if you entered from it! | TODO |  | One way, can't be used at all from this side even if you entered from it! |
| R | right1 | Right Side | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | UL |  | TODO |  |  |
| L | left1 | Left Side | [Choral Chambers Eastern Shaft (Song_05)](#choral-chambers-eastern-shaft-song05) | R2 | activate door switch |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Left Side | Right Side | clawline OR ledge grab OR faydown cloak OR spike pogo |  | Verified |  |
| H | Horizontal | Right Side | Left Side | clawline OR ledge grab OR faydown cloak OR spike pogo |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| door switch | Left Side | flip switch left |  | Verified | switch |  |
| Second Sentinel Encounter | Right Side | complete THE Second Sentinel Activation | TODO | Needs verification | event | Random. Need to verify it is on this side |

#### Notes

Door on the east can be only opened from the west

## Cogwork Core

### Cog Dancers (Cog_Dancers)

**Game ID:** Cog_Dancers

**Contributors:** samupo

#### Subrooms

- BaseLeft
- Top
- BaseRight
- BossArena

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | BaseRight | [Memorium Entrance Tunnel (Song_25)](#memorium-entrance-tunnel-song25) | L | none |  | Verified |  |
| L | left1 | BaseLeft | [High Halls Corridor (Hang_07)](#high-halls-corridor-hang07) | R | none |  | Verified |  |
| B1 | bot1 | BossArena | [Cogwork Core South Main (Cog_04)](#cogwork-core-south-main-cog04) | TL | Defeat Cogwork Dancers Boss Fight |  | Verified |  |
| B2 | bot2 | BossArena | [Cogwork Core South Main (Cog_04)](#cogwork-core-south-main-cog04) | TR | Defeat Cogwork Dancers Boss Fight |  | Verified |  |
| E | elevator | BossArena | [Lace 2 Fight (Song_Tower_01)](#lace-2-fight-songtower01) | D |  | TODO |  | TODO: Check all that's needed for the elevator to work |
| D | door1 | Top | [Cogwork Core Main Connection (Cog_Pass)](#cogwork-core-main-connection-cogpass) | TL | Nothing. |  |  | TODO |
| T | top1 | Top | [Cogwork Core North Main (Cog_08)](#cogwork-core-north-main-cog08) | B | clawline |  |  | probably one way |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | BossArena | Top | Defeat Cogwork Dancers Boss Fight AND Silk Soar |  | Verified |  |
| V | Vertical | Top | BossArena | Nothing | TODO |  | falling, check if dancers boss is required on a new save |
| R | RightSide | BaseRight | BossArena | none |  | Verified |  |
| R | RightSide | BossArena | BaseRight | Defeat Cogwork Dancers Boss Fight |  | Verified |  |
| L | LeftSide | BossArena | BaseLeft | Defeat Cogwork Dancers Boss Fight |  | Verified |  |
| L | LeftSide | BaseLeft | BossArena | Nothing |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Dancers Boss Fight | BossArena | Nothing | TODO | Verified | boss |  |
| Play Threefold Melody | BossArena | defeat Cogwork Dancers Boss Fight AND threefold melody parts 3 |  | Verified | logic-point | Used in Liquid Lacquer wish requirements per the wiki. |

#### Notes

Boss needs only any crest to be beatable. The big line attack can be parried with appropriate timing.

### Cogwork Core Architect's Melody (Cog_09)

**Game ID:** Cog_09

**Contributors:** Rebel

#### Subrooms

- Bottom
- Melody Puzzle

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom | [Cogwork Core North Main (Cog_08)](#cogwork-core-north-main-cog08) | T | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TP | To Puzzle | Bottom | Melody Puzzle | Silk Soar OR Cling Grip OR (Faydown Cloak AND Scuttlebrace) |  | Verified |  |
| TP | To Puzzle | Melody Puzzle | Bottom | Nothing. (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Architect's Melody | Melody Puzzle | Nothing (?) |  | Verified | event | ??????????????????????? |

### Cogwork Core Architect's Melody (Act 3) (Cog_09_Destroyed)

**Game ID:** Cog_09_Destroyed

**Contributors:** Rebel

#### Subrooms

- Bottom
- Center
- Silk Soar Ceiling
- Top Entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Bottom | [Cogwork Core Breakable Walls (Cog_10_Destroyed)](#cogwork-core-breakable-walls-cog10destroyed) | L | Nothing. |  | Verified |  |
| T | top1 | Top Entrance | [ACT3 Lace2 Arena (Song_Tower_Destroyed)](#act3-lace2-arena-songtowerdestroyed) | F | Nothing. | TODO | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BC | Bottom-Center | Bottom | Center | Silk Soar OR (Faydown Cloak AND Cling Grip) |  | Verified |  |
| BC | Bottom-Center | Center | Bottom | Nothing. (Fall) |  | Verified |  |
| CSE | Center-Silk Soar Entrance | Center | Silk Soar Ceiling | Silk Soar |  | Verified |  |
| CSE | Center-Silk Soar Entrance | Silk Soar Ceiling | Center | Nothing. (Fall) |  | Verified |  |
| STE | Soar Ceiling-Top Entrance | Silk Soar Ceiling | Top Entrance | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| STE | Soar Ceiling-Top Entrance | Top Entrance | Silk Soar Ceiling | Nothing. (Fall) |  | Verified |  |

#### Check Locations

No check locations defined.

### Cogwork Core Bench & Map (Cog_Bench)

**Game ID:** Cog_Bench

**Contributors:** Rebel

#### Subrooms

- Bench
- Map

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Map | [Cogwork Core South Main (Cog_04)](#cogwork-core-south-main-cog04) | DL | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BM | Bench-Map | Bench | Map | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| BM | Bench-Map | Map | Bench | Nothing. (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Flip Switch #4 | Bench | Nothing. |  | Verified | switch |  |
| Cogwork Core: Flip Switch #5 | Map | Nothing. |  | Verified | switch |  |
| Cogwork Core: Map | Map | Activate Cogwork Core: Flip Switch #5 |  | Verified | collectible |  |
| Cogwork Core: Bench | Bench | Activate Cogwork Core: Flip Switch #4 |  | Verified | bench |  |

### Cogwork Core Breakable Walls (Cog_10_Destroyed)

**Game ID:** Cog_10_Destroyed

**Contributors:** Rebel

#### Subrooms

- Top Entrance
- Steam Shaft
- Center Shaft
- Northern Gauntlet
- Southern Shaft
- Breakable Wall Shaft
- Spike Platform
- Bottom Entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom Entrance | [Memorium Entrance Tunnel (Song_25)](#memorium-entrance-tunnel-song25) | TL | Nothing. |  | Verified |  |
| L | left1 | Top Entrance | [Cogwork Core Architect's Melody (Act 3) (Cog_09_Destroyed)](#cogwork-core-architects-melody-act-3-cog09destroyed) | R | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ESH | Top Entrance-Steam Shaft | Top Entrance | Steam Shaft | (Activate Cogwork Core: Break Wall #3 AND (Dash OR Drifter's Cloak OR Faydown Cloak OR Sharpdart OR Clawline OR Scuttlebrace OR Cling Grip)) |  | Verified |  |
| ESH | Top Entrance-Steam Shaft | Steam Shaft | Top Entrance | (Activate Cogwork Core: Break Wall #3 AND (Silk Soar OR (Faydown Cloak AND (Scuttlebrace OR (Ledge Grab AND Clawline AND Cling Grip))))) |  | Verified |  |
| SCS | Steam Shaft-Center Shaft | Steam Shaft | Center Shaft | Activate Cogwork Core: Break Wall #4 |  | Verified |  |
| SCS | Steam Shaft-Center Shaft | Center Shaft | Steam Shaft | (Activate Cogwork Core: Break Wall #4 AND (Silk Soar OR Cling Grip OR (Scuttlebrace AND Faydown Cloak))) |  | Verified |  |
| SNG | Center Shaft-Northern Gauntlet | Center Shaft | Northern Gauntlet | Activate Cogwork Core: Break Wall #5 |  | Verified |  |
| SNG | Center Shaft-Northern Gauntlet | Northern Gauntlet | Center Shaft | Activate Cogwork Core: Break Wall #5 AND Silk Soar AND Faydown Cloak |  | Verified |  |
| GSS | Northern Gauntlet-Southern Shaft | Northern Gauntlet | Southern Shaft | Complete Cogwork Core: Gauntlet #3 |  | Verified |  |
| GSS | Northern Gauntlet-Southern Shaft | Southern Shaft | Northern Gauntlet | (Complete Cogwork Core: Gauntlet #3 AND (Silk Soar OR (Cling Grip AND Faydown Cloak))) |  | Verified |  |
| SWS | Southern Shaft-Wall Shaft | Southern Shaft | Breakable Wall Shaft | Activate Cogwork Core: Break Wall #6 |  | Verified |  |
| SWS | Southern Shaft-Wall Shaft | Breakable Wall Shaft | Southern Shaft | (Activate Cogwork Core: Break Wall #6 AND (Cling Grip OR Faydown Cloak)) |  | Verified |  |
| WSP | Breakable Wall Shaft-Spike Platform | Breakable Wall Shaft | Spike Platform | Activate Cogwork Core: Break Wall #7 |  | Verified |  |
| WSP | Breakable Wall Shaft-Spike Platform | Spike Platform | Breakable Wall Shaft | (Activate Cogwork Core: Break Wall #7 AND (Dash OR Faydown Cloak OR Drifter's Cloak OR Cling Grip OR Sharpdart OR Clawline OR Scuttlebrace OR Ledge Grab)) |  | Verified |  |
| SPE | Spike Platform-Bottom Entrance | Spike Platform | Bottom Entrance | Nothing. (Fall) |  | Verified |  |
| SPE | Spike Platform-Bottom Entrance | Bottom Entrance | Spike Platform | (Scuttlebrace AND (Spike Pogo OR Dash)) OR Cling Grip OR (Faydown Cloak AND (Spike Pogo OR Clawline)) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Break Wall #3 | Steam Shaft | Break Wall Left OR Break Wall Right |  | Verified | blockade |  |
| Cogwork Core: Break Wall #4 | Steam Shaft | Break Wall Left OR Break Wall Right |  | Verified | blockade |  |
| Cogwork Core: Break Wall #5 | Center Shaft | Break Wall Down |  | Verified | blockade | Can't be broken from the bottom. |
| Cogwork Core: Break Wall #6 | Breakable Wall Shaft | Break Wall Left OR Break Wall Right |  | Verified | blockade |  |
| Cogwork Core: Break Wall #7 | Breakable Wall Shaft | Break Wall Left OR Break Wall Right |  | Verified | blockade |  |
| Cogwork Core: Gauntlet #3 | Northern Gauntlet | Nothing |  | Verified | gauntlet |  |

### Cogwork Core East Choral Entrance (Cog_06)

**Game ID:** Cog_06

**Contributors:** Rebel

#### Subrooms

- Left Side
- Right Side

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right Side | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | LH | Activate Cogwork Core: Flip Switch #3 |  | Verified |  |
| L | left2 | Left Side | [Cogwork Core South Main (Cog_04)](#cogwork-core-south-main-cog04) | MR | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| J | Jump | Left Side | Right Side | Spike Pogo OR (Clawline AND (Drifter's Cloak OR Faydown Cloak OR (Faydown Cloak AND Swift Step 2 AND (Drifter's Cloak OR Spike Pogo)))) |  | Verified |  |
| J | Jump | Right Side | Left Side | Spike Pogo OR (Clawline AND (Drifter's Cloak OR Faydown Cloak OR (Faydown Cloak AND Swift Step 2 AND (Drifter's Cloak OR Spike Pogo)))) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Flip Switch #3 | Right Side | Flip Switch Up |  | Verified | switch |  |

### Cogwork Core East Silk Spool & Gauntlet (Cog_07)

**Game ID:** Cog_07

**Contributors:** Rebel

#### Subrooms

- Entrance
- Left Room
- Right Room
- Silk Spool Jump Left
- Silk Spool Jump Right
- Bottom Room
- Arena 

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Entrance | [Cogwork Core South Main (Cog_04)](#cogwork-core-south-main-cog04) | BR | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EL | Entrance-Left | Entrance | Left Room | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| LR | Left-Right | Left Room | Right Room | Activate Cogwork Core: Flip Switch #2 |  | Verified |  |
| RB | Right-Bottom | Right Room | Bottom Room | Nothing. (Fall) |  | Verified |  |
| BLS | Bottom-Spool Left | Bottom Room | Silk Spool Jump Left | Nothing. (Fall) |  | Verified |  |
| SSJ | Silk Spool Jump | Silk Spool Jump Left | Silk Spool Jump Right | Dash OR Sprint OR Clawline OR Sharpdart OR Scuttlebrace |  | Verified | hehe, funny dragonball reference. |
| SSJ | Silk Spool Jump | Silk Spool Jump Right | Silk Spool Jump Left | Dash OR Sprint OR Clawline OR Sharpdart OR Scuttlebrace |  | Verified |  |
| BLS | Bottom-Spool Left | Silk Spool Jump Left | Bottom Room | Scuttlebrace OR Cling Grip |  | Verified |  |
| BE | Bottom-Entrance | Bottom Room | Entrance | Nothing. |  | Verified |  |
| BE | Bottom-Entrance | Entrance | Bottom Room | Invalid |  | Verified |  |
| EL | Entrance-Left | Left Room | Entrance | Nothing. (Fall) |  | Verified |  |
| LR | Left-Right | Right Room | Left Room | Activate Cogwork Core: Flip Switch #2 |  | Verified |  |
| RB | Right-Bottom | Bottom Room | Right Room | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| LG | Left-Gauntlet | Left Room | Arena | Silk Soar |  | Verified |  |
| LG | Left-Gauntlet | Arena | Left Room | Complete Cogwork Core: Gauntlet #2 |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Silk Spool #1 | Silk Spool Jump Left | Nothing. |  | Verified | collectible |  |
| Cogwork Core: Flip Switch #2 | Left Room | Nothing. |  | Verified | switch | interacting with this switch causes a mini-boss type enemy to spawn |
| Cogwork Core: Pristine Core | Arena | Complete Cogwork Core: Gauntlet #2 |  | Verified | collectible |  |
| Cogwork Core: Gauntlet #2 | Arena | Nothing. |  | Verified | gauntlet |  |

### Cogwork Core Main Connection (Cog_Pass)

**Game ID:** Cog_Pass

#### Subrooms

- Lower Entrance
- Upper Entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | left2 | Lower Entrance | [Cogwork Core South Main (Cog_04)](#cogwork-core-south-main-cog04) | DR | Nothing. |  | Verified |  |
| TL | left1 | Upper Entrance | [Cog Dancers (Cog_Dancers)](#cog-dancers-cogdancers) | D | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LU | Lower-Upper | Lower Entrance | Upper Entrance | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| LU | Lower-Upper | Upper Entrance | Lower Entrance | Nothing. (Fall) |  | Verified |  |

#### Check Locations

No check locations defined.

### Cogwork Core North Main (Cog_08)

**Game ID:** Cog_08

**Contributors:** Rebel

#### Subrooms

- Lower Entrance
- Upper Entrance
- Lever Door

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Lever Door | [Cog Dancers (Cog_Dancers)](#cog-dancers-cogdancers) | T | Nothing |  | Verified |  |
| T | top1 | Upper Entrance | [Cogwork Core Architect's Melody (Cog_09)](#cogwork-core-architects-melody-cog09) | B | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BEL | Bottom Entrance-Lever | Lower Entrance | Lever Door | ((Proficient Movement AND Spike Pogo)  AND Medium Hunter Pogo AND Medium Reaper Pogo AND Medium Architect Pogo AND Medium Shaman Pogo AND (Cling Grip OR Faydown Cloak OR Ledge Grab) AND Easy Enemy Pogo (Easy Skip)) |  | Verified | Can be clawline only'd but since theres no specific skip tag for that i am omitting it. |
| BEL | Bottom Entrance-Lever | Lever Door | Lower Entrance | Drifter's Cloak |  | Verified | let me add a Nothing as a medium skip pls it'll be funny |
| LTE | Lever-Top Entrance | Lever Door | Upper Entrance | Clawline AND Faydown Cloak AND Cling Grip |  | Verified |  |
| LTE | Lever-Top Entrance | Upper Entrance | Lever Door | Clawline OR Sharpdart OR Dash OR Faydown Cloak OR Drifter's Cloak |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Flip Switch #7 | Lever Door | Nothing. |  | Verified | switch |  |

### Cogwork Core Second Sentinel (Cog_10)

**Game ID:** Cog_10

**Contributors:** Rebel

#### Subrooms

- Shard Bundle Check
- Second Sentinel
- Entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Entrance | [Cogwork Core West Gauntlet (Cog_05)](#cogwork-core-west-gauntlet-cog05) | T | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EB | Entrance-Bundle | Entrance | Shard Bundle Check | Silk Soar OR Faydown Cloak |  | Verified |  |
| BS | Bundle-Sentinel | Shard Bundle Check | Second Sentinel | Activate Cogwork Core: Break Wall #1 AND Activate Cogwork Core: Break Wall #2 |  | Verified |  |
| BS | Bundle-Sentinel | Second Sentinel | Shard Bundle Check | Activate Cogwork Core: Break Wall #1 AND Activate Cogwork Core: Break Wall #2 |  | Verified |  |
| EB | Entrance-Bundle | Shard Bundle Check | Entrance | Nothing. (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Shard Bundle #1 | Shard Bundle Check | Nothing. |  | Verified | collectible |  |
| Cogwork Core: Break Wall #1 | Shard Bundle Check | Nothing. |  | Verified | blockade |  |
| Cogwork Core: Break Wall #2 | Shard Bundle Check | Nothing. |  | Verified | blockade |  |
| Second Sentinel Activation | Second Sentinel | (Break Wall Right AND Cogheart Pieces 3) |  | Verified | event |  |

### Cogwork Core South Main (Cog_04)

**Game ID:** Cog_04

**Contributors:** Rebel

#### Subrooms

- Top Entrance
- Left Shaft Top Side
- Bottom
- Right Shaft Top Side
- Top Right Door
- Bottom Right Entrance
- Left Shaft Bottom Side
- Right Shaft Bottom Side
- Shaft Shortcut

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BR | right3 | Bottom | [Cogwork Core East Silk Spool & Gauntlet (Cog_07)](#cogwork-core-east-silk-spool-gauntlet-cog07) | L | Nothing. |  | Verified |  |
| ML | left2 | Left Shaft Bottom Side | [Cogwork Core West Gauntlet (Cog_05)](#cogwork-core-west-gauntlet-cog05) | R | Nothing. |  | Verified |  |
| DL | door1 | Top Entrance | [Cogwork Core Bench & Map (Cog_Bench)](#cogwork-core-bench-map-cogbench) | L | Nothing. |  | Verified |  |
| DR | door2 | Top Right Door | [Cogwork Core Main Connection (Cog_Pass)](#cogwork-core-main-connection-cogpass) | BL | Nothing. |  | Verified |  |
| MR | right2 | Right Shaft Top Side | [Cogwork Core East Choral Entrance (Cog_06)](#cogwork-core-east-choral-entrance-cog06) | L | Nothing. |  | Verified |  |
| TL | top1 | Top Entrance | [Cog Dancers (Cog_Dancers)](#cog-dancers-cogdancers) | B1 | Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown Cloak |  | Verified |  |
| TR | top2 | Top Entrance | [Cog Dancers (Cog_Dancers)](#cog-dancers-cogdancers) | B2 | Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown Cloak |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TLT | Top-Left Top | Top Entrance | Left Shaft Top Side | Nothing. (Fall) |  | Verified |  |
| TLT | Top-Left Top | Left Shaft Top Side | Top Entrance | Ledge Grab OR Clawline OR Faydown Cloak OR Scuttlebrace |  | Verified |  |
| LTB | Left Top-Left Bottom | Left Shaft Top Side | Left Shaft Bottom Side | Nothing. (Fall) |  | Verified |  |
| LTB | Left Top-Left Bottom | Left Shaft Bottom Side | Left Shaft Top Side | (Spike Pogo AND (Ledge Grab OR Clawline OR Faydown Cloak (Easy Skip))) OR (Cling Grip AND Ledge Grab) | TODO | Verified |  |
| LBB | Left Bottom-Bottom | Left Shaft Bottom Side | Bottom | Nothing. (Fall) |  | Verified |  |
| LBB | Left Bottom-Bottom | Bottom | Left Shaft Bottom Side | (Cling Grip AND Ledge Grab) OR (Faydown Cloak AND (Spike Pogo OR Enemy Pogo (Easy Skip))) | TODO | Verified |  |
| BRR | Bottom-Right Bottom Shaft | Bottom | Right Shaft Bottom Side | (Cling Grip AND (Faydown Cloak OR Clawline OR (Dash AND Drifter's Cloak) OR Spike Pogo)) OR (Spike Pogo AND (Faydown Cloak OR (Clawline AND Faydown Cloak (Hard Skip)))) | TODO | Verified |  |
| BRR | Bottom-Right Bottom Shaft | Right Shaft Bottom Side | Bottom | Nothing. (Fall) |  | Verified |  |
| RBT | Right Bottom-Right Top | Right Shaft Bottom Side | Right Shaft Top Side | (Cling Grip AND Faydown Cloak AND (Drifter's Cloak OR Dash)) OR (Faydown Cloak AND Spike Pogo) OR (Clawline AND Faydown Cloak (Hard Skip)) | TODO | Verified | unsure if any of these marks are being properly read as skips |
| RBT | Right Bottom-Right Top | Right Shaft Top Side | Right Shaft Bottom Side | Nothing. (fall) |  | Verified |  |
| RST | Right Top-Top Door | Right Shaft Top Side | Top Right Door | ((Ledge Grab OR Clawline OR Scuttlebrace) AND (Spike Pogo AND (Cling Grip OR Faydown Cloak))) OR (Clawline AND (Faydown Cloak (Easy Skip))) |  | Verified | AQ - my cat |
| RST | Right Top-Top Door | Top Right Door | Right Shaft Top Side | Nothing. (Fall) |  | Verified |  |
| TDT | Right Top Door-Top | Top Right Door | Top Entrance | Activate Cogwork Core: Flipped Switch #4 |  | Verified |  |
| TDT | Right Top Door-Top | Top Entrance | Top Right Door | Activate Cogwork Core: Flipped Switch #5 |  | Verified |  |
| SC | Shortcut | Left Shaft Bottom Side | Right Shaft Bottom Side | Activate Cogwork Core: Flipped Switch #4 |  | Verified |  |
| SC | Shortcut | Right Shaft Bottom Side | Left Shaft Bottom Side | Activate Cogwork Core: Flipped Switch #4 |  | Verified |  |
| BBE | Bottom-Bottom Exit | Bottom | Bottom Right Entrance | Spike Pogo OR Clawline OR Sharpdart OR Sprint OR Dash OR Drifter's Cloak OR Faydown Cloak |  | Verified |  |
| BBE | Bottom-Bottom Exit | Bottom Right Entrance | Bottom | Spike Pogo OR Clawline OR Sharpdart OR Sprint OR Dash OR Drifter's Cloak OR Faydown Cloak |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Flipped Switch #5 | Top Right Door | Nothing. |  | Verified | switch |  |
| Cogwork Core: Flipped Switch #4 | Shaft Shortcut | Flip Switch Left |  | Verified | switch |  |

### Cogwork Core West Gauntlet (Cog_05)

**Game ID:** Cog_05

**Contributors:** Rebel

#### Subrooms

- Top Entrance
- Main
- Arena
- Left Entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right2 | Main | [Cogwork Core South Main (Cog_04)](#cogwork-core-south-main-cog04) | ML | Nothing. |  | Verified |  |
| L | left1 | Left Entrance | [Choral Chambers Over Dininig (Song_09)](#choral-chambers-over-dininig-song09) | R | Nothing. |  | Verified |  |
| T | top1 | Top Entrance | [Cogwork Core Second Sentinel (Cog_10)](#cogwork-core-second-sentinel-cog10) | B | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MT | Main-Top | Main | Top Entrance | (Silk Soar OR (Faydown Cloak AND (Cling Grip OR Scuttlebrace OR Ledge Grab))) |  | Verified |  |
| MT | Main-Top | Top Entrance | Main | Nothing. (fall) |  | Verified |  |
| ML | Main-Left | Main | Left Entrance | (Complete Cogwork Core: Gauntlet #1 AND (Silk Soar OR Cling Grip OR Scuttlebrace)) |  | Verified |  |
| ML | Main-Left | Left Entrance | Main | Complete Cogwork Core: Gauntlet #1 |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Gauntlet #1 | Arena | Nothing |  | Verified | gauntlet |  |

## Whispering Vaults

### Vaultkeeper Cauldron Entrance (Library_10)

**Game ID:** Library_10

**Contributors:** Rebel

#### Subrooms

- Left Side
- Right Side
- Top Room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | Bottom | Right Side | [Underworks Below Vaultkeeper (Library_12b)](#underworks-below-vaultkeeper-library12b) | T | Nothing. |  | Verified |  |
| L | Left | Left Side | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | BR | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| W | Walk | Right Side | Left Side | Activate Whispering Vaults: Flip Switch #1 |  | Verified |  |
| W | Walk | Left Side | Right Side | Activate Whispering Vaults: Flip Switch #1 |  | Verified |  |
| J | Jump | Right Side | Top Room | Silk Soar OR Cling Grip OR Scuttlebrace OR (Faydown Cloak AND Ledge Grab) |  | Verified |  |
| J | Jump | Top Room | Right Side | Nothing. (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Break Wall #1 (Up) | Right Side | Nothing. |  | Verified | blockade |  |
| Sacred Cylinder | Left Side | Nothing. |  | Verified | collectible |  |
| Whispering Vaults: Flip Switch #1 | Right Side | Flip Switch Left |  | Verified | switch |  |
| Whispering Vaults: Needolin Lore #1 | Left Side | Needolin |  | Verified | event |  |

### Whispering Vaults Below Bench (Library_06)

**Game ID:** Library_06

**Contributors:** Rebel

#### Subrooms

- Bottom
- Top
- Rosary
- Right Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | left2 | Bottom | [Whispering Vaults East To West (Library_05)](#whispering-vaults-east-to-west-library05) | BR | Nothing. |  | Verified |  |
| R | right1 | Top | [Whispering Vaults Totally Not White Palace (Library_07)](#whispering-vaults-totally-not-white-palace-library07) | BL | Nothing. |  | Verified |  |
| TL | left1 | Top | [Whispering Vaults East To West (Library_05)](#whispering-vaults-east-to-west-library05) | TR | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LA | Lower Ascent | Bottom | Top | (Silk Soar OR Cling Grip OR Scuttlebrace) AND (Dash OR Clawline OR Sharpdart OR Faydown Cloak) |  | Verified |  |
| HA | Higher Ascent | Top | Rosary | Silk Soar OR Proficient Movement (easy box pogo) OR (Cling Grip AND (Faydown Cloak OR Clawline OR Sharpdart OR easy Needle Strike Stall (Architect) OR (Cling Grip AND Easy Enemy Pogo))) |  | Verified |  |
| E | Exit | Top | Right Exit | Silk Soar OR Cling Grip OR Scuttlebrace OR (Faydown Cloak AND Ledge Grab) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| AP Minor Cache - Whispering Vaults - Rosary Cache #4 | Rosary | Nothing. |  | Verified | resource |  |
| Whispering Vaults: Rosary Cache #3 | Rosary | Nothing. |  | Verified | resource |  |
| Whispering Vaults: Rosary Dish #2 | Rosary | Nothing. |  | Verified | resource |  |

### Whispering Vaults Bench (Library_08)

**Game ID:** Library_08

**Contributors:** Rebel

#### Subrooms

- Bench
- Loot
- Cylinder
- Cardinius
- Side Room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right | Side Room | [Whispering Vaults Totally Not White Palace (Library_07)](#whispering-vaults-totally-not-white-palace-library07) | TL | Nothing. |  | Verified |  |
| L | Left | Cardinius | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | MHR | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| L | Loot! | Side Room | Loot | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| BT | Bench Time! | Cardinius | Bench | Silk Soar OR (Cling Grip AND (Faydown Cloak OR Clawline OR Sharpdart OR Sprint OR Dash OR Easy Needle Strike Stall (Beast OR Architect))) |  | Verified |  |
| PC | Psalm Cylinder | Cardinius | Cylinder | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| L | Loot! | Loot | Side Room | Nothing (Fall) |  | Verified |  |
| BT | Bench Time! | Bench | Cardinius | Activate Whispering Vaults: Breakable Floor |  | Verified |  |
| PC | Psalm Cylinder | Cylinder | Cardinius | Nothing (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Rosary Cache #1 | Loot | Nothing. |  | Verified | resource |  |
| Whispering Vaults: Memory Locket #1 | Loot | Nothing. |  | Verified | collectible |  |
| Whispering Vaults: Rosary Cache #2 | Loot | Nothing. |  | Verified | resource |  |
| Whispering Vaults: Psalm Cylinder #1 | Cylinder | Nothing. |  | Verified | collectible |  |
| Whispering Vaults: Breakable Floor | Bench | Break Wall Down |  | Verified | blockade | stand on it and it breaks |

### Whispering Vaults East To West (Library_05)

**Game ID:** Library_05

**Contributors:** Rebel

#### Subrooms

- Top
- Center
- Bottom
- Shard

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bottom Left | Bottom | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | LR | Nothing. |  | Verified |  |
| BR | Bottom Right | Bottom | [Whispering Vaults Below Bench (Library_06)](#whispering-vaults-below-bench-library06) | BL | Nothing. |  | Verified |  |
| TR | Top Right | Top | [Whispering Vaults Below Bench (Library_06)](#whispering-vaults-below-bench-library06) | TL | Nothing. |  | Verified |  |
| TL | Top Left | Top | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | CR | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VL | Vertical Low | Bottom | Center | Activate Whispering Vaults: Flip Switch #3 AND (Silk Soar OR Cling Grip OR (Faydown Cloak AND Ledge Grab)) |  | Verified |  |
| VH | Vertical High | Center | Top | Cling Grip OR Silk Soar |  | Verified |  |
| MS | Mask Shard | Top | Shard | Silk Soar OR Proficient Movement (Easy Box Pogo) |  | Verified |  |
| MS | Mask Shard | Shard | Top | Nothing. (Fall) |  | Verified |  |
| VH | Vertical High | Top | Center | Nothing. (Fall) |  | Verified |  |
| VL | Vertical Low | Center | Bottom | Activate Whispering Vaults: Flip Switch #3 |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Mask Shard #1 | Shard | Nothing. |  | Verified | collectible |  |
| Whispering Vaults: Flip Switch #3 | Bottom | Nothing. |  | Verified | switch |  |

### Whispering Vaults Flea Shaft (Library_01)

**Game ID:** Library_01

**Contributors:** Rebel

#### Subrooms

- Top
- Bottom
- Flea Check
- Lower Platforms
- Upper Platforms

- **Top:** Self contained.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BR | right2 | Bottom | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | LL | Nothing. |  | Verified |  |
| CL | left2 | Lower Platforms | [Grand Bellway Library (Library_03)](#grand-bellway-library-library03) | R | Silk Soar OR (Activate Whispering Vaults: Flip Switch #5 IN whispering vaults vaultborn lever AND Easy Enemy Pogo (2)) OR (Faydown Cloak AND (Ledge Grab OR (Sprint AND (Easy Beast Crest Pogo OR Easy Shaman Crest Pogo OR Easy Needle Strike Stall (Beast))))) OR (Cling Grip AND (Easy Enemy Pogo OR Sprint OR Dash OR Clawline OR Drifter's Cloak OR Sharpdart OR Easy Beast Crest Pogo OR Easy Needle Strike Stall (Beast OR Architect))) |  | Verified | first enemy pogo only available with flipped lever. crest specific options and enemy pogos probably easy skip? |
| TR | right1 | Top | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | TL | Nothing. |  | Verified |  |
| TL | left1 | Top | [Songclave Steam Tunnel (Library_02)](#songclave-steam-tunnel-library02) | BR | Nothing. |  | Verified |  |
| BL | left3 | Bottom | [Whispering Vaults Vaultborn Lever (Library_15)](#whispering-vaults-vaultborn-lever-library15) | R | Activate Whispering Vaults: Break Wall #4 |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| GF | Ground to Floor 1 | Bottom | Lower Platforms | Silk Soar OR (Faydown Cloak AND Ledge Grab) OR Enemy Pogo (Easy Skip) |  | Verified |  |
| GF | Ground to Floor 1 | Lower Platforms | Bottom | None (Falling) |  | Verified | added due to none all connections being one-way - hero, 9/26 |
| UT | Upwards Traversal | Lower Platforms | Upper Platforms | Silk Soar OR (Medium Enemy Pogo AND Faydown Cloak) OR (Faydown Cloak AND (Ledge Grab OR Easy Beast Crest Pogo OR Easy Needle Strike Stall (Beast) OR Easy Shaman Crest Pogo)) OR (Cling Grip AND (Sprint OR Dash OR Easy Beast Crest Pogo OR Easy Needle Strike Stall (Beast OR Architect) OR Sharpdart OR Drifter's Cloak OR Clawline)) |  | Verified |  |
| UT | Upwards Traversal | Upper Platforms | Lower Platforms | None (Falling) |  | Verified | added due to none all connections being one-way - hero, 9/26 |
| FG | Flea Grab | Upper Platforms | Flea Check | Silk Soar OR (Cling Grip AND (Clawline OR Sharpdart OR Drifter's Cloak OR Easy Beast Crest Pogo OR Easy Needle Strike Stall (Beast OR Architect) OR Cling Grip)) OR (Scuttlebrace AND Faydown Cloak AND Swift Step 2) |  | Verified | collect yo flea. |
| FG | Flea Grab | Flea Check | Upper Platforms | None (Falling) |  | Verified | added due to none all connections being one-way - hero, 9/26 |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Flea #1 | Flea Check | Silk Soar OR Scuttlebrace OR (Cling Grip AND (Clawline OR Sharpdart OR Drifter's Cloak OR Easy Beast Crest Pogo OR Easy Needle Strike Stall (Beast OR Architect) OR Cling Grip)) OR (Scuttlebrace AND (Faydown Cloak AND Swift Step 2)) |  | Verified | collectible |  |
| Whispering Vaults: Break Wall #4 | Bottom | Break Wall Left |  | Verified | blockade |  |

### Whispering Vaults Hell (Library_04)

**Game ID:** Library_04

**Contributors:** Rebel

#### Subrooms

- Ground
- Lowest Hallway
- Middle Hallway
- Upper Platform
- Map Room
- Top Hallway
- Upper Low Hallway
- Rosary Dish
- Left Side Shaft
- Lever
- Distant Platform
- Shortcut Box

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | Top | Map Room | [Songclave (Song_Enclave)](#songclave-songenclave) | B | Nothing |  | Verified |  |
| HR | High Right | Distant Platform | [Whispering Vaults Silkeater (Library_14)](#whispering-vaults-silkeater-library14) | L | Nothing |  | Verified |  |
| CR | Center Right | Middle Hallway | [Whispering Vaults East To West (Library_05)](#whispering-vaults-east-to-west-library05) | TL | Nothing |  | Verified |  |
| BL | Bottom Left | Lowest Hallway | [Whispering Vaults Music Box (Library_16)](#whispering-vaults-music-box-library16) | R | Nothing |  | Verified |  |
| CL | Center Left | Middle Hallway | [Trobbio Entrance (Library_13b)](#trobbio-entrance-library13b) | R | Nothing |  | Verified |  |
| LL | Low Left | Left Side Shaft | [Whispering Vaults Flea Shaft (Library_01)](#whispering-vaults-flea-shaft-library01) | BR | Nothing |  | Verified |  |
| LR | Low Right | Upper Low Hallway | [Whispering Vaults East To West (Library_05)](#whispering-vaults-east-to-west-library05) | BL | Nothing |  | Verified |  |
| TR | Top Right | Top Hallway | [Whispering Vaults Jumps (Library_09)](#whispering-vaults-jumps-library09) | L | Activate Whispering Vaults: Flip Switch #6 IN Whispering Vaults Jumps |  | Verified |  |
| TL | Top Left | Top Hallway | [Whispering Vaults Flea Shaft (Library_01)](#whispering-vaults-flea-shaft-library01) | TR | Nothing |  | Verified |  |
| BR | Bottom Right | Ground | [Vaultkeeper Cauldron Entrance (Library_10)](#vaultkeeper-cauldron-entrance-library10) | L | Nothing |  | Verified |  |
| MHR | Mid High Right | Upper Platform | [Whispering Vaults Bench (Library_08)](#whispering-vaults-bench-library08) | L | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| A1 | Ascent 1 | Ground | Lowest Hallway | Silk Soar OR Ledge Grab OR Clawline OR Faydown Cloak OR Cling Grip |  | Verified |  |
| BR | BL to LR | Lowest Hallway | Upper Low Hallway | Silk Soar OR Easy Enemy Pogo OR Clawline OR Ledge Grab OR Faydown Cloak OR Sprint OR Cling Grip OR Scuttlebrace |  | Verified |  |
| CR | Collect Rosaries | Lever | Rosary Dish | Sprint OR Dash OR Clawline OR Drifter's Cloak OR Faydown Cloak OR Cling Grip OR Scuttlebrace OR Sharpdart OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo OR Easy Needle Strike Stall (Beast OR Architect) |  | Verified |  |
| PR | Progresion! | Left Side Shaft | Lever | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| MP | More Progression! | Lever | Upper Platform | Activate Whispering Vaults: Flip Switch #8 AND (Silk Soar OR Cling Grip OR Scuttlebrace OR (Faydown Cloak AND (Ledge Grab OR Easy Shaman Crest Pogo))) |  | Verified |  |
| EMP | Even More Progression! | Upper Platform | Distant Platform | Silk Soar OR ((Cling Grip OR Scuttlebrace) AND (Faydown Cloak OR (Clawline AND (Sprint OR Dash OR Drifter's Cloak) AND Ledge Grab))) |  | Verified |  |
| LP | Last Push! | Distant Platform | Top Hallway | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| MT | Map Time! | Top Hallway | Map Room | Activate Whispering Vaults: Flip Switch #9 AND (Silk Soar OR Cling Grip OR (Scuttlebrace AND (Easy Enemy Pogo/ OR Faydown Cloak))) |  | Verified |  |
| MT | Map Time! | Map Room | Top Hallway | Nothing (fall) |  | Verified |  |
| LP | Last Push! | Top Hallway | Distant Platform | Nothing (Fall) |  | Verified |  |
| EMP | Even More Progression! | Distant Platform | Upper Platform | Activate Whispering Vaults: Flip Switch #7 |  | Verified |  |
| MP | More Progression! | Upper Platform | Lever | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified | accounting for the fact the player may not have activated the shortcut |
| PR | Progresion! | Lever | Left Side Shaft | Nothing (Fall) |  | Verified |  |
| BR | BL to LR | Upper Low Hallway | Lowest Hallway | Nothing (Fall) |  | Verified |  |
| A1 | Ascent 1 | Lowest Hallway | Ground | Nothing (Fall) |  | Verified |  |
| US | Unlock Shortcut | Middle Hallway | Shortcut Box | Ledge Grab OR Cling Grip OR Scuttlebrace OR Faydown Cloak OR Clawline |  | Verified | Opens Shortcut |
| US2 | Use Shortcut | Shortcut Box | Middle Hallway | Activate Hell Room Box Shortcut Thing |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Flip Switch #7 | Distant Platform | flip Switch Left |  | Verified | switch |  |
| Whispering Vaults: Flip Switch #8 | Lever | Nothing |  | Verified | switch |  |
| Whispering Vaults: Flip Switch #9 | Top Hallway | Nothing |  | Verified | switch |  |
| Map: Whispering Vaults | Map Room | Nothing |  | Verified | collectible |  |
| Whispering Vaults: Break Wall #5 (Up) | Map Room | Nothing |  | Verified | blockade |  |
| Whispering Vaults: Rosary Dish #3 | Rosary Dish | Nothing |  | Verified | resource |  |
| Hell Room Box Shortcut thing. | Shortcut Box | Break Wall Right |  | Verified | logic-point | not a proper check, for logic documentation only. |

### Whispering Vaults Jumps (Library_09)

**Game ID:** Library_09

**Contributors:** Rebel

#### Subrooms

- Flea Chase
- Flea
- Annoying Ass Jump (Left)
- Annoying Ass Jump (Right)
- Jump 2 (Right)
- Jump 2 (Left)
- Rosary Necklace
- Room With Stuff
- Bottom Right Entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Flea Chase | [Whispering Vaults Totally Not White Palace (Library_07)](#whispering-vaults-totally-not-white-palace-library07) | T | Nothing. |  | Verified |  |
| L | left1 | Room With Stuff | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | TR | Activate Whispering Vaults: Flip Switch #6 |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FG | Flea Get | Flea Chase | Flea | Silk Soar OR (Clawline AND Cling Grip) OR (Clawline AND Scuttlebrace AND (Spike Pogo OR Faydown Cloak)) |  | Verified |  |
| FG | Flea Get | Flea | Flea Chase | Nothing. (BIG fall) |  | Verified |  |
| AJ | Annoying Jump | Annoying Ass Jump (Right) | Annoying Ass Jump (Left) | Sprint OR Dash OR Drifter's Cloak OR Faydown Cloak OR Clawline OR Scuttlebrace OR Sharpdart OR Easy Enemy Pogo OR Spike Pogo OR Easy Hazard Respawn |  | Verified |  |
| AJ | Annoying Jump | Annoying Ass Jump (Left) | Annoying Ass Jump (Right) | Dash OR Sprint OR Faydown Cloak OR Scuttlebrace OR Clawline OR Sharpdart OR (Spike Pogo OR Enemy Pogo (Easy Skip))  OR (Drifter's Cloak AND Ledge Grab) |  | Verified | this side you CANT damage boost. |
| JT | Jump Two | Jump 2 (Left) | Jump 2 (Right) | Dash OR Sprint OR Faydown Cloak OR Scuttlebrace OR Clawline OR Sharpdart OR (Spike Pogo OR Enemy Pogo (Easy Skip))  OR (Drifter's Cloak AND Ledge Grab) |  | Verified | its literally the SAME jump again. |
| JT | Jump Two | Jump 2 (Right) | Jump 2 (Left) | Dash OR Sprint OR Faydown Cloak OR Scuttlebrace OR Clawline OR Sharpdart OR (Spike Pogo OR Enemy Pogo (Easy Skip))  OR (Drifter's Cloak AND Ledge Grab) |  | Verified |  |
| RP | Rosary Pickup | Jump 2 (Right) | Rosary Necklace | (Sprint AND Clawline) OR (Sprint AND Faydown Cloak AND Spike Pogo AND (Drifter's Cloak OR Dash)) |  | Verified |  |
| EC | Enter to Chase | Bottom Right Entrance | Flea Chase | Silk Soar OR Scuttlebrace OR Cling Grip |  | Verified |  |
| EC | Enter to Chase | Flea Chase | Bottom Right Entrance | Nothing. (Fall) |  | Verified |  |
| CJ1 | Chase to Jump 1 | Flea Chase | Annoying Ass Jump (Right) | Nothing. |  | Verified |  |
| CJ1 | Chase to Jump 1 | Annoying Ass Jump (Right) | Flea Chase | Nothing. |  | Verified |  |
| J12 | Jump 1 to Jump 2 | Annoying Ass Jump (Left) | Jump 2 (Right) | Nothing. |  | Verified |  |
| J12 | Jump 1 to Jump 2 | Jump 2 (Right) | Annoying Ass Jump (Left) | Nothing. |  | Verified |  |
| RP | Rosary Pickup | Rosary Necklace | Jump 2 (Right) | (Sprint AND (Clawline OR (Faydown Cloak AND Drifter's Cloak))) |  | Verified |  |
| J2S | Jump 2 to Stuff | Jump 2 (Left) | Room With Stuff | Nothing. |  | Verified |  |
| J2S | Jump 2 to Stuff | Room With Stuff | Jump 2 (Left) | Nothing. |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Flip Switch #6 | Room With Stuff | Nothing. |  | Verified | switch |  |
| Whispering Vaults: Heavy Rosary Necklace #1 | Rosary Necklace | Nothing. |  | Verified | resource |  |
| Whispering Vaults: Psalm Cylinder #2 | Room With Stuff | Nothing. |  | Verified | collectible |  |

### Whispering Vaults Silkeater (Library_14)

**Game ID:** Library_14

**Contributors:** Rebel

#### Subrooms

- The Room
- Silkeater

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | The Room | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | HR | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SBC | The One Subroom Connection | The Room | Silkeater | Activate Whispering Vaults: Break Wall #5 |  | Verified |  |
| SBC | The One Subroom Connection | Silkeater | The Room | Activate Whispering Vaults: Break Wall #5 |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Break Wall #5 | The Room | Break Wall Right |  | Verified | blockade |  |
| Whispering Vaults: Silkeater #1 | Silkeater | Nothing. |  | Verified | collectible |  |

#### Notes

lol

### Whispering Vaults Totally Not White Palace (Library_07)

**Game ID:** Library_07

**Contributors:** Rebel

#### Subrooms

- White Palace Lite
- Up And Away
- Collectibles(TM)
- Collectibles 2(TM)
- Down We Go
- Sky High

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | left1 | Down We Go | [Whispering Vaults Bench (Library_08)](#whispering-vaults-bench-library08) | R | Nothing |  | Verified |  |
| BL | left2 | Up And Away | [Whispering Vaults Below Bench (Library_06)](#whispering-vaults-below-bench-library06) | R | Nothing |  | Verified |  |
| T | top1 | Sky High | [Whispering Vaults Jumps (Library_09)](#whispering-vaults-jumps-library09) | B | Nothing |  | Verified |  |
| B1 | bot1 | White Palace Lite | [Bilewater Citadel Exit (Shadow_22)](#bilewater-citadel-exit-shadow22) | T1 | Nothing |  | Verified |  |
| B2 | bot2 | White Palace Lite | [Bilewater Citadel Exit (Shadow_22)](#bilewater-citadel-exit-shadow22) | T2 | nothing |  | Verified |  |
| B3 | bot3 | White Palace Lite | [Bilewater Citadel Exit (Shadow_22)](#bilewater-citadel-exit-shadow22) | T3 | nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CS | Collect Shit | Up And Away | Collectibles(TM) | Silk Soar OR Cling Grip OR (Scuttlebrace AND Faydown Cloak) |  | Verified |  |
| MC | More Collecting | Down We Go | Collectibles(TM) | Nothing (Fall) |  | Verified |  |
| NHA | NOT HIM AGAIN! | Collectibles(TM) | White Palace Lite | Activate Whispering Vaults: Clawline Ring AND (Clawline OR Faydown Cloak OR (Cling Grip AND Spike Pogo) OR (Cling Grip AND (Dash OR Drifter's Cloak))) |  | Verified |  |
| OH | GET ME OUTTA HERE!! | White Palace Lite | Sky High | (Activate Whispering Vaults: Flip Switch #2 AND Drifter's Cloak) OR Silk Soar OR Cling Grip OR (Scuttlebrace AND Faydown Cloak) |  | Verified |  |
| CS | Collect Shit | Collectibles(TM) | Up And Away | Silk Soar OR Scuttlebrace OR Cling Grip |  | Verified |  |
| MC | More Collecting | Collectibles(TM) | Down We Go | Nothing (Fall) |  | Verified |  |
| NHA | NOT HIM AGAIN! | White Palace Lite | Collectibles(TM) | Invalid |  | Verified |  |
| OH | GET ME OUTTA HERE!! | Sky High | White Palace Lite | Nothing (BIG fall.) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Clawline Ring | Collectibles(TM) | Clawline |  | Verified | switch |  |
| AP Minor Cache - Whispering Vaults - Rosary Cache #5 | Collectibles 2(TM) | Nothing. |  | Verified | resource |  |
| AP Minor Cache - Whispering Vaults - Shell Shard Cache #1 | Collectibles(TM) | Activate Whispering Vaults: Break Wall #2 AND Activate Whispering Vaults: Break Wall #3 |  | Verified | resource |  |
| Whispering Vaults: Break Wall #2 | Collectibles(TM) | Break Wall Right |  | Verified | blockade |  |
| Whispering Vaults: Break Wall #3 | Collectibles(TM) | Break Wall Right |  | Verified | blockade |  |
| Whispering Vaults: Flip Switch #2 | White Palace Lite | Flip Switch Left |  | Verified | switch |  |

### Whispering Vaults Vaultborn Lever (Library_15)

**Game ID:** Library_15

**Contributors:** Rebel

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Whispering Vaults Flea Shaft (Library_01)](#whispering-vaults-flea-shaft-library01) | BL | Nothing. |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Flip Switch #5 |  | Flip Switch Left |  | Verified | switch |  |

### Grand Bellway Library (Library_03)

**Game ID:** Library_03

**Contributors:** Rebel

#### Subrooms

- Oil Room
- Entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Oil Room | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | UR | Activate Whispering Vaults: Flip Switch #10 |  | Verified |  |
| R | right1 | Entrance | [Whispering Vaults Flea Shaft (Library_01)](#whispering-vaults-flea-shaft-library01) | CL | Nothing. (Fall) |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Entrance | Oil Room | Silk Soar OR Cling Grip OR (Scuttlebrace AND (Faydown Cloak OR Drifter's Cloak OR Clawline OR Sharpdart OR Sprint OR (Dash AND Proficient Movement (Easy Box Pogo)))) |  | Verified | lever, one sided door |
| V | Vertical | Oil Room | Entrance | Nothing. (Fall) |  | Verified | both sides. |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Pale Oil | Oil Room | Activate Whispering Vaults: Flip Switch #11 |  | Verified | collectible |  |
| Whispering Vaults: Flip Switch #11 | Oil Room | Nothing. |  | Verified | switch |  |
| Whispering Vaults: Flip Switch #10 | Oil Room | Activate Whispering Vaults: Flip Switch #11 |  | Verified | switch |  |

### Songclave Steam Tunnel (Library_02)

**Game ID:** Library_02

**Contributors:** Rebel

#### Subrooms

- Top
- Bottom
- Arena
- Bottom Right
- Blocks

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | left2 | Top | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | R1 | Nothing. |  | Verified |  |
| TR | right2 | Top | [Songclave (Song_Enclave)](#songclave-songenclave) | BL | Nothing. |  | Verified |  |
| BL | left1 | Bottom | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | RH | Nothing. |  | Verified |  |
| BR | right1 | Bottom | [Whispering Vaults Flea Shaft (Library_01)](#whispering-vaults-flea-shaft-library01) | TL | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LV | Left Vertical | Blocks | Arena | Silk Soar OR (Faydown Cloak AND Spike Pogo (except Witch) AND Ledge Grab) OR (Cling Grip AND (Spike Pogo OR Dash OR Sprint OR Clawline OR Drifter's Cloak OR Sharpdart)) OR (Scuttlebrace AND (Faydown Cloak OR (Dash AND Ledge Grab) OR Clawline OR Sharpdart OR Easy Beast Crest Pogo)) |  | Verified |  |
| RV | Right Vertical | Bottom Right | Arena | Silk Soar OR Cling Grip OR (Scuttlebrace AND Faydown Cloak) |  | Verified |  |
| LV | Left Vertical | Arena | Blocks | Spike Pogo OR Proficient Movement (Easy Box Pogo) OR Clawline OR Faydown Cloak OR Drifter's Cloak OR Sharpdart |  | Verified |  |
| RV | Right Vertical | Arena | Bottom Right | Nothing. (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Arena #1 | Arena | Nothing. |  | Verified | gauntlet |  |

### Trobbio (Library_13)

**Game ID:** Library_13

**Contributors:** Rebel

#### Subrooms

- Top
- Bottom Left Entrance
- Fight
- Bottom Right
- Bottom Center

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TR | right1 | Top | [Trobbio Entrance (Library_13b)](#trobbio-entrance-library13b) | L | Nothing. |  | Verified |  |
| L | left1 | Bottom Left Entrance | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | RS | Nothing. |  | Verified |  |
| BR | right2 | Bottom Right | [Vaults & Bellway Cauldron Entrance (Library_11)](#vaults-bellway-cauldron-entrance-library11) | TL | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VR | Vertical Right | Top | Bottom Right | Activate Whispering Vaults: Flip Switch #12 |  | Verified |  |
| VR | Vertical Right | Bottom Right | Top | Activate Whispering Vaults: Flip Switch #12 AND (Cling Grip OR Scuttlebrace OR Faydown Cloak OR Clawline OR Dash OR Silk Soar OR Ledge Grab) |  | Verified |  |
| VL | Vertical Left | Top | Bottom Center | Nothing. (Fall) |  | Verified |  |
| VL | Vertical Left | Bottom Center | Top | Silk Soar OR (Faydown Cloak AND (Cling Grip OR Scuttlebrace)) |  | Verified |  |
| LL | Leave Left | Bottom Center | Bottom Left Entrance | Activate Whispering Vaults: Flip Switch #4 |  | Verified |  |
| LL | Leave Left | Bottom Left Entrance | Bottom Center | Activate Whispering Vaults: Flip Switch #4 |  | Verified |  |
| ESL | Enter Stage Left | Bottom Center | Fight | Nothing. |  | Verified |  |
| ESL | Enter Stage Left | Fight | Bottom Center | Defeat Trobbio OR (Act 3 AND Defeat Tormented Trobbio) |  | Verified |  |
| ESR | Enter Stage Right | Bottom Right | Fight | Nothing. |  | Verified |  |
| ESR | Enter Stage Right | Fight | Bottom Right | Defeat Trobbio OR (Act 3 AND Defeat Tormented Trobbio) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Lore #4 | Bottom Left Entrance | Nothing. |  | Verified | lore |  |
| Trobbio | Fight | Nothing. |  | Verified | boss |  |
| Progressive Claw Mirror 1 | Fight | Defeat Trobbio |  | Verified | collectible |  |
| Whispering Vaults: Flip Switch #4 | Bottom Center | Nothing. |  | Verified | switch |  |
| Whispering Vaults: Flip Switch #12 | Bottom Right | Nothing. |  | Verified | switch |  |
| AP Minor Cache - Whispering Vaults - Shell Shard Cache #2 | Top | Nothing. |  | Verified | resource |  |
| Tormented Trobbio | Fight | complete THE Pain, Anguish and Misery Wish Promised |  | Verified | boss | Is there a hard act 3 requirement for his spawn? - hero, 9/26 |
| Pain, Anguish and Misery Wish Granted | Fight | Defeat Tormented Trobbio |  | Verified | event |  |
| Progressive Claw Mirror 2 | Fight | Defeat Tormented Trobbio |  | Verified | collectible |  |

### Trobbio Entrance (Library_13b)

**Game ID:** Library_13b

**Contributors:** Rebel

#### Subrooms

- The Only Jump In This Entire Room
- Not The Jump.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | Not The Jump. | [Trobbio (Library_13)](#trobbio-library13) | TR | Nothing. |  | Verified |  |
| R | Right | The Only Jump In This Entire Room | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | CL | Nothing. |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| J | Jump | The Only Jump In This Entire Room | Not The Jump. | Ledge Grab OR Cling Grip OR Faydown Cloak OR Clawline OR Easy Needle Strike Stall (Beast) OR Scuttlebrace OR Sprint |  | Verified |  |
| J | Jump | Not The Jump. | The Only Jump In This Entire Room | Spike Pogo OR Clawline OR Dash OR Sprint OR Faydown Cloak OR Drifter's Cloak OR Scuttlebrace OR Cling Grip OR Sharpdart |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Collectable Item Pickup - Quill Red | Not The Jump. | Nothing. |  | Verified | collectible | Missable (Exclusive with other Quills |
| Collectable Item Pickup - Quill Purple | Not The Jump. | Nothing. |  | Verified | collectible | Missable (Exclusive with other Quills) |
| Whispering Vaults: Lore #2 | Not The Jump. | Nothing. |  | Verified | lore |  |
| Whispering Vaults: Lore #3 | Not The Jump. | Nothing. |  | Verified | lore |  |

### Whispering Vaults Music Box (Library_16)

**Game ID:** Library_16

**Contributors:** Rebel

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right |  | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | BL | Nothing. |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whispering Vaults: Cogheart Piece |  | Flip Switch Down OR Flip Switch UP |  | Verified | collectible | (Aka Nothing.) |

## Whiteward

### Whiteward Entrance (Ward_01)

**Game ID:** Ward_01

**Contributors:** skai

#### Subrooms

- Top Third
- Middle Third (Left)
- Middle Third (Right)
- Bottom Third (Left)
- Elevator Shaft
- Vertical Shaft (Upper)
- Vertical Shaft (Lower)
- Pit
- Top Right (Entrance)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | Top Left | Top Third | [Choral Chambers Eastern Shaft (Song_05)](#choral-chambers-eastern-shaft-song05) | R1 | Nothing |  | Verified |  |
| TR | Top Right | Top Right (Entrance) | [Whiteward Long Horizontal (Ward_05)](#whiteward-long-horizontal-ward05) | L | Nothing |  | Verified |  |
| ML | Middle Left | Middle Third (Left) | [Whiteward Tunnel Room (Ward_02b)](#whiteward-tunnel-room-ward02b) | R | Nothing |  | Verified |  |
| MR | Middle Right | Middle Third (Right) | [Whiteward Silkeater (Ward_04)](#whiteward-silkeater-ward04) | L | Break Wall Left |  | Verified |  |
| BL | Bottom Left | Bottom Third (Left) | [Whiteward Unravelled Arena Room (Ward_02)](#whiteward-unravelled-arena-room-ward02) | R | Nothing |  | Verified |  |
| BR | Bottom Right | Vertical Shaft (Lower) | [Whiteward Descent Connection (Ward_03)](#whiteward-descent-connection-ward03) | L | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TES | Top to Elevator Shaft | Top Third | Elevator Shaft | Have White Key |  | Verified |  |
| TES | Top to Elevator Shaft | Elevator Shaft | Top Third | Have White Key |  | Verified |  |
| EBL | Elevator to Bottom Left | Elevator Shaft | Bottom Third (Left) | Have White Key |  | Verified |  |
| EBL | Elevator to Bottom Left | Bottom Third (Left) | Elevator Shaft | Have White Key |  | Verified |  |
| MLR | Middle Left to Right | Middle Third (Left) | Middle Third (Right) | Nothing (Jump) |  | Verified |  |
| MLR | Middle Left to Right | Middle Third (Right) | Middle Third (Left) | Nothing (Jump) |  | Verified |  |
| RVL | Right to Vertical Lower | Middle Third (Right) | Vertical Shaft (Lower) | Nothing (Fall) |  | Verified |  |
| RVL | Right to Vertical Lower | Vertical Shaft (Lower) | Middle Third (Right) | Cling Grip OR (Scuttlebrace AND (Medium Flea Brew Stall OR Medium Heal Stall OR Faydown)) OR Silk Soar |  | Verified |  |
| RVU | Right to Vertical Upper | Middle Third (Right) | Vertical Shaft (Upper) | Silk Soar OR (Faydown AND Cling Grip AND Proficient Movement) |  | Verified |  |
| RVU | Right to Vertical Upper | Vertical Shaft (Upper) | Middle Third (Right) | Nothing (Fall) |  | Verified |  |
| VTR | Vertical to Top Right (Entrance) | Vertical Shaft (Upper) | Top Right (Entrance) | Silk Soar OR (Faydown AND Cling Grip AND Proficient Movement) |  | Verified |  |
| VTR | Vertical to Top Right (Entrance) | Top Right (Entrance) | Vertical Shaft (Upper) | Nothing (Fall) |  | Verified |  |
| ETP | Elevator to Pit | Elevator Shaft | Pit | Have White Key |  | Verified |  |
| ETP | Elevator to Pit | Pit | Elevator Shaft | (Cling Grip OR Scuttlebrace OR Silk Soar) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whiteward - Spool Fragment | Pit | Nothing |  | Verified | collectible |  |
| Whiteward Bench | Top Third | Have White Key |  | Verified | bench |  |
| Whiteward - Map Purchase | Vertical Shaft (Lower) | Nothing |  | Verified | collectible |  |
| Set Elevator to Top | Top Third | Nothing |  | Verified | event | Does this need to be defined? |

### Whiteward Sherma Gauntlet (Ward_09)

**Game ID:** Ward_09

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Whiteward Descent Connection (Ward_03)](#whiteward-descent-connection-ward03) | SG | Nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Balm for the Wounded Gauntlet |  | Nothing |  | Verified | gauntlet | Completion for the wish. |
| Balm for the Wounded Wish Granted |  | Defeat Balm for the Wounded Gauntlet |  | Verified | event |  |
| Balm for the Wounded - Spool Fragment |  | Complete Balm for the Wounded Wish Granted |  | Verified | collectible | Completion for the wish. |

### Whiteward Descent Connection (Ward_03)

**Game ID:** Ward_03

**Contributors:** skai

#### Subrooms

- Bottom (Left)
- Spikes
- Bottom (Middle)
- Ascent
- Middle (Left)
- Middle (Right)
- Top
- Bottom Right (Upper)
- Bottom Right (Lower)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | Bottom (Left) | [Whiteward Entrance (Ward_01)](#whiteward-entrance-ward01) | BR | Nothing |  | Verified |  |
| B | Bottom | Bottom Right (Lower) | [Whiteward Descent (Ward_06)](#whiteward-descent-ward06) | T | Nothing |  | Verified |  |
| T | Top | Top | [Whiteward Junk Dump (Ward_07)](#whiteward-junk-dump-ward07) | B | Nothing |  | Verified |  |
| SG | SG | Middle (Left) | [Whiteward Sherma Gauntlet (Ward_09)](#whiteward-sherma-gauntlet-ward09) | L | Complete THE Balm for the Wounded Wish Promised |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLS | Bottom Left to Spikes | Bottom (Left) | Spikes | Spike Pogo OR Dash OR Sprint OR Sharpdart OR Clawline OR Faydown OR Drifter's Cloak OR Have Flea Brew OR Easy Plasmium Phial Stall OR Easy Voltvessels Stall |  | Verified |  |
| BLS | Bottom Left to Spikes | Spikes | Bottom (Left) | Spike Pogo OR Dash OR Sprint OR Sharpdart OR Clawline OR Faydown OR Drifter's Cloak OR Have Flea Brew OR Easy Plasmium Phial Stall OR Easy Voltvessels Stall |  | Verified |  |
| SBR | Spikes to Bottom Right | Spikes | Bottom (Middle) | Spike Pogo  OR Dash OR Sprint OR Sharpdart OR Clawline OR Faydown OR Drifter's Cloak OR Flea Brew OR Easy Plasmium Phial Stall OR Easy Voltvessels Stall |  | Verified |  |
| SBR | Spikes to Bottom Right | Bottom (Middle) | Spikes | Spike Pogo  OR Dash OR Sprint OR Sharpdart OR Clawline OR Faydown OR Drifter's Cloak OR Flea Brew OR Easy Plasmium Phial Stall OR Easy Voltvessels Stall |  | Verified |  |
| BMA | Bottom to Ascent | Bottom (Middle) | Ascent | Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown |  | Verified |  |
| BMA | Bottom to Ascent | Ascent | Bottom (Middle) | Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown |  | Verified |  |
| AML | Ascent to Middle Left | Ascent | Middle (Left) | Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown |  | Verified |  |
| AML | Ascent to Middle Left | Middle (Left) | Ascent | Nothing (Fall) |  | Verified |  |
| AMR | Ascent to Middle Right | Ascent | Middle (Right) | Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown |  | Verified |  |
| AMR | Ascent to Middle Right | Middle (Right) | Ascent | Nothing (Fall) |  | Verified |  |
| MRB | Middle Right to Bottom | Bottom Right (Upper) | Middle (Right) | (Magma Bell AND Silk Soar) OR (Faydown AND Cling Grip) |  | Verified |  |
| MRB | Middle Right to Bottom | Middle (Right) | Bottom Right (Upper) | Nothing (Fall) |  | Verified |  |
| AAT | Ascent to Top | Ascent | Top | Cling Grip OR Silk Soar OR Faydown |  | Verified |  |
| AAT | Ascent to Top | Top | Ascent | Cling Grip OR Silk Soar OR Faydown |  | Verified |  |
| BUL | Bottom Right Upper to Lower | Bottom Right (Lower) | Bottom Right (Upper) | Cling Grip OR Silk Soar |  | Verified |  |
| BUL | Bottom Right Upper to Lower | Bottom Right (Upper) | Bottom Right (Lower) | Nothing (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Injector Band | Middle (Left) | Nothing |  | Verified | collectible |  |

### Whiteward Descent (Ward_06)

**Game ID:** Ward_06

**Contributors:** skai

#### Subrooms

- Descent Rosary Side
- Descent Upper
- Descent Lower

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | Top | Descent Upper | [Whiteward Descent Connection (Ward_03)](#whiteward-descent-connection-ward03) | B | Nothing |  | Verified |  |
| B | Bottom | Descent Lower | [Underworks Twelfth Architect (Under_17)](#underworks-twelfth-architect-under17) | UP | Nothing (Fall) |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LTR | Descent Lower to Rosaries | Descent Lower | Descent Rosary Side | Break Wall Left OR Break Wall Right |  | Verified |  |
| LTR | Descent Lower to Rosaries | Descent Rosary Side | Descent Lower | Break Wall Left OR Break Wall Right |  | Verified |  |
| LTU | Descent Lower to Upper | Descent Lower | Descent Upper | Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown |  | Verified |  |
| LTU | Descent Lower to Upper | Descent Upper | Descent Lower | Nothing (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whiteward - Rosary Cache #1 | Descent Rosary Side | Nothing |  | Verified | collectible |  |
| Whiteward - Rosary Cache #2 | Descent Rosary Side | Nothing |  | Verified | collectible |  |

### Whiteward Junk Dump (Ward_07)

**Game ID:** Ward_07

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | Bottom |  | [Whiteward Descent Connection (Ward_03)](#whiteward-descent-connection-ward03) | T | Nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whiteward - Oath |  | Nothing |  | Verified | lore |  |
| Surgeon's Key |  | Clawline |  | Verified | collectible |  |

### Whiteward Long Horizontal (Ward_05)

**Game ID:** Ward_05

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Whiteward Entrance (Ward_01)](#whiteward-entrance-ward01) | TR | Nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Relic: Choral Commandment (Eastern Whiteward) |  | Nothing |  | Verified | collectible |  |

### Whiteward Silkeater (Ward_04)

**Game ID:** Ward_04

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Whiteward Entrance (Ward_01)](#whiteward-entrance-ward01) | MR | Nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| White Ward: Silkeater |  | Cling Grip OR Scuttlebrace OR Silk Soar OR (Faydown AND Ledge Grab) |  | Verified | collectible |  |

### Whiteward Unravelled Arena Room (Ward_02)

**Game ID:** Ward_02

**Contributors:** skai

#### Subrooms

- Vertical Left
- Surgery Tables (Right)
- Surgery Tables (Left)
- Key Shaft
- Unravelled Arena

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | Top | Vertical Left | [Whiteward Tunnel Room (Ward_02b)](#whiteward-tunnel-room-ward02b) | B | Silk Soar OR Faydown OR Cling Grip OR Scuttlebrace |  | Verified |  |
| R | Right | Surgery Tables (Right) | [Whiteward Entrance (Ward_01)](#whiteward-entrance-ward01) | BL | Nothing |  | Verified |  |
| B | Bottom | Unravelled Arena | [Confession Toll (Under_08)](#confession-toll-under08) | T | Defeat The Unravelled Gauntlet |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SLV | Surgery Left to Vertical | Surgery Tables (Left) | Vertical Left | Ledge Grab OR Faydown OR Clawline OR Silk Soar OR (Proficient Movement AND Scuttlebrace) |  | Verified |  |
| SLV | Surgery Left to Vertical | Vertical Left | Surgery Tables (Left) | Nothing (Falling) |  | Verified |  |
| SRL | Surgery Right to Left | Surgery Tables (Right) | Surgery Tables (Left) | Nothing |  | Verified |  |
| SRL | Surgery Right to Left | Surgery Tables (Left) | Surgery Tables (Right) | Nothing |  | Verified |  |
| SKS | Surgery to Key Shaft | Surgery Tables (Left) | Key Shaft | Have Surgeon's Key |  | Verified |  |
| SKS | Surgery to Key Shaft | Key Shaft | Surgery Tables (Left) | Have Surgeon's Key AND Silk Soar |  | Verified |  |
| KSA | Key Shaft to Arena | Key Shaft | Unravelled Arena | Nothing (Falling) |  | Verified |  |
| KSA | Key Shaft to Arena | Unravelled Arena | Key Shaft | Have Surgeon's Key AND Silk Soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Unravelled - Silk Heart | Unravelled Arena | Defeat Boss: The Unravelled |  | Verified | collectible |  |
| The Unravelled Gauntlet | Unravelled Arena | Nothing |  | Verified | gauntlet |  |
| Boss: The Unravelled | Unravelled Arena | Defeat The Unravelled Gauntlet |  | Verified | boss |  |

### Whiteward Tunnel Room (Ward_02b)

**Game ID:** Ward_02b

**Contributors:** skai

#### Subrooms

- Top Horizontal
- Pickup Section
- Lower Tunnels
- Upper Tunnels
- Center Tunnels

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | Bottom | Lower Tunnels | [Whiteward Unravelled Arena Room (Ward_02)](#whiteward-unravelled-arena-room-ward02) | T | Nothing |  | Verified |  |
| R | Right | Pickup Section | [Whiteward Entrance (Ward_01)](#whiteward-entrance-ward01) | ML | Break Wall Left |  | Verified | There are four walls. |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LUT | Lower to Upper Tunnels | Lower Tunnels | Upper Tunnels | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| LUT | Lower to Upper Tunnels | Upper Tunnels | Lower Tunnels | Nothing (Falling) |  | Verified |  |
| UCT | Upper to Center Tunnels | Center Tunnels | Upper Tunnels | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| UCT | Upper to Center Tunnels | Upper Tunnels | Center Tunnels | Nothing (Falling) |  | Verified |  |
| CTH | Center to Top Horizontal | Center Tunnels | Top Horizontal | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| CTH | Center to Top Horizontal | Top Horizontal | Center Tunnels | Nothing (Falling) |  | Verified |  |
| TTP | Top to Pickup Section | Top Horizontal | Pickup Section | Nothing (Falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Relic: Choral Commandment (Western Whiteward) | Pickup Section | Nothing |  | Verified | collectible |  |

## High Halls

### High Halls Small Slide (Hang_02)

**Game ID:** Hang_02

**Contributors:** samupo

#### Subrooms

- left exit
- right exit
- left platform
- center platform
- right platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right exit | [High Halls Shaft Bottom (Hang_03)](#high-halls-shaft-bottom-hang03) | ML | none |  | Verified |  |
| L | left1 | left exit | [High Halls Entrance (Hang_01)](#high-halls-entrance-hang01) | TP | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | left exit | left platform | invalid |  | Needs verification | placeholder until can map it - original logic is in OG connection |
| V1 | vertical 1 | left platform | left exit | invalid |  | Needs verification | placeholder until can map it - original logic is in OG connection |
| C1 | crossing 1 | left platform | center platform | invalid |  | Needs verification | placeholder until can map it - original logic is in OG connection |
| C1 | crossing 1 | center platform | left platform | invalid |  | Needs verification | placeholder until can map it - original logic is in OG connection |
| C2 | crossing 2 | center platform | right platform | invalid |  | Needs verification | placeholder until can map it - original logic is in OG connection |
| C2 | crossing 2 | right platform | center platform | invalid |  | Needs verification | placeholder until can map it - original logic is in OG connection |
| C3 | crossing 3 | right platform | right exit | invalid |  | Needs verification | placeholder until can map it - original logic is in OG connection |
| C3 | crossing 3 | right exit | right platform | invalid |  | Needs verification | placeholder until can map it - original logic is in OG connection |
| OG | original requirements | left exit | right exit | clawline OR (faydown cloak AND dash AND ledge grab) |  | Verified | delete after remapped |
| OG | original requirements | right exit | left exit | (ledge grab OR clawline OR cling grip OR faydown cloak) AND swim |  | Verified | delete after remapped |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Second Sentinel Encounter | center platform | act 3 AND complete THE second sentinel activation | TODO | Needs verification | event | need to verify this is the correct platform |

### High Halls Shaft Top (Hang_03_top)

**Game ID:** Hang_03_top

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 |  | [High Halls Shaft Bottom (Hang_03)](#high-halls-shaft-bottom-hang03) | T | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| High Halls - Spool Fragment |  | silk soar OR (clawline AND faydown cloak AND cling grip) |  | Verified | collectible |  |

### High Halls Shaft Bottom (Hang_03)

**Game ID:** Hang_03

**Contributors:** samupo

#### Subrooms

- Top
- Top Right
- Middle Left
- Bottom Left
- Bottom Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Top | [High Halls Shaft Top (Hang_03_top)](#high-halls-shaft-top-hang03top) | B | none |  | Verified |  |
| TR | right1 | Top Right | [High Halls Big Slide (Hang_13)](#high-halls-big-slide-hang13) | L | none |  | Verified |  |
| BL | left2 | Bottom Left | [High Halls Small Room (Hang_15)](#high-halls-small-room-hang15) | R | none |  | Verified |  |
| BR | right2 | Bottom Right | [High Halls Flooded Room (Hang_10)](#high-halls-flooded-room-hang10) | L | clear left exit blockade IN high halls flooded room |  | Verified |  |
| ML | left1 | Middle Left | [High Halls Small Slide (Hang_02)](#high-halls-small-slide-hang02) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| B | Bottom Traversal | Bottom Left | Bottom Right | swim OR clawline OR (faydown cloak AND dash) |  | Verified |  |
| B | Bottom Traversal | Bottom Right | Bottom Left | swim OR clawline OR (faydown cloak AND dash) |  | Verified |  |
| B2 | Bottom Right to Mid Left | Bottom Right | Middle Left | ( cling grip AND faydown cloak ) OR clawline |  | Verified |  |
| M | Middle Left to Top Right | Middle Left | Top Right | clawline AND cling grip |  | Verified |  |
| T | Top Right to Top | Top Right | Top | faydown cloak AND (clawline OR (cling grip AND dash)) |  | Verified |  |
| FT | Falling from Top | Top | Middle Left | none |  | Verified | falilng |
| FT2 | Falling from Top 2 | Top | Top Right | clawline OR dash OR faydown cloak |  | Verified |  |
| FM | Falling from Mid | Middle Left | Bottom Left | none |  | Verified | falling |
| FM2 | Falling from Mid 2 | Middle Left | Bottom Right | clawline OR dash OR faydown cloak |  | Verified |  |

#### Check Locations

No check locations defined.

### High Halls Small Room (Hang_15)

**Game ID:** Hang_15

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [High Halls Shaft Bottom (Hang_03)](#high-halls-shaft-bottom-hang03) | BL | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| High Halls - Shell Shard Cache #2 |  | none |  | Verified | collectible |  |

### High Halls Big Slide (Hang_13)

**Game ID:** Hang_13

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [High Halls Big Shaft (Hang_08)](#high-halls-big-shaft-hang08) | TL | clawline AND (ledge grab OR faydown cloak OR dash) |  | Verified |  |
| L | left1 |  | [High Halls Shaft Bottom (Hang_03)](#high-halls-shaft-bottom-hang03) | TR | (swim AND ledge grab) OR (clawline AND dash) OR drifter's cloak |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### High Halls Big Shaft (Hang_08)

**Game ID:** Hang_08

**Contributors:** samupo

#### Subrooms

- Top
- Middle
- Left Spike Exit
- Bottom
- Behind Sentinel Gate

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SL | left3 | Left Spike Exit | [High Halls Flooded Room (Hang_10)](#high-halls-flooded-room-hang10) | R | none |  | Verified |  |
| B | bot1 | Bottom | [High Halls Vault (Hang_06)](#high-halls-vault-hang06) | T | none |  | Verified | One way only (opened from this side) |
| L | left4 | Bottom | [High Halls Baby Room (Hang_16)](#high-halls-baby-room-hang16) | R | none |  | Verified |  |
| NI | right2 | Middle | [High Halls Not Implemented Room (Cog_11)](#high-halls-not-implemented-room-cog11) | L | invalid |  | Verified | NOT IMPLEMENTED BY DEVS |
| R | right1 | Behind Sentinel Gate | [High Halls Sentinel Graveyard (Hang_17b)](#high-halls-sentinel-graveyard-hang17b) | L | none |  | Verified |  |
| ML | left2 | Middle | [High Halls Cogfly Room (Hang_09)](#high-halls-cogfly-room-hang09) | R | none |  | Verified |  |
| TL | left1 | Top | [High Halls Big Slide (Hang_13)](#high-halls-big-slide-hang13) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TF | Falling from Top | Top | Middle | clawline AND drifter's cloak |  | Verified |  |
| S | Spiked Secret | Middle | Left Spike Exit | drifter's cloak AND (cling grip OR clawline) AND break wall left |  | Verified |  |
| SF | Falling from Secret | Left Spike Exit | Bottom | drifter's cloak AND clawline |  | Verified |  |
| MF | Falling from Middle | Middle | Bottom | drifter's cloak AND clawline |  | Verified |  |
| WG | wish gate | Bottom | Behind Sentinel Gate | complete THE final audience wish promised |  | Verified |  |
| WG | wish gate | Behind Sentinel Gate | Bottom | complete THE final audience wish promised |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| High Halls - Rosary Cache | Top | clawline AND (silk soar OR cling grip) |  | Verified | collectible |  |

### High Halls Flooded Room (Hang_10)

**Game ID:** Hang_10

**Contributors:** samupo, herounit

#### Subrooms

- left exit area
- right exit area
- relic spot

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [High Halls Shaft Bottom (Hang_03)](#high-halls-shaft-bottom-hang03) | BR | clear left exit blockade |  | Verified |  |
| R | right1 | right exit area | [High Halls Big Shaft (Hang_08)](#high-halls-big-shaft-hang08) | SL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CL | climb | left exit area | relic spot | ( faydown AND cling grip ) OR ( swim AND easy enemy pogo AND cling grip  ) OR ( swim AND easy enemy pogo AND faydown AND ledge grab ) |  | Verified |  |
| CL | climb | relic spot | left exit area | silk soar AND swim |  | Verified |  |
| WC | water crossing | left exit area | right exit area | swim |  | Verified |  |
| WC | water crossing | right exit area | left exit area | swim |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| relic psalm cylinder high halls | relic spot | none |  | Verified | collectible |  |
| left exit blockade | left exit area | break wall left |  | Verified | blockade |  |

#### Notes

this room needs swimming requirements added to cross it - at least two subrooms

### High Halls Cogfly Room (Hang_09)

**Game ID:** Hang_09

**Contributors:** samupo, herounit

#### Subrooms

- main area
- down the drain

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | main area | [High Halls Big Shaft (Hang_08)](#high-halls-big-shaft-hang08) | ML | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | main area | down the drain | none (falling) |  | Verified | a tiny bit tight but no requirements to get down here |
| V1 | vertical 1 | down the drain | main area | cling grip OR ( scuttlebrace AND ledge grab ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogfly | main area | craftmetals 1 |  | Verified | collectible |  |
| High Halls - Shell Shard Cache #1 | down the drain | none |  | Verified | collectible |  |

### High Halls Baby Room (Hang_16)

**Game ID:** Hang_16

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [High Halls Big Shaft (Hang_08)](#high-halls-big-shaft-hang08) | L | none |  | Verified |  |
| S | door1 |  | TODO |  | faydown cloak AND cling grip | TODO |  | Secret door to Hang_14 (not in the map, doesn't have any checks) |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Relic Psalm Cylinder (High Halls) |  | none |  | Verified | collectible |  |

### High Halls Vault (Hang_06)

**Game ID:** Hang_06

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 |  | TODO |  | (ledge grab OR faydown cloak OR silk soar) AND have Simple Key Rosary Bank | TODO |  |  |
| L | left1 |  | [High Halls Arena (Hang_04)](#high-halls-arena-hang04) | R | none |  | Verified |  |
| B | bot1 |  | [High Halls Corridor (Hang_07)](#high-halls-corridor-hang07) | T | none |  | Verified | One way lever (opens from this side) |
| R | right1 |  | [High Halls Ventrica (Hang_06b)](#high-halls-ventrica-hang06b) | L | none |  | Verified |  |
| T | top1 |  | [High Halls Big Shaft (Hang_08)](#high-halls-big-shaft-hang08) | B | cling grip OR (faydown cloak AND ledge grab) OR silk soar |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### High Halls Ventrica (Hang_06b)

**Game ID:** Hang_06b

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [High Halls Vault (Hang_06)](#high-halls-vault-hang06) | R | none |  | Verified |  |
| V | door_tubeEnter |  | [Ventrica Menu](#ventrica-menu) | HH | unlock Ventrica High Halls |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| High Halls - Map Purchase |  | rosaries 70 |  | Verified | collectible |  |
| Ventrica High Halls Rosary Lock |  | rosaries 80 |  | Verified | lock |  |
| Ventrica High Halls |  | unlock Ventrica High Halls Rosary Lock |  | Verified | travel |  |

### High Halls Conductor (Hang_12)

**Game ID:** Hang_12

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [High Halls Arena (Hang_04)](#high-halls-arena-hang04) | L | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Conductors Melody |  | Act 2 |  | Verified | collectible |  |

### High Halls Arena (Hang_04)

**Game ID:** Hang_04

**Contributors:** samupo

#### Subrooms

- left of gauntlet
- gauntlet arena
- right of gauntlet

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left of gauntlet | [High Halls Conductor (Hang_12)](#high-halls-conductor-hang12) | R | none |  | Verified |  |
| R | right1 | right of gauntlet | [High Halls Vault (Hang_06)](#high-halls-vault-hang06) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RG | right gauntlet door | right of gauntlet | gauntlet arena | none (starts gauntlet) |  | Verified |  |
| RG | right gauntlet door | gauntlet arena | right of gauntlet | defeat gauntlet fight |  | Verified |  |
| LG | left gauntlet door | gauntlet arena | left of gauntlet | defeat gauntlet fight |  | Verified |  |
| LG | left gauntlet door | left of gauntlet | gauntlet arena | defeat gauntlet fight | TODO | Needs verification | need to double check this for room rando |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| gauntlet fight | gauntlet arena | none |  | Verified | gauntlet |  |

### High Halls Sentinel Graveyard (Hang_17b)

**Game ID:** Hang_17b

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [High Halls Big Shaft (Hang_08)](#high-halls-big-shaft-hang08) | R | none |  | Verified | gate on the other side has no influence on this exit |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Second Sentinel Boss Fight |  | none | TODO | Verified | boss | normally would be `complete THE Final Audience Wish Promised` but team cherry did nothing to protect the boss fight from starting without the wish - not ideal for entrance rando, and might need to be patched |
| Final Audience Wish Granted |  | complete THE Final Audience Wish Promised  AND defeat Second Sentinel Boss Fight |  | Verified | event | assuming this becomes impossible if the boss is defeated before the wish is accepted |
| Reserve Bind |  | complete Final Audience Wish Granted |  | Verified | collectible |  |

### High Halls Not Implemented Room (Cog_11)

**Game ID:** Cog_11

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [High Halls Big Shaft (Hang_08)](#high-halls-big-shaft-hang08) | NI | invalid |  | Verified | this room does not exist, so therefore neither does this transition |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

This room does not exist in the game. The map chunk exists, and this room is included in the area map, but it has no reachable room in the game. It only exists in the docs to make it not a problem in the area map. Also to break whatever room reachability fuzzing logic Moriko has set up.

## Bilewater

### Bilewater Arena Shack (Shadow_Bilehaven_Room)

**Game ID:** Shadow_Bilehaven_Room

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Bilewater Groal Arena (Shadow_18)](#bilewater-groal-arena-shadow18) | D | nada |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Seeker's Soul |  | none |  | Verified | collectible |  |

### Bilewater Bellway (Bellway_Shadow)

**Game ID:** Bellway_Shadow

**Contributors:** Herchey

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door |  | [Bellway Menu](#bellway-menu) | BW | none |  | Verified |  |
| L | left |  | [Bilewater Organ Entrance (Shadow_04)](#bilewater-organ-entrance-shadow04) | LR | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater - Bellway |  | rosaries 60 |  | Verified | travel |  |
| Bilewater Bellway Bench |  | none |  | Verified | bench |  |
| Craw Summons |  | craw summons ready |  | Verified | collectible |  |

### Bilewater Bullshit Bench (Shadow_15)

**Game ID:** Shadow_15

**Contributors:** Herchey and The Black Dahlia Murder (band)

#### Subrooms

- upper
- lower

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | lower | [Bilewater Upper Bloatroach Tower (Shadow_01)](#bilewater-upper-bloatroach-tower-shadow01) | ML | none |  | Verified |  |
| UR | upper right | upper | [Bilewater Upper Bloatroach Tower (Shadow_01)](#bilewater-upper-bloatroach-tower-shadow01) | UL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper to lower | upper | lower | swim |  | Verified |  |
| UL | upper to lower | lower | upper | invalid |  | Verified | Going back up to upper is impossible. One way connection. |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater Bullshit Bench Exit Wall | lower | break wall right |  | Verified | blockade |  |

### Bilewater Citadel Exit (Shadow_22)

**Game ID:** Shadow_22

**Contributors:** herchey all by himself this time like a big, strong man

#### Subrooms

- pond
- platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T1 | top1 | pond | [Whispering Vaults Totally Not White Palace (Library_07)](#whispering-vaults-totally-not-white-palace-library07) | B1 | invalid |  | Verified |  |
| T2 | top2 | pond | [Whispering Vaults Totally Not White Palace (Library_07)](#whispering-vaults-totally-not-white-palace-library07) | B2 | invalid |  | Verified |  |
| T3 | top3 | pond | [Whispering Vaults Totally Not White Palace (Library_07)](#whispering-vaults-totally-not-white-palace-library07) | B3 | invalid |  | Verified |  |
| B | bot1 | platform | [Bilewater West Secret Rooms (Shadow_20)](#bilewater-west-secret-rooms-shadow20) | C | nada |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pp | pond and platform | pond | platform | swim AND ( cling grip OR ledge grab OR faydown cloak ) |  | Verified |  |
| pp | pond and platform | platform | pond | swim |  | Verified |  |

#### Check Locations

No check locations defined.

### Bilewater East Bench (Shadow_08)

**Game ID:** Shadow_08

**Contributors:** Herchey and Sadako Yamamura

#### Subrooms

- top right
- right room
- bench room
- bench entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | top right | [Bilewater Lower Trap Gauntlet Hall (Shadow_10)](#bilewater-lower-trap-gauntlet-hall-shadow10) | LR | none |  | Verified |  |
| L | left | bench entrance | [Bilewater Mothleaf Hall (Shadow_27)](#bilewater-mothleaf-hall-shadow27) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RB | right to bench | right room | bench room | (cling grip OR scuttlebrace) AND (swim OR clawline OR sharpdart OR drifter's cloak OR faydown cloak) AND break wall left |  | Verified | breakable wall |
| RB | right to bench | bench room | right room | break wall right AND (cling grip OR silk soar OR scuttlebrace) |  | Verified | breakable wall |
| BE | bench entrance to bench room | bench entrance | bench room | break wall right |  | Verified | breakable wall |
| BE | bench entrance to bench room | bench room | bench entrance | break wall left |  | Verified | breakable wall |
| TR | top right to right | top right | right room | none |  | Verified |  |
| TR | top right to right | right room | top right | cling grip AND faydown cloak |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater - Storeroom Record | bench room | none |  | Verified | lore |  |
| Bilewater East Bench | bench room | none |  | Verified | bench |  |
| Bilewater East Bench Left Exit Wall | bench entrance | break wall left |  | Verified | blockade |  |

### Bilewater East Column (Shadow_09)

**Game ID:** Shadow_09

**Contributors:** Herchey Man

#### Subrooms

- upper
- behind wall
- middle
- floor
- nest

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | nest | [Bilewater Weavenest Murglin (Shadow_Weavehome)](#bilewater-weavenest-murglin-shadowweavehome) | L | needolin |  | Verified |  |
| ML | middle left | behind wall | [Bilewater Flea Rescue (Shadow_28)](#bilewater-flea-rescue-shadow28) | R | break wall left |  | Verified | breakable wall depending on entrance direction |
| UL | upper left | upper | [Bilewater Lower East Hall (Shadow_03)](#bilewater-lower-east-hall-shadow03) | R | none |  | Verified |  |
| LL | lower left | floor | [Bilewater Sinner's Entrance (Shadow_05)](#bilewater-sinners-entrance-shadow05) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FM | Floor to middle | floor | middle | Silk soar OR ((cling grip OR scuttlebrace) AND (clawline OR sharpdart OR faydown cloak)) OR (cling grip AND drifter’s cloak) |  | Verified |  |
| FM | Floor to middle | middle | floor | none |  | Verified |  |
| MU | middle to upper | middle | upper | Silk soar OR ((cling grip OR scuttlebrace) AND (clawline OR sharpdart OR faydown cloak)) OR (cling grip AND drifter’s cloak) |  | Verified |  |
| MU | middle to upper | upper | middle | none |  | Verified |  |
| FN | floor to nest | floor | nest | swim |  | Verified |  |
| FN | floor to nest | nest | floor | swim |  | Verified |  |
| MBW | middle to behind wall | middle | behind wall | break wall left |  | Verified |  |
| MBW | middle to behind wall | behind wall | middle | break wall right |  | Verified |  |

#### Check Locations

No check locations defined.

### Bilewater Flea Rescue (Shadow_28)

**Game ID:** Shadow_28

**Contributors:** Herchey and absolutely no one else

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Bilewater East Column (Shadow_09)](#bilewater-east-column-shadow09) | ML | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Bilewater - Thieves |  | Scuttlebrace OR cling grip |  | Verified | collectible |  |

### Bilewater Groal Arena (Shadow_18)

**Game ID:** Shadow_18

**Contributors:** Herchey and Dante (the Divine Comedy one, not DMC)

#### Subrooms

- left of arena
- arena
- right of arena

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right of arena | [Bilewater Upper Trap Gauntlet Hall (Shadow_12)](#bilewater-upper-trap-gauntlet-hall-shadow12) | L | none |  | Verified |  |
| D | door | left of arena | [Bilewater Arena Shack (Shadow_Bilehaven_Room)](#bilewater-arena-shack-shadowbilehavenroom) | L | none |  | Verified |  |
| L | left | left of arena | [Bilewater Upper Bloatroach Tower (Shadow_01)](#bilewater-upper-bloatroach-tower-shadow01) | UR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LA | left to arena | left of arena | arena | none |  | Verified |  |
| LA | left to arena | arena | left of arena | none |  | Verified |  |
| RA | right to arena | right of arena | arena | clawline OR sharpdart OR drifter's cloak OR sharpdart OR run |  | Verified |  |
| RA | right to arena | arena | right of arena | clawline OR sharpdart OR drifter's cloak OR sharpdart OR run |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Groal the Great | arena | none |  | Verified | boss | Technically none, lol. |
| Bilewater - Bilehaven Plaque | right of arena | cling grip OR silk soar OR scuttlebrace |  | Verified | lore |  |

### Bilewater Hanging Corpse Room (Shadow_16)

**Game ID:** Shadow_16

**Contributors:** Herchey and Dude (his neighbor's cat)

#### Subrooms

- left
- right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right | [Bilewater Lower Trap Gauntlet Hall (Shadow_10)](#bilewater-lower-trap-gauntlet-hall-shadow10) | L | none |  | Verified |  |
| L | left | left | [Bilewater Upper Bloatroach Tower (Shadow_01)](#bilewater-upper-bloatroach-tower-shadow01) | MR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CR | cross the room | left | right | cling grip AND (clawline OR (faydown cloak AND (drifter's cloak OR (sharpdart AND dash)))) |  | Verified |  |
| CR | cross the room | right | left | drifter's cloak OR clawline OR (faydown AND (run OR sharpdart OR easy beast pogo)) OR (sharpdart AND (swim OR easy beast pogo)) |  | Verified |  |

#### Check Locations

No check locations defined.

### Bilewater Lower Bloatroach Tower (Shadow_02)

**Game ID:** Shadow_02

**Contributors:** Herchey and Wesker (his cat)

#### Subrooms

- low left
- low right
- mid right
- halfway up
- rosary plat
- up left

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | low right | [Bilewater Lower East Hall (Shadow_03)](#bilewater-lower-east-hall-shadow03) | L | none |  | Verified |  |
| UR | upper right | halfway up | [Bilewater Upper East Column (Shadow_26)](#bilewater-upper-east-column-shadow26) | LL | (clawline OR enemy pogo) AND (faydown cloak OR drifter's cloak) |  | Verified |  |
| LL | lower left | low left | [Bilewater West Hall (Shadow_04b)](#bilewater-west-hall-shadow04b) | R | none |  | Verified |  |
| MR | middle right | mid right | [Bilewater Shakra Room (Shadow_23)](#bilewater-shakra-room-shadow23) | L | none |  | Verified |  |
| UL | upper left | up left | [Bilewater Upper West Column (Shadow_14)](#bilewater-upper-west-column-shadow14) | LR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LOW | low left and right | low left | low right | swim OR dash OR clawline OR sharpdart OR faydown cloak OR drifter's cloak OR easy beast pogo |  | Verified |  |
| LOW | low left and right | low right | low left | swim OR dash OR clawline OR sharpdart OR faydown cloak OR drifter's cloak OR easy beast pogo |  | Verified |  |
| LLM | low left to mid | low left | mid right | ((faydown cloak AND cling grip) OR silk soar) AND (clawline OR sharpdart OR drifter's cloak OR faydown cloak) |  | Verified |  |
| LLM | low left to mid | mid right | low left | silk soar OR clawline OR sharpdart OR drifter's cloak OR faydown cloak OR dash |  | Verified |  |
| LRM | low right to mid | low right | mid right | silk soar AND faydown cloak AND cling grip |  | Verified | Pretty goddamn precise from the silk soar to faydown. Maybe easy_skip though. Very easy to try again without penalty. |
| LRM | low right to mid | mid right | low right | none |  | Verified | falling |
| MUR | mid to halfway | mid right | halfway up | cling grip AND (clawline OR faydown cloak OR (drifter's cloak AND enemy pogo)) |  | Verified |  |
| MUR | mid to halfway | halfway up | mid right | none |  | Verified | falling |
| UPR | halfway to rosary | halfway up | rosary plat | faydown cloak AND (clawline OR enemy pogo) |  | Verified |  |
| UPR | halfway to rosary | rosary plat | halfway up | none |  | Verified | falling |
| HUL | halfway to upper left | halfway up | up left | faydown cloak AND cling grip AND (clawline OR enemy pogo) |  | Verified |  |
| HUL | halfway to upper left | up left | halfway up | none |  | Verified | falling |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater - Frayed Rosary String | rosary plat | none |  | Verified | collectible |  |

### Bilewater Lower East Hall (Shadow_03)

**Game ID:** Shadow_03

**Contributors:** Herchey and Peter Griffin from Family Guy

#### Subrooms

- right hall
- left platform
- left lower
- under upper
- upper

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right hall | [Bilewater East Column (Shadow_09)](#bilewater-east-column-shadow09) | UL | none |  | Verified |  |
| C | ceiling | upper | [Bilewater Lower East Hall Secret (Shadow_21)](#bilewater-lower-east-hall-secret-shadow21) | L | Faydown cloak OR cling grip OR silk soar OR scuttlebrace |  | Verified |  |
| L | left | left platform | [Bilewater Lower Bloatroach Tower (Shadow_02)](#bilewater-lower-bloatroach-tower-shadow02) | LR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LLL | left to left lower | left platform | left lower | none |  | Verified |  |
| LLL | left to left lower | left lower | left platform | (cling grip AND (swim OR clawline OR sharpdart OR drifter’s cloak OR run OR dash)) OR faydown cloak |  | Verified |  |
| LLU | left lower to upper | left lower | upper | silk soar |  | Verified |  |
| LLU | left lower to upper | upper | left lower | none |  | Verified |  |
| LUU | left lower to under upper | left lower | under upper | none |  | Verified |  |
| LUU | left lower to under upper | under upper | left lower | Ledge grab OR cling grip OR scuttlebrace |  | Verified |  |
| RUU | right to under upper | right hall | under upper | ((cling grip OR ledge grab) AND (swim OR clawline OR sharpdart OR drifter’s cloak OR run OR dash)) OR faydown cloak |  | Verified |  |
| RUU | right to under upper | under upper | right hall | swim OR run OR sharpdart OR clawline OR scuttlebrace OR drifter's cloak OR faydown cloak OR easy hunter pogo OR easy beast pogo OR easy architect pogo |  | Verified |  |
| UUU | under upper to upper | under upper | upper | Cling grip OR silk soar |  | Verified |  |
| UUU | under upper to upper | upper | under upper | none |  | Verified |  |

#### Check Locations

No check locations defined.

### Bilewater Lower East Hall Secret (Shadow_21)

**Game ID:** Shadow_21

**Contributors:** Herchey and Castle Guard 3

#### Subrooms

- lower area
- upper area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | lower | lower area | [Bilewater Lower East Hall (Shadow_03)](#bilewater-lower-east-hall-shadow03) | C | nada |  | Verified |  |
| SC | slab capture | upper area | [Slab Capture](#slab-capture) | BW | after Get Kidnapped |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | lower area | upper area | clawline OR (enemy pogo AND (cling grip OR ledge grab OR faydown cloak OR drifter's cloak OR dash)) |  | Verified | converted get kidnapped into subroom connection to simplify kidnapping requirements |
| V1 | vertical 1 | upper area | lower area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Wardenfly | upper area | ( act 1 AND act 2 ) AND defeat THE Bell Beast Boss Fight AND (  after Lace Second Encounter IN Choral Chambers Eastern Shaft OR after Lace Second Encounter IN Grand Bellway Shaft ) |  | Verified | enemy | per the wiki |
| Get Kidnapped | upper area | after Wardenfly |  | Verified | logic-point |  |

### Bilewater Lower Trap Gauntlet Hall (Shadow_10)

**Game ID:** Shadow_10

**Contributors:** Herchey and Leon Sexgod Kennedy

#### Subrooms

- bottom
- right door plat
- left door plat
- flea room
- below flea
- bottom right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | bottom right | [Bilewater East Bench (Shadow_08)](#bilewater-east-bench-shadow08) | C | none |  | Verified | breakable wall |
| L | left | left door plat | [Bilewater Hanging Corpse Room (Shadow_16)](#bilewater-hanging-corpse-room-shadow16) | R | none |  | Verified |  |
| R | right | right door plat | [Bilewater Vertical Sac Pogo Room (Shadow_19)](#bilewater-vertical-sac-pogo-room-shadow19) | LL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LM | left to mid | left door plat | below flea | (cling grip OR scuttlebrace) AND (swim OR dash OR clawline OR sharpdart OR faydown cloak OR drifter's cloak) |  | Verified |  |
| LM | left to mid | below flea | left door plat | (cling grip OR scuttlebrace) AND (swim OR run OR clawline OR sharpdart OR faydown cloak OR drifter's cloak OR easy beast pogo) |  | Verified |  |
| MF | mid to flea | below flea | flea room | cling grip OR scuttlebrace |  | Verified |  |
| MF | mid to flea | flea room | below flea | none |  | Verified |  |
| MBR | mid to bottom right | below flea | bottom | break wall right |  | Verified |  |
| MBR | mid to bottom right | bottom | below flea | cling grip OR scuttlebrace |  | Verified |  |
| MRP | mid to right plat | below flea | right door plat | faydown cloak AND cling grip |  | Verified |  |
| MRP | mid to right plat | right door plat | below flea | none |  | Verified | falling |
| WB | wall breakthrough | bottom | bottom right | break wall right |  | Verified |  |
| WB | wall breakthrough | bottom right | bottom | break wall left |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Bilehaven | flea room | break vines left |  | Verified | collectible |  |
| Bilewater - Shell Shard Cache #1 | bottom | attack up AND swim |  | Verified | collectible |  |
| Bilewater - Shell Shard Cache #2 | bottom | attack up AND swim |  | Verified | collectible |  |

### Bilewater Mothleaf Hall (Shadow_27)

**Game ID:** Shadow_27

**Contributors:** Herchey and Sherma (he was very helpful)

#### Subrooms

- left
- right
- center ground
- behind wall

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left | [Bilewater Upper East Column (Shadow_26)](#bilewater-upper-east-column-shadow26) | UR | none |  | Verified |  |
| R | right | behind wall | [Bilewater East Bench (Shadow_08)](#bilewater-east-bench-shadow08) | L | none |  | Verified | Only opens when breaking the left wall in shadow_08 |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LC | left to center | left | center ground | swim OR (clawline OR enemy pogo) |  | Verified |  |
| LC | left to center | center ground | left | swim OR (clawline OR enemy pogo) |  | Verified |  |
| RC | right to center | right | center ground | (drifter's cloak OR faydown cloak OR clawline OR sharpdart) OR swim |  | Verified |  |
| RC | right to center | center ground | right | (drifter's cloak OR faydown cloak OR clawline OR sharpdart) OR swim |  | Verified |  |
| RW | right to wall | right | behind wall | prereq Bilewater East - Breakable Wall |  | Verified |  |
| RW | right to wall | behind wall | right | prereq Bilewater East - Breakable Wall |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater East - Memory Locket | right | none |  | Verified | collectible |  |
| Bilewater East - Breakable Wall | behind wall | prereq Bilewater East Bench Left Exit Wall IN Bilewater East Bench |  | Verified | blockade |  |

### Bilewater Northeast Tiny Room (Shadow_25)

**Game ID:** Shadow_25

**Contributors:** Herchey and NOT 8bitdo (awful ass controller firmware)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Bilewater Vertical Sac Pogo Room (Shadow_19)](#bilewater-vertical-sac-pogo-room-shadow19) | LR | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater - Shell Shard Cache #5 |  | silk soar OR faydown cloak OR (ledge grab AND (sharpdart OR clawline)) OR (cling grip AND easy beast pogo) |  | Verified | resource |  |
| Bilewater - Shell Shard Cache #6 |  | silk soar OR faydown cloak OR (ledge grab AND (sharpdart OR clawline)) OR (cling grip AND easy beast pogo) |  | Verified | resource |  |
| Bilewater - Shell Shard Cache #7 |  | silk soar OR faydown cloak OR (ledge grab AND (sharpdart OR clawline)) OR (cling grip AND easy beast pogo) |  | Verified | resource |  |

### Bilewater Organ Entrance (Shadow_04)

**Game ID:** Shadow_04

**Contributors:** Herchey and Bill Gates

#### Subrooms

- up right
- ceiling
- left
- lower right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | lower right | [Bilewater Bellway (Bellway_Shadow)](#bilewater-bellway-bellwayshadow) | L | break wall right |  | Verified |  |
| L | left | left | [Exhaust Organ Exterior (Dust_09)](#exhaust-organ-exterior-dust09) | R | none |  | Verified |  |
| C | ceiling | ceiling | [Bilewater West Secret Rooms (Shadow_20)](#bilewater-west-secret-rooms-shadow20) | L | cling grip OR scuttlebrace OR silk soar |  | Verified |  |
| UR | upper right | up right | [Bilewater West Hall (Shadow_04b)](#bilewater-west-hall-shadow04b) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LLR | left to low right | left | lower right | drifter's cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace OR run OR easy hunter pogo OR easy beast pogo OR easy architect pogo OR easy shaman pogo OR ledge grab OR cling grip |  | Verified |  |
| LLR | left to low right | lower right | left | drifter's cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace OR run OR easy hunter pogo OR easy beast pogo OR easy architect pogo OR easy shaman pogo OR ledge grab OR cling grip |  | Verified |  |
| LU | left to up right | left | up right | faydown cloak OR silk soar OR (cling grip AND (drifter's cloak OR (clawline AND ledge grab))) |  | Verified |  |
| LU | left to up right | up right | left | none |  | Verified |  |
| UC | up right to ceiling | up right | ceiling | ledge grab OR cling grip OR faydown cloak OR silk soar |  | Verified |  |
| UC | up right to ceiling | ceiling | up right | none |  | Verified |  |

#### Check Locations

No check locations defined.

### Bilewater Shakra Room (Shadow_23)

**Game ID:** Shadow_23

**Contributors:** Herchey ft. Lil Jon

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Bilewater Lower Bloatroach Tower (Shadow_02)](#bilewater-lower-bloatroach-tower-shadow02) | MR | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater - Map Purchase |  | none |  | Verified | collectible |  |

### Bilewater Sinner's Entrance (Shadow_05)

**Game ID:** Shadow_05

**Contributors:** Herchey and the big man upstairs (Jesus)

#### Subrooms

- left quarter
- left rosary platform
- middle quarter
- right quarter

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right quarter | [Bilewater East Column (Shadow_09)](#bilewater-east-column-shadow09) | LL | none |  | Verified |  |
| L | left | left quarter | [Sinner's Road Vertical Hall East (Dust_06)](#sinners-road-vertical-hall-east-dust06) | UR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LLR | left quarter to left rosary | left quarter | left rosary platform | silk soar OR (faydown cloak AND ledge grab) |  | Verified |  |
| LLR | left quarter to left rosary | left rosary platform | left quarter | none |  | Verified |  |
| LMQ | left quarter to middle quarter | left quarter | middle quarter | (cling grip AND (drifter’s cloak OR clawline OR sharpdart OR (faydown cloak AND swim))) OR (faydown cloak AND scuttlebrace AND swim) OR ((clawline OR sharpdart OR run) AND scuttlebrace) |  | Verified |  |
| LMQ | left quarter to middle quarter | middle quarter | left quarter | Drifter’s cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace OR run OR dash OR swim OR easy hunter pogo OR easy beast pogo OR easy architect pogo OR easy shaman pogo |  | Verified |  |
| MQL | middle quarter to left rosary | middle quarter | left rosary platform | Clawline OR sharpdart OR (ledge grab AND (drifter’s cloak OR run)) |  | Verified | (run AND scuttlebrace) is possible, but probably easy_skips |
| MQL | middle quarter to left rosary | left rosary platform | middle quarter | Clawline OR drifter’s cloak OR sharpdart OR dash OR (run AND (faydown cloak OR cling grip OR scuttlebrace OR easy architect pogo OR easy beast pogo)) |  | Verified |  |
| RQM | right quarter to middle quarter | right quarter | middle quarter | Drifter’s cloak OR faydown cloak OR sharpdart OR clawline OR swim OR scuttlebrace OR run OR easy beast pogo OR easy architect pogo |  | Verified |  |
| RQM | right quarter to middle quarter | middle quarter | right quarter | (silk soar AND (easy beast pogo OR dash OR clawline OR sharpdart OR drifter’s cloak OR faydown OR scuttlebrace)) OR (cling grip AND (clawline OR sharpdart OR faydown cloak OR (drifter’s cloak AND ledge grab))) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater - Rosary Cache #1 | left rosary platform | none |  | Verified | collectible |  |
| Bilewater - Rosary Cache #2 | middle quarter | (Faydown cloak AND (ledge grab OR scuttlebrace)) OR silk soar OR cling grip |  | Verified | collectible |  |

### Bilewater Slubberlug River (Shadow_13)

**Game ID:** Shadow_13

**Contributors:** Herchey and pannenkoek2012

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Bilewater Spike Ball Ceiling Trap Room (Shadow_11)](#bilewater-spike-ball-ceiling-trap-room-shadow11) | R | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater - Mask Shard |  | cling grip AND (clawline OR (sharpdart AND (faydown cloaK OR enemy pogo)) OR (faydown cloak AND drifter's cloak)) |  | Verified | collectible |  |

### Bilewater Spike Ball Ceiling Trap Room (Shadow_11)

**Game ID:** Shadow_11

**Contributors:** Herchey and Me

#### Subrooms

- upper
- lower

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | upper | [Bilewater Slubberlug River (Shadow_13)](#bilewater-slubberlug-river-shadow13) | L | none |  | Verified |  |
| L | left | lower | [Bilewater Upper East Column (Shadow_26)](#bilewater-upper-east-column-shadow26) | LR | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| UD | up and down | upper | lower | none |  | Verified |  |
| UD | up and down | lower | upper | cling grip OR silk soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater - Shell Shard Cache #3 | lower | none |  | Verified | collectible |  |
| Bilewater - Shell Shard Cache #4 | lower | none |  | Verified | collectible |  |
| Quick Sling | upper | (cling grip OR silk soar) AND attack up |  | Verified | collectible | up attack for breakable wall |

### Bilewater Upper Bloatroach Tower (Shadow_01)

**Game ID:** Shadow_01

**Contributors:** Herchey and Red (his cat)

#### Subrooms

- lower left
- lower right
- middle left
- middle right
- upper left
- upper right
- top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MR | middle right | middle right | [Bilewater Hanging Corpse Room (Shadow_16)](#bilewater-hanging-corpse-room-shadow16) | L | none |  | Verified |  |
| UR | upper right | upper right | [Bilewater Groal Arena (Shadow_18)](#bilewater-groal-arena-shadow18) | L | none |  | Verified |  |
| LR | lower right | lower right | [Bilewater Upper East Column (Shadow_26)](#bilewater-upper-east-column-shadow26) | UL | none |  | Verified |  |
| ML | middle left | middle left | [Bilewater Bullshit Bench (Shadow_15)](#bilewater-bullshit-bench-shadow15) | LR | prereq Bilewater Bullshit Bench Exit Wall IN Bilewater Bullshit Bench |  | Verified | Cannot enter from right until broken from left. |
| UL | upper left | upper left | [Bilewater Bullshit Bench (Shadow_15)](#bilewater-bullshit-bench-shadow15) | UR | none |  | Verified |  |
| LL | lower left | lower left | [Bilewater Upper West Column (Shadow_14)](#bilewater-upper-west-column-shadow14) | UR | none |  | Verified |  |
| C | ceiling | top | [Putrified Ducts Connection To Bilewater (Aqueduct_04)](#putrified-ducts-connection-to-bilewater-aqueduct04) | F | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LLR | lower left to lower right | lower left | lower right | swim OR (dash AND (faydown cloak OR cling grip OR enemy pogo)) OR (faydown cloak AND drifter's cloak) |  | Verified | Due to the nature of the room, enemy pogos are expected here |
| LLR | lower left to lower right | lower right | lower left | (swim AND faydown cloak AND (ledge grab OR cling grip)) OR clawline OR (cling grip AND faydown cloak AND (enemy pogo OR clawline)) |  | Verified | Due to the nature of the room, enemy pogos are expected here |
| LMR | lower left to middle right | lower left | middle right | cling grip AND ((faydown cloak AND (clawline OR enemy pogo)) OR (drifter's cloak AND clawline)) |  | Verified | Due to the nature of the room, enemy pogos are expected here |
| LMR | lower left to middle right | middle right | lower left | swim OR enemy pogo OR clawline OR dash |  | Verified | Dash only is very easily possible if the nearby bloatroach is dead |
| RML | middle right to middle left | middle right | middle left | cling grip AND  ((drifter's cloak AND (sharpdart OR clawline OR (enemy pogo AND ledge grab))) OR (faydown cloak AND (drifter's cloak OR dash OR clawline OR sharpdart)) OR (run AND faydown cloak AND (clawline OR enemy pogo))) |  | Verified |  |
| RML | middle right to middle left | middle left | middle right | drifter's cloak OR faydown cloak OR clawline OR sharpdart OR dash OR run |  | Verified | Doing this with only run is a pretty precise coyote jump to make it past the spikes. easy_skips maybe? |
| URT | upper right to top | upper right | top | cling grip AND (dash OR clawline OR (faydown cloak AND ledge grab) OR (drifter's cloak AND enemy pogo)) |  | Verified |  |
| URT | upper right to top | top | upper right | none |  | Verified |  |
| MLL | middle left to upper left | middle left | upper left | faydown cloak AND (ledge grab OR cling grip) AND (enemy pogo OR clawline) |  | Verified |  |
| MLL | middle left to upper left | upper left | middle left | drifter's cloak OR faydown cloak OR clawline OR sharpdart OR run OR dash OR enemy pogo OR scuttlebrace |  | Verified | Throw scuttle into easy_skips probably because it's not as intuitive |
| ULR | upper left to upper right | upper left | upper right | faydown cloak AND cling grip AND (enemy pogo OR sharpdart OR clawline) |  | Verified |  |
| ULR | upper left to upper right | upper right | upper left | drifter's cloak OR (cling grip AND (dash OR sharpdart OR clawline OR faydown cloak OR easy beast pogo)) |  | Verified |  |
| MLT | middle left to top | middle left | top | silk soar |  | Verified |  |
| MLT | middle left to top | top | middle left | none |  | Verified | falling |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| collapsible bridge | upper right | attack left |  | Verified | blockade |  |

### Bilewater Upper East Column (Shadow_26)

**Game ID:** Shadow_26

**Contributors:** Herchey and Super Mario RPG

#### Subrooms

- low left door
- low right door
- up left door
- up right door

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | up left door | [Bilewater Upper Bloatroach Tower (Shadow_01)](#bilewater-upper-bloatroach-tower-shadow01) | LR | none |  | Verified |  |
| LL | lower left | low left door | [Bilewater Lower Bloatroach Tower (Shadow_02)](#bilewater-lower-bloatroach-tower-shadow02) | UR | none |  | Verified |  |
| LR | lower right | low right door | [Bilewater Spike Ball Ceiling Trap Room (Shadow_11)](#bilewater-spike-ball-ceiling-trap-room-shadow11) | L | none |  | Verified |  |
| UR | upper right | up right door | [Bilewater Mothleaf Hall (Shadow_27)](#bilewater-mothleaf-hall-shadow27) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LDC | low door crossing | low left door | low right door | clawline OR sharpdart OR drifter's cloak OR run |  | Verified |  |
| LDC | low door crossing | low right door | low left door | (ledge grab AND (faydown cloak OR easy beast pogo)) OR drifter's cloak OR clawline OR sharpdart OR run |  | Verified |  |
| TC | the climb | low left door | up left door | cling grip AND faydown cloak |  | Verified |  |
| TC | the climb | up left door | low left door | none |  | Verified |  |
| UDC | up door crossing | up left door | up right door | cling grip OR scuttlebrace OR (silk soar AND (clawline OR sharpdart OR drifter's cloak OR (faydown cloak AND ledge grab))) |  | Verified |  |
| UDC | up door crossing | up right door | up left door | clawline OR sharpdart OR faydown cloak OR drifter's cloak OR easy hunter pogo OR easy reaper pogo OR easy beast pogo OR easy witch pogo OR easy architect pogo OR easy shaman pogo |  | Verified |  |

#### Check Locations

No check locations defined.

### Bilewater Upper Trap Gauntlet Hall (Shadow_12)

**Game ID:** Shadow_12

**Contributors:** Herchey and John Madden

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Bilewater Vertical Sac Pogo Room (Shadow_19)](#bilewater-vertical-sac-pogo-room-shadow19) | UL | run OR clawline OR sharpdart OR drifter's cloak OR faydown cloak OR swim |  | Verified | Sharpdart requires 6 uses == 24 silk, so you'd need to farm the little shits to get across with ONLY this. |
| L | left |  | [Bilewater Groal Arena (Shadow_18)](#bilewater-groal-arena-shadow18) | R | faydown cloak OR ((ledge grab OR cling grip OR silk soar) AND (run OR clawline OR sharpdart OR drifter's cloak OR swim)) |  | Verified | Sharpdart requires 6 uses == 24 silk, so you'd need to farm the little shits to get across with ONLY this. |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Bilewater Upper West Column (Shadow_14)

**Game ID:** Shadow_14

**Contributors:** Herchey and his whole entire extended family

#### Subrooms

- lower
- upper

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | upper right | upper | [Bilewater Upper Bloatroach Tower (Shadow_01)](#bilewater-upper-bloatroach-tower-shadow01) | LL | none |  | Verified |  |
| LR | lower right | lower | [Bilewater Lower Bloatroach Tower (Shadow_02)](#bilewater-lower-bloatroach-tower-shadow02) | UL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LM | low to up | lower | upper | cling grip AND (Faydown cloak OR enemy pogo) AND (clawline OR sharpdart) |  | Verified | crest_pogo should be an easy or medium skip since it requires a one-hit death enemy that you need to let float up before pogoing |
| LM | low to up | upper | lower | Cling grip AND (Drifter’s cloak OR faydown cloak OR clawline OR sharpdart OR dash) |  | Verified | Clawline, sharpdart, dash are pretty annoying to hit without a cloak, so easy/medium skips |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater - Rosary Cache #3 | upper | Cling grip AND (faydown cloak OR enemy pogo) |  | Verified | resource |  |

### Bilewater Vertical Sac Pogo Room (Shadow_19)

**Game ID:** Shadow_19

**Contributors:** Herchey and someone he grabbed off the street real quick

#### Subrooms

- upper platform
- low left platform
- low right door platform
- up left door platform
- climb start wall

- **upper platform:** none
- **low left platform:** none
- **low right door platform:** none
- **up left door platform:** none

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | up left door platform | [Bilewater Upper Trap Gauntlet Hall (Shadow_12)](#bilewater-upper-trap-gauntlet-hall-shadow12) | R | none |  | Verified |  |
| UR | upper right | upper platform | [Bilewater Waterfall (Shadow_24)](#bilewater-waterfall-shadow24) | L | complete THE trails end wish promised |  | Verified | Without Trails End quest, this is inaccessible from both sides. |
| LR | lower right | low right door platform | [Bilewater Northeast Tiny Room (Shadow_25)](#bilewater-northeast-tiny-room-shadow25) | L | none |  | Verified |  |
| LL | lower left | low left platform | [Bilewater Lower Trap Gauntlet Hall (Shadow_10)](#bilewater-lower-trap-gauntlet-hall-shadow10) | R | silk soar OR cling grip |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| lp | lower platform crossing | low left platform | climb start wall | dash OR clawline OR swim |  | Verified |  |
| lp | lower platform crossing | climb start wall | low left platform | dash OR clawline OR swim |  | Verified |  |
| CR | climb wall to right | climb start wall | low right door platform | swim OR (clawline OR (sharpdart AND (ledge grab OR cling grip))) |  | Verified | Anything other than swim is a bit narrow of a window. Easy_skip? |
| CR | climb wall to right | low right door platform | climb start wall | cling grip AND (swim OR faydown cloak) |  | Verified | faydown is a pretty narrow window. easy_skip? |
| CUL | climb to upper left | climb start wall | up left door platform | clawline AND faydown cloak |  | Verified |  |
| CUL | climb to upper left | up left door platform | climb start wall | drifter's cloak OR (faydown cloak AND clawline) |  | Verified |  |
| ULL | upper left to lower left | up left door platform | low left platform | drifter's cloak OR (faydown cloak AND clawline) |  | Verified |  |
| ULT | upper left to top | up left door platform | upper platform | faydown cloak AND cling grip AND (enemy pogo OR clawline) |  | Verified |  |
| ULT | upper left to top | upper platform | up left door platform | drifter's cloak OR faydown cloak OR clawline OR sharpdart |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater - Rosary Cache #4 | upper platform | none |  | Verified | resource |  |
| Bilewater - Rosary Cache #5 | upper platform | none |  | Verified | resource |  |

### Bilewater Waterfall (Shadow_24)

**Game ID:** Shadow_24

**Contributors:** Herchey and the girl reading this

#### Subrooms

- left exit
- trails end

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left exit | [Bilewater Vertical Sac Pogo Room (Shadow_19)](#bilewater-vertical-sac-pogo-room-shadow19) | UR | none |  | Verified | blockade on other side of this door has no impact on this direction |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CR | crossing | left exit | trails end | faydown cloak  AND swim  AND cling grip  AND ( ledge grab OR dash OR clawline OR sharpdart ) |  | Verified |  |
| CR | crossing | trails end | left exit | silk soar AND faydown cloak  AND swim  AND cling grip  AND ( ledge grab OR dash OR clawline OR sharpdart ) |  | Verified | don't think you can get out without silk soar's height? |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| trails end wish granted | trails end | complete THE trails end wish promised AND needolin |  | Verified | event |  |
| Throwing Ring | trails end | complete THE trails end wish promised |  | Verified | collectible | Dash, clawline, and sharpdart are a bit precise and require you to get nearly the most possible height out of first and second jumps |

### Bilewater Weavenest Murglin (Shadow_Weavehome)

**Game ID:** Shadow_Weavehome

**Contributors:** Herchey and The Silent from StS 1 (not 2)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Bilewater East Column (Shadow_09)](#bilewater-east-column-shadow09) | R | needolin |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Ruined Tool |  | (cling grip OR silk soar) AND (swim OR clawline OR drifter's cloak) |  | Verified | collectible |  |
| Bilewater - Weaver Workshop Scroll |  | (cling grip OR silk soar) AND (swim OR clawline OR drifter's cloak) AND attack right |  | Verified | lore | breakable wall |

### Bilewater West Hall (Shadow_04b)

**Game ID:** Shadow_04b

**Contributors:** Herchey and the Tonight Show Band

#### Subrooms

- left
- right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left | [Bilewater Organ Entrance (Shadow_04)](#bilewater-organ-entrance-shadow04) | UR | none |  | Verified |  |
| R | right | right | [Bilewater Lower Bloatroach Tower (Shadow_02)](#bilewater-lower-bloatroach-tower-shadow02) | LL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CR | cross the room | left | right | (enemy pogo AND (faydown cloak OR ((clawline OR sharpdart OR dash OR drifter’s cloak) AND cling grip))) OR (silk soar AND ((drifter’s cloak AND (cling grip OR clawline OR sharpdart)) OR (clawline AND sharpdart))) |  | Verified |  |
| CR | cross the room | right | left | Clawline OR sharpdart OR easy hunter pogo OR easy reaper pogo OR easy beast pogo OR easy shaman pogo OR (ledge grab AND (easy witch pogo OR easy architect pogo)) OR (swim AND faydown cloak) OR (silk soar AND drifter’s cloak) |  | Verified |  |

#### Check Locations

No check locations defined.

### Bilewater West Secret Rooms (Shadow_20)

**Game ID:** Shadow_20

**Contributors:** Herchey and someone else

#### Subrooms

- top area
- lower area
- ceiling exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | lower | lower area | [Bilewater Organ Entrance (Shadow_04)](#bilewater-organ-entrance-shadow04) | C | none |  | Verified |  |
| C | ceiling | ceiling exit | [Bilewater Citadel Exit (Shadow_22)](#bilewater-citadel-exit-shadow22) | B | cling grip AND medium enemy pogo AND faydown cloak |  | Verified | Requires an annoying enemy lure. Medium_skips. Should be one-way normally. |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TL | top to bottom | lower area | top area | faydown cloak OR silk soar OR scuttlebrace OR cling grip |  | Verified |  |
| TL | top to bottom | top area | lower area | none |  | Verified |  |
| TC | top to ceiling | top area | ceiling exit | (enemy pogo OR clawline) AND (ledge grab OR cling grip OR faydown cloak) |  | Verified |  |
| TC | top to ceiling | ceiling exit | top area | (faydown cloak AND (swim OR enemy pogo)) OR drifter's cloak OR clawline OR sharpdart |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater West - Memory Locket | lower area | cling grip AND (swim OR clawline OR easy hunter pogo OR easy beast pogo OR easy architect pogo OR ((easy wanderer pogo OR easy witch pogo OR easy reaper pogo) AND (dash OR faydown cloak OR drifter's cloak))) |  | Verified | collectible |  |
| Bilewater - Rosary Cache #6 | lower area | none |  | Verified | collectible |  |
| Bilewater - Rosary Cache #7 | lower area | none |  | Verified | collectible |  |
| Twisted Bud | top area | break wall left AND break wall right AND (cling grip OR silk soar) AND (spike pogo OR enemy pogo OR clawline) AND (dash OR clawline OR sharpdart OR drifter's cloak OR spike pogo) |  | Verified | collectible |  |

### Exhaust Organ Exterior (Dust_09)

**Game ID:** Dust_09

**Contributors:** Herchey and the Forgotten Contributor

#### Subrooms

- middle platform
- left platform
- right platform
- upper door plat
- flea hall plat

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UD | up door | upper door plat | [Exhaust Organ Interior (Organ_01)](#exhaust-organ-interior-organ01) | ML | none |  | Verified |  |
| LD | low door | middle platform | [Exhaust Organ Interior (Organ_01)](#exhaust-organ-interior-organ01) | LL | none |  | Verified |  |
| L | left | left platform | [Sinner's Road Mist Maze Completed (Dust_Maze_08_completed)](#sinners-road-mist-maze-completed-dustmaze08completed) | UR | none |  | Verified |  |
| R | right | right platform | [Bilewater Organ Entrance (Shadow_04)](#bilewater-organ-entrance-shadow04) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LPM | left plat to middle | left platform | middle platform | faydown cloak OR drifter's cloak OR run OR dash OR clawline OR sharpdart OR silk soar OR scuttlebrace OR swim |  | Verified |  |
| LPM | left plat to middle | middle platform | left platform | faydown cloak OR drifter's cloak OR run OR dash OR clawline OR sharpdart OR silk soar OR scuttlebrace OR swim |  | Verified |  |
| RPM | right plat to middle | right platform | middle platform | swim |  | Verified |  |
| RPM | right plat to middle | middle platform | right platform | swim |  | Verified |  |
| MPU | mid plat to upper | middle platform | upper door plat | silk soar |  | Verified |  |
| MPU | mid plat to upper | upper door plat | middle platform | none |  | Verified | falling |
| LPF | left plat to flea | left platform | flea hall plat | silk soar |  | Verified |  |
| LPF | left plat to flea | flea hall plat | left platform | none |  | Verified | falling |
| UPF | upper plat to flea | upper door plat | flea hall plat | (cling grip OR ledge grab) OR scuttlebrace |  | Verified |  |
| UPF | upper plat to flea | flea hall plat | upper door plat | drifter's cloak OR faydown cloak OR run OR dash OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea Rescue | flea hall plat | (swim OR cling grip OR faydown cloak OR (silk soar AND (clawline OR ((drifter's cloak OR sharpdart) AND ledge grab)))) AND break vines left |  | Verified | collectible |  |

### Exhaust Organ Interior (Organ_01)

**Game ID:** Organ_01

**Contributors:** Herchey's cool "KING" hat with spikes on it

#### Subrooms

- elevator
- top layer
- ground floor
- maze
- bench room
- right column

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UE | Underworks Elevator | elevator | [Underworks Exhaust Organ Transit (Library_12)](#underworks-exhaust-organ-transit-library12) | EV | none |  | Verified |  |
| ML | mid left | maze | [Exhaust Organ Exterior (Dust_09)](#exhaust-organ-exterior-dust09) | UD | none |  | Verified |  |
| LL | low left | ground floor | [Exhaust Organ Exterior (Dust_09)](#exhaust-organ-exterior-dust09) | LD | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TE | top to elevator | top layer | elevator | complete Boss: Phantom |  | Verified |  |
| TE | top to elevator | elevator | top layer | complete Boss: Phantom |  | Verified |  |
| GC | ground to maze | ground floor | maze | complete broken elevator AND cling grip |  | Verified |  |
| GC | ground to maze | maze | ground floor | complete broken elevator |  | Verified |  |
| GRC | ground to right column | ground floor | right column | cling grip |  | Verified |  |
| GRC | ground to right column | right column | ground floor | none |  | Verified |  |
| MRC | maze to right column | maze | right column | cling grip AND faydown cloak |  | Verified |  |
| MRC | maze to right column | right column | maze | cling grip |  | Verified |  |
| MT | maze to top | maze | top layer | cling grip |  | Verified |  |
| MT | maze to top | top layer | maze | cling grip |  | Verified |  |
| GB | ground to bench room | ground floor | bench room | silk soar OR cling grip OR scuttlebrace |  | Verified |  |
| GB | ground to bench room | bench room | ground floor | none |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silk Grub Large Cocoon | maze | none |  | Verified | collectible |  |
| Boss: Phantom | top layer | dash OR run |  | Verified | boss |  |
| Organ Bench | bench room | cling grip |  | Verified | bench |  |
| broken elevator | maze | attack left |  | Verified | blockade |  |

## Memorium

### BEEG flea (Arborium_08)

**Game ID:** Arborium_08

**Contributors:** heric

#### Subrooms

- volt
- left

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | volt | [Memorium Voltnest (Arborium_07)](#memorium-voltnest-arborium07) | T | nada |  | Verified |  |
| L | left1 | left | [Memorium Start Shaft (Arborium_01)](#memorium-start-shaft-arborium01) | T | nada |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| vl | volt left | volt | left | cling grip OR silk soar |  | Verified |  |
| vl | volt left | left | volt | cling grip OR (silk soar AND silkhearts 1) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Big flea wall | left | nada |  | Verified | blockade | custom name |
| Flea: Memorium - Huge Flea | left | cling grip OR (silk soar AND silkhearts 1) OR (easy scuttlebrace AND clawline AND silkhearts 1 AND(ledge grab OR faydown cloak OR medium shaman pogo)) |  | Verified | collectible | technically should be a subroom so silkhearts arent needed one way |

### Memorium Karak (Arborium_06)

**Game ID:** Arborium_06

**Contributors:** heric

#### Subrooms

- Right side
- Middle
- Left side
- left and up

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right side | [Seed Shooty Memorium (Arborium_03)](#seed-shooty-memorium-arborium03) | UT | none |  | Verified |  |
| B | bot1 | Middle | [Memorium water room (Arborium_05)](#memorium-water-room-arborium05) | T | complete Water karak ceiling IN Memorium water room |  | Verified | one way wall |
| L | left1 | Left side | [Memorium Start Shaft (Arborium_01)](#memorium-start-shaft-arborium01) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| rm | blind gameplay | Right side | Middle | easy enemy pogo OR ledge grab OR faydown cloak OR silk soar | TODO | Verified | Room is blind unless dark stuff is removed |
| mr | middle --> right | Middle | Right side | easy enemy pogo OR (ledge grab AND (dash OR run)) OR faydown cloak OR dash OR (run AND cling grip) |  | Verified | theres also an enemy that you can super easily clawline even on accident to get the height you need but I have no clue what to label that as you can also clawline plus silk soar but it feels like it would fall under a skip of some kind and i feel like easy enemy pogo already covers that  damage boosts arent accounted for but if implemented "OR easy damage boost" that can be |
| Ml | Middle <-> Left | Left side | Middle | run OR drifter's cloak OR faydown cloak OR easy architect pogo OR (clawline AND silkhearts 1) OR easy beast pogo | TODO | Verified | Room is blind unless dark stuff is removed |
| Ml | Middle <-> Left | Middle | Left side | medium shaman pogo OR run OR faydown cloak  OR clawline OR drifter's cloak OR easy architect pogo OR easy hunter pogo OR easy needle strike stall(wanderers) OR easy beast pogo |  | Verified | can be done no items but need a precise movement option |
| lu | idk | Middle | left and up | faydown cloak OR (silk soar AND (dash OR clawline)) OR (run AND (ledge grab OR cling grip)) OR (clawline AND ledge grab) |  | Verified |  |
| ll | smth | Left side | left and up | faydown cloak OR (silk soar AND (dash OR (clawline AND silkhearts 1))) OR (run AND (ledge grab OR cling grip)) OR (clawline AND silkhearts 1 AND ledge grab) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memorium - Shell Shard Cache #2 | Middle | cling grip OR ledge grab OR faydown cloak OR silksoar OR easy shaman pogo |  | Verified | resource |  |
| Memorium - Shell Shard Cache #1 | left and up | none |  | Verified | resource |  |

### Memorium Mossy (Arborium_09)

**Game ID:** Arborium_09

**Contributors:** heric

#### Subrooms

- Top
- Fragment
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | topish shaft | Top | [Memorium Start Shaft (Arborium_01)](#memorium-start-shaft-arborium01) | ML | nada |  | Verified |  |
| R2 | bottom shaft | Bottom | [Memorium Start Shaft (Arborium_01)](#memorium-start-shaft-arborium01) | BL | nada |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| tf | top/fragment | Top | Fragment | clawline AND faydown cloak AND dash AND cling grip AND drifter's cloak |  | Verified | clawline AND faydown cloak AND precise movement OR dash AND faydown cloak AND cling grip AND (precise movement OR drifter's cloak) with precise movement clause |
| fb | fragment/bottom | Fragment | Bottom | nada |  | Verified |  |
| fb | fragment/bottom | Bottom | Fragment | silk soar OR cling grip OR (faydown cloak AND ledge grab AND easy shaman pogo) OR(easy scuttlebrace AND (faydown cloak OR ledge grab OR easy shaman pogo OR easy architect pogo OR easy wanderer pogo OR easy reaper pogo OR medium hunter pogo OR easy beast pogo)) | TODO | Verified | Room is blind unless dark stuff is removed |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memorium - Spool Fragment | Fragment | none |  | Verified | collectible |  |
| Memorium Mossy wall | Bottom | none |  | Verified | blockade | custom name |

### Memorium Rhino Room (Arborium_02)

**Game ID:** Arborium_02

**Contributors:** heric

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Seed Shooty Memorium (Arborium_03)](#seed-shooty-memorium-arborium03) | LL | none |  | Verified |  |
| L | left1 |  | [Memorium Start Shaft (Arborium_01)](#memorium-start-shaft-arborium01) | LR | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memorium - Beast Shard |  | none |  | Verified | collectible |  |

### Memorium Start Shaft (Arborium_01)

**Game ID:** Arborium_01

**Contributors:** heric

#### Subrooms

- base
- Almost bottom
- Almost middle
- Lore Platform
- above evil wall
- Ventrica ledge
- Volt Ledge
- Tippidy top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | left2 | Almost bottom | [Memorium Mossy (Arborium_09)](#memorium-mossy-arborium09) | R2 | Complete Memorium Mossy wall IN Memorium Mossy |  | Verified | shortcut |
| R | right3 | above evil wall | [Memorium Karak (Arborium_06)](#memorium-karak-arborium06) | L | nada |  | Verified |  |
| Ve | Ventrica | Ventrica ledge | [Memorium Ventrica (Arborium_Tube)](#memorium-ventrica-arboriumtube) | R | nada |  | Verified |  |
| T | right1 | Tippidy top | [BEEG flea (Arborium_08)](#beeg-flea-arborium08) | l | complete Big flea wall IN BEEG flea |  | Verified | shortcut |
| B | bot1 | base | [Memorium Entrance Tunnel (Song_25)](#memorium-entrance-tunnel-song25) | T | Complete Memorium entrance vines IN memorium entrance tunnel |  | Verified | one way wall |
| ML | left1 | above evil wall | [Memorium Mossy (Arborium_09)](#memorium-mossy-arborium09) | R | nada |  | Verified |  |
| LLR | right5 | Almost bottom | [Memorium bench (Arborium_04)](#memorium-bench-arborium04) | L | nada |  | Verified |  |
| VN | right2 | Volt Ledge | [Memorium Voltnest (Arborium_07)](#memorium-voltnest-arborium07) | L | nada |  | Verified |  |
| LR | right4 | Almost middle | [Memorium Rhino Room (Arborium_02)](#memorium-rhino-room-arborium02) | L | nada |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | one jump | base | Almost bottom | cling grip OR ledge grab OR faydown cloak OR (silk soar AND silkhearts 1) |  | Verified |  |
| 2 | drop | Almost bottom | base | nada |  | Verified |  |
| 3 | drop farther | Almost middle | Lore Platform | nada |  | Verified |  |
| 4 | couple jumps | Almost bottom | Almost middle | faydown cloak OR (silk soar AND silkhearts 1) |  | Verified |  |
| l | lore | Almost bottom | Lore Platform | cling grip OR ledge grab OR faydown cloak OR (silk soar AND silkhearts 1) OR (clawline AND silkhearts 1 AND easy scuttlebrace) |  | Verified |  |
| 5 | drop a lil bit | Lore Platform | Almost bottom | nada |  | Verified |  |
| O | one way | above evil wall | Almost middle | nada |  | Verified |  |
| V | Ventrica-slightly below | above evil wall | Ventrica ledge | ((run OR (clawline AND silkhearts 1))AND (cling grip OR ledge grab)) OR faydown cloak OR (cling grip AND (drifters OR easy needle strike stall(architect))) |  | Verified | easy damage boost AND (drifter's cloak OR ledge grab) OR silk soar OR faydown cloak OR (run And ledge grab)  can be added once damage boosts are added   OR (drifter's cloak AND cling grip)  can be added but also needs some kinda precise movement setting |
| V | Ventrica-slightly below | Ventrica ledge | above evil wall | nada |  | Verified |  |
| VV | ventrica volt | Volt Ledge | Ventrica ledge | nada |  | Verified |  |
| VV | ventrica volt | Ventrica ledge | Volt Ledge | sprint OR (clawline AND silkhearts 1) OR cling grip OR faydown cloak OR easy needle strike stall(architect) OR medium needle strike stall(wanderers) OR easy beast pogo OR (easy needle strike stall(reaper) AND ledge grab) |  | Verified |  |
| tv | top | Tippidy top | Volt Ledge | nada |  | Verified |  |
| tv | top | Volt Ledge | Tippidy top | faydown cloak OR (silk soar AND silkhearts 1) |  | Verified | theres is some stuff you can do to avoid needing a silkheart that requires other items |
| wv | wall to volt | above evil wall | Volt Ledge | silk soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memorium - Lower Plaque | Lore Platform | nada |  | Verified | lore |  |

### Memorium Ventrica (Arborium_Tube)

**Game ID:** Arborium_Tube

**Contributors:** heric

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Memorium Start Shaft (Arborium_01)](#memorium-start-shaft-arborium01) | Ve | nada |  | Verified |  |
| V | door_tubeEnter |  | [Ventrica Menu](#ventrica-menu) | M | unlock Ventrica Memorium |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Ventrica: Memorium |  | unlock Ventrica: Memorium Rosary Lock |  | Verified | travel |  |
| Ventrica: Memorium Rosary Lock |  | rosaries 80 |  | Verified | lock |  |

### Memorium Voltnest (Arborium_07)

**Game ID:** Arborium_07

**Contributors:** heric

#### Subrooms

- left
- Memorium stuff

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left | [Memorium Start Shaft (Arborium_01)](#memorium-start-shaft-arborium01) | VN | nada |  | Verified |  |
| T | top1 | Memorium stuff | [BEEG flea (Arborium_08)](#beeg-flea-arborium08) | b | (silk soar AND silkhearts 1) OR ledge grab OR faydown cloak OR cling grip |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LM | memorium volt back and forth | left | Memorium stuff | (clawline AND silkhearts 1 AND (spike pogo OR dash OR silkhearts 2 OR drifter's cloak OR faydown cloak)) OR (cling grip AND run) OR (drifters AND (spike pogo OR faydown cloak)) OR (faydown cloak AND (run OR spike pogo)) OR (run AND spike pogo) OR easy beast pogo |  | Verified | OR (easy damage boost AND clawline AND silkhearts 1) can be added once damage boosts are added |
| LM | memorium volt back and forth | Memorium stuff | left | cling grip OR (clawline AND silkhearts 1) OR medium hunter pogo OR medium reaper pogo OR (faydown cloak AND spike pogo) OR easy beast pogo OR medium architect pogo OR (spike pogo AND faydown cloak) OR run OR drifters |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Voltvessels | Memorium stuff | complete Memoria gauntlet |  | Verified | collectible |  |
| Memoria gauntlet | Memorium stuff | nada |  | Verified | gauntlet | custom name |

#### Notes

you can do some scuttlebrace things but its rng nonsense thats not reasonable for anyone to figure out

farsight isnt randoed yet but from "Memorium stuff" needs nada

### Memorium bench (Arborium_04)

**Game ID:** Arborium_04

**Contributors:** heric

#### Subrooms

- Post Wall
- Pre Wall

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Pre Wall | [Memorium Start Shaft (Arborium_01)](#memorium-start-shaft-arborium01) | LLR | nada |  | Verified |  |
| R | right1 | Post Wall | [Seed Shooty Memorium (Arborium_03)](#seed-shooty-memorium-arborium03) | BL | nada |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | wall | Post Wall | Pre Wall | nada |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memorium - Mossbery | Post Wall | none |  | Verified | collectible |  |

### Memorium puzzle (Arborium_10)

**Game ID:** Arborium_10

**Contributors:** heric

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Seed Shooty Memorium (Arborium_03)](#seed-shooty-memorium-arborium03) | R | nada |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memorimum Cogheart Piece |  | flip switch up OR flip switch down |  | Verified | collectible | memory puzzle |

#### Notes

the logic for the puzzle thing, can be implemented once its randoed

cling grip OR faydown cloak OR (silk soar AND silkhearts 1)

### Memorium water room (Arborium_05)

**Game ID:** Arborium_05

**Contributors:** heric

#### Subrooms

- Center
- right side

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Center | [Memorium Karak (Arborium_06)](#memorium-karak-arborium06) | B | silk soar OR (faydown cloak AND break wall up) |  | Verified |  |
| r | right1 | right side | [Seed Shooty Memorium (Arborium_03)](#seed-shooty-memorium-arborium03) | T | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| sw | swim | right side | Center | swim |  | Verified | no requirments avialable to list it as but "(hard clawline AND (cling grip OR ledge grab))" |
| 2 | 2 | Center | right side | swim AND (easy enemy pogo OR faydown cloak OR ledge grab OR cling grip) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memorium - Memory Locket | Center | (faydown cloak AND (clawline OR medium beast pogo OR (dash AND (swim OR easy enemy pogo)))) OR (faydown cloak AND (swim OR cling grip) AND((easy architect pogo OR  easy shaman pogo OR medium witch pogo OR easy beast pogo OR easy reaper pogo OR easy hunter pogo OR (easy needle strike stall (wanderers))))) |  | Verified | collectible |  |
| Water karak ceiling | Center | silksoar OR (faydown cloak AND break wall up) |  | Verified | blockade | one way thingy |

### Seed Shooty Memorium (Arborium_03)

**Game ID:** Arborium_03

**Contributors:** heric

#### Subrooms

- Middle
- Bottom
- Top
- Not connected

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UT | left1 | Not connected | [Memorium Karak (Arborium_06)](#memorium-karak-arborium06) | R | nada |  | Verified |  |
| LL | left3 | Middle | [Memorium Rhino Room (Arborium_02)](#memorium-rhino-room-arborium02) | R | nada |  | Verified |  |
| BL | left4 | Bottom | [Memorium bench (Arborium_04)](#memorium-bench-arborium04) | R | nada |  | Verified |  |
| T | left2 | Top | [Memorium water room (Arborium_05)](#memorium-water-room-arborium05) | R | nada |  | Verified |  |
| R | right1 | Middle | [Memorium puzzle (Arborium_10)](#memorium-puzzle-arborium10) | L | nada |  | Verified |  |
| LR | right2 | Bottom | [Shopkeeper hides (Arborium_11)](#shopkeeper-hides-arborium11) | L | nada |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | down | Top | Middle | nada |  | Verified |  |
| 2 | down2 | Middle | Bottom | nada |  | Verified |  |
| 3 | up1 | Middle | Top | (faydown cloak AND (cling grip OR (Easy scuttlebrace OR silk soar))) OR (cling grip AND (medium shaman pogo OR hard reaper pogo)) |  | Verified | OR (clawline AND hard wanderer pogo) feels a bit to hard to me idk |
| 4 | up2 | Bottom | Middle | (silk soar AND silkhearts 1) OR (faydown cloak AND ledge grab) OR (medium Shaman pogo AND faydown cloak) OR Easy scuttlebrace OR (cling grip AND faydown cloak) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memorium - Orders | Not connected | nada |  | Verified | lore | just name required |

### Shopkeeper hides (Arborium_11)

**Game ID:** Arborium_11

**Contributors:** heric

#### Subrooms

- Entrance
- Main Area
- Memorium exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Entrance | [Seed Shooty Memorium (Arborium_03)](#seed-shooty-memorium-arborium03) | LR | nada |  | Verified |  |
| R | right1 | Memorium exit | [Putrified Ducts Entrance (Aqueduct_01)](#putrified-ducts-entrance-aqueduct01) | L | nada |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | hidden area | Entrance | Main Area | (silk soar AND silkhearts 1) OR (faydown cloak AND (cling grip OR easy scuttlebrace)) |  | Verified |  |
| h2 | hidden area other way | Main Area | Entrance | cling grip OR (faydown cloak AND (easy shaman pogo AND easy scuttlebrace)) |  | Verified | enemy pogos can be done but its a weird rng so ima leave it untouched |
| f | fall | Memorium exit | Main Area | nada |  | Verified |  |
| c | climb | Main Area | Memorium exit | (silk soar AND silkhearts 1) OR ( faydown cloak AND cling grip) |  | Verified | enemy pogos can be done but its a weird rng so ima leave it untouched |
| lc | long clawline spam | Memorium exit | Entrance | drifter's cloak AND clawline AND silkhearts 1 AND (medium scuttlebrace OR (faydown cloak AND easy scuttlebrace)) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memorium - Shard Bundle | Main Area | rosaries 70 |  | Verified | collectible | swapped the subroom - as it appeared to be incorrect - hero |
| Memorium - Map Purchase | Entrance | none |  | Verified | collectible | swapped the subroom - as it appeared to be incorrect - hero |
| The Lost Merchant Wish Granted | Main Area | complete THE The Lost Merchant Wish Promised |  | Verified | event |  |

#### Notes

I HATE THIS ROOOOOM

## Sands of Karak

### Coral Tower (Coral_Tower_01)

**Game ID:** Coral_Tower_01

**Contributors:** Pxyl

#### Subrooms

- Entrance
- Main
- Bench

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Entrance | [Coral Tower Entrance (Coral_28)](#coral-tower-entrance-coral28) | D | None |  | Verified |  |
| DR | door_wakeOnGround | Main | TODO |  | Needolin AND Elegy of the Deep |  | Verified | Leads to the Memory Coral Tower, That room only needs silk soar and (Proficient Combat or needle upgrades to beat khan) |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SC | Sandcarver Pit | Entrance | Main | Dash OR Sprint OR Drifters cloak OR Faydown Cloak OR Clawline OR easy Beast Crest pogo OR Sharpdart OR easy Architect Crest pogo |  | Verified |  |
| SC | Sandcarver PIt | Main | Entrance | Dash OR Sprint OR Drifters cloak OR Faydown Cloak OR Clawline OR easy Beast Crest pogo OR Sharpdart OR easy Architect Crest pogo |  | Verified |  |
| S2 | Sandcarver Pit 2 | Main | Bench | Dash OR Sprint OR Drifters cloak OR Faydown Cloak OR Clawline OR easy Beast Crest pogo OR Sharpdart OR ( easy Architect Crest pogo AND Ledge Grab AND easy Needle Strike stall ) |  | Verified |  |
| S2 | Sandcarver Pit 2 | Bench | Main | Dash OR Sprint OR Drifters cloak OR Faydown Cloak OR Clawline OR easy Beast Crest pogo OR Sharpdart OR easy Architect Crest pogo |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Conchcutter | Main | None |  | Verified | collectible |  |
| Sands of Karak - Lower Coral Tablet | Entrance | None |  | Verified | lore |  |

### Coral Tower Entrance (Coral_28)

**Game ID:** Coral_28

**Contributors:** Pxyl

#### Subrooms

- Exit
- Door

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Exit | [Sands of Karak Upper Left Long Room (Coral_27)](#sands-of-karak-upper-left-long-room-coral27) | L | None |  | Verified |  |
| D | door1 | Door | [Coral Tower (Coral_Tower_01)](#coral-tower-coraltower01) | L | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SC | Sandcarver Pit | Door | Exit | Clawline OR Sharpdart OR Drifters Cloak OR ( Sprint AND ( Dash OR Faydown Cloak OR easy Beast Crest pogo ) ) OR  ( Faydown Cloak AND ( easy Beast Crest pogo OR easy Hunter Crest pogo OR easy Architect Crest pogo OR easy Shaman Crest pogo ( Wanderer Crest AND Needle strike ) ) ) |  | Verified |  |
| SC | Sandcarver Pit | Exit | Door | Clawline OR Sharpdart OR ( Sprint AND ( Dash OR Faydown Cloak OR Drifters Cloak OR easy Beast Crest pogo OR easy Architect Crest pogo ) )  OR ( Sprint AND ( easy Shaman Crest pogo OR easy Hunter crest pogo OR medium Heal stall OR ( easy Wanderer Crest pogo AND easy Needle Strike stall AND Ledge Grab ) ) ) OR ( Dash AND ( easy Reaper Crest pogo OR easy Beast Crest pogo OR Faydown Cloak OR Drifters Cloak OR ( easy Architect Crest pogo AND ( Ledge Grab OR easy Needle Strike stall ) ) ) ) OR ( Faydown Cloak AND ( easy Beast Crest pogo OR easy Architect Crest pogo OR medium Shaman Crest pogo OR easy Hunter Crest pogo OR Drifters Cloak OR ( easy Reaper Crest pogo AND Ledge Grab ) OR ( easy Wanderer Crest pogo AND easy Needle strike stall ) ) ) OR ( Drifters Cloak AND ( easy Beast Crest pogo OR easy Architect Crest pogo OR easy Shaman Crest pogo OR easy Wanderer Crest pogo OR medium Heal Stall OR Ledge Grab OR Silk Soar OR ( easy Reaper Crest pogo AND easy Needle Strike stall ) ) ) OR ( Silk Soar AND ( easy Beast Crest pogo OR easy Architect Crest pogo ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Resting Site | Door | prereq Wish: A vassal lost started1 AND Steel soul AND ( Sprint AND ( ( Dash OR Drifters Cloak OR Faydown Cloak OR easy Beast Crest pogo ) OR Clawline OR ( Silk soar AND Ledge Grab ) ) ) |  | Verified | collectible | Not Included for the better |
| Wish: A vassal lost started1 | Door | None |  | Verified | event |  |

### Crustnut (Coral_41)

**Game ID:** Coral_41

**Contributors:** Pyxl

#### Subrooms

- Start
- End
- Shard Platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Start | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | UML | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Start | End | Cling grip AND ( ( Clawline OR Sharpdart OR ( Dash AND ( Drifters Cloak OR easy Beast Crest pogo ) ) ) OR ( easy Beast crest pogo AND Faydown Cloak AND easy Needle Strike stall ) ) |  | Verified |  |
| WR | Whole Room | End | Start | Cling grip AND ( ( Clawline OR Sharpdart OR ( Dash AND ( Drifters Cloak OR easy Beast Crest pogo ) ) ) OR ( easy Beast crest pogo AND Faydown Cloak AND easy Needle Strike stall) ) |  | Verified |  |
| SD | Shard Detour | Start | Shard Platform | Silk Soar OR ( ( Dash AND Scuttlebrace ) AND ( Clawline OR Sharpdart ) ) OR ( Cling grip AND ( Dash OR Clawline OR Sharpdart OR easy Beast Crest pogo OR Faydown Cloak OR Drifters Cloak ) ) |  | Verified |  |
| SD | Shard Detour | Shard Platform | Start | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Crustnut | End | None |  | Verified | collectible |  |
| Shard Cache: Sands of Karak #11 | Shard Platform | None |  | Verified | resource |  |

### Sands of Karak Bellshrine (Bellshrine_Coral)

**Game ID:** Bellshrine_Coral

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Sands of Karak Elevator to Blasted Steps (Coral_38)](#sands-of-karak-elevator-to-blasted-steps-coral38) | R | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Simple key: Sands of Karak east bench |  | None |  | Verified | collectible |  |

### Sands of Karak Elevator to Blasted Steps (Coral_38)

**Game ID:** Coral_38

**Contributors:** Pyxl

#### Subrooms

- Left
- Right
- Bottom
- Shardilard Ledge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Sands of Karak Right Side Tall room (Coral_26)](#sands-of-karak-right-side-tall-room-coral26) | R | None |  | Verified |  |
| R | right1 | Right | [Sands of Karak Bellshrine (Bellshrine_Coral)](#sands-of-karak-bellshrine-bellshrinecoral) | L | None |  | Verified |  |
| F | bot1 | Bottom | [Pre Last Judge Room (Coral_32)](#pre-last-judge-room-coral32) | T | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| OE | Over Elevator | Left | Right | easy Shaman Crest pogo OR Ledge Grab OR Cling Grip OR Sprint OR ( Dash AND Scuttlebrace ) OR Silk Soar OR easy Beast Crest pogo OR Clawline OR Activate Elevator switch Karak OR ( ( easy Reaper Crest pogo OR easy Hunter Crest pogo) AND easy Needle Strike stall ) |  | Verified |  |
| OE | Over Elevator | Right | Left | None |  | Verified |  |
| EL | Elevator | Right | Bottom | Activate Elevator switch Karak |  | Verified |  |
| EL | Elevator | Bottom | Right | Activate Elevator switch Karak |  | Verified |  |
| SH | Shaft | Bottom | Shardilard Ledge | Silk Soar OR ( Cling grip AND ( Faydown Cloak OR Drifters Cloak OR Clawline OR Sharpdart OR ( Dash AND ( ( easy Beast Crest pogo OR easy Shaman Crest pogo ) OR ( easy Architect crest pogo AND easy Needle Strike stall ) ) ) OR ( Dash AND Scuttlebrace AND Clawline AND ( Faydown Cloak OR Drifters Cloak ) ) ) ) |  | Verified |  |
| SH | Shaft | Shardilard Ledge | Bottom | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Sands of Karak - Shellshard Cache #5 | Shardilard Ledge | None |  | Verified | resource |  |
| Sands of Karak - Shellshard Cache #6 | Shardilard Ledge | None |  | Verified | resource |  |
| Sands of Karak - Shellshard Cache #7 | Shardilard Ledge | None |  | Verified | resource |  |
| Sands of Karak - Shellshard Cache #8 | Shardilard Ledge | None |  | Verified | resource |  |
| Shardilard | Shardilard Ledge | None |  | Verified | enemy | Should these be included? |
| Elevator Switch karak | Right | None |  | Verified | switch |  |

### Sands of Karak Entrance (Coral_25)

**Game ID:** Coral_25

**Contributors:** Pyxl

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | Bottom | [Windy Pinstress Entrance (Coral_34)](#windy-pinstress-entrance-coral34) | T | None |  | Verified |  |
| R | right1 | Top | [Sands of Karak Lower Left Long Room (Coral_23)](#sands-of-karak-lower-left-long-room-coral23) | LL | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BS | Big Shaft | Bottom | Top | Silk soar OR ( Cling Grip AND ( ( Proficient Movement AND Spike Pogo ) OR Clawline ) ) |  | Verified |  |
| BS | Big Shaft | Top | Bottom | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Sands of Karak - Upper Coral Tablet | Top | Silk soar OR ( Cling grip AND ( Faydown Cloak OR Dash OR Drifters Cloak OR Clawline OR Sharpdart ) ) OR ( Scuttlebrace AND faydown Cloak ) |  | Verified | lore |  |

### Sands of Karak Lower Left Long Room (Coral_23)

**Game ID:** Coral_23

**Contributors:** Pyxl

#### Subrooms

- Lower Entrance
- Centre Platform
- Upper Left Platform
- Hidden Exit
- Right Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left2 | Hidden Exit | [Watcher at the Edge (Coral_39)](#watcher-at-the-edge-coral39) | R | None |  | Verified |  |
| R | right1 | Right Exit | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | LL | None |  | Verified |  |
| LL | left1 | Lower Entrance | [Sands of Karak Entrance (Coral_25)](#sands-of-karak-entrance-coral25) | R | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LN | Lower Nut Platforming | Lower Entrance | Centre Platform | Dash OR Clawline OR Drifters Cloak OR Faydown Cloak OR easy Beast Crest pogo OR Sharpdart OR ( easy Reaper Crest pogo AND Ledge Grab ) |  | Verified |  |
| LN | Lower Nut Platforming | Centre Platform | Lower Entrance | Clawline OR ( Dash AND Sprint AND Faydown Cloak AND Drifters Cloak ) |  | Verified |  |
| UP | Upper Left Nut Platforming | Centre Platform | Upper Left Platform | ( ( Cling grip OR Silk Soar ) AND ( Dash OR Clawline OR Sharpdart OR Faydown Cloak OR Drifters Cloak ) ) OR ( Silk Soar AND easy Beast Crest pogo ) |  | Verified |  |
| UP | Upper Left Nut Platforming | Upper Left Platform | Centre Platform | Dash OR Clawline OR easy Beast Crest pogo OR Drifters Cloak OR Faydown Cloak OR Sharpdart |  | Verified |  |
| HD | Hidden Shaft | Upper Left Platform | Hidden Exit | Silk Soar |  | Verified |  |
| HD | Hidden Shaft | Hidden Exit | Upper Left Platform | None |  | Verified |  |
| RN | Right Nut Platforming | Centre Platform | Right Exit | Cling Grip AND ( Dash OR Drifters Cloak OR Clawline OR Sharpdart OR ( Faydown Cloak AND easy Beast Crest pogo ) ) |  | Verified |  |
| RN | Right Nut Platforming | Right Exit | Centre Platform | ( Clawline AND ( Dash OR Drifters Cloak OR Faydown Cloak OR Sharpdart ) ) OR ( Drifters Cloak AND Sharpdart x 4 ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Dands of Karak - Memory Locket | Upper Left Platform | None |  | Verified | collectible |  |

### Sands of Karak Lower Right Long Room (Coral_24)

**Game ID:** Coral_24

**Contributors:** Pyxl

#### Subrooms

- Left Exit
- Flea Ledge
- Lower Centre Platform
- Upper Centre Platform
- Right Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Exit | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | LR | None |  | Verified |  |
| R | right1 | Right Exit | [Sands of Karak Right Side Tall room (Coral_26)](#sands-of-karak-right-side-tall-room-coral26) | LL | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LW | Left Wall | Left Exit | Flea Ledge | Silk Soar |  | Verified |  |
| LW | Left Wall | Flea Ledge | Left Exit | None |  | Verified |  |
| LN | Lower Left Nut Platforms | Left Exit | Lower Centre Platform | easy Beast Crest pogo OR Dash OR Clawline OR Faydown Cloak OR Drifters Cloak OR Sharpdart OR ( Ledge grab AND ( easy Reaper crest pogo OR easy Shaman Crest pogo OR easy Hunter Crest pogo OR easy Wanderer Crest pogo ) ) |  | Verified |  |
| LN | Lower Left Nut Platforms | Lower Centre Platform | Left Exit | ( Drifters Cloak AND ( Clawline OR easy Beast crest pogo OR Dash OR Faydown Cloak ) ) OR ( Clawline AND ( easy Shaman crest pogo OR Faydown Cloak OR Silk Soar OR easy Beast Crest pogo ) ) OR ( Faydown Cloak AND ( easy Beast Crest pogo OR Sharpdart ) ) |  | Verified |  |
| UN | Upper Left Nut Platforms | Upper Centre Platform | Flea Ledge | ( Cling grip AND Clawline ) OR ( Clawline AND ( ( Drifters Cloak AND ( hard hunter Crest pogo OR hard Reaper Crest pogo OR hard Wanderer Crest pogo OR hard Shaman Crest pogo ) ) OR Faydown Cloak ) ) |  | Verified | While technically not one way its just cancer to get back and had 0 practical use to dropping down and redoing the lower route |
| RN | Right Nut Platforms | Upper Centre Platform | Right Exit | ( Cling grip AND  ( ( Clawline OR Drifters Cloak ) OR easy Beast Crest pogo ) ) |  | Verified |  |
| RN | Right Nut Platforms | Right Exit | Upper Centre Platform | None |  | Verified |  |
| CN | Centre Platforms | Lower Centre Platform | Upper Centre Platform | Faydown Cloak OR Sprint OR ( Dash AND ( Ledge grab OR Cling grip ) ) OR Drifters Cloak OR Clawline OR Sharpdart OR Silksoar OR easy Beast Crest pogo OR ( easy Architect Crest pogo AND easy Needle Strike stall ) |  | Verified |  |
| CN | Centre Platforms | Upper Centre Platform | Lower Centre Platform | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Sands of Karak #1 | Lower Centre Platform | None |  | Verified | resource |  |
| Shell Shard Cache: Sands of Karak #2 | Lower Centre Platform | None |  | Verified | resource |  |
| Flea: Sands of Karak | Flea Ledge | None |  | Verified | collectible |  |

### Sands of Karak Right Side Tall room (Coral_26)

**Game ID:** Coral_26

**Contributors:** Pyxl

#### Subrooms

- Centre
- Bottom
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left2 | Top | [Sands of Karak Upper Right Long Room (Coral_44)](#sands-of-karak-upper-right-long-room-coral44) | R | None |  | Verified |  |
| LL | left1 | Centre | [Sands of Karak Lower Right Long Room (Coral_24)](#sands-of-karak-lower-right-long-room-coral24) | R | None |  | Verified |  |
| R | right1 | Centre | [Sands of Karak Elevator to Blasted Steps (Coral_38)](#sands-of-karak-elevator-to-blasted-steps-coral38) | L | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TS1 | Tall Shaft1 | Centre | Bottom | None |  | Verified |  |
| TS1 | Tall Shaft1 | Bottom | Centre | Cling Grip |  | Verified |  |
| TS2 | Tall Shaft2 | Top | Bottom | None |  | Verified |  |
| TS2 | Tall Shaft2 | Bottom | Top | Cling Grip AND ( Clawline OR Faydown Cloak OR ( Ledge Grab AND ( ( Drifters Cloak OR Dash ) OR ( easy Beast Crest pogo AND easy Needle Strike stall ) ) ) ) |  | Verified |  |
| TS3 | Tall Shaft3 | Top | Centre | None |  | Verified |  |
| TS3 | Tall Shaft3 | Centre | Top | Silk Soar AND Cling grip AND ( ( Dash OR Clawline OR Sharpdart OR Faydown Cloak OR Drifters Cloak ) OR ( easy Beast Crest pogo AND easy Needle Strike stall) ) |  | Verified |  |

#### Check Locations

No check locations defined.

### Sands of Karak Tall Centre Room (Coral_35b)

**Game ID:** Coral_35b

**Contributors:** Pyxl

#### Subrooms

- Ground Level
- Shakra Ledge
- Stalactite
- Crust Nut Ledge
- Bridge Level
- Voltnest Level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 | Voltnest Level | [Voltnest (Coral_29)](#voltnest-coral29) | L | None |  | Verified |  |
| LL | left3 | Ground Level | [Sands of Karak Lower Left Long Room (Coral_23)](#sands-of-karak-lower-left-long-room-coral23) | R | None |  | Verified |  |
| F | bot1 | Ground Level | [Blasted Steps Thin Long Vertical (Coral_35)](#blasted-steps-thin-long-vertical-coral35) | T | prereq Stalactite |  | Verified |  |
| LR | right2 | Ground Level | [Sands of Karak Lower Right Long Room (Coral_24)](#sands-of-karak-lower-right-long-room-coral24) | L | None |  | Verified |  |
| UL | left2 | Bridge Level | [Sands of Karak Upper Left Long Room (Coral_27)](#sands-of-karak-upper-left-long-room-coral27) | R | None |  | Verified |  |
| UML | left5 | Crust Nut Ledge | [Crustnut (Coral_41)](#crustnut-coral41) | R | None |  | Verified |  |
| UR | right1 | Bridge Level | [Sands of Karak Upper Right Long Room (Coral_44)](#sands-of-karak-upper-right-long-room-coral44) | L | None |  | Verified |  |
| ULL | left4 | Shakra Ledge | [Sands of Shakra (Coral_40)](#sands-of-shakra-coral40) | R | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LS | Lower Shaft | Ground Level | Shakra Ledge | Silk Soar OR ( Faydown Cloak AND ( Cling grip OR ( Dash AND Scuttlebrace ) ) ) OR ( Cling grip AND ( ( Dash OR Sprint OR Drifters Cloak OR Clawline OR Sharpdart ) OR ( ( easy Beast Crest pogo OR easy Architect Crest pogo ) AND easy Needle Strike stall ) ) ) |  | Verified |  |
| LS | Lower Shaft | Shakra Ledge | Ground Level | None |  | Verified |  |
| ST1 | Stalactite | Ground Level | Stalactite | Silk Soar |  | Verified |  |
| ST1 | Stalactite | Stalactite | Ground Level | None |  | Verified |  |
| ST2 | Stalactite2 | Shakra Ledge | Stalactite | ( ( Scuttlebrace OR Cling grip ) AND ( Dash OR Sprint OR Drifters Cloak OR Faydown Cloak OR SharpDart OR Clawline ) ) OR ( Cling Grip AND ( easy Beast Crest pogo OR easy Hunter Crest pogo OR easy Shaman Crest pogo OR ( ( easy Reaper Crest pogo OR easy Architect Crest pogo ) AND easy Needle Strike stall ) ) ) |  | Verified |  |
| St2 | Stalactite2 | Stalactite | Shakra Ledge | None |  | Verified |  |
| US1 | Upper Shaft1 | Shakra Ledge | Crust Nut Ledge | ( ( Scuttlebrace  OR  Cling grip )  AND  ( ( Dash AND ( Ledge Grab OR easy Shaman Crest pogo ) )   OR Clawline OR Faydown Cloak OR Sharpdart ) ) OR ( Cling Grip AND ( easy Beast Crest pogo OR easy Hunter Crest pogo OR ( easy Reaper Crest pogo AND easy Needle Strike stall ) ) ) |  | Verified |  |
| US1 | Upper Shaft1 | Crust Nut Ledge | Shakra Ledge | None |  | Verified |  |
| US2 | Upper Shaft2 | Crust Nut Ledge | Bridge Level | Prereq Stalactite 2 AND ( (  Scuttlebrace OR Cling grip OR  Faydown Cloak  OR (  Silk Soar AND ( easy Architect Crest pogo OR easy Witch Crest pogo OR easy Reaper Crest pogo OR easy Shaman Crest pogo OR ( easy Wanderer Crest pogo AND ( ledge grab OR Dash OR Sharpdart OR Clawline OR Drifters Cloak ) ) ) ) ) ) |  | Verified |  |
| US2 | Upper Shaft2 | Bridge Level | Crust Nut Ledge | Prereq Stalactite 2 |  | Verified |  |
| VS | Voltwyrm Shaft | Bridge Level | Voltnest Level | ( Cling Grip AND Faydown Cloak AND ( Clawline OR Dash OR Sharpdart OR ( ( Medium Beast Crest pogo AND medium Needle Strike stall AND Cling Grip  )  OR ( ( ( medium Architect Crest pogo OR medium Reaper Crest pogo )  AND medium Needle Strike stall ) OR medium Shaman Crest pogo )  )  )  ) OR (  Silk soar AND ( Cling Grip OR Faydown Cloak OR Scuttlebrace ) ) |  | Verified |  |
| VS | VoltWyrm Shaft | Voltnest Level | Bridge Level | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Stalactite | Stalactite | None |  | Verified | blockade |  |
| Stalactite 2 | Bridge Level | None |  | Verified | blockade |  |

### Sands of Karak Upper Left Long Room (Coral_27)

**Game ID:** Coral_27

**Contributors:** Pyxl

#### Subrooms

- Right Ledge
- Left Ledge
- Shell Ledge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Ledge | [Coral Tower Entrance (Coral_28)](#coral-tower-entrance-coral28) | R | None |  | Verified |  |
| R | right1 | Right Ledge | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | UL | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Left Ledge | Right Ledge | easy Beast Crest pogo OR Clawline OR Faydown Cloak OR Drifters Cloak OR Sharpdart OR Dash |  | Verified |  |
| WR | Whole Room | Right Ledge | Left Ledge | ( Cling Grip AND ( ( ( Dash OR Drifters Cloak OR Faydown Cloak ) AND Sprint ) OR Clawline OR Sharpdart ) ) OR ( Faydown Cloak AND Clawline AND ( Proficient Movement AND Spike Pogo ) ) |  | Verified |  |
| DR | Drop | Left Ledge | Shell Ledge | easy Hunter Crest pogo OR easy Beast Crest pogo OR easy Architect Crest pogo OR easy Shaman Crest pogo OR ( Ledge grab AND ( easy Reaper crest pogo OR easy Witch Crest pogo ) ) OR Dash OR Clawline OR Sharpdart OR Drifters Cloak OR Faydown Cloak OR ( easy Wanderer crest pogo AND easy Needle Strike stall ) |  | Verified |  |
| DR | Drop | Shell Ledge | Left Ledge | Ledge Grab OR Clawline OR Faydown Cloak OR medium Beast Crest pogo |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell shard cache: Sands of Karak #3 | Shell Ledge | None |  | Verified | resource |  |
| Shell Shard cache: Sands of Karak #4 | Shell Ledge | None |  | Verified | resource |  |
| Boss: Raging Conchfly | Left Ledge | Needle Upgrades 2 |  | Verified | boss |  |

### Sands of Karak Upper Right Long Room (Coral_44)

**Game ID:** Coral_44

**Contributors:** Pyxl

#### Subrooms

- Left Exit
- Right Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Exit | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | UR | None |  | Verified |  |
| R | right1 | Right Exit | [Sands of Karak Right Side Tall room (Coral_26)](#sands-of-karak-right-side-tall-room-coral26) | UL | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Left Exit | Right Exit | Cling grip AND ( Clawline OR ( Faydown Cloak AND ( Dash OR Sharpdart OR Drifters Cloak ) ) ) |  | Verified |  |
| WR | Whole Room | Right Exit | Left Exit | Clawline AND ( Drifters Cloak OR easy Shaman Crest pogo ) AND ( Cling grip OR Silk Soar ) |  | Verified |  |

#### Check Locations

No check locations defined.

### Sands of Shakra (Coral_40)

**Game ID:** Coral_40

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | ULL | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map: Sands of Karak |  | None |  | Verified | collectible |  |
| Shell Shard Cache: Sands of Karak #9 |  | Faydown Cloak OR Cling Grip OR Silk Soar OR have Silk Skill: Thread Storm OR have Silk Skill: Rune Rage OR ( easy Beast Crest pogo AND easy Needle Strike stall ) |  | Verified | resource |  |
| Shell Shard Cache: Sands of Karak #10 |  | Faydown Cloak OR Cling Grip OR Silk Soar OR have Silk Skill: Thread Storm OR have Silk Skill: Rune Rage OR ( easy Beast Crest pogo AND easy Needle Strike stall ) |  | Verified | resource |  |

### Watcher at the Edge (Coral_39)

**Game ID:** Coral_39

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Sands of Karak Lower Left Long Room (Coral_23)](#sands-of-karak-lower-left-long-room-coral23) | UL | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Watcher at the edge |  | Needolin AND Needle Upgrades 2 |  | Verified | boss |  |
| Grey Memento |  | Needolin AND Needle Upgrades 2 |  | Verified | collectible |  |

### Voltnest (Coral_29)

**Game ID:** Coral_29

**Contributors:** Pyxl

#### Subrooms

- Start
- Centre
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Start | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | D | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EJ | Electric Jumps | Start | Centre | ( Cling grip OR ( ( Dash AND Scuttlebrace ) AND ( Dash OR Clawline OR Drifters Cloak OR Faydown Cloak OR Sharpdart ) ) ) |  | Verified |  |
| EJ | Electric Jumps | Centre | Start | ( Cling grip OR ( ( Dash AND Scuttlebrace ) AND ( Dash OR Clawline OR Drifters Cloak OR Faydown Cloak OR Sharpdart ) ) ) |  | Verified |  |
| BD | Big Drop | Centre | Bottom | None |  | Verified |  |
| CB | Climb back | Bottom | Centre | Cling Grip AND ( Faydown Cloak OR ( Silk Soar AND ( ( Dash AND Ledge grab ) OR Clawline OR easy Beast Crest pogo OR Sharpdart OR Drifters Cloak ) ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Volt Filament | Bottom | None |  | Verified | collectible |  |
| Boss: Voltwyrm | Bottom | None |  | Verified | boss |  |

## The Slab

### Slab Bridge (Slab_01)

**Game ID:** Slab_01

**Contributors:** samupo

#### Subrooms

- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Slab Entrance (Slab_02)](#slab-entrance-slab02) | R | none |  |  |  |
| R | right1 | Right | [Choral Chambers Outside Spa (Song_04)](#choral-chambers-outside-spa-song04) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Left | Right | cling grip OR ledge grab OR faydown cloak OR clawline |  | Verified | You can jump off of the left obstacle and use clawline twice, this cannot be done from the other side |
| H | Horizontal | Right | Left | cling grip OR ledge grab OR faydown cloak |  | Verified |  |

#### Check Locations

No check locations defined.

### Slab Arena (Slab_16)

**Game ID:** Slab_16

#### Subrooms

- Bottom Tunnel
- Right Entrance
- Arena

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 | Arena | [Slab Broodmother Alcove](#slab-broodmother-alcove) | U | complete THE The Wailing Mother Wish Promised |  | Needs verification | need the room mapped |
| B | bot1 | Bottom Tunnel | [Slab Chilly Prison (Slab_15)](#slab-chilly-prison-slab15) | T | none |  |  |  |
| L | left1 | Bottom Tunnel | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | USR | cling grip |  |  | Naked. |
| T | top1 | Arena | [Slab Chilly Top (Slab_22)](#slab-chilly-top-slab22) | BL | cling grip OR silk soar |  |  | Naked |
| R | right1 | Right Entrance | [Slab Cell (Slab_03)](#slab-cell-slab03) | L0L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| A | Arena | Arena | Right Entrance | have Key of Heretic |  |  |  |
| A | Arena | Right Entrance | Arena | have Key of Heretic |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Key of Heretic | Arena | defeat gauntlet fight |  |  | collectible |  |
| Gauntlet Fight | Arena | none |  |  | gauntlet |  |
| The Wailing Mother Wish Broodmother Alcove Trigger | Arena | none |  | Verified | logic-point |  |

### Slab Broodmother Alcove

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| U | unknown |  | [Slab Arena (Slab_16)](#slab-arena-slab16) | D |  | TODO | Needs verification |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Broodmother Boss Fight |  |  | TODO | Needs verification | boss | unknown if gated by quest or just room access |
| Broodmother's Eye |  | defeat Broodmother Boss Fight |  | Verified | collectible |  |

### Slab Cell (Slab_03)

**Game ID:** Slab_03

#### Subrooms

- L0L
- L0R
- L1
- L2L
- L2R
- L3L
- L3R
- Key of Heretic Bridge
- L4
- L5L
- L5R
- L6
- L7
- L8

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CPT | door_slabCaged | L1 | [Slab Capture](#slab-capture) | CG | invalid |  |  | no destination, logically equivalent to L1 since you need to go up to reach L0 |
| L0L | left1 | L0L | [Slab Arena (Slab_16)](#slab-arena-slab16) | R | none |  |  |  |
| L0R | right1 | L0R | [Slab Why Room (Slab_17)](#slab-why-room-slab17) | L | have Key of Apostate |  |  |  |
| L1L | left2 | L1 | [Slab Chilly Prison (Slab_15)](#slab-chilly-prison-slab15) | R | none |  |  |  |
| L1R | right2 | L1 | [Slab Secret Side Room (Slab_18)](#slab-secret-side-room-slab18) | L | clear Breakable Wall Blockade IN slab secret side room |  |  | One way (opens from the other side) |
| L2L | left3 | L2L | [Slab Indolent Room (Slab_14)](#slab-indolent-room-slab14) | R | none |  |  |  |
| L2R | right3 | L2R | [Slab Grindle (Slab_20)](#slab-grindle-slab20) | L | none |  |  |  |
| L3L | left4 | L3L | [Slab Flea Prison (Slab_13)](#slab-flea-prison-slab13) | R | none |  |  |  |
| L3R | right4 | L3R | [Slab Cavern Exit (Slab_23)](#slab-cavern-exit-slab23) | L | none |  |  |  |
| L4L | left5 | L4 | [Slab Infleatween Top (Slab_04)](#slab-infleatween-top-slab04) | R | none |  |  |  |
| L4R | right5 | L4 | [Slab Entrance (Slab_02)](#slab-entrance-slab02) | L | activate slab entrance switch IN slab entrance |  |  |  |
| L5L | left6 | L5L | [Slab Infleatween Bottom (Slab_05)](#slab-infleatween-bottom-slab05) | R | have Key of Apostate |  |  |  |
| L5R | right8 | L5R | [Slab Cave Entrance (Slab_08)](#slab-cave-entrance-slab08) | L | none |  |  |  |
| L6R | right7 | L6 | [Slab Prelude (Slab_19b)](#slab-prelude-slab19b) | L | have Key of Heretic |  |  |  |
| L7L | left7 | L7 | [Slab Poodle (Slab_07)](#slab-poodle-slab07) | R1 | clear Exit Breakable Wall Blockade IN slab poodle |  |  |  |
| L8L | left8 | L8 | [Slab Poodle (Slab_07)](#slab-poodle-slab07) | R2 | none |  |  |  |
| L8R | right9 | L8 | [Slab Window (Slab_12)](#slab-window-slab12) | L | break wall right |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| L0 | L0 - L0 | L0L | L0R | ledge grab OR cling grip |  |  | Naked |
| 0L1 | L0l - L1 | L0L | L1 | none |  |  | falling |
| 0R1 | L0R - L1 | L0R | L1 | none |  |  | falling |
| 0L1 | L0l - L1 | L1 | L0L | cling grip OR silk soar |  |  | Naked |
| 0R1 | L0R - L1 | L1 | L0R | cling grip OR silk soar |  |  | Naked |
| 2L1 | L2L - L1 | L2L | L1 | cling grip OR silk soar |  |  | Naked. One way only |
| 2R1 | L2R - L1 | L2R | L1 | cling grip OR silk soar |  |  | Naked. One way only |
| L2 | L2 - L2 | L2L | L2R | ledge grab OR silk soar |  |  | Naked |
| L2 | L2 - L2 | L2R | L2L | ledge grab OR silk soar |  |  | Naked |
| 2FL | L2L to L3L | L2L | L3L | none |  |  | falling |
| 2FR | L2L to L3R | L2L | L3R | none |  |  | falling |
| 2DL | L2R to L3L | L2R | L3L | none |  |  | falling |
| 2DR | L2R to L3R | L2R | L3R | none |  |  | falling |
| L3 | L3 - L3 | L3L | L3R | cling grip OR silk soar OR dash |  |  | Naked. When you are still naked the bridge should be closed enabling you to just walk over it but added prior transitions to still have a valid path. |
| BR1 | Bridge1 | L3L | Key of Heretic Bridge | have Key of Heretic |  |  |  |
| BR2 | Bridge2 | L3R | Key of Heretic Bridge | have Key of Heretic |  |  |  |
| BL4 | Bridge to L4 | Key of Heretic Bridge | L4 | none |  |  | falling, one way lever |
| 5R4 | L5R to L4 | L5R | L4 | cling grip |  |  | one way lever |
| 5L4 | L5L to L4 | L5L | L4 | cling grip AND faydown |  |  | one way lever |
| L5 | L5 | L5L | L5R | (dash AND ledge grab) OR faydown OR clawline OR cling grip |  |  |  |
| L5 | L5 | L5R | L5L | ledge grab OR faydown OR clawline OR dash |  |  |  |
| 5LF | L5L to L6 | L5L | L6 | none |  |  | falling |
| 5LF | L5L to L6 | L6 | L5L | (cling grip OR silk soar) AND (ledge grab OR faydown OR clawline OR dash) |  |  |  |
| 5RF | L5R to L6 | L5R | L6 | none |  |  | falling |
| 5RF | L5R to L6 | L6 | L5R | cling grip OR silk soar |  |  |  |
| L6F | L6 to L8 | L6 | L8 | swim |  |  | L7 is non existant until opened |
| L7F | L7 to L8 | L7 | L8 | swim |  |  | falling |
| L7U | L7 to L6 | L7 | L6 | cling grip |  |  |  |

#### Check Locations

No check locations defined.

### Slab Chilly Prison (Slab_15)

**Game ID:** Slab_15

#### Subrooms

- Top
- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | MSR | none |  |  |  |
| B | bot1 | Left | [Slab Indolent Room (Slab_14)](#slab-indolent-room-slab14) | T | none |  |  |  |
| T | top1 | Top | [Slab Arena (Slab_16)](#slab-arena-slab16) | B | cling grip |  |  | Naked |
| R | right1 | Right | [Slab Cell (Slab_03)](#slab-cell-slab03) | L1L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Indolent Key | Left | Right | have Key of Indolent |  |  | Naked |
| H | Indolent Key | Right | Left | have Key of Indolent |  |  |  |
| T | Top | Right | Top | cling grip |  |  | Naked |
| T | Top | Top | Right | none |  |  | falling |

#### Check Locations

No check locations defined.

### Slab Bellway (Slab_06)

**Game ID:** Slab_06

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 |  | [Slab Infleatween Bottom (Slab_05)](#slab-infleatween-bottom-slab05) | B | none |  |  |  |
| NI | door1 |  | TODO |  |  | TODO |  | Not implemented as far as I know |
| L | left1 |  | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | LR | none | TODO |  | To Peaks_01 |
| BW | door_fastTravelExit |  | [Bellway Menu](#bellway-menu) | TS | Unlock Bellway The Slab |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: The Slab - Bellway |  | (cling grip AND faydown) OR silk soar |  |  | collectible |  |
| Bellway The Slab |  | Unlock Bellway Rosary Lock |  |  | travel |  |
| Bellway Rosary Lock |  | rosaries 40 |  |  | lock |  |

### Slab Cave Entrance (Slab_08)

**Game ID:** Slab_08

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 |  | [Slab Quiet Cell (Slab_Cell_Quiet)](#slab-quiet-cell-slabcellquiet) | B | (faydown AND cling grip) OR silk soar |  |  |  |
| L | left1 |  | [Slab Cell (Slab_03)](#slab-cell-slab03) | L5R | have Key of Heretic |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Slab - Left Orders |  | none |  |  | lore |  |
| The Slab - Right Orders |  | none |  |  | lore |  |

### Slab Cavern Exit (Slab_23)

**Game ID:** Slab_23

#### Subrooms

- Left
- Right
- Cavern

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Slab Cell (Slab_03)](#slab-cell-slab03) | L3R | none |  |  |  |
| R | right1 | Right | [Slab Shaft (Slab_21)](#slab-shaft-slab21) | BL | none |  |  |  |
| D1 | door1 | Left | [Slab Penitent Cell (Slab_Cell_Creature)](#slab-penitent-cell-slabcellcreature) | L | none |  |  |  |
| D2 | door2 | Cavern | [Slab Quiet Cell (Slab_Cell_Quiet)](#slab-quiet-cell-slabcellquiet) | T | none |  |  | Cavern door, for alternate entry, TBD |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Indolent Door | Left | Right | have Key of Indolent |  |  |  |
| H | Indolent Door | Right | Left | have Key of Indolent |  |  |  |
| V | Cavern | Cavern | Left | ledge grab OR faydown OR clawline OR silk soar |  |  |  |

#### Check Locations

No check locations defined.

### Slab Chilly Top (Slab_22)

**Game ID:** Slab_22

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | bot1 |  | [Slab Arena (Slab_16)](#slab-arena-slab16) | T | cling grip AND dash |  |  | Naked |
| BR | bot2 |  | [Slab Shaft (Slab_21)](#slab-shaft-slab21) | T | dash AND (cling grip OR ledge grab) |  |  | Naked |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Slab - Frayed Rosary String #3 |  | cling grip AND dash |  |  | collectible | Naked |

### Slab Entrance (Slab_02)

**Game ID:** Slab_02

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Slab Cell (Slab_03)](#slab-cell-slab03) | L4R | activate slab entrance switch |  |  |  |
| R | right1 |  | [Slab Bridge (Slab_01)](#slab-bridge-slab01) | L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Slab - Frayed Rosary String #1 |  | none |  |  | collectible |  |
| Slab Entrance Switch |  | flip switch down |  |  | switch |  |

### Slab First Sinner Antechamber (Slab_10c)

**Game ID:** Slab_10c

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Slab Prelude (Slab_19b)](#slab-prelude-slab19b) | R | cling grip |  |  |  |
| D | door1 |  | TODO |  | none |  |  | First Sinner boss fight |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Slab - Weaver Gate Inscription |  | faydown |  |  | lore |  |
| Rune Rage |  | defeat Boss: First Sinner |  |  | collectible |  |
| Boss: First Sinner |  | faydown |  |  | boss |  |

### Slab Flea Cell (Slab_Cell)

**Game ID:** Slab_Cell

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Slab Flea Prison (Slab_13)](#slab-flea-prison-slab13) | D | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: The Slab |  | none |  |  | collectible |  |

### Slab Flea Prison (Slab_13)

**Game ID:** Slab_13

#### Subrooms

- Top
- Secret

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Secret | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | LSR | none |  |  |  |
| B | bot1 | Secret | [Slab Infleatween Top (Slab_04)](#slab-infleatween-top-slab04) | T | none |  |  |  |
| R | right1 | Top | [Slab Cell (Slab_03)](#slab-cell-slab03) | L3L | none |  |  |  |
| D | door1 | Top | [Slab Flea Cell (Slab_Cell)](#slab-flea-cell-slabcell) | L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Slab Grindle (Slab_20)

**Game ID:** Slab_20

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Slab Cell (Slab_03)](#slab-cell-slab03) | L2R | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Slab - Map Pickup |  | none |  |  | collectible |  |
| The Slab - East Bench |  | none |  |  | bench |  |

### Slab Indolent Room (Slab_14)

**Game ID:** Slab_14

#### Subrooms

- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Left | [Slab Chilly Prison (Slab_15)](#slab-chilly-prison-slab15) | B | silk soar |  |  |  |
| R | right1 | Right | [Slab Cell (Slab_03)](#slab-cell-slab03) | L2L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| D | Indolent Door | Left | Right | have Key of Indolent |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Indolent Key | Left | none |  |  | collectible | Not randomized |

### Slab Infleatween Bottom (Slab_05)

**Game ID:** Slab_05

#### Subrooms

- Top
- Bottom
- Mid

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom | [Slab Bellway (Slab_06)](#slab-bellway-slab06) | T | none |  |  |  |
| T | top1 | Top | [Slab Infleatween Top (Slab_04)](#slab-infleatween-top-slab04) | B | none |  |  |  |
| R | right1 | Mid | [Slab Cell (Slab_03)](#slab-cell-slab03) | L5L | have Key of Apostate |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Mid | Top | cling grip OR silk soar |  |  |  |
| V | Vertical | Top | Mid | none |  |  | falling |
| V2 | Vertical 2 | Mid | Bottom | none |  |  | falling |
| V2 | Vertical 2 | Bottom | Mid | ledge grab OR faydown OR silk soar |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Slab - Shell Shard Cache #1 | Top | none |  |  | collectible |  |
| The Slab - Shell Shard Cache #2 | Top | none |  |  | collectible |  |
| The Slab - Shell Shard Cache #3 | Top | none |  |  | collectible |  |

### Slab Infleatween Top (Slab_04)

**Game ID:** Slab_04

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Slab Cell (Slab_03)](#slab-cell-slab03) | L4L | none |  |  |  |
| T | top1 |  | [Slab Flea Prison (Slab_13)](#slab-flea-prison-slab13) | B | (cling grip AND (ledge grab OR dash)) OR silk soar |  |  |  |
| B | bot1 |  | [Slab Infleatween Bottom (Slab_05)](#slab-infleatween-bottom-slab05) | T | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Slab - Shard Bundle |  | ledge grab OR cling grip OR clawline OR faydown |  |  | collectible |  |

### Slab Penitent Cell (Slab_Cell_Creature)

**Game ID:** Slab_Cell_Creature

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Slab Cavern Exit (Slab_23)](#slab-cavern-exit-slab23) | D1 | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Slab Poodle (Slab_07)

**Game ID:** Slab_07

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R1 | right1 |  | [Slab Cell (Slab_03)](#slab-cell-slab03) | L7L | swim AND faydown AND clawline AND cling grip AND clear Exit Breakable Wall Blockade |  |  |  |
| R2 | right2 |  | [Slab Cell (Slab_03)](#slab-cell-slab03) | L8L | swim |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Exit Breakable Wall Blockade |  | break wall right |  |  | blockade |  |

### Slab Prelude (Slab_19b)

**Game ID:** Slab_19b

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Slab Cell (Slab_03)](#slab-cell-slab03) | L6R | have Key of Heretic |  |  |  |
| R | right1 |  | [Slab First Sinner Antechamber (Slab_10c)](#slab-first-sinner-antechamber-slab10c) | L | (faydown AND cling grip) OR silk soar |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Slab - Rosary Chest |  | none |  |  | collectible |  |
| The Slab - Rosary Cache #2 |  | none |  |  | collectible |  |
| The Slab - Rosary Cache #3 |  | none |  |  | collectible |  |
| The Slab - Rosary Cache #4 |  | none |  |  | collectible |  |
| The Slab - Rosary Cache #5 |  | none |  |  | collectible |  |

### Slab Quiet Cell (Slab_Cell_Quiet)

**Game ID:** Slab_Cell_Quiet

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | left1 | Top | [Slab Cavern Exit (Slab_23)](#slab-cavern-exit-slab23) | D2 | none |  |  |  |
| B | left2 | Bottom | [Slab Cave Entrance (Slab_08)](#slab-cave-entrance-slab08) | D | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Bottom | Top | cling grip OR silk soar |  |  |  |
| V | Vertical | Top | Bottom | none |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Slab - Memory Locket | Top | none |  |  | collectible |  |

### Slab Secret Side Room (Slab_18)

**Game ID:** Slab_18

#### Subrooms

- Top
- Bottom
- Corpse

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Top | [Slab Shaft (Slab_21)](#slab-shaft-slab21) | UL | none |  |  |  |
| L | left1 | Bottom | [Slab Cell (Slab_03)](#slab-cell-slab03) | L1R | clear Breakable Wall Blockade |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TC | Top to Corpse | Top | Corpse | none |  |  | falling |
| TC | Top to Corpse | Corpse | Top | cling grip |  |  |  |
| CB | Corpse to Bottom | Corpse | Bottom |  |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Slab - Shell Shard Cache #6 | Top | cling grip OR (silk soar AND (ledge grab OR dash)) |  |  | collectible | Naked |
| The Slab - Shell Shard Cache #7 | Top | cling grip OR (silk soar AND (ledge grab OR dash)) |  |  | collectible | Naked |
| The Slab - Frayed Rosary String #2 | Corpse | none |  |  | collectible |  |
| The Slab - Rosary Cache #1 | Corpse | none |  |  | collectible |  |
| Breakable Wall Blockade | Bottom | break wall left |  |  | blockade |  |

### Slab Shaft (Slab_21)

**Game ID:** Slab_21

#### Subrooms

- Top
- Mid
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | left3 | Bottom | [Slab Cavern Exit (Slab_23)](#slab-cavern-exit-slab23) | R | none |  |  | Naked. Logic accounting for not being able to do more. |
| T | top1 | Top | [Slab Chilly Top (Slab_22)](#slab-chilly-top-slab22) | BR | cling grip OR silk soar |  |  | Naked. Logic accounting for not being able to do more. |
| UL | left1 | Mid | [Slab Secret Side Room (Slab_18)](#slab-secret-side-room-slab18) | R | none |  |  | Naked. Logic accounting for not being able to do more. |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Vertical 1 | Bottom | Mid | cling grip AND dash |  |  | Naked |
| V1 | Vertical 1 | Mid | Bottom | none |  |  | falling |
| V2 | Vertical 2 | Mid | Top | cling grip |  |  | Naked |
| V2 | Vertical 2 | Top | Mid | none |  |  | falling |

#### Check Locations

No check locations defined.

### Slab Why Room (Slab_17)

**Game ID:** Slab_17

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Slab Cell (Slab_03)](#slab-cell-slab03) | L0R | have Key of Apostate |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Slab (Key of Apostate) - Mask Shard |  | cling grip AND dash AND faydown AND clawline AND spike pogo AND drifter's cloak | TODO |  | collectible | Not actually tested, placeholded everything |

### Slab Window (Slab_12)

**Game ID:** Slab_12

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Slab Cell (Slab_03)](#slab-cell-slab03) | L8R | break wall left | TODO |  | There's a breakable wall on the other side and it hasn't been tested on this side |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Slab - Shell Shard Cache #4 |  | swim |  |  | collectible |  |
| The Slab - Shell Shard Cache #5 |  | swim |  |  | collectible |  |
| Relic: Weaver Effigy (Atla, The Slab) |  | cling grip AND (dash OR clawline OR faydown cloak) |  |  | collectible |  |

## Mount Fay

### Mount Fay Entrance (Peak_01)

**Game ID:** Peak_01

**Contributors:** Pyxl

#### Subrooms

- Slab Spool Room
- Slab Side Room Lower
- Slab Side Room Upper
- lower Entrance
- Lower Left Exit
- Lower Middle Left Exit
- Upper Middle Left Exit
- Upper Left Exit
- Shell Shard Ledge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LSR | right3 | Slab Spool Room | [Slab Flea Prison (Slab_13)](#slab-flea-prison-slab13) | L | None |  | Verified |  |
| C4 | top4 | Upper Left Exit | [Mount Fay Right Side Middle Room (Peak_07)](#mount-fay-right-side-middle-room-peak07) | F4 | Silk Soar |  | Verified |  |
| C2 | top2 | Upper Left Exit | [Mount Fay Right Side Middle Room (Peak_07)](#mount-fay-right-side-middle-room-peak07) | F2 | Silk Soar |  | Verified |  |
| C3 | top3 | Upper Left Exit | [Mount Fay Right Side Middle Room (Peak_07)](#mount-fay-right-side-middle-room-peak07) | F3 | Silk Soar |  | Verified |  |
| UL | left1 | Upper Left Exit | [Mount Fay Shakra (Peak_02)](#mount-fay-shakra-peak02) | UR | None |  | Verified |  |
| LL | left4 | Lower Left Exit | [Mount Fay Shakra (Peak_02)](#mount-fay-shakra-peak02) | LR | None |  | Verified |  |
| LML | left3 | Lower Middle Left Exit | [Mount Fay Shakra (Peak_02)](#mount-fay-shakra-peak02) | LMR | None |  | Verified |  |
| UML | left2 | Upper Middle Left Exit | [Mount Fay Shakra (Peak_02)](#mount-fay-shakra-peak02) | UMR | None |  | Verified |  |
| USR | right1 | Slab Side Room Upper | [Slab Arena (Slab_16)](#slab-arena-slab16) | L | None |  | Verified |  |
| C1 | top1 | Upper Left Exit | [Mount Fay Right Side Middle Room (Peak_07)](#mount-fay-right-side-middle-room-peak07) | F1 | Cling Grip AND ( Clawline OR ( Faydown Cloak AND DRifters Cloak AND Dash ) OR ( Drifters Cloak AND Sharpdart AND ( Proficient Movement AND Spike Pogo ) AND Hard Heal Stall AND Hard Cocoon Skip ) ) |  | Verified |  |
| MSR | right2 | Slab Side Room Lower | [Slab Chilly Prison (Slab_15)](#slab-chilly-prison-slab15) | L | None |  | Verified |  |
| LR | right4 | lower Entrance | [Slab Bellway (Slab_06)](#slab-bellway-slab06) | L | None |  | Verified |  |
| DU | Dummy | Upper Left Exit | [Mount Fay Right Side Middle Room (Peak_07)](#mount-fay-right-side-middle-room-peak07) | F5 | Invalid |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SL | Slab Connection | Slab Side Room Upper | Slab Side Room Lower | None |  | Verified |  |
| SL | Slab Connection | Slab Side Room Lower | Slab Side Room Upper | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| LC | Lower Crossing | lower Entrance | Lower Left Exit | Silk Soar OR Clawline OR ( Faydown Cloak AND ( Proficient Movement AND Spike Pogo ) AND Hard Heal Stall AND Hard Cocoon Skip AND Ledge Grab ) OR ( Sharpdart AND Drifters Cloak ) |  | Verified |  |
| LC | Lower Crossing | Lower Left Exit | lower Entrance | Cling Grip OR Silk Soar OR Clawline OR Faydown Cloak OR ( Dash AND ( Sprint OR Drifters Cloak OR Sharpdart OR easy Beast Crest pogo OR Medium Heal Stall ) ) |  | Verified |  |
| LL | Lower Ledge | Lower Left Exit | Lower Middle Left Exit | Silk Soar OR ( Faydown Cloak AND ( Cling Grip OR ( Hard Heal Stall AND Scuttlebrace ) ) ) |  | Verified |  |
| LL | Lower Ledge | Lower Middle Left Exit | Lower Left Exit | None |  | Verified |  |
| MC | Middle Crossing | Lower Middle Left Exit | Shell Shard Ledge | ( Cling Grip AND ( ( Clawline OR Drifters Cloak OR ( Faydown Cloak AND ( Dash OR Sharpdart ) ) ) OR ( Medium Reaper Crest pogo AND Faydown Cloak AND Clawline AND ( Proficient Movement AND Spike Pogo ) ) ) ) |  | Verified |  |
| MC | Middle Crossing | Shell Shard Ledge | Lower Middle Left Exit | Clawline OR Silk Soar OR Drifters Cloak OR ( Dash AND Faydown Cloak ) |  | Verified |  |
| SS | Silk Soar Shards | lower Entrance | Shell Shard Ledge | Silk Soar |  | Verified |  |
| SS | Silk Soar Shards | Shell Shard Ledge | lower Entrance | None |  | Verified |  |
| TA | The Ascent | Lower Middle Left Exit | Upper Middle Left Exit | Silk Soar OR ( Cling Grip AND ( Clawline OR ( Faydown Cloak AND Drifters Cloak ) OR ( Sharpdart AND Drifters Cloak AND Hard Cocoon Skip AND ( Sprint OR Have Tool Flintslate ) ) ) ) |  | Verified |  |
| TA | The Ascent | Upper Middle Left Exit | Lower Middle Left Exit | None |  | Verified |  |
| SH | Shortcut | Upper Middle Left Exit | Upper Left Exit | Faydown Cloak OR Silk Soar OR ( complete Breakable Wall - Mount Fay Entrance AND ( Cling Grip OR Scuttlebrace OR ( Easy Beast Crest pogo AND Medium Heal Stall AND Ledge Grab ) ) ) |  | Verified |  |
| SH | Shortcut | Upper Left Exit | Upper Middle Left Exit | None |  | Verified |  |
| DR | Drop | Upper Left Exit | Shell Shard Ledge | None |  | Verified |  |
| DR | Drop | Shell Shard Ledge | Upper Left Exit | Silk Soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mount Fay - Shell shard cache #1 | Shell Shard Ledge | None |  | Verified | resource |  |
| Mount Fay - Shell shard cache #2 | Shell Shard Ledge | None |  | Verified | resource |  |
| The Slab - Spool Fragment | Slab Spool Room | cling grip OR Scuttlebrace OR Silk Soar |  | Verified | collectible | Duplicate check name for spool fragment? |
| Breakable Wall - Mount Fay Entrance | Upper Left Exit | None |  | Verified | blockade |  |

### Brightvein (Peak_06)

**Game ID:** Peak_06

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Brightvein Entrance (Peak_06b)](#brightvein-entrance-peak06b) | D | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mount Fay - Shell Shard Cache #3 |  | silk Soar OR ( clawline AND cling grip ) |  | Verified | resource |  |
| Mount Fay - Shell Shard Cache #4 |  | Silk Soar OR ( Clawline AND Cling Grip ) |  | Verified | resource |  |
| Brightvein - Maskshard |  | Silk Soar AND Clawline AND Cling Grip AND Faydown Cloak |  | Verified | collectible |  |

### Brightvein Entrance (Peak_06b)

**Game ID:** Peak_06b

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Mount Fay Magnetite Outcropping (Peak_05e)](#mount-fay-magnetite-outcropping-peak05e) | UR | None |  | Verified |  |
| D | door1 |  | [Brightvein (Peak_06)](#brightvein-peak06) | L | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### FayForn (Peak_08b)

**Game ID:** Peak_08b

**Contributors:** Pyxl

#### Subrooms

- Lower Entrance
- Fayforn
- Left Exit
- Drop
- Bench Entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L2 | left2 | Bench Entrance | [Mount Fay Peak Bench (Peak_12)](#mount-fay-peak-bench-peak12) | R | None |  | Verified |  |
| F3 | bot6 | Drop | [Mount Fay Right Side Middle Room (Peak_07)](#mount-fay-right-side-middle-room-peak07) | C3 | None |  | Verified |  |
| L1 | left1 | Left Exit | [Mount Fay Upper Slope (Peak_08)](#mount-fay-upper-slope-peak08) | R | Silk Soar OR Faydown Cloak |  | Verified |  |
| F1 | bot4 | Lower Entrance | [Mount Fay Right Side Middle Room (Peak_07)](#mount-fay-right-side-middle-room-peak07) | C1 | None |  | Verified |  |
| F2 | bot5 | Drop | [Mount Fay Right Side Middle Room (Peak_07)](#mount-fay-right-side-middle-room-peak07) | C2 | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WT | Wind Tunnel Acsent | Lower Entrance | Fayforn | Drifters Cloak AND ( Cling Grip OR Scuttlebrace OR Silk Soar ) |  | Verified |  |
| WT2 | Wind TUnnel 2 | Lower Entrance | Left Exit | Drifters Cloak AND ( Cling Grip OR Scuttlebrace OR Silk Soar ) |  | Verified |  |
| DR1 | Drop 1 | Fayforn | Bench Entrance | None |  | Verified |  |
| DR1 | Drop 1 | Bench Entrance | Fayforn | Silk Soar OR ( Cling Grip AND Faydown Cloak ) |  | Verified |  |
| DR2 | Drop 2 | Bench Entrance | Drop | None |  | Verified |  |
| CR | Crossing | Left Exit | Fayforn | Drifters Cloak |  | Verified |  |
| CR | Crossing | Fayforn | Left Exit | Dash OR Sprint OR Drifters Cloak OR Faydown Cloak OR Clawline OR Sharpdart OR Easy Beast Crest Pogo |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Faydown Cloak | Fayforn | Needolin |  | Verified | collectible |  |

### Mask Maker (Peak_Mask_Maker)

**Game ID:** Peak_Mask_Maker

**Contributors:** Pxyl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Mask Maker Passage (Peak_05d)](#mask-maker-passage-peak05d) | D | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Mask Maker Passage (Peak_05d)

**Game ID:** Peak_05d

**Contributors:** Pyxl

#### Subrooms

- Mask Maker Hut
- Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | Exit | [Mount Fay Upper Slope (Peak_08)](#mount-fay-upper-slope-peak08) | C | None |  | Verified |  |
| D | door1 | Mask Maker Hut | [Mask Maker (Peak_Mask_Maker)](#mask-maker-peakmaskmaker) | R | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PL | Platforming | Exit | Mask Maker Hut | Cling Grip AND Faydown Cloak |  | Verified |  |
| PL | Platforming | Mask Maker Hut | Exit | None |  | Verified |  |

#### Check Locations

No check locations defined.

### Memory Crystal (Bellway_Peak_02)

**Game ID:** Bellway_Peak_02

**Contributors:** Pyxl

#### Subrooms

- End
- Start

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Start | [Mount Fay Bench Toll (Bellway_Peak)](#mount-fay-bench-toll-bellwaypeak) | LR | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| IT | Ice Tunnel | Start | End | None |  | Verified |  |
| IT | Ice Tunnel | End | Start | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mount Fay - Rosary Cache #4 | Start | None |  | Verified | resource |  |
| Memory Crystal | End | None |  | Verified | collectible |  |

### Mount Fay Bench Toll (Bellway_Peak)

**Game ID:** Bellway_Peak

**Contributors:** Pyxl

#### Subrooms

- Lower Area
- Upper Area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Upper Area | [Mount Fay Ice Lake Platforming Room (Peak_04)](#mount-fay-ice-lake-platforming-room-peak04) | L | None |  | Verified |  |
| LR | right2 | Lower Area | [Memory Crystal (Bellway_Peak_02)](#memory-crystal-bellwaypeak02) | L | complete Breakable Wall - Mount Fay Bench Toll |  | Verified | Can Be Broken From Both sides |
| C | top1 | Upper Area | [Mount Fay Lower Slope (Peak_05)](#mount-fay-lower-slope-peak05) | F | Silk Soar OR ( Cling Grip AND ( Dash OR Drifters Cloak OR Faydown Cloak OR Clawline ) ) OR ( Clawline AND Faydown Cloak AND Ledge Grab ) OR ( Faydown Cloak AND Scuttlebrace ) |  | Verified |  |
| UL | left1 | Upper Area | [Mount Fay Mask Shard (Peak_04c)](#mount-fay-mask-shard-peak04c) | UR | None |  | Verified |  |
| LL | left2 | Lower Area | [Mount Fay Mask Shard (Peak_04c)](#mount-fay-mask-shard-peak04c) | LR | Ledge Grab OR Dash OR Faydown Cloak OR Cling Grip OR Silk Soar |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TD | Trapdoor | Lower Area | Upper Area | ( Faydown Cloak OR Silk Soar OR ( Cling Grip AND Clawline ) OR ( Ledge Grab AND ( Dash OR Clawline OR Drifters Cloak ) ) ) AND Complete Trapdoor lever |  | Verified | Lever activation is permanent |
| TD | Trapdoor | Upper Area | Lower Area | ( Faydown Cloak OR Silk Soar OR ( Cling Grip AND Clawline ) OR ( Ledge Grab AND ( Dash OR Clawline OR Drifters Cloak ) ) ) AND Complete Trapdoor lever |  | Verified | Lever activation is permanent |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mount Fay - Rosary Cache #1 | Upper Area | Cling Grip OR Silk Soar OR Ledge grab OR Faydown Cloak |  | Verified | resource |  |
| Mount Fay - Rosary Cache #2 | Upper Area | Cling Grip OR Silk Soar OR Ledge grab OR Faydown Cloak |  | Verified | resource |  |
| Mount Fay - Rosary Cache #3 | Upper Area | Cling Grip OR Silk Soar OR Ledge grab OR Faydown Cloak |  | Verified | resource |  |
| Trapdoor Lever | Lower Area | Faydown Cloak OR Silk Soar OR ( Cling Grip AND Clawline ) OR ( Ledge Grab AND ( Dash OR Clawline OR Drifters Cloak ) ) |  | Verified | switch |  |
| Breakable Wall - Mount Fay Bench Toll | Lower Area | None |  | Verified | blockade |  |

### Mount Fay Frozen Flea (Peak_05c)

**Game ID:** Peak_05c

**Contributors:** Pyxl

#### Subrooms

- Upper Left
- Right Exit
- Frozen Flea

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right Exit | [Mount Fay Magnetite Outcropping (Peak_05e)](#mount-fay-magnetite-outcropping-peak05e) | L | None |  | Verified |  |
| L | left2 | Upper Left | [Mount Fay Lower Slope (Peak_05)](#mount-fay-lower-slope-peak05) | R | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SD | Spike Drop | Upper Left | Right Exit | Clawline AND ( Cling Grip OR ( Faydown Cloak AND Ledge Grab ) ) |  | Verified | One Way |
| FF | Frozen Flea | Right Exit | Frozen Flea | Cling Grip OR Scuttlebrace |  | Verified |  |
| FF | Frozen Flea | Frozen Flea | Right Exit | Cling Grip OR Dash OR Drifters Cloak OR Faydown Cloak OR Clawline OR Sharpdart |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Mount Fay | Frozen Flea | None |  | Verified | collectible |  |

### Mount Fay Ice Lake Platforming Room (Peak_04)

**Game ID:** Peak_04

**Contributors:** Pyxl

#### Subrooms

- Left Ledge
- Right Ledge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Ledge | [Mount Fay Bench Toll (Bellway_Peak)](#mount-fay-bench-toll-bellwaypeak) | UR | None |  | Verified |  |
| R | right1 | Right Ledge | [Mount Fay Large Servitor Hallway (Peak_04d)](#mount-fay-large-servitor-hallway-peak04d) | L | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| IL | Ice Lake | Left Ledge | Right Ledge | ( Clawline AND ( Swim OR Faydown Cloak OR Drifters Cloak OR Cling Grip ) ) |  | Verified |  |
| IL | Ice Lake | Right Ledge | Left Ledge | ( Clawline AND ( Swim OR Faydown Cloak OR Drifters Cloak OR Cling Grip ) ) |  | Verified |  |

#### Check Locations

No check locations defined.

### Mount Fay Large Servitor Hallway (Peak_04d)

**Game ID:** Peak_04d

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Mount Fay Shakra (Peak_02)](#mount-fay-shakra-peak02) | ML | None |  | Verified |  |
| L | left1 |  | [Mount Fay Ice Lake Platforming Room (Peak_04)](#mount-fay-ice-lake-platforming-room-peak04) | R | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Mount Fay Lore Room (Peak_10)

**Game ID:** Peak_10

**Contributors:** pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Mount Fay Shakra (Peak_02)](#mount-fay-shakra-peak02) | LL | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mount Fay - Weaver Inscrytion |  | None |  | Verified | lore |  |

### Mount Fay Lower Slope (Peak_05)

**Game ID:** Peak_05

**Contributors:** Pyxl

#### Subrooms

- Bottom
- Ceiling Area
- Right Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top2 | Ceiling Area | [Mount Fay Upper Slope (Peak_08)](#mount-fay-upper-slope-peak08) | F | None |  | Verified |  |
| F | bot1 | Bottom | [Mount Fay Bench Toll (Bellway_Peak)](#mount-fay-bench-toll-bellwaypeak) | C | None |  | Verified |  |
| R | right3 | Right Exit | [Mount Fay Frozen Flea (Peak_05c)](#mount-fay-frozen-flea-peak05c) | L | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SH | Shaft | Ceiling Area | Right Exit | Complete Mount Fay Slope Lever |  | Verified |  |
| SH | Shaft | Right Exit | Ceiling Area | Complete Mount Fay Slope Lever AND ( ( Faydown Cloak AND Drifters Cloak AND Cling Grip AND Sharpdart ) OR Silk Soar OR ( Clawline AND Faydown Cloak AND Cling Grip ) ) |  | Verified |  |
| BS | Big Slope | Right Exit | Bottom | None |  | Verified |  |
| BS | Big Slope | Bottom | Right Exit | Faydown Cloak OR ( Cling Grip AND Clawline ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mount Fay Slope Lever | Ceiling Area | None |  | Verified | switch |  |

### Mount Fay Magnetite Outcropping (Peak_05e)

**Game ID:** Peak_05e

**Contributors:** Pyxl

#### Subrooms

- Left Exit
- Brightvein
- Right Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right2 | Brightvein | [Brightvein Entrance (Peak_06b)](#brightvein-entrance-peak06b) | L | Faydown Cloak OR Clawline OR Dash |  | Verified |  |
| LR | right1 | Right Exit | [Mount Fay Shakra (Peak_02)](#mount-fay-shakra-peak02) | UL | None |  | Verified |  |
| L | left1 | Left Exit | [Mount Fay Frozen Flea (Peak_05c)](#mount-fay-frozen-flea-peak05c) | R | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| IL | Ice Lake | Right Exit | Left Exit | Swim OR Sprint OR Clawline OR Faydown Cloak OR ( Drifters Cloak AND Dash ) OR Sharpdart |  | Verified |  |
| IL | Ice Lake | Left Exit | Right Exit | Swim OR Sprint OR Clawline OR Faydown Cloak OR ( Drifters Cloak AND Dash ) OR Sharpdart |  | Verified |  |
| BRL | Brightvein Left | Brightvein | Left Exit | Drifters Cloak OR Dash OR Clawline OR Faydown Cloak OR Sharpdart OR Swim |  | Verified |  |
| BRL | Brightvein Left | Left Exit | Brightvein | Silk Soar AND ( Swim OR Clawline OR Faydown Cloak OR ( Dash AND Drifters Cloak ) ) |  | Verified |  |
| BRR | Brightvein Right | Right Exit | Brightvein | Silk Soar AND ( Swim OR Clawline OR Faydown Cloak OR ( Dash AND Drifters Cloak ) ) |  | Verified |  |
| BRR | Brightvein Right | Brightvein | Right Exit | Drifters Cloak OR Dash OR Clawline OR Faydown Cloak OR Sharpdart OR Swim |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Magnetite Outcrop | Brightvein | None |  | Verified | lore | Lore thingy not included rn |

### Mount Fay Mask Shard (Peak_04c)

**Game ID:** Peak_04c

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | right2 |  | [Mount Fay Bench Toll (Bellway_Peak)](#mount-fay-bench-toll-bellwaypeak) | LL | None |  | Verified |  |
| UR | right1 |  | [Mount Fay Bench Toll (Bellway_Peak)](#mount-fay-bench-toll-bellwaypeak) | UL | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mount Fay - Mask Shard |  | Silk Soar OR ( Faydown Cloak AND ( Cling Grip OR Scuttlebrace ) ) |  | Verified | collectible |  |

### Mount Fay Peak Bench (Peak_12)

**Game ID:** Peak_12

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [FayForn (Peak_08b)](#fayforn-peak08b) | L2 | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mount Fay Peak Bench |  | None |  | Verified | bench |  |
| Silkshot ( Original ) |  | Have Craftmetal AND Have Ruined Tool |  | Verified | collectible |  |

### Mount Fay Right Side Middle Room (Peak_07)

**Game ID:** Peak_07

**Contributors:** Pyxl

#### Subrooms

- Bottom
- Pinstress Arena
- Shell Shard Slope
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C2 | top2 | Top | [FayForn (Peak_08b)](#fayforn-peak08b) | F2 | Silk Soar |  | Verified |  |
| F5 | bot5 | Bottom | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | DU | INVALID |  | Verified | Doesnt Have an inverse |
| C3 | top3 | Top | [FayForn (Peak_08b)](#fayforn-peak08b) | F3 | Silk Soar |  | Verified |  |
| F1 | bot1 | Bottom | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | C1 | None |  | Verified |  |
| C1 | top1 | Top | [FayForn (Peak_08b)](#fayforn-peak08b) | F1 | None |  | Verified |  |
| F2 | bot2 | Bottom | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | C2 | None |  | Verified |  |
| F4 | bot4 | Bottom | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | C4 | None |  | Verified |  |
| F3 | bot3 | Bottom | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | C3 | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WA | Wall | Bottom | Pinstress Arena | Silk Soar OR ( Cling Grip AND ( ( Faydown Cloak AND Enemy Pogo AND Spike Pogo ) OR ( Clawline AND Enemy Pogo ) OR ( Hard Reaper crest Pogo AND Dash AND Sprint AND Drifters Cloak AND Hard Flea Brew Stall AND Hard Heal Stall ) ) ) |  | Verified |  |
| WA | Wall | Pinstress Arena | Bottom | None |  | Verified |  |
| LS | Lower Slope | Bottom | Shell Shard Slope | Silk SOar OR ( cling Grip AND ( Faydown Cloak OR Clawline OR ( Dash AND Drifters Cloak AND Easy Reaper Crest Pogo ) ) ) |  | Verified |  |
| LS | Lower Slope | Shell Shard Slope | Bottom | None |  | Verified |  |
| US | Upper Slope | Pinstress Arena | Shell Shard Slope | None |  | Verified |  |
| US | Upper Slope | Shell Shard Slope | Pinstress Arena | Faydown Cloak AND Cling Grip AND  Proficient Movement  AND Spike Pogo |  | Verified |  |
| UW | Upper Wall | Pinstress Arena | Top | Silk Soar OR ( Cling Grip AND ( ( Clawline OR Faydown Cloak ) OR ( Dash AND Drifters Cloak AND Sharpdart ) ) ) |  | Verified |  |
| UW | Upper Wall | Top | Pinstress Arena | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mount Fay Warm Bench | Bottom | None |  | Verified | bench |  |
| Mount Fay - Shell Shard Cache #5 | Shell Shard Slope | None |  | Verified | resource |  |
| Mount Fay - Shell Shard Cache #6 | Shell Shard Slope | None |  | Verified | resource |  |
| Mount Fay - Shell Shard Cache #7 | Shell Shard Slope | None |  | Verified | resource |  |
| Pinstress Boss Fight | Pinstress Arena | complete Fatal Resolve Wish Promised IN Windy Pinstress Room OR (  complete Fatal Resolve Wish Promised IN Bellhart Wish Wall AND complete Read Pinstress Note IN Windy Pinstress Room ) | TODO |  | boss | wiki says you need to read the note if you start from the wish wall - may need to change if inaccurate |
| Fatal Resolve Wish Granted | Pinstress Arena | defeat Pinstress Boss Fight |  | Verified | event |  |
| Pin Badge | Pinstress Arena | complete Pinstress Boss Fight |  | Verified | collectible |  |

### Mount Fay Shakra (Peak_02)

**Game ID:** Peak_02

**Contributors:** Pyxl

#### Subrooms

- Shakra
- Lower Middle Hallway
- Lower Left Ledge
- Middle Left Ledge
- Upper Left Ledge
- Upper Hallway
- Upper Middle Hallway

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | right3 | Shakra | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | LL | None |  | Verified |  |
| UR | right4 | Upper Hallway | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | UL | None |  | Verified |  |
| ML | left1 | Middle Left Ledge | [Mount Fay Large Servitor Hallway (Peak_04d)](#mount-fay-large-servitor-hallway-peak04d) | R | None |  | Verified |  |
| LL | left2 | Lower Left Ledge | [Mount Fay Lore Room (Peak_10)](#mount-fay-lore-room-peak10) | R | None |  | Verified |  |
| UMR | right1 | Upper Middle Hallway | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | UML | None |  | Verified |  |
| LMR | right2 | Lower Middle Hallway | [Mount Fay Entrance (Peak_01)](#mount-fay-entrance-peak01) | LML | None |  | Verified |  |
| UL | left3 | Upper Left Ledge | [Mount Fay Magnetite Outcropping (Peak_05e)](#mount-fay-magnetite-outcropping-peak05e) | LR | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| IL | Ice Lake | Shakra | Lower Left Ledge | Faydown Cloak OR Clawline OR Sharpdart OR ( Easy Heal Stall AND Cling Grip AND Swim ) OR ( Dash AND Drifters Cloak ) |  | Verified |  |
| IL | Ice Lake | Lower Left Ledge | Shakra | Dash OR Sprint OR Swim OR Drifters Cloak OR Faydown Cloak OR Clawline OR Sharpdart |  | Verified |  |
| PL | Platforms | Shakra | Lower Middle Hallway | Faydown Cloak OR ( Clawline AND ( Dash OR Ledge Grab OR Drifters Cloak ) ) OR Silk Soar |  | Verified |  |
| PL | Platforms | Lower Middle Hallway | Shakra | None |  | Verified |  |
| TS1 | Tall Shaft 1 | Middle Left Ledge | Lower Left Ledge | None |  | Verified |  |
| TS2 | Tall Shaft 2 | Middle Left Ledge | Shakra | None |  | Verified |  |
| TS3 | Tall Shaft 3 | Upper Middle Hallway | Middle Left Ledge | None |  | Verified |  |
| JD1 | Jump Down 1 | Upper Hallway | Upper Middle Hallway | None |  | Verified |  |
| JD1 | Jump Down 1 | Upper Middle Hallway | Upper Hallway | Faydown Cloak |  | Verified |  |
| JD2 | Jump Down 2 | Upper Left Ledge | Upper Middle Hallway | None |  | Verified |  |
| JD2 | Jump Down 2 | Upper Middle Hallway | Upper Left Ledge | Faydown Cloak AND ( Sprint OR Dash OR Drifters Cloak OR Cling Grip OR Ledge Grab OR Sharpdart OR Clawline ) |  | Verified |  |
| GP | Gap | Upper Left Ledge | Upper Hallway | Sprint OR Dash OR Drifters Cloak OR Faydown Cloak OR Clawline OR Sharpdart OR Easy Hunter Crest Pogo OR Easy Beast Crest pogo OR Easy Architect Crest pogo OR ( Ledge Grab AND ( Easy Reaper Crest Pogo OR ( Easy Wanderer Crest Pogo AND Easy needle strike stall ) OR Easy Witch Crest Pogo OR Easy Shaman Crest Pogo ) ) |  | Verified |  |
| GP | Gap | Upper Hallway | Upper Left Ledge | Sprint OR Dash OR Drifters Cloak OR Faydown Cloak OR Clawline OR Sharpdart OR Easy Hunter Crest Pogo OR Easy Beast Crest pogo OR Easy Architect Crest pogo OR ( Ledge Grab AND ( Easy Reaper Crest Pogo OR ( Easy Wanderer Crest Pogo AND Easy needle strike stall ) OR Easy Witch Crest Pogo OR Easy Shaman Crest Pogo ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mount Fay - Map Purchase | Shakra | None |  | Verified | collectible |  |

### Mount Fay Upper Slope (Peak_08)

**Game ID:** Peak_08

**Contributors:** Pyxl

#### Subrooms

- Upper Entrance
- Lower Exit
- Mask Maker Path

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | Lower Exit | [Mount Fay Lower Slope (Peak_05)](#mount-fay-lower-slope-peak05) | C | None |  | Verified |  |
| C | top1 | Mask Maker Path | [Mask Maker Passage (Peak_05d)](#mask-maker-passage-peak05d) | F | Cling Grip OR Scuttlebrace OR Faydown Cloak OR Silk Soar |  | Verified |  |
| R | right1 | Upper Entrance | [FayForn (Peak_08b)](#fayforn-peak08b) | L1 | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BS | Big Slide | Upper Entrance | Lower Exit | None |  | Verified | One Way Slide |
| MM | Mask Maker Path | Lower Exit | Mask Maker Path | Enemy Pogo AND Cling Grip AND Faydown Cloak |  | Verified |  |
| MM | Mask Maker Path | Mask Maker Path | Lower Exit | None |  | Verified |  |

#### Check Locations

No check locations defined.

## Putrified Ducts

### Fleatopia (Aqueduct_05)

**Game ID:** Aqueduct_05

**Contributors:** Pyxl

#### Subrooms

- Entrance
- Fleatopia
- The Herald
- Craftmetal
- Upper Ledge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Entrance | [Putrified Ducts Lower Bridge Room (Aqueduct_03)](#putrified-ducts-lower-bridge-room-aqueduct03) | R | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MP | Maggot Puddle | Entrance | Fleatopia | Swim OR Clawline OR Drifters Cloak OR ( Sprint AND Dash ) OR Sharpdart |  | Verified |  |
| MP | Maggot Puddle | Fleatopia | Entrance | ( Swim AND Cling Grip ) OR ( Faydown cloak AND ( Clawline OR ( Sprint AND Dash ) ) ) |  | Verified |  |
| PL1 | Pale Lake1 | Fleatopia | Craftmetal | Swim AND Faydown Cloak AND ( Cling Grip OR Scuttlebrace ) |  | Verified |  |
| PL1 | Pale Lake1 | Craftmetal | Fleatopia | Swim |  | Verified |  |
| PL2 | Pale Lake2 | Fleatopia | Upper Ledge | Swim AND ( Cling Grip OR Scuttlebrace ) |  | Verified |  |
| PL2 | Pale Lake2 | Upper Ledge | Fleatopia | Clawline OR ( Drifters Cloak AND Sprint AND Faydown Cloak ) |  | Verified |  |
| HS | Hidden Shaft | Upper Ledge | The Herald | Silk Soar |  | Verified |  |
| HS | Hidden Shaft | The Herald | Upper Ledge | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Putrified Ducts - Craft Metal | Craftmetal | None |  | Verified | collectible |  |
| Putrified Ducts - Shell Shard Cache #9 | Upper Ledge | Faydown Cloak OR Clawline OR ( Sprint AND Dash ) OR SharpDart |  | Verified | resource |  |
| Putrified Ducts - Shell Shard Cache #10 | Upper Ledge | Faydown Cloak OR Clawline OR ( Sprint AND Dash ) OR SharpDart |  | Verified | resource |  |
| Putrified Ducts - Shell Shard Cache #11 | Upper Ledge | Faydown Cloak OR Clawline OR ( Sprint AND Dash ) OR SharpDart |  | Verified | resource |  |
| Putrified Ducts - Shell Shard Cache #8 | Fleatopia | Silk Soar |  | Verified | resource |  |
| Putrified Ducts - White Lake Waver Sign | Fleatopia | Needolin |  | Verified | lore | Missable / no check |
| Wish: Passing Of The Age | The Herald | ACT 3 AND Needolin AND ( "Ruined Chapel" In Logic AND "Bone Bottom Town" In Logic AND "Far Fields Skull Room East" In Logic AND "Greymoor_06, Top Area" In Logic AND "Slab First Sinner Antechamber" In Logic AND "Peak_08. Faythorn" In Logic AND "Path Of Pain SilkSong, Top" In Logic ) | TODO |  | event | Need room and subroom name from greymoor and the room and subroom from mount fay |
| Ecstasy of the End Wish Promised | Fleatopia | act 3 AND after THE flea caravan move to fleatopia AND silk soar AND fleas 30 |  | Verified | event | one of two places to accept this wish  spreadsheet flag is vague, so using wiki requirements |
| Ecstasy of the End Wish Granted | Fleatopia | complete Ecstasy of the End Wish Promised AND complete Flea Juggle High Score AND complete Flea Dodge High Score AND after Flea Bounce High Score |  | Verified | event |  |
| Pale Oil | Fleatopia | complete Ecstasy of the End Wish Granted |  | Verified | collectible |  |
| Fleatopia - Tool Pouch | Fleatopia | fleas 22 |  | Verified | collectible |  |
| Egg of Flealia | Fleatopia | fleas 30 |  | Verified | collectible | All fleas |
| Reached Pale Lake | Fleatopia | none |  | Verified | logic-point |  |
| Festival of the Flea | Fleatopia | complete Ecstasy of the End Wish Promised |  | Verified | logic-point |  |
| Flea Juggle High Score | Fleatopia | after Festival of the Flea |  | Verified | event | these probably need movement requirements |
| Flea Dodge High Score | Fleatopia | after Festival of the Flea |  | Verified | event | these probably need movement requirements |
| Flea Bounce High Score | Fleatopia | after Festival of the Flea |  | Verified | event | these probably need movement requirements |
| Seth Joins Festival of the Flea | Fleatopia | after THE Seth Move to Fleatopia  ACT 3  AND Defeat THE Boss Nyleth  AND ( Defeat THE Boss Crust King Khan OR Defeat THE Boss Karmelita OR Defeat THE Boss Clover Dancers )  AND "Greymoor_02" In Logic  AND "Shellwood Flower Pogo Upper Hall" In logic  AND "Grand Bridge" In Logic  AND after Ecstasy of the End Wish Granted | TODO |  | logic-point |  |
| Flea Juggle Beat Seth Score | Fleatopia | after Seth Joins Festival of the Flea |  | Verified | event | these probably need movement requirements |
| Flea Dodge Beat Seth Score | Fleatopia | after Seth Joins Festival of the Flea |  | Verified | event | these probably need movement requirements |
| Flea Bounce Beat Seth Score | Fleatopia | after Seth Joins Festival of the Flea |  | Verified | event | these probably need movement requirements |
| Gaurdians Memento | Fleatopia | complete Flea Juggle Beat Seth Score AND complete Flea Dodge Beat Seth Score AND after Flea Bounce Beat Seth Score |  | Verified | collectible |  |

### Huntress (Room_Huntress)

**Game ID:** Room_Huntress

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Putrified Ducts Connection To Bilewater (Aqueduct_04)](#putrified-ducts-connection-to-bilewater-aqueduct04) | D | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Putrified Ducts - Bench Huntress |  | None |  | Verified | bench |  |
| Longclaw |  | complete Wish: Broodfeast OR complete Wish: Runtfeast |  | Verified | collectible |  |
| Wish: Broodfeast |  | ACT 2  AND ( Seared Organs 15 AND Shredded Organs 35 AND Skewered Organs 10 )  AND ( Searing Damage AND Shredding Damage AND Skewering Damage ) |  | Verified | event | Searing Damage: Flintslate OR Pimpillo OR Wispfire Lantern OR Voltvessels  Shredding Damage: Sawtooth Circlet OR Cogwork Wheel OR Delver's Drill OR Conchcutter OR Beast Crest OR Architect Crest  Skewering Damage: Sting Shard OR Longpin OR Needle Phial*  *Needle Phial need not be included in logic due to losing it when upgrading to Plasmium Phial |
| Wish: Runtfeast |  | ACT 3  AND ( Seared Organs 15 AND Shredded Organs 35 AND Skewered Organs 10 )  AND ( Searing Damage AND Shredding Damage AND Skewering Damage ) |  | Verified | event | Mutually exclusive with Broodfeast. Probably needs to be functionally treated as the same location or split into separate checks and made permanently available. |

### Putrified Ducts Bellway (Bellway_Aqueduct)

**Game ID:** Bellway_Aqueduct

**Contributors:** Pyxl

#### Subrooms

- Bellway
- Vog Camp

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BB | door_fastTravelExit | Bellway | [Bellway Menu](#bellway-menu) | PD | Unlock Bellway Putrified Ducts |  | Verified |  |
| L | left1 | Bellway | [Putrified Ducts Tall Room (Aqueduct_02)](#putrified-ducts-tall-room-aqueduct02) | UR | None |  | Verified |  |
| R | right1 | Vog Camp | [Putrified Ducts Path To Vog (Aqueduct_06)](#putrified-ducts-path-to-vog-aqueduct06) | UL | Dash OR Ledge Grab OR Silk Soar OR Faydown Cloak OR Cling Grip OR easy Shaman Crest pogo OR ( easy Beast Crest pogo AND ( Hard Heal Stall OR easy Needle Strike stall ) ) |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SH | Shaft | Vog Camp | Bellway | Prereq vog floor |  | Verified |  |
| SH | Shaft | Bellway | Vog Camp | Prereq vog floor AND Silk Soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Putrified Ducts - Bellway Bench | Bellway | None |  | Verified | bench |  |
| Flea: Putrified Ducts - Vog | Vog Camp | None |  | Verified | collectible |  |
| Bellway: Putrified Ducts | Bellway | Unlock Bellway Rosary Lock |  | Verified | travel |  |
| Vog Floor | Vog Camp | None |  | Verified | blockade |  |
| Bellway Rosary Lock | Bellway | Rosaries 80 |  | Verified | lock |  |

### Putrified Ducts Connection To Bilewater (Aqueduct_04)

**Game ID:** Aqueduct_04

**Contributors:** Pyxl

#### Subrooms

- Bilewater Entrance
- Putrified Ducts Entrance
- Shell Shard Platform
- Apostate Key Area
- Lower Shell Ledge
- Hut Door
- Hub Area
- Upper Platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Putrified Ducts Entrance | [Putrified Ducts Tall Room (Aqueduct_02)](#putrified-ducts-tall-room-aqueduct02) | LL | None |  | Verified |  |
| D | door1 | Hut Door | [Huntress (Room_Huntress)](#huntress-roomhuntress) | L | None |  | Verified |  |
| F | bot1 | Bilewater Entrance | [Bilewater Upper Bloatroach Tower (Shadow_01)](#bilewater-upper-bloatroach-tower-shadow01) | C | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PDE | Putrified Ducts Entrance | Putrified Ducts Entrance | Hub Area | prereq Breakable wall from Ducts |  | Verified |  |
| PDE | Putrified Ducts Entrance | Hub Area | Putrified Ducts Entrance | prereq Breakable wall from Ducts |  | Verified |  |
| BWE | Bilewater Entrance | Bilewater Entrance | Hub Area | prereq Breakable Floor From Bilewater AND ( Silk Soar OR ( Faydown Cloak AND ( Cling Grip OR Scuttlebrace ) ) ) |  | Verified |  |
| BWE | Bilewater Entrance | Hub Area | Bilewater Entrance | prereq Breakable Floor From Bilewater |  | Verified |  |
| RS | Right Steps | Hub Area | Upper Platform | Silk Soar OR Faydown Cloak OR Cling Grip OR Scuttlebrace OR ( Ledge Grab AND ( easy Shaman crest pogo OR Hard Heal Stall) ) |  | Verified |  |
| RS | Right Steps | Upper Platform | Hub Area | None |  | Verified |  |
| KV | Kidnap Vines | Upper Platform | Shell Shard Platform | None |  | Verified |  |
| KV | Kidnap Vines | Shell Shard Platform | Upper Platform | None |  | Verified |  |
| BG | Gap Slightly too big to jump across | Upper Platform | Apostate Key Area | Dash OR Sprint OR Clawline OR Sharpdart OR easy Beast Crest pogo OR Faydown Cloak OR Drifters Cloak OR Easy Hunter Crest pogo OR easy Architect Crest Pogo OR ( Ledge Grab AND (( easy Needle strike stall AND easy Wanderer Crest pogo ) OR Hard Heal Stall )) |  | Verified |  |
| BG | Gap Slightly too big to jump across | Apostate Key Area | Upper Platform | Dash OR Sprint OR Clawline OR Sharpdart OR easy Beast Crest pogo OR Faydown Cloak OR Drifters Cloak OR easy Hunter Crest pogo OR easy Architect Crest pogo OR ( Ledge Grab AND ( ( easy Needle strike stall AND easy Wanderer Crest pogo ) OR Hard Heal Stall ) ) |  | Verified |  |
| MLL | Maggot Lake Left | Upper Platform | Lower Shell Ledge | Clawline OR ( Drifters Cloak AND ( Ledge Grab OR Dash OR Faydown Cloak OR Easy Beast Crest Pogo OR Sharpdart ) ) OR ( Swim AND ( Ledge Grab OR Dash OR Faydown Cloak OR Cling Grip OR easy Shaman Crest pogo OR ( Hard Beast Crest pogo AND Hard Heal Stall ) ) ) OR ( Sprint AND Dash ) OR Sharpdart |  | Verified |  |
| MLL | Maggot Lake Left | Lower Shell Ledge | Upper Platform | Cling Grip AND Clawline AND Faydown Cloak |  | Verified |  |
| MLR | Maggot Lake Right | Upper Platform | Hut Door | Drifters Cloak OR Faydown Cloak OR Swim OR Clawline OR ( Sprint AND Dash ) OR Sharpdart |  | Verified |  |
| MLC | Maggot Lake Centre | Lower Shell Ledge | Hut Door | Clawline OR Swim OR ( Faydown Cloak AND Drifters Cloak ) OR ( Sprint AND Drifters Cloak ) |  | Verified |  |
| MLC | Maggot Lake Centre | Hut Door | Lower Shell Ledge | Clawline OR ( Swim AND ( Ledge Grab OR Dash OR Faydown Cloak OR Cling Grip OR easy Shaman Crest pogo OR ( easy Beast Crest pogo AND Hard Heal Stall ) ) )  OR ( Faydown Cloak AND Drifters Cloak ) OR ( Sprint AND Drifters Cloak ) |  | Verified |  |
| HH | Hut to HUB | Hut Door | Hub Area | prereq Breakable Wall From Hut Door AND ( ( Faydown Cloak AND ( Cling Grip OR Scuttlebrace ) ) OR ( Silk Soar AND ( Sprint OR Dash OR Clawline OR Sharpdart OR easy Beast Crest pogo OR Drifters Cloak OR Faydown Cloak ) ) ) |  | Verified |  |
| HH | Hut to HUB | Hub Area | Hut Door | prereq Breakable Wall From Hut Door AND ( Swim OR Sprint OR Dash OR Drifters Cloak OR Faydown Cloak OR Clawline OR Sharpdart OR easy Hunter Crest pogo OR easy Beast Crest pogo OR easy Architect Crest pogo OR ( easy Needle strike stall AND easy Wanderer Crest pogo AND Ledge Grab ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Breakable Wall From Ducts | Putrified Ducts Entrance | None |  | Verified | blockade |  |
| Breakable Floor From Bilewater | Bilewater Entrance | None |  | Verified | blockade |  |
| Breakable Wall From Hut Door | Hut Door | None |  | Verified | blockade |  |
| Putrified Ducts - Shell Shard Cache #3 | Lower Shell Ledge | None |  | Verified | resource |  |
| Putrified Ducts - Shell Shard Cache #4 | Lower Shell Ledge | None |  | Verified | resource |  |
| Putrified Ducts - Shell Shard Cache #5 | Lower Shell Ledge | None |  | Verified | resource |  |
| Putrified Ducts - Shell Shard Cache #6 | Shell Shard Platform | None |  | Verified | resource |  |
| Putrified Ducts - Shell Shard Cache #7 | Shell Shard Platform | None |  | Verified | resource |  |
| Key of Apostate | Apostate Key Area | None |  | Verified | collectible |  |

### Putrified Ducts Entrance (Aqueduct_01)

**Game ID:** Aqueduct_01

**Contributors:** Pyxl

#### Subrooms

- Entrance
- Left Platform
- Centre Platform
- Shell Shards bridge
- Exit
- Rosary String Ledge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Exit | [Putrified Ducts Tall Room (Aqueduct_02)](#putrified-ducts-tall-room-aqueduct02) | UL | None |  | Verified |  |
| L | left1 | Entrance | [Shopkeeper hides (Arborium_11)](#shopkeeper-hides-arborium11) | R | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EC | Entrance Cave | Entrance | Left Platform | Faydown Cloak AND ( CLing Grip OR Scuttlebrace ) |  | Verified |  |
| EC | Entrance Cave | Left Platform | Entrance | ( Faydown Cloak AND Cling Grip ) OR ( Silk Soar AND ( Dash OR Clawline OR Sharpdart OR Faydown Cloak OR Drifters Cloak ) ) |  | Verified |  |
| LBB | Left Broken Bridge | Left Platform | Centre Platform | Dash OR Faydown Cloak OR ( ( Cling Grip OR Ledge Grab ) AND ( Sprint OR Clawline OR SharpDart ) ) |  | Verified |  |
| LBB | Left Broken Bridge | Centre Platform | Left Platform | Faydown Cloak OR Clawline OR Sprint OR ( Drifters Cloak AND Easy enemy pogo ) OR Silk Soar OR ( Cling Grip AND Dash ) |  | Verified |  |
| UB | Under The Bridge | Centre Platform | Shell Shards bridge | ( Easy enemy pogo AND ( Ledge Grab OR Drifters Cloak OR easy Hunter Crest pogo OR easy Beast Crest pogo OR easy Architect Crest pogo OR  easy Shaman Crest pogo OR Clawline OR  Dash OR Sharpdart ) ) OR Faydown Cloak OR Cling Grip OR Scuttlebrace |  | Verified |  |
| UB | Under The Bridge | Shell Shards bridge | Centre Platform | ( Faydown Cloak AND ( Cling Grip OR Clawline OR Sprint OR Scuttlebrace OR Drifters Cloak OR Sharpdart ) ) |  | Verified |  |
| OB | Over The Bridge | Centre Platform | Exit | Clawline OR Drifters Cloak OR Silk Soar OR ( Faydown Cloak AND ( Cling Grip OR Dash OR Sprint ) ) OR ( Swim AND Dash AND Cling Grip ) |  | Verified |  |
| OB | Over The Bridge | Exit | Centre Platform | Dash OR Faydown Cloak OR Run OR Drifters Cloak OR Cling Grip OR Silk Soar OR Clawline OR Sharpdart |  | Verified |  |
| UE | Under The Exit | Exit | Rosary String Ledge | None |  | Verified |  |
| UE | Under The Exit | Rosary String Ledge | Exit | Faydown Cloak OR Silk Soar OR ( ( Dash OR Cling Grip ) AND ( Clawline OR Drifters Cloak OR Sharpdart OR Sprint ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Putrified Ducts - Shell Shard Cache #1 | Shell Shards bridge | None |  | Verified | resource | Merge Map icons on map |
| Putrified Ducts - Shell Shard Cache #2 | Shell Shards bridge | None |  | Verified | resource | Merge Map icons on map |
| Putrified Ducts - Frayed Rosary String | Rosary String Ledge | None |  | Verified | collectible |  |

### Putrified Ducts Lower Bridge Room (Aqueduct_03)

**Game ID:** Aqueduct_03

**Contributors:** Pyxl

#### Subrooms

- Left Exit
- Right Exit
- Ceiling Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right Exit | [Fleatopia (Aqueduct_05)](#fleatopia-aqueduct05) | L | None |  | Verified |  |
| L | left1 | Left Exit | [Putrified Ducts Tall Room (Aqueduct_02)](#putrified-ducts-tall-room-aqueduct02) | LR | None |  | Verified |  |
| C | top1 | Ceiling Exit | [Putrified Ducts Path To Vog (Aqueduct_06)](#putrified-ducts-path-to-vog-aqueduct06) | F | Faydown Cloak OR Cling Grip OR Silk Soar OR Scuttlebrace |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AB | Across The Bridges | Left Exit | Right Exit | ( Cling Grip AND ( Clawline OR Faydown Cloak ) ) OR ( Silk Soar AND ( Drifters Cloak OR Clawline ) ) |  | Verified |  |
| AB | Across The Bridges | Right Exit | Left Exit | ( Cling Grip AND Clawline )  OR ( Silk Soar AND ( Drifters Cloak OR Clawline ) ) |  | Verified |  |
| TC | Ceiling Tunnel | Right Exit | Ceiling Exit | ( Silk Soar AND ( Faydown Cloak OR Sprint OR Dash OR Cling Grip OR Clawline OR Drifters Cloak OR Faydown Cloak OR Sharpdart ) ) OR ( Faydown Cloak AND ( Dash OR Clawline OR Sharpdart OR easy Beast Crest pogo OR Drifters Cloak ) ) OR ( Cling Grip AND Clawline ) |  | Verified |  |
| TC | Ceiling Tunnel | Ceiling Exit | Right Exit | Sprint OR Clawline OR Faydown Cloak OR ( Silk Soar AND ( Dash OR Drifters Cloak OR Cling Grip ) ) |  | Verified |  |
| SS | Silk Soar Up | Left Exit | Ceiling Exit | Silk Soar AND ( Drifters cloak OR Faydown Cloak OR Clawline ) |  | Verified |  |
| SS | Silk Soar Up | Ceiling Exit | Left Exit | Drifters Cloak OR Clawline OR ( Swim AND Faydown Cloak ) OR ( Silk Soar AND ( Dash OR Sharpdart ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Breakable Wall | Right Exit | Faydown Cloak OR ( Cling Grip AND Clawline ) OR ( Silk Soar AND ( Drifters Cloak OR Dash OR Cling Grip OR Clawline OR Sharpdart OR Sprint ) ) |  | Verified | blockade |  |

### Putrified Ducts Map Room (Aqueduct_07)

**Game ID:** Aqueduct_07

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Putrified Ducts Tall Room (Aqueduct_02)](#putrified-ducts-tall-room-aqueduct02) | ML | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Putrified Ducts - thread memory Map Room |  | Needolin |  | Verified | lore |  |
| Putrified Ducts - Map Pickup |  | None |  | Verified | collectible |  |

### Putrified Ducts Path To Vog (Aqueduct_06)

**Game ID:** Aqueduct_06

**Contributors:** Pyxl

#### Subrooms

- Main
- Camp
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | Main | [Putrified Ducts Lower Bridge Room (Aqueduct_03)](#putrified-ducts-lower-bridge-room-aqueduct03) | C | None |  | Verified |  |
| UL | left1 | Top | [Putrified Ducts Bellway (Bellway_Aqueduct)](#putrified-ducts-bellway-bellwayaqueduct) | R | None |  | Verified |  |
| LL | left2 | Main | [Putrified Ducts Rosary Room (Aqueduct_08)](#putrified-ducts-rosary-room-aqueduct08) | R | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VA | Vine Acsent | Main | Top | ( Clawline AND ( Cling Grip OR ( Drifters Cloak AND ( Faydown Cloak OR Dash ) ) )  ) |  | Verified |  |
| VA | Vine Acsent | Top | Main | Clawline AND Faydown Cloak |  | Verified |  |
| TC | Thorn Crossing | Main | Camp | ( Faydown Cloak AND ( easy Hunter Crest pogo OR Swim OR easy Reaper Crest pogo OR easy Beast Crest pogo OR easy Architect Crest pogo OR Sprint OR Dash OR ( Ledge Grab AND Hard Heal Stall) ) ) OR Sharpdart OR Clawline OR Drifters Cloak OR ( Sprint AND Dash ) |  | Verified |  |
| TC | Thorn Crossing | Camp | Main | ( Faydown Cloak AND ( easy Hunter Crest pogo OR Swim OR easy Reaper Crest pogo OR easy Beast Crest pogo OR easy Architect Crest pogo OR Sprint OR Dash OR ( Ledge Grab AND Hard heal stall ) ) ) OR Sharpdart OR Clawline OR Drifters Cloak OR ( Sprint AND Dash ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| thread_memory | Camp | Needolin |  | Verified | lore | dont think we doing these |
| Wreath OF Purity | Camp | None |  | Verified | collectible |  |

### Putrified Ducts Rosary Room (Aqueduct_08)

**Game ID:** Aqueduct_08

**Contributors:** Pyxl

#### Subrooms

- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Putrified Ducts Tall Room (Aqueduct_02)](#putrified-ducts-tall-room-aqueduct02) | MR | prereq Breakable Sewer Grate 2 |  | Verified |  |
| R | right1 | Right | [Putrified Ducts Path To Vog (Aqueduct_06)](#putrified-ducts-path-to-vog-aqueduct06) | LL | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MP | Maggot Puddle | Left | Right | Swim OR Sprint OR Dash OR Faydown Cloak OR Drifters Cloak OR Clawline OR Sharpdart OR easy Beast Crest pogo |  | Verified |  |
| MP | Maggot Puddle | Right | Left | Swim OR Sprint OR Dash OR Faydown Cloak OR Drifters Cloak OR Clawline OR Sharpdart OR easy Beast Crest pogo |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Putrified Ducts - Rosary Cache #1 | Right | None |  | Verified | resource |  |
| Putrified Ducts - Rosary Cache #2 | Right | None |  | Verified | resource |  |
| Putrified Ducts - Rosary Cache #3 | Right | None |  | Verified | resource |  |
| Breakable Sewer Grate 2 | Left | None |  | Verified | blockade |  |

### Putrified Ducts Tall Room (Aqueduct_02)

**Game ID:** Aqueduct_02

**Contributors:** Pyxl

#### Subrooms

- Top Left
- Bellway Door
- Middle Platform
- Lower Sewage Tunnel

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | Top Left | [Putrified Ducts Entrance (Aqueduct_01)](#putrified-ducts-entrance-aqueduct01) | R | None |  | Verified |  |
| UR | right2 | Bellway Door | [Putrified Ducts Bellway (Bellway_Aqueduct)](#putrified-ducts-bellway-bellwayaqueduct) | L | None |  | Verified |  |
| ML | left3 | Middle Platform | [Putrified Ducts Map Room (Aqueduct_07)](#putrified-ducts-map-room-aqueduct07) | R | None |  | Verified |  |
| MR | right3 | Middle Platform | [Putrified Ducts Rosary Room (Aqueduct_08)](#putrified-ducts-rosary-room-aqueduct08) | L | Prereq Breakable Sewer Grate 2 IN Putrified Ducts Rosary Room |  | Verified |  |
| LL | left2 | Lower Sewage Tunnel | [Putrified Ducts Connection To Bilewater (Aqueduct_04)](#putrified-ducts-connection-to-bilewater-aqueduct04) | R | Prereq Breakable Sewer Grate |  | Verified |  |
| LR | right1 | Lower Sewage Tunnel | [Putrified Ducts Lower Bridge Room (Aqueduct_03)](#putrified-ducts-lower-bridge-room-aqueduct03) | L | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| UG | Upper Gap | Top Left | Bellway Door | Ledge Grab OR Dash OR Cling Grip OR Drifters Cloak OR Faydown Cloak OR Silk Soar OR Clawline OR Sharpdart OR Scuttlebrace OR easy Hunter Crest pogo OR easy Reaper Crest pogo OR easy Beast Crest pogo OR easy Witch Crest pogo OR easy Architect Crest pogo OR easy Shaman Crest pogo OR ( easy Needle Strike stall AND easy Wanderer Crest pogo ) |  | Verified |  |
| UG | Upper Gap | Bellway Door | Top Left | Faydown Cloak OR Cling Grip OR Silk Soar OR Scuttlebrace |  | Verified |  |
| TS | The Shaft | Top Left | Middle Platform | None |  | Verified |  |
| TS | The Shaft | Middle Platform | Top Left | Cling Grip OR Silk Soar OR Faydown CLoak OR ( Scuttlebrace AND ( Clawline OR Ledge Grab ) ) |  | Verified |  |
| TS2 | The Shaft 2 | Bellway Door | Middle Platform | None |  | Verified |  |
| TS2 | The Shaft 2 | Middle Platform | Bellway Door | Cling Grip OR Silk Soar OR Faydown CLoak OR ( Scuttlebrace AND ( Clawline OR Ledge Grab ) ) |  | Verified |  |
| TT | The Tunnel | Middle Platform | Lower Sewage Tunnel | None |  | Verified |  |
| TT | The Tunnel | Lower Sewage Tunnel | Middle Platform | Silk Soar OR ( Faydown Cloak AND ( Cling Grip OR Scuttlebrace ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Breakable Sewer Grate | Lower Sewage Tunnel | None |  | Verified | blockade |  |

## The Cradle

### ACT3 Connection To GMS (Cradle_01_Destroyed)

**Game ID:** Cradle_01_Destroyed

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 |  | [ACT3 Lace2 Arena (Song_Tower_Destroyed)](#act3-lace2-arena-songtowerdestroyed) | C | ~None |  | Verified |  |
| C | top1 |  | [ACT3 GMS Arena (Cradle_03_Destroyed)](#act3-gms-arena-cradle03destroyed) | F | ( Cling Grip OR Scuttlebrace ) AND ( Silk Soar OR Faydown Cloak ) |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### ACT3 GMS Arena (Cradle_03_Destroyed)

**Game ID:** Cradle_03_Destroyed

**Contributors:** Pyxl

#### Subrooms

- Bottom
- Bridge
- Door To Surface

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | Bottom | [ACT3 Connection To GMS (Cradle_01_Destroyed)](#act3-connection-to-gms-cradle01destroyed) | C | None |  | Verified |  |
| D | door1 | Door To Surface | [Cradle Path Of Pain First Room (Cradle_Destroyed_Challenge_02)](#cradle-path-of-pain-first-room-cradledestroyedchallenge02) | L | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CB | Climb Bridge | Bottom | Bridge | Silk Soar OR ( Cling Grip AND Faydown Cloak AND ( Clawline OR Dash OR Drifters Cloak ) ) |  | Verified |  |
| CB | Climb Bridge | Bridge | Bottom | None |  | Verified |  |
| SS | Surface Shaft | Bridge | Door To Surface | Silk Soar |  | Verified |  |
| SS | Surface Shaft | Door To Surface | Bridge | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pale Nails | Bridge | None |  | Verified | collectible |  |

### ACT3 Lace2 Arena (Song_Tower_Destroyed)

**Game ID:** Song_Tower_Destroyed

**Contributors:** Pyxl

#### Subrooms

- Surface Path
- Flower Bed

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | Flower Bed | [Cogwork Core Architect's Melody (Act 3) (Cog_09_Destroyed)](#cogwork-core-architects-melody-act-3-cog09destroyed) | T | None |  | Verified |  |
| C | top1 | Surface Path | [ACT3 Connection To GMS (Cradle_01_Destroyed)](#act3-connection-to-gms-cradle01destroyed) | F | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| UA | Up And Away | Flower Bed | Surface Path | Silk Soar |  | Verified |  |
| UA | Up And Away | Surface Path | Flower Bed | None |  | Verified |  |

#### Check Locations

No check locations defined.

### ACT2 GMS Arena (Cradle_03)

**Game ID:** Cradle_03

**Contributors:** Pyxl

#### Subrooms

- Bottom
- Shell Shard Ledge
- Arena

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left2 | Bottom | [Act2 Cradle Left Shaft (Cradle_02)](#act2-cradle-left-shaft-cradle02) | UR | None |  | Verified | None |
| R | right2 | Bottom | [Terminus Ventrica (Tube_Hub)](#terminus-ventrica-tubehub) | UL | None |  | Verified | None |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| P1 | Platforms 1 | Bottom | Shell Shard Ledge | Silk Soar OR ( Cling Grip AND ( Dash OR Clawline OR Faydown Cloak OR Sharpdart ) ) |  | Verified |  |
| P1 | Platforms 1 | Shell Shard Ledge | Bottom | None |  | Verified |  |
| P2 | Platforms 2 | Shell Shard Ledge | Arena | Silk Soar OR ( Cling Grip AND ( Dash OR Clawline OR Sharpdart ) ) OR Faydown Cloak |  | Verified |  |
| P2 | Platforms 2 | Arena | Shell Shard Ledge | None |  | Verified |  |
| P3 | Platforms 3 | Bottom | Arena | Silk Soar OR ( Cling Grip AND ( Dash OR Clawline OR Faydown Cloak OR Sharpdart ) ) |  | Verified |  |
| P3 | Platforms 3 | Arena | Bottom | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Cradle #1 | Shell Shard Ledge | None |  | Verified | resource |  |
| Boss: Grand Mother Silk | Arena | None |  | Verified | boss |  |

### Act2 Cradle Connector Hallway (Cradle_01)

**Game ID:** Cradle_01

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Act2 Cradle Left Shaft (Cradle_02)](#act2-cradle-left-shaft-cradle02) | LR | None |  | Verified |  |
| R | right1 |  | [Terminus Ventrica (Tube_Hub)](#terminus-ventrica-tubehub) | ML | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Act2 Cradle Left Shaft (Cradle_02)

**Game ID:** Cradle_02

**Contributors:** Pyxl

#### Subrooms

- Map Ledge
- Weaver Lore Ledge
- Lower Right Ledge
- Upper Right Ledge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Upper Right Ledge | [ACT2 GMS Arena (Cradle_03)](#act2-gms-arena-cradle03) | L | None |  | Verified |  |
| L | left2 | Weaver Lore Ledge | [Weaver Jail Lore Room (Cradle_02b)](#weaver-jail-lore-room-cradle02b) | R | None |  | Verified |  |
| LR | right2 | Lower Right Ledge | [Act2 Cradle Connector Hallway (Cradle_01)](#act2-cradle-connector-hallway-cradle01) | L | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S1 | Lower Shaft | Weaver Lore Ledge | Lower Right Ledge | Faydown Cloak OR Cling Grip OR Scuttlebrace |  | Verified |  |
| S1 | Lower Shaft | Lower Right Ledge | Weaver Lore Ledge | None |  | Verified |  |
| S2 | Central Shaft | Lower Right Ledge | Map Ledge | Cling Grip OR Scuttlebrace |  | Verified |  |
| S2 | Central Shaft | Map Ledge | Lower Right Ledge | None |  | Verified |  |
| S3 | Upper Shaft | Map Ledge | Upper Right Ledge | Cling Grip OR Scuttlebrace |  | Verified |  |
| S3 | Upper Shaft | Upper Right Ledge | Map Ledge | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map: Cradle | Map Ledge | None |  | Verified | collectible |  |

### Lace 2 Fight (Song_Tower_01)

**Game ID:** Song_Tower_01

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door_cinematicEnd |  | [Cog Dancers (Cog_Dancers)](#cog-dancers-cogdancers) | E | Prereq Boss: Lace 2 |  | Verified | You know im not actually sure which of these doors is the elevator will need to double check once images are in |
| R | right1 |  | [Terminus Ventrica (Tube_Hub)](#terminus-ventrica-tubehub) | LL | Prereq Boss: Lace 2 |  | Verified |  |
| DR | door_cutsceneEndLaceTower |  | [Lace 2 Fight (Song_Tower_01)](#lace-2-fight-songtower01) | DR | None |  | Verified | The silk heart room, think its been disabled in mod |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Lace 2 |  | needle upgrades 2 |  | Verified | boss |  |
| Silk Heart: Lace 2 |  | prereq Boss: Lace 2 |  | Verified | collectible |  |

#### Notes

No map image for this

### Terminus Ventrica (Tube_Hub)

**Game ID:** Tube_Hub

**Contributors:** Pyxl

#### Subrooms

- Ventricas
- Silkeater Room
- Lower Shaft
- Central Shaft
- Upper Shaft

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | left1 | Lower Shaft | [Lace 2 Fight (Song_Tower_01)](#lace-2-fight-songtower01) | R | ACT 2 |  | Verified |  |
| ML | left4 | Central Shaft | [Act2 Cradle Connector Hallway (Cradle_01)](#act2-cradle-connector-hallway-cradle01) | R | ACT 2 |  | Verified |  |
| UL | left3 | Upper Shaft | [ACT2 GMS Arena (Cradle_03)](#act2-gms-arena-cradle03) | R | ACT 2 |  | Verified |  |
| V | door_tubeEnter | Ventricas | [Ventrica Menu](#ventrica-menu) | T | unlock ventrica terminus |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SES | Silk Eater Shaft | Silkeater Room | Ventricas | prereq Breakable floor terminus AND ( Cling Grip OR Scuttlebrace ) |  | Verified | Potentially possible with silk soar if you come during act 3 |
| SES | Silk Eater Shaft | Ventricas | Silkeater Room | prereq Breakable floor terminus |  | Verified |  |
| TS1 | Tall Shaft1 | Ventricas | Lower Shaft | prereq Terminus OWW |  | Verified |  |
| TS1 | Tall Shaft1 | Lower Shaft | Ventricas | prereq Terminus OWW AND ( Scuttlebrace OR Cling Grip OR Silk Soar ) |  | Verified |  |
| TS2 | Tall Shaft2 | Lower Shaft | Central Shaft | Scuttlebrace OR Cling Grip OR Silk Soar |  | Verified |  |
| TS2 | Tall Shaft2 | Central Shaft | Lower Shaft | None |  | Verified |  |
| TS3 | Tall Shaft3 | Central Shaft | Upper Shaft | prereq Terminus Upper Shaft AND ( Scuttlebrace OR Cling Grip OR Silk Soar ) |  | Verified |  |
| TS3 | Tall Shaft3 | Upper Shaft | Central Shaft | prereq Terminus Upper Shaft |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silkeate: Terminus | Silkeater Room | None |  | Verified | collectible |  |
| Breakable Floor terminus | Ventricas | None |  | Verified | blockade |  |
| Terminus OWW | Lower Shaft | None |  | Verified | blockade |  |
| Terminus Upper Shaft | Upper Shaft | None |  | Verified | switch |  |
| Ventrica Terminus | Ventricas | None |  | Verified | travel | Always owned |

#### Notes

I entered this during act 3 and got the same scene dump, dont believe they count as differant rooms also cannot find the area on the map

### Weaver Jail Lore Room (Cradle_02b)

**Game ID:** Cradle_02b

**Contributors:** Pyxl

#### Subrooms

- Bottom
- Loreplatform1
- Loreplatform2
- Loreplatform3
- Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Exit | [Act2 Cradle Left Shaft (Cradle_02)](#act2-cradle-left-shaft-cradle02) | L | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| B1 | Bottom To Platform 1 | Bottom | Loreplatform1 | Silk Soar OR Faydown Cloak OR ( Cling Grip AND Clawline ) |  | Verified |  |
| B1 | Bottom To Platform 1 | Loreplatform1 | Bottom | None |  | Verified |  |
| P12 | Platform 1 To Platform 2 | Loreplatform1 | Loreplatform2 | Silk Soar OR Faydown Cloak OR ( Cling Grip AND Clawline ) |  | Verified |  |
| P12 | Platform 1 To Platform 2 | Loreplatform2 | Loreplatform1 | None |  | Verified |  |
| P23 | Platform 2 To Platform 3 | Loreplatform2 | Loreplatform3 | Silk Soar OR Faydown Cloak OR ( Cling Grip AND Clawline ) |  | Verified |  |
| P23 | Platform 2 To Platform 3 | Loreplatform3 | Loreplatform2 | None |  | Verified |  |
| P3L | Platform 3 To Exit | Loreplatform3 | Exit | Clawline OR ( Faydown Cloak AND Drifters Cloak ) |  | Verified |  |
| P3L | Platform 3 To Exit | Exit | Loreplatform3 | Faydown Cloak OR Drifters Cloak OR Clawline OR Sprint OR Dash |  | Verified |  |
| LP2 | Exit To Platform 2 | Exit | Loreplatform2 | None |  | Verified |  |
| LP2 | Exit To Platform 2 | Loreplatform2 | Exit | Cling Grip OR Silk Soar OR Scuttlebrace OR ( Faydown Cloak AND ( Ledge grab OR easy Shaman Crest pogo OR Clawline ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lore: Cradle #1 | Bottom | None |  | Verified | lore |  |
| Lore: Cradle #2 | Loreplatform1 | None |  | Verified | lore |  |
| Lore: Cradle #3 | Loreplatform3 | None |  | Verified | lore |  |

### Cradle Path Of Pain First Room (Cradle_Destroyed_Challenge_02)

**Game ID:** Cradle_Destroyed_Challenge_02

**Contributors:** Pyxl

#### Subrooms

- Start
- End

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | End | [Path of Pain Bench (Cradle_Destroyed_Challenge_Bench)](#path-of-pain-bench-cradledestroyedchallengebench) | F | Cling Grip OR Silk Soar OR Scuttlebrace |  | Verified |  |
| L | left1 | Start | [ACT3 GMS Arena (Cradle_03_Destroyed)](#act3-gms-arena-cradle03destroyed) | D | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Start | End | Faydown Cloak AND Cling Grip AND ( Clawline OR Dash ) |  | Verified |  |
| WR | Whole Room | End | Start | Faydown Cloak OR Drifters Cloak OR Clawline OR Dash |  | Verified |  |

#### Check Locations

No check locations defined.

#### Notes

Needs a map link

### Path of Pain Bench (Cradle_Destroyed_Challenge_Bench)

**Game ID:** Cradle_Destroyed_Challenge_Bench

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Path Of Pain Silksong (Cradle_Destroyed_Challenge_01)](#path-of-pain-silksong-cradledestroyedchallenge01) | L | None |  | Verified |  |
| F | bot1 |  | [Cradle Path Of Pain First Room (Cradle_Destroyed_Challenge_02)](#cradle-path-of-pain-first-room-cradledestroyedchallenge02) | C | none |  | Verified |  |
| D | door1 |  | [The Surface (Abandoned_town)](#the-surface-abandonedtown) | D | Silk Soar OR ( Faydown Cloak AND Cling grip ) |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Path of Pain Bench |  | None |  | Verified | bench |  |

#### Notes

Needs a map link

### Path Of Pain Silksong (Cradle_Destroyed_Challenge_01)

**Game ID:** Cradle_Destroyed_Challenge_01

**Contributors:** Pyxl

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | Top | [The Surface (Abandoned_town)](#the-surface-abandonedtown) | F | Cling Grip AND Clawline AND Faydown Cloak |  | Verified |  |
| L | left1 | Bottom | [Path of Pain Bench (Cradle_Destroyed_Challenge_Bench)](#path-of-pain-bench-cradledestroyedchallengebench) | R | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

No map link for this

### The Surface (Abandoned_town)

**Game ID:** Abandoned_town

**Contributors:** Pyxl

#### Subrooms

- Hole
- Door
- Nameless Town

- **Nameless Town:**  Right Side of room cant place box

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 | Door | [Path of Pain Bench (Cradle_Destroyed_Challenge_Bench)](#path-of-pain-bench-cradledestroyedchallengebench) | D | None |  | Verified |  |
| F | bot1 | Hole | [Path Of Pain Silksong (Cradle_Destroyed_Challenge_01)](#path-of-pain-silksong-cradledestroyedchallenge01) | C | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SL | Surface Left | Hole | Door | None |  | Verified |  |
| SL | Surface Left | Door | Hole | Faydown Cloak OR Cling Grip OR Ledge Grab OR Scuttlebrace |  | Verified |  |
| SR | Surface Right | Door | Nameless Town | None |  | Verified |  |
| SR | Surface Right | Nameless Town | Door | None |  | Verified |  |
| HN | Hole to Nameless Town | Hole | Nameless Town | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Surface Memento | Nameless Town | None |  | Verified | collectible |  |

#### Notes

No map link for this

## The Abyss

### Abyss Bottom Left Lore Room (Abyss_06)

**Game ID:** Abyss_06

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Abyss Tall Room (Abyss_01)](#abyss-tall-room-abyss01) | L | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lore: Abyss #3 |  | ( Faydown Cloak AND ( easy Reaper Crest pogo OR Cling Grip ) ) OR ( Silk Soar AND ( ( ( Proficient Movement AND spike pogo ) AND Ledge grab ) OR Cling Grip OR Clawline OR Scuttlebrace )  ) |  | Verified | lore |  |

### Abyss Collapsing Hallway (Abyss_07)

**Game ID:** Abyss_07

**Contributors:** Pyxl

#### Subrooms

- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Abyss Tall Room (Abyss_01)](#abyss-tall-room-abyss01) | LR | None |  | Verified |  |
| R | right1 | Right | [Abyss Final Bench (Abyss_12)](#abyss-final-bench-abyss12) | L | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CR | Crossing | Left | Right | have Everbloom OR Clawline OR ( ( Sprint OR Dash OR Sharpdart ) AND Faydown Cloak AND Drifters Cloak ) |  | Verified |  |
| CR | Crossing | Right | Left | have Everbloom OR Clawline OR ( ( Sprint OR Dash OR Sharpdart ) AND Faydown Cloak AND Drifters Cloak ) |  | Verified |  |

#### Check Locations

No check locations defined.

### Abyss Diving Bell Broken (Room_Diving_Bell_Abyss)

**Game ID:** Room_Diving_Bell_Abyss

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Abyss Landing Zone (Abyss_03)](#abyss-landing-zone-abyss03) | D1 | None |  | Verified |  |
| D | door_wakeOnGround |  | [Abyss Diving Bell Broken (Room_Diving_Bell_Abyss)](#abyss-diving-bell-broken-roomdivingbellabyss) | D | None |  | Verified | One Way from deep docks |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Abyss Diving Bell Fixed (Room_Diving_Bell_Abyss_Fixed)

**Game ID:** Room_Diving_Bell_Abyss_Fixed

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Abyss Landing Zone (Abyss_03)](#abyss-landing-zone-abyss03) | D2 | None |  | Verified |  |
| B | door_cinematicEnd |  | [Deep Docks Diving Bell Interior (Room_Diving_Bell)](#deep-docks-diving-bell-interior-roomdivingbell) | D | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Abyss Drop Down From Escape Hall (Abyss_11)

**Game ID:** Abyss_11

**Contributors:** Pyxl

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Top | [Abyss Escape Hallway (Abyss_13)](#abyss-escape-hallway-abyss13) | L | None |  | Verified |  |
| F | bot1 | Bottom | [Abyss Upper Big Room (Abyss_02b)](#abyss-upper-big-room-abyss02b) | C | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SH | Shaft | Top | Bottom | None |  | Verified | Spike Pogo |
| SH | Shaft | Bottom | Top | Silk Soar AND ( Cling Grip OR ( easy Reaper Crest pogo AND Ledge Grab ) OR Scuttlebrace ) |  | Verified |  |

#### Check Locations

No check locations defined.

### Abyss Escape (Abyss_09)

**Game ID:** Abyss_09

**Contributors:** Pyxl

#### Subrooms

- Start
- End

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | End | [Deep Docks Church (Dock_06_Church)](#deep-docks-church-dock06church) | F | ( Faydown Cloak AND ( Cling grip OR Scuttlebrace ) ) OR Silk Soar |  | Verified |  |
| F | bot1 | Start | [Abyss Escape Hallway (Abyss_13)](#abyss-escape-hallway-abyss13) | C | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TE | The Escape | Start | End | ( Silk Soar AND Drifters Cloak AND Cling Grip AND Faydown Cloak AND ( ( Proficient Movement AND spike pogo ) OR Clawline ) ) |  | Verified | One way |

#### Check Locations

No check locations defined.

### Abyss Escape Hallway (Abyss_13)

**Game ID:** Abyss_13

**Contributors:** Pyxl

#### Subrooms

- Escape Ledge
- Left Exit
- Right Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Exit | [Abyss Drop Down From Escape Hall (Abyss_11)](#abyss-drop-down-from-escape-hall-abyss11) | R | None |  | Verified |  |
| R | right1 | Right Exit | [Abyss Landing Zone (Abyss_03)](#abyss-landing-zone-abyss03) | UL | None |  | Verified |  |
| C | top1 | Escape Ledge | [Abyss Escape (Abyss_09)](#abyss-escape-abyss09) | F | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Right Exit | Left Exit | Clawline OR ( Drifters Cloak AND Faydown Cloak AND ( easy Beast Crest pogo OR medium Reaper Crest pogo OR medium Wanderer Crest pogo OR medium Witch Crest pogo OR Medium Shaman Crest pogo OR ( ( easy Hunter Crest pogo OR easy Architect Crest pogo ) AND ( Dash OR Sharpdart ) ) ) ) |  | Verified |  |
| WR | Whole Room | Left Exit | Right Exit | Clawline OR ( Drifters Cloak AND Faydown Cloak AND ( easy Beast Crest pogo OR easy Reaper Crest pogo OR easy Wanderer Crest pogo OR medium Witch Crest pogo OR medium Shaman Crest pogo OR ( ( easy Hunter Crest pogo OR easy Architect Crest pogo ) AND ( Dash OR Sharpdart ) ) ) ) |  | Verified |  |
| EL | Escape Ledge | Left Exit | Escape Ledge | Silk Soar OR Cling Grip |  | Verified |  |
| EL | Escape Ledge | Escape Ledge | Left Exit | None |  | Verified |  |

#### Check Locations

No check locations defined.

### Abyss Final Bench (Abyss_12)

**Game ID:** Abyss_12

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right2 |  | [Abyss Lower Big Room (Abyss_05)](#abyss-lower-big-room-abyss05) | L | None |  | Verified |  |
| L | left1 |  | [Abyss Collapsing Hallway (Abyss_07)](#abyss-collapsing-hallway-abyss07) | R | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map: Abyss |  | Silk Soar OR Cling Grip OR ( Faydown Cloak AND Scuttlebrace ) |  | Verified | collectible |  |
| Bench: Final Bench |  | None |  | Verified | bench |  |

### Abyss Hallway To Upper Big Room (Abyss_02)

**Game ID:** Abyss_02

**Contributors:** Pyxl

#### Subrooms

- Left Exit
- Right Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Exit | [Abyss Upper Big Room (Abyss_02b)](#abyss-upper-big-room-abyss02b) | R | None |  | Verified |  |
| R | right1 | Right Exit | [Abyss Landing Zone (Abyss_03)](#abyss-landing-zone-abyss03) | LL | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Left Exit | Right Exit | Clawline OR Faydown Cloak OR Cling Grip OR ( ( Proficient Movement AND spike pogo ) AND Drifters Cloak ) OR Dash OR easy Reaper Crest pogo OR easy Beast Crest pogo OR easy Shaman Crest pogo |  | Verified |  |
| WR | Whole Room | Right Exit | Left Exit | Clawline OR Faydown Cloak OR Cling Grip OR ( ( Proficient Movement AND spike pogo ) AND Drifters Cloak ) OR Dash OR easy Reaper Crest pogo OR easy Beast Crest pogo OR easy Shaman Crest pogo |  | Verified |  |

#### Check Locations

No check locations defined.

### Abyss Landing Zone (Abyss_03)

**Game ID:** Abyss_03

**Contributors:** Pyxl

#### Subrooms

- Landing Zone
- Shard room
- Lower Exit
- Upper Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left2 | Upper Exit | [Abyss Escape Hallway (Abyss_13)](#abyss-escape-hallway-abyss13) | R | None |  | Verified |  |
| D1 | door1 | Landing Zone | [Abyss Diving Bell Broken (Room_Diving_Bell_Abyss)](#abyss-diving-bell-broken-roomdivingbellabyss) | L | invalid |  | Verified | logic always keeps the bell fixed |
| D2 | door2 | Landing Zone | [Abyss Diving Bell Fixed (Room_Diving_Bell_Abyss_Fixed)](#abyss-diving-bell-fixed-roomdivingbellabyssfixed) | L | Have Everbloom |  | Verified |  |
| LL | left1 | Lower Exit | [Abyss Hallway To Upper Big Room (Abyss_02)](#abyss-hallway-to-upper-big-room-abyss02) | R | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RD | Right Drop | Landing Zone | Shard room | None ( Spike Pogo ) |  | Verified |  |
| RD | Right Drop | Shard room | Landing Zone | Cling Grip OR Faydown Cloak   OR ( Scuttlebrace AND Clawline ) |  | Verified | Faydown Cloak barely clips the hazard respawn without ledge grab |
| LD | Left Drop | Landing Zone | Lower Exit | None |  | Verified |  |
| LD | Left Drop | Lower Exit | Landing Zone | easy Reaper Crest pogo OR Cling Grip OR Faydown Cloak OR Silk Soar OR Scuttlebrace |  | Verified | Silk Soar up to first Platform then Spike pogo with any crest to get up |
| SE | Silk Soar Escape | Landing Zone | Upper Exit | Silk Soar AND ( easy Beast Crest pogo OR Dash OR Clawline OR Faydown Cloak ) |  | Verified |  |
| SE | Silk Soar Escape | Upper Exit | Landing Zone | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Abyss #1 | Shard room | None |  | Verified | collectible |  |
| Shell Shard Cache: Abyss #2 | Shard room | None |  | Verified | collectible |  |
| Shell Shard Cache: Abyss #3 | Shard room | None |  | Verified | collectible |  |
| Shell Shard Cache: Abyss #4 | Shard room | None |  | Verified | collectible |  |

### Abyss Lower Big Room (Abyss_05)

**Game ID:** Abyss_05

**Contributors:** Pyxl

#### Subrooms

- Start
- End
- Hidden Shellshards
- Centre Platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | End | [Weavenest Absolom (Abyss_08)](#weavenest-absolom-abyss08) | L | Needolin |  | Verified |  |
| L | left2 | Start | [Abyss Final Bench (Abyss_12)](#abyss-final-bench-abyss12) | R | None |  | Verified |  |
| DI | Dive | Start | [Last Dive (Last_Dive)](#last-dive-lastdive) | D | Have Everbloom |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TV | The Void | Start | Centre Platform | ( Have Everbloom AND ( ( Faydown Cloak AND ( Drifters Cloak OR Dash OR Clawline OR Sharpdart ) AND Cling Grip ) OR ( Clawline AND Faydown Cloak AND Cling Grip ) ) ) |  | Verified |  |
| TV | The Void | Centre Platform | Start | Clawline OR Drifters Cloak |  | Verified |  |
| UV | Upper Void | Centre Platform | Hidden Shellshards | Clawline OR Drifters Cloak OR Faydown Cloak |  | Verified |  |
| DR | Drop | Hidden Shellshards | Start | Clawline OR Drifters Cloak |  | Verified |  |
| TR | Top Right | Centre Platform | End | Silk Soar OR ( Clawline AND Cling Grip AND Faydown Cloak ) |  | Verified |  |
| TR | Top Right | End | Centre Platform | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Abyss_05 #1 | Centre Platform | None |  | Verified | collectible |  |
| Shell Shard Cache: Abyss_05 #2 | Centre Platform | None |  | Verified | collectible |  |
| Shell Shard Cache: Abyss_05 #3 | Centre Platform | None |  | Verified | collectible |  |
| Shell Shard Cache: Abyss_05 #4 | Hidden Shellshards | None |  | Verified | collectible |  |
| Shell Shard Cache: Abyss_05 #5 | Hidden Shellshards | None |  | Verified | collectible |  |

### Abyss Tall Room (Abyss_01)

**Game ID:** Abyss_01

**Contributors:** Pyxl

#### Subrooms

- Bottom
- Top
- Spike Platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right2 | Top | [Abyss Upper Big Room (Abyss_02b)](#abyss-upper-big-room-abyss02b) | L | None |  | Verified |  |
| L | left1 | Bottom | [Abyss Bottom Left Lore Room (Abyss_06)](#abyss-bottom-left-lore-room-abyss06) | R | None |  | Verified |  |
| LR | right4 | Bottom | [Abyss Collapsing Hallway (Abyss_07)](#abyss-collapsing-hallway-abyss07) | L | None |  | Verified |  |
| MR | right3 | Spike Platform | [Arcane Egg Room (Abyss_04)](#arcane-egg-room-abyss04) | L | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SS | Silk Soar | Bottom | Top | Silk Soar |  | Verified |  |
| SS | Silk Soar | Top | Bottom | None |  | Verified |  |
| US | Upper Spikes | Top | Spike Platform | ( Proficient Movement AND spike pogo ) OR ( Drifters Cloak OR Clawline ) |  | Verified |  |
| US | Upper Spikes | Spike Platform | Top | Cling Grip AND ( ( Proficient Movement AND spike pogo ) OR Clawline ) |  | Verified |  |
| LS | Lower Spikes | Bottom | Spike Platform | Silk Soar AND ( ( Proficient Movement AND spike pogo ) OR Drifters Cloak OR Clawline ) |  | Verified |  |
| LS | Lower Spikes | Spike Platform | Bottom | ( Proficient Movement AND spike pogo ) OR ( Drifters Cloak OR Clawline ) |  | Verified |  |

#### Check Locations

No check locations defined.

### Abyss Upper Big Room (Abyss_02b)

**Game ID:** Abyss_02b

**Contributors:** Pyxl

#### Subrooms

- Upper Zone
- Right Exit
- Left Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left2 | Left Exit | [Abyss Tall Room (Abyss_01)](#abyss-tall-room-abyss01) | UR | None |  | Verified |  |
| C | top1 | Upper Zone | [Abyss Drop Down From Escape Hall (Abyss_11)](#abyss-drop-down-from-escape-hall-abyss11) | F | NOne |  | Verified |  |
| R | right1 | Right Exit | [Abyss Hallway To Upper Big Room (Abyss_02)](#abyss-hallway-to-upper-big-room-abyss02) | L | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Left Exit | Right Exit | Faydown Cloak OR ( Silk Soar AND ( Ledge grab OR Cling Grip OR Clawline OR Dash OR Drifters Cloak OR Sharpdart ) ) |  | Verified |  |
| WR | Whole Room | Right Exit | Left Exit | Cling Grip OR Faydown Cloak OR Clawline |  | Verified |  |
| SS | Silk Soar Shaft | Right Exit | Upper Zone | Silk Soar AND ( Faydown Cloak OR Drifters Cloak OR Clawline OR Cling grip OR Scuttlebrace ) |  | Verified |  |
| SS | Silk Soar Shaft | Upper Zone | Right Exit | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lore: Abyss #1 | Upper Zone | None |  | Verified | lore |  |

### Arcane Egg Room (Abyss_04)

**Game ID:** Abyss_04

**Contributors:** Pyxl

#### Subrooms

- Start
- End
- Entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Entrance | [Abyss Tall Room (Abyss_01)](#abyss-tall-room-abyss01) | MR | None |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Start | End | Clawline AND Cling Grip AND Faydown Cloak |  | Verified |  |
| EX | Exit | End | Start | ( Cling Grip AND ( Faydown Cloak OR Clawline ) ) |  | Verified |  |
| EX | Exit | Start | End | Silk Soar AND ( Proficient Movement AND spike pogo ) |  | Verified |  |
| SP | Spikes | Entrance | Start | Sprint OR Dash OR Clawline OR Sharpdart OR Drifters Cloak OR Faydown Cloak |  | Verified |  |
| SP | Spikes | Start | Entrance | None |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Arcane Egg | End | None |  | Verified | collectible |  |

### Weavenest Absolom (Abyss_08)

**Game ID:** Abyss_08

**Contributors:** Pyxl

#### Subrooms

- The Void
- Entrance Zone
- Passageways

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Entrance Zone | [Abyss Lower Big Room (Abyss_05)](#abyss-lower-big-room-abyss05) | R | Needolin |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| US | Upper Shaft | Entrance Zone | Passageways | None |  | Verified |  |
| US | Upper Shaft | Passageways | Entrance Zone | Silk Soar |  | Verified |  |
| LS | Lower Shaft | Passageways | The Void | None |  | Verified |  |
| LS | Lower Shaft | The Void | Passageways | Silk Soar AND ( Faydown Cloak OR Drifters Cloak OR Dash OR Clawline OR Sharpdart ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Farsight | Entrance Zone | Silk Soar OR Clawline OR ( Faydown Cloak AND ( Dash OR Drifters Cloak ) ) |  | Verified | collectible |  |
| Silk Soar | The Void | None |  | Verified | collectible |  |
| Journal Entry: Void Tentrils | Passageways | Silk Soar OR ( Faydown Cloak AND ( Cling grip OR Scuttlebrace ) ) |  | Verified | lore |  |

### Abyss Cocoon (Abyss_Cocoon)

**Game ID:** Abyss_Cocoon

**Contributors:** Pxyl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door_entry |  | [Last Dive (Last_Dive)](#last-dive-lastdive) | D2 | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Lost Lace |  | Cling Grip OR Faydown Cloak OR Silk Soar |  | Verified | boss | Only include as a check for win cons like flea hunt |

#### Notes

Absolute Cinema ( Seriously yhough the room doesnt exist in the map links )

### Last Dive (Last_Dive)

**Game ID:** Last_Dive

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door_cutscenePosition |  | [Abyss Lower Big Room (Abyss_05)](#abyss-lower-big-room-abyss05) | DI | None |  | Verified |  |
| D2 | door_cutscenePosition2 |  | [Abyss Cocoon (Abyss_Cocoon)](#abyss-cocoon-abysscocoon) | D | None |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

Cut Scene That leads into Lost Lace Boss Arena

## Fast Travel

### Bellway Menu

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BB | bone bottom |  | [Bone Bottom Bellway (Bellway_01)](#bone-bottom-bellway-bellway01) | BB | have bellway bone bottom |  | Verified |  |
| TM | the marrow |  | [The Marrow Bellway (Bone_05)](#the-marrow-bellway-bone05) | BB | have bellway the marrow |  | Verified |  |
| DD | deep docks |  | [Deep Docks Bellway (Bellway_02)](#deep-docks-bellway-bellway02) | BB | have bellway deep docks |  | Verified |  |
| FF | far fields |  | [Far Fields Bellway (Bellway_03)](#far-fields-bellway-bellway03) | BB | have bellway far fields |  | Verified |  |
| GM | greymoor |  | [Greymoor Bellway (Bellway_04)](#greymoor-bellway-bellway04) | BW | have bellway greymoor |  | Verified |  |
| BH | bellhart |  | [Bellhart Bellway (Belltown_basement)](#bellhart-bellway-belltownbasement) | BH | have bellway bellhart |  | Verified |  |
| SW | shellwood |  | [Shellwood Bellway  (Shellwood_19)](#shellwood-bellway) | BB | have bellway shellwood |  | Verified |  |
| BS | blasted steps |  | [Blasted Steps Bellway (Bellway_08)](#blasted-steps-bellway-bellway08) | BB | have bellway blasted steps |  | Verified |  |
| TS | the slab |  | [Slab Bellway (Slab_06)](#slab-bellway-slab06) | BW | have bellway the slab |  | Verified |  |
| GB | grand bellway |  | [Grand Bellway (Bellway_City)](#grand-bellway-bellwaycity) | BW | have bellway grand bellway |  | Verified |  |
| BW | bilewater |  | [Bilewater Bellway (Bellway_Shadow)](#bilewater-bellway-bellwayshadow) | D | have bellway bilewater |  | Verified |  |
| PD | putrified ducts |  | [Putrified Ducts Bellway (Bellway_Aqueduct)](#putrified-ducts-bellway-bellwayaqueduct) | BB | have bellway putrified ducts |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

a virtual room to represent the bellway fast travel menu

### Ventrica Menu

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | terminus |  | [Terminus Ventrica (Tube_Hub)](#terminus-ventrica-tubehub) | V | have ventrica terminus |  | Verified |  |
| M | memorium |  | [Memorium Ventrica (Arborium_Tube)](#memorium-ventrica-arboriumtube) | V | have ventrica memorium |  | Verified |  |
| HH | high halls |  | [High Halls Ventrica (Hang_06b)](#high-halls-ventrica-hang06b) | V | have ventrica high halls |  | Verified |  |
| FS | first shrine |  | [Songclave Tube (Song_Enclave_Tube)](#songclave-tube-songenclavetube) | V | have ventrica first shrine |  | Verified |  |
| CC | choral chambers |  | [Choral Chambers Ventrica Room (Song_01b)](#choral-chambers-ventrica-room-song01b) | V | have ventrica choral chambers |  | Verified |  |
| GB | grand bellway |  | [Grand Bellway (Bellway_City)](#grand-bellway-bellwaycity) | VT | have ventrica grand bellway |  | Verified |  |
| UW | underworks |  | [Underworks Ventrica (Under_22)](#underworks-ventrica-under22) | V | have ventrica underworks |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

a virtual room to represent the ventrica fast travel menu

### Slab Capture

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CG | cage |  | [Slab Cell (Slab_03)](#slab-cell-slab03) | CPT | none |  | Verified |  |
| DD | deep docks |  | ["Deep Docks" March Side Room (Bone_East_04c)](#deep-docks-march-side-room-boneeast04c) | SC | invalid |  | Verified | one-way to prevent logic traversal bleed |
| BW | bilewater |  | [Bilewater Lower East Hall Secret (Shadow_21)](#bilewater-lower-east-hall-secret-shadow21) | SC | invalid |  | Verified | one-way to prevent logic traversal bleed |
| GM | greymoor |  | [Greymoor Towers Patio (Greymoor_05)](#greymoor-towers-patio-greymoor05) | SC | invalid |  | Verified | one-way to prevent logic traversal bleed |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

A virtual room to represent being captured by a wardenfly cage and transported to The Slab.

## Wish Menus

### Bone Bottom Wish Wall

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BB | bone bottom |  | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | WW | invalid |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| the lost fleas wish promised |  | none |  | Verified | event | also promised/granted at the flea caravan |
| berry picking wish promised |  | none |  | Verified | event | granted at the moss druid |
| garb of the pilgrims wish promised |  | act 1 OR act 2 |  | Verified | event |  |
| garb of the pilgrims wish granted |  | complete garb of the pilgrims wish promised  AND pilgrim shawls 12 |  | Verified | event | reward is 120 rosary necklace |
| volatile flintbeetles wish promised |  | ( act 1 OR act 2 ) AND  ( visit greymoor  OR visit shellwood ) |  | Verified | event | new predicate for reaching a zone, woo |
| volatile flintbeetles wish granted |  | complete volatile flintbeetles wish promised AND flintgems 3 |  | Verified | event |  |
| volatile flintbeetles memory locket |  | complete volatile flintbeetles wish granted |  | Verified | collectible |  |
| the terrible tyrant wish promised |  | ( act 1 OR act 2 ) AND  have cling grip |  | Verified | event | granted at the marrow boss arena |
| the terrible tyrant wish granted |  | complete the terrible tyrant wish promised AND have crown fragment |  | Verified | event | reward is 220 rosary necklace |
| bone bottom repairs wish promised |  | act 1 OR act 2 |  | Verified | event |  |
| bone bottom repairs wish granted |  | complete bone bottom repairs wish promised AND shell shards 200 |  | Verified | event | reward is self-satisfaction (and unlocking other wishes) |
| a lifesaving bridge wish promised |  | ( act 1 OR act 2 ) AND  complete bone bottom repairs wish granted AND ( defeat THE boss widow  OR visit greymoor ) |  | Verified | event |  |
| a lifesaving bridge wish granted |  | complete a lifesaving bridge wish promised AND shell shards 300 |  | Verified | event | reward is a breakable bridge |
| an icon of hope wish promised |  | ( act 1 OR act 2 ) AND  complete a lifesaving bridge wish granted AND ( visit the citadel ) |  | Verified | event |  |
| an icon of hope wish granted |  | complete an icon of hope wish promised AND shell shards 440 |  | Verified | event | reward is hornet statuette AND flick breakable statue |
| hornet statuette |  | complete an icon of hope wish granted |  | Verified | collectible |  |

#### Notes

Access to the Wish Wall (and this virtual room) is gated by defeating Bell Beast. All wishes below therefore have that as a prerequisite.

### Bellhart Wish Wall

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BH | bellhart |  | [Belltown (Belltown)](#belltown-belltown) | WW | invalid |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| pinmasters oil wish promised |  | none |  | Verified | event | reward is needle upgrade  granted at pimaster plinney's shop |
| my missing courier wish promised |  | none |  | Verified | event |  |
| silver bells wish promised |  | none |  | Verified | event |  |
| silver bells wish granted |  | complete silver bells wish promised AND Silver Bells 8 |  | Verified | event | reward is a rosary necklace |
| crawbug clearing wish promised |  | none |  | Verified | event | can be started here or with creige directly |
| restoration of bellhart wish promised |  | needle upgrades 1 AND sold relics 1 |  | Verified | event | spreadsheet says requirements are: - nail upgrades > 0 - sold relics > 0 - pavo conversation > 0 + time passed |
| restoration of bellhart wish granted |  | complete restoration of bellhart wish promised AND rosaries 250 |  | Verified | event | reward is self-satisfaction, I guess? |
| my missing brother wish promised |  | complete THE My Missing Courier Wish Granted AND ( complete THE Great Taste Of Pharloom Wish Promised OR complete Meet the Caretaker IN Songclave ) |  | Verified | event |  |
| trails end wish promised |  | shakra map purchases 14 AND have faydown cloak  AND ( defeat THE boss groal the great OR threefold melody parts 2 ) |  | Verified | event | Must have purchased all Shakra maps, own at least two of the threefold melody parts or defeat groal the great |
| silk and soul wish promised |  | after silk and soul wish promised IN songclave wish wall |  | Verified | event | usually wouldn't do it this way, because this makes it look like you need to go songclave to collect this wish (technically true), but this wish req is a pain  not even sure it should be on here from a logic perspective |
| savage beastfly wish promised |  | defeat THE savage beastfly boss fight AND defeat THE fourth chorus boss fight AND complete THE reach songclave |  | Verified | event | spreadsheet says requirements are: - defeat savage beastfly - defeated fourth chorus - visited songclave |
| savage beastfly wish granted |  | complete savage beastfly wish promised AND have horn fragment |  | Verified | event | reward is a mask shard |
| Savage Beastfly - Mask Shard |  | complete savage beastfly wish granted |  | Verified | collectible |  |
| bellharts glory wish promised |  | complete restoration of bellhart wish granted AND ( defeat THE cogwork dancers boss fight OR have clawline OR complete THE reach songclave ) |  | Needs verification | event | Spreadsheet flags are vague, so rolling with the wiki requirements for a bit  "datamining gem" spreadsheet says that requirements are: - quest completed: Belltown House Start  - BelltownHouseState == 1  - citadelHalfwayComplete == true  "player anecdote coal" wiki says that requirements are: - restore bellhart - cogwork dancers or clawline or songclave |
| bellharts glory wish granted |  | complete restoration of bellhart wish promised AND rosaries 400 |  | Verified | event | reward is bellhome key |
| Bellhome Key |  | complete bellharts glory wish granted |  | Verified | collectible |  |
| fatal resolve wish promised |  | act 3 AND have silk soar AND have needle strike |  | Verified | event | one of two locations to start the wish - wiki says you need to swing by the hut first if you accept here |
| heros call wish promised |  | ( garmond and zaza encounters 3 OR have everbloom ) |  | Needs verification | event | spreadsheet has single quest ready flag, so using wiki as source  they have 9 locations where they spawn, will map them later - hero, 9/26 |
| dark hearts wish promised |  | act 3 |  | Needs verification | event | actual flag is quest completed: Black Thread Pt1 Shamans? |
| dark hearts wish granted |  | destroy void masses 12 |  | Verified | event | this one is going to take a LOT of time to map properly - there are 47 void masses (45 in steel soul) locations per the wiki |
| Dark Hearts - Mask Shard |  | complete dark hearts wish granted |  | Verified | collectible |  |
| the hidden hunter wish promised |  | complete THE meet karmelita |  | Verified | event |  |
| the hidden hunter wish granted |  | have grass doll |  | Verified | event |  |
| The Hidden Hunter - Mask Shard |  | complete the hidden hunter wish granted |  | Verified | collectible |  |
| fastest in pharloom wish promised |  | have silk soar |  | Verified | event | one of two places to accept this wish |
| ecstasy of the end wish promised |  | act 3 AND after THE flea caravan move to fleatopia AND silk soar AND fleas 30 |  | Verified | event | one of two places to accept this wish  spreadsheet flag is vague, so using wiki requirements |

#### Notes

Access to the Wish Wall (and this virtual room) is gated by defeating Widow. All wishes below therefore have that as a prerequisite.

### Bellhart Deliveries

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BH | bellhart |  | [Belltown (Belltown)](#belltown-belltown) | DW | invalid |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bone bottom supplies wish promised |  | act 1 OR act 2 |  | Verified | event |  |
| pilgrims rest supplies wish promised |  | act 1 OR act 2 |  | Verified | event |  |
| queens egg wish promised |  | after THE styx grew first grub |  | Verified | event | per the spreadsheet |
| songclave supplies wish promised |  | act 3 OR complete THE meet the caretaker |  | Verified | event | per the spreadsheet: (enclaveLevel > 0 AND soulSnareReady == false) OR (blackThreadWorld == true)) |
| liquid lacquer wish promised |  | have faydown AND after THE Play Threefold Melody |  | Verified | event |  |
| fleatopia supplies wish promised |  | after THE flea caravan move to fleatopia |  | Verified | event |  |
| survivors camp wish supplies |  | act 3 |  | Verified | event | doesn't seem to require having saved the couriers? might cause problems later, because this room is locked behind that requirement, teehee |

#### Notes

Access to the Delivery Wishes (and this virtual room) is gated by rescuing Tipp & Phil. All wishes below therefore have that as a prerequisite.

### Songclave Wish Wall

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SC | songclave |  | [Songclave (Song_Enclave)](#songclave-songenclave) | WW | invalid |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| building up songclave wish promised |  | act 2 |  |  | event |  |
| building up songclave wish granted |  | complete building up songclave wish promised AND rosaries 300 |  | Verified | event |  |
| strengthening songclave wish promised |  | act 2 AND complete building up songclave wish granted AND grant songclave wishes 4 |  | Needs verification | event | "datamining gem" spreadsheet says that requirements are: - quest completed: Songclave Donation 1  - (enclaveLevel > 1 AND enclaveDonation2_Available == true)  "player anecdote coal" wiki says that requirements are: - complete building up songclave - complete 3 other wishes (4 counting building up songclave) |
| strengthening songclave wish granted |  | complete strengthening songclave wish promised AND rosaries 500 |  | Verified | event |  |
| balm for the wounded wish promised |  | act 2 AND complete THE building up songclave wish granted AND grant songclave wishes 2 AND visit whiteward |  | Needs verification | event | granted in whiteward; rewards spool fragment  "datamining gem" spreadsheet says that requirements are: - shermaQuestActive == true  "player anecdote coal" wiki says that requirements are: - meet sherma within songclave, which requires building up songclave wish, and one other wish - visit the whiteward |
| the wandering merchant wish promised |  | act 2 |  |  | event | granted in choral chambers merchant room; reward is jubilana setting up shop  "datamining gem" spreadsheet says that requirements are: - always  "player anecdote coal" wiki says that requirements are: - discover songclave |
| the lost merchant wish promised |  | act 2 AND complete THE the wandering merchant wish granted AND grant songclave wishes 5 AND have faydown cloak |  | Needs verification | event | granted in memorium shopkeeper hides; reward is more shop inventory  "datamining gem" spreadsheet says that requirements are: - quest completed: Save City Merchant - cityMerchantCanLeaveForBridge == true  "player anecdote coal" wiki says that requirements are: - complete the wandering merchant wish - complete 5 total songclave wishes (including the above) - speak to jubilana - faydown cloak |
| fine pins wish promised |  | none |  | Needs verification | event | unsure if limited to act 2  "datamining gem" spreadsheet says that requirements are: - always  "player anecdote coal" wiki says that requirements are: - ring the bell in the first shrine |
| fine pins wish granted |  | complete THE fine pins wish promised AND fine pins 12 |  | Verified | event | reward is heavy rosary necklace |
| cloaks of the choir wish promised |  | complete building up songclave wish granted AND complete fine pins wish granted |  | Needs verification | event | unsure if limited to act 2  "datamining gem" spreadsheet says that requirements are: - quest completed: Fine Pins - enclaveLevel > 1  "player anecdote coal" wiki says that requirements are: - building up songclave wish - fine pins wish granted |
| cloaks of the choir wish granted |  | complete THE cloaks of the choir wish promised AND choir cloaks 16 |  | Verified | event | reward is heavy rosary necklace |
| the wailing mother wish promised |  | act 2 AND defeat gauntlet fight IN slab arena AND complete building up songclave wish granted AND grant songclave wishes 5 |  |  | event | unsure if limited to act 2  "datamining gem" spreadsheet says that requirements are: - slab_cloak_battle_completed == true  - enclaveLevel > 2  "player anecdote coal" wiki says that requirements are: - Visit slab arena room - complete building up songclave wish - complete 5 total songclave wishes (including the above) |
| the wailing mother wish granted |  | complete the wailing mother wish promised AND have broodmothers eye |  | Verified | event | reward is heavy rosary necklace |
| final audience wish promised |  | activate THE second sentinel activation AND have conductors melody AND ( second sentinel encounters 2 OR ( have everbloom AND second sentinel encounters 1 )  ) AND complete THE building up songclave wish granted AND   complete THE balm for the wounded wish granted AND grant songclave wishes 2 |  | Needs verification | event | "datamining gem" spreadsheet says that requirements are: - songChevalierQuestReady == true  "player anecdote coal" wiki says that requirements are: - activating second sentinel - meet second sentinel twice in citadel OR once if have everbloom - have conductor's melody - complete two wishes in songclave, one of which should be building up songclave  without further datamining insight, i'll roll with the wiki requirements |
| silk and soul wish promised |  | act 2 AND have faydown cloak AND defeat THE boss lace 2 AND complete THE flea caravan move to fleatopia AND complete THE flexible spines wish granted AND complete THE bone bottom repairs wish granted AND complete THE a lifesaving bridge wish granted AND complete THE crawbug clearing wish granted AND complete THE restoration of bellhart wish granted AND complete THE bellharts glory wish granted AND complete THE building up songclave wish granted AND complete THE strengthening songclave wish granted AND complete THE trails end wish granted AND complete THE balm for the wounded wish granted AND silk and soul points 17 |  |  | event | LOL  per the spreadsheet for required wishes  spreadsheet also has a requirement to talk to pavo under BelltownGreeterHouseFullDlg - not sure how to represent that  sadly "silk and soul points 17" is load-bearing here |
| pain anguish and misery wish promised |  | have silksoar AND have progressive claw mirror |  |  | event | reward is dark mirror (progressive claw mirror) and is granted in the stage  act 3 is implicit in vanilla because of silksoar, but not explicitly enforced. in theory could you get this quest before defeating trobbio 1?  "datamining gem" spreadsheet says that requirements are: - tool "dazzle bind" (claw mirror?) - silksoar  "player anecdote coal" wiki says that requirements are: - claw mirror - silksoar |

#### Notes

Access to the Wish Wall (and this virtual room) is gated by activating the Songclave Bellshrine and meeting the Caretaker. All wishes below therefore have that as a prerequisite.
