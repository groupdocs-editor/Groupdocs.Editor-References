---
title: "GetContent"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen metin kodlamasıyla bu içeriği belirtilen akıma yazarak HTML belgesinin tüm içeriğini bir bayt akışı olarak döndürür"
type: docs
weight: 130
url: /tr/net/groupdocs.editor/editabledocument/getcontent/
---
## GetContent&lt;TStream&gt;(TStream, Encoding) {#getcontent_2}

Belirtilen metin kodlamasıyla bu içeriği belirtilen akıma yazarak HTML belgesinin tüm içeriğini bir bayt akışı olarak döndürür

```csharp
public TStream GetContent<TStream>(TStream storage, Encoding encoding)
    where TStream : Stream
```

| Parameter | Açıklama |
| --- | --- |
| TStream | Stream'in herhangi bir uygulaması |
| storage | Yazmayı destekleyen null olmayan bayt akışı |
| encoding | Belirtilen *storage* içine metin içeriği yazılırken uygulanması gereken null olmayan metin kodlaması |

### Dönüş Değeri

Belirtilen *storage* örneği

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | Girdi argümanlarından herhangi biri null |
| ArgumentException | Belirtilen akış yazılamaz |

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent() {#getcontent}

HTML belgesinin tüm içeriğini bir dize olarak döndürür.

```csharp
public string GetContent()
```

### Dönüş Değeri

HTML belgesinin içeriğini içeren String

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent(string, string) {#getcontent_1}

HTML belgesinin tüm içeriğini bir dize olarak döndürür; dış kaynaklara bağlantılar belirtilen yer tutucularla şablonu içerir.

```csharp
public string GetContent(string externalImagesTemplate, string externalCssTemplate)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| externalImagesTemplate | String | Bu parametre aracılığıyla, sonuç HTML dizesinde bulunacak IMG öğelerindeki tüm harici görüntülere uygulanacak bir yer tutucu içeren bir dize şablonu belirtebilirsiniz. NULL veya boş ise şablon eklenmez ve saf dosya adları sonuç HTML işaretlemesinde yer alır. Şablon geçersiz ise, bir önek olarak kabul edilir, böylece dosya adları onun sonuna eklenir. |
| externalCssTemplate | String | Bu parametre aracılığıyla, tek bir yer tutucu içeren bir dize şablonu belirtebilirsiniz; bu şablon, sonuç HTML dizesinde bulunacak LINK öğelerindeki tüm harici stil sayfalarına olan bağlantılara eklenecektir. NULL veya boş ise, şablon eklenmez ve saf dosya adları sonuç HTML işaretlemesinde bulunur. Şablon geçersiz ise, bir önek olarak kabul edilir, böylece dosya adları sonuna eklenir. |

### Dönüş Değeri

Bağlantılarla birlikte HTML belgesinin içeriğini içeren ve harici kaynaklara göre ayarlanmış String

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
