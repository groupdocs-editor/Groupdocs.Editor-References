---
title: "ICssDataType"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Vanligt gränssnitt för alla CSS-datatyper som används i CSS-egenskaperna"
type: docs
weight: 15
url: /sv/java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

Gemensamt gränssnitt för alla CSS‑datatyper som används i CSS‑egenskaper.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | Ska returnera en standardsträngrepresentation av det aktuella värdet för |
datatyp
|
|  | [isDefault()](#isDefault--) | Ska definiera om det aktuella värdet för datatypen är standardvärdet |
värde för denna specifika datatyp eller inte
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


Ska returnera en standardsträngrepresentation av det aktuella värdet för
datatyp


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


Ska definiera om det aktuella värdet för datatypen är standardvärdet
värde för denna specifika datatyp eller inte


**Returns:**
boolean -
