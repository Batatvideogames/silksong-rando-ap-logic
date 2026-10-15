# Choral Chambers Above Ventrica (Song_03)

**Game ID:** Song_03

**Contributors:** samupo,Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Top | ✓ |
| S2 | Bottom Left | ✓ |
| S3 | Bottom Right | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom Left | [Choral Chambers Ventrica Room (Song_01b)](choral-chambers-ventrica-room.md) | T | none |  |  | ✓ |  |
| T | top1 | Top | [Choral Chambers Outside Spa (Song_04)](choral-chambers-outside-spa.md) | B | Activate Switch - Outside Spa IN Choral chambers outside spa |  |  | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top | Bottom Left | none |  |  |  | falling |
| V | Vertical | Bottom Left | Top | silk soar OR ((ledge grab OR cling grip) AND faydown cloak) OR ((Dash OR easy Shaman pogo) AND cling grip) OR (ledge grab AND easy pogo off Reed AND easy damage boost) |  |  |  |  |
| V2 | Vertical2 | Top | Bottom Right | none |  |  |  | falling |
| V2 | Vertical2 | Bottom Right | Top | silk soar OR cling grip right OR (cling grip left AND easy pogo off [Reed, Choristor]) OR (ledge grab AND faydown cloak AND easy pogo off [Reed, Choristor]) |  |  |  |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | import enemies |  |  | TODO | Needs verification |  |  |  |
| 2 | Rosary Chest - Choral Chambers #1 | Bottom Right | none |  |  | collectible | ✓ |  |
| 3 | Rosary Cache - Choral Chambers #8 | Top | none |  |  | collectible | ✓ |  |
| 4 | Rosary Cache - Choral Chambers #9 | Top | none |  |  | collectible | ✓ |  |
| 5 | Choir Pouncer 1 |  |  |  |  | enemy | ✓ |  |
| 6 | Reed 1 |  |  |  |  | enemy | ✓ | FSM Boolean flags: marionettesBurned, marionettesMet |
| 7 | Choristor 1 |  |  |  |  | enemy | ✓ |  |
| 8 | Envoy 1 |  |  |  |  | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Choral Chambers Above Ventrica (Song_03)](../00-annotations/choral-chambers/choral-chambers-above-ventrica-connections.png)](../00-annotations/choral-chambers/choral-chambers-above-ventrica-connections.png)

### Checks

[![Checks for Choral Chambers Above Ventrica (Song_03)](../00-annotations/choral-chambers/choral-chambers-above-ventrica-checks.png)](../00-annotations/choral-chambers/choral-chambers-above-ventrica-checks.png)

### Scene

[![Scene for Choral Chambers Above Ventrica (Song_03)](../00-annotations/choral-chambers/choral-chambers-above-ventrica-scene.png)](../00-annotations/choral-chambers/choral-chambers-above-ventrica-scene.png)
