# Seed Apocalypse – PvZ Fusion 4.0.5.2 (MelonLoader 0.7.x)

A hard challenge mode: every plant in the game falls as a seed (basic, fusions,
super, ultimate, doom/gold/silver variants...), while zombies scale every wave.

## Build
1. Install the .NET 6+ SDK.
2. Make `libs/net6/` and `libs/Il2CppAssemblies/` next to `SeedApocalypse.csproj`
   (unzip your two zips there) – or pass `-p:LibDir=<folder>/`.
3. `dotnet build -c Release`
4. Copy `bin/Release/net6.0/SeedApocalypse.dll` to `<game>/Mods/`.

## Play
Main menu → **SEED APOCALYPSE** button (or **F9**). **F10** cycles Hard / Brutal / Nightmare.
Settings: `UserData/MelonPreferences.cfg` → `[SeedApocalypse]`.

## Wave design
- Every wave: extra zombies, tier grows every 10 waves, HP scales with wave and difficulty.
- Waves rotate modifiers: Iron Tide, Swarm, Titans, Pincer (one row).
- Every 5th wave: mini-boss. Every 10th: APOCALYPSE (double zombies, higher tier).
- Win at wave 40 (configurable).
