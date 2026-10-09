---
title: "Save"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bu HTML belgesini, HTML işaretlemesinin saklanacağı belirtilen yoldaki dosyaya ve kaynakların bulunduğu ek klasöre kaydeder."
type: docs
weight: 160
url: /tr/net/groupdocs.editor/editabledocument/save/
---
## Save(string) {#save_1}

HTML işaretlemesinin saklanacağı belirtilen yoldaki dosyaya ve ilgili kaynak klasörüne bu HTML belgesini kaydeder.

```csharp
public void Save(string htmlFilePath)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| htmlFilePath | String | HTML işaretlemesinin saklanacağı dosyanın tam yolu. Dosya mevcutsa oluşturulacak veya üzerine yazılacaktır. Ek kaynak klasörü, HTML dosyasının bulunduğu aynı klasörde oluşturulacaktır. |

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(string, string) {#save_2}

HTML işaretlemesinin saklanacağı belirtilen yoldaki dosyaya ve belirtilen yolda bulunan ilgili kaynak klasörüne bu HTML belgesini kaydeder.

```csharp
public void Save(string htmlFilePath, string resourcesFolderPath)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| htmlFilePath | String | HTML işaretlemesinin saklanacağı dosyanın tam yolu. NULL veya boş olamaz. Dosya mevcutsa oluşturulacak veya üzerine yazılacaktır. |
| resourcesFolderPath | String | Tüm ilgili kaynakların saklanacağı ek klasörün tam yolu. NULL veya boş ise, klasör *.html dosyasının bulunduğu aynı dizinde otomatik olarak oluşturulacaktır. Belirtilmiş ve mevcut değilse, oluşturulacaktır. |

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(TextWriter, HtmlSaveOptions) {#save}

Bu [`EditableDocument`](../../editabledocument) içeriğini HTML belgesi olarak belirtilen metin yazıcısına kaydeder, ikinci seçenek parametresi ise kaydetme prosedürünü özelleştirmeye ve kaynak kaydetme geri çağrısını belirtmeye olanak tanır.

```csharp
public void Save(TextWriter htmlMarkup, HtmlSaveOptions saveOptions)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| htmlMarkup | TextWriter | HTML işaretlemesinin yazılacağı metin yazıcısının uygulaması. Null olamaz. |
| saveOptions | HtmlSaveOptions | HTML kaydetme seçenekleri, kaydetme prosedürünü kontrol eder: HTML işaretlemesinin nasıl saklandığı (etiket adları, tırnak türleri) ve CSS ile resim veya font gibi diğer kaynakların nasıl ve nerede kaydedileceği. Kullanıcı, kaynakların nasıl kaydedileceğini ve HTML işaretlemesinden nasıl referans verileceğini kontrol etmek için [`SavingCallback`](../../../groupdocs.editor.options/htmlsaveoptions/savingcallback) özelliğinde arayüzün türetilmiş sınıfını belirtmelidir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | Belirtilen argümanlardan herhangi biri veya *saveOptions* içindeki `SavingCallback` özelliği `null` değerindedir. |

### Ayrıca Bakınız

* class [HtmlSaveOptions](../../../groupdocs.editor.options/htmlsaveoptions)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
