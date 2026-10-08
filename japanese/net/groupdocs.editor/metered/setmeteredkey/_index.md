---
title: "SetMeteredKey"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "Metered キーで製品を有効化します。"
type: docs
weight: 20
url: /ja/net/groupdocs.editor/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Metered キーで製品を有効化します。

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| publicKey | 文字列 | 公開鍵です。 |
| privateKey | 文字列 | 秘密鍵です。 |

### 例

以下の例は、Metered キーを使用して製品を有効化する方法を示しています。

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### 参照

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
