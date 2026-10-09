---
title: "InsertAsNewWorksheet"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Boolean bayrağı, düzenlenmiş çalışma sayfasının orijinal elektronik tabloda, WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber özelliği tarafından belirtilen konumda mevcut çalışma sayfasını değiştirip değiştirmeyeceğini veya mevcut çalışma sayfası ile bir önceki arasına, içeriğini değiştirmeden enjekte edilip edilmeyeceğini belirtir. Varsayılan olarak false'tur  mevcut çalışma sayfası değiştirilecektir."
type: docs
weight: 20
url: /tr/net/groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet/
---
## SpreadsheetSaveOptions.InsertAsNewWorksheet property

Boolean bayrağı, düzenlenmiş çalışma sayfasının orijinal elektronik tabloda, [`WorksheetNumber`](../worksheetnumber) özelliği tarafından belirtilen konumda mevcut çalışma sayfasını değiştirip değiştirmeyeceğini veya mevcut çalışma sayfası ile bir önceki arasına, içeriğini değiştirmeden enjekte edilip edilmeyeceğini belirtir. Varsayılan olarak false — mevcut çalışma sayfası değiştirilecektir. Bu özellik, [`WorksheetNumber`](../worksheetnumber) özelliğinin değeri '0' olarak ayarlandığında yok sayılır.

```csharp
public bool InsertAsNewWorksheet { get; set; }
```

### Açıklamalar

Varsayılan olarak çalışma sayfası değiştirilir. Bu, verilen elektronik tablonun 5 çalışma sayfası olduğu ve [`WorksheetNumber`](../worksheetnumber)=4 olduğu durumda, 4. çalışma sayfasının yeni düzenlenmiş çalışma sayfası ile değiştirileceği, ancak elektronik tablodaki toplam çalışma sayfası sayısının (5) dokunulmaz kalacağı anlamına gelir. Ancak, bu özelliğin değeri true olarak ayarlandığında, yeni düzenlenmiş çalışma sayfası 4. çalışma sayfası olarak enjekte edilir ve sonraki tüm çalışma sayfaları sona doğru kaydırılır: "eski" 4. çalışma sayfası 5. olur, 5. çalışma sayfası 6. olur ve elektronik tablodaki toplam çalışma sayfası sayısı bir artarak 6 olur.

### Ayrıca Bakınız

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
