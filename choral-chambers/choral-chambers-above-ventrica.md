# Choral Chambers Above Ventrica (Song_03)

**Game ID:** Song_03

**Contributors:** samupo, Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Top | ✓ |
| S2 | Bottom Left | ✓ |
| S3 | Bottom Right | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom Left | [Choral Chambers Ventrica Room (Song_01b)](choral-chambers-ventrica-room.md) | T | none |  | Verified | ✓ |  |
| T | top1 | Top | [Choral Chambers Outside Spa (Song_04)](choral-chambers-outside-spa.md) | B | Activate Switch - Outside Spa IN Choral chambers outside spa |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Vertical | Bottom Left | Top | silk soar OR (ledge grab both AND easy pogo off Reed AND easy damage boost off Reed) OR (ledge grab left AND scuttlebrace) OR (faydown cloak AND ((easy pogo off Reed AND easy damage boost off Reed) OR scuttlebrace OR ledge grab either)) OR (cling grip right AND (ledge grab left OR cling grip left)) OR (cling grip left AND ledge grab right) |  | Verified | ✓ |  |
| V1 | Vertical | Top | Bottom Left | none |  | Verified | ✓ | falling |
| V2 | Vertical2 | Bottom Left | Bottom Right | (cling grip right AND (ledge grab left OR cling grip left)) OR (cling grip left AND ledge grab right) OR faydown cloak OR silk soar |  | Verified | ✓ |  |
| V2 | Vertical2 | Bottom Right | Bottom Left | silk soar OR cling grip right OR (faydown cloak AND (easy pogo off Reed OR (ledge grab left AND easy pogo off Choristor))) OR ((scuttlebrace OR cling grip left) AND easy pogo off [Reed, Choristor]) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Choristor's precious belongings | Bottom Right | none |  | Verified | collectible | ✓ | rosary chest |
| 2 | Old Ventrica gains | Top | none |  | Verified | collectible | ✓ | rosary cache |
| 3 | Old Ventrica treasury | Top | none |  | Verified | collectible | ✓ | rosary cache |
| 4 | Choir Pouncer 1 | Bottom Left | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 5 | Reed 1 | Bottom Left | Normal World Spawn |  | Verified | enemy | ✓ | FSM Boolean flags: marionettesBurned, marionettesMet |
| 6 | Choristor 1 | Bottom Right | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 7 | Envoy 1 | Bottom Left | Normal World Spawn |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Choral Chambers Above Ventrica (Song_03)](../00-annotations/choral-chambers/choral-chambers-above-ventrica-connections.png)](../00-annotations/choral-chambers/choral-chambers-above-ventrica-connections.png)

### Checks

[![Checks for Choral Chambers Above Ventrica (Song_03)](../00-annotations/choral-chambers/choral-chambers-above-ventrica-checks.png)](../00-annotations/choral-chambers/choral-chambers-above-ventrica-checks.png)

### Scene

[![Scene for Choral Chambers Above Ventrica (Song_03)](../00-annotations/choral-chambers/choral-chambers-above-ventrica-scene.png)](../00-annotations/choral-chambers/choral-chambers-above-ventrica-scene.png)
