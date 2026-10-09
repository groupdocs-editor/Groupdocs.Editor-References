---
title: "FormFieldManager"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Legacy Form Alanlarıyla bir Form yönetin. Legacy form alanları, Word işlemcinin önceki sürümlerinde mevcut olan alan türleridir. Legacy Tools simgesine tıkladığınızda görünen Legacy Forms grubu, bir belgeye ekleyebileceğiniz üç tür form alanı içerir: metin, onay kutusu, açılır menü, tarih vb. daha fazla bilgi için FormFieldType../groupdocs.editor.words.fieldmanagement/formfieldtype adresine bakın. Bu form alanlarının her biri, form kullanıcısının uygun gördüğünüz türde bilgi seçmesine veya girmesine olanak tanır."
type: docs
weight: 40
url: /tr/net/groupdocs.editor/formfieldmanager/
---
## FormFieldManager class

Legacy Form Alanlarıyla bir Form yönetin. Legacy form alanları, Word işlemcinin önceki sürümlerinde mevcut olan alan türleridir. Legacy Tools simgesine tıkladığınızda görünen Legacy Forms grubu, bir belgeye ekleyebileceğiniz üç tür form alanı içerir: metin, onay kutusu, açılır menü, tarih vb., daha fazla bilgi için [`FormFieldType`](../../groupdocs.editor.words.fieldmanagement/formfieldtype) adresine bakın. Bu form alanlarının her biri, form kullanıcısının uygun gördüğünüz türde bilgi seçmesine veya girmesine olanak tanır.

```csharp
public sealed class FormFieldManager
```

## Properties

| Name | Açıklama |
| --- | --- |
| [FormFieldCollection](../../groupdocs.editor/formfieldmanager/formfieldcollection) { get; } | Belgedeki form alanları koleksiyonunu alır. |

## Methods

| Name | Açıklama |
| --- | --- |
| [FixInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/fixinvalidformfieldnames)(IEnumerable&lt;InvalidFormField&gt;) | Belgedeki geçersiz form alanı adlarını belirtilen güncellemeleri uygulayarak veya otomatik olarak benzersiz adlar üreterek düzeltir. |
| [GetInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/getinvalidformfieldnames)() | Belgeden geçersiz form alanı adlarının bir koleksiyonunu alır. |
| [HasInvalidFormFields](../../groupdocs.editor/formfieldmanager/hasinvalidformfields)() | Belgenin herhangi bir geçersiz form alanı içerip içermediğini kontrol eder. |
| [RemoveFormFields](../../groupdocs.editor/formfieldmanager/removeformfields)(IEnumerable&lt;IFormField&gt;) | Belgeden birden fazla form alanını kaldırır. |
| [RemoveFormFiled](../../groupdocs.editor/formfieldmanager/removeformfiled)(IFormField) | Belgeden belirli bir form alanını kaldırır. |
| [UpdateFormFiled](../../groupdocs.editor/formfieldmanager/updateformfiled)(FormFieldCollection) | Belgedeki form alanlarını sağlanan form alanları koleksiyonuna göre günceller. |

### Açıklamalar

Bu [`FormFieldManager`](../formfieldmanager) sınıfı, bir belgede form alanlarını yönetmek için işlevsellik sağlar. Kullanıcıların form alanlarını elde etmesine, güncellemesine, düzeltmesine, geçersizliğini kontrol etmesine ve belge üzerinden kaldırmasına olanak tanır.

### Ayrıca Bakınız

* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
