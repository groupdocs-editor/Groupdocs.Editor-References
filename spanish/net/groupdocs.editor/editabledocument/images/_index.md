---
title: "Imágenes"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite obtener recursos de imágenes externas, raster y vectoriales, que son utilizados por este documento HTML"
type: docs
weight: 80
url: /es/net/groupdocs.editor/editabledocument/images/
---
## EditableDocument.Images property

Permite obtener recursos de imágenes externas (imágenes raster y vectoriales), que son utilizados por este documento HTML

```csharp
public List<IImageResource> Images { get; }
```

### Observaciones

Este método devuelve una copia superficial de todos los recursos de imagen utilizados: `List` es una nueva instancia para cada llamada, pero las instancias de los recursos son las mismas.

### Ver también

* interface [IImageResource](../../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
