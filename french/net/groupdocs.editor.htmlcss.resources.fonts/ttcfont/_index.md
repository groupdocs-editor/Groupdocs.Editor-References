---
title: "TtcFont"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente une police au format TTC TrueType Collection"
type: docs
weight: 380
url: /fr/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
## TtcFont class

Représente une police au format TTC (TrueType Collection).

```csharp
public sealed class TtcFont : FontResourceBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TtcFont](ttcfont#constructor)(string, Stream) | Crée une nouvelle classe TtcFont à partir du contenu, représenté sous forme de flux d’octets, et avec le nom spécifié |
| [TtcFont](ttcfont#constructor_1)(string, string) | Crée une nouvelle classe TtcFont à partir du contenu, représenté sous forme de chaîne encodée en base64, et avec le nom spécifié |

## Propriétés

| Nom | Description |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Renvoie le contenu de cette police sous forme de flux d'octets |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Renvoie le nom de fichier correct de cette ressource de police, qui se compose du nom et de l’extension. Théoriquement, il peut différer du nom. |
| [FontsNumber](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/fontsnumber) { get; } | Nombre de polices dans ce TTC |
| [HasDsigTable](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/hasdsigtable) { get; } | Indique si ce TTC possède une table DSIG. La table DSIG peut être présente uniquement si le TTC a un en‑tête version 2.0. |
| [HeaderVersion](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/headerversion) { get; } | Version d'en-tête TTC, peut être "1" ou "2" |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Détermine si cette police est libérée ou non |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Renvoie le nom de cette ressource de police. Habituellement, il ne contient pas l'extension du nom de fichier et peut théoriquement différer du nom de fichier. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Renvoie le contenu de cette police sous forme de chaîne encodée en base64. Cette valeur est mise en cache après le premier appel. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/type) { get; } | Renvoie FontType.Ttc |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Libère cette ressource de police, libérant son contenu et rendant la plupart des méthodes et propriétés non fonctionnelles |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | Vérifie cette instance avec la ressource de police spécifiée sur l'égalité de référence |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | Vérifie cette instance avec la ressource HTML spécifiée sur l'égalité de référence |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Enregistre cette police dans le fichier spécifié |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/isvalid#isvalid)(Stream) | Vérifie si le flux spécifié est une police TTC valide |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/isvalid#isvalid_1)(string) | Vérifie si la chaîne encodée en base64 spécifiée est une police TTF valide |

## Champs

| Nom | Description |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/requiredheadersize) | Taille de l'en-tête TTC (en octets), requise pour sa validation |

## Événements

| Nom | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Événement qui se produit lorsque cette police est libérée |

### Remarques

Voir plus : https://docs.fileformat.com/font/ttc/

### Voir aussi

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
