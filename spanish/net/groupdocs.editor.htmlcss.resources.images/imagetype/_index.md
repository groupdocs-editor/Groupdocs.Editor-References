---
title: "ImageType"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa un formato de tipo de imagen compatible que admite tanto formatos raster como vectoriales"
type: docs
weight: 480
url: /es/net/groupdocs.editor.htmlcss.resources.images/imagetype/
---
## ImageType structure

Representa un tipo de imagen compatible (formato), admite tanto formatos raster como vectoriales.

```csharp
public struct ImageType : IEquatable<ImageType>, IResourceType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Bmp](../../groupdocs.editor.htmlcss.resources.images/imagetype/bmp) { get; } | Tipo de imagen BMP |
| static [Emf](../../groupdocs.editor.htmlcss.resources.images/imagetype/emf) { get; } | Tipo de imagen vectorial EMF (Enhanced MetaFile) |
| static [Gif](../../groupdocs.editor.htmlcss.resources.images/imagetype/gif) { get; } | Tipo de imagen GIF |
| static [Icon](../../groupdocs.editor.htmlcss.resources.images/imagetype/icon) { get; } | Tipo de imagen ICON |
| static [Jpeg](../../groupdocs.editor.htmlcss.resources.images/imagetype/jpeg) { get; } | Tipo de imagen JPEG |
| static [Png](../../groupdocs.editor.htmlcss.resources.images/imagetype/png) { get; } | Tipo de imagen PNG |
| static [Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) { get; } | Tipo de imagen vectorial SVG |
| static [Tiff](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) { get; } | Tipo de imagen raster TIFF (Tagged Image File Format) |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.images/imagetype/undefined) { get; } | Tipo de imagen indefinido - valor especial, que normalmente no debería ocurrir |
| static [Wmf](../../groupdocs.editor.htmlcss.resources.images/imagetype/wmf) { get; } | Tipo de imagen vectorial WMF (Windows MetaFile) |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/fileextension) { get; } | Extensión de archivo (sin el carácter de punto inicial) de un tipo de imagen particular en minúsculas. Para el tipo Undefined devuelve la cadena 'unsefined'. |
| [FormalName](../../groupdocs.editor.htmlcss.resources.images/imagetype/formalname) { get; } | Devuelve un nombre formal de este formato de imagen. Nunca devuelve NULL. Si la instancia no está corrupta, nunca lanza una excepción. |
| [IsVector](../../groupdocs.editor.htmlcss.resources.images/imagetype/isvector) { get; } | Indica si este formato particular es vectorial (true) o raster (false) |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/mimecode) { get; } | Código MIME de un tipo de imagen particular como cadena. Para el tipo Undefined devuelve la cadena 'unsefined'. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefromfilenamewithextension)(string) | Devuelve el valor ImageType, que es equivalente a la extensión del nombre de archivo, extraída del nombre de archivo especificado |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefrommime)(string) | Devuelve el valor ImageType, que es equivalente al código MIME especificado |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals)(ImageType) | Determina si esta instancia es igual a la instancia "ImageType" especificada |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals_1)(object) | Determina si esta instancia es igual al objeto no convertido especificado, que presumiblemente es otra instancia "ImageType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/gethashcode)() | Devuelve un código hash, que es un número inmutable para esta instancia específica |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/imagetype/tostring)() | Devuelve la propiedad FormalName |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_equality) | Define si dos instancias específicas de ImageType son iguales |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_inequality) | Define si dos instancias específicas de ImageType no son iguales |

### Ver también

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
