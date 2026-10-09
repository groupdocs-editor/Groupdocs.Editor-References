---
title: "ICssDataType"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Gemeinsame Schnittstelle für alle CSS-Datentypen, die in den CSS-Eigenschaften verwendet werden"
type: docs
weight: 15
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

Gemeinsame Schnittstelle für alle CSS-Datentypen, die in CSS-Eigenschaften verwendet werden.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | Sollte eine Standard-String-Darstellung des aktuellen Werts von dem zurückgeben |
Datentyp
|
|  | [isDefault()](#isDefault--) | Sollte festlegen, ob der aktuelle Wert des Datentyps der Standardwert ist |
Wert für diesen spezifischen Datentyp oder nicht
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


Sollte eine Standard-String-Darstellung des aktuellen Werts von dem zurückgeben
Datentyp


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


Sollte festlegen, ob der aktuelle Wert des Datentyps der Standardwert ist
Wert für diesen spezifischen Datentyp oder nicht


**Returns:**
boolean -
