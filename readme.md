# Dark And Darker Lobby Helper

## Goal

Improve the functionality and convenience of Dark and Darker's pre-game lobby.

## Fuctionality

Use hotkeys to do common things in the pre-game lobby such as vendor treasure, transfer inventory, buy meds, execute buy list on market, ReSquire, go to common crafters, ... and much more. Functions are designed to work when logged into a character and in the pre-game lobby.

## Requirements

  - This version is made for 1920x1080 screen res.
  - Install auto-hotkey v2 productivity tool (this is just what I happend to code it in, but in theory could be done with any coding language).

## How to Run

  0. Address requirements.
  1. Clone/download this repo, Run the script "DarkAndDarkerLobbyHelper.ank".
  2. Launch "Dark and Darker", Log into a character and be in the Pre-Game Lobby at 1920x1080p res (this doesn't work elsewhere).

## Default Keybinds

These are set up in "src/Keybinds.ank". You can change them if you like in that code file.
  
  - **Left Cntrl** (Or Right Cntrl if there is no overlap (see Right Cntrl below)) +
    - U - Set Volume to 2 (press Esc first)
    - O - Buy 18 Potions
    - P - Go To Class Spec
    - 5 - Go To Goblin Purchase
    - 6 - Go To Alchemist Service
    - 7 - Go to Leathersmithing Service
    - 8 - Go to Armourer Service
    - 9 - Go to Tailoring Service
    - 0 - Go to Weaponsmith Service
    - numpad0 - Insta-Queue - a dangerous but speedy button
    - numpad2 - Hotswap Characters (go to prev character)
    - numpad3 - Go to Squire and fill
    - numpad4 - Go to Stash
    - numpad5 - Gather all from Expressman
    - numpad6 - Gather all from Goblin Buyback
    - numpad7 - not assigned
    - numpad8 - Sell at Vendor
    - numpad9 - Go To Marketplace Search - disabled if ssf
    - numpadAdd - Buy 18 Potions

  - **Right Cntrl** + 
    - U - Set Volume to 50 (press Esc first)
    - numpadAdd - Buy 9 Potions
    - O - Buy 9 Potions
    - 1 - Go To Squire Sets
    - K - Refill Squire Kit
    - Alt+K - Refill Squire Right Side Bow, Left Side Potions
    - M - Go To Search Marketplace
    - Q - Insta-Queue
    - ALT+Q - ToolBelt Reset and Requeue (designed for arena)
    - H - Hotswap characters (go to last selected character)
    - Alt+I - Invest In Consumables (green potions, green bandages, greater luck)
    - E - Gather All From Expressman
    - G - Gather All From Goblin Buyback
    - Alt+H - Halt long process - Stop the current process on next stop point
    - Alt+G - Gather All Front Page Characters (6 most recent played) From Goblin Buyback & Expressmen (long routine for when afk) (long process)
    - Alt+P - MARKET POST from PosterSettings.txt File (long process) - disabled if ssf
    - Alt+M - MARKET BUY from GearBuyingSettings File (long process) - disabled if ssf
    - A - Go To Goldsmith To Gem Gear
    - W - Go to Workshop Scrap
    - C - Gather All From Cockatrice
    - X - Go to Vendor and Quickfill (waits for confirm)
    - T - Move All Inventory To Stash Routine

## Known Issues

  - there can be issues with the lobby being slower than expected, in which case the delay globals constants need increased in [src/LobbyButtonFunctionsLibrary.ank](src/LobbyButtonFunctionsLibrary.ank)
  - there is an issue with some DaD UI buttons occasionally not functioning. (appears to be an native game UI problem)
  - the de-equip routine will sometimes throw things in your stash (especially if you are holding down alt (or have that longstanding native bug were DaD thinks you are holding alt until you tap it again))
  - Moving your mouse while a routine is active may click the wrong place or fail, Take hand off mouse after pressing a hotkey for best results
  - Some fuctions require a minimum in-game Merchant reputation (do your alch/surgeon quests to get the green potion and bandage unlock for the invest med buying func)
