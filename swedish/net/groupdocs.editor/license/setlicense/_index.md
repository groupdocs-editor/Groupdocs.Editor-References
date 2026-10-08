---
title: "SetLicense"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Licensierar komponenten."
type: docs
weight: 20
url: /sv/net/groupdocs.editor/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licensierar komponenten.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| licenseStream | Stream | Licensströmmen. |

### Exempel

Följande exempel visar hur du anger en licens genom att skicka en Stream av licensfilen.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
    lic.SetLicense(licenseStream);
}
```

### Se även

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## SetLicense(string) {#setlicense_1}

Licensierar komponenten.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| licensePath | String | Licenssökvägen. |

### Exempel

Följande exempel visar hur du anger en licens genom att skicka en sökväg till licensfilen.

```csharp
string licensePath = "GroupDocs.Editor.lic";
GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
lic.SetLicense(licensePath);
```

### Se även

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
