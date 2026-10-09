---
title: "Save"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen düzenlenmiş belgeyi EditableDocumentgroupdocs.editor/editabledocument örneği olarak temsil edilen belgeyi, belirtilen biçimdeki sonuç belgeye dönüştürür ve içeriğini belirtilen akışa kaydeder."
type: docs
weight: 80
url: /tr/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

Belirtilen düzenlenmiş belgeyi, '[`EditableDocument`](../../editabledocument)' örneği olarak temsil edilen belgeyi, belirtilen biçimdeki sonuç belgeye dönüştürür ve içeriğini belirtilen akışa kaydeder.

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| inputDocument | EditableDocument | WYSIWYG HTML editöründe düzenlenen ve '[`EditableDocument`](../../editabledocument)' sınıfının bir örneği olarak saklanan giriş belgesinin sürümü, belirli bir biçimdeki çıktı belgesine dönüştürülmelidir. Null olmamalı veya yok edilmemiş olmalıdır. |
| outputDocument | Stream | Sonuç belgesinin içeriğinin kaydedileceği çıktı akışı. Null olmamalı, yok edilmemiş olmalı ve yazma desteği sağlamalıdır. |
| saveOptions | ISaveOptions | Belge kaydetme seçenekleri, sonuç belgesinin biçimini ve ayrıca genel ve biçime özgü kaydetme seçeneklerini tanımlar. Null olmamalıdır. |

### Açıklamalar

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

Belirtilen düzenlenmiş belgeyi, '[`EditableDocument`](../../editabledocument)' örneği olarak temsil edilen belgeyi, belirtilen biçimdeki sonuç belgeye dönüştürür ve içeriğini belirtilen dosya yolu ile bir dosyaya kaydeder.

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| inputDocument | EditableDocument | WYSIWYG HTML editöründe düzenlenen ve '[`EditableDocument`](../../editabledocument)' sınıfının bir örneği olarak saklanan giriş belgesinin sürümü, belirli bir biçimdeki çıktı belgesine dönüştürülmelidir. Null olmamalı veya yok edilmemiş olmalıdır. |
| filePath | String | Çıktı belgesinin kaydedileceği dosyanın yolu. Aynı ada sahip bir dosya varsa tamamen üzerine yazılacaktır. Yol içeren dize null, boş olmamalı ve yalnızca boşluk karakterlerinden oluşmamalıdır. |
| saveOptions | ISaveOptions | Belge kaydetme seçenekleri, sonuç belgesinin biçimini ve ayrıca genel ve biçime özgü kaydetme seçeneklerini tanımlar. Null olmamalıdır. |

### Açıklamalar

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

Belirtilen düzenlenmiş belgeyi, '[`EditableDocument`](../../editabledocument)' örneği olarak temsil edilen, dosya adı uzantısına göre belirlenen formatta sonuç belgeye dönüştürür ve içeriğini belirtilen dosya yoluna kaydeder.

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| inputDocument | EditableDocument | WYSIWYG HTML editöründe düzenlenen ve '[`EditableDocument`](../../editabledocument)' sınıfının bir örneği olarak saklanan giriş belgesinin sürümü, belirli bir biçimdeki çıktı belgesine dönüştürülmelidir. Null olmamalı veya yok edilmemiş olmalıdır. |
| filePath | String | Çıktı belgesinin kaydedileceği dosyanın yolu. Aynı ada sahip bir dosya varsa, tamamen üzerine yazılacaktır. Yol içeren dize null, boş veya yalnızca boşluk karakteri içermemelidir. Varsayılan kaydetme seçenekleri ve çıktı formatı bu dosya adından belirlendiği için, geçerli bir uzantıya sahip olmalıdır. |

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

Orijinal belgeyi, değişiklikten (örneğin, [`FormFieldManager`](../formfieldmanager)) sonra, belirtilen formatta sonuç belgeye dönüştürür ve içeriğini sağlanan akışa kaydeder.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| outputDocument | Stream | Çıktı belgesinin kaydedileceği akış. Bu akış yazılabilir olmalı ve belge içeriğinin başlangıcında konumlandırılmalıdır. Null olmamalıdır. |
| saveOptions | WordProcessingSaveOptions | Sonuç belgenin formatını ve genel ile formata özgü kaydetme seçeneklerini tanımlayan belge kaydetme seçenekleri. Null olmamalıdır. |

### Dönüş Değeri

Kaydedilen belge içeriğini içeren akış.

### Açıklamalar

Eğer *outputDocument* veya *saveOptions* null ise, bir ArgumentNullException fırlatılacaktır. Kaydedilecek belge eksikse, bir ArgumentNullException fırlatılacaktır.

Eğer *outputDocument* veya *saveOptions* null ise veya kaydedilecek belge eksikse fırlatılır.**Daha fazla bilgi edinin:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Ayrıca Bakınız

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

Geçerli belge içeriğini belirtilen çıktı akışına kaydeder.

```csharp
public Stream Save(Stream outputDocument)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| outputDocument | Stream | Belge içeriğinin kaydedileceği akış. Bu null olamaz. |

### Dönüş Değeri

Kaydedilen belge içeriğine sahip akış.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *outputDocument* null olduğunda veya belge içeriği eksik olduğunda fırlatılır. |

### Açıklamalar

Bu yöntem, iç belge temsilinden içeriği sağlanan çıktı akışına kopyalar. Kaydetme işleminden sonra akışın orijinal konumu korunur.

### Ayrıca Bakınız

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
