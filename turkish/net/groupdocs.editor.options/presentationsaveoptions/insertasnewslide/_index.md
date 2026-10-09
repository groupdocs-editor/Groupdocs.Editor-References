---
title: "InsertAsNewSlide"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Düzenlenmiş slaytın, orijinal sunumda SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber özelliğiyle belirtilen konumda mevcut slaytı değiştirip değiştirmeyeceğini belirten Boolean bayrak veya içeriğini değiştirmeden mevcut slayt ile bir önceki slayt arasına enjekte edilip edilmeyeceğini belirler. Varsayılan olarak false'tur, mevcut slayt değiştirilecektir. Bu özellik, SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber özelliğinin değeri 0 olarak ayarlandığında yok sayılır."
type: docs
weight: 20
url: /tr/net/groupdocs.editor.options/presentationsaveoptions/insertasnewslide/
---
## PresentationSaveOptions.InsertAsNewSlide property

Düzenlenmiş slaydın, orijinal sunumda [`SlideNumber`](../slidenumber) özelliğiyle belirtilen konumda mevcut slaytı değiştirip değiştirmeyeceğini veya mevcut slayt ile bir önceki slayt arasına, içeriğini değiştirmeden enjekte edilip edilmeyeceğini belirten Boolean bayrak. Varsayılan değer `false` — mevcut slayt değiştirilecektir. Bu özellik, [`SlideNumber`](../slidenumber) özelliğinin değeri `'0'` olarak ayarlandığında yok sayılır.

```csharp
public bool InsertAsNewSlide { get; set; }
```

### Açıklamalar

Varsayılan olarak slayt değiştirilir. Bu, verilen sunumda 5 slayt varsa ve [`SlideNumber`](../slidenumber)=4 ise, 4. slayt yeni düzenlenmiş slaytla değiştirilecek, sunumdaki toplam slayt sayısı (5) ise aynı kalacaktır. Ancak, bu özelliğin değeri true olarak ayarlandığında, yeni düzenlenmiş slayt 4. slayt olarak enjekte edilecek ve sonraki tüm slaytlar sona doğru kaydırılacaktır: \"eski\" 4. slayt 5. slayt olur, 5. slayt 6. slayt olur ve sunumdaki toplam slayt sayısı bir artarak 6 olacaktır.

### Ayrıca Bakınız

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
