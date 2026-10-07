---
title: "FontWeight"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "La propriété Fontweight définit le poids ou l'épaisseur de la police. Les poids disponibles dépendent de la fontfamily qui est actuellement définie."
type: docs
weight: 280
url: /fr/net/groupdocs.editor.htmlcss.css.properties/fontweight/
---
## FontWeight structure

La propriété font-weight définit le poids (ou l'épaisseur) de la police. Les poids disponibles dépendent de la famille de polices actuellement définie.

```csharp
public struct FontWeight : IEquatable<FontWeight>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.properties/fontweight/isabsolute) { get; } | Indique si cette instance de font-weight stocke une valeur absolue du poids (épaisseur) de la police, sous forme d'un nombre entier. |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontweight/isinitial) { get; } | Indique si cette taille de police possède une valeur initiale (Moyenne). |
| [IsRelative](../../groupdocs.editor.htmlcss.css.properties/fontweight/isrelative) { get; } | Indique si cette instance de font-weight stocke une valeur relative du poids (épaisseur) de la police - comparée à l'épaisseur de l'élément parent. |
| [Number](../../groupdocs.editor.htmlcss.css.properties/fontweight/number) { get; } | Renvoie un nombre - valeur entière comprise entre 1 et 1000, inclus, qui décrit l'épaisseur de la police, ou lève une exception si l'épaisseur actuelle n'est pas absolue, mais relative. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontweight/value) { get; } | Renvoie une valeur de ce font-weight sous forme de chaîne. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromNumber](../../groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber)(ushort) | Crée un font-weight à partir du nombre spécifié. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals)(FontWeight) | Détermine si les instances de FontWeight spécifiées sont égales. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals_1)(object) | Détermine si cette instance de FontWeight est égale à l'instance non convertie spécifiée. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontweight/gethashcode)() | Returns a hash-code for this instance |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontweight/tryparse)(string, out FontWeight) | Essaie d'analyser une chaîne spécifiée et renvoie une instance valide de FontWeight en cas de succès. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_equality) | Vérifie si deux valeurs "FontWeight" sont égales. |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_inequality) | Vérifie si deux valeurs "FontWeight" ne sont pas égales. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Bold](../../groupdocs.editor.htmlcss.css.properties/fontweight/bold) | Poids de police gras. Identique à 700. |
| static readonly [Bolder](../../groupdocs.editor.htmlcss.css.properties/fontweight/bolder) | Un poids de police relatif plus lourd que l'élément parent. |
| static readonly [Lighter](../../groupdocs.editor.htmlcss.css.properties/fontweight/lighter) | Un poids de police relatif plus léger que l'élément parent. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontweight/normal) | Poids de police normal. Identique à 400. |

### Voir aussi

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
