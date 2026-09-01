# WSF Roadmap

Features that would be added to Where Soldiers Fall, everything on the list can get changed or removed

## ECS Platoon/Units Systems

- Platoon Selecting
  - [X] Click Detection
  - [X] Multi-Select
  - Orders
    - [X] Move To
    - [ ] Move Look To
    - [ ] Run/Walk
    - [X] Change Formation
- Platoon UI
  - Platoon Hotbar
    - Platoon Frame
      - [ ] Counting Max Units/Alive Units
      - [ ] Showing HP (alive units out of max units)
      - [ ] Interacting
- Platoon Formations
  - [X] Column
  - [ ] Skirmish
  - [X] Scatter
- Platoon Movement
  - [X] Follow Destination
  - [ ] Platoon Navmesh Agent
- Platoon Other
  - [X] Platoon Disbanding when last unit dies
  - [X] Handling dead units
- Unit Spawning
  - [X] Height Variation
  - [X] Supporting ScriptableObjects
- Unit Movement
  - [X] Follow Platoon
  - [X] Idle/Walk/Run Enum Changing
  - [X] Look at Moving Direction
  - [X] Raycast Ground Alignment
  - [ ] Play Animations (stalled)
- Unit Health
  - [X] Take Damage System
    - [X] DMG Resistance
    - [X] Damage System Logic
- Unit Targeting
  - [ ] Spatial Grids
  - [ ] Raycasting
- Unit Animations (stalled)
  - [ ] Idle
  - [ ] Walk
  - [ ] Run

## Nations
- Marley Empire
  - [X] Flag
  - [X] Victory Theme
- Kingdom of Eldia
  - [X] Flag
  - [X] Victory Theme
- Mid Eastern Allied Forces
  - [ ] Flag
  - [ ] Victory Theme
- Hizuru Shogunate
  - [ ] Flag
  - [ ] Victory Theme

## Main Menu
- Settings
  - [ ] Video
  - [ ] Audio
  - [ ] forgot

## Models
- Unit_EldianMiltia
  - [x] Make Unit_EldianMiltia1
  - [ ] Make Unit_EldianMiltia2
  - [ ] Make Unit_EldianMiltia3
  - [ ] Make Unit_EldianMiltia4
  - [ ] Make Unit_EldianMiltia5
- Unit_EldianVolunteer
  - [X] Make Unit_EldianVolunteer
- Unit_MarleyanInfantry
  - [ ] Make Unit_MarleyanInfantry
- ZA-848
  - Remake ZA-848
    - [ ] LODs
    - [ ] UVs
    - [ ] Texture
    - ??? Tris | ??? Tris | ??? Tris

## Weapons
- Arsenal-P34 (marley old standard issued rifle, Gewehr 1888)
  - [ ] LODs
  - [ ] UVs
  - [ ] Texture
  - 1,153 Tris | ??? Tris | ??? Tris only lod1 model is done
- Arsenal-P44 (marley standard issued rifle, Carcano M1891)
  - [ ] LODs
  - [ ] UVs
  - [ ] Texture
- Arsenal-P47 (marley standard issued sidearm, C96)
  - [ ] LODs
  - [ ] UVs
  - [ ] Texture
- Arsenal-P51 (marley anti titan rifle, PTRD-41)
  - [X] LODs
  - [X] UVs
  - [X] Texture
  - 2,000 Tris | 1,323 Tris | 729 Tris

## Maps
- Forest map
  - [ ] Assets
  - [ ] Navmeshes

## Ballistium ECS
- Ballistium
  - [X] Raycast Collisions
  - [X] Projectile Movement
  - [X] Projectile Prefab Data reading and using
  - Impact Logic
    - [ ] Spawning VFX
    - [X] Damaging Units
    - [ ] Explosions
    - [ ] Ricochets
       
## Essentials
- VFX Manager
  - [X] Storing System
  - [ ] ECS-GameObject Bridging
  - Playing VFX
    - [X] Set Position
    - [ ] Set Rotation
- Audio Manager 2.0
  - [ ] Pooling
  - [ ] Params Playing
  - [ ] Timescale affecting
  - [ ] ECS-GameObject Bridging
  - (possibly Burst compatible)

## VFX
- [X] Make VFX_ArtilleryImpact
- [X] Make VFX_MuzzleFlash
- [X] Make VFX_BloodBulletImpact
- [ ] Make VFX_BulletImpact
- [ ] Make VFX_ATBulletImpact

## Platoons
- Marleyan Anti-Titan Squad
  - [ ] Icon
  - [ ] Stats
- Marleyan Infantry
  - [ ] Icon
  - [ ] Stats
