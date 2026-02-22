---
allegiances:
  - "[[Player View/Groups/Rolling Thunder|Rolling Thunder]]"
  - "[[Player View/Groups/The Eye of the Storm|The Eye of the Storm]]"
enemies:
  - "[[Player View/Groups/Pirates|Pirates]]"
---
#group #playerview
# Overview:
Text
## Characters:
```base
filters:
  and:
    - file.hasTag("stormcouncil")
    - file.hasTag("playerview")
views:
  - type: table
    name: Characters
```