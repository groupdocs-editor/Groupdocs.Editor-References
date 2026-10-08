---
title: "FromNumber"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Crea un fontweight a partir del número especificado"
type: docs
weight: 50
url: /es/net/groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber/
---
## FontWeight.FromNumber method

Crea un font-weight a partir de un número especificado

```csharp
public static FontWeight FromNumber(ushort number)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| número | UInt16 | Entero sin signo, debe estar dentro del rango [1..1000] |

### Valor devuelto

Nueva instancia de FontWeight o excepción

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | El número especificado está fuera del rango [1..1000] |

### Ver también

* struct [FontWeight](../../fontweight)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
