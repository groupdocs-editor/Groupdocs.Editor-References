---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Encapsula todos los formatos de procesamiento de texto."
type: docs
weight: 17
url: /es/java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

Encapsula todos los formatos de procesamiento de texto. Incluye los siguientes tipos de archivo:
[Doc](../../com.groupdocs.editor.formats/wordprocessingformats#Doc),
[Docm](../../com.groupdocs.editor.formats/wordprocessingformats#Docm),
[Docx](../../com.groupdocs.editor.formats/wordprocessingformats#Docx),
[Dot](../../com.groupdocs.editor.formats/wordprocessingformats#Dot),
[Dotm](../../com.groupdocs.editor.formats/wordprocessingformats#Dotm),
[Dotx](../../com.groupdocs.editor.formats/wordprocessingformats#Dotx),
[FlatOpc](../../com.groupdocs.editor.formats/wordprocessingformats#FlatOpc),
[Odt](../../com.groupdocs.editor.formats/wordprocessingformats#Odt),
[Ott](../../com.groupdocs.editor.formats/wordprocessingformats#Ott),
[Rtf](../../com.groupdocs.editor.formats/wordprocessingformats#Rtf),
[WordML](../../com.groupdocs.editor.formats/wordprocessingformats#WordML).
Obtenga más información sobre los formatos de procesamiento de texto [aquí](../https://wiki.fileformat.com/word-processing).

Los códigos MIME se obtienen de los recursos proporcionados:
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Doc](#Doc) | El formato de archivo binario MS Word 97-2007 (DOC) representa documentos generados por Microsoft Word u otros procesadores de texto en formato de archivo binario. |
|
|  | [Docx](#Docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) es un formato bien conocido para documentos de Microsoft Word. |
|
|  | [Dot](#Dot) | MS Word 97-2007 Template (DOT) son archivos de plantilla creados por Microsoft Word que tienen configuraciones preformateadas para la generación de futuros archivos DOC o DOCX. |
|
|  | [Docm](#Docm) | Los archivos Office Open XML WordProcessingML Macro-Enabled Document (DOCM) son documentos generados por Microsoft Word 2007 o superior con la capacidad de ejecutar macros. |
|
|  | [Dotx](#Dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) son archivos de plantilla creados por Microsoft Word con configuraciones preformateadas para la generación de futuros archivos DOCX. |
|
|  | [Dotm](#Dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) representa archivos de plantilla creados con Microsoft Word 2007 o superior. |
|
|  | [FlatOpc](#FlatOpc) | Office Open XML WordprocessingML se almacena en un archivo XML plano en lugar de un paquete ZIP. |
|
|  | [Rtf](#Rtf) | Rich Text Format (RTF) representa un método de codificación de texto formateado y gráficos para su uso dentro de aplicaciones. |
|
|  | [Odt](#Odt) | Los archivos Open Document Format Text Document (ODT) son un tipo de documentos creados con aplicaciones de procesamiento de texto basadas en el formato de archivo OpenDocument Text. |
|
|  | [Ott](#Ott) | Open Document Format Text Document Template (OTT) representa documentos de plantilla generados por aplicaciones en cumplimiento con el formato estándar OpenDocument de OASIS. |
|
|  | [WordML](#WordML) | Microsoft Office Word 2003 XML Format \\u2014 WordProcessingML o WordML (.XML). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAll()](#getAll--) | Obtiene una colección enumerable de todos los [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Recupera una instancia del tipo especificado [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) que tiene la extensión de archivo especificada. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Convierte una cadena que representa una extensión de archivo a un objeto [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


El formato de archivo binario MS Word 97-2007 (DOC) representa documentos generados por Microsoft Word u otros procesadores de texto en formato de archivo binario.
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


Office Open XML WordProcessingML Macro-Free Document (DOCX) es un formato bien conocido para documentos de Microsoft Word.
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


MS Word 97-2007 Template (DOT) son archivos de plantilla creados por Microsoft Word que tienen configuraciones preformateadas para la generación de futuros archivos DOC o DOCX.
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


Los archivos Office Open XML WordProcessingML Macro-Enabled Document (DOCM) son documentos generados por Microsoft Word 2007 o superior con la capacidad de ejecutar macros.
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


Office Open XML WordprocessingML Macro-Free Template (DOTX) son archivos de plantilla creados por Microsoft Word con configuraciones preformateadas para la generación de futuros archivos DOCX.
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


Office Open XML WordprocessingML Macro-Enabled Template (DOTM) representa archivos de plantilla creados con Microsoft Word 2007 o superior.
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


Office Open XML WordprocessingML se almacena en un archivo XML plano en lugar de un paquete ZIP.


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


Rich Text Format (RTF) representa un método de codificación de texto formateado y gráficos para su uso dentro de aplicaciones.
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


Los archivos Open Document Format Text Document (ODT) son un tipo de documentos creados con aplicaciones de procesamiento de texto basadas en el formato de archivo OpenDocument Text.
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


Open Document Format Text Document Template (OTT) representa documentos de plantilla generados por aplicaciones en cumplimiento con el formato estándar OpenDocument de OASIS.
Obtén más información sobre este formato de archivo
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


Microsoft Office Word 2003 XML Format \\u2014 WordProcessingML o WordML (.XML).

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


Obtiene una colección enumerable de todos los [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).
Valor: Un IEnumerable{WordProcessingFormats} que contiene todas las instancias de [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


Recupera una instancia del tipo especificado [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) que tiene la extensión de archivo especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | La extensión de archivo del formato del documento. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


Convierte una cadena que representa una extensión de archivo a un objeto [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | La extensión de archivo a convertir. Si la extensión contiene varios puntos, se usa la parte después del último punto. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.

