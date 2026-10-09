---
title: "FromMarkupAndResourceFolder"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen HTML işaretlemesinden ve tam yol ile belirtilen klasördeki kaynaklardan bir EditableDocument örneği oluşturan statik fabrika"
type: docs
weight: 30
url: /tr/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

Belirtilen HTML işaretlemesinden ve tam yol ile belirtilen klasörde bulunan kaynaklardan bir EditableDocument örneği oluşturan statik fabrika

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| newHtmlContent | String | İşlenmesi gereken ham HTML işaretlemesini içeren String. NULL, boş veya geçersiz olamaz. |
| resourceFolderPath | String | Kaynakların bulunduğu klasöre zorunlu yol. Bu klasörde bulunan tüm stil sayfaları kullanılacaktır. NULL veya boş dize olamaz ve bu klasör mevcut olmalıdır. |

### Dönüş Değeri

Yeni null olmayan EditableDocument örneği

### Açıklamalar

Bu statik fabrika, HTML belgesinin içeriği bir dize olarak sunulduğunda, ancak tüm kaynakların bir klasörde bulunduğu ve genellikle HTML işaretlemesindeki bu kaynaklara olan bağlantıların geçersiz ve eksik olduğu durumlarda faydalıdır. Bu yöntem çağrıldığında belirtilen klasörü tarar ve bulunan tüm stil sayfalarını belgeye otomatik olarak uygular. Bu yöntem, genellikle belge meta verilerini ve benzerlerini kesen farklı HTML editörlerinden içerik alırken çok yararlıdır.

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
