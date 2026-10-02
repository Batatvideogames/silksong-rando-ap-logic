# Trobbio (Library_13)

**Game ID:** Library_13

**Contributors:** Rebel

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Top | ✓ |
| S2 | Bottom Left Entrance | ✓ |
| S3 | Fight | ✓ |
| S4 | Bottom Right | ✓ |
| S5 | Bottom Center | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TR | right1 | Top | [Trobbio Entrance (Library_13b)](trobbio-entrance.md) | L | Nothing. |  | Verified | ✓ |  |
| L | left1 | Bottom Left Entrance | [Grand Bellway Shaft (Song_20)](../choral-chambers/grand-bellway-shaft.md) | RS | Nothing. |  | Verified | ✓ |  |
| BR | right2 | Bottom Right | [Vaults & Bellway Cauldron Entrance (Library_11)](../underworks/vaults-bellway-cauldron-entrance.md) | TL | Nothing. |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| VR | Vertical Right | Top | Bottom Right | Activate Whispering Vaults: Flip Switch #12 |  | Verified | ✓ |  |
| VR | Vertical Right | Bottom Right | Top | Activate Whispering Vaults: Flip Switch #12 AND (Cling Grip OR Scuttlebrace OR Faydown Cloak OR Clawline OR Dash OR Silk Soar OR Ledge Grab) |  | Verified | ✓ |  |
| VL | Vertical Left | Top | Bottom Center | Nothing. (Fall) |  | Verified | ✓ |  |
| VL | Vertical Left | Bottom Center | Top | Silk Soar OR (Faydown Cloak AND (Cling Grip OR Scuttlebrace)) |  | Verified | ✓ |  |
| LL | Leave Left | Bottom Center | Bottom Left Entrance | Activate Whispering Vaults: Flip Switch #4 |  | Verified | ✓ |  |
| LL | Leave Left | Bottom Left Entrance | Bottom Center | Activate Whispering Vaults: Flip Switch #4 |  | Verified | ✓ |  |
| ESL | Enter Stage Left | Bottom Center | Fight | Nothing. |  | Verified | ✓ |  |
| ESL | Enter Stage Left | Fight | Bottom Center | Defeat Trobbio OR (Act 3 AND Defeat Tormented Trobbio) |  | Verified | ✓ |  |
| ESR | Enter Stage Right | Bottom Right | Fight | Nothing. |  | Verified | ✓ |  |
| ESR | Enter Stage Right | Fight | Bottom Right | Defeat Trobbio OR (Act 3 AND Defeat Tormented Trobbio) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Whispering Vaults: Lore #4 | Bottom Left Entrance | Nothing. |  | Verified | lore | ✓ |  |
| 2 | Trobbio | Fight | Nothing. |  | Verified | boss | ✓ |  |
| 3 | Progressive Claw Mirror 1 | Fight | Defeat Trobbio |  | Verified | collectible | ✓ |  |
| 4 | Whispering Vaults: Flip Switch #4 | Bottom Center | Nothing. |  | Verified | switch | ✓ |  |
| 5 | Whispering Vaults: Flip Switch #12 | Bottom Right | Nothing. |  | Verified | switch | ✓ |  |
| 6 | AP Minor Cache - Whispering Vaults - Shell Shard Cache #2 | Top | Nothing. |  | Verified | resource | ✓ |  |
| 7 | Tormented Trobbio | Fight | complete THE Pain, Anguish and Misery Wish Promised AND defeat Trobbio AND Act 3 |  | Verified | boss | ✓ |  |
| 8 | Pain, Anguish and Misery Wish Granted | Fight | Defeat Tormented Trobbio |  | Verified | event | ✓ |  |
| 9 | Progressive Claw Mirror 2 | Fight | Defeat Tormented Trobbio |  | Verified | collectible | ✓ |  |

## Room Images

### Connections

[![Connections for Trobbio (Library_13)](../00-annotations/whispering-vaults/trobbio-connections.png)](../00-annotations/whispering-vaults/trobbio-connections.png)

### Checks

[![Checks for Trobbio (Library_13)](../00-annotations/whispering-vaults/trobbio-checks.png)](../00-annotations/whispering-vaults/trobbio-checks.png)

### Scene

[![Scene for Trobbio (Library_13)](../00-annotations/whispering-vaults/trobbio-scene.png)](../00-annotations/whispering-vaults/trobbio-scene.png)
