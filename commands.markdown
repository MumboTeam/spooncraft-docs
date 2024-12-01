---
title: "Commands"
description: "A list of all the commands on the Spooncraft server."
permalink: /commands/
layout: single
sidebar:
  title: "Pages"
  nav: sidebar
last_modified_at: 2024-12-01
toc: true
---
A list of all the commands on the Spooncraft server.

## General
- `/afk` - This makes you AFK, or away from keyboard. Doing this will make your name in the tab list have the words [AFK] next to it. This also happens automatically after being inactive for some time.
- `/destination` - Allows you to add destinations to generate paths to.
- `/hud` - Brings up a menu in chat that can be used to enable/disable and change settings for the server-side HUD.
- `/distance` - Computes the distance between two sets of coordinates.
- `/modviewer` - Shows the mods installed on the server.
- `/polydex` - Shows every item in the game and their recipes, including custom items for the server. You can also click the book to sort by group or source.
- `/pvp` - Toggles between PVP on and off. By default, PVP is off.
- `/r` - This is a shortcut to replying to someone in game. Example: /r “Hi!”
- `:item:` - Displays the item you are holding in chat.
- `:pos:` - Sends your current coordinates in chat.

## Claims
This server utilizes Flan for claiming. You can create claims using a [claim scroll]({{ site.url }}{{ site.baseurl }}/craftingrecipes/#claim-scroll). Simply right click one corner and right click another corner to create a claim. 10 blocks minimum. 
Nobody but you can build or do anything in this claim without permissions.

- `/flan menu` - When standing in a claim, you can open this menu to change various options for the claim.
- `/flan add` - Creates a claim from point to point, in X and Z radius around you (rectangle) or as large as possible around you.
- `/flan claimMessage` - Can be used to create a message when someone leaves or enters your claim that will appear in the middle of their screen (assuming title) or near their hotbar (assuming subtitle).
- `/flan delete` - Deletes the claim you are standing in.
- `/flan deleteAll` - Deletes **all** of your claims.
- `/flan expand` - Expands a claim by however many blocks you input in the direction you are facing.
- `/flan group add|remove <name>` - Adds/removes the group with that name. Also editable via the claim menu.
- `/flan group players add|remove <player>` - Adds/remove a player to the group. if overwrite then will overwrite the players current group else does nothing. Also editable via the claim menu.
- `/flan info` - Shows information about the claim you’re standing in.
- `/flan list` - Shows all the claims you currently have.
- `/flan name` - Changes the name of your claim.
- `/flan permission` - Sets global/group/personal permissions. Also editable via the claim menu (for group permissions right click on the group in the menu).
- `/flan personalGroups` - Opens the menu to edit personal groups. These are the default groups for when you create a new claim.
- `/flan switchMode` - Switches between normal and subclaim mode.
- `/flan transferClaim` - Transfer ownership of the claim to someone else.
- `/flan trapped` - Teleports you out of the claim if someone trapped you in a box and claimed it.