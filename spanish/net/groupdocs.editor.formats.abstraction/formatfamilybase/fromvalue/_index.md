---
title: "FromValue"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Obtiene una instancia del tipo T especificado que tiene el identificador especificado."
type: docs
weight: 70
url: /es/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue/
---
## FormatFamilyBase.FromValue&lt;T&gt; method

Recupera una instancia del tipo especificado *T* que tiene el identificador especificado.

```csharp
public static T FromValue<T>(int value)
    where T : FormatFamilyBase
```

| Parameter | Descripción |
| --- | --- |
| T | El tipo de familia de formato. |
| valor | El identificador de la familia de formato. |

### Valor devuelto

Una instancia del tipo *T* especificado con el identificador especificado.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se lanza cuando no se encuentra una familia de formato coincidente. |

### Ver también

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
