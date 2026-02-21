---
allegiances:
enemies:
  - "[[Kai DM Notes/General Notes/The Navy|The Navy]]"
---
#kaidm #group 
# Overview:
Text
## # Characters:
```base
filters:
  and:
    - file.hasTag("pirate")
    - file.hasTag("kaidm")
views:
  - type: table
    name: Table
    sort:
      - property: file.name
        direction: ASC

```