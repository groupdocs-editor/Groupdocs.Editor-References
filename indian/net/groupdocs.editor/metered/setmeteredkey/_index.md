---
title: "SetMeteredKey"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "Metered कुंजियों के साथ उत्पाद को सक्रिय करता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.editor/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Metered कुंजियों के साथ उत्पाद को सक्रिय करता है।

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| publicKey | String | सार्वजनिक कुंजी। |
| privateKey | String | निजी कुंजी। |

### उदाहरण

निम्न उदाहरण दर्शाता है कि मीटरड कुंजियों के साथ उत्पाद को कैसे सक्रिय किया जाए।

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### संबंधित देखें

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
