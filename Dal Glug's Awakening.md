---
type: campaign
tags: dnd
created: 2022-09-15 03:33:27 -07:00
updated: 2023-01-28 11:36:04 -08:00
---
# Dal Glug's Awakening
## *Frogs Campaign Season One*

## Sessions
```dataview
TABLE location as "Locations", date as "Session Date"
FROM "Dungeons and Dragons/Frogs Campaign/Session Notes"
WHERE campaign = "Dal Glug's Awakening"
SORT file.name desc
```

## Player Characters
```dataview
TABLE race AS "Race", class AS "Class"
FROM "Dungeons and Dragons/Frogs Campaign/People" AND -#former-pc
WHERE type = "character" AND campaign = "Dal Glug's Awakening"
```

## NPCs
```dataview
TABLE description as "Description", location as "Location"
FROM "Dungeons and Dragons/Frogs Campaign/People"
WHERE type = "npc" AND campaign = "Dal Glug's Awakening" 
```

## Locations
```dataview
TABLE description as Description
FROM "Dungeons and Dragons/Frogs Campaign/Locations"
WHERE type = "location" AND campaign = "Dal Glug's Awakening"
```

## Key Objects

## Questlines
### Main Quests
#### Obtain the [[Keys of the Beast]]
- [x] [[King Fleshbarg's Key]]
- [ ] [[Troll's Key]]
- [ ] [[Orc's Key]]
- We can take a dirigible from [[Yi]] to [[Orcida]]
- [ ] [[Gnome's Key]]
- Also in [[Orcida]]?
- [ ] [[Lizardfolk's Key]]
- The lizardfolk have leadership in the [[Kidneys]], according to [[Renwick]]
- [ ] [[Goblin's Key]]

#### Miscellaneous
- [ ] Pick up [[Urgon Walfa]] on [[Scaramar]] when we leave the [[Andees]]
- [ ] Look into the [[Authority]] and [[Incash Gurzarita]] for [[Renwick]], due to increasing [[Writtle Fruit]] requirements in exchange for decreasing quality of fresh blood

### Side Quests
#### Destroy the Damien the Vampire
- [ ] Find out where he resides