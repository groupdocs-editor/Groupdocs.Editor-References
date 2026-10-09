---
title: "TextDirection"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt 3 mögliche Varianten dar, wie die Textausrichtung in Klartextdokumenten behandelt wird"
type: docs
weight: 38
url: /de/nodejs-java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

Stellt 3 mögliche Varianten dar, wie die Textausrichtung im Klartext behandelt wird
Dokumente

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | Links‑nach‑Rechts‑Richtung, üblicher Text, Standardwert. |
|
|  | [RightToLeft](#RightToLeft) | Rechts‑nach‑Links‑Richtung |
|
|  | [Auto](#Auto) | Richtung automatisch erkennen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


Links‑nach‑Rechts‑Richtung, üblicher Text, Standardwert.


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


Rechts‑nach‑Links‑Richtung


### Auto {#Auto}
```
public static final int Auto
```


Richtung automatisch erkennen. Wenn diese Option ausgewählt ist und der Text enthält
Zeichen, die zu RTL‑Schriften gehören, wird die Dokumentenrichtung festgelegt
automatisch auf RTL.


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
