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
| Wish: Passing Of The Age | The Herald | ACT 3 AND Needolin AND ( "Ruined Chapel" In Logic AND "Bone Bottom Town" In Logic AND "Far Fields Skull Room East" In Logic AND "Greymoor_06, Top Area" In Logic AND "Slab First Sinner Antechamber" In Logic AND "Peak_08. Faythorn" In Logic AND "Path Of Pain SilkSong, Top" In Logic ) | TODO |  | event | Need room and subroom name from greymoor and the room and subroom from mount fay |
| Ecstasy of the End Wish Promised | Fleatopia | act 3 AND after THE flea caravan move to fleatopia AND silk soar AND fleas 30 |  | Verified | event | one of two places to accept this wish  spreadsheet flag is vague, so using wiki requirements |
| Ecstasy of the End Wish Granted | Fleatopia | complete Ecstasy of the End Wish Promised AND complete Flea Juggle High Score AND complete Flea Dodge High Score AND after Flea Bounce High Score |  | Verified | event |  |
| Pale Oil | Fleatopia | complete Ecstasy of the End Wish Granted |  | Verified | collectible |  |
| Fleatopia - Tool Pouch | Fleatopia | fleas 22 |  | Verified | collectible |  |
| Egg of Flealia | Fleatopia | fleas 30 |  | Verified | collectible | All fleas |
| Reached Pale Lake | Fleatopia | none |  | Verified | logic-point |  |
| Festival of the Flea | Fleatopia | complete Ecstasy of the End Wish Promised |  | Verified | logic-point |  |
| Flea Juggle High Score | Fleatopia | after Festival of the Flea |  | Verified | event | these probably need movement requirements |
| Flea Dodge High Score | Fleatopia | after Festival of the Flea |  | Verified | event | these probably need movement requirements |
| Flea Bounce High Score | Fleatopia | after Festival of the Flea |  | Verified | event | these probably need movement requirements |
| Seth Joins Festival of the Flea | Fleatopia | after THE Seth Move to Fleatopia  ACT 3  AND Defeat THE Boss Nyleth  AND ( Defeat THE Boss Crust King Khan OR Defeat THE Boss Karmelita OR Defeat THE Boss Clover Dancers )  AND "Greymoor_02" In Logic  AND "Shellwood Flower Pogo Upper Hall" In logic  AND "Grand Bridge" In Logic  AND after Ecstasy of the End Wish Granted | TODO |  | logic-point |  |
| Flea Juggle Beat Seth Score | Fleatopia | after Seth Joins Festival of the Flea |  | Verified | event | these probably need movement requirements |
| Flea Dodge Beat Seth Score | Fleatopia | after Seth Joins Festival of the Flea |  | Verified | event | these probably need movement requirements |
| Flea Bounce Beat Seth Score | Fleatopia | after Seth Joins Festival of the Flea |  | Verified | event | these probably need movement requirements |
| Gaurdians Memento | Fleatopia | complete Flea Juggle Beat Seth Score AND complete Flea Dodge Beat Seth Score AND after Flea Bounce Beat Seth Score |  | Verified | collectible |  |
