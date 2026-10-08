---
title: "SetLicense"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Melisensikan komponen."
type: docs
weight: 20
url: /id/net/groupdocs.editor/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Melisensikan komponen.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseStream | Stream | Aliran lisensi. |

### Contoh

Contoh berikut menunjukkan cara mengatur lisensi dengan melewatkan Stream dari file lisensi.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
    lic.SetLicense(licenseStream);
}
```

### Lihat Juga

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## SetLicense(string) {#setlicense_1}

Melisensikan komponen.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licensePath | String | Jalur lisensi. |

### Contoh

Contoh berikut menunjukkan cara mengatur lisensi dengan melewatkan jalur ke file lisensi.

```csharp
string licensePath = "GroupDocs.Editor.lic";
GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
lic.SetLicense(licensePath);
```

### Lihat Juga

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
