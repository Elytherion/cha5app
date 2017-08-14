# 0.49.1

- Fixed issue with lists for advantages, disadvantages and special abilities containing skills/spells/liturgical chants.
- Fixed issue with RCP skill specialization selection.
- Fixed exporting heroes as JSON.
- Fixed equipment view.
- Professions are now sorted by name and them by subname (e.g. the academy name). Previously, professions with subnames were sorted randomly (changing from render to render).

# English Specific

- Added translation for skill name separation in RCP skill specialization selection.

# 0.49.0

- *Smash* does not require *Rundumschlag I* anymore.
- Protective/Warding Circles now require *Magical Signs*.
- Added missing *Ancestor Glyphs* from The Warring Kingdoms. They require *Magical Signs* as well.
- *Nimble* now increases MOV by 1.
- *Immunity to (Disease/Poison)* now correctly adds the selected entry.
- Derived characteristics are now correctly calculated on character sheet.
- Item templates have floating number values (again). This **won't** affect non-locked item templates in items.
- Requiring Spells now correctly disables the decrease button if the SR hits the required value.
- Invalid avatar paths will no longer result in a colored border with black background and an invalid file error in the console.
- Now filters Aspect Knowledge selection by active tradition.
- Now sorts lists properly depending on the selected locale (e.g. ä, ö and ü in German are basically treated as a, o and u respectively).
- Items now correcly reset if you load a character after you opened/created a character with items.
- Item weights are now correctly displayed.
- Item PA mods do not use the AT mod value anymore.
- *Improved Dodge I-III* now increases DO value.
- Profession *Spy* now correctly increases *Commerce* by 3.
- The used attributes for the skill check of ODEM ARCANUM are SGC/INT/INT now (following the German Regel-Wiki).
- *Combat Reflexes I-III* now increases INI value.
- Window is maximizable, unmaximizable and resizable.
	- Added a title bar on Windows and Linux, providing buttons in Windows 10 UWP style to minimize, (un)maximize and close the app. This bar is also the draggable area of the window.
- Removed the Start tab.
- Improved general performance.
- In *Profile Overview* and *Character Sheet* tabs, entries such as `Skill Specialization (Climbing: Trees), Skill Specialization (Survival: Find Campsite)` are now written as `Skill Specialization (Climbing: Trees, Survival: Find Campsite)`, providing a better overview and readability in addition to more space.
- A new Redo button is added to the Navigation Bar. History resets after saving, finishing RCP selection and finishing character creation as well as switching to another character.
- Fixed *Property Knowledge*'s and *Aspect Knowledge*'s AP cost and effects.
- Fixed Languages and Scripts selection texts in RCP selections window.
- Fixed loading characters with active Blessings.

## German Specific

- Includes new traditions, aspects and liturgcal chants from **Aventurisches Götterwirken I**.
- Added info for selected race in Races tab.
- CON instead of COU now increases WS value.
- Fixed *Intuitive Caster*'s spell limit and AE value.

## English Specific

- Added info box for selected race in Races tab, but (most of the) texts are still missing.

# 0.48.1

- Undo function is working again for advantages, disadvantages and special abilities.
- Spells can now be de/activated as intended.
- Cantrips/Blessing are now sorted on the character sheet.
- The total attribute maximum is shown on the attribute page during character creation.

# 0.48.0

- Heaps of bugs fixed. I lost sight of all bugs, so I won't provide a detailed list this time.
- Added a funtion to duplicate heroes.
- New interface for managing permanent AE/KP loss.
- Windows x86 support. (I am sorry for all the macOS users out there; I am still searching for a good way to build for Mac as I do not have a Mac at home.)
- Removed support for heroes created with app version lower than 0.45.0.
- If advantage/disadvantage list is empty, a placeholder will be shown. This is to ensure that having an empty list is intentional - and not a bug.

## German Specific

- Aventurian Names, Inns & Taverns, Aventurian Bestiary and The Warring Kingdoms are fully implemented (they should be). All entries from Aventurian Magic I are available. Optional Rules from AMI are not (yet) available.
- AMI is now basically complete. During reworking the entries some issues occured that might cause your characters to not work properly.
	- Selecting *Meistertalentierte*, *Zauberbarden* or *Zaubertänzer* as your magical tradition requires a second selection. *Meistertalentierte* choose their *Meistertalent*, *Zauberbarden* or *Zaubertänzer* choose their music/dance tradition (Ceoladir etc). If the affected characters are in character creation phase, you will be able to remove the existing tradition special ability and reactivate it with the correct selection. If character creation is finished, you have to create the respective character(s) again.
	- *Exorzist I* and *Meistertrick I* were missing selection options. Now they are included. The selection options do not affect the AP cost, so you can try to fix it the same way as you did for the magical tradition above.

# 0.47.3

- The requirement *Manifesto 10* for Elemental Servant referred to Wall of Fog instead of Manifesto.

# 0.47.2

- The calculations of total weight and total price in equipment tab should work again. Armor is excluded from the total weight calculation, because armor is excluded from carrying capacity if its in use.
- Character Sheet is working again.
- The skills tab contains a pane on the right side. If you click on the "i" buttons, it will show you additional information about the respective skill. Well, it will show you in the future: Currently, there is not much data available to show.
- The item list now properly resets for every new character.

# 0.47.1

- Fixed an issue with a race or a culture as a requirement. This issue caused some professions to never appear in the list.

# 0.47.0

Initial English release.
