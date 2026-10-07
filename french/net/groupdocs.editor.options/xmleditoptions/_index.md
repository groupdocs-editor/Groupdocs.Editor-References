---
title: "XmlEditOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour l'édition de documents XML (eXtensible Markup Language) et leur conversion en HTML"
type: docs
weight: 1270
url: /fr/net/groupdocs.editor.options/xmleditoptions/
---
## XmlEditOptions class

Permet de spécifier des options personnalisées pour l'édition de documents XML (eXtensible Markup Language) et leur conversion en HTML

```csharp
public sealed class XmlEditOptions : IEditOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XmlEditOptions](xmleditoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AttributeValuesQuoteType](../../groupdocs.editor.options/xmleditoptions/attributevaluesquotetype) { get; set; } | Permet de spécifier le type de guillemets (simples ou doubles) pour les valeurs d'attribut. Les guillemets doubles sont la valeur par défaut. |
| [Encoding](../../groupdocs.editor.options/xmleditoptions/encoding) { get; set; } | Encodage des caractères du document texte, qui sera appliqué lors de son ouverture. Par défaut, il est null — l'encodage interne du document sera utilisé. |
| [FixIncorrectStructure](../../groupdocs.editor.options/xmleditoptions/fixincorrectstructure) { get; set; } | Permet d'activer ou de désactiver le mécanisme de correction d'une structure XML corrompue. Désactivé par défaut (false). |
| [FormatOptions](../../groupdocs.editor.options/xmleditoptions/formatoptions) { get; } | Permet d'ajuster le formatage XML qui sera appliqué à la structure XML lorsqu'elle est représentée en HTML. Le formatage par défaut est utilisé et est ajustable. Ne peut pas être nul. |
| [HighlightOptions](../../groupdocs.editor.options/xmleditoptions/highlightoptions) { get; } | Permet d'ajuster la mise en évidence XML qui sera appliquée à la structure XML lorsqu'elle est représentée en HTML. La mise en évidence par défaut est utilisée et est ajustable. Ne peut pas être nulle. |
| [RecognizeEmails](../../groupdocs.editor.options/xmleditoptions/recognizeemails) { get; set; } | Permet d'activer l'algorithme de reconnaissance des adresses e-mail dans les valeurs d'attributs |
| [RecognizeUris](../../groupdocs.editor.options/xmleditoptions/recognizeuris) { get; set; } | Permet d'activer l'algorithme de reconnaissance d'URI |
| [TrimTrailingWhitespaces](../../groupdocs.editor.options/xmleditoptions/trimtrailingwhitespaces) { get; set; } | Permet d'activer la troncature des espaces de fin dans le texte des balises internes. Désactivé par défaut (false) — les espaces de fin seront conservés. |

### Voir aussi

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
