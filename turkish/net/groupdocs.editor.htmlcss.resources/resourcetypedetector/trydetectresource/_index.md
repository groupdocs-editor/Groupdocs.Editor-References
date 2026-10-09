---
title: "TryDetectResource"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bir giriş akışını analiz etmeye çalışır ve null değilse belirtilen varsayımsal türü dikkate alarak desteklenen HTML kaynaklarından birini oluşturur"
type: docs
weight: 20
url: /tr/net/groupdocs.editor.htmlcss.resources/resourcetypedetector/trydetectresource/
---
## ResourceTypeDetector.TryDetectResource method

Bir giriş akışını analiz etmeye çalışır ve belirtilen varsayımsal tür null değilse, bunu dikkate alarak desteklenen HTML kaynaklarından birini oluşturur

```csharp
public static IHtmlResource TryDetectResource(Stream inputResourceStream, string name, 
    IResourceType assumptiveFormat)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| inputResourceStream | Stream | HTML kaynağı içerdiği varsayılan giriş akışı. Geçersizse bir istisna fırlatılacaktır. |
| ad | String | Başarıyla oluşturulan ve döndürülen kaynak için kullanılacak kaynak adı. NULL, boş veya sadece boşluk olamaz |
| assumptiveFormat | IResourceType | En iyi performansı elde etmek için yararlı olan giriş HTML kaynağının varsayılan formatı. Tamamen bilinmiyorsa NULL değeri kullanın. Yanlış olabilir, bu sadece performansı düşürür. |

### Dönüş Değeri

Başarılı olduğunda 'IHtmlResource' arayüzünü uygulayan ve desteklenen HTML kaynaklarından birini temsil eden, başarısız olduğunda ise NULL olan örnek

### Ayrıca Bakınız

* interface [IHtmlResource](../../ihtmlresource)
* interface [IResourceType](../../iresourcetype)
* class [ResourceTypeDetector](../../resourcetypedetector)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
