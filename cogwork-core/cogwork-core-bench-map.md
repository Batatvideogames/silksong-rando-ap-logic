# Cogwork Core Bench & Map (Cog_Bench)

**Game ID:** Cog_Bench

**Contributors:** Rebel

## Subrooms

- Bench
- Map

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Map | [Cogwork Core South Main (Cog_04)](cogwork-core-south-main.md) | DL | Nothing. |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BM | Bench-Map | Bench | Map | Silk Soar OR Cling Grip OR Scuttlebrace |  | Verified |  |
| BM | Bench-Map | Map | Bench | Nothing. (Fall) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogwork Core: Flip Switch #4 | Bench | Nothing. |  | Verified | switch |  |
| Cogwork Core: Flip Switch #5 | Map | Nothing. |  | Verified | switch |  |
| Cogwork Core: Map | Map | Activate Cogwork Core: Flip Switch #5 |  | Verified | collectible |  |
| Cogwork Core: Bench | Bench | Activate Cogwork Core: Flip Switch #4 |  | Verified | bench |  |
