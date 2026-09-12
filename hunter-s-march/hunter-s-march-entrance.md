# Hunter's March Entrance (Ant_02)

**Game ID:** Ant_02

**Contributors:** herounit

## Subrooms

- before door
- after door
- checks alcove

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | before door | [The Marrow Jail Pathway (Bone_08)](../the-marrow/the-marrow-jail-pathway.md) | MR | none |  | Verified |  |
| R | right1 | after door | [Hunter's March Pogo Intro (Ant_03)](hunter-s-march-pogo-intro.md) | L | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FG | fight grunt | before door | after door | defeat grunt fight |  | Verified |  |
| FG | fight grunt | after door | before door | defeat grunt fight |  | Verified |  |
| LG | ledge grab | after door | checks alcove | ledge grab OR faydown cloak OR silk soar |  | Verified |  |
| LG | ledge grab | checks alcove | after door | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache hunter's march 1 | checks alcove | none |  | Verified | collectible | MARKED AS ??? ON TRACKER |
| shell shard cache hunter's march 2 | checks alcove | none |  | Verified | collectible | MARKED AS ??? ON TRACKER |
| grunt fight | before door | none |  | Verified | miniboss |  |
