---
title: "set_license metod"
second_title: "GroupDocs.Editor för Python via .NET API-referenser"
description: 
type: docs
url: /sv/python-net/groupdocs.editor/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Applicera en licens på den aktuella processen.

```python
def set_license(self, license_source):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| license_source |  | Antingen en strängsökväg till en ``.lic``‑fil eller ett läsbart fil‑liknande objekt som returnerar licensbytarna. Fil‑liknande inmatningar skrivs till en temporär fil innan de skickas till bryggan. |

| Utlöser | Beskrivning |
| :- | :- |
| `TypeError` | Om ``license_source`` varken är en strängsökväg eller ett läsbart fil‑liknande objekt. |

### Se även
* class [`License`](/editor/python-net/groupdocs.editor/license/)
