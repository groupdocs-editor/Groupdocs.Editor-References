---
title: "SetLicense"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Лицензирует компонент."
type: docs
weight: 20
url: /ru/net/groupdocs.editor/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Лицензирует компонент.

```csharp
public void SetLicense(Stream licenseStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseStream | Stream | Поток лицензии. |

### Примеры

В следующем примере показано, как установить лицензию, передавая Stream файла лицензии.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
    lic.SetLicense(licenseStream);
}
```

### См. также

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## SetLicense(string) {#setlicense_1}

Лицензирует компонент.

```csharp
public void SetLicense(string licensePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| licensePath | String | Путь к лицензии. |

### Примеры

В следующем примере показано, как установить лицензию, передавая путь к файлу лицензии.

```csharp
string licensePath = "GroupDocs.Editor.lic";
GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
lic.SetLicense(licensePath);
```

### См. также

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
