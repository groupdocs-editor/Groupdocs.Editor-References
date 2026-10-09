---
title: "IDocumentInfo"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Tüm dosya meta veri sarmalayıcıları için ortak arayüz"
type: docs
weight: 740
url: /tr/net/groupdocs.editor.metadata/idocumentinfo/
---
## IDocumentInfo interface

Tüm dosya meta veri sarmalayıcıları için ortak arayüz

```csharp
public interface IDocumentInfo
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/idocumentinfo/format) { get; } | Uygulayan tip, bir format ailesini temsil eden ve IDocumentFormat arabiriminden türetilen bir tipten tek bir değer olarak belge formatını döndürmelidir |
| [IsEncrypted](../../groupdocs.editor.metadata/idocumentinfo/isencrypted) { get; } | Belirli dosyanın şifrelenip şifrelenmediğini ve açmak için parola gerekip gerekmediğini gösterir. Şifrelenemeyen belge türleri (tüm metin tabanlı olanlar gibi) her zaman 'false' döndürmelidir. |
| [PageCount](../../groupdocs.editor.metadata/idocumentinfo/pagecount) { get; } | Uygulayan tip, sayfa sayısı veya benzeri format bağımlı varlıkların (sekme, slayt vb.) sayısını döndürmelidir. Benzer bir şey olmayan aile tipleri (düz metin belgeleri veya XML gibi) 1 döndürmelidir. |
| [Size](../../groupdocs.editor.metadata/idocumentinfo/size) { get; } | Belge boyutu bayt cinsinden |

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
