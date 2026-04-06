#playerview  #s3mp 
# Main Plot:
```base
filters:
  and:
    - file.hasTag("s3mp")
    - file.hasTag("playerview")
views:
  - type: list
    name: Main Plot
```
