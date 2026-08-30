# Putrified Ducts Entrance (Aqueduct_01)

**Game ID:** Aqueduct_01

**Contributors:** Pyxl

## Subrooms

- Entrance
- Left Platform
- Centre Platform
- Shell Shards bridge
- Exit
- Rosary String Ledge

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Exit | [Putrified Ducts Tall Room (Aqueduct_02)](putrified-ducts-tall-room.md) | UL | None |  | Verified |  |
| L | left1 | Entrance | Arborium_11 | R | None | TODO | Verified | Memorium has not been done yet |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EC | Entrance Cave | Entrance | Left Platform | Faydown Cloak AND ( CLing Grip OR Scuttlebrace ) |  | Verified |  |
| EC | Entrance Cave | Left Platform | Entrance | ( Faydown Cloak AND Cling Grip ) OR ( Silk Soar AND ( Dash OR Clawline OR Sharpdart OR Faydown Cloak OR Drifters Cloak ) ) |  | Verified |  |
| LBB | Left Broken Bridge | Left Platform | Centre Platform | Dash OR Faydown Cloak OR ( ( Cling Grip OR Ledge Grab ) AND ( Sprint OR Clawline OR Sharp Dart ) ) |  | Verified |  |
| LBB | Left Broken Bridge | Centre Platform | Left Platform | Faydown Cloak OR Clawline OR Sprint OR ( Drifters Cloak AND Easy Skips ) OR Silk Soar OR ( Cling Grip AND Dash ) |  | Verified |  |
| UB | Under The Bridge | Centre Platform | Shell Shards bridge | ( Easy Skips AND ( Ledge Grab OR Drifters Cloak OR Hunters Crest OR Beast Crest OR Architect Crest OR  Shaman Crest OR Clawline OR  Dash OR Sharpdart ) ) OR Faydown Cloak OR Cling Grip OR Scuttlebrace |  | Verified |  |
| UB | Under The Bridge | Shell Shards bridge | Centre Platform | ( Faydown Cloak AND ( Cling Grip OR Clawline OR Sprint OR Scuttlebrace OR Drifters Cloak OR Sharpdart ) ) |  | Verified |  |
| OB | Over The Bridge | Centre Platform | Exit | Clawline OR Drifters Cloak OR Silk Soar OR ( Faydown Cloak AND ( Cling Grip OR Dash OR Sprint ) ) OR ( Swim AND Dash AND Cling Grip ) |  | Verified |  |
| OB | Over The Bridge | Exit | Centre Platform | Dash OR Faydown Cloak OR Run OR Drifters Cloak OR Cling Grip OR Silk Soar OR Clawline OR Sharpdart |  | Verified |  |
| UE | Under The Exit | Exit | Rosary String Ledge | None |  | Verified |  |
| UE | Under The Exit | Rosary String Ledge | Exit | Faydown Cloak OR Silk Soar OR ( ( Dash OR Cling Grip ) AND ( Clawline OR Drifters Cloak OR Sharpdart OR Sprint ) ) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Putrified Ducts - Shell Shard Cache #1 | Shell Shards bridge | None |  | Verified | Included | Merge Map icons on map |
| Putrified Ducts - Shell Shard Cache #2 | Shell Shards bridge | None |  | Verified | Included | Merge Map icons on map |
| Putrified Ducts - Frayed Rosary String | Rosary String Ledge | None |  | Verified | Included |  |
