---
title: "EBookFormats"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Encapsula todos los formatos de eBook. Incluye los siguientes tipos de archivo Mobi./ebookformats/mobi Epub./ebookformats/epub Azw3./ebookformats/azw3."
type: docs
weight: 80
url: /es/net/groupdocs.editor.formats/ebookformats/
---
## EBookFormats class

Encapsula todos los formatos de eBook. Incluye los siguientes tipos de archivo: [`Mobi`](./mobi), [`Epub`](./epub), [`Azw3`](./azw3).

```csharp
public class EBookFormats : DocumentFormatBase
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtiene la extensión de archivo del formato de documento. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtiene la familia de formato a la que pertenece el formato de documento. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtiene el identificador único de la familia de formato. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtiene el tipo MIME del formato de documento. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtiene el nombre de la familia de formato. |
| static [All](../../groupdocs.editor.formats/ebookformats/all) { get; } | Obtiene una colección enumerable de todos los [`EBookFormats`](../ebookformats). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/ebookformats/fromextension)(string) | Recupera una instancia del tipo especificado [`EBookFormats`](../ebookformats) que tiene la extensión de archivo especificada. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina si esta instancia es igual a la instancia especificada de [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determina si esta instancia es igual a la instancia especificada de [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determina si esta instancia es igual a la instancia especificada de [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Devuelve un código hash para el objeto actual. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Devuelve una cadena que representa el objeto actual. |
| [explicit operator](../../groupdocs.editor.formats/ebookformats/op_explicit) | Convierte una cadena que representa una extensión de archivo a un objeto [`EBookFormats`](../ebookformats). |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Azw3](../../groupdocs.editor.formats/ebookformats/azw3) | AZW3, también conocido como Kindle Format 8 (KF8), es la versión modificada del formato de libro digital AZW desarrollado para dispositivos Amazon Kindle. El formato es una mejora respecto a los archivos AZW más antiguos. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/ebook/azw3/). |
| static readonly [Epub](../../groupdocs.editor.formats/ebookformats/epub) | El formato Electronic Publication (IDPF ePub) es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar para editores y consumidores. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Mobi](../../groupdocs.editor.formats/ebookformats/mobi) | MOBI es el nombre dado al formato desarrollado para el lector MobiPocket. También llamado PRC, AZW. Actualmente es utilizado por Amazon con un esquema DRM ligeramente diferente y se llama AZW. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/ebook/mobi/). |

### Observaciones

Obtenga más información sobre el formato Mobi [aquí](https://docs.fileformat.com/ebook/mobi/), sobre el formato AZW3 [aquí](https://docs.fileformat.com/ebook/azw3/), y sobre el formato ePub [aquí](https://docs.fileformat.com/ebook/epub/).

### Ver también

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
