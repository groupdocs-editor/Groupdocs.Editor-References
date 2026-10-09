---
title: "WorksheetNumbersToDelete"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Düzenlenen çalışma sayfası mevcut bir çalışma sayfasına eklendiğinde, kaydedilirken silinmesi gereken çalışma sayfalarının 1 tabanlı numaralarını içeren bir dizi belirtmeye izin verir."
type: docs
weight: 60
url: /tr/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete/
---
## SpreadsheetSaveOptions.WorksheetNumbersToDelete property

Düzenlenmiş çalışma sayfası mevcut elektronik tabloya eklendiğinde, kaydetme sırasında elektronik tablodan silinmesi gereken 1 tabanlı çalışma sayfası numaralarını içeren bir dizi belirtmeye izin verir.

```csharp
public int[] WorksheetNumbersToDelete { get; set; }
```

### Açıklamalar

Düzenlenen çalışma sayfası yeni tek‑çalışma‑sayfası elektronik tablo olarak (varsayılan davranış) kaydedilmek yerine mevcut bir elektronik tabloya ([`WorksheetNumber`](../worksheetnumber) özelliği kullanılarak) kaydedildiğinde, bu elektronik tablodan belirli çalışma sayfalarını bu dizideki numaraları belirterek silmek de mümkündür.

Varsayılan olarak bu dizi `null`'dır — hiçbir çalışma sayfası silinmez. Ancak dizi null değil ve boş değilse ve en az bir geçerli çalışma sayfası numarası içeriyorsa, düzenlenen çalışma sayfasının içeriğiyle çıktı elektronik tablo belgesi oluşturulduktan sonra, belirtilen numaralı çalışma sayfaları, içeriği çıktı akışına veya dosyasına yazılmadan hemen önce elektronik tablodan silinir.

Bu dizideki çalışma sayfası numaraları 1 tabanlıdır, 0 tabanlı değildir; geçersiz numaralar (1'den küçük veya toplam çalışma sayfası sayısından büyük) yok sayılır.

### Ayrıca Bakınız

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
