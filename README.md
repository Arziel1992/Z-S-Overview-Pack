# Zirio-Syundai Special Overview
### Overview Pack for EVE Online

The Zirio-Syundai Special™ Overview was created to provide a generalized, user-friendly, 6- or 8-tab overview, ready to use as-is with room to be tailored as needed.
What started as a stop-gap measure to bring the SaraShawa overview up-to-date for 118.6 instead snowballed into a complete re-write of the .yaml file and [total overhaul of the visuals.](http://prntscr.com/br0lar)
If you're familiar with SaraShawa, it shouldn't take too long to adjust to the changes.

##### New features include:
- Choice of Full-Size or Compact 6- or 8-Tab Layouts that can be swapped at any time without reloading the entire pack.
- Modular Setup: Load the Preset Packs you need, not the ones you don't.
- New presets, including dedicated Faction Warfare and Incursion presets.
- [Color-coded presets by category for improved ease of selection.](http://prntscr.com/br0kp1)

#### Current Version: 2.6.1
- For Release: 118.6
- Updated: 2016.07.16 EVE Calendar
- Join our Mailing List in-game: Zirio-Syundai Overview
- Visit us on [Reddit r/EVE](http://www.reddit.com/r/Eve/comments/4s3z9i/introducing_the_ziriosyundai_special_overview_pack/)

Zirio - YAML Coding & Pack Maintenence  
Deuce Syundai - Design & Text Formatting

### How to install

#### Option 1: In-game, from "Zirio-Syundai Overview" chat channel:
1. Open up your Overview Settings ( ≡ button at top left of the Overview window).
2. Go to the "Misc" tab and click "Reset All Overview Settings." You MUST do this the first time you install. This prevents any weirdness that may be caused by any changes already made to the overview.
3. Apply the Z-S Core preset pack FIRST. This is the only preset pack required. When combined with a Tab Layout, it includes the following presets:
	- All Travel, Warpout, D-scan, and Bracket presets
	- PvE: Basic and PvE: Salvage/Loot
	- PvP: Basic and Target: Drones
	- Friendly: All and Friendly: Fleet
4. (Optional) Apply any of these Optional preset packs you may need for more specialized presets:
	- Z-S PvE contains presets for Anoms/Ratting, Incursion, Mining, and Show Drones.
	- Z-S PvP Basic contains presets for Faction Warfare, Ships Only, Bombing Warpouts, Deployables, NPSI, Structures, and Wartargets.
	- Z-S PvP Extended packs include presets for specific categories from Fighters to Frigates to Logi to Titans. Each pack contains half the categories and should be installed together.
	- Z-S Friendly Extended includes presets for Capitals, Supercapitals, Carriers, Dictors, Dreads, Logi, and Recon.
5. To finish and set up the tabs, apply a Tab Layout. Standard has each tab named for a purpose, and Compact replaces most of the names with numbers or sorter names for reduced tab width.
	- You can alternate between Layouts at any time without reloading the entire pack.
	- _Some features might not show correctly at first, It may be necessary to Dock and then Undock at any station to reload the UI to apply all changes._

#### Option 2: Out of game:
1. Go to the most recent version folder and download the "Zirio-Syundai Full.yaml" file.
2. Go to "C:\Users\YourName\Documents\EVE\Overview" and paste the downloaded file here.
3. Start the game and open up your Overview Settings ( ≡ button at top left of the Overview window).
4. Go to the "Misc" tab and click "Import Overview Settings".
5. Select "Zirio-Syundai Full" on the left list and click "Check All" on the top middle, then click "Import".
	- _Some features might not show correctly at first, It may be necessary to Dock and then Undock at any station to reload the UI to apply all changes._


### Changelog

##### Version v2.6.1
>1. Updated Ship Brackets:
	- Removed "ShipName" variable (completely).
>2. Reordered Overview Columns:
	- Added "Tag" coumn.
>3. Renamed packs:
	- "Z-S PvE Basic" to "Z-S PvE Basic Extended"
		- Corrected "Loaded" text to match the pack name.
	- "Z-S PvE Friendly" to "Z-S PvE Friendly Extended"
		- Corrected "Loaded" text to match the pack name.
>4. Updated presets:
	- Added missing "Overseer NPC's" to preset:
		- "✥ --- PvP: Basic"
		- "✥ --- PvP: FW"
	- Removed "Starbase: Control Tower" from "✥ --- PvP: Basic":
	- Renamed "✥ --- PvP: Basic" to "✥ --- PvP: Basic (NPC)"
>5. Added presets:
	- "✥ --- PvP: Basic (No NPC)"


##### Version v2.6
>1. Revamped Ship Brackets:
	- Condensed the information from 4 to 2 rows for legibility in ship clusters.
	- Recolored the variables for better identification.
	- Resized the variables, distinguishing from most important to insignificant (tactically speaking).
	- Removed "ShipName" variable (partially).
>2. Ranamed Tabs:
	- "Loot" to "Misc" (yellow).
	- "Misc" to "Friendly" (blue).
>3. Reorganized column order: Alliance > Corporation
>4. Updated presets:
	- Added missing NPC's to ALL PvE presets:
		- Overseer NPC's
		- Event NPC's
	- Renamed "※ D-Scan" presets for better understanding: (Cel stands for Celestial)
		- "※ D-Scan: Pos" to "※ D-Scan: Pos (Cel)"
		- "※ D-Scan: Pos All" to "※ D-Scan: Pos + Mods (Cel)"
		- "※ D-Scan: Ships" to "※ D-Scan: Ships (No Cel)"
	- Updated "✜ PvE: Incursion":
		- Added the most widely used and useful entities.
>5. Added presets:
	- "※ D-Scan: Pos + Mods (No Cel)" 


##### Version v2.5
>1. Categorized preset links:
	- Replaces the split preset part system for a more convenient preset category system, where the player loads the preset category he/she wants/needs, then applies the final Tab Layout.
	- Made to reduce cluttering of unwanted/unneeded presets.
>2. Included changes from:
	- Version v2.3
	- Version v2.4


##### Version v2.4 (not released, pushed to next version)
>1. Renamed "Brackets" presets for consistency.
>2. Renamed "Hostile" presets to "Target" for consistency.
>3. Updated presets:
	- Ranamed "✥ --- PvP: Normal" to "✥ --- PvP: Basic".
	- Updated preset "➲ Extra: Align Points":
		- Added Structure: Citadel.
	- Updated preset "✜ --- PvE: Basic":
		- Added Entity: Missing event NPC's.
	- Updated preset "✜ PvE: Salvage/Loot":
		- Added Celestial: Biomass, Secure Cargo Container, Audit Log Secure Container, Freight Container.
		- Added Deployable: Mobile Depot, Mobile Siphon Unit.
		- Added Entity: Mission Container, Event Container.


##### Version v2.3 (not released, pushed to next version)
>1. Added presets:
	- Added new preset "⌘ --- Brackets: All":
		- More permanent solution to "Show All Brackets".
		- Works as a Collidable locator.
	- Added new preset "✥ --- PvP: FW":
		- Derivative of "✥ --- PvP: Normal".
		- Added Entity: All FW related entities.
	- Added new preset "※ --- D-Scan: All":
		- Combination of "※ D-Scan: Ships" and "※ D-Scan: Pos All".


##### Version v2.2
>1. Ranamed "Finishes" to "Tab Layouts".
>2. Adjusted the sizes of both 6 & 8 Compact Layouts to fit better on smaller screens.
>3. Increased the Icon size on the presets for better legibility.
>4. Replaced the Hostile Icon for a more adequate one to fit the new sizes.


##### Version v2.1
>1. Adjusted information rows on Player Ship brackets.
>2. Updated presets:
	- Added Fighters to preset "Friendly: All".
	- Added Warpgates to preset "PvE: Incursions".
	- Added Custom Offices to preset "Structures".
	- Corrected typo on preset "PvP: Normal".


##### Version v2.0
>1. Rewrote the entirety of the code for consistency, readability, compactness and scalability.
>2. Adjusted split imports:
	- Adjusted into 4 base parts.
	- Added 4 finish parts.
>3. Added finishes:
	- Added "6 Compact Tabs".
	- Added "6 Normal Tabs".
	- Added "8 Compact Tabs".
	- Added "8 Normal Tabs".
>4. Updated presets:
	- Added Citadels to preset "Friendly: All".
>5. Added presets:
	- Added "PvE: Incursion: preset.


##### Version v1.0
>1. Manual fork from SaraShawa-Overview Pack v9.1.
	- (Export pack from the game to the overview folder, then edit the .YAML file)
>2. Simplified tabs:
	- Added tab colouring.
>3. Simplified presets:
	- Added preset colouring.
	- Added preset ideography.
>4. Created split imports:
	- Added 6 base parts.
	- Added 1 finish.
	- Added 1 optional finish.


### Notice:
SaraShawa Overview Pack did not have a GitHub repository nor it was under any License at the moment of the manual fork and at the moment of creation of this repository.
