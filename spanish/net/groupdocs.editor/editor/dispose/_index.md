---
title: "Dispose"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Libera esta instancia de Editor para que libere todos los recursos internos y quede no disponible para uso posterior."
type: docs
weight: 50
url: /es/net/groupdocs.editor/editor/dispose/
---
## Editor.Dispose method

Elimina esta instancia de Editor, liberando todos los recursos internos y haciéndola indisponible para su uso posterior.

```csharp
public void Dispose()
```

### Observaciones

Después de invocar este método, llamar a cualquier otro método de esta instancia lanzará una ObjectDisposedException. Es seguro llamar a este método varias veces — todas las llamadas posteriores se ignoran.

### Ver también

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
