---
title: "RecognizeLists"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belge düz metin formatından içe aktarıldığında numaralı liste öğelerinin nasıl tanınacağını belirtmeye izin verir. Varsayılan değer doğrudur (true)."
type: docs
weight: 60
url: /tr/net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

Belge düz metin formatından içe aktarıldığında numaralı liste öğelerinin nasıl tanınacağını belirtmeye izin verir. Varsayılan değer doğrudur (true).

```csharp
public bool RecognizeLists { get; set; }
```

### Açıklamalar

Bu seçenek false olarak ayarlanırsa, liste tanıma algoritması, liste numaraları nokta, sağ köşeli parantez veya madde işareti (örneğin "•", "*", "-" veya "o") ile bittiğinde liste paragraflarını algılar. Bu seçenek true olarak ayarlanırsa, boşluk karakterleri de liste numarası ayırıcıları olarak kullanılır: Arapça stil numaralandırma (1., 1.1.2.) için liste tanıma algoritması hem boşlukları hem de nokta (".") sembollerini kullanır.

### Ayrıca Bakınız

* class [TextEditOptions](../../texteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
