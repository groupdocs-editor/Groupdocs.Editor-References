---
title: "GeneratePreview"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Genera y devuelve una vista previa de la diapositiva seleccionada en forma de imagen SVG"
type: docs
weight: 50
url: /es/net/groupdocs.editor.metadata/presentationdocumentinfo/generatepreview/
---
## PresentationDocumentInfo.GeneratePreview method

Genera y devuelve una vista previa de la diapositiva seleccionada en forma de imagen SVG

```csharp
public SvgImage GeneratePreview(int slideIndex)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| slideIndex | Int32 | Índice basado en cero de la diapositiva deseada. No puede ser menor que 0, no puede exceder el número de diapositivas en esta presentación. |

### Valor devuelto

Imagen SVG como la instancia no nula de la clase [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | El *slideIndex* especificado es menor que 0 o mayor que el número de diapositivas en esta presentación. |

### Ver también

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [PresentationDocumentInfo](../../presentationdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
