# Deep Docks Diving Bell Room (Dock_12)

**Game ID:** Dock_12

**Contributors:** herounit & Pyxl

## Subrooms

- diving bell platform
- diving bell control room

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 | diving bell platform | [Deep Docks Diving Bell Interior (Room_Diving_Bell)](deep-docks-diving-bell-interior.md) | L | unlock diving bell lock |  | Verified |  |
| L | left1 | diving bell platform | [Deep Docks Magma Slug Tunnels (Dock_11)](deep-docks-magma-slug-tunnels.md) | R | none |  | Verified | transition is not blocked by door in next room |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CL | climb | diving bell platform | diving bell control room | silk soar OR cling grip OR scuttlebrace |  | Verified |  |
| CL | climb | diving bell control room | diving bell platform | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| diving bell lock | diving bell platform | have diving bell key |  | Verified | lock |  |
| diving bell key | diving bell control room | after Ballow in Diving Bell Control Room |  | Verified | collectible |  |
| Ballow in Diving Bell Control Room | diving bell control room | complete THE Ballow Move to Control Room |  | Verified | event |  |

## Notes

dive bell thingy room wow.
