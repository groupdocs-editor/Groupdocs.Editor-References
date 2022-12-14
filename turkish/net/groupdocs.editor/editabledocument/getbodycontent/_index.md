---
title: GetBodyContent
second_title: .NET API Başvurusu için GroupDocs.Editor
description: HTML belgesinin gövdesini bu etiketler olmadan BODY etiketlerinin açılması ve kapatılması arasındaki içerik bir dize olarak döndürür.
type: docs
weight: 120
url: /tr/net/groupdocs.editor/editabledocument/getbodycontent/
---
## GetBodyContent() {#getbodycontent}

HTML belgesinin gövdesini (bu etiketler olmadan BODY etiketlerinin açılması ve kapatılması arasındaki içerik) bir dize olarak döndürür.

```csharp
public string GetBodyContent()
```

### Geri dönüş değeri

HTML belgesinin gövdesini içeren dize

### Notlar

WYSIWYG editörleri, belgenin gövdesiyle birlikte çalışır ve HEAD bloğundaki meta bilgilerini doğru bir şekilde işleyemez. Bu yöntem, bu tür durumlar için tasarlanmıştır. Bu aşırı yükleme, harici kaynak istekleri için URI'lerin ayarlanmasına izin vermiyor.

### Ayrıca bakınız

* class [EditableDocument](../../editabledocument)
* ad alanı [GroupDocs.Editor](../../editabledocument)
* toplantı [GroupDocs.Editor](../../../)

---

## GetBodyContent(string) {#getbodycontent_1}

HTML belgesinin bir gövdesini (bu etiketler olmadan BODY etiketlerinin açılması ve kapatılması arasındaki içerik) bir dize, olarak döndürür; burada harici kaynaklara bağlantılar belirtilen öneki içerir.

```csharp
public string GetBodyContent(string externalImagesPrefix)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| externalImagesPrefix | String | Kullanılan bu parametre aracılığıyla, elde edilen HTML dizisinde bulunacak olan IMG öğelerindeki tüm harici görüntülere links 'ye eklenecek bir önek belirtilebilir. NULL veya boş ise önekler eklenmez. |

### Geri dönüş değeri

Bağlantılarla birlikte HTML belgesinin gövdesini içeren dize, harici görüntülere göre ayarlanmış

### Notlar

WYSIWYG editörleri, belgenin gövdesiyle birlikte çalışır ve HEAD bloğundaki meta bilgilerini doğru bir şekilde işleyemez. Bu yöntem, bu tür durumlar için tasarlanmıştır. Bu aşırı yükleme, harici kaynak istekleri için URI'lerin ayarlanmasına izin verir.

### Ayrıca bakınız

* class [EditableDocument](../../editabledocument)
* ad alanı [GroupDocs.Editor](../../editabledocument)
* toplantı [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
