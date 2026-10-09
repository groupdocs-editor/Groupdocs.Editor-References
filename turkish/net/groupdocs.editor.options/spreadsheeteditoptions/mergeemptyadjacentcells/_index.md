---
title: "MergeEmptyAdjacentCells"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Etkinleştirildiğinde, giriş Spreadsheet belgesindeki boş bitişik yatay hücreler, düzenlenebilir HTML belgesinde ilgili colspan özniteliğiyle tek bir hücreye birleştirilmiş olarak gösterilir. Varsayılan olarak devre dışıdır (false)."
type: docs
weight: 40
url: /tr/net/groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells/
---
## SpreadsheetEditOptions.MergeEmptyAdjacentCells property

Etkinleştirildiğinde, girdi Elektronik Tablo belgesindeki boş yan yana yatay hücreler, düzenlenebilir HTML belgesinde ilgili `colspan` özniteliğiyle tek bir hücreye birleştirilmiş olarak gösterilir. Varsayılan olarak devre dışıdır (`false`).

```csharp
public bool MergeEmptyAdjacentCells { get; set; }
```

### Açıklamalar

Varsayılan olarak GroupDocs.Editor, giriş Spreadsheet belgesindeki bir tabloyu her hücreyi koruyarak çıktı HTML belgesine dönüştürür. Ancak Spreadsheet belgeleri seyrek olabilir — çok sayıda "boş alan" içerebilir, yani birçok hücre boş olur. Bu seçenek etkinleştirildiğinde, bu boş hücreleri `TD` öğesindeki `colspan` özniteliğiyle tek bir hücreye birleştirir ve böylece üretilen HTML işaretlemesinin boyutunu önemli ölçüde azaltabilir.

### Ayrıca Bakınız

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
