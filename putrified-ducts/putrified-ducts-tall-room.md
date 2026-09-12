# Putrified Ducts Tall Room (Aqueduct_02)

**Game ID:** Aqueduct_02

**Contributors:** Pyxl

## Subrooms

- Top Left
- Bellway Door
- Middle Platform
- Lower Sewage Tunnel

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | Top Left | [Putrified Ducts Entrance (Aqueduct_01)](putrified-ducts-entrance.md) | R | None |  | Verified |  |
| UR | right2 | Bellway Door | [Putrified Ducts Bellway (Bellway_Aqueduct)](putrified-ducts-bellway.md) | L | None |  | Verified |  |
| ML | left3 | Middle Platform | [Putrified Ducts Map Room (Aqueduct_07)](putrified-ducts-map-room.md) | R | None |  | Verified |  |
| MR | right3 | Middle Platform | [Putrified Ducts Rosary Room (Aqueduct_08)](putrified-ducts-rosary-room.md) | L | Prereq Breakable Sewer Grate 2 IN Putrified Ducts Rosary Room |  | Verified |  |
| LL | left2 | Lower Sewage Tunnel | [Putrified Ducts Connection To Bilewater (Aqueduct_04)](putrified-ducts-connection-to-bilewater.md) | R | Prereq Breakable Sewer Grate |  | Verified |  |
| LR | right1 | Lower Sewage Tunnel | [Putrified Ducts Lower Bridge Room (Aqueduct_03)](putrified-ducts-lower-bridge-room.md) | L | None |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| UG | Upper Gap | Top Left | Bellway Door | Ledge Grab OR Dash OR Cling Grip OR Drifters Cloak OR Faydown Cloak OR Silk Soar OR Clawline OR Sharpdart OR Scuttlebrace OR easy Hunter Crest pogo OR easy Reaper Crest pogo OR easy Beast Crest pogo OR easy Witch Crest pogo OR easy Architect Crest pogo OR easy Shaman Crest pogo OR ( easy Needle Strike stall AND easy Wanderer Crest pogo ) |  | Verified |  |
| UG | Upper Gap | Bellway Door | Top Left | Faydown Cloak OR Cling Grip OR Silk Soar OR Scuttlebrace |  | Verified |  |
| TS | The Shaft | Top Left | Middle Platform | None |  | Verified |  |
| TS | The Shaft | Middle Platform | Top Left | Cling Grip OR Silk Soar OR Faydown CLoak OR ( Scuttlebrace AND ( Clawline OR Ledge Grab ) ) |  | Verified |  |
| TS2 | The Shaft 2 | Bellway Door | Middle Platform | None |  | Verified |  |
| TS2 | The Shaft 2 | Middle Platform | Bellway Door | Cling Grip OR Silk Soar OR Faydown CLoak OR ( Scuttlebrace AND ( Clawline OR Ledge Grab ) ) |  | Verified |  |
| TT | The Tunnel | Middle Platform | Lower Sewage Tunnel | None |  | Verified |  |
| TT | The Tunnel | Lower Sewage Tunnel | Middle Platform | Silk Soar OR ( Faydown Cloak AND ( Cling Grip OR Scuttlebrace ) ) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Breakable Sewer Grate | Lower Sewage Tunnel | None |  | Verified | blockade |  |
