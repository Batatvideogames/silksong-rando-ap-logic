# Wormways Shaft (Crawl_02)

**Game ID:** Crawl_02

**Contributors:** herounit, cry

## Subrooms

- entrance tunnel
- middle platform area
- upper platform area
- mask grotto
- rosary duct

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | entrance tunnel | [Wormways Craggler Hallway (Crawl_04)](wormways-craggler-hallway.md) | L | none |  | Verified |  |
| LL | lower left | entrance tunnel | [Wormways Middle (Crawl_03b)](wormways-middle.md) | R | prereq use simple key on lock |  | Verified |  |
| UL | upper left | upper platform area | [Wormways Upper West (Crawl_03)](wormways-upper-west.md) | R | complete shaft wall IN Wormways Upper West |  | Verified |  |
| UR | upper right | middle platform area | [Wormways Upper East (Crawl_01)](wormways-upper-east.md) | L | none |  | Verified |  |
| MR | middle right | middle platform area | [Wormways Flea Rescue (Crawl_06)](wormways-flea-rescue.md) | L | break wall {right} |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | middle platform area | entrance tunnel | none (door switch is on this side) |  | Verified |  |
| DS | door switch | entrance tunnel | middle platform area | prereq flip door switch AND (cling grip OR (ledge grab AND faydown cloak) OR scuttlebrace OR silk soar) |  | Verified |  |
| CG | platform gaps | middle platform area | upper platform area | (ledge grab AND (silk soar OR cling grip OR scuttlebrace OR faydown cloak)) OR (silk soar OR cling grip OR scuttlebrace) OR (faydown cloak AND (easy shaman pogo OR easy beast pogo OR easy reaper pogo OR easy architect pogo)) |  | Verified |  |
| CG | platform gaps | upper platform area | middle platform area | none (falling) |  | Verified |  |
| GT | grotto tunnel | entrance tunnel | mask grotto | none (falling) |  | Verified |  |
| GT | grotto tunnel | mask grotto | entrance tunnel | ledge grab OR (cling grip OR faydown cloak OR scuttlebrace OR silk soar) |  | Verified |  |
| DL | duct ledge | upper platform area | rosary duct | cling grip OR scuttlebrace |  | Verified |  |
| DL | duct ledge | rosary duct | upper platform area | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| use simple key on lock | entrance tunnel | have Simple Key Wormways |  | Verified | lock | unlocks the LL room exit |
| mask shard wormways | mask grotto | (ledge grab OR cling grip OR silksoar OR faydown cloak) |  | Verified | collectible | current hazard respawn from grotto water makes the theoretical no-swim req arbitrary, (you spawn in the entrance tunnel  or in the shaft if you came from above) |
| frayed rosary string wormways | rosary duct | (ledge grab AND (cling grip OR silk soar OR scuttlebrace)) OR (cling grip OR silk soar OR (scuttlebrace AND (flea brew OR clawline OR sharpdart OR faydown cloak))) |  | Verified | collectible |  |
| flip door switch | middle platform area | none |  | Verified | switch | unlocks the middle/lower shortcut |
