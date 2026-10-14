# Slab Cell (Slab_03)

**Game ID:** Slab_03

**Contributors:** MayaXTG

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Arena | ✓ |
| S2 | Why | ✓ |
| S3 | L1 | ✓ |
| S4 | Indolent | ✓ |
| S5 | Grindle | ✓ |
| S6 | Flea1 | ✓ |
| S7 | Cavern | ✓ |
| S8 | Heretic Bridge | ✓ |
| S9 | L4 | ✓ |
| S10 | Flea2 | ✓ |
| S11 | Cave | ✓ |
| S12 | Prelude | ✓ |
| S13 | Poodle | ✓ |
| S14 | Lowest | ✓ |

- **L1:** entrances to secret side and chilly prison
- **L4:** slab entrance and infleatween top
- **Prelude:** to first sinner

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CPT | door_slabCaged | L1 | [Slab Capture](../fast-travel/slab-capture.md) | CG | invalid |  |  | ✓ | no destination, logically equivalent to L1 since you need to go up to reach L0 |
| ARN | left1 | Arena | [Slab Arena (Slab_16)](slab-arena.md) | R | none |  |  | ✓ |  |
| WHY | right1 | Why | [Slab Why Room (Slab_17)](slab-why-room.md) | L | unlock apostate door mask shard |  |  | ✓ |  |
| CHL | left2 | L1 | [Slab Chilly Prison (Slab_15)](slab-chilly-prison.md) | R | none |  |  | ✓ |  |
| SCR | right2 | L1 | [Slab Secret Side Room (Slab_18)](slab-secret-side-room.md) | L | clear Breakable Wall Blockade IN slab secret side room |  |  | ✓ | One way (opens from the other side) |
| IND | left3 | Indolent | [Slab Indolent Room (Slab_14)](slab-indolent-room.md) | R | none |  |  | ✓ |  |
| GRN | right3 | Grindle | [Slab Grindle (Slab_20)](slab-grindle.md) | L | none |  |  | ✓ |  |
| FL1 | left4 | Flea1 | [Slab Flea Prison (Slab_13)](slab-flea-prison.md) | R | none |  |  | ✓ |  |
| CVN | right4 | Cavern | [Slab Cavern Exit (Slab_23)](slab-cavern-exit.md) | L | none |  |  | ✓ |  |
| F2T | left5 | L4 | [Slab Infleatween Top (Slab_04)](slab-infleatween-top.md) | R | none |  |  | ✓ |  |
| ENT | right5 | L4 | [Slab Entrance (Slab_02)](slab-entrance.md) | L | activate slab entrance switch IN slab entrance |  |  | ✓ |  |
| F2B | left6 | Flea2 | [Slab Infleatween Bottom (Slab_05)](slab-infleatween-bottom.md) | R | have Key of Apostate |  |  | ✓ |  |
| CAV | right8 | Cave | [Slab Cave Entrance (Slab_08)](slab-cave-entrance.md) | L | none |  |  | ✓ |  |
| PRL | right7 | Prelude | [Slab Prelude (Slab_19b)](slab-prelude.md) | L | unlock heretic door first sinner |  |  | ✓ |  |
| PDT | left7 | Poodle | [Slab Poodle (Slab_07)](slab-poodle.md) | R1 | clear Exit Breakable Wall Blockade IN slab poodle |  |  | ✓ |  |
| PDB | left8 | Lowest | [Slab Poodle (Slab_07)](slab-poodle.md) | R2 | none |  |  | ✓ |  |
| WND | right9 | Lowest | [Slab Window (Slab_12)](slab-window.md) | L | break wall right |  |  | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L0 | L0 - L0 | Arena | Why | ledge grab OR cling grip |  |  |  | Naked |
| 0L1 | L0l - L1 | Arena | L1 | none |  |  |  | falling |
| 0R1 | L0R - L1 | Why | L1 | none |  |  |  | falling |
| 0L1 | L0l - L1 | L1 | Arena | cling grip OR silk soar |  |  |  | Naked |
| 0R1 | L0R - L1 | L1 | Why | cling grip OR silk soar |  |  |  | Naked |
| 2L1 | L2L - L1 | Indolent | L1 | cling grip OR silk soar |  |  |  | Naked. One way only |
| 2R1 | L2R - L1 | Grindle | L1 | cling grip OR silk soar |  |  |  | Naked. One way only |
| L2 | L2 - L2 | Indolent | Grindle | ledge grab OR silk soar |  |  |  | Naked |
| L2 | L2 - L2 | Grindle | Indolent | ledge grab OR silk soar |  |  |  | Naked |
| 2FL | L2L to L3L | Indolent | Flea1 | none |  |  |  | falling |
| 2FR | L2L to L3R | Indolent | Cavern | none |  |  |  | falling |
| 2DL | L2R to L3L | Grindle | Flea1 | none |  |  |  | falling |
| 2DR | L2R to L3R | Grindle | Cavern | none |  |  |  | falling |
| L3 | L3 - L3 | Flea1 | Cavern | cling grip OR silk soar OR dash |  |  |  | Naked. When you are still naked the bridge should be closed enabling you to just walk over it but added prior transitions to still have a valid path. |
| BR1 | Bridge1 | Flea1 | Heretic Bridge | have Key of Heretic |  |  |  |  |
| BR2 | Bridge2 | Cavern | Heretic Bridge | have Key of Heretic |  |  |  |  |
| BL4 | Bridge to L4 | Heretic Bridge | L4 | none |  |  |  | falling, one way lever |
| 5R4 | L5R to L4 | Cave | L4 | cling grip |  |  |  | one way lever |
| 5L4 | L5L to L4 | Flea2 | L4 | cling grip AND faydown |  |  |  | one way lever |
| L5 | L5 | Flea2 | Cave | (dash AND ledge grab) OR faydown OR clawline OR cling grip |  |  |  |  |
| L5 | L5 | Cave | Flea2 | ledge grab OR faydown OR clawline OR dash |  |  |  |  |
| 5LF | L5L to L6 | Flea2 | Prelude | none |  |  |  | falling |
| 5LF | L5L to L6 | Prelude | Flea2 | (cling grip OR silk soar) AND (ledge grab OR faydown OR clawline OR dash) |  |  |  |  |
| 5RF | L5R to L6 | Cave | Prelude | none |  |  |  | falling |
| 5RF | L5R to L6 | Prelude | Cave | cling grip OR silk soar |  |  |  |  |
| L6F | L6 to L8 | Prelude | Lowest | swim |  |  |  | L7 is non existant until opened |
| L7F | L7 to L8 | Poodle | Lowest | swim |  |  |  | falling |
| L7U | L7 to L6 | Poodle | Prelude | cling grip |  |  |  |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | poodle blockade |  |  |  |  | blockade | ✓ |  |
| 2 | heretic lever upper |  |  |  |  | switch | ✓ |  |
| 3 | heretic lever lower |  |  |  |  | switch | ✓ |  |
| 4 | apostate door mask shard | Why | have key of apostate |  |  | lock |  |  |
| 5 | heretic door first sinner | Prelude | have key of heretic |  |  | lock |  |  |
| 6 | Guardfly 1 |  |  |  |  | enemy | ✓ |  |
| 7 | Guardfly 2 |  |  |  |  | enemy | ✓ |  |

## Notes

I'll go over this when I'm more sane

## Room Images

### Connections

[![Connections for Slab Cell (Slab_03)](../00-annotations/the-slab/slab-cell-connections.png)](../00-annotations/the-slab/slab-cell-connections.png)

### Checks

[![Checks for Slab Cell (Slab_03)](../00-annotations/the-slab/slab-cell-checks.png)](../00-annotations/the-slab/slab-cell-checks.png)

### Scene

[![Scene for Slab Cell (Slab_03)](../00-annotations/the-slab/slab-cell-scene.png)](../00-annotations/the-slab/slab-cell-scene.png)
