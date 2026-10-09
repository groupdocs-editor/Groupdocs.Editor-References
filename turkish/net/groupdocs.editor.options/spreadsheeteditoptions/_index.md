---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Tüm desteklenen Elektronik Tablo Excel uyumlu formatlarda belgeleri düzenlemek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 1110
url: /tr/net/groupdocs.editor.options/spreadsheeteditoptions/
---
## SpreadsheetEditOptions class

Tüm desteklenen Elektronik Tablo (Excel uyumlu) formatlarındaki belgeleri düzenlemek için özel seçenekleri belirtmeye izin verir.

```csharp
public class SpreadsheetEditOptions : IEditOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [SpreadsheetEditOptions](spreadsheeteditoptions)() | Varsayılan yapıcı. |

## Properties

| Name | Açıklama |
| --- | --- |
| [ExcludeHiddenWorksheets](../../groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets) { get; set; } | Girdi Elektronik Tablo belgesindeki gizli çalışma sayfalarını dışlamaya izin verir, böylece tamamen göz ardı edilirler. Varsayılan olarak yanlıştır - gizli çalışma sayfaları mevcuttur ve normal şekilde işlenir. |
| [ExportBogusRowData](../../groupdocs.editor.options/spreadsheeteditoptions/exportbogusrowdata) { get; set; } | Etkinleştirildiğinde, üretilen HTML belgesindeki HTML tablosu, yalnızca genişliğin belirtildiği boş hücrelere sahip, sıfır yüksekliğinde ve gizli bir alt satır içerir. Bu boş hücreli satır, her sütun için kesin genişlik değerlerini içerir ve HTML'den Elektronik Tabloya geri dönüşümü iyileştirir. Varsayılan olarak etkindir (`true`). |
| [MergeEmptyAdjacentCells](../../groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells) { get; set; } | Etkinleştirildiğinde, girdi Elektronik Tablo belgesindeki boş yan yana yatay hücreler, düzenlenebilir HTML belgesinde ilgili `colspan` özniteliğiyle tek bir hücreye birleştirilmiş olarak gösterilir. Varsayılan olarak devre dışıdır (`false`). |
| [WorksheetIndex](../../groupdocs.editor.options/spreadsheeteditoptions/worksheetindex) { get; set; } | Giriş Spreadsheet belgesinin HTML'ye dönüştürülmesi gereken çalışma sayfasının (sekme) 0 tabanlı indeksini belirtmeye izin verir (notlara bakınız). |

### Ayrıca Bakınız

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
