---
title: "GetBodyContent"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Açılış ve kapanış BODY etiketleri arasındaki HTML belgesinin içeriğinin gövdesini bu etiketler olmadan bir dize olarak döndürür."
type: docs
weight: 120
url: /tr/net/groupdocs.editor/editabledocument/getbodycontent/
---
## GetBodyContent() {#getbodycontent}

HTML belgesinin gövdesini (açılış ve kapanış BODY etiketleri arasındaki içeriği, etiketler olmadan) bir dize olarak döndürür.

```csharp
public string GetBodyContent()
```

### Dönüş Değeri

Açılış ve kapanış BODY etiketleri olmadan HTML belgesinin gövdesini içeren String

### Açıklamalar

Çoğu WYSIWYG editörü genellikle belgenin BODY içeriğiyle çalışır ve HEAD bloğundaki meta bilgilerini doğru şekilde işleyemez. Bu yöntem bu tür durumlar için tasarlanmıştır. Bu aşırı yükleme, harici kaynak istekleri için URI'leri ayarlamaya izin vermez.

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetBodyContent(string) {#getbodycontent_1}

HTML belgesinin gövdesini (açılış ve kapanış BODY etiketleri arasındaki içeriği, etiketler olmadan) bir dize olarak döndürür; dış kaynaklara bağlantılar belirtilen yer tutucularla şablonu içerir.

```csharp
public string GetBodyContent(string externalImagesTemplate)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| externalImagesTemplate | String | Bu parametre aracılığıyla, sonuç HTML dizesinde bulunacak IMG öğelerindeki tüm harici görüntülere uygulanacak bir yer tutucu içeren bir dize şablonu belirtebilirsiniz. NULL veya boş ise şablon eklenmez ve saf dosya adları sonuç HTML işaretlemesinde yer alır. Şablon geçersiz ise, bir önek olarak kabul edilir, böylece dosya adları onun sonuna eklenir. |

### Dönüş Değeri

Açılış ve kapanış BODY etiketleri olmadan HTML belgesinin gövdesini, harici görüntülere göre ayarlanmış bağlantılarla içeren String

### Açıklamalar

Çoğu WYSIWYG editörü genellikle belgenin BODY içeriğiyle çalışır ve HEAD bloğundaki meta bilgilerini doğru şekilde işleyemez. Bu yöntem bu tür durumlar için tasarlanmıştır. Bu aşırı yükleme, harici kaynak istekleri için URI'leri ayarlamaya izin verir.

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
