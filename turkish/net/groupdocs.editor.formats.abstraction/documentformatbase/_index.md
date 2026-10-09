---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belge formatları için ortak işlevsellik sağlayan temel sınıfı temsil eder."
type: docs
weight: 50
url: /tr/net/groupdocs.editor.formats.abstraction/documentformatbase/
---
## DocumentFormatBase class

Belge formatları için temel sınıfı temsil eder ve format örnekleri için ortak işlevsellik sağlar.

```csharp
public abstract class DocumentFormatBase : FormatFamilyBase, IDocumentFormat
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Belge formatının dosya uzantısını alır. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Belge formatının ait olduğu format ailesini alır. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Format ailesinin benzersiz tanımlayıcısını alır. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Belge formatının MIME tipini alır. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Format ailesinin adını alır. |

## Methods

| Name | Açıklama |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bu örneğin belirtilen [`FormatFamilyBase`](../formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_1)(IDocumentFormat) | Bu örneğin belirtilen [`IDocumentFormat`](../idocumentformat) örneğiyle eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_2)(object) | Bu örneğin belirtilen [`DocumentFormatBase`](../documentformatbase) örneğiyle eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Geçerli nesne için bir karma kod (hash code) döndürür. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |
| static [FromMime&lt;T&gt;](../../groupdocs.editor.formats.abstraction/documentformatbase/frommime)(string) | Belirtilen MIME tipine sahip belirtilen *T* tipinde bir örnek getirir. |
| [implicit operator](../../groupdocs.editor.formats.abstraction/documentformatbase/op_implicit) | Bir [`DocumentFormatBase`](../documentformatbase) örneğini örtük olarak bir dizeye dönüştürür. |

### Ayrıca Bakınız

* class [FormatFamilyBase](../formatfamilybase)
* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
