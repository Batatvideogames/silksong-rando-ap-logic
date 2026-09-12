# Fleatopia (Aqueduct_05)

**Game ID:** Aqueduct_05

**Contributors:** Pyxl

## Subrooms

- Entrance
- Fleatopia
- The Herald
- Craftmetal
- Upper Ledge

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Entrance | [Putrified Ducts Lower Bridge Room (Aqueduct_03)](putrified-ducts-lower-bridge-room.md) | R | None |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MP | Maggot Puddle | Entrance | Fleatopia | Swim OR Clawline OR Drifters Cloak OR ( Sprint AND Dash ) OR Sharpdart |  | Verified |  |
| MP | Maggot Puddle | Fleatopia | Entrance | ( Swim AND Cling Grip ) OR ( Faydown cloak AND ( Clawline OR ( Sprint AND Dash ) ) ) |  | Verified |  |
| PL1 | Pale Lake1 | Fleatopia | Craftmetal | Swim AND Faydown Cloak AND ( Cling Grip OR Scuttlebrace ) |  | Verified |  |
| PL1 | Pale Lake1 | Craftmetal | Fleatopia | Swim |  | Verified |  |
| PL2 | Pale Lake2 | Fleatopia | Upper Ledge | Swim AND ( Cling Grip OR Scuttlebrace ) |  | Verified |  |
| PL2 | Pale Lake2 | Upper Ledge | Fleatopia | Clawline OR ( Drifters Cloak AND Sprint AND Faydown Cloak ) |  | Verified |  |
| HS | Hidden Shaft | Upper Ledge | The Herald | Silk Soar |  | Verified |  |
| HS | Hidden Shaft | The Herald | Upper Ledge | None |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Putrified Ducts - Craft Metal | Craftmetal | None |  | Verified | collectible |  |
| Putrified Ducts - Shell Shard Cache #9 | Upper Ledge | Faydown Cloak OR Clawline OR ( Sprint AND Dash ) OR SharpDart |  | Verified | resource |  |
| Putrified Ducts - Shell Shard Cache #10 | Upper Ledge | Faydown Cloak OR Clawline OR ( Sprint AND Dash ) OR SharpDart |  | Verified | resource |  |
| Putrified Ducts - Shell Shard Cache #11 | Upper Ledge | Faydown Cloak OR Clawline OR ( Sprint AND Dash ) OR SharpDart |  | Verified | resource |  |
| Putrified Ducts - Shell Shard Cache #8 | Fleatopia | Silk Soar |  | Verified | resource |  |
| Putrified Ducts - White Lake Waver Sign | Fleatopia | Needolin |  | Verified | lore | Missable / no check |
| Wish: Passing Of The Age | The Herald | ACT 3 AND Needolin AND ( "Ruined Chapel" In Logic AND "Bone Bottom Town" In Logic AND "Far Fields Skull Room East" In Logic AND "Greymoor_06, Top Area" In Logic AND "Slab First Sinner Antechamber" In Logic AND "Peak_08. Faythorn" In Logic AND "Path Of Pain SilkSong, Top" In Logic ) |  | Verified | event | Need room and subroom name from greymoor and the room and subroom from mount fay |
| Wish: Ecstasy of the end | Fleatopia | ACT 3 AND Beat all 3 highscores in the festival minigames |  | Verified | event |  |
| Gaurdians Memento | Fleatopia | ACT 3 AND Nyleth Defeated AND ( Crust King Khan Defeated OR Karmelita Defeated OR Clover Dancers Defeated ) AND "Greymoor_02" In Logic AND "Shellwood Flower Pogo Upper Hall" In logic AND "Grand Bridge" In Logic AND Beat All of Seths Highscores in Festival |  | Verified | collectible |  |
| Pale Oil | Fleatopia | Prereq Wish: Ecstasy of the end |  | Verified | collectible |  |
| Egg of Flealia | Fleatopia | fleas 30 |  | Verified | collectible | All fleas |
| Fleatopia - Tool Pouch | Fleatopia | fleas 22 |  | Verified | collectible |  |
