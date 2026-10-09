---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "PowerPoint uyumlu Sunum belgelerini oluşturmak ve kaydetmek için özel seçenekler belirtmeye izin verir."
type: docs
weight: 1100
url: /tr/net/groupdocs.editor.options/presentationsaveoptions/
---
## PresentationSaveOptions class

Sunum (PowerPoint uyumlu) belgelerini oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir.

```csharp
public sealed class PresentationSaveOptions : ISaveOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions#constructor)() | Parametresiz bu yapıcı, PPTX çıktı formatı ile yeni bir PresentationSaveOptions örneği oluşturur (daha sonra [`OutputFormat`](./outputformat) özelliği ile değiştirilebilir). |
| [PresentationSaveOptions](presentationsaveoptions#constructor_1)(PresentationFormats) | Belirtilen zorunlu Sunum çıktı formatı ile yeni bir PresentationSaveOptions örneği oluşturur, diğer tüm parametreler varsayılandır. |

## Properties

| Name | Açıklama |
| --- | --- |
| [InsertAsNewSlide](../../groupdocs.editor.options/presentationsaveoptions/insertasnewslide) { get; set; } | Düzenlenen slaytın, [`SlideNumber`](./slidenumber) özelliği ile belirtilen konumda orijinal sunumdaki mevcut slaytı değiştirip değiştirmeyeceğini belirten Boolean bayrak; ya mevcut slaytı değiştirir ya da içeriğini değiştirmeden mevcut slayt ile öncekisi arasına eklenir. Varsayılan değer `false` — mevcut slayt değiştirilecektir. [`SlideNumber`](./slidenumber) özelliğinin değeri `'0'` olarak ayarlanırsa bu özellik yok sayılır. |
| [OutputFormat](../../groupdocs.editor.options/presentationsaveoptions/outputformat) { get; set; } | Belgeyi kaydetmek için kullanılacak bir Sunum formatı belirtmeye izin verir. |
| [Password](../../groupdocs.editor.options/presentationsaveoptions/password) { get; set; } | Sonuç Sunum belgesini kodlamak için kullanılacak şifreyi belirtmeye, değiştirmeye ve almaya izin verir. Varsayılan olarak NULL - şifre ayarlanmaz. Daha önce ayarlanmışsa şifreyi kaldırmak için NULL veya boş dizeye ayarlayın. |
| [SlideNumber](../../groupdocs.editor.options/presentationsaveoptions/slidenumber) { get; set; } | Yeni tek slaytlı bir sunum oluşturmak yerine (varsayılan davranış) düzenlenen slaytı mevcut sunuma eklemeye izin verir. Slayt numarası, Editor sınıfında yüklü sunumdaki slaytların 1 tabanlı numarasıdır. 0 ise (varsayılan değer), yeni sunum tek düzenlenmiş slayt ile oluşturulur. Sıfırdan büyük veya küçük ise ve Editor sınıfında geçerli bir sunum yüklüyse, giriş EditableDocument örneğinde depolanan düzenlenmiş slayt bu sunuma eklenecektir. |
| [SlideNumbersToDelete](../../groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete) { get; set; } | Düzenlenen slayt mevcut sunuma eklendiğinde, kaydetme sırasında sunumdan silinmesi gereken 1 tabanlı slayt numaralarını içeren bir dizi belirtmeye izin verir. |

### Açıklamalar

Bu sınıfın örneği, düzenlenen sunumu belirli bir Sunum formatındaki nihai belgeye kaydetmek için  yöntemine geçirilmelidir. Diğer tüm parametreler isteğe bağlıdır ve atlanabilir; varsayılan olarak kaydedilen sunumun formatı PPTX'tir, ancak yapıcı veya özellik aracılığıyla değiştirilebilir.

### Ayrıca Bakınız

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
