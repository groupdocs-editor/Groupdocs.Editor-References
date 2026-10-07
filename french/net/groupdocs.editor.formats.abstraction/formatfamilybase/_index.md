---
title: "FormatFamilyBase"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente la classe de base pour les familles de formats fournissant des fonctionnalités communes aux instances de familles de formats."
type: docs
weight: 60
url: /fr/net/groupdocs.editor.formats.abstraction/formatfamilybase/
---
## FormatFamilyBase class

Représente la classe de base pour les familles de formats, offrant une fonctionnalité commune aux instances de famille de format.

```csharp
public abstract class FormatFamilyBase : IEquatable<FormatFamilyBase>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtient l'identifiant unique de la famille de formats. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtient le nom de la famille de formats. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals)(FormatFamilyBase) | Détermine si cette instance est égale à l'instance [`FormatFamilyBase`](../formatfamilybase) spécifiée. |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals_1)(object) | Détermine si cette instance est égale à l'instance [`FormatFamilyBase`](../formatfamilybase) spécifiée. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Renvoie un code de hachage pour l'objet actuel. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| static [FromName&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromname)(string) | Récupère une instance du type spécifié *T* qui possède le nom spécifié. |
| static [FromValue&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue)(int) | Récupère une instance du type spécifié *T* qui possède l'identifiant spécifié. |
| static [GetAll&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/getall)() | Récupère toutes les instances du type spécifié *T* qui dérivent de [`FormatFamilyBase`](../formatfamilybase). |
| [operator ==](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_equality#op_equality) | Détermine si deux instances de [`FormatFamilyBase`](../formatfamilybase) sont égales. (2 opérateurs) |
| [explicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit#op_explicit_1) | Convertit une chaîne représentant le nom d'une famille de formats en objet [`FormatFamilyBase`](../formatfamilybase). (2 opérateurs) |
| [implicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_implicit#op_implicit) | Convertit implicitement une instance de [`FormatFamilyBase`](../formatfamilybase) en entier. (2 opérateurs) |
| [operator !=](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_inequality#op_inequality) | Détermine si deux instances de [`FormatFamilyBase`](../formatfamilybase) ne sont pas égales. (2 opérateurs) |

### Remarques

Cette classe est abstraite et doit être héritée par une classe dérivée qui spécifie les détails réels de la famille de formats.

### Voir aussi

* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
