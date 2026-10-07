---
title: "Ratio"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente un type de données CSS ratio qui est utilisé pour décrire les rapports d'aspect dans les requêtes média et pour les images raster en indiquant la proportion entre deux valeurs sans unité appelées numérateur et dénominateur. Structure immuable."
type: docs
weight: 250
url: /fr/net/groupdocs.editor.htmlcss.css.datatypes/ratio/
---
## Ratio structure

Représente un type de données CSS \"ratio\", qui est utilisé pour décrire les rapports d'aspect dans les requêtes média et pour les images raster en indiquant la proportion entre deux valeurs sans unité appelées \"numérateur\" et \"dénominateur\". Structure immuable.

```csharp
public struct Ratio : ICloneable, ICssDataType, IEquatable<Ratio>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Denominator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/denominator) { get; } | Renvoie le dénominateur de ce ratio |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/isdefault) { get; } | Détermine si ce ratio a la valeur par défaut ou est un "1/1" (Simple) |
| [Numerator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/numerator) { get; } | Renvoie le numérateur de ce ratio |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Create](../../groupdocs.editor.htmlcss.css.datatypes/ratio/create)(ushort, ushort) | Crée et renvoie une instance de Ratio à partir du numérateur et du dénominateur spécifiés |
| [Calculate](../../groupdocs.editor.htmlcss.css.datatypes/ratio/calculate)() | Calcule et renvoie ce ratio sous forme d'un nombre à virgule flottante simple |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/ratio/clone)() | Renvoie une copie complète de ce ratio |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals_1)(object) | Détermine si cette instance est égale à l'objet non casté spécifié, qui est probablement une autre instance de "Ratio" |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals)(Ratio) | Détermine si cette instance est égale à l'instance "Ratio" spécifiée |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/ratio/gethashcode)() | Renvoie un code de hachage pour cette instance, qui ne peut pas être modifié pendant sa durée de vie |
| [GetInverseRatio](../../groupdocs.editor.htmlcss.css.datatypes/ratio/getinverseratio)() | Génère et renvoie un ratio inverse (réciproque) pour ce ratio |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/serializedefault)() | Sérialise ce ratio en chaîne et le renvoie |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/ratio/tostring)() | Renvoie une représentation sous forme de chaîne de ce ratio ; identique à "SerializeDefault()" |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_equality) | Compare deux ratios et renvoie un booléen indiquant si les deux correspondent. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_inequality) | Compare deux rapports et renvoie un booléen indiquant si les deux ne correspondent pas. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Single](../../groupdocs.editor.htmlcss.css.datatypes/ratio/single) | Ratio par défaut unique 1/1 |

### Remarques

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

### Voir aussi

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
