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
| BRM | Bottom Right to Middle | Bottom Right | Middle | Swift Step OR Faydown OR Clawline OR Flea Brew OR Sharpdart |  | Verified |  |
| BRM | Bottom Right to Middle | Middle | Bottom Right | Nothing (Falling) |  | Verified |  |
| BLM | Bottom Left to Middle | Bottom Left | Middle | ((Swift Step OR Easy Beast Crest Pogo OR Clawline OR Sharpdart OR (Flea Brew AND Easy Flea Brew Stall AND Ledge Grab)) AND (Faydown OR Cling Grip OR Silk Soar)) OR (Scuttlebrace AND Swift Step) OR (Drifter's Cloak AND ((Faydown AND Enemy Pogo AND Ledge Grab) OR Silk Soar)) |  | Verified |  |
| BLM | Bottom Left to Middle | Middle | Bottom Left | Nothing (Falling) |  | Verified |  |
| MTL | Middle to Top Left | Middle | Top Left | ((Swift Step OR Easy Beast Crest Pogo OR Clawline OR Sharpdart OR (Flea Brew AND Easy Flea Brew Stall AND Ledge Grab)) AND (Faydown OR Cling Grip OR Silk Soar)) OR (Scuttlebrace AND Swift Step) OR (Drifter's Cloak AND ((Faydown AND Enemy Pogo AND Ledge Grab) OR Silk Soar)) |  | Verified |  |
| MTL | Middle to Top Left | Top Left | Middle | Swift Step OR Faydown OR Clawline OR Flea Brew OR Sharpdart OR Crest Pogo |  | Verified |  |
| TLR | Top Left to Top Right | Top Left | Top Right | ((Swift Step OR Easy Beast Crest Pogo OR Clawline OR Sharpdart OR (Flea Brew AND Easy Flea Brew Stall AND Ledge Grab)) AND (Faydown OR Cling Grip OR Silk Soar)) OR (Scuttlebrace AND Swift Step) OR (Drifter's Cloak AND ((Faydown AND Enemy Pogo AND Ledge Grab) OR Silk Soar)) |  | Verified |  |
| TLR | Top Left to Top Right | Top Right | Top Left | ((Swift Step OR Easy Beast Crest Pogo OR Clawline OR Sharpdart OR (Flea Brew AND Easy Flea Brew Stall AND Ledge Grab)) AND (Faydown OR Cling Grip OR Silk Soar)) OR (Scuttlebrace AND Swift Step) OR (Drifter's Cloak AND ((Faydown AND Enemy Pogo AND Ledge Grab) OR Silk Soar)) |  | Verified |  |
| PLT | Pit Left to Top Right | Top Right Pit (Left) | Top Right | Cling Grip OR Scuttlebrace OR Silk Soar OR (Faydown AND Ledge Grab AND (Easy Heal Stall or Easy Flea Brew Stall)) |  | Verified |  |
| PLT | Pit Left to Top Right | Top Right | Top Right Pit (Left) | Nothing (Falling) |  | Verified |  |
| PRT | Pit Right to Top RIght | Top Right Pit (Right) | Top Right | Cling Grip OR Scuttlebrace OR Faydown |  | Verified |  |
| PRT | Pit Right to Top RIght | Top Right | Top Right Pit (Right) | Nothing (Falling) |  | Verified |  |
| BRP | Bottom Right to Pit | Top Right Pit (Left) | Bottom Right | Nothing (Falling) |  | Verified |  |
| BRP | Bottom Right to Pit | Bottom Right | Top Right Pit (Left) | Lever Broken FROM Coral_02 (Top Right Pit) AND Silk Soar AND Ledge Grab |  | Verified |  |
| LPM | Left Pit to Middle | Top Right Pit (Left) | Middle | Lever Broken FROM Coral_02 (Top Right Pit) OR Easy Crest Pogo OR Clawline OR Flea Brew OR Sharpdart OR Swift Step OR Faydown |  | Verified |  |
| LPM | Left Pit to Middle | Middle | Top Right Pit (Left) | Lever Broken FROM Coral_02 (Top Right Pit) AND Faydown OR (Silk Soar AND Ledge Grab) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket: Blasted Steps | Top Right Pit (Right) | ((Swift Step OR Easy Beast Crest Pogo OR Clawline OR Sharpdart) AND (Faydown OR Cling Grip)) OR (Swift Step AND Scuttlebrace) OR (Drifter's Cloak AND (Faydown OR Silk Soar)) OR (Silk Soar AND Faydown) |  | Verified | Included |  |
| Shell Shard Cache: Blasted Steps #1 | Bottom Left | (Cling Grip AND (Swift Step OR Flea Brew OR Faydown OR Clawline)) OR (Swift Step and Scuttlebrace) |  | Verified | Included |  |
| Shell Shard Cache: Blasted Steps #2 | Bottom Left | (Cling Grip AND (Swift Step OR Flea Brew OR Faydown OR Clawline)) OR (Swift Step and Scuttlebrace) |  | Verified | Included |  |
| Shell Shard Cache: Blasted Steps #3 | Bottom Left | (Cling Grip AND (Swift Step OR Flea Brew OR Faydown OR Clawline)) OR (Swift Step and Scuttlebrace) |  | Verified | Included |  |
| Lever Coral_02 (Top Right Pit) | Top Right Pit (Left) | Nothing |  | Verified | Not included |  |
