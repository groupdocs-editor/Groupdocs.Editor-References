---
title: MhtmlSaveOptions
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Permet de spécifier des options personnalisées pour générer et enregistrer les documents MHTML encapsulation MIME des documents HTML agrégés
type: docs
weight: 1010
url: /fr/net/groupdocs.editor.options/mhtmlsaveoptions/
---
## MhtmlSaveOptions class

Permet de spécifier des options personnalisées pour générer et enregistrer les documents MHTML (encapsulation MIME des documents HTML agrégés)

```csharp
public sealed class MhtmlSaveOptions : ISaveOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MhtmlSaveOptions](mhtmlsaveoptions)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [ExportCidUrls](../../groupdocs.editor.options/mhtmlsaveoptions/exportcidurls) { get; set; } | Spécifie s'il faut utiliser les URL CID (Content-ID) pour référencer les ressources (images, polices, CSS) incluses dans les documents MHTML. La valeur par défaut est`FAUX` . |
| [ExportDocumentProperties](../../groupdocs.editor.options/mhtmlsaveoptions/exportdocumentproperties) { get; set; } | Spécifie s'il faut exporter les propriétés de document intégrées et personnalisées vers MHTML. La valeur par défaut est`FAUX` . |
| [ExportLanguageInformation](../../groupdocs.editor.options/mhtmlsaveoptions/exportlanguageinformation) { get; set; } | Spécifie si les informations de langue sont exportées vers MHTML. La valeur par défaut est`FAUX` . |

### Voir également

* interface [ISaveOptions](../isaveoptions)
* espace de noms [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
