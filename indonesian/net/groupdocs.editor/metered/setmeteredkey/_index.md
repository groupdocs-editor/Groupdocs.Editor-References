---
title: "SetMeteredKey"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengaktifkan produk dengan kunci Metered."
type: docs
weight: 20
url: /id/net/groupdocs.editor/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Mengaktifkan produk dengan kunci Metered.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| publicKey | String | Kunci publik. |
| privateKey | String | Kunci pribadi. |

### Contoh

Contoh berikut menunjukkan cara mengaktifkan produk dengan kunci Metered.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Lihat Juga

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
