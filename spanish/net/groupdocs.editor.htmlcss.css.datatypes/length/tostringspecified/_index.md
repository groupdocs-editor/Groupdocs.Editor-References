---
title: "ToStringSpecified"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Devuelve una representación en cadena de esta longitud en el tipo de unidad especificado. El valor numérico se convertirá de acuerdo con el cambio de tipo de unidad."
type: docs
weight: 260
url: /es/net/groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified/
---
## Length.ToStringSpecified method

Devuelve una representación en cadena de esta longitud en el tipo de unidad especificado. El valor numérico se convertirá de acuerdo con el cambio de tipo de unidad.

```csharp
public string ToStringSpecified(Unit unit)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| unidad | Unidad | Unidad especificada, a la que esta instancia debe convertirse antes de serializarla a la cadena. Debe ser válida. No puede ser sin unidad. |

### Valor devuelto

Representación de cadena

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidEnumArgumentException | El valor no está definido |
| ArgumentOutOfRangeException | Se prohíbe un valor sin unidad |

### Ver también

* enum [Unit](../../length.unit)
* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
