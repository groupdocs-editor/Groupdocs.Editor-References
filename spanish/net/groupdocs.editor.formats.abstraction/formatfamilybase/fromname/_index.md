---
title: "FromName"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Obtiene una instancia del tipo T especificado que tiene el nombre especificado."
type: docs
weight: 60
url: /es/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromname/
---
## FormatFamilyBase.FromName&lt;T&gt; method

Recupera una instancia del tipo especificado *T* que tiene el nombre especificado.

```csharp
public static T FromName<T>(string name)
    where T : FormatFamilyBase
```

| Parameter | Descripción |
| --- | --- |
| T | El tipo de familia de formato. |
| nombre | El nombre de la familia de formato. |

### Valor devuelto

Una instancia del tipo *T* especificado con el nombre especificado.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se lanza cuando no se encuentra una familia de formato coincidente. |

### Ver también

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
