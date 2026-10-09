---
title: "LocaleId"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Form alanının temsil ettiği kültür veya bölgesel ayarlarla ilişkili locale ID'sini alır veya ayarlar."
type: docs
weight: 30
url: /tr/net/groupdocs.editor.words.fieldmanagement/numberformfield/localeid/
---
## NumberFormField.LocaleId property

Form alanının kültür veya bölgesel ayarlarını temsil eden yerel kimliğini (locale ID) alır veya ayarlar.

```csharp
public int LocaleId { get; set; }
```

### Açıklamalar

LocaleId özelliği, belirli bir kültür veya bölgeye karşılık gelen bir yerel tanımlayıcıyı (LCID) belirtir.

### Örnekler

Aşağıdaki örnek, LocaleId özelliğinin nasıl ayarlanacağını gösterir:

```csharp
Set the LocaleId to represent the English (United States) culture
numberField.LocaleId = new CultureInfo("en-US").LCID;
```

### Ayrıca Bakınız

* class [NumberFormField](../../numberformfield)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
