---
title: "Edit"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen format‑özel seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme amaçlı açar; bunun için HTML işaretlemesi ve ilgili kaynakları üreten yöntemleri içeren EditableDocumentgroupdocs.editor/editabledocument sınıfının bir örneğini oluşturur ve döndürür."
type: docs
weight: 60
url: /tr/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

Belirtilen format‑özel seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme amaçlı açar; bunun için HTML işaretlemesi ve ilgili kaynakları üreten yöntemleri içeren '[`EditableDocument`](../../editabledocument)' sınıfının bir örneğini oluşturur ve döndürür.

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| editOptions | IEditOptions | Biçime özgü belge seçenekleri, dönüşüm sürecini ayarlamaya olanak tanır. NULL olabilir — bu durumda GroupDocs.Editor daha önce yüklenmiş belgenin biçimini algılar ve bu biçim için varsayılan seçenekleri uygular. Daha önce uygulanmış yükleme seçenekleriyle çakışmamalıdır. |

### Dönüş Değeri

'[`EditableDocument`](../../editabledocument)' sınıfının bir örneği, giriş belgesini tüm kaynaklarıyla ara formatta kapsüller. Bu yöntem, başarılı bir şekilde tamamlandığında asla NULL döndürmez.

### Açıklamalar

'Editor' örneğine yapıcı üzerinden giriş orijinal belgesi yüklendiğinde, bu yöntem belgeyi ara formata dönüştürerek düzenleme için açmaya olanak tanır; ara format 'EditableDocument' sınıfının bir örneği içinde kapsüllenir. Bu yöntemden dönen '[`EditableDocument`](../../editabledocument)', HTML işaretlemesi ve ilgili kaynakları (görseller, yazı tipleri ve stil sayfaları gibi) üretmek için gerekli tüm yöntem ve özellikleri içerir ve bunların herhangi bir WYSIWYG HTML editörüne aktarılması için gereken tüm yapılandırmaları sağlar. Bu aşırı yükleme, aile biçimleri için özgü düzenleme seçeneklerini alır. **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

Varsayılan seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme için açar; bu işlem '[`EditableDocument`](../../editabledocument)' sınıfının bir örneğini oluşturur ve döndürür; bu örnek de HTML işaretlemesi ve ilişkili kaynakları üretmek için yöntemler içerir.

```csharp
public EditableDocument Edit()
```

### Dönüş Değeri

'[`EditableDocument`](../../editabledocument)' sınıfının bir örneği, giriş belgesini tüm kaynaklarıyla ara formatta kapsüller. Bu yöntem, başarılı bir şekilde tamamlandığında asla NULL döndürmez.

### Açıklamalar

'Editor' örneğine yapıcı üzerinden giriş orijinal belgesi yüklendiğinde, bu yöntem belgeyi ara formata dönüştürerek düzenleme için açmaya olanak tanır; ara format '[`EditableDocument`](../../editabledocument)' sınıfının bir örneği içinde kapsüllenir. Bu yöntemden dönen '[`EditableDocument`](../../editabledocument)', HTML işaretlemesi ve ilgili kaynakları (görseller, yazı tipleri ve stil sayfaları gibi) üretmek için gerekli tüm yöntem ve özellikleri içerir ve bunların herhangi bir WYSIWYG HTML editörüne aktarılması için gereken tüm yapılandırmaları sağlar. Bu aşırı yükleme, giriş belgesinin ait olduğu biçim için varsayılan düzenleme seçeneklerini uygular. **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
