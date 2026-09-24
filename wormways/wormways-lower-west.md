# Wormways Lower West (Crawl_09)

**Game ID:** Crawl_09

**Contributors:** herounit, cry

## Subrooms

- left exit shaft
- right exit tunnel
- upper tunnels
- lower tunnels
- right exit basement
- pilgrim tomb

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right exit tunnel | [Wormways Lower East (Crawl_07)](wormways-lower-east.md) | L | none |  | Verified |  |
| L | left | left exit shaft | [Wormways Zango Arena (Crawl_10)](wormways-zango-arena.md) | R | break wall {left] OR break wall {right |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LC | left climb | left exit shaft | upper tunnels | spike pogo AND (silk soar OR cling grip OR scuttlebrace) |  | Verified |  |
| LC | left climb | upper tunnels | left exit shaft | cling grip OR faydown cloak OR easy architect pogo OR easy shaman pogo OR easy reaper pogo OR easy beast pogo OR (scuttlebrace AND spike pogo) |  | Verified |  |
| RC | right climb | right exit tunnel | right exit basement | none (falling) |  | Verified |  |
| RC | right climb | right exit basement | right exit tunnel | cling grip OR scuttlebrace OR easy enemy pogo |  | Verified |  |
| TS | tunnel shaft | lower tunnels | upper tunnels | silk soar OR scuttlebrace OR cling grip |  | Verified |  |
| TS | tunnel shaft | upper tunnels | lower tunnels | none (falling) |  | Verified |  |
| TC | tunnel connector | right exit tunnel | upper tunnels | none |  | Verified |  |
| TC | tunnel connector | upper tunnels | right exit tunnel | none |  | Verified |  |
| PC | pilgrim crevace | lower tunnels | pilgrim tomb | spike pogo OR dash OR faydown cloak |  | Verified |  |
| PC | pilgrim crevace | pilgrim tomb | lower tunnels | cling grip OR scuttlebrace OR faydown cloak |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| wormways memory locket | pilgrim tomb | none |  | Verified | collectible |  |
| plasmium bud lower west | left exit shaft | complete THE alchemist's assistant wish promised  AND needle phial |  | Verified | collectible |  |
| Breakable Mid Wall | upper tunnels | needle {right} OR needle {left} |  | Verified | blockade | the area behind this wall will remain in the dark until broken |
| plasmid upper | upper tunnels | act 3 |  | Verified | enemy | location per the wiki |
| plasmified blood upper | upper tunnels | needle phial AND defeat plasmid upper |  | Verified | resource |  |
| plasmid lower | lower tunnels | act 3 |  | Verified | enemy | location per the wiki; two spawn points in this subroom |
| plasmified blood lower | lower tunnels | needle phial AND defeat plasmid lower |  | Verified | resource |  |
| plasmid east | right exit basement | act 3 |  | Verified | enemy | location per the wiki |
| plasmified blood east | right exit basement | needle phial AND defeat plasmid east |  | Verified | resource |  |

## Notes

this one seems a bit tricky, but also it's just a bit late
i think you need cling grip to from any one point to another in here
TODO: review the mapping in here
cry: wasn't sure how to mark the second markable wall in this room, there's one at the left exit and one right before the climb connecting to the tunnel network -- the full area behind this second wall is left in the dark until that wall is broken; worth noting since you will have to navigate to it blindly in future room rando if you first enter this room from the left entrance
