# cs2-nade-practice-config
A CS2 configuration for practicing nade lineups. At a high level, this config:
* Removes interruptions from nade practice
  * Main annoyances removed: bots, self-damage, limited ammo, round end
* Makes it easier to see where nades are going
  * Adds an easy capslock bind for `noclip`
  * Enables the nade camera & trajectory line

## Using the cfg
* Place in `SteamLibrary\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`
  * 🛈 Note: this is **not** `SteamLibrary\steamapps\common\Counter-Strike Global Offensive\csgo\cfg`
* Enable the developer console (Set ⚙️ -> Game -> Game -> Enable Developer Console (~) to "YES")
* Run with `exec nade`
  * 🛈 Note: this script requires a lobby launched with the practice menu (eg: Play -> Practice -> Competitive -> Nuke), not a lobby launched via the console command (eg: `map de_nuke`) to work properly
* Start throwing nades.
  * For extra visibility into where nades are going, tap capslock to zoom around with `noclip` enabled.
