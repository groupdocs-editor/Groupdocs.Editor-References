---
title: "SetLicense"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يرخص المكوّن."
type: docs
weight: 20
url: /ar/net/groupdocs.editor/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

يرخص المكوّن.

```csharp
public void SetLicense(Stream licenseStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseStream | Stream | دفق الترخيص. |

### أمثلة

المثال التالي يوضح كيفية تعيين ترخيص بتمرير Stream لملف الترخيص.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
    lic.SetLicense(licenseStream);
}
```

### انظر أيضًا

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## SetLicense(string) {#setlicense_1}

يرخص المكوّن.

```csharp
public void SetLicense(string licensePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| licensePath | String | مسار الترخيص. |

### أمثلة

المثال التالي يوضح كيفية تعيين ترخيص بتمرير مسار إلى ملف الترخيص.

```csharp
string licensePath = "GroupDocs.Editor.lic";
GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
lic.SetLicense(licensePath);
```

### انظر أيضًا

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
