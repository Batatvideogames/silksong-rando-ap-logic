# Blasted Steps Wide Long Vertical (Coral_03)

**Game ID:** Coral_03

**Contributors:** skai

## Subrooms

- Pit
- Bottom Third (Left)
- Bottom Third (Right)
- Middle Left (Entrance)
- Middle Right (Entrance)
- Middle Section 1
- Middle Section 2
- Top Third Entrances
- Top Third

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bottom Left | Bottom Third (Left) | [Blasted Steps Toll Bench Bottom (Coral_02)](blasted-steps-toll-bench-bottom.md) | TR | Nothing |  | Verified |  |
| B3 | Bottom (3) | Pit | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TR3 | Nothing |  | Verified |  |
| B4 | Bottom (4) | Pit | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TR4 | Nothing |  | Verified |  |
| B5 | Bottom (5) | Pit | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TR5 | Nothing |  | Verified |  |
| B6 | Bottom (6) | Pit | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TR6 | Nothing |  | Verified |  |
| B7 | Bottom (7) | Pit | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TR7 | Nothing |  | Verified |  |
| B8 | Bottom (8) | Pit | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TR8 | Nothing |  | Verified |  |
| BR | Bottom Right | Bottom Third (Right) | [Blasted Steps Shakra Room (Coral_12)](blasted-steps-shakra-room.md) | BL | Nothing |  | Verified |  |
| ML | Middle Left | Middle Left (Entrance) | [Great Conchflies (Coral_11)](great-conchflies.md) | R | Nothing |  | Verified |  |
| MR | Middle Right | Middle Right (Entrance) | [Blasted Steps Shakra Room (Coral_12)](blasted-steps-shakra-room.md) | TL | Nothing |  | Verified |  |
| TR | Top Right | Top Third Entrances | [Pre Last Judge Room (Coral_32)](pre-last-judge-room.md) | L | Nothing |  | Verified |  |
| TL | Top Left | Top Third Entrances | [Blasted Steps Bellway (Bellway_08)](blasted-steps-bellway.md) | R | Nothing |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLR | Bottom Left to Right | Bottom Third (Left) | Bottom Third (Right) | Swift Step OR Faydown OR Enemy Pogo OR Silk Soar OR Clawline OR (Flea Brew AND (Easy Crest Pogo OR Easy Flew Brew Stall)) |  | Verified |  |
| BLR | Bottom Left to Right | Bottom Third (Right) | Bottom Third (Left) | Swift Step OR Faydown OR Enemy Pogo OR Silk Soar OR Clawline OR (Flea Brew AND (Easy Crest Pogo OR Easy Flew Brew Stall)) |  | Verified |  |
| BLM | Bottom Left to Middle 1 | Bottom Third (Left) | Middle Section 1 | (Easy Enemy Pogo AND Faydown AND Ledge Grab) OR ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR Easy Enemy Pogo OR (Flea Brew AND (Easy Crest Pogo OR Easy Flea Brew Stall))) AND Cling Grip) OR (Swift Step AND Scuttlebrace AND Faydown) OR Silk Soar |  | Verified |  |
| BLM | Bottom Left to Middle 1 | Middle Section 1 | Bottom Third (Left) | Nothing (Falling) |  | Verified |  |
| BRM | Bottom Right to Middle | Bottom Third (Right) | Middle Section 1 | (Easy Enemy Pogo AND Faydown AND Ledge Grab) OR ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR Easy Enemy Pogo OR (Flea Brew AND (Easy Crest Pogo OR Easy Flea Brew Stall))) AND Cling Grip) OR (Swift Step AND Scuttlebrace AND Faydown) OR Silk Soar |  | Verified |  |
| BRM | Bottom Right to Middle | Middle Section 1 | Bottom Third (Right) | Nothing (Falling) |  | Verified |  |
| M12 | Middle 1 to Middle 2 | Middle Section 1 | Middle Section 2 | Nothing (Jumping) |  | Verified |  |
| M12 | Middle 1 to Middle 2 | Middle Section 2 | Middle Section 1 | Nothing (Falling) |  | Verified |  |
| MLE | Middle to Middle Left | Middle Section 2 | Middle Left (Entrance) | Easy Enemy Pogo OR Silk Soar OR Swift Step OR Clawline OR Sharpdart OR (Drifter's Cloak AND Ledge Grab) OR (Flea Brew AND (Cling Grip OR Easy Flea Brew Stall OR Easy Heal Stall)) |  | Verified |  |
| MLE | Middle to Middle Left | Middle Left (Entrance) | Middle Section 2 | Easy Enemy Pogo OR Swift Step OR Clawline OR Sharpdart OR Drifter's Cloak OR Faydown OR Flea Brew OR Silk Soar OR (Easy Crest Pogo (Hunter, Reaper, Beast, Architect, Shaman) AND Cling Grip) |  | Verified |  |
| MRE | Middle to Middle Right | Middle Section 2 | Middle Right (Entrance) | (Moderate Skip AND Drifter's Cloak AND Swift Step) OR (Easy Skip AND Swift Step AND Clawline AND Cling AND Ledge Grab) OR (Faydown AND ((Swift Step AND Ledge Grab) OR (Easy Skip AND Drifter's Cloak AND Wind AND Ledge Grab) OR Clawline)) OR Silk Soar |  | Verified |  |
| MRE | Middle to Middle Right | Middle Right (Entrance) | Middle Section 2 | Nothing (Falling) |  | Verified |  |
| PTB | Pit to Bottom | Pit | Bottom Third (Left) | Cling Grip OR Scuttle OR Silk Soar |  | Verified |  |
| PTB | Pit to Bottom | Bottom Third (Left) | Pit | Nothing (Falling) |  | Verified |  |
| MRT | Middle Right to Top | Middle Right (Entrance) | Top Third | Ledge Grab OR Cling Grip OR Faydown OR Silk Soar OR Scuttle |  | Verified |  |
| MRT | Middle Right to Top | Top Third | Middle Right (Entrance) | Nothing (Falling) |  | Verified |  |
| TTE | Top Third to Entrances | Top Third | Top Third Entrances | (Ledge Grab AND (Cling Grip OR (Scuttlebrace AND Easy Skip)) AND ((Lever BROKEN From Coral_03 (Top Third) AND Flea Brew) OR Swift Step OR Clawline)) OR Silk Soar |  | Verified |  |
| TTE | Top Third to Entrances | Top Third Entrances | Top Third | Nothing (Falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Frayed Rosary String: Blasted Steps | Pit | Nothing (Falling) |  | Verified |  |  |
| Lever Coral_03 (Top Third) | Top Third | Ledge Grab AND (Cling Grip OR Scuttlebrace) OR Faydown OR Silk Soar |  | Verified |  |  |
