---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Este constructor sin parámetros crea una nueva instancia de DelimitedTextSaveOptions con un punto y coma como separador predeterminado; luego puede modificarse a través de la propiedad Separatorgroupdocs.editor.options/delimitedtextsaveoptions/separator."
type: docs
weight: 10
url: /es/net/groupdocs.editor.options/delimitedtextsaveoptions/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions() {#constructor}

Este constructor sin parámetros crea una nueva instancia de DelimitedTextSaveOptions con un punto y coma (;) como separador predeterminado (puede modificarse luego a través de la propiedad [`Separator`](../separator)).

```csharp
public DelimitedTextSaveOptions()
```

### Ver también

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

---

## DelimitedTextSaveOptions(string) {#constructor_1}

Crea una instancia de la clase de opciones para texto delimitado con un separador (delimitador) obligatorio

```csharp
public DelimitedTextSaveOptions(string separator)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| separator | String | Separador de cadena (delimitador), que no puede ser NULL ni vacío. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando el separador especificado es nulo o una cadena vacía. |

### Ver también

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
