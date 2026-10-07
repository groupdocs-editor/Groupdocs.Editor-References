---
title: "ArgbColor"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente une valeur de couleur en format ARGB 32 bits, 8 bits par canal incluant la transparence, avec des convertisseurs et des sérialiseurs."
type: docs
weight: 160
url: /fr/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Représente une valeur de couleur en format ARGB 32 bits (8 bits par canal, y compris la transparence) avec des convertisseurs et des sérialiseurs

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Obtient la partie alpha de la couleur. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Obtient la partie alpha de la couleur en pourcentage (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Obtient la partie bleue de la couleur. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Obtient la partie verte de la couleur. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | Indique si cette instance [`ArgbColor`](../argbcolor) est par défaut (Transparent) - les 4 canaux sont réglés à 0 |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Couleur non initialisée - les 4 canaux sont réglés à 0. Identique à Default et Transparent. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Indique si cette instance [`ArgbColor`](../argbcolor) est totalement opaque, sans transparence (son canal Alpha a la valeur maximale). |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Indique si cette instance [`ArgbColor`](../argbcolor) est totalement transparente - son canal Alpha a la valeur minimale (0), de sorte que les autres canaux R, G et B n'ont aucun effet visible. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Indique si cette instance [`ArgbColor`](../argbcolor) est translucide (ni totalement transparente, ni totalement opaque). |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Obtient la partie rouge de la couleur. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Obtient la valeur Int32 de la couleur. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Crée une valeur [`ArgbColor`](../argbcolor) à partir des canaux Rouge, Vert, Bleu spécifiés, tandis que le canal Alpha est totalement opaque |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Crée une valeur [`ArgbColor`](../argbcolor) à partir des canaux Rouge, Vert, Bleu et Alpha spécifiés |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Crée une couleur totalement opaque (A=255) à partir d’une seule valeur, qui sera appliquée à tous les canaux |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Vérifie l’égalité de deux couleurs [`ArgbColor`](../argbcolor) |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Teste si un autre objet est égal à cette instance [`ArgbColor`](../argbcolor). |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Renvoie un code de hachage qui définit la couleur actuelle. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Sérialise cette instance [`ArgbColor`](../argbcolor) dans la notation de fonction CSS la plus appropriée selon la translucidité |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Sérialise cette instance [`ArgbColor`](../argbcolor) dans la notation de fonction CSS 'rgb' |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Sérialise cette instance [`ArgbColor`](../argbcolor) dans la notation de fonction CSS 'rgba' |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Identique à [`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Compare deux couleurs et renvoie un booléen indiquant si les deux correspondent. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Compare deux couleurs et renvoie un booléen indiquant si les deux ne correspondent pas. |

## Autres membres

| Nom | Description |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Contient toutes les \"couleurs connues\", qui ont un nom et une valeur uniques fixes dans le standard CSS |

### Remarques

Ce type est conçu pour être utile aux opérations CSS (mais pas uniquement). En savoir plus : https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Voir aussi

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
