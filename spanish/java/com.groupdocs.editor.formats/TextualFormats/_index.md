---
title: "TextualFormats"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Encapsula todos los formatos basados en texto, incluidos los de marcado XML HTML y otros."
type: docs
weight: 16
url: /es/java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

Encapsula todos los formatos textuales (basados en texto), incluidos los de marcado (XML, HTML) y otros.
Incluye los siguientes formatos:
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Html](#Html) | El documento HyperText Markup Language (HTML) es la extensión para páginas web creadas para mostrarse en navegadores. |
|
|  | [Xml](#Xml) | El documento eXtensible Markup Language (XML) es similar a HTML pero diferente al usar etiquetas para definir objetos. |
|
|  | [Txt](#Txt) | El documento Plain Text (TXT) representa un documento de texto que contiene texto plano en forma de líneas. |
|
|  | [Md](#Md) | Markdown es un lenguaje de marcado ligero para crear texto formateado usando un editor de texto plano. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) es un formato de archivo estándar abierto para compartir datos que utiliza texto legible por humanos para almacenar y transmitir datos. |
|
|  | [Mhtml](#Mhtml) | La encapsulación MIME de documentos HTML agregados es un formato de archivo de página web utilizado para combinar, en un solo archivo informático, el código HTML y sus recursos asociados. |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help es un formato binario de ayuda en línea propietario de Microsoft, que consiste en una colección de páginas HTML, un índice y otras herramientas de navegación. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAll()](#getAll--) | Obtiene una colección enumerable de todos los [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Recupera una instancia del tipo especificado [TextualFormats](../../com.groupdocs.editor.formats/textualformats) que tiene la extensión de archivo especificada. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Convierte una cadena que representa una extensión de archivo a un objeto [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
### Html {#Html}
```
public static final TextualFormats Html
```


El documento HyperText Markup Language (HTML) es la extensión para páginas web creadas para mostrarse en navegadores.
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


El documento eXtensible Markup Language (XML) es similar a HTML pero diferente al usar etiquetas para definir objetos.
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


El documento Plain Text (TXT) representa un documento de texto que contiene texto plano en forma de líneas.
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown es un lenguaje de marcado ligero para crear texto formateado usando un editor de texto plano.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation) es un formato de archivo estándar abierto para compartir datos que utiliza texto legible por humanos para almacenar y transmitir datos.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


La encapsulación MIME de documentos HTML agregados es un formato de archivo de página web utilizado para combinar, en un solo archivo informático, el código HTML y sus recursos asociados.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help es un formato binario de ayuda en línea propietario de Microsoft, que consiste en una colección de páginas HTML, un índice y otras herramientas de navegación.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


Obtiene una colección enumerable de todos los [TextualFormats](../../com.groupdocs.editor.formats/textualformats).
Valor: Un IEnumerable{TextualFormats} que contiene todas las instancias de [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


Recupera una instancia del tipo especificado [TextualFormats](../../com.groupdocs.editor.formats/textualformats) que tiene la extensión de archivo especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | La extensión de archivo del formato del documento. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


Convierte una cadena que representa una extensión de archivo a un objeto [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | La extensión de archivo a convertir. Si la extensión contiene varios puntos, se usa la parte después del último punto. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

