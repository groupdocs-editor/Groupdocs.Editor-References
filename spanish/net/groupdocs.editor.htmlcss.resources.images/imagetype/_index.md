---
title: ImageType
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Representa un tipo de imagen compatible formato admite formatos ráster y vectoriales
type: docs
weight: 490
url: /es/net/groupdocs.editor.htmlcss.resources.images/imagetype/
---
## ImageType structure

Representa un tipo de imagen compatible (formato), admite formatos ráster y vectoriales

```csharp
public struct ImageType : IEquatable<ImageType>, IResourceType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Bmp](../../groupdocs.editor.htmlcss.resources.images/imagetype/bmp) { get; } | tipo de imagen BMP |
| static [Emf](../../groupdocs.editor.htmlcss.resources.images/imagetype/emf) { get; } | EMF (Metaarchivo mejorado) tipo de imagen vectorial |
| static [Gif](../../groupdocs.editor.htmlcss.resources.images/imagetype/gif) { get; } | tipo de imagen GIF |
| static [Icon](../../groupdocs.editor.htmlcss.resources.images/imagetype/icon) { get; } | ICONO tipo de imagen |
| static [Jpeg](../../groupdocs.editor.htmlcss.resources.images/imagetype/jpeg) { get; } | tipo de imagen JPEG |
| static [Png](../../groupdocs.editor.htmlcss.resources.images/imagetype/png) { get; } | tipo de imagen PNG |
| static [Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) { get; } | Tipo de imagen vectorial SVG |
| static [Tiff](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) { get; } | TIFF (Formato de archivo de imagen etiquetado) tipo de imagen ráster |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.images/imagetype/undefined) { get; } | Tipo de imagen indefinido: valor especial, que normalmente no debería ocurrir |
| static [Wmf](../../groupdocs.editor.htmlcss.resources.images/imagetype/wmf) { get; } | WMF (Windows MetaFile) tipo de imagen vectorial |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/fileextension) { get; } | Extensión de archivo (sin carácter de punto inicial) de un tipo de imagen particular en minúsculas. Para el tipo Indefinido devuelve una cadena 'unsefined'. |
| [FormalName](../../groupdocs.editor.htmlcss.resources.images/imagetype/formalname) { get; } | Devuelve un nombre formal de este formato de imagen. Nunca devuelve NULL. Si la instancia no está dañada, nunca lanza una excepción. |
| [Format](../../groupdocs.editor.htmlcss.resources.images/imagetype/format) { get; } | Descripción del formato de imagen estándar de .NET de un formato de imagen en particular, si tiene una representación específica de .NET. Para el tipo Indefinido devuelve un valor nulo. Para todos los formatos, que no están representados en .NET, arroja una InvalidOperationException. |
| [IsVector](../../groupdocs.editor.htmlcss.resources.images/imagetype/isvector) { get; } | Indica si este formato en particular es vectorial (verdadero) o ráster (falso) |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/mimecode) { get; } | Código MIME de un tipo de imagen en particular como una cadena. Para el tipo Indefinido devuelve una cadena 'unsefined'. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefromfilenamewithextension)(string) | Devuelve el valor ImageType, que es equivalente a la extensión del nombre de archivo, que se extrae del nombre de archivo especificado |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefrommime)(string) | Devuelve el valor de ImageType, que es equivalente al código MIME especificado |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals)(ImageType) | Determina si esta instancia es igual a la instancia "ImageType" especificada |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals_1)(object) | Determina si esta instancia es igual al objeto no emitido especificado, que presumiblemente es otra instancia de "ImageType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/gethashcode)() | Devuelve un código hash, que es un número inmutable para esta instancia específica |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/imagetype/tostring)() | Devuelve una propiedad FormalName |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_equality) | Define si dos instancias específicas de ImageType son iguales |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_inequality) | Define si dos instancias específicas de ImageType no son iguales |

### Ver también

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* espacio de nombres [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
