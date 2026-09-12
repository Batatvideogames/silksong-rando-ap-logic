# Underworks Exhaust Organ Transit (Library_12)

**Game ID:** Library_12

## Subrooms

- Shell Shard Cache #1
- Shell Shard Cache #2
- Shell Bundle Pickup
- Exhaust Organ Elevator
- Far Right
- Lower Left
- Upper Left
- Center
- One-Way Floor

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | Upper Left | Upper Left | [Vaults & Bellway Cauldron Entrance (Library_11)](vaults-bellway-cauldron-entrance.md) | UR | Nothing. |  | Verified |  |
| LL | Lower Left | Lower Left | [Vaults & Bellway Cauldron Entrance (Library_11)](vaults-bellway-cauldron-entrance.md) | LR | Nothing. |  | Verified |  |
| EV | Elevator | Exhaust Organ Elevator | [Exhaust Organ Interior (Organ_01)](../bilewater/exhaust-organ-interior.md) | UE | Nothing. |  | Verified |  |
| R | Right | Far Right | [Underworks Below Vaultkeeper (Library_12b)](underworks-below-vaultkeeper.md) | L | Nothing. |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SB | Collect Shell Bundle | Far Right | Shell Bundle Pickup | Nothing. (Fall) |  | Verified |  |
| SB | Collect Shell Bundle | Shell Bundle Pickup | Far Right | Silk Soar OR Scuttlebrace AND Spike Pogo OR Cling Grip AND (Spike Pogo OR Faydown Cloak OR Drifter's Cloak OR Clawline OR Sharp Dart) |  | Verified |  |
| CFR | Center-Far Right | Far Right | Center | Spike Pogo OR Sprint OR Dash OR Faydown Cloak OR Drifter's Cloak OR Clawline OR Sharp Dart OR Scuttlebrace |  | Verified |  |
| CT | Center-Top | Center | One-Way Floor | Scuttlebrace AND (Faydown Cloak OR Clawline OR Sharp Dart OR ((Sprint OR Spike Pogo) AND (Ledge Grab OR Dash OR Drifter's Cloak)) OR Cling Grip AND (Spike Pogo OR Drifter's Cloak OR Faydown Cloak OR Clawline OR Sharp Dart OR Dash OR Crest Pogo (Beast) OR Crest Needle Strike (Architect OR Beast) |  | Verified |  |
| CL | Center-Low | Lower Left | Center | Silk Soar AND (Clawline OR Sharp Dart OR Dash OR Faydown Cloak OR Drifter's Cloak OR Crest Pogo (Beast)) Cling Grip OR Scuttlebrace |  | Verified |  |
| CFR | Center-Far Right | Center | Far Right | Silk Soar AND (Clawline OR Dash OR Sharp Dart OR Drifter's Cloak OR Faydown Cloak) OR Scuttlebrace OR Cling Grip |  | Verified |  |
| CL | Center-Low | Center | Lower Left | Silk Soar OR Faydown Cloak OR Drifter's Cloak OR OR Dash OR Cling Grip OR Clawline OR Sharp Dart OR Scuttlebrace OR Spike Pogo |  | Verified |  |
| CT | Center-Top | One-Way Floor | Center | Nothing. (Fall) |  | Verified | IF floor is broken. |
| BF | Breakable Floor | One-Way Floor | Upper Left | Break the ceiling |  | Verified |  |
| SP | Shard Pillars Center | Center | Shell Shard Cache #2 | Nothing. (Fall) |  | Verified |  |
| SSR | Shell Shard Rocks | Upper Left | Shell Shard Cache #1 | Nothing. |  | Verified |  |
| SPL | Shard Pillars Left | Lower Left | Shell Shard Cache #2 | Spike Pogo OR Clawline AND Sharp Dart AND Ledge Grab OR Clawline AND (Faydown Cloak OR Drifter's Cloak) |  | Verified |  |
| ET | Elevator Transit | Upper Left | Exhaust Organ Elevator | Opened Shortcut |  | Verified |  |
| ET | Elevator Transit | Exhaust Organ Elevator | Upper Left | Nothing. |  | Verified |  |
| BF | Breakable Floor | Upper Left | One-Way Floor | Nothing. (Fall) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Location Type | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Underworks: Break Wall #1 (Left OR Right) | Far Right | Nothing. |  | Verified |  |  |
| Underworks: Shell Shard Pillar #1 | Shell Shard Cache #2 | Nothing. |  | Verified |  |  |
| Underworks: Shell Shard Pillar #2 | Shell Shard Cache #2 | Nothing. |  | Verified |  |  |
| Underworks: Shell Shard Rock #2 | Shell Shard Cache #1 | Nothing. |  | Verified |  |  |
| Underworks: Shard Bundle #1 | Shell Bundle Pickup | Nothing. |  | Verified |  |  |
| Underworks: Shell Shard Rock #1 | Shell Shard Cache #1 | Nothing. |  | Verified |  |  |
| Wunderworks: Break Wall #2 (Up) | Upper Left | Nothing. |  | Verified |  |  |
| Underworks: Flip Switch #1 (Left) | Exhaust Organ Elevator | Nothing. |  | Verified |  |  |
