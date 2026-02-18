# Characters:
## Player Characters:
```base
filters:
  and:
    - file.hasTag("pc")
    - file.hasTag("dhdm")
views:
  - type: cards
    name: PCs
    order:
      - file.name
    image: note.cover
    imageAspectRatio: 1
    cardSize: 150

```
## Groups:
```base
filters:
  and:
    - file.hasTag("group")
    - file.hasTag("dhdm")
views:
  - type: table
    name: Groups
    order:
      - file.name
      - allegiances
      - enemies
    columnSize:
      file.name: 173
      note.allegiances: 135

```
## Non Player Characters:
```base
filters:
  and:
    - file.hasTag("npc")
    - file.hasTag("dhdm")
views:
  - type: table
    name: NPCs
    order:
      - file.name
      - group
      - allegiances
    sort:
      - property: allegiances
        direction: ASC
      - property: file.name
        direction: ASC
    columnSize:
      file.name: 223
      note.group: 91

```
# Islands:
```base
filters:
  and:
    - file.hasTag("island")
    - file.hasTag("dhdm")
views:
  - type: table
    name: Table
```