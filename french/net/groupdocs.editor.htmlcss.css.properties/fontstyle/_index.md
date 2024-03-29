---
title: FontStyle
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Définit comment la police doit être stylée avec  une face normale italique ou oblique de sa famille de polices.
type: docs
weight: 300
url: /fr/net/groupdocs.editor.htmlcss.css.properties/fontstyle/
---
## FontStyle structure

Définit comment la police doit être stylée avec : une face normale, italique ou oblique de sa famille de polices.

```csharp
public struct FontStyle
```

## Propriétés

| Nom | La description |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontstyle/isinitial) { get; } | Indique si ce style de police a une valeur initiale (Normal) |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontstyle/value) { get; } | Renvoie une valeur de ce style de police sous forme de chaîne |

## Méthodes

| Nom | La description |
| --- | --- |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals)(FontStyle) | Détermine si cette instance de style de police est égale à spécifié |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals_1)(object) | Détermine si cette instance de style de police est égale à uncasted spécifié |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontstyle/gethashcode)() | Renvoie un code de hachage pour cette instance |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse)(string, out FontStyle) | Essaie de reconnaître un mot-clé spécifié comme une valeur de mot-clé appropriée du 'style de police' et le renvoie en cas de succès ou NULL en cas d'échec. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_equality) | Vérifie si deux valeurs "FontStyle" sont égales |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_inequality) | Vérifie si deux valeurs "FontStyle" ne sont pas égales |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Italic](../../groupdocs.editor.htmlcss.css.properties/fontstyle/italic) | Sélectionne une police classée en italique. Si aucune version italique du visage n'est disponible, une version classée comme oblique est utilisée à la place. Si aucun n'est disponible, le style est artificiellement simulé. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontstyle/normal) | Sélectionne une police classée comme normale dans une famille de polices. Valeur initiale. |
| static readonly [Oblique](../../groupdocs.editor.htmlcss.css.properties/fontstyle/oblique) | Sélectionne une police classée comme oblique. Si aucune version oblique du visage n'est disponible, une version classée en italique est utilisée à la place. Si aucun n'est disponible, le style est artificiellement simulé. |

### Voir également

* espace de noms [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
