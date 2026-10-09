---
title: "GetHashCode"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Geçerli nesne için bir karma kod (hash code) döndürür."
type: docs
weight: 40
url: /tr/net/groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode/
---
## FormatFamilyBase.GetHashCode method

Geçerli nesne için bir karma kod (hash code) döndürür.

```csharp
public override int GetHashCode()
```

### Dönüş Değeri

Mevcut nesne için bir karma kodu, karma algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.

### Açıklamalar

Bu yöntem GetHashCode metodunu geçersiz kılar. Karma kodu, nesnenin `Id` ve `Name` özellikleri kullanılarak hesaplanır. `unchecked` bağlamı taşmayı izin verir; bu, bir karma kodu hesaplama bağlamında kabul edilebilir.

### Ayrıca Bakınız

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
