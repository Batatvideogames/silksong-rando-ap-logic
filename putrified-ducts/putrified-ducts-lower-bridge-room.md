# Putrified Ducts Lower Bridge Room (Aqueduct_03)

**Game ID:** Aqueduct_03

**Contributors:** Pyxl

## Subrooms

- Left Exit
- Right Exit
- Ceiling Exit

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right Exit | [Fleatopia (Aqueduct_05)](fleatopia.md) | L | None |  | Verified |  |
| L | left1 | Left Exit | [Putrified Ducts Tall Room (Aqueduct_02)](putrified-ducts-tall-room.md) | LR | None |  | Verified |  |
| C | top1 | Ceiling Exit | [Putrified Ducts Path To Vog (Aqueduct_06)](putrified-ducts-path-to-vog.md) | F | Faydown Cloak OR Cling Grip OR Silk Soar OR Scuttlebrace |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AB | Across The Bridges | Left Exit | Right Exit | ( Cling Grip AND ( Clawline OR Faydown Cloak ) ) OR ( Silk Soar AND ( Drifters Cloak OR Clawline ) ) |  | Verified |  |
| AB | Across The Bridges | Right Exit | Left Exit | ( Cling Grip AND Clawline )  OR ( Silk Soar AND ( Drifters Cloak OR Clawline ) ) |  | Verified |  |
| TC | Ceiling Tunnel | Right Exit | Ceiling Exit | ( Silk Soar AND ( Faydown Cloak OR Sprint OR Dash OR Cling Grip OR Clawline OR Drifters Cloak OR Faydown Cloak OR Sharpdart ) ) OR ( Faydown Cloak AND ( Dash OR Clawline OR Sharpdart OR easy Beast Crest pogo OR Drifters Cloak ) ) OR ( Cling Grip AND Clawline ) |  | Verified |  |
| TC | Ceiling Tunnel | Ceiling Exit | Right Exit | Sprint OR Clawline OR Faydown Cloak OR ( Silk Soar AND ( Dash OR Drifters Cloak OR Cling Grip ) ) |  | Verified |  |
| SS | Silk Soar Up | Left Exit | Ceiling Exit | Silk Soar AND ( Drifters cloak OR Faydown Cloak OR Clawline ) |  | Verified |  |
| SS | Silk Soar Up | Ceiling Exit | Left Exit | Drifters Cloak OR Clawline OR ( Swim AND Faydown Cloak ) OR ( Silk Soar AND ( Dash OR Sharpdart ) ) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Breakable Wall | Right Exit | Faydown Cloak OR ( Cling Grip AND Clawline ) OR ( Silk Soar AND ( Drifters Cloak OR Dash OR Cling Grip OR Clawline OR Sharpdart OR Sprint ) ) |  | Verified | blockade |  |
