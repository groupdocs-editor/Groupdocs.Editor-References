---
title: "ImageType"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente un format de type d'image pris en charge qui supporte à la fois les formats raster et vectoriels"
type: docs
weight: 480
url: /fr/net/groupdocs.editor.htmlcss.resources.images/imagetype/
---
## ImageType structure

Représente un type d’image (format) pris en charge, supportant les formats raster et vectoriel.

```csharp
public struct ImageType : IEquatable<ImageType>, IResourceType
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [Bmp](../../groupdocs.editor.htmlcss.resources.images/imagetype/bmp) { get; } | Type d'image BMP |
| static [Emf](../../groupdocs.editor.htmlcss.resources.images/imagetype/emf) { get; } | Type d'image vectorielle EMF (Enhanced MetaFile) |
| static [Gif](../../groupdocs.editor.htmlcss.resources.images/imagetype/gif) { get; } | Type d'image GIF |
| static [Icon](../../groupdocs.editor.htmlcss.resources.images/imagetype/icon) { get; } | Type d'image ICON |
| static [Jpeg](../../groupdocs.editor.htmlcss.resources.images/imagetype/jpeg) { get; } | Type d'image JPEG |
| static [Png](../../groupdocs.editor.htmlcss.resources.images/imagetype/png) { get; } | Type d'image PNG |
| static [Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) { get; } | type d'image vectorielle SVG |
| static [Tiff](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) { get; } | type d'image raster TIFF (Tagged Image File Format) |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.images/imagetype/undefined) { get; } | type d'image indéfini - valeur spéciale, qui ne devrait normalement pas se produire |
| static [Wmf](../../groupdocs.editor.htmlcss.resources.images/imagetype/wmf) { get; } | type d'image vectorielle WMF (Windows MetaFile) |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/fileextension) { get; } | Extension de fichier (sans le caractère point initial) d'un type d'image particulier en minuscules. Pour le type Indéfini, renvoie la chaîne 'unsefined'. |
| [FormalName](../../groupdocs.editor.htmlcss.resources.images/imagetype/formalname) { get; } | Renvoie un nom officiel de ce format d'image. Ne renvoie jamais NULL. Si l'instance n'est pas corrompue, ne lève jamais d'exception. |
| [IsVector](../../groupdocs.editor.htmlcss.resources.images/imagetype/isvector) { get; } | Indique si ce format particulier est vectoriel (true) ou raster (false) |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/mimecode) { get; } | Code MIME d'un type d'image particulier sous forme de chaîne. Pour le type Indéfini, renvoie la chaîne 'unsefined'. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefromfilenamewithextension)(string) | Renvoie la valeur ImageType, qui est équivalente à l'extension de nom de fichier, extraite du nom de fichier spécifié |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefrommime)(string) | Renvoie la valeur ImageType, qui est équivalente au code MIME spécifié |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals)(ImageType) | Détermine si cette instance est égale à l'instance "ImageType" spécifiée |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals_1)(object) | Détermine si cette instance est égale à l'objet non casté spécifié, qui est probablement une autre instance "ImageType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/gethashcode)() | Renvoie un code de hachage, qui est un nombre immuable pour cette instance spécifique |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/imagetype/tostring)() | Renvoie la propriété FormalName |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_equality) | Définit si deux instances ImageType spécifiques sont égales |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_inequality) | Définit si deux instances ImageType spécifiques ne sont pas égales |

### Voir aussi

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
