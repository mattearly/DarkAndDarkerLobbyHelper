# Dark And Darker pre-grame ".ank" scripts

## goal

  Improve the functionality and convenience of Dark and Darker's pre-game lobby

## fuctionality

  Use hotkeys to do common things in the pre-game lobby such as buy, sell, market, queue, and more

## requirements

  auto-hotkey v2

## how to run & use

  0. Have "auto hotkey v2" installed
  1. Run the script "run.ank"
  2. Log into "Dark and Darker", Log into character and in the Pre-Game Lobby (this doesn't work elsewere)
  3. Have most quests done (as some button locations change for things at different affinity levels)
  4. Know Default KeyBindings - change these in "run.ank" to whatever you want
    - cntrl +
      - numpad0 - Insta-Queue - a dangerous but speedy button
      - numpad1 - Go to Leathersmithing Service
      - numpad2 - Go to Tailoring Service
      - numpad3 - Go to Squire and fill
      - numpad4 - Go to Stash
      - numpad5 - Gather all from expressman
      - numpad6 - Gather all from goblin
      - numpad7 - Sell at Collector
      - numpad8 - Sell at Vendor
      - numpad9 - Go To Marketplace
      - numpadDiv - next market seller quickbutton - Setup to 9 classes to level 20 and Market Ready (change function if you have less or more)
      - numpadMulti - Buy White Pickaxe
      - numpadSub - Buy Rogue Arena Kit (3 potions, 2 green bandages)
      - numpadAdd - Buy Potions and Bandages for a run (6 pots, 3 grey bandage, 3 white bandages)
      - numpadDot - Class Spec


## known issues

  - there can be issues with the lobby being slower than expected, in which case the delays between clicks must be increased
  - there is an issue with the dungeon changing and the notification text blocking some of the clicks. There is nothing I can do about this. IronMace needs to make the text non-interactable/non-click blocking (which is one property toggle in Unreal Engine and probably the easist bug to fix of all time (but will they do it?))