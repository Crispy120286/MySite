---
type: organization
organization: "Pathfinder Society"
location: []
campaign: "Shattered Star"
description: "Explorers guild"
tags:
 - shattered-star/organization/pathfinder-society
---
# Pathfinder Society

### Description

The Pathfinder Society has existed for more than 400 years. Members include treasure hunters, explorers, tomb raiders, historians, and vagabonds who roam the farthest reaches of the world seeking lost relics and answers to the world’s most enigmatic and dangerous riddles. These heroes brave vine-choked jungle ruins, ascend snow-capped peaks, and comb sun-seared desert sands in search of buried tombs and monuments of bygone ages. 

Society members send records of their exploits to their venture-captain superiors, who in turn review them for accuracy before forwarding the manuscripts to the leaders of the Pathfinder Society. The most exciting and enlightening of these have the potential to be printed and distrubuted as volumes of the famed Pathfinder Chronicles. 

Though the Pathfinder Society itself isn’t concerned with the specific actions of individual Pathfinder agents, they require those agents and their actions to conform to the general code of exploration, reporting, and cooperation. Those Pathfinders deemed incapable of following these simple rules are removed from the Society. 

Most Pathfinders are trained in the necessary skills at the Grand Lodge in Absalom, but a few experienced adventurers are given field commissions in the Society once they’ve proved they’re capable. Such is likely the case for most Pathfinders participating in the Shattered Star Adventure Path. 

The Society is directed by the Decemvirate—10 masked and secret members whose identities are protected even from each other. It’s not known how long each Decemvirate member occupies the position; likewise, every aspect of their existence, from nomination to election, from meetings to formal public functions, and from day-today functions to retirement, is utterly mysterious. The identity of the Ten is the Society’s most closely guarded secret—one, some say, that the Decemvirate is willing to kill to protect.

The Pathfinder Society is based at the sprawling Grand Lodge of Absalom, but the organization as a whole has many official lodges spread throughout the Inner Sea and toeholds across Golarion.



### Members
```dataview 
list
where type = "NPC" or type = "PC" and organization = "Pathfinder Society"
WHERE campaign = "Shattered Star"
sort file.name asc 
``` 
boop
```dataview
list 
FROM #organization/pathfinder-society/member
WHERE campaign = "Shattered Star"
WHERE none(contains(file.etags, "#organization/pathfinder-society/member/leader"))
```

