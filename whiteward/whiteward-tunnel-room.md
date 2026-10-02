# Whiteward Tunnel Room (Ward_02b)

**Game ID:** Ward_02b

**Contributors:** skai

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Top Horizontal | ✓ |
| S2 | Pickup Section | ✓ |
| S3 | Lower Tunnels | ✓ |
| S4 | Upper Tunnels | ✓ |
| S5 | Center Tunnels | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | Bottom | Lower Tunnels | [Whiteward Unravelled Arena Room (Ward_02)](whiteward-unravelled-arena-room.md) | T | Nothing |  | Verified | ✓ |  |
| R | Right | Pickup Section | [Whiteward Entrance (Ward_01)](whiteward-entrance.md) | ML | Break Wall Left |  | Verified | ✓ | There are four walls. |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LUT | Lower to Upper Tunnels | Lower Tunnels | Upper Tunnels | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified | ✓ |  |
| LUT | Lower to Upper Tunnels | Upper Tunnels | Lower Tunnels | Nothing (Falling) |  | Verified | ✓ |  |
| UCT | Upper to Center Tunnels | Center Tunnels | Upper Tunnels | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified | ✓ |  |
| UCT | Upper to Center Tunnels | Upper Tunnels | Center Tunnels | Nothing (Falling) |  | Verified | ✓ |  |
| CTH | Center to Top Horizontal | Center Tunnels | Top Horizontal | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified | ✓ |  |
| CTH | Center to Top Horizontal | Top Horizontal | Center Tunnels | Nothing (Falling) |  | Verified | ✓ |  |
| TTP | Top to Pickup Section | Top Horizontal | Pickup Section | Nothing (Falling) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Relic: Choral Commandment (Western Whiteward) | Pickup Section | Nothing |  | Verified | collectible | ✓ |  |

## Room Images

### Scene

[![Scene for Whiteward Tunnel Room (Ward_02b)](../00-annotations/whiteward/whiteward-tunnel-room-scene.png)](../00-annotations/whiteward/whiteward-tunnel-room-scene.png)

### Connections

[![Connections for Whiteward Tunnel Room (Ward_02b)](../00-annotations/whiteward/whiteward-tunnel-room-connections.png)](../00-annotations/whiteward/whiteward-tunnel-room-connections.png)

### Checks

[![Checks for Whiteward Tunnel Room (Ward_02b)](../00-annotations/whiteward/whiteward-tunnel-room-checks.png)](../00-annotations/whiteward/whiteward-tunnel-room-checks.png)
