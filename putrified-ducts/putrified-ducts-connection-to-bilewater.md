# Putrified Ducts Connection To Bilewater (Aqueduct_04)

**Game ID:** Aqueduct_04

**Contributors:** Pyxl

## Subrooms

- Bilewater Entrance
- Putrified Ducts Entrance
- Shell Shard Platform
- Apostate Key Area
- Lower Shell Ledge
- Hut Door
- Hub Area
- Upper Platform

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Putrified Ducts Entrance | [Putrified Ducts Tall Room (Aqueduct_02)](putrified-ducts-tall-room.md) | LL | None |  | Verified |  |
| D | door1 | Hut Door | [Huntress (Room_Huntress)](huntress.md) | L | None |  | Verified |  |
| F | bot1 | Bilewater Entrance | [Bilewater Upper Bloatroach Tower (Shadow_01)](../bilewater/bilewater-upper-bloatroach-tower.md) | C | None |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PDE | Putrified Ducts Entrance | Putrified Ducts Entrance | Hub Area | "Breakable wall from Ducts" Broken From Putrified Ducts Entrance |  | Verified |  |
| PDE | Putrified Ducts Entrance | Hub Area | Putrified Ducts Entrance | "Breakable wall from Ducts" Broken From Putrified Ducts Entrance |  | Verified |  |
| BWE | Bilewater Entrance | Bilewater Entrance | Hub Area | "Breakable Floor From Bilewater" Broken From Bilewater Entrance AND ( Silk Soar OR ( Faydown Cloak AND ( Cling Grip OR Scuttlebrace ) ) ) |  | Verified |  |
| BWE | Bilewater Entrance | Hub Area | Bilewater Entrance | "Breakable Floor From Bilewater" Broken From Bilewater Entrance |  | Verified |  |
| RS | Right Steps | Hub Area | Upper Platform | Silk Soar OR Faydown Cloak OR Cling Grip OR Scuttlebrace OR ( Ledge Grab AND ( Shaman crest OR Hard Skips ) ) |  | Verified |  |
| RS | Right Steps | Upper Platform | Hub Area | None |  | Verified |  |
| KV | Kidnap Vines | Upper Platform | Shell Shard Platform | None |  | Verified |  |
| KV | Kidnap Vines | Shell Shard Platform | Upper Platform | None |  | Verified |  |
| BG | Gap Slightly too big to jump across | Upper Platform | Apostate Key Area | Dash OR Sprint OR Clawline OR Sharpdart OR Beast Crest OR Faydown Cloak OR Drifters Cloak OR Hunter Crest OR Architect Crest OR ( Ledge Grab AND ( Needle strike AND Wanderer Crest ) OR Hard skips ) |  | Verified |  |
| BG | Gap Slightly too big to jump across | Apostate Key Area | Upper Platform | Dash OR Sprint OR Clawline OR Sharpdart OR Beast Crest OR Faydown Cloak OR Drifters Cloak OR Hunter Crest OR Architect Crest OR ( Ledge Grab AND ( Needle strike AND Wanderer Crest ) OR Hard skips ) |  | Verified |  |
| MLL | Maggot Lake Left | Upper Platform | Lower Shell Ledge | Clawline OR ( Drifters Cloak AND ( Ledge Grab OR Dash OR Faydown Cloak OR Beast Crest OR Sharpdart ) ) OR ( Swim AND ( Ledge Grab OR Dash OR Faydown Cloak OR Cling Grip OR Shaman Crest OR ( Beast Crest AND Hard Skips ) ) ) OR ( Sprint AND Dash ) OR Sharpdart |  | Verified |  |
| MLL | Maggot Lake Left | Lower Shell Ledge | Upper Platform | Cling Grip AND Clawline AND Faydown Cloak |  | Verified |  |
| MLR | Maggot Lake Right | Upper Platform | Hut Door | Drifters Cloak OR Faydown Cloak OR Swim OR Clawline OR ( Sprint AND Dash ) OR Sharpdart |  | Verified |  |
| MLC | Maggot Lake Centre | Lower Shell Ledge | Hut Door | Clawline OR Swim OR ( Faydown Cloak AND Drifters Cloak ) OR ( Sprint AND Drifters Cloak ) |  | Verified |  |
| MLC | Maggot Lake Centre | Hut Door | Lower Shell Ledge | Clawline OR ( Swim AND ( Ledge Grab OR Dash OR Faydown Cloak OR Cling Grip OR Shaman Crest OR ( Beast Crest AND Hard Skips ) ) )  OR ( Faydown Cloak AND Drifters Cloak ) OR ( Sprint AND Drifters Cloak ) |  | Verified |  |
| HH | Hut to HUB | Hut Door | Hub Area | "Breakable Wall From Hut Door" Broken From Hut Door AND ( ( Faydown Cloak AND ( Cling Grip OR Scuttlebrace ) ) OR ( Silk Soar AND ( Sprint OR Dash OR Clawline OR Sharpdart OR Beast Crest  OR Drifters Cloak OR Faydown Cloak ) ) |  | Verified |  |
| HH | Hut to HUB | Hub Area | Hut Door | "Breakable Wall From Hut Door" Broken From Hut Door AND ( Swim OR Sprint OR Dash OR Drifters Cloak OR Faydown Cloak OR Clawline OR Sharpdart OR Hunters Crest OR Beast Crest OR Architect Crest OR ( Needle strike AND Wanderer Crest AND Ledge Grab ) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Breakable Wall From Ducts | Putrified Ducts Entrance | None |  | Verified | Included |  |
| Breakable Floor From Bilewater | Bilewater Entrance | None |  | Verified | Included |  |
| Breakable Wall From Hut Door | Hut Door | None |  | Verified | Included |  |
| Putrified Ducts - Shell Shard Cache #3 | Lower Shell Ledge | None |  | Verified | Included |  |
| Putrified Ducts - Shell Shard Cache #4 | Lower Shell Ledge | None |  | Verified | Included |  |
| Putrified Ducts - Shell Shard Cache #5 | Lower Shell Ledge | None |  | Verified | Included |  |
| Putrified Ducts - Shell Shard Cache #6 | Shell Shard Platform | None |  | Verified | Included |  |
| Putrified Ducts - Shell Shard Cache #7 | Shell Shard Platform | None |  | Verified | Included |  |
| Key of Apostate | Apostate Key Area | None |  | Verified | Included |  |
