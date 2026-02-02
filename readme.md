# Dark And Darker Lobby Helper

## Goal

Improve the functionality and convenience of Dark and Darker's pre-game lobby.

## Fuctionality

Use hotkeys to do common things in the pre-game lobby such as vendor treasure, transfer inventory, buy meds, execute buy list on market, ReSquire, go to common crafters, ... and much more.

## Requirements

  - This version is made for 1920x1080 screen res
  - Install auto-hotkey v2 productivity tool (this is just what I happend to code it in, but in theory could be done with any coding language).
  - Functions are designed to work when logged into a character and in the pre-game lobby.

## How to Run

  1. Clone/download this repo, Run the script "DarkAndDarkerLobbyHelper.ank"
  2. Launch "Dark and Darker", Log into a character and be in the Pre-Game Lobby at 1920x1080p res (this doesn't work elsewhere)

## Default Keybinds

These are set up in "src/Keybinds.ank". You can change them if you like in that code file.
  
  - **Left Cntrl** (Or Right Cntrl if there is no overlap (see Right Cntrl below)) +
    - U - Set Volume to 1 (press Esc first)
    - numpad0 - Insta-Queue - a dangerous but speedy button
    - numpad2 - Hotswap Characters (go to prev character)
    - numpad3 - Go to Squire and fill
    - numpad4 - Go to Stash
    - numpad5 - Gather all from expressman
    - numpad6 - Gather all from goblin
    - numpad7 - Sell at Collector
    - numpad8 - Sell at Vendor
    - numpad9 - Go To Marketplace Search
    - numpadSub - Buy 15 Bandages
    - numpadAdd - Buy 15 Potions
    - B - Buy 15 Bandages
    - O - Buy 15 Potions
    - P - Go To Class Spec
    - 5 - Go To Goblin Purchase
    - 6 - Go To Alchemist Service
    - 7 - Go to Leathersmithing Service
    - 8 - Go to Armourer Service
    - 9 - Go to Tailoring Service
    - 0 - Go to Weaponsmith Service

  - **Right Cntrl** + 
    - U - Set Volume to 100 (press Esc first)
    - numpadSub - Buy 6 Bandages
    - numpadAdd - Buy 6 Potions
    - B - Buy 6 Bandages
    - O - Buy 6 Potions
    - 1 - Go To Squire Sets
    - K - Refill Squire Kit
    - Alt+K - Full Squire Reset (DANGER: sells entire inventory and equipped kit)
    - M - Go To Search Marketplace
    - Q - Insta-Queue
    - ALT+Q - ToolBelt Reset and Requeue (designed for arena)
    - H - Hotswap characters (go to last selected character)
    - Alt+I - Invest in green pots and bandages (buy out, check availablity  first)
    - E - Gather All From Expressman
    - G - Gather All From Goblin
    - A - Go To Goldsmith
    - Alt+G - Buy Kit Off Market from GearBuyingSettings File
    - Alt+H - Halt(when buying) Stop the buying process on next iteration
    - C - Gather All From Cockatrice
    - J - Go To Jewel Collector
    - X - Vendor All Collector Items (waits for confirm)
    - V - Go To Vendor
    - Z - Vender All Non-Collector Items (waits for confirm)
    - T - Move All Inventory To Stash Routine

## Known Issues

  - there can be issues with the lobby being slower than expected, in which case the delay globals constants need increased in [src/LobbyButtonFunctionsLibrary.ank](src/LobbyButtonFunctionsLibrary.ank)
  - there is an issue with some DaD UI buttons occasionally not functioning. (appears to be an native game UI problem)
  - the de-equip routine will sometimes throw things in your stash (especially if you are holding down alt (or have that longstanding native bug were DaD thinks you are holding alt until you tap it again))
  - Moving your mouse while a routine is active may click the wrong place or fail, Take hand off mouse after pressing a hotkey for best results
  - Some fuctions require a minimum in-game Merchant reputation (do your alch/surgeon quests to get the green potion and bandage unlock for the invest med buying func)
