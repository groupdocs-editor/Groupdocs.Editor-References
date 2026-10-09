---
title: "SetLicense"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bileşeni lisanslar."
type: docs
weight: 20
url: /tr/net/groupdocs.editor/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Bileşeni lisanslar.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| licenseStream | Stream | Lisans akışı. |

### Örnekler

Aşağıdaki örnek, lisans dosyasının Stream'ini geçirerek bir lisansın nasıl ayarlanacağını gösterir.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
    lic.SetLicense(licenseStream);
}
```

### Ayrıca Bakınız

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## SetLicense(string) {#setlicense_1}

Bileşeni lisanslar.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| licensePath | String | Lisans yolu. |

### Örnekler

Aşağıdaki örnek, lisans dosyasının yolunu geçirerek bir lisansın nasıl ayarlanacağını gösterir.

```csharp
string licensePath = "GroupDocs.Editor.lic";
GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
lic.SetLicense(licensePath);
```

### Ayrıca Bakınız

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
