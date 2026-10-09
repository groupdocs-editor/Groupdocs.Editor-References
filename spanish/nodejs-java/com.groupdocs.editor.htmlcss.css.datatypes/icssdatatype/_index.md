---
title: "ICssDataType"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Interfaz común para todos los tipos de datos CSS que se utilizan en las propiedades CSS"
type: docs
weight: 15
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

Interfaz común para todos los tipos de datos CSS, que se utilizan en las propiedades CSS.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | Debe devolver una representación de cadena predeterminada del valor actual del |
tipo de dato
|
|  | [isDefault()](#isDefault--) | Debe definir si el valor actual del tipo de dato es el predeterminado |
valor para este tipo de dato específico o no
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


Debe devolver una representación de cadena predeterminada del valor actual del
tipo de dato


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


Debe definir si el valor actual del tipo de dato es el predeterminado
valor para este tipo de dato específico o no


**Returns:**
boolean -
