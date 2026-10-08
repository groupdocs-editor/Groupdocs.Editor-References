---
title: "SetLicense"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Licencia el componente."
type: docs
weight: 20
url: /es/net/groupdocs.editor/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licencia el componente.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| licenseStream | Stream | El flujo de la licencia. |

### Ejemplos

El siguiente ejemplo muestra cómo establecer una licencia pasando el Stream del archivo de licencia.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
    lic.SetLicense(licenseStream);
}
```

### Ver también

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## SetLicense(string) {#setlicense_1}

Licencia el componente.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| licensePath | String | La ruta de la licencia. |

### Ejemplos

El siguiente ejemplo muestra cómo establecer una licencia pasando una ruta al archivo de licencia.

```csharp
string licensePath = "GroupDocs.Editor.lic";
GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
lic.SetLicense(licensePath);
```

### Ver también

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
