---
title: "FromMarkup"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen HTML işaretlemesinden EditableDocumentgroupdocs.editor/editabledocument örneği oluşturan statik fabrika."
type: docs
weight: 20
url: /tr/net/groupdocs.editor/editabledocument/frommarkup/
---
## FromMarkup(string) {#frommarkup}

Belirtilen HTML işaretlemesinden [`EditableDocument`](../../editabledocument) örneği oluşturan statik fabrika.

```csharp
public static EditableDocument FromMarkup(string newHtmlContent)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| newHtmlContent | String | İşlenmesi gereken ham HTML işaretlemesini içeren String. NULL, boş veya geçersiz olamaz. |

### Dönüş Değeri

Yeni null olmayan EditableDocument örneği

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | Girdi ham HTML işaretlemesi içeren dize null veya boş olamaz. |

### Açıklamalar

Bu statik yöntem, tüm kaynakların base64 kodlamasıyla tek dize HTML işaretlemesinden [`EditableDocument`](../../editabledocument) örneği oluşturmak için kullanışlıdır.

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## FromMarkup(string, IEnumerable&lt;IHtmlResource&gt;) {#frommarkup_1}

Belirtilen HTML işaretlemesi ve ilgili bağlı kaynakların bir setinden bir EditableDocument örneği oluşturan statik fabrika

```csharp
public static EditableDocument FromMarkup(string newHtmlContent, 
    IEnumerable<IHtmlResource> resources)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| newHtmlContent | String | İşlenmesi gereken ham HTML işaretlemesini içeren String. NULL, boş veya geçersiz olamaz. |
| resources | IEnumerable`1 | HTML belgesinde kullanılan, *newHtmlContent* parametresinde belirtilen tüm kaynakların (görseller, stil sayfaları, yazı tipleri) koleksiyonu. Boş (NULL veya boş koleksiyon) olabilir. |

### Dönüş Değeri

Yeni null olmayan EditableDocument örneği

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | Girdi ham HTML işaretlemesi içeren dize null veya boş olamaz. |

### Ayrıca Bakınız

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
