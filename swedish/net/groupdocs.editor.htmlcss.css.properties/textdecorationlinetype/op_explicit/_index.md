---
title: "op_Explicit"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Kastar specifik Byte 8bit oktett till motsvarande TextDecorationLineTypegroupdocs.editor.htmlcss.css.properties/textdecorationlinetype, kastar undantag om konverteringen är ogiltig"
type: docs
weight: 180
url: /sv/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit/
---
## explicit operator {#op_explicit_1}

Kastar specifik Byte (8-bit oktett) till motsvarande [`TextDecorationLineType`](../../textdecorationlinetype), kastar undantag om konverteringen är ogiltig

```csharp
public static explicit operator TextDecorationLineType(byte octet)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| oktet | Byte | En 8-bit oktett (bitfält), där de 5 första bitarna är noll, medan de sista 3 indikerar flaggor |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Angiven *oktet* har ogiltigt värde |

### Se även

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

Kastar angivet [`TextDecorationLineType`](../../textdecorationlinetype)-instans till motsvarande oktett (8-bit bitfält)

```csharp
public static explicit operator byte(TextDecorationLineType input)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| input | TextDecorationLineType | `[`TextDecorationLineType`](../../textdecorationlinetype)`-instans att kasta |

### Se även

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
