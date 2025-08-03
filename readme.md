# Dark And Darker pre-grame ".ank" scripts

## goal

  Improve the functionality and convenience of Dark and Darker's pre-game lobby.

## fuctionality

  Use hotkeys to do common things in the pre-game lobby such as buy, sell, market, craft, queue, and more...

## requirements

  - auto-hotkey v2
  - dark and darker v89
    - Have most quests done (as some button locations change for things at different affinity levels)
  - 1920x1080 screen res
  - in Character Lobby

## how to run

  0. Have "auto hotkey v2" installed 
  1. Clone/download this repo, Run the script "Keybinds.ank"
  2. Launch "Dark and Darker", Log into a character and be in the Pre-Game Lobby at 1920x1080p res (this doesn't work elsewhere)

## default keybinds

  These are set up in "Keybinds.ank"
  
  - **Left Cntrl** (Or Right Cntrl if there is no overlap (see Right Cntrl below)) +
    - numpad0 - Insta-Queue - a dangerous but speedy button
    - numpad2 - Hotswap Characters (go to prev character)
    - numpad3 - Go to Squire and fill
    - numpad4 - Go to Stash
    - numpad5 - Gather all from expressman
    - numpad6 - Gather all from goblin
    - numpad7 - Sell at Collector
    - numpad8 - Sell at Vendor
    - numpad9 - Go To Marketplace Search
    - numpadSub - Buy 12 Bandages
    - numpadAdd - Buy 12 Potions
    - numpadAdd - Buy 12 Potions
    - B - Buy 12 Bandages
    - O - Buy 12 Potions
    - U - Set Volume to Zero (press Esc first)
    - P - Go To Class Spec
    - 5 - Go To Goblin Purchase
    - 6 - Go To Alchemist Service
    - 7 - Go to Leathersmithing Service
    - 8 - Go to Armourer Service
    - 9 - Go to Tailoring Service
    - 0 - Go to Weaponsmith Service

  - **Right Cntrl** + 
    - numpadSub - Buy 6 Bandages
    - numpadAdd - Buy 6 Potions
    - B - Buy 6 Bandages
    - O - Buy 6 Potions
    - U - Set Volume to Fifty (press Esc first)
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
    - Alt+G - Buy Kit Off Market from GearBuyingSettings File
    - Alt+H - Halt(when buying) Stop the buying process on next iteration
    - C - Gather All From Cockatrice
    - J - Go To Jewel Collector
    - X - Vendor All Collector Items (waits for confirm)
    - V - Go To Vendor
    - Z - Vender All Non-Collector Items (waits for confirm)
    - T - Move All Inventory To Stash Routine

## known issues

  - there can be issues with the lobby being slower than expected, in which case the delays between clicks must be increased, adjust making delays faster with prejudice as it can exacerbate this problem
  - there is an issue with some DaD UI buttons occasionally not functioning. (appears to be an native game UI problem)
  - the de-equip routine will sometimes throw things in your stash (especially if you are holding down alt (or have that longstanding native bug were DaD thinks you are pressing alt until you tap it again))
  - Moving your mouse while something is active may cause it to click the wrong place or fail, take hand off mouse while pressing a hotkey for best results

