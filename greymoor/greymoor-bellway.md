# Greymoor Bellway (Bellway_04)

**Game ID:** Bellway_04

**Contributors:** Isssma

## Subrooms

- upper entrance
- lower passage
- bellway zone

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | upper entrance | [Greymoor Towers Patio (Greymoor_05)](greymoor-towers-patio.md) | LR | none |  | Verified |  |
| BW | Bellway | bellway zone | [Greymoor Bellway (Bellway_04)](greymoor-bellway.md) | BW | prereq Greymoor - Bellway |  | Verified |  |
| D | down | lower passage | [Greymoor Rat Tunnel (Greymoor_16)](greymoor-rat-tunnel.md) | T | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PG1 | platform gap 1 | upper entrance | bellway zone | nothing |  | Verified |  |
| PG1 | platform gap 1 | bellway zone | upper entrance | ledge grab OR cling grip OR silk soar OR faydown cloak OR easy scuttlebrace |  | Verified |  |
| HP | hidden passage | bellway zone | lower passage | break wall left |  | Verified |  |
| HP | hidden passage | lower passage | bellway zone | break wall right AND (ledge grab OR faydown cloak OR easy scuttlebrace OR cling grip) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Bellway | bellway zone | none |  | Verified | travel |  |
