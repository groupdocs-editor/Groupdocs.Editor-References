---
title: "IHtmlResource"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente une instance d'une ressource HTML inconnue raster ou vecteur image feuille de style police texte ressource CSS XML audio, etc."
type: docs
weight: 430
url: /fr/net/groupdocs.editor.htmlcss.resources/ihtmlresource/
---
## IHtmlResource interface

Représente une instance d'une ressource HTML inconnue (image raster ou vectorielle, feuille de style, police, ressource texte (CSS, XML), audio, etc.)

```csharp
public interface IHtmlResource : IAuxDisposable, IEquatable<IHtmlResource>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/bytecontent) { get; } | Contenu de la ressource HTML sous forme de flux d'octets |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) { get; } | Nom de fichier correct de la ressource spécifiée avec l'extension de fichier appropriée |
| [Name](../../groupdocs.editor.htmlcss.resources/ihtmlresource/name) { get; } | Nom de la ressource HTML |
| [TextContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/textcontent) { get; } | Contenu de la ressource HTML sous forme de chaîne de texte encodée en base64 pour les ressources binaires ou de texte simple pour les ressources textuelles |
| [Type](../../groupdocs.editor.htmlcss.resources/ihtmlresource/type) { get; } | Type de la ressource HTML |

## Méthodes

| Nom | Description |
| --- | --- |
| [Save](../../groupdocs.editor.htmlcss.resources/ihtmlresource/save)(string) | Enregistre la ressource actuelle dans le fichier spécifié |

### Voir aussi

* interface [IAuxDisposable](../iauxdisposable)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
