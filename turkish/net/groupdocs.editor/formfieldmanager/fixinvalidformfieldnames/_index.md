---
title: "FixInvalidFormFieldNames"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belgedeki geçersiz form alanı adlarını belirtilen güncellemeleri uygulayarak veya otomatik olarak benzersiz adlar üreterek düzeltir."
type: docs
weight: 20
url: /tr/net/groupdocs.editor/formfieldmanager/fixinvalidformfieldnames/
---
## FormFieldManager.FixInvalidFormFieldNames method

Belgedeki geçersiz form alanı adlarını belirtilen güncellemeleri uygulayarak veya otomatik olarak benzersiz adlar üreterek düzeltir.

```csharp
public void FixInvalidFormFieldNames(IEnumerable<InvalidFormField> updateInvalidFormFieldNames)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| updateInvalidFormFieldNames | IEnumerable`1 | Geçersiz form alanı adları için bir güncelleme koleksiyonu. Her güncelleme, form alanının orijinal adını ve karşılık gelen yeni adını içerir. Boş bırakılırsa, geçersiz form alanı adları benzersizliği sağlamak için otomatik olarak yeniden adlandırılır. |

### Açıklamalar

Bu `FixInvalidFormFieldNames` yöntemi, *updateInvalidFormFieldNames* koleksiyonunda belirtilen güncellemeleri uygulayarak belge içindeki form alanları arasındaki ad çakışmalarını veya tutarsızlıkları çözer; koleksiyon boşsa benzersiz adlar otomatik olarak oluşturulur. Belirli form alanı adları geçersiz olduğunda veya belgede diğer öğelerle çakıştığında, doğru işlevselliği sağlamak için düzeltilmesi gerektiğinde bu yöntem kullanışlıdır. ; ;

### Ayrıca Bakınız

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
