# Songclave Steam Tunnel (Library_02)

**Game ID:** Library_02

**Contributors:** Rebel

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Top | ✓ |
| S2 | Bottom Left | ✓ |
| S3 | Arena | ✓ |
| S4 | Bottom Right | ✓ |
| S5 | Upper Blocks | ✓ |
| S6 | Lower Blocks | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | left2 | Top | [Rotating Tunnel (Song_20b)](../choral-chambers/rotating-tunnel.md) | R1 | Nothing. |  | Verified | ✓ |  |
| TR | right2 | Top | [Songclave (Song_Enclave)](../choral-chambers/songclave.md) | BL | Nothing. |  | Verified | ✓ |  |
| BL | left1 | Bottom Left | [Rotating Tunnel (Song_20b)](../choral-chambers/rotating-tunnel.md) | RH | Nothing. |  | Verified | ✓ |  |
| BR | right1 | Bottom Right | [Whispering Vaults Flea Shaft (Library_01)](whispering-vaults-flea-shaft.md) | TL | Nothing. |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LV | Left Vertical | Upper Blocks | Arena | (Faydown Cloak AND Spike Pogo (except Witch) AND Ledge Grab) OR (Cling Grip AND (Spike Pogo OR Dash OR Sprint OR Clawline OR Drifter's Cloak OR Sharpdart)) OR (Scuttlebrace AND (Faydown Cloak OR (Dash AND Ledge Grab) OR Clawline OR Sharpdart OR Easy Beast Crest Pogo)) |  | Verified | ✓ |  |
| RV | Right Vertical | Bottom Right | Arena | Silk Soar OR Cling Grip OR (Scuttlebrace AND Faydown Cloak) |  | Verified | ✓ |  |
| LV | Left Vertical | Arena | Upper Blocks | Spike Pogo OR Proficient Movement (Easy Box Pogo) OR Clawline OR Faydown Cloak OR Drifter's Cloak OR Sharpdart |  | Verified | ✓ |  |
| RV | Right Vertical | Arena | Bottom Right | Nothing. (Fall) |  | Verified | ✓ |  |
| LBL | Lower Block Left Travel | Bottom Left | Lower Blocks | Nothing |  | Verified | ✓ |  |
| LBL | Lower Block Left Travel | Lower Blocks | Bottom Left | Nothing |  | Verified | ✓ |  |
| LBR | Lower Block Right Travel | Lower Blocks | Bottom Right | Activate Logic Box |  | Verified | ✓ |  |
| LBR | Lower Block Right Travel | Bottom Right | Lower Blocks | Activate Logic Box |  | Verified | ✓ |  |
| VBT | Lower <> Upper Block | Lower Blocks | Upper Blocks | Silk Soar OR (Proficient Movement (Box Pogo) AND Faydown Cloak AND Ledge Grab) OR Cling Grip OR ((Scuttlebrace AND (Faydown Cloak OR Clawline OR Sharpdart OR ((Drifter's Cloak OR Dash) AND Ledge Grab)))) OR (Activate Logic Box AND (Faydown Cloak)) |  | Verified | ✓ |  |
| VBT | Lower <> Upper Block | Upper Blocks | Lower Blocks | Nothing. (Fall) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Whispering Vaults: Arena #1 | Arena | Nothing. |  | Verified | gauntlet | ✓ |  |
| 2 | Logic Box | Bottom Right | Attack Right OR Attack Left |  | Verified | logic-point | ✓ | < add predicate |

## Notes

No connection from Top to the rest of the subrooms.

## Room Images

### Connections

[![Connections for Songclave Steam Tunnel (Library_02)](../00-annotations/whispering-vaults/songclave-steam-tunnel-connections.png)](../00-annotations/whispering-vaults/songclave-steam-tunnel-connections.png)

### Checks

[![Checks for Songclave Steam Tunnel (Library_02)](../00-annotations/whispering-vaults/songclave-steam-tunnel-checks.png)](../00-annotations/whispering-vaults/songclave-steam-tunnel-checks.png)

### Scene

[![Scene for Songclave Steam Tunnel (Library_02)](../00-annotations/whispering-vaults/songclave-steam-tunnel-scene.png)](../00-annotations/whispering-vaults/songclave-steam-tunnel-scene.png)
