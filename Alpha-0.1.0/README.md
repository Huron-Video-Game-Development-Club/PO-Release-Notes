# Project Odyssey Alpha Version

Released 07/19/22

## Controls

The controls are as follows:
- Use the **_arrow keys_** or **_WASD_** to move
- Press `space` to interact with overworld elements and UI elements
- Press `x` to go back
- Press `shift` to open the menu in the overworld

> **_NOTE:_** Mouse controls are currently not fully supported. While using a mouse should not break the game, it may result in you getting lost in the UI system. Using a mouse is discouraged.

PO currently does not support configuring controls. 
> I'm lazy :P -Peter

## The Battle System

The battle system combines elements of the traditional **_Active Time Battle (ATB)_** and **_Break_** systems from newer rpgs.

### The ATB Gauge

From the start of a battle, yellow gauges in the character tags on the left side of the screen will slowly fill. Once this gauge is full, the corresponding character's turn will begin. 

### Turns

During a character's turn, you will be able to select one of the following actions to perform:

- ATTACK
- DEFEND
- SKILL
- ITEM
- COMBO
- FLEE

> **_NOTE:_** As of this demo, the `COMBO` action has not been implemented. Selecting it will do nothing.

### The BREAK Gauge

Upon attacking an enemy, a red gauge will begin to fill below them. This gauge is called the `BREAK Gauge`, and it is  **NOT** a health bar (you can't see enemy health).
When this gauge is full, an enemy will be considered broken. A big `BREAK` effect will appear on the screen, and the last moving character  will be given a second chance to perform an action.

An `ATTACK` will always fill the break gauge some amount. Certain `SKILL`s may fill the break gauge more, or have different effects during a `BREAK`.

## The Menu

The menu allows you to select from the following options:

- Status (View character information)
- Item (Use and view items -- `Arrange` and `Key` commands currently do nothing)
- Equip (Manage weapons/armor)
- Position (Change lead character in party)
- Config (Not implemented yet. Use computer config to configure brightness and sound)
- Save (Not implemented yet)

## Other Information

- Character deaths and game over are currently not supported. Feel free to abuse this if you really want to.
