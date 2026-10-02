# Underworks Exhaust Organ Transit (Library_12)

**Game ID:** Library_12

**Contributors:** Rebel

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Shell Shard Cache #1 | ✓ |
| S2 | Shell Shard Cache #2 | ✓ |
| S3 | Shell Bundle Pickup | ✓ |
| S4 | Exhaust Organ Elevator | ✓ |
| S5 | Far Right | ✓ |
| S6 | Lower Left | ✓ |
| S7 | Upper Left | ✓ |
| S8 | Center | ✓ |
| S9 | One-Way Floor | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | Upper Left | Upper Left | [Vaults & Bellway Cauldron Entrance (Library_11)](vaults-bellway-cauldron-entrance.md) | UR | Nothing. |  | Verified | ✓ |  |
| LL | Lower Left | Lower Left | [Vaults & Bellway Cauldron Entrance (Library_11)](vaults-bellway-cauldron-entrance.md) | LR | Nothing. |  | Verified | ✓ |  |
| EV | Elevator | Exhaust Organ Elevator | [Exhaust Organ Interior (Organ_01)](../bilewater/exhaust-organ-interior.md) | UE | Nothing. |  | Verified | ✓ |  |
| R | Right | Far Right | [Underworks Below Vaultkeeper (Library_12b)](underworks-below-vaultkeeper.md) | L | Activate Underworks: Break Wall #1 |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SB | Collect Shell Bundle | Far Right | Shell Bundle Pickup | Nothing. (Fall) |  | Verified |  |  |
| SB | Collect Shell Bundle | Shell Bundle Pickup | Far Right | Silk Soar OR (Scuttlebrace AND Spike Pogo) OR (Cling Grip AND (Spike Pogo OR Faydown Cloak OR Drifter's Cloak OR Clawline OR Sharpdart)) |  | Verified |  |  |
| CFR | Center-Far Right | Far Right | Center | Spike Pogo OR Sprint OR Dash OR Faydown Cloak OR Drifter's Cloak OR Clawline OR Sharpdart OR Scuttlebrace |  | Verified |  |  |
| CT | Center-Top | Center | One-Way Floor | Scuttlebrace AND (Faydown Cloak OR Clawline OR Sharpdart OR ((Sprint OR Spike Pogo) AND (Ledge Grab OR Dash OR Drifter's Cloak)) OR (Cling Grip AND (Spike Pogo OR Drifter's Cloak OR Faydown Cloak OR Clawline OR Sharpdart OR Dash OR Easy Beast Crest Pogo OR Easy Needle Strike Stall (Beast OR Architect)))) |  | Verified |  |  |
| CL | Center-Low | Lower Left | Center | (Silk Soar AND (Clawline OR Sharpdart OR Dash OR Faydown Cloak OR Drifter's Cloak OR Easy Beast Crest Pogo OR Cling Grip OR Scuttlebrace)) |  | Verified |  |  |
| CFR | Center-Far Right | Center | Far Right | (Silk Soar AND (Clawline OR Dash OR Sharpdart OR Drifter's Cloak OR Faydown Cloak)) OR Scuttlebrace OR Cling Grip |  | Verified |  |  |
| CL | Center-Low | Center | Lower Left | Silk Soar OR Faydown Cloak OR Drifter's Cloak OR Dash OR Cling Grip OR Clawline OR Sharpdart OR Scuttlebrace OR Spike Pogo |  | Verified |  |  |
| CT | Center-Top | One-Way Floor | Center | Activate Underworks: Break Wall #2 |  | Verified |  | IF floor is broken. |
| BF | Breakable Floor | One-Way Floor | Upper Left | Activate Underworks: Break Wall #2 |  | Verified |  |  |
| SP | Shard Pillars Center | Center | Shell Shard Cache #2 | Nothing. (Fall) |  | Verified |  |  |
| SSR | Shell Shard Rocks | Upper Left | Shell Shard Cache #1 | Nothing. |  | Verified |  |  |
| SPL | Shard Pillars Left | Lower Left | Shell Shard Cache #2 | Spike Pogo OR (Clawline AND Sharpdart AND Ledge Grab) OR (Clawline AND (Faydown Cloak OR Drifter's Cloak)) |  | Verified |  |  |
| ET | Elevator Transit | Upper Left | Exhaust Organ Elevator | Activate Underworks: Flip Switch #1 |  | Verified |  |  |
| ET | Elevator Transit | Exhaust Organ Elevator | Upper Left | Activate Underworks: Flip Switch #1 |  | Verified |  |  |
| BF | Breakable Floor | Upper Left | One-Way Floor | Nothing. (Fall) |  | Verified |  |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Underworks: Break Wall #1 | Far Right | Break Wall Right |  | Verified | blockade | ✓ |  |
| 2 | Underworks: Shell Shard Pillar #1 | Shell Shard Cache #2 | Nothing. |  | Verified | resource | ✓ |  |
| 3 | Underworks: Shell Shard Pillar #2 | Shell Shard Cache #2 | Nothing. |  | Verified | resource | ✓ |  |
| 4 | Underworks: Shell Shard Rock #2 | Shell Shard Cache #1 | Nothing. |  | Verified | resource | ✓ |  |
| 5 | Underworks: Shard Bundle #1 | Shell Bundle Pickup | Nothing. |  | Verified | collectible | ✓ |  |
| 6 | Underworks: Shell Shard Rock #1 | Shell Shard Cache #1 | Nothing. |  | Verified | resource | ✓ |  |
| 7 | Underworks: Break Wall #2 | Upper Left | Break Wall Up |  | Verified | blockade | ✓ |  |
| 8 | Underworks: Flip Switch #1 | Exhaust Organ Elevator | Flip Switch Left |  | Verified | switch | ✓ |  |

## Room Images

### Connections

[![Connections for Underworks Exhaust Organ Transit (Library_12)](../00-annotations/underworks/underworks-exhaust-organ-transit-connections.png)](../00-annotations/underworks/underworks-exhaust-organ-transit-connections.png)

### Checks

[![Checks for Underworks Exhaust Organ Transit (Library_12)](../00-annotations/underworks/underworks-exhaust-organ-transit-checks.png)](../00-annotations/underworks/underworks-exhaust-organ-transit-checks.png)

### Scene

[![Scene for Underworks Exhaust Organ Transit (Library_12)](../00-annotations/underworks/underworks-exhaust-organ-transit-scene.png)](../00-annotations/underworks/underworks-exhaust-organ-transit-scene.png)
