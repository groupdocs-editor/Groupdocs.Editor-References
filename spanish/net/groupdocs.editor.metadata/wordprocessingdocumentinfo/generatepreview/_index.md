---
title: "GeneratePreview"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Genera y devuelve una vista previa de la página seleccionada en forma de imagen SVG"
type: docs
weight: 60
url: /es/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview/
---
## WordProcessingDocumentInfo.GeneratePreview method

Genera y devuelve una vista previa de la página seleccionada en forma de imagen SVG

```csharp
public SvgImage GeneratePreview(int pageIndex)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| pageIndex | Int32 | Índice basado en cero de la página deseada. No puede ser menor que 0, no puede exceder el número de páginas en este documento WordProcessing. |

### Valor devuelto

Imagen SVG como la instancia no nula de la clase [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | El *pageIndex* especificado es menor que 0 o mayor que el número de páginas en este documento WordProcessing. |

### Ver también

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [WordProcessingDocumentInfo](../../wordprocessingdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
