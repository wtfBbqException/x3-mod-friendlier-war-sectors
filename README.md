# x3-mod-friendlier-war-sectors

**X3AP mod to stop Terrans and Argons from destroying player assets.**

Normally, as soon as you leave a war sector, Terran and Argon forces will make a beeline for any player assets (ships, satellites, stations) and destroy them regardless of your reputation.

With this mod, your assets are safe as long as you maintain a positive standing with both factions.

## Gameplay Changes

Once installed, your assets will only be attacked if your standing with either the Terrans or Argons is negative.

- If both factions allow you to dock in their border systems, your assets are safe.
- This only affects X3AP's war sector logic.
- Normal combat and faction hostility mechanics still apply.
- Most non-Terran starts begin with slightly negative Terran rep; the reverse applies for most Terran starts.

You can toggle between **vanilla aggression** and **modded friendliness** via:
> **Options → Gameplay → Artificial Life → Friendlier War Sectors**

## Installation

(Optional) Back up the original file:
- `<x3base>/addon/scripts/!fight.war.protectsector.pck`

Then:
- Extract the archive
- Copy the files **inside** the fws-v10 folder into your `<x3base>/addon/scripts/` folder
- Overwrite when prompted

## Update

Same process as installation:
- Copy files into the scripts folder
- Overwrite when asked

## Uninstallation

You don’t need to uninstall—the mod can be disabled via Artificial Life settings (see above). Overhead is negligible.

To fully remove:
- Delete the two `.xml` files
- Restore the `.pck` file from your backup  
  (or verify game files via Steam)

**Note:** A complete purge requires a new save or manual version reset in the Script Editor.

---

This mod lives at github: [https://github.com/wtfBbqException/x3-mod-friendlier-war-sectors](https://github.com/wtfBbqException/x3-mod-friendlier-war-sectors)

## License

This mod is released under a custom non-commercial license.  
You may freely use, modify, and share it **as long as credit is given** and **no money is involved**.  
See [LICENSE.md](LICENSE.md) for full terms.
