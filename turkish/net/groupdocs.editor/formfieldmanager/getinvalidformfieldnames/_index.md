---
title: "GetInvalidFormFieldNames"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belgeden geçersiz form alanı adlarının bir koleksiyonunu alır."
type: docs
weight: 30
url: /tr/net/groupdocs.editor/formfieldmanager/getinvalidformfieldnames/
---
## FormFieldManager.GetInvalidFormFieldNames method

Belgeden geçersiz form alanı adlarının bir koleksiyonunu alır.

```csharp
public IEnumerable<InvalidFormField> GetInvalidFormFieldNames()
```

### Dönüş Değeri

Belgede bulunan geçersiz form alanı adlarını temsil eden dizelerden oluşan bir yinelenebilir koleksiyon.

### Açıklamalar

Bu `GetInvalidFormFieldNames` yöntemi, belge içeriğini tarayarak geçersiz adlara sahip form alanlarını belirler. Bu yöntem, bu geçersiz form alanlarının adlarını içeren bir dize koleksiyonu döndürür. Bir form alanı, diğer form alanlarıyla benzersiz bir tanımlayıcıyı tekrarlıyorsa ve ona bağlı benzersiz bir yer imi adı yoksa geçersiz kabul edilir. Bu yer imi adları her form alanı için tanımlayıcı görevi görür. Döndürülen koleksiyon, form alanı adlarının belgede göründükleri sırayı korur. Bu yöntem, form alanları içindeki adlandırma sorunlarını tespit etmek ve analiz etmek için kullanışlıdır; bu sorunlar, [`FixInvalidFormFieldNames`](../fixinvalidformfieldnames) yöntemi kullanılarak ele alınabilir.

### Ayrıca Bakınız

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
