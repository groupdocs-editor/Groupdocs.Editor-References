---
title: "FontType"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa un tipo de fuente compatible"
type: docs
weight: 360
url: /es/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
## FontType structure

Representa un tipo de fuente compatible

```csharp
public struct FontType : IEquatable<FontType>, IResourceType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Eot](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/eot) { get; } | Representa un tipo de fuente EOT (Embedded OpenType) |
| static [Otf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/otf) { get; } | Representa un tipo de fuente OTF (OpenType Font) |
| static [Ttc](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttc) { get; } | Representa una fuente TrueType Collection (TTC) |
| static [Ttf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttf) { get; } | Representa un tipo de fuente TTF (TrueType Font) |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/undefined) { get; } | Valor especial, que marca un recurso de fuente indefinido, desconocido o no compatible |
| static [Woff](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff) { get; } | Representa un tipo de fuente WOFF (Web Open Font Format) |
| static [Woff2](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff2) { get; } | Representa un tipo de fuente WOFF2 (Web Open Font Format versión 2) |
| [CssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/cssname) { get; } | Devuelve el nombre compatible con CSS de este tipo de fuente, que se usa en la regla @font-face |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fileextension) { get; } | Extensión de nombre de archivo (sin el carácter punto) para este tipo de fuente |
| [FontFormat](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fontformat) { get; } | Formato de fuente para @font-face |
| [FormalName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/formalname) { get; } | Devuelve un nombre formal de este tipo de fuente |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/mimecode) { get; } | Código MIME de un tipo de fuente particular |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [GetFirstDefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined)(params FontType[]) | Devuelve el primer tipo de fuente del conjunto especificado que no sea un valor \"Undefined\", o el tipo de fuente \"Undefined\" en caso contrario (cuando todos los elementos son \"Undefined\") |
| static [ParseFromCssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromcssname)(string) | Devuelve el valor FontType, que es equivalente al nombre compatible con CSS especificado del tipo de fuente |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromfilenamewithextension)(string) | Devuelve el valor FontType, que es equivalente a la extensión de nombre de archivo extraída del nombre de archivo especificado |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefrommime)(string) | Devuelve el valor FontType, que es equivalente al código MIME especificado |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals)(FontType) | Determina si esta instancia es igual a la instancia \"FontType\" especificada |
| override [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals_1)(object) | Determina si esta instancia es igual al objeto no convertido especificado, que presumiblemente es otra instancia \"FontType\" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/gethashcode)() | Devuelve un código hash, que es un número constante para este tipo de valor específico |
| [operator ==](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_equality) | Comprueba si dos valores \"FontType\" son iguales |
| [operator !=](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_inequality) | Comprueba si dos valores \"FontType\" no son iguales |

### Ver también

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
