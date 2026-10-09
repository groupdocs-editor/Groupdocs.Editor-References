---
title: "SaveOneResource"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Sağlanan HTML kaynağını elde etmek ve kaydetmek ve ardından bu kaynağa bir bağlantıyı çağırana geri döndürmek için Savegroupdocs.editor/editabledocument/save yöntemi çağrısı sırasında tetiklenen örnek yöntem; son kullanıcı tarafından uygulanmalıdır."
type: docs
weight: 10
url: /tr/net/groupdocs.editor.options/ihtmlsavingcallback/saveoneresource/
---
## IHtmlSavingCallback.SaveOneResource method

Sağlanan HTML kaynağını elde etmek ve kaydetmek ve ardından bu kaynağa bir bağlantıyı çağırana geri döndürmek için [`Save`](../../../groupdocs.editor/editabledocument/save) yöntemi çağrısı sırasında tetiklenen örnek yöntem; son kullanıcı tarafından uygulanmalıdır.

```csharp
public string SaveOneResource(IHtmlResource resource)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| kaynak | IHtmlResource | Her türlü HTML kaynağı (görseller ve yazı tipleri, gömülü değilse stil sayfaları da dahil), GroupDocs.Editor tarafından bu arayüzün kullanıcı tanımlı uygulamasına geçirilen, kullanıcı tarafından elde edilen ve kaydetme, gönderme, dönüştürme gibi gerekli işlemlerin yapılabildiği bir kaynaktır. GroupDocs.Editor bu yönteme asla `null` bir HTML kaynağı göndermez. |

### Dönüş Değeri

*resource* parametresinde elde edilen kaynak için bir bağlantı (referans), kullanıcının GroupDocs.Editor'e sağlaması gerekir; böylece GroupDocs.Editor bu bağlantıyı HTML işaretlemesine ekler.

### Açıklamalar

GroupDocs.Editor, bu yöntemin kullanıcı tanımlı uygulamasının yürütme sırasında istisna fırlatmadığını varsayar. Ancak bir istisna oluşursa, GroupDocs.Editor, HTML işaretlemesine [`FilenameWithExtension`](../../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) özelliğinin değerini yazar.

### Ayrıca Bakınız

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
