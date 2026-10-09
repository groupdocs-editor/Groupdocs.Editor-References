---
title: "Parola"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Şifreli bir Presentation belgesi açmak için kullanılacak şifreyi belirtmeye, değiştirmeye ve almaya olanak tanır. Şifreyi kaldırmak için NULL veya boş bir dize ayarlayın."
type: docs
weight: 20
url: /tr/net/groupdocs.editor.options/presentationloadoptions/password/
---
## PresentationLoadOptions.Password property

Şifreyi belirtmenizi, değiştirmenizi ve almanızı sağlar; bu şifre, Presentation belgesi şifrelenmişse açmak için kullanılır. Şifreyi kaldırmak için NULL veya boş dize olarak ayarlayın.

```csharp
public string Password { get; set; }
```

### Açıklamalar

Varsayılan olarak bu özelliğin değeri NULL'dır — şifre ayarlanmamıştır. Giriş Presentation belgesi şifre korumalıysa, şifre zorunludur ve şifre belirtilmezse veya geçersizse bir istisna fırlatılır. Giriş Presentation belgesi şifre korumalı DEĞİLSE ancak şifre ayarlanmışsa, şifre yoksayılır.

### Ayrıca Bakınız

* class [PresentationLoadOptions](../../presentationloadoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
