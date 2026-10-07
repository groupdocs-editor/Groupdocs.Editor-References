---
title: "XmlHighlightOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Contient des options qui permettent de personnaliser la mise en évidence XML lors de la conversion XMLtoHTML"
type: docs
weight: 1290
url: /fr/net/groupdocs.editor.options/xmlhighlightoptions/
---
## XmlHighlightOptions class

Contient des options qui permettent de personnaliser la mise en évidence du XML lors de la conversion XML vers HTML

```csharp
public sealed class XmlHighlightOptions : IEditOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AttributeNamesFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/attributenamesfontsettings) { get; } | Responsable de la représentation de la police des noms d'attributs |
| [AttributeValuesFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/attributevaluesfontsettings) { get; } | Responsable de la représentation de la police des valeurs d'attributs |
| [CDataFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/cdatafontsettings) { get; } | Responsable de la représentation de la police des sections CDATA (y compris la paire de balises d'ouverture et de fermeture) |
| [HtmlCommentsFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/htmlcommentsfontsettings) { get; } | Responsable de la représentation de la police des commentaires HTML (y compris la paire de balises d'ouverture et de fermeture) |
| [InnerTextFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/innertextfontsettings) { get; } | Responsable de la représentation de la police du texte des balises internes |
| [IsDefault](../../groupdocs.editor.options/xmlhighlightoptions/isdefault) { get; } | Détermine si cet objet d'options de mise en évidence XML possède des paramètres de police par défaut |
| [XmlTagsFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/xmltagsfontsettings) { get; } | Responsable de la représentation de la police des balises XML (crochets angulaires avec les noms de balises) |

## Méthodes

| Nom | Description |
| --- | --- |
| [ResetToDefault](../../groupdocs.editor.options/xmlhighlightoptions/resettodefault)() | Réinitialise les paramètres de police actuels à leurs valeurs par défaut |

### Voir aussi

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
