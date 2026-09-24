# Wormways Middle (Crawl_03b)

**Game ID:** Crawl_03b

**Contributors:** herounit, cry

## Subrooms

- wormways west scaffold
- main tunnel

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | main tunnel | [Wormways Shaft (Crawl_02)](wormways-shaft.md) | LL | none |  | Verified |  |
| F | floor | main tunnel | [Wormways Lower East (Crawl_07)](wormways-lower-east.md) | C | none |  | Verified | Imported destination text: wormways lower east - C |
| C | ceiling | wormways west scaffold | [Wormways Upper West (Crawl_03)](wormways-upper-west.md) | F | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RJ | running jump | main tunnel | wormways west scaffold | (ledge grab AND (run OR dash OR faydown cloak OR drifter's cloak OR clawline OR silk soar OR sharpdart OR flea brew)) OR (run OR dash OR faydown cloak OR drifter's cloak OR clawline OR silk soar OR sharpdart OR  (cling grip AND flea brew)) OR (cling grip AND proficient movement AND (architect slash [right] OR easy shaman pogo OR flea brew)) OR easy beast pogo |  | Verified |  |
| RJ | running jump | wormways west scaffold | main tunnel | none (falling) |  | Verified |  |

## Check Locations

No check locations defined.
