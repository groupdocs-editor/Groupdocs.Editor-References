---
title: "TextDirection"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt 3 mogelijke varianten voor hoe de tekstrichting in platte‑tekstdocumenten moet worden behandeld"
type: docs
weight: 38
url: /nl/java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

Stelt 3 mogelijke varianten voor hoe de tekstrichting in platte tekst moet worden behandeld
documenten

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | Van links naar rechts richting, gebruikelijke tekst, standaardwaarde. |
|
|  | [RightToLeft](#RightToLeft) | Van rechts naar links richting |
|
|  | [Auto](#Auto) | Automatisch detecteren van richting. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


Van links naar rechts richting, gebruikelijke tekst, standaardwaarde.


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


Van rechts naar links richting


### Auto {#Auto}
```
public static final int Auto
```


Automatisch detecteren van richting. Wanneer deze optie is geselecteerd en tekst bevat
tekens die behoren tot RTL‑scripts, wordt de documentrichting ingesteld
automatisch op RTL.


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
