# Deep Docks Entrance (Dock_08)

**Game ID:** Dock_08

**Contributors:** herounit and Rebel

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | main pathway | ✓ |
| S2 | gauntlet left | ✓ |
| S3 | gauntlet | ✓ |
| S4 | gauntlet right | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left2 | gauntlet left | [The Marrow Lava Docks (Bone_09)](../the-marrow/the-marrow-lava-docks.md) | UR | none |  | Verified | ✓ |  |
| LL | left1 | main pathway | [The Marrow Lava Docks (Bone_09)](../the-marrow/the-marrow-lava-docks.md) | LR | none |  | Verified | ✓ |  |
| R | right1 | main pathway | [Deep Docks Bench Shaft (Dock_01)](deep-docks-bench-shaft.md) | L | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | main pathway | gauntlet right | Activate Deep Docks Entrance Lever AND (Ledge Grab OR Faydown Cloak OR Easy Scuttlebrace OR Easy Shaman Crest Pogo OR Easy Needle Strike Stall (Beast)) |  | Verified | ✓ |  |
| DS | door switch | gauntlet right | main pathway | Activate Deep Docks Entrance Lever |  | Verified | ✓ |  |
| GL | gauntlet fight left | gauntlet left | gauntlet | Nothing. |  | Verified | ✓ |  |
| GL | gauntlet fight left | gauntlet | gauntlet left | Defeat Deep Docks Entrance Battle |  | Verified | ✓ |  |
| GR | gauntlet fight right | gauntlet | gauntlet right | Defeat Deep Docks Entrance Battle |  | Verified | ✓ |  |
| GR | gauntlet fight right | gauntlet right | gauntlet | Activate Deep Docks Entrance Lever |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Deep Docks Entrance Lever | gauntlet right | Flip Switch Right |  | Verified | switch | ✓ |  |
| 2 | Deep Docks Entrance Battle | gauntlet | Nothing. |  | Verified | gauntlet | ✓ |  |
| 3 | Deep Docks Entrance - Mask Shard | gauntlet right | Nothing. |  | Verified | collectible | ✓ |  |

## Room Images

### Connections

[![Connections for Deep Docks Entrance (Dock_08)](../00-annotations/deep-docks/deep-docks-entrance-connections.png)](../00-annotations/deep-docks/deep-docks-entrance-connections.png)

### Checks

[![Checks for Deep Docks Entrance (Dock_08)](../00-annotations/deep-docks/deep-docks-entrance-checks.png)](../00-annotations/deep-docks/deep-docks-entrance-checks.png)

### Scene

[![Scene for Deep Docks Entrance (Dock_08)](../00-annotations/deep-docks/deep-docks-entrance-scene.png)](../00-annotations/deep-docks/deep-docks-entrance-scene.png)
