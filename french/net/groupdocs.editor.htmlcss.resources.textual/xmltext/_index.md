---
title: "XmlText"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente une ressource textuelle qui est un XML."
type: docs
weight: 650
url: /fr/net/groupdocs.editor.htmlcss.resources.textual/xmltext/
---
## XmlText class

Représente une ressource textuelle, qui est un XML.

```csharp
public sealed class XmlText : TextResourceBase
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | Renvoie le contenu de cette ressource texte sous forme de flux d'octets avec l'encodage d'origine |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | Renvoie l'encodage de cette ressource textuelle. Retourne généralement UTF-8. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | Renvoie le nom de fichier correct de cette ressource texte, qui se compose du nom et de l'extension |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | Détermine si cette ressource texte est libérée ou non |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | Renvoie le nom de cette ressource texte sans l'extension du fichier |
| [ParsedDocument](../../groupdocs.editor.htmlcss.resources.textual/xmltext/parseddocument) { get; } | Renvoie un "XmlDocument" à partir de cette ressource XML |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | Renvoie le contenu de cette ressource texte sous forme de chaîne standard |
| override [Type](../../groupdocs.editor.htmlcss.resources.textual/xmltext/type) { get; } | Renvoie TextType.Xml |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | Libère cette ressource texte, libérant son contenu et rendant la plupart des méthodes et propriétés non fonctionnelles. Tolérant aux appels multiples. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals)(IHtmlResource) | Vérifie cette instance avec celle spécifiée pour l'égalité. |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | Enregistre cette ressource texte dans le fichier spécifié |

## Événements

| Nom | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | Événement qui se produit lorsque cette ressource texte est libérée |

### Voir aussi

* class [TextResourceBase](../textresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
