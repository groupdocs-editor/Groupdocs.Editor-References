---
title: "op_Explicit"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Convierte un octeto Byte de 8 bits específico al TextDecorationLineType correspondiente (groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) y lanza una excepción si la conversión es inválida"
type: docs
weight: 180
url: /es/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit/
---
## explicit operator {#op_explicit_1}

Convierte un Byte específico (octeto de 8 bits) al [`TextDecorationLineType`](../../textdecorationlinetype) correspondiente, lanza una excepción si la conversión es inválida

```csharp
public static explicit operator TextDecorationLineType(byte octet)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| octeto | Byte | Un octeto de 8 bits (campo de bits), donde los 5 bits iniciales son cero, mientras que los últimos 3 indican banderas |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | El *octeto* especificado tiene un valor inválido |

### Ver también

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

Convierte la instancia especificada de [`TextDecorationLineType`](../../textdecorationlinetype) al octeto equivalente (campo de bits de 8 bits)

```csharp
public static explicit operator byte(TextDecorationLineType input)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| input | TextDecorationLineType | Instancia de [`TextDecorationLineType`](../../textdecorationlinetype) a convertir |

### Ver también

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
