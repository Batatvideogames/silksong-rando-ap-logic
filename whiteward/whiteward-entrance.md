# Whiteward Entrance (Ward_01)

**Game ID:** Ward_01

**Contributors:** skai

## Subrooms

- Top Third
- Middle Third (Left)
- Middle Third (Right)
- Bottom Third (Left)
- Elevator Shaft
- Vertical Shaft (Upper)
- Vertical Shaft (Lower)
- Pit
- Top Right (Entrance)

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | Top Left | Top Third | [Choral Chambers Eastern Shaft (Song_05)](../choral-chambers/choral-chambers-eastern-shaft.md) | R1 | Nothing |  | Verified |  |
| TR | Top Right | Top Right (Entrance) | [Whiteward Long Horizontal (Ward_05)](whiteward-long-horizontal.md) | L | Nothing |  | Verified |  |
| ML | Middle Left | Middle Third (Left) | [Whiteward Tunnel Room (Ward_02b)](whiteward-tunnel-room.md) | R | Nothing |  | Verified |  |
| MR | Middle Right | Middle Third (Right) | [Whiteward Silkeater (Ward_04)](whiteward-silkeater.md) | L | Break Wall Left |  | Verified |  |
| BL | Bottom Left | Bottom Third (Left) | [Whiteward Unravelled Arena Room (Ward_02)](whiteward-unravelled-arena-room.md) | R | Nothing |  | Verified |  |
| BR | Bottom Right | Vertical Shaft (Lower) | [Whiteward Descent Connection (Ward_03)](whiteward-descent-connection.md) | L | Nothing |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TES | Top to Elevator Shaft | Top Third | Elevator Shaft | Have White Key |  | Verified |  |
| TES | Top to Elevator Shaft | Elevator Shaft | Top Third | Have White Key |  | Verified |  |
| EBL | Elevator to Bottom Left | Elevator Shaft | Bottom Third (Left) | Have White Key |  | Verified |  |
| EBL | Elevator to Bottom Left | Bottom Third (Left) | Elevator Shaft | Have White Key |  | Verified |  |
| MLR | Middle Left to Right | Middle Third (Left) | Middle Third (Right) | Nothing (Jump) |  | Verified |  |
| MLR | Middle Left to Right | Middle Third (Right) | Middle Third (Left) | Nothing (Jump) |  | Verified |  |
| RVL | Right to Vertical Lower | Middle Third (Right) | Vertical Shaft (Lower) | Nothing (Fall) |  | Verified |  |
| RVL | Right to Vertical Lower | Vertical Shaft (Lower) | Middle Third (Right) | Cling Grip OR (Scuttlebrace AND (Medium Flea Brew Stall OR Medium Heal Stall OR Faydown)) OR Silk Soar |  | Verified |  |
| RVU | Right to Vertical Upper | Middle Third (Right) | Vertical Shaft (Upper) | Silk Soar OR (Faydown AND Cling Grip AND Easy Proficient Movement) |  | Verified |  |
| RVU | Right to Vertical Upper | Vertical Shaft (Upper) | Middle Third (Right) | Nothing (Fall) |  | Verified |  |
| VTR | Vertical to Top Right (Entrance) | Vertical Shaft (Upper) | Top Right (Entrance) | Silk Soar OR (Faydown AND Cling Grip AND Easy Proficient Movement) |  | Verified |  |
| VTR | Vertical to Top Right (Entrance) | Top Right (Entrance) | Vertical Shaft (Upper) | Nothing (Fall) |  | Verified |  |
| ETP | Elevator to Pit | Elevator Shaft | Pit | Have White Key |  | Verified |  |
| ETP | Elevator to Pit | Pit | Elevator Shaft | (Cling Grip OR Scuttlebrace OR Silk Soar) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whiteward - Spool Fragment | Pit | Nothing |  | Verified | collectible |  |
| Whiteward Bench | Top Third | Have White Key |  | Verified | bench |  |
| Whiteward - Map Purchase | Vertical Shaft (Lower) | Nothing |  | Verified | collectible |  |
| Set Elevator to Top | Top Third | Nothing |  | Verified | event | Does this need to be defined? |
