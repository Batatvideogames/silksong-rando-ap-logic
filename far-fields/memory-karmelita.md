# Memory Karmelita (Memory_Ant_Queen)

**Game ID:** Memory_Ant_Queen

**Contributors:** herounit

## Subrooms

- entrance
- arena

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MG | door_wakeInMemory | entrance | [Current Karmelita (Ant_Queen)](current-karmelita.md) | MG | none |  | Verified | just walk left to leave |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AP | arena passage | entrance | arena | silk soar OR faydown cloak |  | Verified |  |
| AP | arena passage | arena | entrance | silk soar OR ( faydown cloak AND ledge grab ) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| skarrsinger karmelita boss fight | arena | none |  | Verified | boss |  |
| hunter's heart | arena | defeat skarrsinger karmelita boss fight |  | Verified | collectible |  |
