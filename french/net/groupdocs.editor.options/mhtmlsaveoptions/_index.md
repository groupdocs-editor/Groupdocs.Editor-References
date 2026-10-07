---
title: "MhtmlSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour générer et enregistrer l’encapsulation MIME MHTML de documents HTML agrégés"
type: docs
weight: 1020
url: /fr/net/groupdocs.editor.options/mhtmlsaveoptions/
---
## MhtmlSaveOptions class

Permet de spécifier des options personnalisées pour générer et enregistrer les documents MHTML (MIME encapsulation of aggregate HTML documents)

```csharp
public sealed class MhtmlSaveOptions : ISaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MhtmlSaveOptions](mhtmlsaveoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ExportCidUrls](../../groupdocs.editor.options/mhtmlsaveoptions/exportcidurls) { get; set; } | Spécifie s’il faut utiliser des URL CID (Content-ID) pour référencer les ressources (images, polices, CSS) incluses dans les documents MHTML. La valeur par défaut est `false`. |
| [ExportDocumentProperties](../../groupdocs.editor.options/mhtmlsaveoptions/exportdocumentproperties) { get; set; } | Spécifie s’il faut exporter les propriétés de document intégrées et personnalisées vers le MHTML. La valeur par défaut est `false`. |
| [ExportLanguageInformation](../../groupdocs.editor.options/mhtmlsaveoptions/exportlanguageinformation) { get; set; } | Spécifie si les informations de langue sont exportées vers le MHTML. La valeur par défaut est `false`. |

### Voir aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
