---
title: "TextDirection"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar 3 möjliga varianter hur man behandlar textriktning i vanliga textdokument"
type: docs
weight: 38
url: /sv/java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

Representerar 3 möjliga varianter hur man behandlar textriktning i vanlig text
dokument

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | Vänster-till-höger-riktning, vanlig text, standardvärde. |
|
|  | [RightToLeft](#RightToLeft) | Höger-till-vänster-riktning |
|
|  | [Auto](#Auto) | Auto-detektera riktning. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


Vänster-till-höger-riktning, vanlig text, standardvärde.


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


Höger-till-vänster-riktning


### Auto {#Auto}
```
public static final int Auto
```


Auto-detektera riktning. När detta alternativ är valt och text innehåller
tecken som tillhör RTL-skript, kommer dokumentets riktning att sättas
automatiskt till RTL.


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
