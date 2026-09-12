# Trobbio (Library_13)

**Game ID:** Library_13

**Contributors:** Rebel

## Subrooms

- Top
- Bottom Left Entrance
- Fight
- Bottom Right
- Bottom Center

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TR | right1 | Top | [Trobbio Entrance (Library_13b)](trobbio-entrance.md) | L | Nothing. |  | Verified |  |
| L | left1 | Bottom Left Entrance | [Grand Bellway Shaft (Song_20)](../choral-chambers/grand-bellway-shaft.md) | RS | Nothing. |  | Verified |  |
| BR | right2 | Bottom Right | [Vaults & Bellway Cauldron Entrance (Library_11)](../underworks/vaults-bellway-cauldron-entrance.md) | TL | Nothing. |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VR | Vertical Right | Top | Bottom Right | Activate Whispering Vaults: Flip Switch #12 |  | Verified |  |
| VR | Vertical Right | Bottom Right | Top | Activate Whispering Vaults: Flip Switch #12 AND (Cling Grip OR Scuttlebrace OR Faydown Cloak OR Clawline OR Dash OR Silk Soar OR Ledge Grab) |  | Verified |  |
| VL | Vertical Left | Top | Bottom Right | Nothing. (Fall) |  | Verified |  |
| VL | Vertical Left | Bottom Right | Top | Silk Soar OR (Faydown Cloak AND (Cling Grip OR Scuttlebrace)) |  | Verified |  |
| LL | Leave Left | Bottom Center | Bottom Left Entrance | Activate Whispering Vaults: Flip Switch #4 |  | Verified |  |
| LL | Leave Left | Bottom Left Entrance | Bottom Center | Activate Whispering Vaults: Flip Switch #4 |  | Verified |  |
| ESL | Enter Stage Left | Bottom Center | Fight | Nothing. |  | Verified |  |
| ESL | Enter Stage Left | Fight | Bottom Center | Defeat Trobbio OR (Act 3 AND Defeat Tormented Trobbio) |  | Verified |  |
| ESR | Enter Stage Right | Bottom Right | Fight | Nothing. |  | Verified |  |
| ESR | Enter Stage Right | Fight | Bottom Right | Defeat Trobbio OR (Act 3 AND Defeat Tormented Trobbio) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Progressive Claw Mirror 2 | Fight | Defeat Tormented Trobbio |  | Verified | collectible |  |
| Whispering Vaults: Lore #4 | Bottom Left Entrance | Nothing. |  | Verified | lore |  |
| Trobbio | Fight | Nothing. |  | Verified | boss |  |
| Progressive Claw Mirror 1 | Fight | Defeat Trobbio |  | Verified | collectible |  |
| Whispering Vaults: Flip Switch #4 | Bottom Center | Nothing. |  | Verified | switch |  |
| Whispering Vaults: Flip Switch #12 | Bottom Right | Nothing. |  | Verified | switch |  |
| AP Minor Cache - Whispering Vaults - Shell Shard Cache #2 | Top | Nothing. |  | Verified | resource |  |
| Tormented Trobbio | Fight | (Act 3 AND Activate Wish: Pain, Anguish and Misery IN Songclave) |  | Verified | boss |  |
