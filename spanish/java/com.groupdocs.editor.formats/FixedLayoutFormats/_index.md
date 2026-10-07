---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Encapsula todos los formatos de diseño fijo, también conocidos como formatos de página fija, que incluyen PDF y XPS; esto no incluye imágenes rasterizadas."
type: docs
weight: 12
url: /es/java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

Encapsula todos los formatos de diseño fijo (también conocido como "página fija") que incluyen PDF y XPS (esto no incluye imágenes rasterizadas)

<br />

*** ** * ** ***

Varias aplicaciones de visualización o publicación de documentos permiten a los usuarios abrir (Adobe Acrobat, XPS Viewer) y, a veces, editar (Adobe InDesign) documentos de formatos específicos. Estas aplicaciones normalmente generan documentos de formato \u201cfixed-page\u201d. Este tipo de formato de documento describe con precisión dónde se coloca el contenido de un documento\u2019s en cada página. Internamente, el formato PDF o XPS contiene una descripción de cada página, así como instrucciones de dibujo que especifican la disposición del contenido en la página. Esto es similar a los formatos de imagen, describiendo dónde se muestra el contenido ya sea en forma rasterizada o vectorial.

<br />


## Campos

| Campo | Descripción |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF) es un tipo de documento creado por Adobe en la década de 1990. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAll()](#getAll--) | Obtiene una colección enumerable de todos los [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Recupera una instancia del tipo especificado [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) que tiene la extensión de archivo especificada. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Convierte una cadena que representa una extensión de archivo a un objeto [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Portable Document Format (PDF) es un tipo de documento creado por Adobe en la década de 1990. El propósito de este formato de archivo fue introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


Obtiene una colección enumerable de todos los [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).
Valor: Un IEnumerable{FixedLayoutFormats} que contiene todas las instancias de [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


Recupera una instancia del tipo especificado [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) que tiene la extensión de archivo especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | La extensión de archivo del formato del documento. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


Convierte una cadena que representa una extensión de archivo a un objeto [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | La extensión de archivo a convertir. Si la extensión contiene varios puntos, se usa la parte después del último punto. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

