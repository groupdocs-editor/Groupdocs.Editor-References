---
title: "SetMeteredKey"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Aktiverar produkten med Metered‑nycklar."
type: docs
weight: 20
url: /sv/net/groupdocs.editor/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Aktiverar produkten med Metered‑nycklar.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| publicKey | String | Den offentliga nyckeln. |
| privateKey | String | Den privata nyckeln. |

### Exempel

Följande exempel visar hur man aktiverar produkten med mätade nycklar.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Se även

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
