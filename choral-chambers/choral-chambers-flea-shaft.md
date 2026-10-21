# Choral Chambers Flea Shaft (Song_11)

**Game ID:** Song_11

**Contributors:** samupo, Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Base Bottom | ✓ |
| S2 | Base Middle | ✓ |
| S3 | Base Upper Right | ✓ |
| S4 | Base Upper Left | ✓ |
| S5 | Top Section 1 | ✓ |
| S6 | Top Section 2 | ✓ |
| S7 | Top Section 3 Left | ✓ |
| S8 | Top Section 3 Right | ✓ |

- **Base Upper Right:** 


## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S3L | left1 | Top Section 3 Left | [Corridor to High Halls (Song_17)](corridor-to-high-halls.md) | R | none |  | Verified | ✓ |  |
| S2L | left2 | Top Section 2 | [Choral Chambers Maintenance Tunnel (Song_15)](choral-chambers-maintenance-tunnel.md) | R | none |  | Verified | ✓ |  |
| S3R | right2 | Top Section 3 Right | [High Halls Corridor (Hang_07)](high-halls-corridor.md) | L | activate Lever Flea Shaft 2 |  | Verified | ✓ |  |
| BLB | left4 | Base Middle | [Choral Chambers Spa (Song_10)](choral-chambers-spa.md) | R | activate Lever Chambers Spa 2 IN choral chambers spa |  | Verified | ✓ |  |
| BR | right3 | Base Bottom | [Choral Chambers Eastern Shaft (Song_05)](choral-chambers-eastern-shaft.md) | L3 | none |  | Verified | ✓ |  |
| BLT | left3 | Base Upper Left | [Choral Chambers Above Spa (Song_13)](choral-chambers-above-spa.md) | R | none |  | Verified | ✓ |  |
| S1R | right1 | Top Section 1 | [Choral Chambers Dining Room (Song_09b)](choral-chambers-dining-room.md) | L | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| VS | Vertical Base | Base Bottom | Base Middle | (cling grip left AND (dash left OR clawline left OR sharpdart)) OR easy pogo off Choir flyer OR (faydown cloak AND (ledge grab either OR easy Shaman pogo OR scuttlebrace OR cling grip right)) OR silk soar OR (scuttlebrace AND clawline both) |  | Verified | ✓ |  |
| VS | Vertical Base | Base Middle | Base Bottom | none |  | Verified | ✓ | falling |
| VR | Vertical Middle | Base Middle | Base Upper Right | faydown cloak OR hard pogo off [Choir hornhead, Choir Pouncer] OR ((Dash right OR sharpdart OR clawline right) AND ledge grab right) OR (run AND (ledge grab right OR easy Damage boost off Choir hornhead OR (easy Damage boost off Choir pouncer AND (easy heal stall OR easy voltvessels stall OR easy plasmium phial stall OR easy flintslate stall)))) OR silk soar OR scuttlebrace OR (clawline right AND easy damage boost off [Choir Hornhead,Choir pouncer]) |  | Verified | ✓ |  |
| VR | Vertical Middle | Base Upper Right | Base Middle | none |  | Verified | ✓ | falling |
| LR | Base Upper Traversal | Base Upper Right | Base Upper Left | faydown cloak OR silk soar OR ((clawline left OR sharpdart) AND (easy shaman pogo OR ledge grab left)) OR (run AND ledge grab left) OR scuttlebrace |  | Verified | ✓ |  |
| LR | Base Upper Traversal | Base Upper Left | Base Upper Right | none |  | Verified | ✓ | falling |
| VL | Vertical Lever | Base Upper Left | Top Section 1 | activate Lever Flea Shaft 1 AND ((easy pogo off Choir Elder) OR faydown cloak OR silk soar OR cling grip right OR scuttlebrace) |  | Verified | ✓ |  |
| VL | Vertical Lever | Top Section 1 | Base Upper Left | activate Lever Flea Shaft 1 |  | Verified | ✓ | falling |
| V1 | Section 1 to Section 2 | Top Section 1 | Top Section 2 | silk soar OR (cling grip left AND (faydown cloak OR cling grip right OR (easy  pogo off Choir Flyer AND easy heal stall))) OR (faydown cloak AND ledge grab left AND easy pogo off Choir Elder AND spike pogo) OR (easy  pogo off [Choir Flyer, Choir Elder] AND easy heal stall AND spike pogo AND ledge grab either) OR (scuttlebrace AND (drifter's cloak OR clawline left OR sharpdart OR easy pogo off [Choir Flyer, Choir Elder])) |  | Verified | ✓ |  |
| V1 | Section 1 to Section 2 | Top Section 2 | Top Section 1 | none |  | Verified | ✓ | falling |
| V2 | Section 2 to Section 3 Left | Top Section 2 | Top Section 3 Left | (silk soar AND (ledge grab left OR clawline left OR dash left OR sharpdart OR faydown cloak OR drifter's cloak OR scuttlebrace OR easy pogo off Choir Flyer)) OR (cling grip left AND spike pogo) OR (cling grip right AND (ledge grab left OR easy pogo off Choir Flyer OR scuttlebrace OR faydown cloak)) OR (scuttlebrace AND ((drifter's cloak AND spike pogo) OR sharpdart x 2 OR (sharpdart AND clawline either) OR clawline both)) |  | Verified | ✓ |  |
| V2 | Section 2 to Section 3 Left | Top Section 3 Left | Top Section 2 | none |  | Verified | ✓ | falling |
| H | Top Horizontal Traversal | Top Section 3 Right | Top Section 3 Left | ledge grab left OR clawline left OR drifter's cloak OR sharpdart OR scuttlebrace OR easy pogo off Choir Flyer |  | Verified | ✓ |  |
| H | Top Horizontal Traversal | Top Section 3 Left | Top Section 3 Right | (run AND (ledge grab right OR easy heal stall OR easy voltvessels stall OR easy plasmium phial stall OR easy flintslate stall)) OR (silk soar AND (ledge grab right OR clawline right OR dash right OR sharpdart OR faydown cloak OR drifter's cloak OR scuttlebrace OR easy pogo off Choir Flyer)) OR cling grip right OR scuttlebrace OR (easy pogo off Choir Flyer AND (dash right OR (easy heal stall OR easy voltvessels stall OR easy plasmium phial stall OR easy flintslate stall)) AND easy damage boost off Choir FLyer) OR clawline right OR sharpdart OR faydown cloak |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Flea: Choral Chambers - Walled Room | Top Section 2 | Break Wall right AND (silk soar OR drifter's cloak OR (faydown cloak AND easy [Wanderer, Reaper,Witch, Shaman] pogo)) |  | Verified | collectible | ✓ | Secret hidden by breaking a wall And possible while cursed |
| 2 | Flea Shaft's stolen rosaries | Base Upper Right | none |  | Verified | collectible | ✓ | rosary cache |
| 3 | Flea Shaft's bounty | Base Upper Right | none |  | Verified | collectible | ✓ | rosary cache |
| 4 | Flea Shaft's kidnappers' bonus | Base Upper Right | none |  | Verified | collectible | ✓ | rosary cache |
| 5 | Lever Flea Shaft 1 | Top Section 1 | none |  | Verified | switch | ✓ |  |
| 6 | Lever Flea Shaft 2 | Top Section 3 Right | none |  | Verified | switch | ✓ |  |
| 7 | Choir Bellbearer 1 | Top Section 3 Left | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 8 | Choir Elder 1 | Top Section 1 | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 9 | Choir Flyer 1 | Base Bottom | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 10 | Choir Flyer 2 | Top Section 2 | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 11 | Choir Flyer 3 | Top Section 3 Left | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 12 | Choir Hornhead 1 | Base Upper Right | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 13 | Choir Pouncer 1 | Base Upper Right | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 14 | Choir Pouncer 2 | Top Section 2 | Normal World Spawn |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Choral Chambers Flea Shaft (Song_11)](../00-annotations/choral-chambers/choral-chambers-flea-shaft-connections.png)](../00-annotations/choral-chambers/choral-chambers-flea-shaft-connections.png)

### Checks

[![Checks for Choral Chambers Flea Shaft (Song_11)](../00-annotations/choral-chambers/choral-chambers-flea-shaft-checks.png)](../00-annotations/choral-chambers/choral-chambers-flea-shaft-checks.png)

### Scene

[![Scene for Choral Chambers Flea Shaft (Song_11)](../00-annotations/choral-chambers/choral-chambers-flea-shaft-scene.png)](../00-annotations/choral-chambers/choral-chambers-flea-shaft-scene.png)
