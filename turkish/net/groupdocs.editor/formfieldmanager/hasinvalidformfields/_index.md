---
title: "HasInvalidFormFields"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belgenin herhangi bir geçersiz form alanı içerip içermediğini kontrol eder."
type: docs
weight: 40
url: /tr/net/groupdocs.editor/formfieldmanager/hasinvalidformfields/
---
## FormFieldManager.HasInvalidFormFields method

Belgenin herhangi bir geçersiz form alanı içerip içermediğini kontrol eder.

```csharp
public bool HasInvalidFormFields()
```

### Dönüş Değeri

`true` belge bir veya daha fazla geçersiz form alanı içeriyorsa; aksi takdirde `false`.

### Açıklamalar

Bu `HasInvalidFormFields` yöntemi, belge içeriğini tarayarak geçersiz adlara sahip form alanları içerip içermediğini belirler. Bir form alanı, diğer form alanlarıyla benzersiz bir tanımlayıcıyı tekrarlıyorsa ve ona bağlı benzersiz bir yer imi adı yoksa geçersiz kabul edilir. Bu yer imi adları her form alanı için tanımlayıcı görevi görür. Bu yöntem, belgenin daha fazla incelenmesi ve form alanı adlarının olası düzeltilmesi gerekip gerekmediğini hızlı bir şekilde kontrol etmek için kullanışlıdır. ; ; ;

### Ayrıca Bakınız

* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
