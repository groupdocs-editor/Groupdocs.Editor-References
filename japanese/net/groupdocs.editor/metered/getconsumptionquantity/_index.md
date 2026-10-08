---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "処理された MB の量を取得します。"
type: docs
weight: 40
url: /ja/net/groupdocs.editor/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

処理された MB の量を取得します。

```csharp
public static decimal GetConsumptionQuantity()
```

### 例

以下の例は、処理された MB の量を取得する方法を示しています。

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### 参照

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
