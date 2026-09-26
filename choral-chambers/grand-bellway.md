# Grand Bellway (Bellway_City)

**Game ID:** Bellway_City

**Contributors:** samupo

## Subrooms

- Base
- Secret Tunnel

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Secret Tunnel | [Vaults & Bellway Cauldron Entrance (Library_11)](../underworks/vaults-bellway-cauldron-entrance.md) | HL |  | TODO |  |  |
| L | left1 | Base | [Grand Bellway Shaft (Song_20)](grand-bellway-shaft.md) | BR | none |  | Verified |  |
| BW | door_fastTravelExit | Base | [Bellway Menu](../fast-travel/bellway-menu.md) | GB | unlock Bellway: Grand Bellway |  | Verified |  |
| VT | door_tubeEnter | Base | [Ventrica Menu](../fast-travel/ventrica-menu.md) | GB | unlock Ventrica: Grand Bellway |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Secret Tunnel | Base | none |  |  | falling, one sided door |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket: Choral Chambers | Secret Tunnel | none |  | Verified | collectible | breakable wall |
| Map Purchase: Choral Chambers | Base | rosaries 70 |  | Verified | collectible | one of two possible locations - hero, 9/26 |
| Ventrica: Grand Bellway Rosary Lock | Base | rosaries 80 |  | Verified | lock |  |
| Ventrica: Grand Bellway | Base | Unlock Ventrica: Grand Bellway Rosary Lock |  | Verified | travel |  |
| Bellway: Grand Bellway Rosary Lock | Base | rosaries 80 |  | Verified | lock |  |
| Bellway: Grand Bellway | Base | Unlock Bellway Grand Bellway Rosary Lock |  | Verified | travel |  |
