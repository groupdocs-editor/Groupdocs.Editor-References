---
title: "ExportCidUrls"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "MHTML belgelerinde yer alan kaynak (resim, yazı tipi, CSS) referansları için CID ContentID URL'lerinin kullanılıp kullanılmayacağını belirtir. Varsayılan değer false'tur."
type: docs
weight: 20
url: /tr/net/groupdocs.editor.options/mhtmlsaveoptions/exportcidurls/
---
## MhtmlSaveOptions.ExportCidUrls property

MHTML belgelerinde bulunan kaynakları (görseller, yazı tipleri, CSS) referanslamak için CID (Content-ID) URL'lerinin kullanılıp kullanılmayacağını belirtir. Varsayılan değer `false`.

```csharp
public bool ExportCidUrls { get; set; }
```

### Açıklamalar

Varsayılan olarak, MHTML belgelerindeki kaynaklar dosya adıyla (örneğin, "image.png") referans verilir ve bu adlar MIME parçalarının "Content-Location" başlıklarıyla eşleşir. Bu seçenek, kaynak dosyalarına yapılan referansların CID (Content-ID) URL'leri (örneğin, "cid:image.png") olarak yazıldığı ve "Content-ID" başlıklarıyla eşleştiği alternatif bir yöntemi etkinleştirir.

Teorik olarak, iki referans yönteminde bir fark olmamalı ve her ikisi de herhangi bir tarayıcı ya da e-posta istemcisinde sorunsuz çalışmalıdır. Ancak pratikte, bazı istemciler dosya adıyla kaynakları getirmekte başarısız olur. Tarayıcınız ya da e-posta istemciniz bir MTHML belgesine dahil edilen kaynakları (görselleri göstermez veya CSS stillerini yüklemez) yüklemeyi reddederse, belgeyi CID URL'leriyle dışa aktarmayı deneyin.

### Ayrıca Bakınız

* class [MhtmlSaveOptions](../../mhtmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
