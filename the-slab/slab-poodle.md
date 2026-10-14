# Slab Poodle (Slab_07)

**Game ID:** Slab_07

**Contributors:** MayaXTG

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | bottom right | ✓ |
| S2 | bottom | ✓ |
| S3 | top right | ✓ |
| S4 | top left | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R1 | right1 | top right | [Slab Cell (Slab_03)](slab-cell.md) | PDT | none |  | Verified | ✓ |  |
| R2 | right2 | bottom right | [Slab Cell (Slab_03)](slab-cell.md) | PDB | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BB | Bottom | bottom right | bottom | swim AND (clawline right x 1 OR sharpdart x 1) AND hit left |  | Verified | ✓ |  |
| BB | Bottom | bottom | bottom right | swim AND (clawline left x 1 OR sharpdart x 1) AND hit right |  | Verified | ✓ |  |
| TB | Top | bottom | top right | ((faydown cloak AND (cling grip left OR scuttlebrace)) OR (silk soar AND (clawline right x 1 OR sharpdart x 1))) AND hit up |  | Verified | ✓ |  |
| TB | Top | top right | bottom | hit down |  | Verified | ✓ |  |
| VL | vertical left | bottom | top left | ((faydown cloak AND (cling grip left OR scuttlebrace)) OR (silk soar AND (clawline right x 1 OR sharpdart x 1))) AND hit up |  |  |  | temporary fix until maya can review; better than what was here - hero, 10/13 |
| VL | vertical left | top left | bottom | none (falling) |  |  |  |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Exit Breakable Wall Blockade | top right | break wall right |  | Verified | blockade | ✓ |  |
| 2 | Snitchfly 1 | top left | none |  | Verified | enemy | ✓ |  |
| 3 | Snitchfly 2 | top left | none |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Slab Poodle (Slab_07)](../00-annotations/the-slab/slab-poodle-connections.png)](../00-annotations/the-slab/slab-poodle-connections.png)

### Checks

[![Checks for Slab Poodle (Slab_07)](../00-annotations/the-slab/slab-poodle-checks.png)](../00-annotations/the-slab/slab-poodle-checks.png)

### Scene

[![Scene for Slab Poodle (Slab_07)](../00-annotations/the-slab/slab-poodle-scene.png)](../00-annotations/the-slab/slab-poodle-scene.png)
