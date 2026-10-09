---
title: "SetMeteredKey"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Metered anahtarlarıyla ürünü etkinleştirir."
type: docs
weight: 20
url: /tr/net/groupdocs.editor/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Metered anahtarlarıyla ürünü etkinleştirir.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| publicKey | String | Genel anahtar. |
| privateKey | String | Özel anahtar. |

### Örnekler

Aşağıdaki örnek, Ölçümlü anahtarlarla ürünü nasıl etkinleştireceğinizi gösterir.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Ayrıca Bakınız

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
