---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirli Byte 8 bit okteti ilgili TextDecorationLineTypegroupdocs.editor.htmlcss.css.properties/textdecorationlinetype tipine dönüştürür, dönüşüm geçersizse istisna fırlatır"
type: docs
weight: 180
url: /tr/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit/
---
## explicit operator {#op_explicit_1}

Belirli Byte (8-bit oktet) ilgili [`TextDecorationLineType`](../../textdecorationlinetype) tipine dönüştürür, dönüşüm geçersizse istisna fırlatır

```csharp
public static explicit operator TextDecorationLineType(byte octet)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| oktet | Byte | 5 öncü biti sıfır, son 3 biti bayrakları gösteren 8-bitlik bir oktet (bit alanı) |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | Belirtilen *oktet* geçersiz bir değere sahip |

### Ayrıca Bakınız

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

Belirtilen [`TextDecorationLineType`](../../textdecorationlinetype) örneğini eşdeğer oktete (8-bit bit alanı) dönüştürür

```csharp
public static explicit operator byte(TextDecorationLineType input)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| input | TextDecorationLineType | [`TextDecorationLineType`](../../textdecorationlinetype) örneği dönüştürülmek için |

### Ayrıca Bakınız

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
