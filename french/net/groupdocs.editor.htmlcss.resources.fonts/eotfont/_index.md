---
title: "EotFont"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente une police au format EOT Embedded OpenType"
type: docs
weight: 340
url: /fr/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
## EotFont class

Représente une police au format EOT (Embedded OpenType).

```csharp
public sealed class EotFont : FontResourceBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EotFont](eotfont#constructor)(string, Stream) | Crée une nouvelle classe EotFont à partir du contenu, représenté sous forme de flux d'octets, et avec le nom spécifié |
| [EotFont](eotfont#constructor_1)(string, string) | Crée une nouvelle classe EotFont à partir du contenu, représenté sous forme de chaîne encodée en base64, et avec le nom spécifié |

## Propriétés

| Nom | Description |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Renvoie le contenu de cette police sous forme de flux d'octets |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Renvoie le nom de fichier correct de cette ressource de police, qui se compose du nom et de l’extension. Théoriquement, il peut différer du nom. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Détermine si cette police est libérée ou non |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Renvoie le nom de cette ressource de police. Habituellement, il ne contient pas l'extension du nom de fichier et peut théoriquement différer du nom de fichier. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Renvoie le contenu de cette police sous forme de chaîne encodée en base64. Cette valeur est mise en cache après le premier appel. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/eotfont/type) { get; } | Renvoie FontType.Eot |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Libère cette ressource de police, libérant son contenu et rendant la plupart des méthodes et propriétés non fonctionnelles |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | Vérifie cette instance avec la ressource de police spécifiée sur l'égalité de référence |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | Vérifie cette instance avec la ressource HTML spécifiée sur l'égalité de référence |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Enregistre cette police dans le fichier spécifié |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/eotfont/isvalid#isvalid)(Stream) | Vérifie si le flux spécifié est une police EOT valide |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/eotfont/isvalid#isvalid_1)(string) | Vérifie si la chaîne codée en base64 spécifiée est une police EOT valide |

## Champs

| Nom | Description |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/eotfont/requiredheadersize) | Taille de l'en-tête EOT (en octets), requise pour sa validation |

## Événements

| Nom | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Événement qui se produit lorsque cette police est libérée |

### Voir aussi

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
