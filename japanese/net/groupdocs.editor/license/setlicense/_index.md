---
title: "SetLicense"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "コンポーネントにライセンスを付与します。"
type: docs
weight: 20
url: /ja/net/groupdocs.editor/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(Stream licenseStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| licenseStream | Stream | ライセンス ストリームです。 |

### 例

次の例は、ライセンス ファイルの Stream を渡してライセンスを設定する方法を示しています。

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
    lic.SetLicense(licenseStream);
}
```

### 参照

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## SetLicense(string) {#setlicense_1}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(string licensePath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| licensePath | 文字列 | ライセンス パスです。 |

### 例

次の例は、ライセンス ファイルへのパスを渡してライセンスを設定する方法を示しています。

```csharp
string licensePath = "GroupDocs.Editor.lic";
GroupDocs.Editor.License lic = new GroupDocs.Editor.License();
lic.SetLicense(licensePath);
```

### 参照

* class [License](../../license)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
