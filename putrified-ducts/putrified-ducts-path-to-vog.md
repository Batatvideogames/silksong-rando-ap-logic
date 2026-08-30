# Putrified Ducts Path To Vog (Aqueduct_06)

**Game ID:** Aqueduct_06

**Contributors:** Pyxl

## Subrooms

- Main
- Camp
- Top

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | Main | [Putrified Ducts Lower Bridge Room (Aqueduct_03)](putrified-ducts-lower-bridge-room.md) | C | None |  | Verified |  |
| UL | left1 | Top | [Putrified Ducts Bellway (Bellway_Aqueduct)](putrified-ducts-bellway.md) | R | None |  | Verified |  |
| LL | left2 | Main | [Putrified Ducts Rosary Room (Aqueduct_08)](putrified-ducts-rosary-room.md) | R | None |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VA | Vine Acsent | Main | Top | ( Clawline AND ( Cling Grip OR ( Drifters Cloak AND ( Faydown Cloak OR Dash ) ) )  ) |  | Verified |  |
| VA | Vine Acsent | Top | Main | Clawline AND Faydown Cloak |  | Verified |  |
| TC | Thorn Crossing | Main | Camp | ( Faydown Cloak AND ( Hunter Crest OR Swim OR Reaper Crest OR Beast Crest OR Architect Crest OR Sprint OR Dash OR ( Ledge Grab AND Hard Skips ) ) ) OR Sharpdart OR Clawline OR Drifters Cloak OR ( Sprint AND Dash ) |  | Verified |  |
| TC | Thorn Crossing | Camp | Main | ( Faydown Cloak AND ( Hunter Crest OR Swim OR Reaper Crest OR Beast Crest OR Architect Crest OR Sprint OR Dash OR ( Ledge Grab AND Hard Skips ) ) ) OR Sharpdart OR Clawline OR Drifters Cloak OR ( Sprint AND Dash ) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| thread_memory | Camp | Needolin |  | Verified | Not included |  |
| Wreath OF Purity | Camp | None |  | Verified | Included |  |
