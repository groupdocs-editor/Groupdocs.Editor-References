---
title: XmlEditOptions
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Permet de spécifier des options personnalisées pour charger des documents XML eXtensible Markup Language et les convertir au format HTML
type: docs
weight: 1040
url: /fr/net/groupdocs.editor.options/xmleditoptions/
---
## XmlEditOptions class

Permet de spécifier des options personnalisées pour charger des documents XML (eXtensible Markup Language) et les convertir au format HTML

```csharp
public sealed class XmlEditOptions : IEditOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [XmlEditOptions](xmleditoptions)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AttributeValuesQuoteType](../../groupdocs.editor.options/xmleditoptions/attributevaluesquotetype) { get; set; } | Permet de spécifier le type de guillemets (guillemets simples ou doubles) pour les valeurs d'attribut. Les guillemets sont par défaut. |
| [Encoding](../../groupdocs.editor.options/xmleditoptions/encoding) { get; set; } | Encodage des caractères du document texte, qui sera appliqué pour son ouverture. Par défaut, est nul — l'encodage interne du document sera appliqué. |
| [FixIncorrectStructure](../../groupdocs.editor.options/xmleditoptions/fixincorrectstructure) { get; set; } | Permet d'activer ou de désactiver le mécanisme de réparation de la structure XML corrompue. Par défaut est désactivé (false). |
| [HighlightOptions](../../groupdocs.editor.options/xmleditoptions/highlightoptions) { get; set; } | Permet d'ajuster la surbrillance, qui sera appliquée à la structure XML, lorsqu'elle est représentée en HTML. Par défaut est NULL — la surbrillance par défaut est appliquée. |
| [RecognizeEmails](../../groupdocs.editor.options/xmleditoptions/recognizeemails) { get; set; } | Permet d'activer l'algorithme de reconnaissance des adresses e-mail dans les valeurs d'attribut |
| [RecognizeUris](../../groupdocs.editor.options/xmleditoptions/recognizeuris) { get; set; } | Permet d'activer l'algorithme de reconnaissance d'URI |
| [TrimTrailingWhitespaces](../../groupdocs.editor.options/xmleditoptions/trimtrailingwhitespaces) { get; set; } | Permet d'activer la troncature des espaces de fin dans le texte de la balise interne. Par défaut est désactivé (false) — les espaces de fin seront préservés. |

### Voir également

* interface [IEditOptions](../ieditoptions)
* espace de noms [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->