---
title: "FormatFamilies"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa las diferentes familias de formatos disponibles en el sistema."
type: docs
weight: 13
url: /es/java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

Representa las diferentes familias de formatos disponibles en el sistema.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [EBook](#EBook) | Representa la familia de formatos eBook. |
|
|  | [Email](#Email) | Representa la familia de formatos Email. |
|
|  | [FixedLayout](#FixedLayout) | Representa la familia de formatos Fixed Layout. |
|
|  | [Presentation](#Presentation) | Representa la familia de formatos Presentation. |
|
|  | [Spreadsheet](#Spreadsheet) | Representa la familia de formatos Spreadsheet. |
|
|  | [Textual](#Textual) | Representa la familia de formatos Textual. |
|
|  | [WordProcessing](#WordProcessing) | Representa la familia de formatos Word Processing. |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


Representa la familia de formatos eBook.
Aprende más sobre el formato Mobi
[here](../https://docs.fileformat.com/ebook/mobi/)
,
sobre el formato AZW3
[here](../https://docs.fileformat.com/ebook/azw3/)
,
y sobre el formato ePub
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


Representa la familia de formatos Email.
Obtén más información sobre el formato de correos electrónicos
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


Representa la familia de formatos Fixed Layout.
Varias aplicaciones de visualización o publicación de documentos permiten a los usuarios abrir (Adobe Acrobat, XPS Viewer) y, a veces, editar (Adobe InDesign) documentos de formatos específicos.
Estas aplicaciones normalmente generan documentos de formato \u201cfixed-page\u201d.
Este formato de documento describe con precisión dónde se coloca el contenido de un documento\u2019s en cada página.
Internamente, el formato PDF o XPS contiene una descripción de cada página, así como instrucciones de dibujo que especifican la disposición del contenido en la página.
Esto es similar a los formatos de imagen, describiendo dónde se muestra el contenido ya sea en forma rasterizada o vectorial.


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


Representa la familia de formatos Presentation.
Obtén más información sobre los formatos de presentación
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


Representa la familia de formatos Spreadsheet.
Todos los formatos binarios, XML y de texto de hojas de cálculo (excluyendo todos los formatos basados en delimitadores de texto con separadores como CSV, TSV, delimitados por punto y coma, etc.), en los que se puede guardar el libro de trabajo.


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Representa la familia de formatos Textual.
Encapsula todos los formatos textuales (basados en texto), incluidos los de marcado (XML, HTML) y otros.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Representa la familia de formatos Word Processing.
Obtén más información sobre los formatos de procesamiento de texto
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

Los códigos MIME se obtienen de los recursos proporcionados: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



