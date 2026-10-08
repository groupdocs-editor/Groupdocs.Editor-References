---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "消費されたクレジット数を取得します。"
type: docs
weight: 30
url: /ja/net/groupdocs.editor/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

消費されたクレジット数を取得します。

```csharp
public static decimal GetConsumptionCredit()
```

### 戻り値

既に使用されたクレジットの数

### 例

以下の例は、消費されたクレジットの数を取得する方法を示しています。

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### 参照

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
