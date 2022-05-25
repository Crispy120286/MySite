---
type: location
location: Varisia
campaign: "Shattered Star"
description: ""
tags:
 - shattered-star/location/nation
---
# Varisia

## Places
```dataview
table description as "Description"
WHERE contains(type,"location") and contains(location,"Varisia") 
SORT file.name ASC
```

## People
```dataview
table description as "Description"
WHERE contains(type,"NPC") and contains(location,"Varisia") 
SORT file.name ASC
```
## History

## Map
```leaflet
id: index
height: 500px
image: [[Varisia Drawn.jpg]]
defaultZoom: 5
zoomDelta: 0.5
unit: miles
scale: 41
```