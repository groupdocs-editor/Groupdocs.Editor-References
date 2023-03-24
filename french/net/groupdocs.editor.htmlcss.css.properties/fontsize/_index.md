---
title: FontSize
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Représente une taille de police sous la forme dune unité spéciale ou dune valeur de longueur qui spécifie la taille de la police historiquement la largeur du M majuscule.
type: docs
weight: 290
url: /fr/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Représente une taille de police sous la forme d'une unité spéciale ou d'une valeur de longueur, qui spécifie la taille de la police (historiquement la largeur du "M" majuscule).

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Indique si cette taille de police est définie avec une taille absolue comme mot clé, basée sur la taille de police par défaut de l'utilisateur (qui est moyenne) |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Indique si cette font-size a une valeur initiale (Medium) |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Indique si cette taille de police est définie avec un[`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) value |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Indique si cette taille de police est définie avec une taille relative comme mot-clé. La police sera plus grande ou plus petite par rapport à la taille de police de l'élément parent, à peu près selon le rapport utilisé pour séparer les mots-clés de taille absolue. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Une valeur de longueur, si cette taille de police a été définie avec elle, ou une exception levée sinon |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Renvoie une valeur de cette taille de police sous forme de chaîne |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Crée une taille de police à partir de la longueur spécifiée |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Détermine si cette instance de taille de police est égale à spécifié |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Détermine si cette instance de taille de police est égale à uncasted spécifié |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Renvoie un code de hachage pour cette instance |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Essaie de reconnaître un mot-clé spécifié comme une valeur de mot-clé appropriée de 'font-size' et le renvoie en cas de succès ou NULL en cas d'échec. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Vérifie si deux valeurs "FontSize" sont égales |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Vérifie si deux valeurs "FontSize" ne sont pas égales |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | La taille absolue normalement grande |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Larger relative-size - la police sera plus grande par rapport à la taille de police de l'élément parent, approximativement selon le rapport utilisé pour séparer les mots-clés de taille absolue ci-dessus. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Taille moyenne. Valeur initiale. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | La taille absolue normalement petite |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Taille relative plus petite - la police sera plus petite par rapport à la taille de police de l'élément parent, à peu près par le rapport utilisé pour séparer les mots-clés de taille absolue ci-dessus. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | La grande taille absolue médiocre |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | La petite taille absolue médiocre |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | La très grande taille absolue |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | La très petite taille absolue |

### Voir également

* espace de noms [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
