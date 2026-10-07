---
title: "Mp3Audio"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente une ressource audio d'un format arbitraire"
type: docs
weight: 330
url: /fr/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
## Mp3Audio class

Représente une ressource audio d'un format arbitraire

```csharp
public sealed class Mp3Audio : IEquatable<Mp3Audio>, IHtmlResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Mp3Audio](mp3audio)(string, Stream) | Crée une nouvelle classe Mp3Audio à partir du contenu MP3, représenté sous forme de flux d'octets, et avec le nom spécifié |

## Propriétés

| Nom | Description |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/bytecontent) { get; } | Renvoie le contenu de cette police sous forme de flux d'octets |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/filenamewithextension) { get; } | Renvoie le nom de fichier correct de ce contenu MP3, qui comprend le nom et l'extension. Théoriquement, il peut différer du nom. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isdisposed) { get; } | Détermine si ce contenu MP3 est libéré ou non |
| [Name](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/name) { get; } | Renvoie le nom de ce contenu MP3. Habituellement, il ne contient pas l'extension du nom de fichier et peut théoriquement différer du nom de fichier. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/textcontent) { get; } | Renvoie le contenu de cette ressource MP3 sous forme de chaîne encodée en base64. Cette valeur est mise en cache après le premier appel. |
| [Type](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/type) { get; } | Renvoie un AudioType.Mp3 |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/dispose)() | Libère cette ressource MP3, libérant son contenu et rendant la plupart des méthodes et propriétés non fonctionnelles |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals_1)(IHtmlResource) | Vérifie cette instance avec la ressource HTML spécifiée sur l'égalité de référence |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals)(Mp3Audio) | Vérifie cette instance avec la ressource de police spécifiée sur l'égalité de référence |
| [Save](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/save)(string) | Enregistre cette ressource MP3 dans le fichier spécifié |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isvalid)(Stream) | Vérifie si le flux spécifié est un contenu MP3 valide |

## Événements

| Nom | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/disposed) | Événement qui se produit lorsque ce contenu MP3 est libéré |

### Voir aussi

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
