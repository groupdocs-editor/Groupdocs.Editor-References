---
title: "TextType"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa un tipo de recurso textual soportado"
type: docs
weight: 12
url: /es/java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

Representa un tipo de recurso textual soportado

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextType()](#TextType--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Valor especial, que marca texto indefinido, desconocido o no compatible |
recurso
|
|  | [getCss()](#getCss--) | Tipo CSS del recurso textual |
|
|  | [getXml()](#getXml--) | Tipo XML del recurso textual |
|
|  | [getFormalName()](#getFormalName--) | Devuelve un nombre formal de este tipo de recurso textual |
|
|  | [getFileExtension()](#getFileExtension--) | Extensión de archivo (sin el carácter de punto inicial) de un texto particular |
recurso
|
|  | [getMimeCode()](#getMimeCode--) | Código MIME de un tipo de recurso textual particular |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Determina si esta instancia es igual a la \"TextType\" especificada |
instancia
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia es igual al objeto sin convertir especificado, |
que presumiblemente es otra instancia de \"TextType\"
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Define si dos instancias específicas de \"TextType\" son iguales |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Define si dos instancias específicas de \"TextType\" no son iguales |
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash, que es un número constante para este valor específico |
tipo
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Devuelve el valor TextType, que equivale a la extensión de nombre de archivo, extraída del nombre de archivo especificado con extensión o de la extensión pura |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


Valor especial, que marca texto indefinido, desconocido o no compatible
recurso


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


Tipo CSS del recurso textual


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


Tipo XML del recurso textual


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Devuelve un nombre formal de este tipo de recurso textual


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Extensión de archivo (sin el carácter de punto inicial) de un texto particular
recurso


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Código MIME de un tipo de recurso textual particular


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


Determina si esta instancia es igual a la \"TextType\" especificada
instancia


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Otra instancia de TextType, que debe compararse con esta para igualdad |
|

**Returns:**
boolean - Devuelve true si son iguales o false si son diferentes

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia es igual al objeto sin convertir especificado,
que presumiblemente es otra instancia de \"TextType\"


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Otra instancia de TextType, que está encapsulada en un objeto |
|

**Returns:**
boolean - Devuelve true si son iguales o false si son diferentes

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


Define si dos instancias específicas de \"TextType\" son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Primera instancia de TextType |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Segunda instancia de TextType |
|

**Returns:**
boolean - Devuelve true si son iguales o false si son diferentes

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


Define si dos instancias específicas de \"TextType\" no son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Primera instancia de TextType |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Segunda instancia de TextType |
|

**Returns:**
boolean - Devuelve true si son diferentes o false si son iguales

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash, que es un número constante para este valor específico
tipo


**Returns:**
int - Número entero con signo de 4 bytes. Devuelve 0 si esta instancia tiene el valor predeterminado.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


Devuelve el valor TextType, que equivale a la extensión de nombre de archivo, extraída del nombre de archivo especificado con extensión o de la extensión pura


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre de archivo | java.lang.String | Nombre de archivo con extensión, puede ser una ruta relativa o absoluta, o la propia extensión pura |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

