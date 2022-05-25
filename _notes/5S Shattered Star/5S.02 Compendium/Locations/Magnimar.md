---
type: location
sub-type: city
location: [-10.62,5.66]
mapmarker:
campaign: "Shattered Star"
description: "Large city where we begin our story."
tags:
 - shattered-star/location/city/magnimar
---
# Magnimar
[[Heidmarch Manor]], a Pathfinder Lodge and home base for characters.

## People
```dataview
table description as "Description"
WHERE contains(type,"NPC") 
WHERE contains(location,"Magnimar")
WHERE contains(campaign,"Shattered Star")
SORT file.name ASC
```
## Places
```dataview
table description as "Description"
WHERE type = "location"
where location = "Magnimar"
SORT file.name ASC
```
### Shops
```dataview
table proprietor as "Proprietor" and type as "Type"
WHERE type = "shop"
where location = "Magnimar"
SORT file.name ASC
```

# The Nine Districts
Alabaster District 
Beacon's Point
Capital District 
Dockway
Keystone
Lowcleft
Naos
Ordellia
Underbridge
