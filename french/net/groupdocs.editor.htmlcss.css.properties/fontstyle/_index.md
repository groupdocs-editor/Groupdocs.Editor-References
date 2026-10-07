---
title: "FontStyle"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Defines how the font should be styled with a normal italic or oblique face from its fontfamily."
type: docs
weight: 270
url: /fr/net/groupdocs.editor.htmlcss.css.properties/fontstyle/
---
## FontStyle structure

Définit comment la police doit être stylisée avec : une forme normale, italique ou oblique provenant de sa famille de polices.

```csharp
public struct FontStyle
```

## Propriétés

| Nom | Description |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontstyle/isinitial) { get; } | Indicates whether this font-style has an initial value (Normal) |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontstyle/value) { get; } | Returns a value of this font style as a string |

## Méthodes

| Nom | Description |
| --- | --- |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals)(FontStyle) | Determines whether this font-style instance is equal to specified |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals_1)(object) | Determines whether this font-style instance is equal to specified uncasted |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontstyle/gethashcode)() | Returns a hash-code for this instance |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse)(string, out FontStyle) | Tries to recognize a specified keyword as a proper keyword value of the 'font-style' and return it on success or NULL on failure. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_equality) | Checks whether two "FontStyle" values are equal |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_inequality) | Checks whether two "FontStyle" values are not equal |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Italic](../../groupdocs.editor.htmlcss.css.properties/fontstyle/italic) | Sélectionne une police classée comme italique. Si aucune version italique de la police n'est disponible, une version classée comme oblique est utilisée à la place. Si aucune n'est disponible, le style est simulé artificiellement. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontstyle/normal) | Sélectionne une police classée comme normale au sein d'une famille de polices. Valeur initiale. |
| static readonly [Oblique](../../groupdocs.editor.htmlcss.css.properties/fontstyle/oblique) | Sélectionne une police classée comme oblique. Si aucune version oblique de la police n'est disponible, une version classée comme italique est utilisée à la place. Si aucune n'est disponible, le style est simulé artificiellement. |

### Voir aussi

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
