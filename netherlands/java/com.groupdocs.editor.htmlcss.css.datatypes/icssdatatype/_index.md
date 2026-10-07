---
title: "ICssDataType"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Gemeenschappelijke interface voor alle CSS-datatypen die worden gebruikt in de CSS-eigenschappen"
type: docs
weight: 15
url: /nl/java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

Gemeenschappelijke interface voor alle CSS‑datatypes die worden gebruikt in CSS‑eigenschappen.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | Moet een standaard tekenreeksrepresentatie van de huidige waarde van de teruggeven |
datatype
|
|  | [isDefault()](#isDefault--) | Moet definiëren of de huidige waarde van het datatype de standaard is |
waarde voor dit specifieke datatype al dan niet
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


Moet een standaard tekenreeksrepresentatie van de huidige waarde van de teruggeven
datatype


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


Moet definiëren of de huidige waarde van het datatype de standaard is
waarde voor dit specifieke datatype al dan niet


**Returns:**
boolean -
