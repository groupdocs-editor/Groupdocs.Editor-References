---
title: "Dispose"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Descarta esta instancia de documento Editable, eliminando su contenido y haciendo que sus métodos y propiedades no funcionen"
type: docs
weight: 110
url: /es/net/groupdocs.editor/editabledocument/dispose/
---
## EditableDocument.Dispose method

Elimina esta instancia del documento Editable, descartando su contenido y haciendo que sus métodos y propiedades no funcionen

```csharp
public void Dispose()
```

### Observaciones

Después de invocar este método, llamar a cualquier otro método de esta instancia lanzará una ObjectDisposedException. Es seguro llamar a este método varias veces — todas las llamadas posteriores se ignoran.

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
