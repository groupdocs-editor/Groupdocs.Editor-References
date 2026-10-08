---
title: "Css"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite obtener recursos CSS de hojas de estilo, tanto externos como incrustados pero no en línea, que son utilizados por este documento HTML"
type: docs
weight: 60
url: /es/net/groupdocs.editor/editabledocument/css/
---
## EditableDocument.Css property

Permite obtener recursos de hojas de estilo (CSS) (tanto externas como incrustadas, pero no en línea), que son utilizados por este documento HTML

```csharp
public List<CssText> Css { get; }
```

### Observaciones

Este método devuelve una copia superficial de todos los recursos de hojas de estilo utilizados: `List` es una nueva instancia para cada llamada, pero las instancias de los recursos son las mismas.

### Ver también

* class [CssText](../../../groupdocs.editor.htmlcss.resources.textual/csstext)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
