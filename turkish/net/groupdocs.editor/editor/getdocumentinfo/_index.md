---
title: "GetDocumentInfo"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bu Editor örneğine yüklenen belge hakkında meta verileri döndürür."
type: docs
weight: 70
url: /tr/net/groupdocs.editor/editor/getdocumentinfo/
---
## Editor.GetDocumentInfo method

Bu 'Editor' örneğine yüklenen belgeye ait meta verileri döndürür.

```csharp
public IDocumentInfo GetDocumentInfo(string password)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| password | String | Kullanıcı, belge şifrelenmişse belge için bir şifre belirtebilir. NULL veya boş dize olabilir; bu, şifrenin yokluğu ile eşdeğerdir. Şifre koruması özelliği olmayan belge formatları için bu argüman göz ardı edilir. Belge şifrelenmişse ve bu parametrede şifre belirtilmemişse, ancak bu [`Editor`](../../editor) örneği oluşturulurken yükleme seçeneklerinde daha önce belirtilmişse, o şifre kullanılacaktır. |

### Dönüş Değeri

[`IDocumentInfo`](../../../groupdocs.editor.metadata/idocumentinfo) arayüzünün format‑özel türevi, tespit edilen formatı format‑özel meta verilerle gösterir; belge desteklenebilir olarak tanımlanamazsa veya bozuksa NULL döner.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ObjectDisposedException | Editor örneği zaten atıldıysa ve "GetDocumentInfo" çağrıldığında fırlatılır. |
| [PasswordRequiredException](../../passwordrequiredexception) | Yüklenen belge şifre korumalıysa, ancak şifre "*password*" parametresinde ve örnek oluşturulurken yükleme seçeneklerinde belirtilmemişse fırlatılır. |
| [IncorrectPasswordException](../../incorrectpasswordexception) | Yüklenen belge şifre korumalıysa, şifre belirtilmiş ancak yanlışsa fırlatılır. |
| InvalidOperationException | Bilinmeyen bir doğadaki beklenmeyen bir hata oluştuğunda fırlatılır. |

### Açıklamalar

GetDocumentInfo yöntemi, giriş belgesinin hangi formatta olduğu, şifre korumalı olup olmadığı ve/veya kaç sayfa/çalışma sayfası/slayt içerdiği belli olmadığında faydalıdır. GetDocumentInfo tarafından döndürülen bu meta verilere dayanarak, ana işleme hattı için yükleme ve düzenleme seçenekleri doğru şekilde ayarlanabilir.

GetDocumentInfo yöntemi her zaman tam veri döndürür, deneme modundan etkilenmez; kullanımı tüketilen baytları veya kredileri harcamaz.

**Learn more**

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Extracting+document+metainfo)

### Ayrıca Bakınız

* interface [IDocumentInfo](../../../groupdocs.editor.metadata/idocumentinfo)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
