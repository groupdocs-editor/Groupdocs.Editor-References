---
title: "EnablePagination"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. Varsayılan olarak false devre dışıdır."
type: docs
weight: 30
url: /tr/net/groupdocs.editor.options/ebookeditoptions/enablepagination/
---
## EbookEditOptions.EnablePagination property

Ortaya çıkan HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. Varsayılan olarak devre dışıdır (`false`).

```csharp
public bool EnablePagination { get; set; }
```

### Açıklamalar

Özünde, çoğu e-kitap formatı dahili olarak Office Open XML gibi bir akış formatıdır; içerik tek bir bütün olarak bulunur ve bölümlere ayrılır, sayfalara değil. Ancak sayfa numaraları, dipnotlar, üstbilgi/altbilgi gibi sayfaya özgü bilgiler içerir. Bazı e-kitap okuyucular e-kitap içeriğini sayfalara bölme işlemi yaparken, diğerleri (özellikle mobil) — yapmaz. Bu seçenek, e-kitap içeriğinin düzenleme sırasında HTML/CSS içinde nasıl temsil edileceğini — akış (`false`) ya da sayfalı (`true`) görünümde — kontrol etmenizi sağlar.

### Ayrıca Bakınız

* class [EbookEditOptions](../../ebookeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
