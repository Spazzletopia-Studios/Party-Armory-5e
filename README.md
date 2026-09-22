# Party Armory 5E

An **Armory** tab on the dnd5e **group** actor sheet: the party's shared
inventory, with judgement. It answers the questions a table asks every session:
what do we have, who can use it, who should get it, and who is out of
attunement slots. 5E compatible.

A free SpazzMods module by Spazzletopia Studios.

## What it does

The Armory tab has three parts.

- **Members.** Every character's attunement slots (used and maximum), the items
  that need or hold attunement, and attune or unattune in place. A fourth
  attunement is refused with the reason.
- **Party loot.** The group's own stash with item art and stacked quantities,
  the party purse with the system's Award and Transfer dialogs, an add-coin
  control, and a Give control that suggests who each item suits. The
  suggestion reads the character sheets: proficiency, Strength requirements,
  armour class with the Dexterity cap, average damage, weapon mastery,
  ammunition, size and stealth, with the reasoning on hover. A handed-over item
  arrives unequipped, so identical items stack.
- **Unclaimed** (gamemaster). The current scene's defeated creatures, their
  gear and their coin, with Take and Take all. A container moves with its
  contents. An unidentified item shows only its cover name.

## Using it

Open a Group actor's sheet and choose the **Armory** tab. Members of the group
are read from the group itself.

- The gamemaster gives, takes and claims loot and changes the party purse.
- A character's owner can attune and unattune that character's items.
- Everyone sees the members they are allowed to observe and the party stash.

## Requirements

- Foundry VTT V13 or V14.
- The dnd5e system 5.3.0 or newer (tested on 5.3.3 with Foundry 13 and 6.0.3
  with Foundry 14).
- No other modules. Party Armory 5E works alongside the SpazzMods Hub but does
  not need it.

## Known limits in 0.1.0

- The world setting **Players can take party loot** shows players the Give
  control, but the hand-off itself still needs the gamemaster, and a player's
  click is refused with a warning. Leave the setting off for now.
- What a container holds is not listed, on purpose. Nested containers move
  correctly but are listed one level deep.
- No translations yet.
- Tested with parties of up to four characters and with one client connected.

## Licence and attribution

Software: MIT (see LICENSE). Not affiliated with, endorsed by, or sponsored by
Foundry Gaming LLC. Party Armory 5E ships no rules text or rules data of its own:
everything it shows is read from the actors and items in your world, and its
coin icons are loaded from the installed dnd5e system.

This work includes material from the System Reference Document 5.2.1 ("SRD 5.2.1") by Wizards of the Coast LLC, available at https://www.dndbeyond.com/srd. The SRD 5.2.1 is licensed under the Creative Commons Attribution 4.0 International License, available at https://creativecommons.org/licenses/by/4.0/legalcode.

This work includes material taken from the System Reference Document 5.1 ("SRD 5.1") by Wizards of the Coast LLC and available at https://dnd.wizards.com/resources/systems-reference-document. The SRD 5.1 is licensed under the Creative Commons Attribution 4.0 International License available at https://creativecommons.org/licenses/by/4.0/legalcode.
