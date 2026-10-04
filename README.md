# Party Armory 5E

## Purpose and features

Party Armory puts the party's shared inventory and character attunement on a
dedicated **Armory** tab in the dnd5e Group actor sheet.

- Review members' attunement slots and attune or unattune owned characters.
- Sort party loot, see suggested recipients, and hand items to characters.
- Let the GM claim gear and coins from defeated creatures in the current scene.

## Setup

- Foundry VTT V13 or V14 with dnd5e 5.3.0 or later.
- Party Armory 5E is free and needs no other module. Install it from the
  [Party Armory 5E releases](https://github.com/Spazzletopia-Studios/Party-Armory-5e/releases/latest),
  or use its manifest URL in Foundry's **Install Module** dialog.
- Enable **Party Armory 5E** in **Game Settings → Manage Modules**.

## Quick start

1. Open a dnd5e Group actor sheet that contains the party characters.
2. Select the **Armory** tab. If sheet integration is unavailable, use the
   module's Armory panel fallback on the group sheet.
3. Review the party stash and character attunement rows.
4. As GM, use Give or claim scene loot; as a character owner, attune or
   unattune that character's items.

## Detailed use

### Player workflow

Everyone can view the party stash and members allowed by Foundry permissions.
Character owners can attune or unattune their own character's items.

### GM workflow

Use the current scene's defeated-creature list to Take items or Take all, and
manage the party purse. Item hand-offs and coins use the controls described
below.

Free module by Spazzletopia Studios; current public release: 0.1.1.

### Armory features

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

### Using it

Open a Group actor's sheet and choose the **Armory** tab. Members of the group
are read from the group itself.

- The gamemaster gives, takes and claims loot and changes the party purse.
- A character's owner can attune and unattune that character's items.
- Everyone sees the members they are allowed to observe and the party stash.

## Limits and recovery

- The **Players can take party loot** setting shows a Give control, but the
  hand-off still requires the GM; a player's direct attempt is refused. Leave
  the setting off.
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
