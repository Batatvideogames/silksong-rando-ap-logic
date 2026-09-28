# Underworks Lever Spike Corridor (Under_11)

**Game ID:** Under_11

**Contributors:** Rebel

## Subrooms

- Left Side Entrance
- Right Side Entrance
- Central Top Shaft
- Lever Shaft

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Side Entrance | [Underworks Central Shaft (Under_05)](underworks-central-shaft.md) | TR | Nothing. |  | Verified |  |
| R | right1 | Right Side Entrance | [Underworks East Shaft (Under_13)](underworks-east-shaft.md) | TL | Nothing. |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LC | Left-CentraL | Left Side Entrance | Central Top Shaft | Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak |  | Verified |  |
| LC | Left-CentraL | Central Top Shaft | Left Side Entrance | Nothing. (Fall) |  | Verified |  |
| RC | Right-Central | Right Side Entrance | Central Top Shaft | Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak |  | Verified |  |
| RC | Right-Central | Central Top Shaft | Right Side Entrance | Nothing. (Fall) |  | Verified |  |
| CL | Central-Lever | Central Top Shaft | Lever Shaft | Nothing. (fall) |  | Verified |  |
| CL | Central-Lever | Lever Shaft | Central Top Shaft | Activate Underworks: Flip Switch #4 AND (Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak) |  | Verified |  |
| LL | Left-Lever | Left Side Entrance | Lever Shaft | (Activate Underworks: Flip Switch #4 AND (Spike Pogo OR Dash OR Sprint OR Clawline OR Sharpdart OR Faydown Cloak OR Drifter's Cloak OR Scuttlebrace)) |  | Verified |  |
| LL | Left-Lever | Lever Shaft | Left Side Entrance | (Activate Underworks: Flip Switch #4 AND (Spike Pogo OR Dash OR Sprint OR Clawline OR Sharpdart OR Faydown Cloak OR Drifter's Cloak OR Scuttlebrace)) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Flip Switch #4 | Lever Shaft | Flip Switch Left |  | Verified | switch |  |
