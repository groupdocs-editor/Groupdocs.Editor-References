---
title: ExportImagesAsBase64
second_title: GroupDocs.Editor för .NET API-referens
description: Anger om bilder sparas i Base64format till utdatafilen. Standard ärfalsk .
type: docs
weight: 20
url: /sv/net/groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64/
---
## MarkdownSaveOptions.ExportImagesAsBase64 property

Anger om bilder sparas i Base64-format till utdatafilen. Standard är`falsk` .

```csharp
public bool ExportImagesAsBase64 { get; set; }
```

### Anmärkningar

När den här egenskapen är inställd på`Sann` sedan exporteras bilddata direkt till bildelementen ![]() och separata filer skapas inte. Denna egenskap, om den är inställd på`Sann` , har högre prioritet än[`ImagesFolder`](../imagesfolder) fast egendom.

### Se även

* class [MarkdownSaveOptions](../../markdownsaveoptions)
* namnutrymme [GroupDocs.Editor.Options](../../markdownsaveoptions)
* hopsättning [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->