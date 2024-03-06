# Shared-Mods

Can be used as dependency / submod in your mod. 

Download from the release section and put the mod into your mod at `/data` level. Add the `ModID` of the shared mod to the `ModDependencies` in your `modinfo.json`.

Alternatively, if you use the "Build & Deploy" feature from the Visual Studio Code Anno Plugin, you can add the urls shown below to your `ModDependencies` in your `modinfo.json`: 

## Small Elevator Factory (Lion053)

This mod brings a small elevator factory to the game. This way modded buildings can have elevators as a construction material without being dependent on the HighLife-DLC (DLC-09). If DLC-09 is not owned / active, the building is unlocked at 5.000 investors. If DLC-09 is active, the building is unlocked as soon as the original elevator factory from DLC-09 is built (in order to not break the related quests from Donny Bader). Menu location: Right after Steam Carriages. If DLC-09 is active, the factory is inserted into the original production chain. 

⚠ Attention: This mod has [`shared-ground-textures-industry-jakob`](https://github.com/jakobharder/anno1800-shared-mods/releases) as a dependency. Please add this mod to your mod as well. LoadOrder does not matter.   

ModID: `shared-small-elevator-factory-lion053`

![Small_Elevator_Factory](/sources/small_elevator_factory.png)
```json
"ModDependencies": [
  "https://github.com/lion053/shared-mods/releases/download/v1.0/shared-small-elevator-factory-lion053.zip"
]
```

## Milk from Cattle Farm (Lion053)

With this mod each cattle pasture module from the basegame cattle farm produces 1t of milk per cycle, independently of their ModuleOwner's productivity. Pasture production can be paused manually, their output is teleported into area storage. Cattle farm infotips are extended a bit to take this production into account. Unlock at 1 Artisan. Without DLC-12, this mod affects the Old and New World cattle farm, with DLC-12 active, the New World remains untouched. Compatible with 'Cattle needs to be butchered' (Kurila) and 'Pescetarians' (Jakob). 

ModID: `shared-milk-from-cattle-farm-lion053`

![Cattle Pasture](/sources/cattle_pasture.png)
```json
"ModDependencies": [
  "https://github.com/lion053/shared-mods/releases/download/v1.0/shared-milk-from-cattle-farm-lion053.zip"
]
```

## Infotip Fix Tourist Buildings (Lion053)

This mod assigns the correct happiness-infotip to modded hotels, which otherwise show the normal residence infotip by default. It can be used for every new hotel, as long as they accommodate tourists with `GUID="601379"`. Includes the upgrade infotip for modded visitor piers as well.

On the left side: wrong happiness-infotip for modded hotels; On the right side: correct happiness-infotip for modded hotels:

ModID: `shared-infotip-fix-tourist-buildings-lion053`

![Happiness-Infotip](/sources/infotip_tourists.png)

```json
"ModDependencies": [
  "https://github.com/lion053/shared-mods/releases/download/v1.0/shared-infotip-fix-tourist-buildings-lion053.zip"
]
```
