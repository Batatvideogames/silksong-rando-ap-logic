# Pre Last Judge Room (Coral_32)

**Game ID:** Coral_32

**Contributors:** skai

## Subrooms

- Ascension
- Intermission
- Descent
- Top (Entrance)
- Right (Entrance)
- Top Vertical Shaft
- Top Right
- Left (Entrance)

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | Left (Entrance) | [Blasted Steps Wide Long Vertical (Coral_03)](blasted-steps-wide-long-vertical.md) | TR | Nothing |  | Verified |  |
| T | Top | Top (Entrance) | [Sands of Karak Elevator to Blasted Steps (Coral_38)](../sands-of-karak/sands-of-karak-elevator-to-blasted-steps.md) | F | BROKEN Wall from Coral_38 Side |  | Verified |  |
| R | Right | Right (Entrance) | [Last Judge Arena (Coral_Judge_Arena)](last-judge-arena.md) | L | Nothing |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LTA | Left to Ascension | Left (Entrance) | Ascension | Nothing |  | Verified |  |
| LTA | Left to Ascension | Ascension | Left (Entrance) | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  | Verified |  |
| ATI | Ascension to Intermission | Ascension | Intermission | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  | Verified |  |
| ATI | Ascension to Intermission | Intermission | Ascension | Nothing (Fall) |  | Verified |  |
| ITR | Intermission to Top Right | Intermission | Top Right | Nothing (Fall) |  | Verified |  |
| ITR | Intermission to Top Right | Top Right | Intermission | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  | Verified |  |
| TRD | Top Right to Descent | Top Right | Descent | Nothing (Fall) |  | Verified |  |
| TRD | Top Right to Descent | Descent | Top Right | (Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND (Ledge Grab OR Easy Hazard Respawn)) AND Cling Grip |  | Verified |  |
| TRV | Top Right to Top Vertical | Top Right | Top Vertical Shaft | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  | Verified |  |
| TRV | Top Right to Top Vertical | Top Vertical Shaft | Top Right | Nothing (Fall) |  | Verified |  |
| VTE | Top Vertical to Top (Entrance) | Top Vertical Shaft | Top (Entrance) | Cling Grip OR Silk Soar |  | Verified |  |
| VTE | Top Vertical to Top (Entrance) | Top (Entrance) | Top Vertical Shaft | Nothing (Fall) |  | Verified |  |
| TRE | Top Right to Right (Entrance) | Top Right | Right (Entrance) | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  | Verified |  |
| TRE | Top Right to Right (Entrance) | Right (Entrance) | Top Right | Nothing (Fall) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Craftmetal: Blasted Steps | Descent | Swift Step OR Faydown OR Clawline OR Drifter's Cloak |  | Verified | Included |  |
