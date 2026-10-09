---
title: "FromFile"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "HTML dosyasının kendisine ve bağlı kaynakların bulunduğu klasöre bir yol belirten bir .html dosyasından EditableDocument örneği oluşturan statik fabrika"
type: docs
weight: 10
url: /tr/net/groupdocs.editor/editabledocument/fromfile/
---
## EditableDocument.FromFile method

Bir HTML dosyasından, *.html dosyasının kendisine ve bağlı kaynakların bulunduğu klasöre verilen yol ile bir EditableDocument örneği oluşturan statik fabrika

```csharp
public static EditableDocument FromFile(string htmlFilePath, string resourceFolderPath)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| htmlFilePath | String | HTML dosyasına tam bir yol içeren String. Null olamaz, geçerli bir dosya yolu olmalı ve dosya kendisi mevcut olmalıdır. |
| resourceFolderPath | String | HTML kaynaklarının bulunduğu klasöre isteğe bağlı yol. NULL, geçersiz veya klasör mevcut değilse, Editor bu klasörü kendisi bulmaya çalışacak, HTML işaretlemesini analiz ederek |

### Dönüş Değeri

Yeni null olmayan EditableDocument örneği

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | HTML dosya yolu ve/veya kaynak klasör yolu geçersiz |
| FileNotFoundException | Belirtilen HTML dosyası bulunamıyor |

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
