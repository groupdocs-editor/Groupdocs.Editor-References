---
title: "ImagesFolder"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Especifica la carpeta física donde se guardan las imágenes al exportar un documento al formato Markdown. El valor predeterminado es null."
type: docs
weight: 30
url: /es/net/groupdocs.editor.options/markdownsaveoptions/imagesfolder/
---
## MarkdownSaveOptions.ImagesFolder property

Especifica la carpeta física donde se guardan las imágenes al exportar un documento al formato Markdown. El valor predeterminado es null.

```csharp
public string ImagesFolder { get; set; }
```

### Observaciones

Si ni `ImagesFolder` ni [`ExportImagesAsBase64`](../exportimagesasbase64) son especificados por el usuario, entonces GroupDocs.Editor intentará determinar `ImagesFolder` por sí mismo y lo aplicará si tiene éxito

### Ver también

* class [MarkdownSaveOptions](../../markdownsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
