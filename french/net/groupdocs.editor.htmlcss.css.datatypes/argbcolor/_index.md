---
title: ArgbColor
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Représente une valeur de couleur au format ARGB avec convertisseurs et sérialiseurs
type: docs
weight: 190
url: /fr/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Représente une valeur de couleur au format ARGB avec convertisseurs et sérialiseurs

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Obtient la partie alpha de la couleur. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Obtient la partie alpha de la couleur en pourcentage (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Obtient la partie bleue de la couleur. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Obtient la partie verte de la couleur. |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Couleur non initialisée - les 4 canaux sont réglés sur 0. Identique à Par défaut et Transparent. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Indique si cela[`ArgbColor`](../argbcolor) l'instance est entièrement opaque, sans transparence (son canal Alpha a une valeur maximale) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Indique si cela[`ArgbColor`](../argbcolor) est entièrement transparente - son canal Alpha a la valeur min (0), donc les autres canaux R, G et B n'ont aucun effet visible. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Indique si cela[`ArgbColor`](../argbcolor) l'instance est translucide (pas totalement transparente, mais pas non plus totalement opaque) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Obtient la partie rouge de la couleur. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Obtient la valeur Int32 de la couleur. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | en crée un[`ArgbColor`](../argbcolor) valeur des canaux rouges, verts et bleus spécifiés, tandis que le canal Alpha est entièrement opaque |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | en crée un[`ArgbColor`](../argbcolor) valeur des canaux rouges, verts, bleus et alpha spécifiés |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Crée une couleur entièrement opaque (A=255) à partir d'une seule valeur, qui sera appliquée à tous les canaux |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Vérifie deux[`ArgbColor`](../argbcolor) couleurs pour l'égalité |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Teste si un autre objet est égal à celui-ci[`ArgbColor`](../argbcolor) instance. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Renvoie un code de hachage qui définit la couleur actuelle. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | sérialise ceci[`ArgbColor`](../argbcolor)instance à la notation de fonction CSS la plus appropriée en fonction de translucency |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | sérialise ceci[`ArgbColor`](../argbcolor) instance à la fonction CSS 'rgb' notation |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | sérialise ceci[`ArgbColor`](../argbcolor) instance à la fonction CSS 'rgba' notation |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Identique à[`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Compare deux couleurs et renvoie un booléen indiquant si les deux correspondent. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Compare deux couleurs et renvoie un booléen indiquant si les deux ne correspondent pas. |

## Autres membres

| Nom | La description |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Contient toutes les "couleurs connues", qui ont un nom et une valeur uniques fixes dans CSS standart |

### Remarques

Ce type est conçu pour être utile pour (mais sans s'y limiter) les opérations CSS. Voir plus : https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Voir également

* interface [ICssDataType](../icssdatatype)
* espace de noms [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
