# about the GearBuyingSettings.txt file

Fill each line with a syntax. Market search and purchase based on these setting will be performed.

## mode 1 - by name

`item_name,search_offset,item_rarity,modifier1,modifier2`

- special modes: item_name as `*ring`, `*neck`, or `*back` searches by slot

## mode 2 - by class, static stat, and magic mods

`class_name,slot_name,item_rarity,static_stat,modifier1,modifier2`

## definitions

### item_rarity
- 0 = none specified
- 1 = rare
- 2 = epic
- 3 = legendary
- 4 = unique
- 5 = artifact

## samples

`*ring,0,0,all,true p`

- buys cheapest ring with +1 all and true physical damage


