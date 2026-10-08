---
title: "FromMime"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Recupera una instancia del tipo especificado T que tiene el tipo MIME especificado."
type: docs
weight: 60
url: /es/net/groupdocs.editor.formats.abstraction/documentformatbase/frommime/
---
## DocumentFormatBase.FromMime&lt;T&gt; method

Recupera una instancia del tipo especificado *T* que tiene el tipo MIME especificado.

```csharp
public static T FromMime<T>(string mime)
    where T : DocumentFormatBase
```

| Parameter | Descripción |
| --- | --- |
| T | El tipo de formato de documento. |
| mime | El tipo MIME del formato de documento. |

### Valor devuelto

Una instancia del tipo especificado *T* con el tipo MIME especificado.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se lanza cuando no se encuentra un formato de documento coincidente. |

### Ver también

* class [DocumentFormatBase](../../documentformatbase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
