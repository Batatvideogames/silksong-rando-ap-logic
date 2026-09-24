# Bilewater Mothleaf Hall (Shadow_27)

**Game ID:** Shadow_27

**Contributors:** Herchey and Sherma (he was very helpful)

## Subrooms

- left
- right
- center ground
- behind wall

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left | [Bilewater Upper East Column (Shadow_26)](bilewater-upper-east-column.md) | UR | none |  | Verified |  |
| R | right | behind wall | [Bilewater East Bench (Shadow_08)](bilewater-east-bench.md) | L | none |  | Verified | Only opens when breaking the left wall in shadow_08 |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LC | left to center | left | center ground | swim OR (clawline OR enemy pogo) |  | Verified |  |
| LC | left to center | center ground | left | swim OR (clawline OR enemy pogo) |  | Verified |  |
| RC | right to center | right | center ground | (drifter's cloak OR faydown cloak OR clawline OR sharpdart) OR swim |  | Verified |  |
| RC | right to center | center ground | right | (drifter's cloak OR faydown cloak OR clawline OR sharpdart) OR swim |  | Verified |  |
| RW | right to wall | right | behind wall | prereq Bilewater East - Breakable Wall |  | Verified |  |
| RW | right to wall | behind wall | right | prereq Bilewater East - Breakable Wall |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bilewater East - Memory Locket | right | none |  | Verified | collectible |  |
| Bilewater East - Breakable Wall | behind wall | prereq Bilewater East Bench Left Exit Wall IN Bilewater East Bench |  | Verified | blockade |  |
