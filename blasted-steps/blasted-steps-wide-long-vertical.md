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
| BLR | Bottom Left to Right | Bottom Third (Left) | Bottom Third (Right) | Progressive Swift Step 1 OR Faydown OR Easy Enemy Pogo OR Silk Soar OR Clawline OR (Flea Brew AND ((Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo) OR Easy Flea Brew Stall OR Ledge Grab)) |  | Verified |  |
| BLR | Bottom Left to Right | Bottom Third (Right) | Bottom Third (Left) | Progressive Swift Step 1 OR Faydown OR Easy Enemy Pogo OR Silk Soar OR Clawline OR (Flea Brew AND ((Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo) OR Easy Flea Brew Stall OR Ledge Grab)) |  | Verified |  |
| BLM | Bottom Left to Middle 1 | Bottom Third (Left) | Middle Section 1 | (Easy Enemy Pogo AND Faydown AND Ledge Grab) OR ((Progressive Swift Step 2 OR Faydown OR Clawline OR Drifter's Cloak OR Easy Enemy Pogo OR (Flea Brew AND (((Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo)) OR Easy Flea Brew Stall))) AND Cling Grip) OR (Progressive Swift Step 2 AND Scuttlebrace AND Faydown) OR Silk Soar |  | Verified |  |
| BLM | Bottom Left to Middle 1 | Middle Section 1 | Bottom Third (Left) | Nothing (Falling) |  | Verified |  |
| BRM | Bottom Right to Middle | Bottom Third (Right) | Middle Section 1 | (Easy Enemy Pogo AND Faydown AND Ledge Grab) OR ((Progressive Swift Step 2 OR Faydown OR Clawline OR Drifter's Cloak OR Easy Enemy Pogo OR (Flea Brew AND (((Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Easy Beast Crest Pogo OR Easy Architect Crest Pogo)) OR Easy Flea Brew Stall))) AND Cling Grip) OR (Progressive Swift Step 2 AND Scuttlebrace AND Faydown) OR Silk Soar |  | Verified |  |
| BRM | Bottom Right to Middle | Middle Section 1 | Bottom Third (Right) | Nothing (Falling) |  | Verified |  |
| M12 | Middle 1 to Middle 2 | Middle Section 1 | Middle Section 2 | Nothing (Jumping) |  | Verified |  |
| M12 | Middle 1 to Middle 2 | Middle Section 2 | Middle Section 1 | Nothing (Falling) |  | Verified |  |
| MLE | Middle to Middle Left | Middle Section 2 | Middle Left (Entrance) | Easy Enemy Pogo OR Silk Soar OR Progressive Swift Step 2 OR Clawline OR Sharpdart OR (Drifter's Cloak AND Ledge Grab) OR (Flea Brew AND (Cling Grip OR Easy Flea Brew Stall OR Easy Heal Stall)) |  | Verified |  |
| MLE | Middle to Middle Left | Middle Left (Entrance) | Middle Section 2 | Easy Enemy Pogo OR Progressive Swift Step 2 OR Clawline OR Sharpdart OR Drifter's Cloak OR Faydown OR Flea Brew OR Silk Soar OR ((Easy Hunter Pogo OR Easy Reaper Pogo OR Easy Beast Pogo OR Easy Architect Pogo OR Easy Shaman Pogo) AND Cling Grip) |  | Verified |  |
| MRE | Middle to Middle Right | Middle Section 2 | Middle Right (Entrance) | (Medium Proficient Movement AND Drifter's Cloak AND Progressive Swift Step 2) OR (Easy Proficient Movement AND Progressive Swift Step 2 AND Clawline AND Cling Grip AND Ledge Grab) OR (Faydown AND ((Progressive Swift Step 2 AND Ledge Grab) OR (Drifter's Cloak AND Medium Wind Skip AND Ledge Grab) OR Clawline)) OR Silk Soar |  | Verified |  |
| MRE | Middle to Middle Right | Middle Right (Entrance) | Middle Section 2 | Nothing (Falling) |  | Verified |  |
| PTB | Pit to Bottom | Pit | Bottom Third (Left) | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| PTB | Pit to Bottom | Bottom Third (Left) | Pit | Nothing (Falling) |  | Verified |  |
| MRT | Middle Right to Top | Middle Right (Entrance) | Top Third | Ledge Grab OR Cling Grip OR Faydown OR Silk Soar OR Scuttlebrace |  | Verified |  |
| MRT | Middle Right to Top | Top Third | Middle Right (Entrance) | Nothing (Falling) |  | Verified |  |
| TTE | Top Third to Entrances | Top Third | Top Third Entrances | (Ledge Grab AND (Cling Grip OR (Scuttlebrace AND Easy Proficient Movement)) AND ((Prereq Top Third Lever AND Flea Brew) OR Progressive Swift Step 2 OR Clawline)) OR Silk Soar |  | Verified |  |
| TTE | Top Third to Entrances | Top Third Entrances | Top Third | Nothing (Falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Frayed Rosary String: Blasted Steps | Pit | Nothing (Falling) |  | Verified | collectible |  |
| Top Third Lever | Top Third | (Ledge Grab AND (Cling Grip OR Scuttlebrace)) OR Faydown OR Silk Soar |  | Verified | switch |  |
