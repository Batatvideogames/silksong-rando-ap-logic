# Greymoor Rat Tunnel (Greymoor_16)

**Game ID:** Greymoor_16

**Contributors:** skai AND Isssma

## Subrooms

- Top Left Shaft (Upper)
- Top Left Shaft (Center)
- Top Left Shaft (bottom)
- Top Right Section (Upper)
- Top Right Section (Center)
- Top Right Section (Bottom)
- bellway secret entrance
- bottom section left
- bottom section right

- **bottom section right:** fat fuck rat inside

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | Top Left Shaft (Center) | [Greymoor Entry to Bellhart (Greymoor_08)](greymoor-entry-to-bellhart.md) | R | nothing |  | Verified |  |
| T | Top | bellway secret entrance | [Greymoor Bellway (Bellway_04)](greymoor-bellway.md) | D | nothing |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PG1 | platform gap 1 | Top Left Shaft (Center) | Top Left Shaft (Upper) | ledge grab OR silk soar OR faydown cloak OR cling grip OR easy scuttlebrace OR (easy enemy pogo AND (clawline OR progressive swift step 1 OR sharpdart OR drifters cloak OR easy beast pogo OR easy shaman pogo OR easy hunter pogo OR easy architect pogo OR easy reaper pogo)) |  | Verified |  |
| PG1 | platform gap 1 | Top Left Shaft (Upper) | Top Left Shaft (Center) | nothing (just fall) |  | Verified |  |
| PG2 | platform gap 2 | Top Left Shaft (Center) | Top Left Shaft (bottom) | nothing (just fall) |  | Verified |  |
| PG2 | platform gap 2 | Top Left Shaft (bottom) | Top Left Shaft (Center) | ledge grab OR silk soar OR faydown cloak OR cling grip OR easy scuttlebrace OR medium enemy pogo OR easy  shaman pogo OR easy beast pogo OR easy reaper pogo |  | Verified |  |
| S1 | shaft 1 | Top Left Shaft (Center) | Top Right Section (Center) | clear tied blockade |  | Verified |  |
| S1 | shaft 1 | Top Right Section (Center) | Top Left Shaft (Center) | clear tied blockade AND (cling grip OR easy scuttlebrace OR silksoar OR (faydown cloak AND (ledge grab OR medium shaman pogo))) |  | Verified |  |
| PG3 | platform gap 3 | Top Right Section (Center) | Top Right Section (Bottom) | nothing (just fall) |  | Verified |  |
| PG3 | platform gap 3 | Top Right Section (Bottom) | Top Right Section (Center) | faydown cloak OR silk soar OR cling grip OR ledge grab OR (easy scuttlebrace AND drifters cloak) OR medium enemy pogo |  | Verified |  |
| PG4 | platform gap 4 | Top Right Section (Center) | Top Right Section (Upper) | cling grip OR faydown cloak OR silk soar OR ledge grab |  | Verified |  |
| PG4 | platform gap 4 | Top Right Section (Upper) | Top Right Section (Center) | nothing (jsut fall) |  | Verified |  |
| F1 | fall 1 | Top Right Section (Bottom) | bottom section right | nothing (just fall) |  | Verified |  |
| F1 | fall 1 | bottom section right | Top Right Section (Bottom) | hard enemy pogo AND faydown cloak |  | Verified |  |
| SG | swimming gap | bottom section right | bottom section left | (swim AND (ledge grab OR faydown cloak OR cling grip)) OR (clawline AND faydown cloak AND drifters cloak) |  | Verified |  |
| SG | swimming gap | bottom section left | bottom section right | swim OR ((clawline OR sharpdart) AND (faydown cloak OR drifters cloak)) OR (faydown cloak AND progressive swift step 2 AND drifters cloak) OR (clawline AND hard beast pogo) |  | Verified |  |
| F2 | fall 2 | Top Left Shaft (bottom) | bottom section left | open airlock left OR open airlock right OR open airlock up |  | Verified |  |
| F2 | fall 2 | bottom section left | Top Left Shaft (bottom) | (open airlock left OR open airlock right OR open airlock up) AND (progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR easy beast pogo OR drifters cloak) |  | Verified |  |
| BW | breakable wall | Top Right Section (Center) | bellway secret entrance | break wall right OR break wall up |  | Verified |  |
| BW | breakable wall | bellway secret entrance | Top Right Section (Center) | break wall left OR break wall up |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Breakable wooden Wall | Top Right Section (Bottom) | break wall right OR break wall up |  | Verified | blockade |  |
| Greymoor - Shell Shard Cache #1 | bottom section right | none |  | Verified | resource |  |
| Greymoor - Shell Shard Cache #2 | bottom section right | none |  | Verified | resource |  |
| Greymoor - Memory Locket | Top Right Section (Upper) | none |  | Verified | collectible |  |
| Greymoor - Cage Record | Top Left Shaft (Upper) | nothing |  | Verified | lore |  |
| Greymoor - Rosary Cache #23 | Top Right Section (Bottom) | clear Breakable wooden Wall |  | Verified | resource |  |
| Greymoor - Rosary Cache #24 | Top Right Section (Bottom) | clear Breakable wooden Wall |  | Verified | resource |  |
| Greymoor - Rosary Cache #25 | Top Right Section (Bottom) | clear Breakable wooden Wall |  | Verified | resource |  |
| tied blockade | Top Left Shaft (Center) | break switch left OR break switch up OR break switch right |  | Verified | blockade |  |
