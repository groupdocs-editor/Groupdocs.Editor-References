---
title: "EBookFormats"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Encapsula todos los formatos de eBook."
type: docs
weight: 10
url: /es/java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

Encapsula todos los formatos eBook. Incluye los siguientes tipos de archivo:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
Obtén más información sobre el formato Mobi [aquí](../https://docs.fileformat.com/ebook/mobi/), y sobre el formato ePub [aquí](../https://docs.fileformat.com/ebook/epub/).

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI es el nombre dado al formato desarrollado para el lector MobiPocket. |
|
|  | [Epub](#Epub) | El formato Electronic Publication (IDPF ePub) es un formato de archivo e-book que ofrece un estándar de publicación digital para editores y consumidores. |
|
|  | [Azw3](#Azw3) | AZW3, también conocido como Kindle Format 8 (KF8), es la versión modificada del formato de archivo digital AZW para eBook desarrollado para dispositivos Amazon Kindle. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAll()](#getAll--) | Obtiene una colección enumerable de todos los [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Recupera una instancia del tipo especificado [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) que tiene la extensión de archivo especificada. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Convierte una cadena que representa una extensión de archivo a un objeto [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI es el nombre dado al formato desarrollado para el lector MobiPocket. También llamado PRC, AZW.
Actualmente es utilizado por Amazon con un esquema DRM ligeramente diferente y se llama AZW.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


El formato Electronic Publication (IDPF ePub) es un formato de archivo e-book que ofrece un estándar de publicación digital para editores y consumidores.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3, también conocido como Kindle Format 8 (KF8), es la versión modificada del formato de archivo digital AZW para eBook desarrollado para dispositivos Amazon Kindle.
El formato es una mejora respecto a los archivos AZW más antiguos.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


Obtiene una colección enumerable de todos los [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).
Valor: Un IEnumerable{EBookFormats} que contiene todas las instancias de [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


Recupera una instancia del tipo especificado [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) que tiene la extensión de archivo especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | La extensión de archivo del formato del documento. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


Convierte una cadena que representa una extensión de archivo a un objeto [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | La extensión de archivo a convertir. Si la extensión contiene varios puntos, se usa la parte después del último punto. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

