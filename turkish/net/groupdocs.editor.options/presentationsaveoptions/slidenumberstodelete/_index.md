---
title: "SlideNumbersToDelete"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Düzenlenmiş slayt mevcut bir sunuma eklendiğinde, kaydetme sırasında sunumdan silinmesi gereken slaytların 1 tabanlı numaralarını içeren bir dizi belirtmeye olanak tanır."
type: docs
weight: 60
url: /tr/net/groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete/
---
## PresentationSaveOptions.SlideNumbersToDelete property

Düzenlenen slayt mevcut sunuma eklendiğinde, kaydetme sırasında sunumdan silinmesi gereken 1 tabanlı slayt numaralarını içeren bir dizi belirtmeye izin verir.

```csharp
public int[] SlideNumbersToDelete { get; set; }
```

### Açıklamalar

Düzenlenmiş slayt yeni bir tek slaytlık sunum olarak (varsayılan davranış) kaydedilmek yerine mevcut bir sunuma ([`SlideNumber`](../slidenumber) özelliği kullanılarak) kaydedildiğinde, bu dizi içinde numaralarını belirterek bu sunumdan belirli slaytları silmek de mümkündür.

Varsayılan olarak bu dizi `null`dır — hiçbir slayt silinmez. Ancak, dizi null değil ve boş değilse ve en az bir geçerli slayt numarası içeriyorsa, düzenlenmiş slayt içeriğiyle çıktı Presentation belgesi oluşturulduktan sonra, belirtilen numaralı slaytlar, içeriği çıktı akışına veya dosyasına yazılmadan hemen önce sunumdan silinecektir.

Bu dizideki slayt numaraları 1 tabanlıdır, 0 tabanlı değildir; geçersiz numaralar (1'den küçük veya toplam slayt sayısından büyük) yok sayılacaktır.

### Ayrıca Bakınız

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
