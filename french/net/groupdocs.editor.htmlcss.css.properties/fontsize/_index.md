---
title: "FontSize"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente une taille de police sous forme d'une unité spéciale ou d'une valeur de longueur qui spécifie la taille de la police, historiquement la largeur du M majuscule."
type: docs
weight: 260
url: /fr/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Représente une taille de police comme une unité spéciale ou une valeur de longueur, qui spécifie la taille de la police (historiquement la largeur de la majuscule \"M\").

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Indique si cette taille de police est définie avec une taille absolue sous forme de mot‑clé, basée sur la taille de police par défaut de l'utilisateur (qui est moyenne). |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Indique si cette taille de police possède une valeur initiale (Moyenne). |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Indique si cette taille de police est définie avec une [`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) valeur |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Indique si cette taille de police est définie avec une taille relative sous forme de mot‑clé. La police sera plus grande ou plus petite par rapport à la taille de police de l'élément parent, approximativement selon le ratio utilisé pour séparer les mots‑clés de taille absolue. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Une valeur de longueur, si cette taille de police a été définie avec elle, ou une exception est levée sinon. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Renvoie la valeur de cette taille de police sous forme de chaîne. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Crée une taille de police à partir d'une longueur spécifiée. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Détermine si cette instance de taille de police est égale à celle spécifiée. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Détermine si cette instance de taille de police est égale à celle spécifiée non convertie. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Returns a hash-code for this instance |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Tente de reconnaître un mot‑clé spécifié comme une valeur de mot‑clé appropriée de la propriété 'font-size' et le renvoie en cas de succès ou NULL en cas d'échec. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Vérifie si deux valeurs "FontSize" sont égales. |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Vérifie si deux valeurs "FontSize" ne sont pas égales. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | La taille absolue généralement grande. |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Taille relative plus grande - la police sera plus grande par rapport à la taille de police de l'élément parent, approximativement selon le ratio utilisé pour séparer les mots‑clés de taille absolue ci‑dessus. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Taille moyenne. Valeur initiale. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | La taille absolue généralement petite. |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Taille relative plus petite - la police sera plus petite par rapport à la taille de police de l'élément parent, approximativement selon le ratio utilisé pour séparer les mots‑clés de taille absolue ci‑dessus. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | La taille absolue assez grande. |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | La taille absolue assez petite. |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | La très grande taille absolue. |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | La très petite taille absolue |

### Voir aussi

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
