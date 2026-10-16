# Choral Chambers Below Ventrica (Song_01)

**Game ID:** Song_01

**Contributors:** samupo, Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Bottom | ✓ |
| S2 | Middle | ✓ |
| S3 | Right Exit | ✓ |
| S4 | Side Chamber | ✓ |
| S5 | Pre Top | ✓ |
| S6 | Top | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom | [Grand Gate Maintenance Room (Song_01c)](../grand-gate/grand-gate-maintenance-room.md) | T | break wall down OR break wall up |  | Verified | ✓ |  |
| T | top1 | Top | [Choral Chambers Ventrica Room (Song_01b)](choral-chambers-ventrica-room.md) | B | cling grip either OR silk soar |  | Verified | ✓ |  |
| R | right2 | Right Exit | [Choral Chambers Outisde Underworks (Under_07b)](choral-chambers-outisde-underworks.md) | L | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Bottom to Right Exit | Bottom | Right Exit | ((Drifter's cloak OR Dash both OR Run either) AND ledge grab) OR ((Clawline OR sharpdart x 3 ) AND (easy pogo off [Choir Pouncer, Choir Hornhead, Envoy] OR ledge grab OR cling grip right OR cling grip left)) OR (dash right AND (ledge grab OR cling grip right) AND (sharpdart OR clawline left)) OR (dash left AND (ledge grab AND cling grip left) AND (sharpdart OR clawline right)) OR (Sharpdart AND (ledge grab OR cling grip either) AND (dash right OR dash left OR clawline right OR clawline left)) OR (Scuttlebrace AND (ledge grab OR cling grip either OR (easy pogo off [Choir Pouncer, Choir Hornhead, Envoy] ))) OR faydown cloak OR silk soar OR (ledge grab AND Hard Shaman pogo) OR (Ledge Grab AND medium Beast pogo AND medium Heal stall) OR (ledge grab AND (Flea brew OR easy voltvessels stall OR easy plasmium phial stall)) |  | Verified | ✓ |  |
| V1 | Bottom to Right Exit | Right Exit | Bottom | none |  | Verified | ✓ | falling |
| LV | Lever | Right Exit | Middle | activate Lever Below Ventrica AND (silk soar OR faydown cloak OR ((Flea brew OR sharp dart OR Dash left OR Run either OR clawline left) AND (cling grip left OR (ledge grab AND easy pogo off Choir Pouncer)))) |  | Verified | ✓ |  |
| V2 | Bottom to Middle | Bottom | Middle | cling grip both OR (cling grip right AND faydown cloak) OR silk soar OR ((ledge grab OR faydown cloak)  AND medium pogo off Choir Flyer AND medium Damage boost) |  | Verified | ✓ | can exactly hit the Choir flyer 4 times |
| V2 | Bottom to Middle | Middle | Bottom | none |  | Verified | ✓ | falling |
| V3 | Middle to Pre Top | Middle | Pre Top | silk soar OR ((easy pogo off [Choir Pouncer, Choir Hornhead, Envoy] OR faydown cloak) AND cling grip left) OR (cling grip right AND (faydown cloak OR drifter's cloak OR clawline left OR Dash left OR sharp dart)) OR (ledge grab AND easy Shaman pogo AND easy pogo off Choir Flyer AND faydown cloak) |  | Verified | ✓ | need to aggro Choir Flyer for Shaman skip |
| V3 | Middle to Pre Top | Pre Top | Middle | none |  | Verified | ✓ | falling |
| V4 | Pre Top to Top | Pre Top | Top | cling grip either OR faydown cloak OR silk soar |  | Verified | ✓ |  |
| V4 | Pre Top to Top | Top | Pre Top | none |  | Verified | ✓ | falling |
| LV | Lever | Middle | Right Exit | activate Lever Below Ventrica |  | Verified | ✓ | falling |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Rosary Cache: Choral Chambers #3 | Top | none |  | Verified | collectible | ✓ |  |
| 2 | Rosary Cache: Choral Chambers #4 | Top | none |  | Verified | collectible | ✓ |  |
| 3 | Shell Shard Cache: Choral Chambers | Side Chamber | none |  | Verified | collectible | ✓ |  |
| 4 | Rosary Cache: Choral Chambers #1 | Middle | none |  | Verified | collectible | ✓ |  |
| 5 | Rosary Cache: Choral Chambers #2 | Middle | none |  | Verified | collectible | ✓ |  |
| 6 | Lever Below Ventrica | Middle | none |  | Verified | switch | ✓ |  |
| 7 | Choir Flyer 1 | Bottom | Normal World Spawn AND ((prereq Lace Second Encounter IN choral chambers eastern shaft) OR (prereq Lace Second Encounter IN grand bellway shaft)) |  | Verified | enemy | ✓ |  |
| 8 | Choir Hornhead 1 | Middle | Normal World Spawn AND ((prereq Lace Second Encounter IN choral chambers eastern shaft) OR (prereq Lace Second Encounter IN grand bellway shaft)) |  | Verified | enemy | ✓ |  |
| 9 | Choir Hornhead 2 | Bottom | Normal World Spawn AND ((prereq Lace Second Encounter IN choral chambers eastern shaft) OR (prereq Lace Second Encounter IN grand bellway shaft)) |  | Verified | enemy | ✓ |  |
| 10 | Choir Pouncer 1 | Bottom | Normal World Spawn AND ((prereq Lace Second Encounter IN choral chambers eastern shaft) OR (prereq Lace Second Encounter IN grand bellway shaft)) |  | Verified | enemy | ✓ |  |
| 11 | Choir Pouncer 2 | Bottom | Normal World Spawn AND ((prereq Lace Second Encounter IN choral chambers eastern shaft) OR (prereq Lace Second Encounter IN grand bellway shaft)) |  | Verified | enemy | ✓ |  |
| 12 | Choir Pouncer 3 | Middle | Normal World Spawn AND ((prereq Lace Second Encounter IN choral chambers eastern shaft) OR (prereq Lace Second Encounter IN grand bellway shaft)) |  | Verified | enemy | ✓ |  |
| 13 | Choristor 1 | Middle | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 14 | Envoy 1 | Bottom | Normal World Spawn AND ((prereq Lace Second Encounter IN choral chambers eastern shaft) OR (prereq Lace Second Encounter IN grand bellway shaft)) |  | Verified | enemy | ✓ | FSM Boolean flags: marionettesBurned, marionettesMet |
| 15 | Envoy 2 | Middle | Normal World Spawn AND ((prereq Lace Second Encounter IN choral chambers eastern shaft) OR (prereq Lace Second Encounter IN grand bellway shaft)) |  | Verified | enemy | ✓ | FSM Boolean flags: marionettesBurned, marionettesMet |
| 16 | Reed 1 | Middle | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 17 | Void Mass 1 | Middle | Black Thread World Spawn |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Choral Chambers Below Ventrica (Song_01)](../00-annotations/choral-chambers/choral-chambers-below-ventrica-connections.png)](../00-annotations/choral-chambers/choral-chambers-below-ventrica-connections.png)

### Checks

[![Checks for Choral Chambers Below Ventrica (Song_01)](../00-annotations/choral-chambers/choral-chambers-below-ventrica-checks.png)](../00-annotations/choral-chambers/choral-chambers-below-ventrica-checks.png)

### Scene

[![Scene for Choral Chambers Below Ventrica (Song_01)](../00-annotations/choral-chambers/choral-chambers-below-ventrica-scene.png)](../00-annotations/choral-chambers/choral-chambers-below-ventrica-scene.png)
