# Deep Docks Bellway Flea Rescue (Dock_16)

**Game ID:** Dock_16

**Contributors:** herounit and Rebel

## Subrooms

- Floor
- Upper
- Flea

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Floor | [Deep Docks Bellway (Bellway_02)](deep-docks-bellway.md) | L | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FTU | Floor <> Upper | Floor | Upper | Ledge Grab OR Cling Grip OR Faydown Cloak OR Silk Soar |  | Verified |  |
| FTU | Floor <> Upper | Upper | Floor | Nothing. (Fall) |  | Verified |  |
| UTF | Upper <> Flea | Upper | Flea | Nothing. |  | Verified |  |
| UTF | Upper <> Flea | Flea | Upper | Nothing. |  | Verified |  |
| FTF | Floor <> Flea | Floor | Flea | (Activate Flea Breakable Floor AND (Silk Soar OR (Faydown Cloak AND (Ledge Grab OR Cling Grip OR Scuttlebrace)))) |  | Verified |  |
| FTF | Floor <> Flea | Flea | Floor | Activate Flea Breakable Floor |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue bellway | Flea | Nothing. |  | Verified | collectible |  |
| flea breakable floor | Flea | Break Wall Down |  | Verified | blockade | stand on it |
