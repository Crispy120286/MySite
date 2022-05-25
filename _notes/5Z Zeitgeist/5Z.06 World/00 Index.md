# Index

<span class="nav">[Locations](#Locations) [NPCs](#NPCs)  [Factions](#Factions)</span>

## Map
%%
```leaflet
id: full-index
markerTag:
	- location
	- event
	- faction
	- npc
image: [[Khorvaire.jpg]]
image: [[Mine of Whitecliff.png]]
defaultZoom: 6.3
zoomDelta: 0.05
unit: mi
scale: 400
```
%%

## Organizations

```dataview
table description as "Description"
WHERE world = "Zeitgeist"
WHERE type = "organization"
SORT file.name ASC
```

## Gods

```dataview
table description as "Description"
WHERE world = "Zeitgeist"
WHERE type = "deity"
SORT file.name ASC
```

## Places

```dataview
table description as "Description"
WHERE world = "Zeitgeist"
WHERE type = "place"
SORT file.name ASC
```

In locations..
- [ ] ## Locations in the swamp

```dataview
table description as "Description" from "TTRPGs/Exandya"
WHERE contains(type,"place") and contains(location,"Labenda Swamp")
SORT file.name ASC
```

## NPCs and monsters

```dataview
table description as "Description" from "TTRPGs/Exandya"
- [ ] WHERE contains(type,"NPC") or contains(type,"faction") or contains(type, "monster") and (contains(location,"Lebenda Swamp") or contains(location, "Labenda Swamp"))
SORT file.name ASC
```