---
allegiances:
enemies:
  - "[[Player View/Groups/The Navy|The Navy]]"
---
#group #playerview
# Overview:
The scourge of the seas. While a disparate group, united only by their shared lack of ethics and lawful conduct, generally Pirates can agree on one thing: they HATE those [[Player View/Groups/The Navy|Navy]] dogs.
## Characters:
```base
filters:
  and:
    - file.hasTag("pirate")
    - file.hasTag("playerview")
views:
  - type: table
    name: Characters
```