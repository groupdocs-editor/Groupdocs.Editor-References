---
title: "GroupDocs.Editor"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "GroupDocs.Editor ad alanı, ek bir uygulama gerektirmeden üçüncü taraf ön uç WYSIWYG editörlerini kullanarak belgeleri düzenlemek için sınıflar sağlar."
type: docs
weight: 10
url: /tr/net/groupdocs.editor/
---
GroupDocs.Editor namespace'i, ek bir uygulama gerektirmeden 3. taraf ön uç WYSIWYG editörleri kullanarak belgeleri düzenlemek için sınıflar sağlar.

## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [EditableDocument](./editabledocument) | Düzenlemeden önce ve sonra içeriği içeren ara belge |
| [Editor](./editor) | Tüm dönüştürme yöntemlerini kapsayan ana sınıf. Editor sınıfı, tüm desteklenen formatlardaki belgeleri yükleme, düzenleme ve kaydetme yöntemleri sağlar. Bu sınıf kullanılabilir, bu yüzden bir 'using' yönergesi kullanın veya kaynaklarını manuel olarak 'Dispose()' yöntemiyle serbest bırakın. Belge yükleme, yapıcılar aracılığıyla gerçekleştirilir. Belge düzenleme – 'Edit' yöntemiyle, düzenleme sonrası ortaya çıkan belgeyi kaydetme ise 'Save' yöntemiyle yapılır. |
| [EncryptedException](./encryptedexception) | Kullanıcı, X509Certificates kullanılarak şifrelenmiş bir belgeyi açmaya çalıştığında fırlatılan istisna. |
| [FormFieldManager](./formfieldmanager) | Eski Form Alanlarıyla bir Form yönetin. Eski form alanları, Word işlemcinin önceki sürümlerinde mevcut olan alan türleridir. Legacy Tools simgesine tıkladıktan sonra görünen Legacy Forms grubu, bir belgeye ekleyebileceğiniz üç tür form alanını içerir: metin, onay kutusu, açılır liste, tarih vb., daha fazla bilgi için [`FormFieldType`](../groupdocs.editor.words.fieldmanagement/formfieldtype) bağlantısına bakın. Bu form alanlarının her biri, form kullanıcısının uygun gördüğü türde bilgi seçmesine veya girmesine olanak tanır. |
| [IncorrectPasswordException](./incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda fırlatılan istisna. |
| [InvalidFormatException](./invalidformatexception) | Kullanıcı, orijinal belge formatıyla uyumsuz format‑özel seçeneklere sahip bir belgeyi açmaya çalıştığında fırlatılan istisna. |
| [License](./license) | Bileşeni lisanslamak için yöntemler sağlar. Lisanslama hakkında daha fazla bilgiyi [burada](https://purchase.groupdocs.com/faqs/licensing) öğrenin. |
| [Metered](./metered) | [Metered](https://purchase.groupdocs.com/faqs/licensing/metered) lisansını uygulamak için yöntemler sağlar. |
| [PasswordRequiredException](./passwordrequiredexception) | Kullanıcı, bir formatta parola korumalı şifreli bir belgeyi açmaya çalıştığında ve bu belgeyi açmak için parola sağlamadığında fırlatılan istisna. |

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
