# Whiteward Unravelled Arena Room (Ward_02)

**Game ID:** Ward_02

**Contributors:** skai

## Subrooms

- Vertical Left
- Surgery Tables (Right)
- Surgery Tables (Left)
- Key Shaft
- Unravelled Arena

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | Top | Vertical Left | [Whiteward Tunnel Room (Ward_02b)](whiteward-tunnel-room.md) | B | Silk Soar OR Faydown OR Cling Grip OR Scuttlebrace |  | Verified |  |
| R | Right | Surgery Tables (Right) | [Whiteward Entrance (Ward_01)](whiteward-entrance.md) | BL | Nothing |  | Verified |  |
| B | Bottom | Unravelled Arena | [Confession Toll (Under_08)](../underworks/confession-toll.md) | T | Defeat The Unravelled Gauntlet |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SLV | Surgery Left to Vertical | Surgery Tables (Left) | Vertical Left | Ledge Grab OR Faydown OR Clawline OR Silk Soar OR (Easy Proficient Movement AND Scuttlebrace) |  | Verified |  |
| SLV | Surgery Left to Vertical | Vertical Left | Surgery Tables (Left) | Nothing (Falling) |  | Verified |  |
| SRL | Surgery Right to Left | Surgery Tables (Right) | Surgery Tables (Left) | Nothing |  | Verified |  |
| SRL | Surgery Right to Left | Surgery Tables (Left) | Surgery Tables (Right) | Nothing |  | Verified |  |
| SKS | Surgery to Key Shaft | Surgery Tables (Left) | Key Shaft | Have Surgeon's Key |  | Verified |  |
| SKS | Surgery to Key Shaft | Key Shaft | Surgery Tables (Left) | Have Surgeon's Key AND Silk Soar |  | Verified |  |
| KSA | Key Shaft to Arena | Key Shaft | Unravelled Arena | Nothing (Falling) |  | Verified |  |
| KSA | Key Shaft to Arena | Unravelled Arena | Key Shaft | Have Surgeon's Key AND Silk Soar |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| The Unravelled - Silk Heart | Unravelled Arena | Defeat Boss: The Unravelled |  | Verified | collectible |  |
| The Unravelled Gauntlet | Unravelled Arena | Nothing |  | Verified | gauntlet |  |
| Boss: The Unravelled | Unravelled Arena | Defeat The Unravelled Gauntlet |  | Verified | boss |  |
