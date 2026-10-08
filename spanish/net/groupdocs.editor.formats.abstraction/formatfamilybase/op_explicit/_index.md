---
title: "op_Explicit"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Convierte una cadena que representa un nombre de familia de formato a un objeto FormatFamilyBasegroupdocs.editor.formats.abstraction/formatfamilybase."
type: docs
weight: 100
url: /es/net/groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit/
---
## explicit operator {#op_explicit_1}

Convierte una cadena que representa un nombre de familia de formato a un objeto [`FormatFamilyBase`](../../formatfamilybase).

```csharp
public static explicit operator FormatFamilyBase(string family)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| familia | String | El nombre de la familia de formato a convertir. |

### Valor devuelto

Un objeto [`FormatFamilyBase`](../../formatfamilybase) correspondiente al nombre de familia de formato especificado.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando el nombre de familia de formato especificado no es válido. |

### Ver también

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

Convierte un entero que representa un ID de familia de formato a un objeto [`FormatFamilyBase`](../../formatfamilybase).

```csharp
public static explicit operator FormatFamilyBase(int id)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| id | Int32 | El ID de la familia de formato a convertir. |

### Valor devuelto

Un objeto [`FormatFamilyBase`](../../formatfamilybase) correspondiente al ID de familia de formato especificado.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando el ID de familia de formato especificado no es válido. |

### Ver también

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
