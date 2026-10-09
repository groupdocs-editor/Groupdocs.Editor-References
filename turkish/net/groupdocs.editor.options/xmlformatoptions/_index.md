---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "XML belgesinin HTML olarak temsil edildiğinde biçimlendirmesini ayarlamaya izin veren seçenekleri içerir"
type: docs
weight: 1280
url: /tr/net/groupdocs.editor.options/xmlformatoptions/
---
## XmlFormatOptions class

XML belgesi HTML olarak temsil edildiğinde biçimlendirmeyi ayarlamaya izin veren seçenekler içerir

```csharp
public sealed class XmlFormatOptions : IEditOptions
```

## Properties

| Name | Açıklama |
| --- | --- |
| [EachAttributeFromNewline](../../groupdocs.editor.options/xmlformatoptions/eachattributefromnewline) { get; set; } | Etkinleştirildiğinde, her XML öğesindeki her bir nitelik-değer çifti yeni bir satıra yerleştirilecektir. Varsayılan olarak yanlıştır (devre dışı) — tüm nitelik-değer çiftleri tek bir satıra yerleştirilir. |
| [IsDefault](../../groupdocs.editor.options/xmlformatoptions/isdefault) { get; } | Bu XML biçimlendirme seçenekleri örneğinin varsayılan bir değere sahip olup olmadığını gösterir |
| [LeafTextNodesOnNewline](../../groupdocs.editor.options/xmlformatoptions/leaftextnodesonnewline) { get; set; } | Etkinleştirildiğinde, yaprak metin düğümleri (çocukları olmayan XML öğeleri içindeki metin içeriği) daha büyük sol girinti ile yeni bir satıra yerleştirilecektir. Varsayılan olarak yanlıştır (devre dışı) — yaprak metin düğümleri ebeveynleriyle aynı satıra, yeni girinti olmadan yerleştirilir. |
| [LeftIndent](../../groupdocs.editor.options/xmlformatoptions/leftindent) { get; set; } | Her yeni satırın sol girintisi için bir kaydırma değeri belirtmeye izin verir. Birimsiz sıfır olmayan bir değer olamaz. Varsayılan olarak 10pt'dir. |

### Ayrıca Bakınız

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
