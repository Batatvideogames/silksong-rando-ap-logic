# Blasted Steps Toll Bench Bottom (Coral_02)

**Game ID:** Coral_02

**Contributors:** skai

## Subrooms

- Bottom Right
- Middle
- Bottom Left
- Top Left
- Top Right
- Top Right Pit (Right)
- Top Right Pit (Left)

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BR | Bottom Right | Bottom Right | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TM | Nothing |  | Verified |  |
| TR | Top Right | Top Right | [Blasted Steps Wide Long Vertical (Coral_03)](blasted-steps-wide-long-vertical.md) | BL | Nothing |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BRM | Bottom Right to Middle | Bottom Right | Middle | (Cling Grip AND (Progressive Swift Step 1 OR Sharpdart OR Clawline OR Flea Brew)) OR Faydown OR Easy Scuttlebrace OR Silk Soar |  | Verified |  |
| BRM | Bottom Right to Middle | Middle | Bottom Right | Nothing (Falling) |  | Verified |  |
| BLM | Bottom Left to Middle | Bottom Left | Middle | (Cling Grip AND (Progressive Swift Step 1 OR Sharpdart OR Clawline OR Flea Brew)) OR Faydown OR Medium Scuttlebrace OR Silk Soar |  | Verified |  |
| BLM | Bottom Left to Middle | Middle | Bottom Left | Nothing (Falling) |  | Verified |  |
| MTL | Middle to Top Left | Middle | Top Left | (Cling Grip AND (Progressive Swift Step 1 OR Sharpdart OR Clawline OR Flea Brew)) OR Faydown OR Easy Scuttlebrace OR Silk Soar |  | Verified |  |
| MTL | Middle to Top Left | Top Left | Middle | Nothing (Fall) |  | Verified |  |
| TLR | Top Left to Top Right | Top Left | Top Right | (Cling Grip AND (Progressive Swift Step 2 OR Sharpdart OR Clawline OR (Flea Brew AND (Easy Flea Brew Stall OR Easy Heal Stall OR Ledge Grab)))) OR (Faydown AND Ledge Grab) OR Easy Scuttlebrace OR Silk Soar |  | Verified |  |
| TLR | Top Left to Top Right | Top Right | Top Left | Progressive Swift Step 2 OR Sharpdart OR Clawline OR Faydown OR (Flea Brew AND (Easy Flea Brew Stall OR Easy Heal Stall OR Ledge Grab)) |  | Verified |  |
| PLT | Pit Left to Top Right | Top Right Pit (Left) | Top Right | Cling Grip OR Scuttlebrace OR Silk Soar OR (Faydown AND Ledge Grab AND (Easy Heal Stall OR Easy Flea Brew Stall)) |  | Verified |  |
| PLT | Pit Left to Top Right | Top Right | Top Right Pit (Left) | Nothing (Falling) |  | Verified |  |
| PRT | Pit Right to Top RIght | Top Right Pit (Right) | Top Right | Cling Grip OR Scuttlebrace OR (Faydown AND Ledge Grab) |  | Verified |  |
| PRT | Pit Right to Top RIght | Top Right | Top Right Pit (Right) | Nothing (Falling) |  | Verified |  |
| BRP | Bottom Right to Pit | Top Right Pit (Left) | Bottom Right | Nothing (Falling) |  | Verified |  |
| BRP | Bottom Right to Pit | Bottom Right | Top Right Pit (Left) | (Prereq Top Right Pit Lever (Top Right Pit) OR (Faydown AND Ledge Grab)) AND Silk Soar |  | Verified |  |
| LPM | Left Pit to Middle | Top Right Pit (Left) | Middle | Prereq Top Right Pit Lever OR (Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo) OR Clawline OR Flea Brew OR Sharpdart OR Progressive Swift Step 2 OR Faydown |  | Verified | Didn't Split Sprint/Dash |
| LPM | Left Pit to Middle | Middle | Top Right Pit (Left) | (Prereq Top Right Pit Lever AND (Ledge Grab OR Faydown)) OR Silk Soar |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket: Blasted Steps | Top Right Pit (Right) | Nothing (Fall) |  | Verified | collectible |  |
| Shell Shard Cache: Blasted Steps #1 | Bottom Left | Nothing (Fall) |  | Verified | collectible |  |
| Shell Shard Cache: Blasted Steps #2 | Bottom Left | Nothing (Fall) |  | Verified | collectible |  |
| Shell Shard Cache: Blasted Steps #3 | Bottom Left | Nothing (Fall) |  | Verified | collectible |  |
| Top Right Pit Lever | Top Right Pit (Left) | Nothing |  | Verified | switch |  |
