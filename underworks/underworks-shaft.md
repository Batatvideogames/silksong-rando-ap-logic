# Underworks Shaft (Under_02)

**Game ID:** Under_02

**Contributors:** samupo

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Underground |  |
| S2 | Bottom |  |
| S3 | Lever |  |
| S4 | Mid |  |
| S5 | Top |  |
| S6 | Overtop |  |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R4 | right1 | Overtop | [Underworks Outside Choral Chambers (Under_07c)](underworks-outside-choral-chambers.md) | L | none | TODO |  | ✓ |  |
| R3 | right2 | Top | [Underworks Western Gauntlet (Under_07)](underworks-western-gauntlet.md) | L | none | TODO |  | ✓ |  |
| R2 | right3 | Mid | [Underworks Saw Intro (Under_03b)](underworks-saw-intro.md) | L | none | TODO |  | ✓ |  |
| L2 | left3 | Mid | [Underworks Map Room (Under_16)](underworks-map-room.md) | R | none | TODO |  | ✓ |  |
| L1 | left1 | Bottom | [Broken Elevator (Under_01b)](broken-elevator.md) | R | must be opened from the other side | TODO |  | ✓ |  |
| R1 | right4 | Underground | [Underworks Delver's Drill (Under_14)](underworks-delver-s-drill.md) | L | none | TODO |  | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Reaching Bottom Lever | Bottom | Lever | silk soar OR (cling grip AND (ledge grab OR faydown cloak OR clawline)) |  |  |  |  |
| LM | Lever to Mid | Lever | Mid | cling grip OR silk soar |  |  |  |  |
| TOT | Top to Overtop | Top | Overtop | cling grip OR faydown cloak OR silk soar |  |  |  |  |
| UG | Coming form Underground | Underground | Bottom | been able to reach top and  (faydown cloak and cling grip) or (silk soar and ((dash and ledge grab) or cling grip or clawline) | TODO |  |  | Hard to verify because of the difficult geometry |
| UGL | Underground Level | Top | Underground | none |  |  |  | Hitting the lever will let you go all the way down to the underground |
| FOT | Falling from Overtop | Overtop | Top | none |  |  |  | falling |
| FT | Falling from Top | Top | Mid | none |  |  |  | falling |
| FT2 | Falling from Top 2 | Top | Lever | none |  |  |  | falling. It's not done from Mid, since there would be a wall if you haven't cleared it. |
| FL | Falling from Lever | Lever | Bottom | none |  |  |  | falling |

## Check Locations

No check locations defined.

## Room Images

### Scene

[![Scene for Underworks Shaft (Under_02)](../00-annotations/underworks/underworks-shaft-scene.png)](../00-annotations/underworks/underworks-shaft-scene.png)

### Connections

[![Connections for Underworks Shaft (Under_02)](../00-annotations/underworks/underworks-shaft-connections.png)](../00-annotations/underworks/underworks-shaft-connections.png)

### Checks

[![Checks for Underworks Shaft (Under_02)](../00-annotations/underworks/underworks-shaft-checks.png)](../00-annotations/underworks/underworks-shaft-checks.png)
