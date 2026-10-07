---
title: "QuoteType"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente les caractères de citation simple et double"
type: docs
weight: 660
url: /fr/net/groupdocs.editor.htmlcss.serialization/quotetype/
---
## QuoteType structure

Représente les caractères de citation - guillemet simple (') et guillemet double (\")

```csharp
public struct QuoteType : IEquatable<QuoteType>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Character](../../groupdocs.editor.htmlcss.serialization/quotetype/character) { get; } | Caractère à encadrer de guillemets |
| [Code](../../groupdocs.editor.htmlcss.serialization/quotetype/code) { get; } | Point de code du caractère actuel (U+0027 ou U+0022) |
| [HtmlEncoded](../../groupdocs.editor.htmlcss.serialization/quotetype/htmlencoded) { get; } | Caractère encodé en HTML |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals_1)(object) | Indique si cette instance du type de guillemet est égale à celle spécifiée non convertie |
| [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals)(QuoteType) | Indique si cette instance du type de guillemet est égale à celle spécifiée |
| override [GetHashCode](../../groupdocs.editor.htmlcss.serialization/quotetype/gethashcode)() | Renvoie un code de hachage pour ce caractère |
| override [ToString](../../groupdocs.editor.htmlcss.serialization/quotetype/tostring)() | Renvoie la chaîne "SingleQuote" ou "DoubleQuote" selon la valeur actuelle |
| [operator ==](../../groupdocs.editor.htmlcss.serialization/quotetype/op_equality) | Vérifie si deux valeurs "QuoteType" sont égales |
| [explicit operator](../../groupdocs.editor.htmlcss.serialization/quotetype/op_explicit#op_explicit) | Convertit l'instance spécifiée de [`QuoteType`](../quotetype) en Char (2 opérateurs) |
| [operator !=](../../groupdocs.editor.htmlcss.serialization/quotetype/op_inequality) | Vérifie si deux valeurs "QuoteType" ne sont pas égales |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [DoubleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/doublequote) | Guillemet double (caractère U+0022 MARQUE DE GUILLEMET) |
| static readonly [SingleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/singlequote) | Guillemet simple (caractère U+0027 APOSTROPHE) |

### Voir aussi

* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
