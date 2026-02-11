# about the GearBuyingSettings.txt file

Fill each line with a syntax. Market search and purchase based on these settings will be performed.

## mode 1 - by name

`item_name,search_offset,item_rarity,modifier1,modifier2`

- special mode1 options: item_name as `*ring`, `*neck`, or `*back` searches by slot

## mode 2 - by class name, gear slot, rarity, static stat, and magic mods

`class_name,slot_name,item_rarity,static_stat,modifier1,modifier2`

- class name must be spelled out to activate mode 2

## definitions

### item_rarity

- 0 = none specified
- 1 = rare
- 2 = epic
- 3 = legendary
- 4 = unique
- 5 = artifact

### search offset

- how many rows down to click on item name (useful for when item is not at top of list, even when fully spelling it out)
- keep this 0 most of the time, unless you notice the above

### static stat

- white stat search

### modifiers

- the random enchants

## samples

`*ring,0,0,action,add phys`

- buys cheapest ring with action speed and add physical damage

`*neck,0,0,action`

- buys cheapest amulet with action speed

 `frost am,0,2`

- buys the cheapest epic frost amulet

`fighter,hand,0,dex,action`

- buys cheapest fighter gloves with static dex stat and action speed enchant

`fighter,ches,0,vig,agil`

- buys cheapest fighter chestpiece with white vigor stat and agility enchant

`sturdy boots,0,2`

- buys the cheapest epic sturdy boots