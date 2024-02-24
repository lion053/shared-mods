# Shared-Mods

Can be used as dependency / submod in your mod. 

Download from the release section and put the mod into your mod at `/data` level. Add the `ModID` of the shared mod to the `ModDependencies` in your `modinfo.json`.

Alternatively, if you use the "Build & Deploy" feature from the Visual Studio Code Anno Plugin, you can add the urls shown below to your `ModDependencies` in your `modinfo.json`: 

## Milk from Cattle Farm (Lion053)

With this mod each cattle pasture module from the basegame cattle farm produces 1t of milk each cycle, independently of their ModuleOwner's productivity. Pasture production can be paused manually, their output is teleported into area storage. Cattle farm infotips are extended a bit to take this production into account. Unlock at 1 Artisan. 

![Cattle Pasture](/sources/cattle_pasture.png)
```json
"ModDependencies": [
  "https://github.com/lion053/shared-mods/releases/download/v1.0/shared-milk-from-cattle-farm-lion053.zip"
]
```

## Infotip Fix Tourist Buildings (Lion053)

This mod assigns the correct happiness-infotip to modded hotels, which otherwise show the normal residence infotip by default. It can be used for every new hotel, as long as they accommodate tourists with `GUID="601379"`. Includes the upgrade infotip for modded visitor piers as well.

On the left side: wrong happiness-infotip for modded hotels; On the right side: correct happiness-infotip for modded hotels:

![Happiness-Infotip](/sources/infotip_tourists.png)

```json
"ModDependencies": [
  "https://github.com/lion053/shared-mods/releases/download/v1.0/shared-infotip-fix-tourist-buildings-lion053.zip"
]
```
