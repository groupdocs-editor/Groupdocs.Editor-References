---
title: "SetLicense"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Licence le composant."
type: docs
weight: 20
url: /fr/net/groupdocs.editor/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licence le composant.

```csharp
public void SetLicense(Stream licenseStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| licenseStream | Stream | Le flux de licence. |

### Exemples

L'exemple suivant montre comment définir une licence en passant le Stream du fichier de licence.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
    lic.SetLicense(licenseStream);
}
```

### Voir aussi

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## SetLicense(string) {#setlicense_1}

Licence le composant.

```csharp
public void SetLicense(string licensePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| licensePath | String | Le chemin de la licence. |

### Exemples

L'exemple suivant montre comment définir une licence en passant un chemin vers le fichier de licence.

```csharp
string licensePath = "GroupDocs.Editor.lic";
GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
lic.SetLicense(licensePath);
```

### Voir aussi

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
