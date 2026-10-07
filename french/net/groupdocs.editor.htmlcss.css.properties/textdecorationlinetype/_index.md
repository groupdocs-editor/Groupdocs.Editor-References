---
title: "TextDecorationLineType"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente les types de ligne de décoration du texte underline, underscore, overline et linethrough (strikethrough)."
type: docs
weight: 290
url: /fr/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

Représente les types de ligne de décoration du texte : souligné (underscore), surligné et barré (strikethrough)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | Indique si cette instance possède une valeur initiale — None. |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | Indique si le line-through (strikethrough) est activé. |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | Indique si le overline est activé. |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | Indique si le underline (underscore) est activé. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | Renvoie une valeur de tous les drapeaux de cette instance sous forme de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | Crée et renvoie une instance de [`TextDecorationLineType`](../textdecorationlinetype) avec les drapeaux définis par les paramètres spécifiés. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | Indique si cette instance [`TextDecorationLineType`](../textdecorationlinetype) est égale à la valeur non convertie spécifiée |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | Indique si cette instance [`TextDecorationLineType`](../textdecorationlinetype) est égale à la valeur spécifiée |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | Renvoie un code de hachage de cette instance |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | Renvoie une valeur de tous les drapeaux de cette instance sous forme de texte. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | Tente d’analyser une chaîne spécifiée et renvoie une instance valide de [`TextDecorationLineType`](../textdecorationlinetype) |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | Combine (fusionne) deux types de ligne spécifiés et produit un nouveau type de ligne résultant, où les indicateurs sont fusionnés (union) |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | Renvoie une intersection entre le premier et le deuxième types de ligne, où seuls les indicateurs activés simultanément dans les deux opérandes sont activés. Possède la priorité la plus élevée parmi tous les opérateurs (supérieure à l’union et à la différence) |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | Vérifie si deux valeurs "TextDecorationLineType" sont égales |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | Convertit un octet (Byte de 8 bits) spécifique en le [`TextDecorationLineType`](../textdecorationlinetype) correspondant, lève une exception si la conversion est invalide (2 opérateurs) |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | Vérifie si deux valeurs "TextDecorationLineType" ne sont pas égales |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | Soustrait le deuxième type de ligne spécifié du premier type de ligne spécifié et produit un nouveau type de ligne résultant, où ne sont présents que les indicateurs du premier opérande qui ne se trouvent pas dans le deuxième opérande (différence) |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | Chaque ligne de texte possède une ligne traversant le milieu. |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | Produit aucune décoration de texte. Valeur initiale. |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | Chaque ligne de texte possède une ligne au-dessus. |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | Chaque ligne de texte est soulignée. |

### Remarques

Structure immuable. Similaire à https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

### Voir aussi

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
