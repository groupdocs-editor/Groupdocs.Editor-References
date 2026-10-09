---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Format aileleri için ortak işlevsellik sağlayan temel sınıfı temsil eder."
type: docs
weight: 60
url: /tr/net/groupdocs.editor.formats.abstraction/formatfamilybase/
---
## FormatFamilyBase class

Format aileleri için temel sınıfı temsil eder ve format ailesi örnekleri için ortak işlevsellik sağlar.

```csharp
public abstract class FormatFamilyBase : IEquatable<FormatFamilyBase>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Format ailesinin benzersiz tanımlayıcısını alır. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Format ailesinin adını alır. |

## Methods

| Name | Açıklama |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals)(FormatFamilyBase) | Bu örneğin belirtilen [`FormatFamilyBase`](../formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals_1)(object) | Bu örneğin belirtilen [`FormatFamilyBase`](../formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Geçerli nesne için bir karma kod (hash code) döndürür. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |
| static [FromName&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromname)(string) | Belirtilen ada sahip belirtilen *T* tipinde bir örnek getirir. |
| static [FromValue&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue)(int) | Belirtilen tanımlayıcıya sahip belirtilen *T* tipinde bir örnek getirir. |
| static [GetAll&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/getall)() | Belirtilen *T* tipinde ve [`FormatFamilyBase`](../formatfamilybase) sınıfından türetilen tüm örnekleri getirir. |
| [operator ==](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_equality#op_equality) | İki [`FormatFamilyBase`](../formatfamilybase) örneğinin eşit olup olmadığını belirler. (2 operatör) |
| [explicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit#op_explicit_1) | Format ailesi adını temsil eden bir dizeyi bir [`FormatFamilyBase`](../formatfamilybase) nesnesine dönüştürür. (2 operatör) |
| [implicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_implicit#op_implicit) | Bir [`FormatFamilyBase`](../formatfamilybase) örneğini örtük olarak bir tam sayıya dönüştürür. (2 operatör) |
| [operator !=](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_inequality#op_inequality) | İki [`FormatFamilyBase`](../formatfamilybase) örneğinin eşit olmama durumunu belirler. (2 operatör) |

### Açıklamalar

Bu sınıf soyuttur ve gerçek format ailesi ayrıntılarını belirten türetilmiş bir sınıf tarafından miras alınmalıdır.

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
