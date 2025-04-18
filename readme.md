# Dark And Darker pre-grame ".ank" scripts

## goal

  Improve the functionality and convenience of Dark and Darker's pre-game lobby

## fuctionality

  Use hotkeys to do common things in the pre-game lobby such as buy, sell, market, craft, queue, and more

## requirements

  - auto-hotkey v2
  - dark and darker v82
    - Have most quests done (as some button locations change for things at different affinity levels)

## how to run

  0. Have "auto hotkey v2" installed
  1. Run the script "Keybinds.ank"
  2. Launch "Dark and Darker", Log into a character and be in the Pre-Game Lobby at 1920x1080p res (this doesn't work elsewhere)

## default keybinds

  These are set up in "Keybinds.ank"
  
  - **Cntrl** +
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
    - numpad5 - Gather all from expressman
    - numpad6 - Gather all from goblin
    - numpad7 - Sell at Collector
    - numpad8 - Sell at Vendor
    - numpad9 - Go To Marketplace Search
    - numpadDiv - go to next market seller (9 lvl 20+ characters assumption)
    - numpadSub - Buy a Lot of Bandages
    - B - Buy a Lot of Bandages
    - numpadAdd - Buy 12 Potions
    - O - Buy 12 Potions
    - numpadDot - Class Spec

  - **Right Cntrl** + 
    - numpadSub - Buy 4 Bandages
    - B - Buy 4 Bandages
    - numpadAdd - Buy 6 Potions
    - O - Buy 6 Potions
    - Q - Insta-Queue
    - H - Hotswap characters
    - 1 - Go To Squire Sets
    - K - Squire Kit
    - ALT+Q - ToolBelt Reset and Requeue (designed for arena)
    - G - Goblin Retrieval
    - J - Go To Jewel Collector
    - V - Go To Vendor
    - M - Go To Search Marketplace
    - C - Go To Class Spec
    - X - Vendor All Collector
    - Z - Vender All Non-Collector
    - T - Transfer Inventory To Stash Page

## known issues

  - there can be issues with the lobby being slower than expected, in which case the delays between clicks must be increased, adjust making delays faster with prejudice as it can exacerbate this problem
  - there is an issue with the dungeon changing notification blocking some of the clicks. (appears to be a native game UI problem)
  - there is an issue with some buttons occasionally not functioning. (appears to be an native game UI problem)
  - the de-equip routine will sometimes throw things in your stash (especially if you are holding down alt (or have that longstanding native bug were DaD thinks you are pressing alt until you tap it again))
  - there is an issue with not backing out of the marketplace correctly if you hadn't previously gone there with a hotkey (as the program doesn't know to set the flag if you go there manually)

