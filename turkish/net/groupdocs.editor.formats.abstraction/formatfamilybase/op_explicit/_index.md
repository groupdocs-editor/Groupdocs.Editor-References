---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bir dizeyi format ailesi adı olarak bir FormatFamilyBasegroupdocs.editor.formats.abstraction/formatfamilybase nesnesine dönüştürür."
type: docs
weight: 100
url: /tr/net/groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit/
---
## explicit operator {#op_explicit_1}

Bir dizeyi format ailesi adı olarak bir [`FormatFamilyBase`](../../formatfamilybase) nesnesine dönüştürür.

```csharp
public static explicit operator FormatFamilyBase(string family)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| family | String | Dönüştürülecek format ailesinin adı. |

### Dönüş Değeri

Belirtilen format ailesi adına karşılık gelen bir [`FormatFamilyBase`](../../formatfamilybase) nesnesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | Belirtilen format ailesi adı geçersiz olduğunda atılır. |

### Ayrıca Bakınız

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

Bir tamsayıyı format ailesi kimliği olarak bir [`FormatFamilyBase`](../../formatfamilybase) nesnesine dönüştürür.

```csharp
public static explicit operator FormatFamilyBase(int id)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| id | Int32 | Dönüştürülecek format ailesi kimliği. |

### Dönüş Değeri

Belirtilen format ailesi kimliğine karşılık gelen bir [`FormatFamilyBase`](../../formatfamilybase) nesnesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | Belirtilen format ailesi kimliği geçersiz olduğunda atılır. |

### Ayrıca Bakınız

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
