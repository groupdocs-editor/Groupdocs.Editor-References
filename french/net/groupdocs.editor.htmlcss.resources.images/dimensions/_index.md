---
title: "Dimensions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente les dimensions linéaires largeur et hauteur d'une image raster rectangulaire en unité arbitraire. Structure immuable."
type: docs
weight: 450
url: /fr/net/groupdocs.editor.htmlcss.resources.images/dimensions/
---
## Dimensions structure

Représente les dimensions linéaires (largeur et hauteur) d’une image raster rectangulaire en unité arbitraire. Structure immuable.

```csharp
public struct Dimensions : ICloneable, IEquatable<Dimensions>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Dimensions](dimensions)(ushort, ushort) | Crée une nouvelle instance à partir de la largeur et de la hauteur spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Empty](../../groupdocs.editor.htmlcss.resources.images/dimensions/empty) { get; } | Renvoie une instance Dimensions vide |
| [Area](../../groupdocs.editor.htmlcss.resources.images/dimensions/area) { get; } | Renvoie une surface (Largeur x Hauteur) |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/dimensions/aspectratio) { get; } | Ratio d'aspect de ces dimensions sous forme largeur/hauteur |
| [Height](../../groupdocs.editor.htmlcss.resources.images/dimensions/height) { get; } | Renvoie la hauteur de l'image. |
| [IsEmpty](../../groupdocs.editor.htmlcss.resources.images/dimensions/isempty) { get; } | Détermine si cette instance "Dimensions" est vide et par défaut, c.-à-d. qu'elle ne stocke pas la largeur et la hauteur correctes |
| [IsSquare](../../groupdocs.editor.htmlcss.resources.images/dimensions/issquare) { get; } | Détermine si le 'Dimensions' spécifié représente un carré, c.-à-d. si la largeur est égale à la hauteur |
| [Width](../../groupdocs.editor.htmlcss.resources.images/dimensions/width) { get; } | Renvoie la largeur de l'image |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.editor.htmlcss.resources.images/dimensions/clone)() | Renvoie une copie complète de cette instance |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals)(Dimensions) | Détermine si cette instance est égale à l'instance "Dimensions" spécifiée |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals_1)(object) | Détermine si cette instance est égale à l'objet non converti spécifié, qui est probablement une autre instance "Dimensions" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/dimensions/gethashcode)() | Renvoie un code de hachage pour cette instance, qui ne peut pas être modifié pendant sa durée de vie |
| [ProportionallyResizeForNewHeight](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewheight)(ushort) | Crée et renvoie une nouvelle instance "Dimensions", qui est redimensionnée proportionnellement à partir de l'actuelle, en fonction de la hauteur spécifiée |
| [ProportionallyResizeForNewWidth](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewwidth)(ushort) | Crée et renvoie une nouvelle instance "Dimensions", qui est redimensionnée proportionnellement à partir de l'actuelle, en fonction de la largeur spécifiée |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/dimensions/tostring)() | Renvoie une représentation sous forme de chaîne de caractères de ce "Dimensions" |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_equality) | Vérifie si deux valeurs "Dimensions" sont égales, c.-à-d. qu'elles ont la même largeur et hauteur, ou sont toutes deux vides |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_inequality) | Vérifie si deux valeurs "Dimensions" ne sont pas égales, c.-à-d. que leur largeur et/ou hauteur correspondante sont différentes |

### Voir aussi

* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
