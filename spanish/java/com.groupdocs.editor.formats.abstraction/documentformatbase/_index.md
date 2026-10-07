---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa la clase base para formatos de documento que proporciona funcionalidad común para instancias de formato."
type: docs
weight: 10
url: /es/java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

Representa la clase base para formatos de documento, proporcionando funcionalidad común para instancias de formato.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getMime()](#getMime--) | Obtiene el tipo MIME del formato de documento. |
|
|  | [getExtension()](#getExtension--) | Obtiene la extensión de archivo del formato de documento. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Obtiene la familia de formato a la que pertenece el formato de documento. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | Recupera una instancia del tipo especificado |
T
que tiene el tipo MIME especificado.
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash para el objeto actual. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | Determina si esta instancia es igual a la instancia especificada de [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat). |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia es igual a la instancia especificada de [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase). |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Convierte implícitamente una instancia de [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) a una cadena. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


Obtiene el tipo MIME del formato de documento.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Obtiene la extensión de archivo del formato de documento.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


Obtiene la familia de formato a la que pertenece el formato de documento.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


Recupera una instancia del tipo especificado
T
que tiene el tipo MIME especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | El tipo MIME del formato de documento. |


T
: El tipo de formato de documento.
|

**Returns:**
T - Una instancia del tipo especificado  T  con el tipo MIME especificado.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para el objeto actual.


**Returns:**
int - Un código hash para el objeto actual, combinando los códigos hash del objeto base, tipo MIME, extensión de archivo y familia de formato.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Determina si esta instancia es igual a la instancia especificada de [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | La instancia de [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) para comparar con la instancia actual. |
|

**Returns:**
boolean -  true  si la [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) especificada es igual a la instancia actual; de lo contrario,  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia es igual a la instancia especificada de [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | La instancia de [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) para comparar con la instancia actual. |
|

**Returns:**
boolean -  true  si la [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) especificada es igual a la instancia actual; de lo contrario,  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


Convierte implícitamente una instancia de [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) a una cadena.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | La instancia de [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) a convertir. |
|

**Returns:**
java.lang.String - La extensión de archivo de la instancia de [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase).

