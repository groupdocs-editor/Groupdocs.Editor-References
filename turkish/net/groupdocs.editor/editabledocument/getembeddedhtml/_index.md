---
title: "GetEmbeddedHtml"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bu HTML belgesinin tüm içeriğini ve ilgili tüm kaynakları, tüm kaynakların HTML işaretlemesi içinde base64 kodlu olarak gömülü olduğu tek bir dize şeklinde döndürür."
type: docs
weight: 150
url: /tr/net/groupdocs.editor/editabledocument/getembeddedhtml/
---
## EditableDocument.GetEmbeddedHtml method

Bu HTML belgesinin tüm içeriğini ve ilgili tüm kaynakları tek bir dize olarak döndürür; tüm kaynaklar HTML işaretlemesi içinde base64 kodlu olarak gömülüdür.

```csharp
public string GetEmbeddedHtml()
```

### Dönüş Değeri

Her durumda NULL veya boş olmayan dize.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ObjectDisposedException | Bu EditableDocument örneği zaten çözüldü |

### Açıklamalar

Bu yöntem bu EditableDocument'i HTML'e dönüştürür ve tüm kaynakların HTML işaretlemesiyle birlikte dizeye gömüldüğü tek bir dizeye serileştirir:

* All images from HTML-&gt;BODY are converted to base64 format and are located in the IMG 'src' attribute
* All stylesheets are stored in the STYLE elements inside HTML-&gt;HEAD sections
* All images from stylesheets are converted to base64 format and located in the appropriate CSS declarations
* All fonts from stylesheets are converted to base64 format and located in the appropriate @font-face at-rules

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
