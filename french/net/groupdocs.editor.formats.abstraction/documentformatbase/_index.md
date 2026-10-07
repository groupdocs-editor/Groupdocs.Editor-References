---
title: "DocumentFormatBase"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente la classe de base pour les formats de documents, offrant une fonctionnalité commune aux instances de format."
type: docs
weight: 50
url: /fr/net/groupdocs.editor.formats.abstraction/documentformatbase/
---
## DocumentFormatBase class

Représente la classe de base pour les formats de documents, offrant une fonctionnalité commune aux instances de format.

```csharp
public abstract class DocumentFormatBase : FormatFamilyBase, IDocumentFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtient l'extension de fichier du format de document. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtient la famille de formats à laquelle le format de document appartient. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtient l'identifiant unique de la famille de formats. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtient le type MIME du format de document. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtient le nom de la famille de formats. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Détermine si cette instance est égale à l'instance [`FormatFamilyBase`](../formatfamilybase) spécifiée. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_1)(IDocumentFormat) | Détermine si cette instance est égale à l'instance [`IDocumentFormat`](../idocumentformat) spécifiée. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_2)(object) | Détermine si cette instance est égale à l'instance [`DocumentFormatBase`](../documentformatbase) spécifiée. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Renvoie un code de hachage pour l'objet actuel. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| static [FromMime&lt;T&gt;](../../groupdocs.editor.formats.abstraction/documentformatbase/frommime)(string) | Récupère une instance du type spécifié *T* qui possède le type MIME spécifié. |
| [implicit operator](../../groupdocs.editor.formats.abstraction/documentformatbase/op_implicit) | Convertit implicitement une instance de [`DocumentFormatBase`](../documentformatbase) en chaîne. |

### Voir aussi

* class [FormatFamilyBase](../formatfamilybase)
* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
