---
title: "AudioType"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente un format de type audio pris en charge"
type: docs
weight: 320
url: /fr/net/groupdocs.editor.htmlcss.resources.audio/audiotype/
---
## AudioType structure

Représente un type audio pris en charge (format)

```csharp
public struct AudioType : IEquatable<AudioType>, IResourceType
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [Mp3](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mp3) { get; } | Représente un format audio MPEG-1 Audio Layer III |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.audio/audiotype/undefined) { get; } | Valeur spéciale qui indique un format audio indéfini, inconnu ou non pris en charge |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/fileextension) { get; } | Extension de nom de fichier (sans le caractère point) pour ce format audio |
| [FormalName](../../groupdocs.editor.htmlcss.resources.audio/audiotype/formalname) { get; } | Nom officiel de ce format audio |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mimecode) { get; } | Code MIME pour ce format audio |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/parsefromfilenamewithextension)(string) | Renvoie la valeur AudioType, qui est équivalente à l'extension de nom de fichier extraite du nom de fichier spécifié |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals)(AudioType) | Détermine si cette instance est égale à l'instance "AudioType" spécifiée |
| override [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals_1)(object) | Détermine si cette instance est égale à l'objet non casté spécifié, qui est probablement une autre instance "AudioType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/gethashcode)() | Renvoie un code de hachage, qui est un nombre constant pour ce type de valeur spécifique |
| [operator ==](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_equality) | Vérifie si deux valeurs "AudioType" sont égales |
| [operator !=](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_inequality) | Vérifie si deux valeurs "AudioType" ne sont pas égales |

### Voir aussi

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
