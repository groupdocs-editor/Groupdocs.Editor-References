---
title: "SetLicense"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "घटक को लाइसेंस करता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.editor/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

घटक को लाइसेंस करता है।

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| licenseStream | Stream | लाइसेंस स्ट्रीम। |

### उदाहरण

निम्न उदाहरण दिखाता है कि लाइसेंस फ़ाइल की स्ट्रीम पास करके लाइसेंस कैसे सेट किया जाता है।

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
    lic.SetLicense(licenseStream);
}
```

### संबंधित देखें

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## SetLicense(string) {#setlicense_1}

घटक को लाइसेंस करता है।

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| licensePath | String | लाइसेंस पाथ। |

### उदाहरण

निम्न उदाहरण दिखाता है कि लाइसेंस फ़ाइल के पाथ को पास करके लाइसेंस कैसे सेट किया जाता है।

```csharp
string licensePath = "GroupDocs.Editor.lic";
GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
lic.SetLicense(licensePath);
```

### संबंधित देखें

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
