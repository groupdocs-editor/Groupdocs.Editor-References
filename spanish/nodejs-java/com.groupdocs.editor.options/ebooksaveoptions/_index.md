---
title: "EbookSaveOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Permite especificar opciones personalizadas para generar y guardar el documento en todos los formatos de e-Book compatibles: ePub, MOBI y AZW3."
type: docs
weight: 13
url: /es/nodejs-java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Permite especificar opciones personalizadas para generar y guardar el documento en todos los formatos de libro electrónico compatibles: ePub, MOBI y AZW3.

<br />

*** ** * ** ***

Formatos de e-Book compatibles:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Publicación electrónica)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Formato Kindle 8t)

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | Este constructor sin parámetros crea una nueva instancia de EbookSaveOptions con formato de salida ePub (puede modificarse luego a través de |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | Crea una nueva instancia de [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) con el formato de salida de e-Book obligatorio especificado, mientras que todos los demás parámetros son predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | Especifica el nivel máximo de encabezados en el que dividir el archivo e-Book. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | Especifica el nivel máximo de encabezados en el que dividir el archivo e-Book. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Especifica si exportar las propiedades de documento integradas y personalizadas en el archivo resultante. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Especifica si exportar las propiedades de documento integradas y personalizadas en el archivo resultante. |
|
|  | [getOutputFormat()](#getOutputFormat--) | Especifica el formato del archivo e-Book resultante: IDPF ePub, MOBI o AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | Especifica el formato del archivo e-Book resultante: IDPF ePub, MOBI o AZW3. |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


Este constructor sin parámetros crea una nueva instancia de EbookSaveOptions con formato de salida ePub (puede modificarse luego a través de
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


Crea una nueva instancia de [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) con el formato de salida de e-Book obligatorio especificado, mientras que todos los demás parámetros son predeterminados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | Formato de salida obligatorio, en el que se debe guardar el e-Book |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


Especifica el nivel máximo de encabezados en el que dividir el archivo e-Book. El valor predeterminado es
2
.
Estableciéndolo en
0
desactivará la división, por lo que todo el contenido del e-Book se incorporará en un solo paquete dentro del archivo resultante.

<br />

*** ** * ** ***

Cuando esta propiedad se establece en un valor de 1 a 9, el documento se dividirá en los párrafos formateados usando

**Heading 1**
,
**Heading 2**
,
**Heading 3**
etc. estilos hasta el nivel de encabezado especificado.

Por defecto, solo
**Heading 1**
y
**Heading 2**
los párrafos hacen que el documento se divida.
Establecer esta propiedad a cero (o a un valor menor que cero) hará que el documento no se divida en los párrafos de encabezado en absoluto.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


Especifica el nivel máximo de encabezados en el que dividir el archivo e-Book. El valor predeterminado es
2
.
Estableciéndolo en
0
desactivará la división, por lo que todo el contenido del e-Book se incorporará en un solo paquete dentro del archivo resultante.

<br />

*** ** * ** ***

Cuando esta propiedad se establece en un valor de 1 a 9, el documento se dividirá en los párrafos formateados usando

**Heading 1**
,
**Heading 2**
,
**Heading 3**
etc. estilos hasta el nivel de encabezado especificado.

Por defecto, solo
**Heading 1**
y
**Heading 2**
los párrafos hacen que el documento se divida.
Establecer esta propiedad a cero (o a un valor menor que cero) hará que el documento no se divida en los párrafos de encabezado en absoluto.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Especifica si exportar las propiedades de documento integradas y personalizadas en el archivo resultante.
El valor predeterminado es
false
.


**Returns:**
booleano
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Especifica si exportar las propiedades de documento integradas y personalizadas en el archivo resultante.
El valor predeterminado es
false
.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


Especifica el formato del archivo e-Book resultante: IDPF ePub, MOBI o AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


Especifica el formato del archivo e-Book resultante: IDPF ePub, MOBI o AZW3.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

