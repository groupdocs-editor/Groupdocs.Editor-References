---
title: "ICssDataType"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Interfaz común para todos los tipos de datos CSS que se utilizan en las propiedades CSS"
type: docs
weight: 15
url: /es/java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

Interfaz común para todos los tipos de datos CSS, que se utilizan en las propiedades CSS

## Métodos

| Método | Descripción |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | Debe devolver una representación de cadena predeterminada del valor actual del |
tipo de datos
|
|  | [isDefault()](#isDefault--) | Debe definir si el valor actual del tipo de datos es el predeterminado |
valor para este tipo de datos específico o no
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


Debe devolver una representación de cadena predeterminada del valor actual del
tipo de datos


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


Debe definir si el valor actual del tipo de datos es el predeterminado
valor para este tipo de datos específico o no


**Returns:**
boolean -
